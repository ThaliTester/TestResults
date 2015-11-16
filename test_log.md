#### Test 495261844451736 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":18,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_495261844451736/Sub/serverApp/index.js',
  '{"devices":{"android":18}}' ]

JSON { devices: { android: 18 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
Warning: Phone 30049d9501da2100	offline OFFLINE
Error: problem deploying Android apk(/home/pi/test/builder/builds/495261844451736/build_android/android_0_495261844451736.apk) to device f56ad48d protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_495261844451736.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

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
I/ActivityManager(  952): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4032 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 3836:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
I/ActivityManager(  952): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4054 uid=10062 gids={50062, 9997} abi=armeabi-v7a
I/ActivityManager(  952): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=4072 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  952): Killing 3853:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/ActivityManager(  952): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4092 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  952): Killing 3532:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/ActivityManager(  952): Killing 3225:com.android.settings/1000 (adj 15): empty #11
I/ActivityManager(  952): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  952): setTaskToReturnTo : TaskRecord{173df49d #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  952): setTaskToReturnTo : TaskRecord{173df49d #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  952): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4123 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  952): getTasks: caller 10074 does not hold GET_TASKS; limiting output
I/ActivityManager(  952): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4140 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  952): Process com.lge.defaultaccount (pid 4054) has died
,I/ActivityManager(  952): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4164 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  952): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4192 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  952): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4210 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  952): Killing 3913:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,I/ActivityManager(  952): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4266 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  952): Killing 3942:com.lge.voicerecorder/u0a34 (adj 15): empty #11
,I/ActivityManager(  952): Killing 2280:com.google.android.gms/u0a6 (adj 15): empty #11
,I/ActivityManager(  952): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=4299 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  952): Displayed com.example.hello/.MainActivity: +1s237ms
,W/ActivityThread( 4299): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  952): Waited long enough for: ServiceRecord{4894b0c u0 com.google.android.gms/.gcm.GcmService}
,W/jxcore-log( 4140): Initializing JXcore engine
W/jxcore-log( 4140): JXcore engine is ready
,W/jxcore-log( 4140): Starting JXcore engine
,W/jxcore-log( 4140): Platform android
W/jxcore-log( 4140): 
W/jxcore-log( 4140): Process ARCH arm
W/jxcore-log( 4140): 
,I/jxcore-log( 4140): JXcore Cordova bridge is ready!
I/jxcore-log( 4140): 
W/jxcore-log( 4140): JXcore engine is started
,E/jxcore-log( 4140): >> LGE-LG-D722
E/jxcore-log( 4140): 
I/jxcore-log( 4140): Total memory 906309632
I/jxcore-log( 4140): 
I/jxcore-log( 4140): Free memory 28520448
I/jxcore-log( 4140): 
I/jxcore-log( 4140): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4140): 
I/jxcore-log( 4140): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4140): 
,I/jxcore-log( 4140): userPath [ 'www' ]
I/jxcore-log( 4140): 
I/jxcore-log( 4140): Size 720 1196
I/jxcore-log( 4140): 
I/jxcore-log( 4140): Screen Brightness 255
I/jxcore-log( 4140): 
E/jxcore-log( 4140): Dummy Error Log.
E/jxcore-log( 4140): 
,I/ActivityManager(  952): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4390 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/jxcore-log( 4140): getBuffer is called!!!!
I/jxcore-log( 4140): 
,I/ActivityManager(  952): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4426 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 3968:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/ActivityManager(  952): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4524 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 3988:com.lge.cloudhub/u0a49 (adj 15): empty #11
,W/ActivityManager(  952): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  952): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  952): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  952): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  952): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  952): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  952): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4576 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/ActivityThread( 4524): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2d537487 that was originally bound here
E/ActivityThread( 4524): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2d537487 that was originally bound here
E/ActivityThread( 4524): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4524): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4524): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4524): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4524): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4524): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4524): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4524): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4524): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4524): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4524): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4524): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4524): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4524): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  952): Unbind failed: could not find connection for android.os.BinderProxy@2347844d
,I/ActivityManager(  952): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4602 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 4007:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,I/ActivityManager(  952): Killing 4032:com.lge.lgfota.permission/1000 (adj 15): empty #11
,I/ActivityManager(  952): Waited long enough for: ServiceRecord{3dcd2845 u0 com.android.mms/.service.SwitchedService}
,I/ActivityManager(  952): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4647 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  952): Killing 4072:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/ActivityManager(  952): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4671 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  952): Killing 4092:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/jxcore-log( 4140): Bluetooth turned on
I/jxcore-log( 4140): 
,I/jxcore-log( 4140): WiFi turned off
I/jxcore-log( 4140): 
I/ActivityManager(  952): Killing 4123:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/jxcore-log( 4140): WiFi turned on
I/jxcore-log( 4140): 
,I/ActivityManager(  952): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4708 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  952): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4729 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  952): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=4750 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 4164:com.lge.springcleaning/1000 (adj 15): empty #11
,I/ActivityManager(  952): Killing 4210:com.google.android.configupdater/u0a3 (adj 15): empty #11
,I/jxcore-log( 4140): No internet connection
I/jxcore-log( 4140): 
,I/ActivityManager(  952): Killing 4266:com.lge.eula/1000 (adj 15): empty #11
,I/ActivityManager(  952): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4780 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  952): Killing 4390:com.google.android.talk/u0a61 (adj 15): empty #11
,I/ActivityManager(  952): Killing 4426:com.google.android.youtube/u0a100 (adj 15): empty #11
,I/jxcore-log( 4140): No internet connection
I/jxcore-log( 4140): 
,I/ActivityManager(  952): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4826 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/jxcore-log( 4140): WiFi
I/jxcore-log( 4140): 
,I/ActivityManager(  952): Waited long enough for: ServiceRecord{8d67fef u0 com.lge.mlt/.MltMonitorService}
,I/ActivityManager(  952): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4882 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/jxcore-log( 4140): Response status code was: 200
I/jxcore-log( 4140): 
I/jxcore-log( 4140): ****TEST TOOK:  8362  ms ****
I/jxcore-log( 4140): 
I/jxcore-log( 4140): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4140): 
,I/ActivityManager(  952): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4936 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 4524:com.google.android.gm/u0a53 (adj 15): empty #11
,I/ActivityManager(  952): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4966 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 4602:com.android.vending/u0a36 (adj 15): empty #11
,I/ActivityManager(  952): Killing 4647:com.lge.qmemoplus/1000 (adj 15): empty #11
,I/ActivityManager(  952): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  952): Killing 4140:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  952): Force removing ActivityRecord{14572d12 u0 com.example.hello/.MainActivity t219}: app died, no saved state
,I/ActivityManager(  952): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4989 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  952): Force stopping com.example.hello appid=10030 user=0: pkg removed
W/ActivityManager(  952): Spurious death for ProcessRecord{31b2f500 4140:com.example.hello/u0a30}, curProc for 4140: null
,I/ActivityManager(  952): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5010 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 4729:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  952): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5037 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  952): Killing 4576:com.lge.bnr/1000 (adj 15): empty #11
,I/ActivityManager(  952): Waited long enough for: ServiceRecord{285abd75 u0 com.android.calendar/.alerts.InitAlarmsService}
,D/ActivityManager(  952): enqueue in BackgroundQueue #77 Intent=Intent { act=com.lge.qremote.action.wait_loading flg=0x14 cmp=com.lge.qremote/.appwidget.RemoteAppWidgetProvider (has extras) }


LGE-Nexus 5: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  759): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2240 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  759): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2257 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  759): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2333 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2369 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  759): Displayed com.example.hello/.MainActivity: +621ms (total +18s201ms)
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2484 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/jxcore-log( 2369): Initializing JXcore engine
W/jxcore-log( 2369): JXcore engine is ready
,W/jxcore-log( 2369): Starting JXcore engine
,I/ActivityManager(  759): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2510 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 2369): Platform android
W/jxcore-log( 2369): 
W/jxcore-log( 2369): Process ARCH arm
W/jxcore-log( 2369): 
,I/jxcore-log( 2369): JXcore Cordova bridge is ready!
I/jxcore-log( 2369): 
,W/jxcore-log( 2369): JXcore engine is started
,E/jxcore-log( 2369): >> LGE-Nexus 5
E/jxcore-log( 2369): 
,I/jxcore-log( 2369): Total memory 1946181632
I/jxcore-log( 2369): 
,I/jxcore-log( 2369): Free memory 394665984
I/jxcore-log( 2369): 
I/jxcore-log( 2369): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2369): 
I/jxcore-log( 2369): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2369): 
I/jxcore-log( 2369): userPath [ 'www' ]
I/jxcore-log( 2369): 
,I/jxcore-log( 2369): Size 1080 1776
I/jxcore-log( 2369): 
,I/jxcore-log( 2369): Screen Brightness 82
I/jxcore-log( 2369): 
,E/jxcore-log( 2369): Dummy Error Log.
E/jxcore-log( 2369): 
,D/ActivityThread( 2510): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  759): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2535 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  759): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/ActivityManager(  759): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2574 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 1243:com.android.printspooler/u0a72 (adj 15): empty #17
,I/jxcore-log( 2369): getBuffer is called!!!!
I/jxcore-log( 2369): 
,I/ActivityManager(  759): Killing 1669:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  759): Killing 1722:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,I/ActivityManager(  759): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2642 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 1969:com.android.keychain/1000 (adj 15): empty #17
,I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2666 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 1988:com.google.android.dialer/u0a10 (adj 15): empty #17
,I/ActivityManager(  759): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2694 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  759): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2739 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2072:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,I/ActivityManager(  759): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2786 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2103:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/ActivityThread( 2786): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 2369): Bluetooth turned on
I/jxcore-log( 2369): 
I/ActivityManager(  759): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2839 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 2369): WiFi turned off
I/jxcore-log( 2369): 
,I/jxcore-log( 2369): WiFi turned on
I/jxcore-log( 2369): 
,I/ActivityManager(  759): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2871 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2172:com.google.android.configupdater/u0a36 (adj 15): empty #17
,I/ActivityManager(  759): Killing 2240:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/jxcore-log( 2369): No internet connection
I/jxcore-log( 2369): 
,I/jxcore-log( 2369): No internet connection
I/jxcore-log( 2369): 
,I/jxcore-log( 2369): No internet connection
I/jxcore-log( 2369): 
,I/jxcore-log( 2369): WiFi
I/jxcore-log( 2369): 
,I/jxcore-log( 2369): Response status code was: 200
I/jxcore-log( 2369): 
I/jxcore-log( 2369): ****TEST TOOK:  9316  ms ****
I/jxcore-log( 2369): 
I/jxcore-log( 2369): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2369): 
,I/ActivityManager(  759): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 2369:com.example.hello/u0a277 (adj 0): stop com.example.hello
,W/ActivityManager(  759): Force removing ActivityRecord{12c83a6d u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  759): Spurious death for ProcessRecord{33c7ffcb 2369:com.example.hello/u0a277}, curProc for 2369: null
,I/ActivityManager(  759): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3102 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2333:com.google.android.youtube/u0a80 (adj 15): empty #17
,I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3144 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/ActivityManager(  759): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3169 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,--------- beginning of crash
,I/ActivityManager(  759): Killing 2484:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3206 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a


```

####Node name: thali03
Console output:
```
Error! Unexpected exit on device 320414cd475f91e3 app:com.example.hello code:0 
child process exited with code 0 on device 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3472
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3488 uid=10359 gids={50359, 3003, 3001, 3002}
,I/ActivityManager( 1016): Displayed com.example.hello/.MainActivity: +352ms (total +381ms)
,W/jxcore-log( 3488): Initializing JXcore engine
,W/jxcore-log( 3488): JXcore engine is ready
,W/jxcore-log( 3488): Starting JXcore engine
,W/jxcore-log( 3488): Platform android
W/jxcore-log( 3488): 
,W/jxcore-log( 3488): Process ARCH arm
W/jxcore-log( 3488): 
,I/jxcore-log( 3488): JXcore Cordova bridge is ready!
I/jxcore-log( 3488): 
,W/jxcore-log( 3488): JXcore engine is started
,E/jxcore-log( 3488): >> motorola-XT1039
E/jxcore-log( 3488): 
,I/jxcore-log( 3488): Total memory 893136896
I/jxcore-log( 3488): 
I/jxcore-log( 3488): Free memory 31105024
I/jxcore-log( 3488): 
I/jxcore-log( 3488): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): userPath [ 'www' ]
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): Size 720 1184
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): Screen Brightness 10
I/jxcore-log( 3488): 
,E/jxcore-log( 3488): Dummy Error Log.
E/jxcore-log( 3488): 
,I/jxcore-log( 3488): getBuffer is called!!!!
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): Bluetooth turned on
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): WiFi turned off
I/jxcore-log( 3488): 
I/ActivityManager( 1016): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3545 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,I/jxcore-log( 3488): WiFi turned on
I/jxcore-log( 3488): 
,I/ActivityManager( 1016): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3590 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1016): Killing 3287:com.android.calendar/u0a7 (adj 15): empty #9
,I/jxcore-log( 3488): No internet connection
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): No internet connection
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): No internet connection
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): No internet connection
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): No internet connection
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): WiFi
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): Response status code was: 200
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): ****TEST TOOK:  11430  ms ****
I/jxcore-log( 3488): 
,I/jxcore-log( 3488): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3488): 
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10359 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 3488:com.example.hello/u0a359 (adj 0): stop com.example.hello
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{42819058 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10359 user=0: pkg removed
,I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3776 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1016): Killing 3363:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1016): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3798 uid=10058 gids={50058}
,I/ActivityManager( 1016): Killing 3341:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1016): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3816 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1016): Killing 3590:com.android.settings/1000 (adj 15): empty #9
,I/ActivityManager( 1016): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3834 uid=10020 gids={50020, 1028, 1015, 1023}
,W/ActivityThread( 3816): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());


LGE-LG-D855: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager( 1036): Killing 4918:com.android.calendar/u0a13 (adj 15): empty #17
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{aa84c7a #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{aa84c7a #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1036): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6032 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1036): Display changed displayId=0
,I/ActivityManager( 1036): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6074 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1036): Killing 5637:com.lge.email/u0a23 (adj 15): empty #17
W/ActivityManager( 1036): Activity pause timeout for ActivityRecord{3151ec2b u0 com.example.hello/.MainActivity t2}
I/ActivityManager( 1036): Displayed com.example.hello/.MainActivity: +626ms (total +720ms)
W/jxcore-log( 6032): Initializing JXcore engine
W/jxcore-log( 6032): JXcore engine is ready
W/jxcore-log( 6032): Starting JXcore engine
,W/jxcore-log( 6032): Platform android
W/jxcore-log( 6032): 
W/jxcore-log( 6032): Process ARCH arm
W/jxcore-log( 6032): 
,I/jxcore-log( 6032): JXcore Cordova bridge is ready!
I/jxcore-log( 6032): 
,W/jxcore-log( 6032): JXcore engine is started
,E/jxcore-log( 6032): >> LGE-LG-D855
E/jxcore-log( 6032): 
I/jxcore-log( 6032): Total memory 2995761152
I/jxcore-log( 6032): 
I/jxcore-log( 6032): Free memory 630005760
I/jxcore-log( 6032): 
I/jxcore-log( 6032): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6032): 
I/jxcore-log( 6032): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): userPath [ 'www' ]
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): Size 1440 2392
I/jxcore-log( 6032): 
I/jxcore-log( 6032): Screen Brightness 50
I/jxcore-log( 6032): 
E/jxcore-log( 6032): Dummy Error Log.
E/jxcore-log( 6032): 
,I/jxcore-log( 6032): getBuffer is called!!!!
I/jxcore-log( 6032): 
,I/ActivityManager( 1036): Killing 4872:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,I/jxcore-log( 6032): Bluetooth turned on
I/jxcore-log( 6032): 
I/jxcore-log( 6032): WiFi turned off
I/jxcore-log( 6032): 
I/jxcore-log( 6032): WiFi turned on
I/jxcore-log( 6032): 
I/ActivityManager( 1036): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6152 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6200 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 5682:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/ActivityThread( 6152): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6240 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 5774:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager( 1036): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6267 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1036): Killing 4846:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6292 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/ActivityManager( 1036): Killing 5381:com.google.android.talk/u0a72 (adj 15): empty #17
,I/ActivityManager( 1036): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6345 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,I/ActivityManager( 1036): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6366 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 5499:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager( 1036): Killing 5843:com.google.android.gms:car/u0a5 (adj 15): empty #18
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/ActivityManager( 1036): Killing 5594:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/ActivityManager( 1036): Killing 5612:com.android.contacts/u0a19 (adj 15): empty #17
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): Timeout in log.js file reached!
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): ****TEST TOOK:  125186  ms ****
I/jxcore-log( 6032): 
I/jxcore-log( 6032): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILURE]****
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): No internet connection
I/jxcore-log( 6032): 
,I/ActivityManager( 1036): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1036): Killing 6032:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1036):   Force finishing activity ActivityRecord{3151ec2b u0 com.example.hello/.MainActivity t2}
,W/ActivityManager( 1036): Spurious death for ProcessRecord{3b3debf1 6032:com.example.hello/u0a318}, curProc for 6032: null
I/ActivityManager( 1036): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{3151ec2b u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{3151ec2b u0 com.example.hello/.MainActivity t2 f}
,I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6532 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ActivityManager( 1036): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,I/ActivityManager( 1036): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6554 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 5661:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager( 1036): Killing 5749:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,--------- beginning of crash
,I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6578 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1036): Process android.process.acore (pid 2184) has died
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms


samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager( 2388): Process com.android.email (pid 5537) (adj 9) has died.
D/ActivityThread( 5582): Added TimaKesytore provider
D/ActivityThread( 5586): Added TimaKesytore provider
I/ActivityManager( 2388): Killing 4655:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/ActivityManager( 2388): Killing 4819:com.policydm/1000 (adj 15): empty #43
D/ActivityThread( 5608): Added TimaKesytore provider
I/ActivityManager( 2388): Killing 4842:com.osp.app.signin/u0a44 (adj 15): empty #43
I/ActivityManager( 2388): Process com.android.exchange (pid 5563) (adj 9) has died.
D/ActivityThread( 5624): Added TimaKesytore provider
W/ActivityManager( 2388): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityThread( 5647): Added TimaKesytore provider
,I/ActivityManager( 2388): Killing 3821:com.android.mms/u0a49 (adj 15): empty #43
D/ActivityThread( 5660): Added TimaKesytore provider
D/ActivityThread( 5675): Added TimaKesytore provider
I/ActivityManager( 2388): Killing 4870:com.sec.android.app.safetyassurance/u0a51 (adj 15): empty #43
D/ActivityThread( 5687): Added TimaKesytore provider
I/ActivityManager( 2388): Killing 2818:com.android.settings/1000 (adj 15): empty #43
D/ActivityThread( 5706): Added TimaKesytore provider
W/ActivityManager( 2388): mDVFSHelper.acquire()
D/ActivityThread( 5721): Added TimaKesytore provider
,W/ActivityManager( 2388): mDVFSHelper.release()
,I/ActivityManager( 2388): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 5706) (adj 0) has died.
,D/ActivityThread( 5767): Added TimaKesytore provider
,W/jxcore-log( 5721): Initializing JXcore engine
,W/jxcore-log( 5721): JXcore engine is ready
,W/jxcore-log( 5721): Starting JXcore engine
,D/ActivityThread( 5785): Added TimaKesytore provider
,W/jxcore-log( 5721): Platform android
W/jxcore-log( 5721): 
,W/jxcore-log( 5721): Process ARCH arm
W/jxcore-log( 5721): 
,I/jxcore-log( 5721): JXcore Cordova bridge is ready!
I/jxcore-log( 5721): 
,W/jxcore-log( 5721): JXcore engine is started
I/ActivityManager( 2388): Killing 4936:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/ActivityThread( 5798): Added TimaKesytore provider
,E/jxcore-log( 5721): >> samsung-SM-G800F
E/jxcore-log( 5721): 
,I/jxcore-log( 5721): Total memory 1319530496
I/jxcore-log( 5721): 
,I/jxcore-log( 5721): Free memory 43380736
I/jxcore-log( 5721): 
I/jxcore-log( 5721): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5721): 
,I/jxcore-log( 5721): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5721): 
,I/ActivityManager( 2388): Killing 4919:com.google.android.apps.plus/u0a133 (adj 15): empty #43
,I/jxcore-log( 5721): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5721): 
,I/jxcore-log( 5721): Size 720 1280
I/jxcore-log( 5721): 
,I/jxcore-log( 5721): Screen Brightness 134
I/jxcore-log( 5721): 
,E/jxcore-log( 5721): Dummy Error Log.
E/jxcore-log( 5721): 
,D/ActivityThread( 5811): Added TimaKesytore provider
,I/ActivityManager( 2388): Killing 4974:com.google.android.apps.magazines/u0a115 (adj 15): empty #43
,D/ActivityThread( 5824): Added TimaKesytore provider
,I/jxcore-log( 5721): getBuffer is called!!!!
I/jxcore-log( 5721): 
,D/ActivityThread( 5880): Added TimaKesytore provider
,I/ActivityManager( 2388): Killing 5021:com.samsung.android.intelligenceservice/u0a5 (adj 15): empty #43
D/ActivityThread( 5910): Added TimaKesytore provider
I/ActivityManager( 2388): Killing 5080:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,D/ActivityThread( 5923): Added TimaKesytore provider
,I/ActivityManager( 2388): Killing 5102:com.samsung.android.scloud.sync/u0a64 (adj 15): empty #43
,D/ActivityThread( 5940): Added TimaKesytore provider
,I/ActivityManager( 2388): Killing 5119:com.wssnps/1000 (adj 15): empty #43
,I/jxcore-log( 5721): Bluetooth turned on
I/jxcore-log( 5721): 
,I/jxcore-log( 5721): WiFi turned off
I/jxcore-log( 5721): 
,W/ActivityManager( 2388): Permission Denial: getCurrentUser() from pid=5721, uid=10428 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 5721): WiFi turned on
I/jxcore-log( 5721): 
,D/ActivityThread( 5952): Added TimaKesytore provider
,I/ActivityManager( 2388): Killing 5138:com.samsung.android.app.accesscontrol/u0a67 (adj 15): empty #43
,D/ActivityThread( 5977): Added TimaKesytore provider
,I/jxcore-log( 5721): No internet connection
I/jxcore-log( 5721): 
,D/ActivityThread( 5997): Added TimaKesytore provider


```

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on ZX1C223JKW 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Android task is completed 
```

Logcat output:
```
samsung-SM-G900F: 
--------- beginning of system
--------- beginning of main
,I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  881): mDVFSHelper.acquire()
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=7804 uid=10191 gids={50191, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 7804): Added TimaKeyStore provider
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{20fe44dd u0 com.example.hello/.MainActivity t4}
,D/ActivityManager(  881): post active user change for 0
,W/ActivityManager(  881): mDVFSHelper.release()
,W/jxcore-log( 7804): Initializing JXcore engine
,W/jxcore-log( 7804): JXcore engine is ready
,W/jxcore-log( 7804): Starting JXcore engine
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7888 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 7888): Added TimaKeyStore provider
,W/jxcore-log( 7804): Platform android
W/jxcore-log( 7804): 
W/jxcore-log( 7804): Process ARCH arm
W/jxcore-log( 7804): 
,I/jxcore-log( 7804): JXcore Cordova bridge is ready!
I/jxcore-log( 7804): 
,W/jxcore-log( 7804): JXcore engine is started
,E/jxcore-log( 7804): >> samsung-SM-G900F
E/jxcore-log( 7804): 
,I/jxcore-log( 7804): Total memory 1787449344
I/jxcore-log( 7804): 
,I/jxcore-log( 7804): Free memory 64352256
I/jxcore-log( 7804): 
I/jxcore-log( 7804): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7804): 
I/jxcore-log( 7804): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7804): 
,I/jxcore-log( 7804): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 7804): 
,I/jxcore-log( 7804): Size 1080 1920
I/jxcore-log( 7804): 
,I/jxcore-log( 7804): Screen Brightness 134
I/jxcore-log( 7804): 
,E/jxcore-log( 7804): Dummy Error Log.
E/jxcore-log( 7804): 
,I/jxcore-log( 7804): getBuffer is called!!!!
I/jxcore-log( 7804): 
,I/jxcore-log( 7804): Bluetooth turned on
I/jxcore-log( 7804): 
,I/jxcore-log( 7804): WiFi turned off
I/jxcore-log( 7804): 
,W/ActivityManager(  881): Permission Denial: getCurrentUser() from pid=7804, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 7804): WiFi turned on
I/jxcore-log( 7804): 
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7959 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7959): Added TimaKeyStore provider
,I/jxcore-log( 7804): No internet connection
I/jxcore-log( 7804): 
,I/ActivityManager(  881): Killing 6807:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 7976): Added TimaKeyStore provider
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7995 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7995): Added TimaKeyStore provider
,I/jxcore-log( 7804): No internet connection
I/jxcore-log( 7804): 
,I/ActivityManager(  881): Killing 6944:com.sec.enterprise.knox.cloudmdm.smdms/u0a178 (adj 15): bgCount ##41
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8017 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7049:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,D/ActivityThread( 8017): Added TimaKeyStore provider
,I/ActivityManager(  881): Killing 7068:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=8034 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 8034): Added TimaKeyStore provider
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=8059 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6086:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,D/ActivityThread( 8059): Added TimaKeyStore provider
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8079 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5721:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/ActivityThread( 8079): Added TimaKeyStore provider
,I/jxcore-log( 7804): No internet connection
I/jxcore-log( 7804): 
,I/ActivityManager(  881): Killing 7146:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8103 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 8103): Added TimaKeyStore provider
,I/jxcore-log( 7804): No internet connection
I/jxcore-log( 7804): 
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8210 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7163:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,D/ActivityThread( 8210): Added TimaKeyStore provider
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8228 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6283:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ActivityThread( 8228): Added TimaKeyStore provider
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8254 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,I/jxcore-log( 7804): WiFi
I/jxcore-log( 7804): 
,I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  881): mDVFSHelper.acquire()
,D/ActivityThread( 8254): Added TimaKeyStore provider
,I/jxcore-log( 7804): Response status code was: 200
I/jxcore-log( 7804): 
,I/jxcore-log( 7804): ****TEST TOOK:  10357  ms ****
I/jxcore-log( 7804): 
,I/jxcore-log( 7804): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7804): 
,E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  881): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  881): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8282 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 8282): Added TimaKeyStore provider
,D/ActivityManager(  881): post active user change for 0
,I/ActivityManager(  881): Killing 7182:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,W/ActivityManager(  881): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager(  881): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  881): Killing 7238:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,I/ActivityManager(  881): Force stopping com.example.hello appid=10191 user=-1: uninstall pkg
,I/ActivityManager(  881): Killing 7804:com.example.hello/u0a191 (adj 0): stop com.example.hello
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{20fe44dd u0 com.example.hello/.MainActivity t4}
,I/ActivityManager(  881): Force stopping com.example.hello appid=10191 user=0: pkg removed
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{20fe44dd u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{20fe44dd u0 com.example.hello/.MainActivity t4 f}
,D/ActivityManager(  881): post active user change for 0
,W/ActivityManager(  881): mDVFSHelper.release()


motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  887): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6762 uid=10280 gids={50280, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Displayed com.example.hello/.MainActivity: +1s67ms
,W/jxcore-log( 6762): Initializing JXcore engine
W/jxcore-log( 6762): JXcore engine is ready
,W/jxcore-log( 6762): Starting JXcore engine
,W/jxcore-log( 6762): Platform android
W/jxcore-log( 6762): 
W/jxcore-log( 6762): Process ARCH arm
W/jxcore-log( 6762): 
,I/jxcore-log( 6762): JXcore Cordova bridge is ready!
I/jxcore-log( 6762): 
,W/jxcore-log( 6762): JXcore engine is started
,E/jxcore-log( 6762): >> motorola-XT1072
E/jxcore-log( 6762): 
,I/jxcore-log( 6762): Total memory 916258816
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): Free memory 31535104
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): userPath [ 'www' ]
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): Size 720 1184
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): Screen Brightness 82
I/jxcore-log( 6762): 
,E/jxcore-log( 6762): Dummy Error Log.
E/jxcore-log( 6762): 
,I/jxcore-log( 6762): getBuffer is called!!!!
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): Bluetooth turned on
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): WiFi turned off
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): WiFi turned on
I/jxcore-log( 6762): 
,I/ActivityManager(  887): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6878 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6905 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6365:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/ActivityManager(  887): Killing 6395:com.android.vending/u0a32 (adj 15): empty #7
,I/jxcore-log( 6762): No internet connection
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): No internet connection
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): No internet connection
I/jxcore-log( 6762): 
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6972 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 6972): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7020 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6762): No internet connection
I/jxcore-log( 6762): 
,I/ActivityManager(  887): Killing 6474:com.google.android.youtube/u0a101 (adj 15): empty #7
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7056 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6620:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7079 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6603:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7100 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6878:com.motorola.context/u0a8 (adj 15): empty #7
,I/jxcore-log( 6762): No internet connection
I/jxcore-log( 6762): 
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7179 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6972:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7204 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7020:com.android.mms/u0a23 (adj 15): empty #7
,I/jxcore-log( 6762): No internet connection
I/jxcore-log( 6762): 
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7228 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7056:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/ActivityThread( 7228): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7256 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7079:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7311 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7338 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6905:com.google.android.talk/u0a70 (adj 15): empty #7
,I/jxcore-log( 6762): WiFi
I/jxcore-log( 6762): 
,E/ActivityThread( 1973): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 6762): Response status code was: 200
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): ****TEST TOOK:  12331  ms ****
I/jxcore-log( 6762): 
,I/jxcore-log( 6762): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6762): 
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7363 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7380 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7100:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ActivityManager(  887): Force stopping com.example.hello appid=10280 user=-1: uninstall pkg
I/ActivityManager(  887): Killing 6762:com.example.hello/u0a280 (adj 0): stop com.example.hello
,W/ActivityThread( 7363): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityManager(  887): Force removing ActivityRecord{95d7001 u0 com.example.hello/.MainActivity t29}: app died, no saved state
,W/ActivityManager(  887): Spurious death for ProcessRecord{158539b6 6762:com.example.hello/u0a280}, curProc for 6762: null
,I/ActivityManager(  887): Force stopping com.example.hello appid=10280 user=0: pkg removed
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7430 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7179:com.android.chrome/u0a52 (adj 15): empty #7


samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
V/ActivityManager( 3499): Display changed displayId=0
V/ActivityManager( 3499): Display changed displayId=0
D/ActivityManager( 3499): post active user change for 0
I/ActivityManager( 3499): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager( 3499): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager( 3499): mDVFSHelper.acquire()
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3499): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11844 uid=10387 gids={50387, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread(11844): Added TimaKeyStore provider
V/ActivityManager( 3499): Display changed displayId=0
,D/ActivityManager( 3499): post active user change for 0
,I/ActivityManager( 3499): Displayed com.example.hello/.MainActivity: +644ms
,W/ActivityManager( 3499): mDVFSHelper.release()
,W/jxcore-log(11844): Initializing JXcore engine
W/jxcore-log(11844): JXcore engine is ready
,W/jxcore-log(11844): Starting JXcore engine
,W/jxcore-log(11844): Platform android
W/jxcore-log(11844): 
W/jxcore-log(11844): Process ARCH arm
W/jxcore-log(11844): 
,I/jxcore-log(11844): JXcore Cordova bridge is ready!
I/jxcore-log(11844): 
,W/jxcore-log(11844): JXcore engine is started
,E/jxcore-log(11844): >> samsung-SM-N910C
E/jxcore-log(11844): 
,I/jxcore-log(11844): Total memory 2970812416
I/jxcore-log(11844): 
,I/jxcore-log(11844): Free memory 76836864
I/jxcore-log(11844): 
I/jxcore-log(11844): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11844): 
I/jxcore-log(11844): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11844): 
,I/jxcore-log(11844): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(11844): 
,I/jxcore-log(11844): Size 1440 2560
I/jxcore-log(11844): 
,I/jxcore-log(11844): Screen Brightness 134
I/jxcore-log(11844): 
,E/jxcore-log(11844): Dummy Error Log.
E/jxcore-log(11844): 
,I/jxcore-log(11844): getBuffer is called!!!!
I/jxcore-log(11844): 
,I/jxcore-log(11844): Bluetooth turned on
I/jxcore-log(11844): 
,I/jxcore-log(11844): WiFi turned off
I/jxcore-log(11844): 
,W/ActivityManager( 3499): Permission Denial: getCurrentUser() from pid=11844, uid=10387 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log(11844): WiFi turned on
I/jxcore-log(11844): 
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=11930 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(11930): Added TimaKeyStore provider
,I/ActivityManager( 3499): Killing 11132:com.policydm/1000 (adj 15): bgCount ##31
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11959 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(11959): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=11975 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11047:com.android.mms/u0a52 (adj 15): bgCount ##31
,D/ActivityThread(11975): Added TimaKeyStore provider
,I/ActivityManager( 3499): Killing 11154:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11991 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread(11991): Added TimaKeyStore provider
,I/jxcore-log(11844): No internet connection
I/jxcore-log(11844): 
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=12017 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11181:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,D/ActivityThread(12017): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11196:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/ActivityThread(12073): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12089 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11233:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,I/jxcore-log(11844): No internet connection
I/jxcore-log(11844): 
,D/ActivityThread(12089): Added TimaKeyStore provider
,W/ActivityThread(12089): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12118 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11250:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/ActivityThread(12118): Added TimaKeyStore provider
,I/ActivityManager( 3499): Killing 11016:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread(12142): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12158 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log(11844): No internet connection
I/jxcore-log(11844): 
,D/ActivityThread(12158): Added TimaKeyStore provider
,I/ActivityManager( 3499): Killing 11218:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,I/ActivityManager( 3499): Killing 11271:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##32
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12175 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread(12175): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12191 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11324:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ActivityThread(12191): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12208 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11344:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/ActivityThread(12208): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12229 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3499): Killing 11293:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/ActivityThread(12229): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12246 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11412:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/ActivityThread(12246): Added TimaKeyStore provider
,I/ActivityManager( 3499): Killing 11397:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12274 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread(12274): Added TimaKeyStore provider
,I/ActivityManager( 3499): Killing 11435:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/jxcore-log(11844): No internet connection
I/jxcore-log(11844): 
,I/ActivityManager( 3499): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12291 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread(12291): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12306 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11451:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/ActivityThread(12306): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12322 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11466:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/ActivityThread(12322): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12392 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3499): Killing 11522:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/ActivityThread(12392): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/jxcore-log(11844): No internet connection
I/jxcore-log(11844): 
,I/ActivityManager( 3499): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12417 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11540:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/ActivityThread(12417): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12449 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11558:com.google.android.gm/u0a122 (adj 13): bgCount ##31
,D/ActivityThread(12449): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12475 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11629:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,W/ActivityManager( 3499): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityThread(12475): Added TimaKeyStore provider
,W/ActivityManager( 3499): Failed to clear dns cache for: com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 3499): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/ActivityManager( 3499): Killing 11644:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/jxcore-log(11844): WiFi
I/jxcore-log(11844): 
,I/jxcore-log(11844): Response status code was: 200
I/jxcore-log(11844): 
,I/jxcore-log(11844): ****TEST TOOK:  11299  ms ****
I/jxcore-log(11844): 
I/jxcore-log(11844): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11844): 
,E/ActivityThread(12017): Failed to find provider info for com.facebook.orca.notify.MessengerLoggedInUserProvider
,E/ActivityThread(12017): Failed to find provider info for com.facebook.orca.notify.MessengerLoggedInUserProvider
,I/ActivityManager( 3499): Force stopping com.example.hello appid=10387 user=-1: uninstall pkg
,I/ActivityManager( 3499): Killing 11844:com.example.hello/u0a387 (adj 0): stop com.example.hello
,W/ActivityManager( 3499): Force removing ActivityRecord{29e2d579 u0 com.example.hello/.MainActivity t28}: app died, no saved state
,W/ActivityManager( 3499): mDVFSHelper.acquire()
,I/ActivityManager( 3499): Force stopping com.example.hello appid=10387 user=0: pkg removed
,D/ActivityManager( 3499): handle home activity for 0
D/ActivityManager( 3499): post active user change for 0
,W/ActivityManager( 3499): mDVFSHelper.release()
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12588 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(12588): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12605 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12605): Added TimaKeyStore provider
,I/ActivityManager( 3499): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12622 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12631 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread(12622): Added TimaKeyStore provider
,D/ActivityThread(12631): Added TimaKeyStore provider
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12652 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12652): Added TimaKeyStore provider
,I/ActivityManager( 3499): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12670 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ActivityThread(12670): Added TimaKeyStore provider
,I/ActivityManager( 3499): Killing 11678:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12694 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 10539:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/ActivityThread(12694): Added TimaKeyStore provider
,I/ActivityManager( 3499): Killing 10634:com.android.vending/u0a31 (adj 13): bgCount ##31
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3499): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12715 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 11930:com.samsung.android.app.FileShareServer/u0a79 (adj 13): bgCount ##31
,E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3499): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12715): Added TimaKeyStore provider
,I/ActivityManager( 3499): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12733 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3499): Killing 8888:com.android.settings/1000 (adj 13): bgCount ##31
,D/ActivityThread(12733): Added TimaKeyStore provider


```

####Node name: thali05
Console output:
```
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on 1d6a772d 
Device test finished on SH47FWM00508 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of system
--------- beginning of main
V/ActivityManager(  737): Display changed displayId=0
,V/ActivityManager(  737): Display changed displayId=0
D/ActivityManager(  737): handle home activity for 0
D/ActivityManager(  737): post active user change for 0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  737): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6215 uid=10109 gids={50109, 9997} abi=armeabi-v7a
D/ActivityThread( 6215): Added TimaKeyStore provider
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  737): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager(  737): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6239 uid=10115 gids={50115, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  737): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  737): mDVFSHelper.acquire()
D/ActivityThread( 6239): Added TimaKeyStore provider
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  737): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6254 uid=10220 gids={50220, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 6254): Added TimaKeyStore provider
V/ActivityManager(  737): Display changed displayId=0
V/ActivityThread( 1428): updateVisibility : ActivityRecord{2ad0f1dd token=android.os.BinderProxy@39a9e437 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
E/ActivityThread( 1428): Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1428): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1428): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3818)
E/ActivityThread( 1428): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3906)
E/ActivityThread( 1428): 	at android.app.ActivityThread.access$1200(ActivityThread.java:177)
E/ActivityThread( 1428): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1477)
E/ActivityThread( 1428): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1428): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 1428): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/ActivityThread( 1428): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1428): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1428): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/ActivityThread( 1428): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
V/ActivityThread( 1428): updateVisibility : ActivityRecord{2ad0f1dd token=android.os.BinderProxy@39a9e437 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/ActivityManager(  737): Activity reported stop, but no longer stopping: ActivityRecord{9b8f81e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1}
I/ActivityManager(  737): Killing 5288:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
I/ActivityManager(  737): Killing 5090:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
D/ActivityManager(  737): post active user change for 0
I/ActivityManager(  737): Displayed com.example.hello/.MainActivity: +573ms
W/jxcore-log( 6254): Initializing JXcore engine
W/jxcore-log( 6254): JXcore engine is ready
W/ActivityManager(  737): mDVFSHelper.release()
W/jxcore-log( 6254): Starting JXcore engine
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  737): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/jxcore-log( 6254): Platform android
W/jxcore-log( 6254): 
W/jxcore-log( 6254): Process ARCH arm
W/jxcore-log( 6254): 
,D/ActivityThread( 6315): Added TimaKeyStore provider
I/jxcore-log( 6254): JXcore Cordova bridge is ready!
I/jxcore-log( 6254): 
W/jxcore-log( 6254): JXcore engine is started
I/ActivityManager(  737): Killing 4378:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
E/jxcore-log( 6254): >> samsung-SM-N9005
E/jxcore-log( 6254): 
I/jxcore-log( 6254): Total memory 2971471872
I/jxcore-log( 6254): 
I/jxcore-log( 6254): Free memory 430071808
I/jxcore-log( 6254): 
I/jxcore-log( 6254): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6254): 
I/jxcore-log( 6254): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6254): 
I/jxcore-log( 6254): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6254): 
I/jxcore-log( 6254): Size 1080 1920
I/jxcore-log( 6254): 
I/jxcore-log( 6254): Screen Brightness 162
I/jxcore-log( 6254): 
E/jxcore-log( 6254): Dummy Error Log.
E/jxcore-log( 6254): 
,I/jxcore-log( 6254): getBuffer is called!!!!
I/jxcore-log( 6254): 
,W/ActivityManager(  737): Permission Denial: getCurrentUser() from pid=6254, uid=10220 requires android.permission.INTERACT_ACROSS_USERS
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6254): Bluetooth turned on
I/jxcore-log( 6254): 
,I/jxcore-log( 6254): WiFi turned off
I/jxcore-log( 6254): 
,W/ActivityManager(  737): Permission Denial: getCurrentUser() from pid=6254, uid=10220 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  737): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6344 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 6254): WiFi turned on
I/jxcore-log( 6254): 
,D/ActivityThread( 6344): Added TimaKeyStore provider
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6380 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/ActivityThread( 6380): Added TimaKeyStore provider
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6411 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityThread( 6411): Added TimaKeyStore provider
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6453 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,I/ActivityManager(  737): Killing 5126:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,D/ActivityThread( 6453): Added TimaKeyStore provider
,I/ActivityManager(  737): Killing 5385:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,I/jxcore-log( 6254): No internet connection
I/jxcore-log( 6254): 
,I/ActivityManager(  737): Killing 5409:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/ActivityManager(  737): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6508 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6508): Added TimaKeyStore provider
,I/ActivityManager(  737): Killing 5462:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/jxcore-log( 6254): No internet connection
I/jxcore-log( 6254): 
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6527 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6527): Added TimaKeyStore provider
,I/ActivityManager(  737): Killing 4903:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6550 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/ActivityThread( 6550): Added TimaKeyStore provider
,I/jxcore-log( 6254): No internet connection
I/jxcore-log( 6254): 
,I/ActivityManager(  737): Killing 4974:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,I/jxcore-log( 6254): No internet connection
I/jxcore-log( 6254): 
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6690 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6703 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6690): Added TimaKeyStore provider
,D/ActivityThread( 6703): Added TimaKeyStore provider
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
I/jxcore-log( 6254): WiFi
I/jxcore-log( 6254): 
,I/ActivityManager(  737): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6733 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  737): Killing 5056:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,D/ActivityThread( 6733): Added TimaKeyStore provider
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6749 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/jxcore-log( 6254): Response status code was: 200
I/jxcore-log( 6254): 
I/jxcore-log( 6254): ****TEST TOOK:  9095  ms ****
I/jxcore-log( 6254): 
I/jxcore-log( 6254): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6254): 
,D/ActivityThread( 6749): Added TimaKeyStore provider
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6766 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6766): Added TimaKeyStore provider
,I/ActivityManager(  737): Killing 5577:flipboard.app/u0a125 (adj 15): bgCount ##41
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=6785 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6785): Added TimaKeyStore provider
,I/ActivityManager(  737): Force stopping com.example.hello appid=10220 user=-1: uninstall pkg
,I/ActivityManager(  737): Killing 6254:com.example.hello/u0a220 (adj 0): stop com.example.hello
,W/ActivityManager(  737): Force removing ActivityRecord{c2f5758 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  737): mDVFSHelper.acquire()
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6814 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  737): Spurious death for ProcessRecord{7a14c41 6254:com.example.hello/u0a220}, curProc for 6254: null
,I/ActivityManager(  737): Killing 5624:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,I/ActivityManager(  737): Force stopping com.example.hello appid=10220 user=0: pkg removed
,D/ActivityThread( 6814): Added TimaKeyStore provider
,D/ActivityManager(  737): handle home activity for 0
D/ActivityManager(  737): post active user change for 0
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6840 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  737): Killing 5768:com.google.android.partnersetup/u0a19 (adj 13): bgCount ##41
,D/ActivityThread( 6840): Added TimaKeyStore provider
,W/ActivityManager(  737): mDVFSHelper.release()
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=6868 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ActivityThread( 6868): Added TimaKeyStore provider
,I/ActivityManager(  737): Killing 5786:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6896 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6896): Added TimaKeyStore provider
,E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  737): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  737): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6918 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  737): Killing 5325:sstream.app/u0a25 (adj 15): bgCount ##41
,D/ActivityThread( 6918): Added TimaKeyStore provider
,I/ActivityManager(  737): Killing 5362:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,E/ActivityThread( 6918): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  737): Killing 5859:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41


HTC-HTC One_M8: 
--------- beginning of system
--------- beginning of main
I/ActivityManager(  893): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4382 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  893): Killing 3838:com.htc.backup/u0a118 (adj 15): empty #17
I/ActivityManager(  893): Recipient 3838
,I/ActivityManager(  893): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4412 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  893): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4440 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  893): Killing 3929:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  893): Recipient 3929
I/ActivityManager(  893): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  893): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4503 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  893): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  893): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  893): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=4549 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  893): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  893): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  893): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4440): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@23d59cd1 that was originally bound here
E/ActivityThread( 4440): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@23d59cd1 that was originally bound here
E/ActivityThread( 4440): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4440): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4440): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4440): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
E/ActivityThread( 4440): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4440): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4440): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4440): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4440): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4440): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4440): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4440): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4440): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  893): Unbind failed: could not find connection for android.os.BinderProxy@35d7cc3d
W/ActivityManager(  893): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  893): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4595 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  893): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4621 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
W/ActivityThread( 4595): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  893): Displayed com.example.hello/.MainActivity: +674ms
I/ActivityManager(  893): Killing 3969:com.htc.htccupd/u0a13 (adj 15): empty #17
I/ActivityManager(  893): Recipient 3969
,I/ActivityManager(  893): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4662 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
,W/jxcore-log( 4503): Initializing JXcore engine,
W/jxcore-log( 4503): JXcore engine is ready
,W/jxcore-log( 4503): Starting JXcore engine,
,I/ActivityManager(  893): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4680 uid=10037 gids={50037, 9997} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 3893:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 3893
,W/jxcore-log( 4503): Platform android,
W/jxcore-log( 4503): 
W/jxcore-log( 4503): Process ARCH arm
W/jxcore-log( 4503): 
,I/ActivityManager(  893): Killing 4028:com.htc.mobiledata/u0a48 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4028
,I/jxcore-log( 4503): JXcore Cordova bridge is ready!
I/jxcore-log( 4503): 
,W/jxcore-log( 4503): JXcore engine is started
,I/ActivityManager(  893): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4699 uid=10079 gids={50079, 9997} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 4048:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4048
,E/jxcore-log( 4503): >> HTC-HTC One_M8,
E/jxcore-log( 4503): 
,I/jxcore-log( 4503): Total memory 1912020992
I/jxcore-log( 4503): 
I/jxcore-log( 4503): Free memory 144273408
I/jxcore-log( 4503): 
,I/jxcore-log( 4503): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4503): 
I/jxcore-log( 4503): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4503): 
,I/jxcore-log( 4503): userPath [ 'www' ],
I/jxcore-log( 4503): 
,I/jxcore-log( 4503): Size 1080 1776
I/jxcore-log( 4503): 
,I/jxcore-log( 4503): Screen Brightness 142
I/jxcore-log( 4503): 
E/jxcore-log( 4503): Dummy Error Log.
E/jxcore-log( 4503): 
,I/ActivityManager(  893): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4724 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 4065:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4065
,I/ActivityManager(  893): Killing 4102:com.htc.bgp/u0a11 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4102
,I/ActivityManager(  893): Killing 4125:com.android.smith/1000 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4125
,I/ActivityManager(  893): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4752 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
,I/jxcore-log( 4503): getBuffer is called!!!!,
I/jxcore-log( 4503): 
,I/ActivityManager(  893): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4774 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4799 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a,
,I/ActivityManager(  893): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4820 uid=10029 gids={50029, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,I/ActivityManager(  893): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4841 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 4182:com.google.android.gms:car/u0a25 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4182
,W/ActivityManager(  893): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms,
,I/ActivityManager(  893): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4871 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  893): Killing 4146:com.android.vending/u0a75 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4146,
,I/ActivityManager(  893): Killing 4296:com.google.android.youtube/u0a186 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4296,
,I/ActivityManager(  893): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4913 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 4412:com.google.android.partnersetup/u0a28 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4412
,I/ActivityManager(  893): Killing 4382:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4382,
,W/ActivityThread( 4871): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  893): Killing 4440:com.google.android.gm/u0a115 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4440
,I/ActivityManager(  893): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4947 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=4968 uid=10051 gids={50051, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/ActivityManager(  893): Killing 4549:com.htc.backup/u0a118 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4549
,I/ActivityManager(  893): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4990 uid=10082 gids={50082, 9997, 5001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  893): Resuming delayed broadcast,
,I/ActivityManager(  893): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5017 uid=10088 gids={50088, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=armeabi-v7a,
,I/ActivityManager(  893): Killing 4621:com.htc.sense.news/u0a77 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4621
,I/ActivityManager(  893): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5047 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=5069 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  893): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5091 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
I/ActivityManager(  893): Killing 3987:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 3987
,I/ActivityManager(  893): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5114 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 4680:com.htc.widget.hmsproc1/u0a37 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4680,
,I/ActivityManager(  893): Killing 4699:com.htc.mms.backupagent/u0a79 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4699
,I/ActivityManager(  893): Killing 4259:com.google.android.talk/u0a120 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4259,
,I/ActivityManager(  893): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4085): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  893): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4085): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  893): Killing 4724:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4724
,I/ActivityManager(  893): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5156 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,W/ActivityThread( 5156): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  893): Killing 4774:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4774,
,I/ActivityManager(  893): Killing 4799:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4799
,I/ActivityManager(  893): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5194 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a,
,I/ActivityManager(  893): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5218 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 4662:com.htc.task/u0a72 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4662
,I/ActivityManager(  893): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5264 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  893): Killing 4913:com.htc.task.gtask/u0a69 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4913,
,I/ActivityManager(  893): Killing 4841:com.htc.android.mail:sync/u0a65 (adj 15): empty #18,
,I/ActivityManager(  893): Recipient 4841
,I/ActivityManager(  893): Killing 3572:com.htc.sense.mms/u0a67 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 3572
,W/ActivityManager(  893): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  893): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,I/ActivityManager(  893): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5306 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/jxcore-log( 4503): Bluetooth turned on
I/jxcore-log( 4503): 
,I/jxcore-log( 4503): WiFi turned off
I/jxcore-log( 4503): 
,I/jxcore-log( 4503): WiFi turned on,
,I/jxcore-log( 4503): 
I/ActivityManager(  893): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5337 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=5358 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,I/ActivityManager(  893): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5396 uid=10036 gids={50036, 9997, 3002, 3001} abi=armeabi-v7a,
,I/ActivityManager(  893): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/com.htc.videohub.engine.LiteLRBroadcastReceiver: pid=5424 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 5017:com.htc.updater/u0a88 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 5017
,I/ActivityManager(  893): Killing 4947:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4947
,I/ActivityManager(  893): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5467 uid=10080 gids={50080, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  893): Killing 4990:com.htc.sdm/u0a82 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 4990
,I/ActivityManager(  893): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5492 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  893): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/jxcore-log( 4503): No internet connection
I/jxcore-log( 4503): 
,W/ActivityManager(  893): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found,
,W/ActivityManager(  893): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  893): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/ActivityManager(  893): Killing 4871:com.google.android.music:main/u0a167 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 4871
,I/ActivityManager(  893): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5552 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/ActivityManager(  893): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5585 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5621 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5650 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 5069:com.htc.backup/u0a118 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 5069,
,I/ActivityManager(  893): Killing 5047:com.google.android.partnersetup/u0a28 (adj 15): empty #18
,I/ActivityManager(  893): Recipient 5047
,I/jxcore-log( 4503): No internet connection
I/jxcore-log( 4503): 
,I/ActivityManager(  893): Killing 5091:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 5091
,W/ActivityThread( 5621): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  893): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5687 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  893): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5709 uid=10082 gids={50082, 9997, 5001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 3810:com.htc.cs.dm/u0a105 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 3810,
,I/ActivityManager(  893): Killing 5218:com.google.android.apps.docs/u0a107 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 5218,
,I/ActivityManager(  893): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5741 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 4503): No internet connection
I/jxcore-log( 4503): 
,I/ActivityManager(  893): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=5786 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a,
,I/ActivityManager(  893): Killing 5156:com.google.android.gms:car/u0a25 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 5156
,W/ActivityManager(  893): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,I/ActivityManager(  893): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5830 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 5467:com.google.android.setupwizard/u0a80 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 5467
,I/ActivityManager(  893): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 1998): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  893): Killing 5396:com.htc.widget.hmsproc3/u0a36 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 5396
,I/ActivityManager(  893): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5893 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/jxcore-log( 4503): WiFi,
I/jxcore-log( 4503): 
,W/ActivityThread( 5893): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/jxcore-log( 4503): Response status code was: 200,
I/jxcore-log( 4503): 
I/jxcore-log( 4503): ****TEST TOOK:  9274  ms ****
I/jxcore-log( 4503): 
I/jxcore-log( 4503): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4503): 
,I/ActivityManager(  893): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg,
I/ActivityManager(  893): Killing 4503:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  893): Recipient 4503
,W/ActivityManager(  893): Force removing ActivityRecord{367918ca u0 com.example.hello/.MainActivity t27}: app died, no saved state,
,W/ActivityManager(  893): Spurious death for ProcessRecord{323fe613 4503:com.example.hello/u0a380}, curProc for 4503: null
,I/ActivityManager(  893): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/ActivityManager(  893): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5944 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  893): Killing 5424:com.htc.videocenter/u0a91 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 5424,
,I/ActivityManager(  893): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5975 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5999 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a,
,E/ActivityManager(  893): App crashed! Process: com.google.android.gms
,I/ActivityManager(  893): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6117 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  893): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
,I/ActivityManager(  893): Killing 5650:com.htc.android.mail:sync/u0a65 (adj 15): empty #17,
,I/ActivityManager(  893): Recipient 5650
,I/ActivityManager(  893): Recipient 5999
,W/ActivityManager(  893): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity,
W/ActivityManager(  893): android.os.DeadObjectException
W/ActivityManager(  893): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  893): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  893): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
W/ActivityManager(  893): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
W/ActivityManager(  893): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
W/ActivityManager(  893): 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:1327)
W/ActivityManager(  893): 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:2989)
W/ActivityManager(  893): 	at com.android.server.am.ActivityStackSupervisor.attachApplicationLocked(ActivityStackSupervisor.java:550)
W/ActivityManager(  893): 	at com.android.server.am.ActivityManagerService.attachApplicationLocked(ActivityManagerService.java:6576)
W/ActivityManager(  893): 	at com.android.server.am.ActivityManagerService.attachApplication(ActivityManagerService.java:6638)
W/ActivityManager(  893): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:486)
W/ActivityManager(  893): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/ActivityManager(  893): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  893): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=6136 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/ActivityManager(  893): Spurious death for ProcessRecord{17952538 6136:com.google.android.apps.docs/u0a107}, curProc for 5999: null
,E/ActivityManager(  893): App crashed! Process: com.google.android.youtube
I/ActivityManager(  893): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6163 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  893): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1998): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  893): Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/.TimeChangedReceiver: pid=6190 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/ActivityManager(  893): App crashed! Process: com.android.documentsui,
,W/ActivityManager(  893): Can't addPackageDependency on system process
,I/ActivityManager(  893): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=6224 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a
,I/ActivityManager(  893): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=6242 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a,
,E/ActivityManager(  893): App crashed! Process: com.google.process.gapps
,I/ActivityManager(  893): Killing 5358:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  893): Recipient 5358
,I/ActivityManager(  893): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0,


motorola-Nexus 6: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  822): Start proc 2101:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
I/ActivityManager(  822): Start proc 2127:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  822): Start proc 2153:com.motorola.android.buacontactadapter/u0a88 for broadcast com.motorola.android.buacontactadapter/.BuaReceiver
I/ActivityManager(  822): Start proc 2174:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  822): Start proc 2208:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  822): Start proc 2250:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
,I/ActivityManager(  822): Displayed com.example.hello/.MainActivity: +408ms (total +8s111ms)
,I/ActivityManager(  822): Start proc 2318:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,W/jxcore-log( 2250): Initializing JXcore engine
W/jxcore-log( 2250): JXcore engine is ready
,W/jxcore-log( 2250): Starting JXcore engine
,W/jxcore-log( 2250): Platform android
W/jxcore-log( 2250): 
W/jxcore-log( 2250): Process ARCH arm
W/jxcore-log( 2250): 
,I/jxcore-log( 2250): JXcore Cordova bridge is ready!
I/jxcore-log( 2250): 
W/jxcore-log( 2250): JXcore engine is started
,E/jxcore-log( 2250): >> motorola-Nexus 6
E/jxcore-log( 2250): 
,I/jxcore-log( 2250): Total memory 3113791488
I/jxcore-log( 2250): 
,I/jxcore-log( 2250): Free memory 1229877248
I/jxcore-log( 2250): 
,I/jxcore-log( 2250): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2250): 
I/jxcore-log( 2250): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2250): 
,I/jxcore-log( 2250): userPath [ 'www' ]
I/jxcore-log( 2250): 
,I/jxcore-log( 2250): Size 1440 2392
I/jxcore-log( 2250): 
,I/jxcore-log( 2250): Screen Brightness 82
I/jxcore-log( 2250): 
,E/jxcore-log( 2250): Dummy Error Log.
E/jxcore-log( 2250): 
,I/ActivityManager(  822): Start proc 2357:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,I/ActivityManager(  822): Start proc 2378:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/jxcore-log( 2250): getBuffer is called!!!!
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Start proc 2412:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,I/ActivityManager(  822): Start proc 2444:com.android.keychain/1000 for service com.android.keychain/.KeyChainService
,I/ActivityManager(  822): Start proc 2467:com.google.android.dialer/u0a13 for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver
,I/ActivityManager(  822): Killing 1457:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  822): Killing 1909:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2492:com.motorola.motocit/u0a2 for broadcast com.motorola.motocit/.CQATestBootReceiver
,I/ActivityManager(  822): Start proc 2509:com.android.providers.calendar/u0a3 for broadcast com.android.providers.calendar/.CalendarReceiver
,I/ActivityManager(  822): Start proc 2531:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.BootCompletedReceiver
,I/ActivityManager(  822): Killing 1999:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2037:com.android.cellbroadcastreceiver/u0a4 (adj 15): empty #18
,I/ActivityManager(  822): Killing 2019:com.verizon.omadm/u0a93 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2563:com.google.android.onetimeinitializer/u0a15 for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver
,I/ActivityManager(  822): Killing 1366:com.android.printspooler/u0a81 (adj 15): empty #17,
,I/ActivityManager(  822): Killing 2101:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2127:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2587:com.android.managedprovisioning/u0a17 for broadcast com.android.managedprovisioning/.BootReminder
,I/ActivityManager(  822): Killing 2174:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2208:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  822): Killing 1540:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2609:com.android.settings/1000 for broadcast com.android.settings/.sim.SimBootReceiver
,I/ActivityManager(  822): Start proc 2631:org.simalliance.openmobileapi.service/u0a23 for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver
,I/jxcore-log( 2250): Bluetooth turned on
I/jxcore-log( 2250): 
,I/jxcore-log( 2250): WiFi turned off
I/jxcore-log( 2250): 
,I/jxcore-log( 2250): WiFi turned on
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Start proc 2651:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,I/ActivityManager(  822): Start proc 2669:org.simalliance.openmobileapi.service:remote/u0a23 for service org.simalliance.openmobileapi.service/.SmartcardService
,I/ActivityManager(  822): Start proc 2686:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
I/ActivityManager(  822): Killing 2378:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2412:com.google.android.talk/u0a61 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2732:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/jxcore-log( 2250): No internet connection
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Killing 2444:com.android.keychain/1000 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 2767:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/ActivityManager(  822): Start proc 2793:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  822): Killing 2467:com.google.android.dialer/u0a13 (adj 15): empty #17
,I/jxcore-log( 2250): No internet connection
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Start proc 2821:com.qualcomm.telephony/1000 for broadcast com.qualcomm.atfwd/.AtFwdAutoboot
,I/ActivityManager(  822): Start proc 2843:com.qualcomm.telephony/1001 for broadcast org.codeaurora.ims/.ImsServiceAutoboot
,I/ActivityManager(  822): Killing 2357:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2318:com.android.vending/u0a19 (adj 15): empty #17
,I/jxcore-log( 2250): No internet connection,
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,I/ActivityManager(  822): Resuming delayed broadcast
,I/ActivityManager(  822): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,I/ActivityManager(  822): Resuming delayed broadcast
,I/ActivityManager(  822): Start proc 2919:com.google.android.youtube/u0a86 for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
,I/jxcore-log( 2250): No internet connection
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Start proc 2941:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService
,I/ActivityManager(  822): Killing 2492:com.motorola.motocit/u0a2 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3064:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver
,I/jxcore-log( 2250): No internet connection
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Start proc 3112:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.FitnessBootReceiver
,I/ActivityManager(  822): Start proc 3132:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  822): Killing 2531:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3156:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver
,I/ActivityManager(  822): Killing 1857:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/jxcore-log( 2250): No internet connection
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Start proc 3193:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,I/ActivityManager(  822): Start proc 3218:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver
,I/ActivityManager(  822): Killing 2563:com.google.android.onetimeinitializer/u0a15 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3267:com.google.android.apps.plus/u0a74 for service com.google.android.apps.plus/.service.EsSyncAdapterService
,D/ActivityThread( 3218): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  822): Killing 2587:com.android.managedprovisioning/u0a17 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3323:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,I/jxcore-log( 2250): WiFi
I/jxcore-log( 2250): 
,W/ActivityManager(  822): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/jxcore-log( 2250): Response status code was: 200
I/jxcore-log( 2250): 
I/jxcore-log( 2250): ****TEST TOOK:  13256  ms ****
I/jxcore-log( 2250): 
I/jxcore-log( 2250): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2250): 
,I/ActivityManager(  822): Start proc 3380:com.google.android.apps.messaging/u0a75 for broadcast com.google.android.apps.messaging/.receiver.BootAndPackageReplacedReceiver
,I/ActivityManager(  822): Killing 1399:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3419:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 2250:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/ActivityManager(  822): Force removing ActivityRecord{1485364b u0 com.example.hello/.MainActivity t20}: app died, no saved state
,I/ActivityManager(  822): Start proc 3437:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ActivityManager(  822): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  822): Spurious death for ProcessRecord{291316ea 2250:com.example.hello/u0a272}, curProc for 2250: null
,I/ActivityManager(  822): Killing 2609:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  822): Waited long enough for: ServiceRecord{3f85d412 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,--------- beginning of crash
,I/ActivityManager(  822): Killing 2631:org.simalliance.openmobileapi.service/u0a23 (adj 15): empty #17
,I/ActivityManager(  822): Process com.google.android.apps.books (pid 3437) has died
W/ActivityManager(  822): Scheduling restart of crashed service com.google.android.apps.books/.service.SyncService in 1000ms
,I/ActivityManager(  822): Start proc 3538:com.google.android.apps.genie.geniewidget/u0a80 for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService


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
--------- beginning of main
,I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1017): mDVFSHelper.acquire()
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6037 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 1480): updateVisibility : ActivityRecord{23b30682 token=android.os.BinderProxy@3880e644 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 6037): Added TimaKeyStore provider
V/ActivityManager( 1017): Display changed displayId=0
V/ActivityThread( 1480): updateVisibility : ActivityRecord{23b30682 token=android.os.BinderProxy@3880e644 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,I/ActivityManager( 1017): Displayed Component not be shown by security: +742ms
,W/ActivityManager( 1017): mDVFSHelper.release()
,W/jxcore-log( 6037): Initializing JXcore engine
W/jxcore-log( 6037): JXcore engine is ready
,W/jxcore-log( 6037): Starting JXcore engine
,W/jxcore-log( 6037): Platform android
W/jxcore-log( 6037): 
W/jxcore-log( 6037): Process ARCH arm
W/jxcore-log( 6037): 
,I/jxcore-log( 6037): JXcore Cordova bridge is ready!
I/jxcore-log( 6037): 
,W/jxcore-log( 6037): JXcore engine is started
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6085 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6085): Added TimaKeyStore provider
,E/jxcore-log( 6037): >> samsung-SM-A300FU
E/jxcore-log( 6037): 
,I/jxcore-log( 6037): Total memory 1451114496
I/jxcore-log( 6037): 
,I/jxcore-log( 6037): Free memory 19107840
I/jxcore-log( 6037): 
I/jxcore-log( 6037): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6037): 
I/jxcore-log( 6037): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6037): 
,I/jxcore-log( 6037): userPath [ 'www' ]
,I/jxcore-log( 6037): 
,I/jxcore-log( 6037): Size 540 960
I/jxcore-log( 6037): 
,I/jxcore-log( 6037): Screen Brightness 160
I/jxcore-log( 6037): 
,E/jxcore-log( 6037): Dummy Error Log.
E/jxcore-log( 6037): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6037): getBuffer is called!!!!
I/jxcore-log( 6037): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5291:com.google.android.gm/u0a99 (adj 15): empty #31
,I/jxcore-log( 6037): Bluetooth turned on
I/jxcore-log( 6037): 
,I/jxcore-log( 6037): WiFi turned off
I/jxcore-log( 6037): 
,W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6037, uid=10345 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 6037): WiFi turned on
I/jxcore-log( 6037): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6125 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6125): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6147 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 4940:com.google.android.gms:car/u0a11 (adj 15): empty #31
,D/ActivityThread( 6147): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Killing 4180:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6172 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,D/ActivityThread( 6172): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Killing 5273:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
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
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
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
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6190 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 6190): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityThread( 6190): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/jxcore-log( 6037): No internet connection
I/jxcore-log( 6037): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6216 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 6216): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1017): Killing 5362:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6235 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5694:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityThread( 6235): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6250 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,D/ActivityThread( 6250): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6266 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5713:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/ActivityThread( 6266): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5745:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/ActivityThread( 6250): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6282 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5375:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,D/ActivityThread( 6282): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5793:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6300 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread( 6300): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6315 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 5813:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,D/ActivityThread( 6315): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6338 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,I/jxcore-log( 6037): No internet connection
I/jxcore-log( 6037): 
,D/ActivityThread( 6338): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5854:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 5156:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6355 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6355): Added TimaKeyStore provider
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6373 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3488:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityThread( 6373): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6440 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 5879:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,D/ActivityThread( 6440): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5901:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6037): No internet connection,
I/jxcore-log( 6037): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6461 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 6461): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityThread( 6461): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/jxcore-log( 6037): No internet connection
I/jxcore-log( 6037): 
,I/jxcore-log( 6037): No internet connection
I/jxcore-log( 6037): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6037): No internet connection
I/jxcore-log( 6037): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/jxcore-log( 6037): WiFi
I/jxcore-log( 6037): 
,I/jxcore-log( 6037): Response status code was: 200
I/jxcore-log( 6037): 
,I/jxcore-log( 6037): ****TEST TOOK:  12261  ms ****
I/jxcore-log( 6037): 
I/jxcore-log( 6037): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6037): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6037:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1017): Force removing ActivityRecord{38ddabaa u0 com.example.hello/.MainActivity t19}: app died, no saved state
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,W/ActivityManager( 1017): Spurious death for ProcessRecord{2c844357 6037:com.example.hello/u0a345}, curProc for 6037: null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1017): handle home activity for 0
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6579 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6579): Added TimaKeyStore provider
,I/ActivityManager( 1017): Displayed Component not be shown by security: +273ms (total +27s184ms)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/ActivityManager( 1017): Killing 5334:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6598 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/ActivityThread( 6598): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5665:com.android.defcontainer/u0a3 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 5049:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6616 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityThread( 6616): Added TimaKeyStore provider


HTC-HTC One M8s: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  970): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4770 uid=10035 gids={50035, 9997} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4794 uid=10076 gids={50076, 9997} abi=arm64-v8a
I/ActivityManager(  970): Killing 4025:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4025
I/ActivityManager(  970): Waited long enough for: ServiceRecord{222b9b2a u0 com.htc.HTCSpeaker/.NGFService}
I/ActivityManager(  970): Killing 4055:com.htc.htccupd/u0a13 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4055
I/ActivityManager(  970): Killing 4126:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4126
I/ActivityManager(  970): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4813 on display 0
I/ActivityManager(  970): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4841 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  970): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=4863 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  970): Killing 4149:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4149
,I/ActivityManager(  970): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4890 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  970): Killing 3972:com.htc.cs.dm/u0a99 (adj 15): empty #17
I/ActivityManager(  970): Recipient 3972
I/ActivityManager(  970): Killing 4173:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4173
I/ActivityManager(  970): Killing 4196:com.android.smith/1000 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4196
I/ActivityManager(  970): Killing 4254:com.google.android.gms:car/u0a24 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4254
I/ActivityManager(  970): Start proc com.htc.showme for broadcast com.htc.showme/.update.MobileNetworkTurnOnReceiver: pid=4942 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  970): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=4964 uid=10009 gids={50009, 9997, 5001, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  970): Killing 4217:com.android.vending/u0a72 (adj 15): empty #17
I/ActivityManager(  970): Recipient 4217
I/ActivityManager(  970): Displayed com.example.hello/.MainActivity: +1s405ms
W/jxcore-log( 4841): Initializing JXcore engine
W/jxcore-log( 4841): JXcore engine is ready
W/jxcore-log( 4841): Starting JXcore engine
I/ActivityManager(  970): Killing 4376:com.google.android.talk/u0a112 (adj 15): empty #17
W/jxcore-log( 4841): Platform android
W/jxcore-log( 4841): 
W/jxcore-log( 4841): Process ARCH arm
W/jxcore-log( 4841): 
I/ActivityManager(  970): Recipient 4376
I/jxcore-log( 4841): JXcore Cordova bridge is ready!
I/jxcore-log( 4841): 
W/jxcore-log( 4841): JXcore engine is started
I/ActivityManager(  970): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=5018 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
E/jxcore-log( 4841): >> HTC-HTC One M8s
E/jxcore-log( 4841): 
I/jxcore-log( 4841): Total memory 1931808768
I/jxcore-log( 4841): 
I/jxcore-log( 4841): Free memory 87429120
I/jxcore-log( 4841): 
I/jxcore-log( 4841): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4841): 
I/jxcore-log( 4841): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4841): 
I/jxcore-log( 4841): userPath [ 'www' ]
I/jxcore-log( 4841): 
I/jxcore-log( 4841): Size 1080 1776
I/jxcore-log( 4841): 
I/jxcore-log( 4841): Screen Brightness 142
I/jxcore-log( 4841): 
E/jxcore-log( 4841): Dummy Error Log.
E/jxcore-log( 4841): 
,I/ActivityManager(  970): Killing 3573:com.android.defcontainer/u0a15 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 3573
,I/ActivityManager(  970): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5053 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/jxcore-log( 4841): getBuffer is called!!!!
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5076 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5100 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Killing 4416:com.google.android.youtube/u0a176 (adj 15): empty #17,
,I/ActivityManager(  970): Recipient 4416
,I/ActivityManager(  970): Killing 4505:com.google.android.gm/u0a106 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4505
,W/ActivityThread( 5076): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  970): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5139 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Killing 4613:com.htc.club/u0a181 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4613,
,I/ActivityManager(  970): Killing 4734:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17,
,I/ActivityManager(  970): Recipient 4734
,I/ActivityManager(  970): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5171 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4280): Failed to find provider info for com.google.android.wearable.settings,
,I/ActivityManager(  970): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5206 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5227 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5249 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
,W/ActivityThread( 5227): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  970): Killing 4770:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4770,
,I/ActivityManager(  970): Killing 4794:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4794
,I/ActivityManager(  970): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5326 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  970): Killing 4545:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4545
,I/ActivityManager(  970): Waited long enough for: ServiceRecord{dac939 u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService},
,I/ActivityManager(  970): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5355 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager(  970): Killing 4863:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4863
,I/jxcore-log( 4841): Bluetooth turned on
I/jxcore-log( 4841): 
,I/jxcore-log( 4841): WiFi turned off
I/jxcore-log( 4841): 
,I/jxcore-log( 4841): WiFi turned on
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Killing 4890:com.htc.task/u0a69 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4890,
,I/ActivityManager(  970): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5409 uid=10035 gids={50035, 9997} abi=arm64-v8a
,I/ActivityManager(  970): Killing 4942:com.htc.showme/u0a81 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4942,
,I/ActivityManager(  970): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5431 uid=10076 gids={50076, 9997} abi=arm64-v8a
,I/ActivityManager(  970): Killing 4964:com.htc.sense.browser/u0a9 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4964
,I/jxcore-log( 4841): No internet connection,
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5454 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  970): Killing 4578:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4578
,I/ActivityManager(  970): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5477 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a,
I/ActivityManager(  970): Killing 5018:com.htc.contacts/u0a38 (adj 15): empty #17,
,I/ActivityManager(  970): Recipient 5018
,I/ActivityManager(  970): Waited long enough for: ServiceRecord{efcf151 u0 com.google.android.gms/.config.ConfigFetchService}
,I/ActivityManager(  970): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5508 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  970): Killing 5076:com.google.android.music:main/u0a159 (adj 15): empty #17,
,I/jxcore-log( 4841): No internet connection
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Recipient 5076
,I/ActivityManager(  970): Killing 5139:com.google.android.setupwizard/u0a77 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 5139
,I/ActivityManager(  970): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5530 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5553 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5581 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,I/ActivityManager(  970): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5603 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  970): Killing 5206:com.google.android.apps.magazines/u0a161 (adj 15): empty #17,
I/jxcore-log( 4841): No internet connection
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Recipient 5206
,I/ActivityManager(  970): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5647 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Killing 5326:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 5326,
,I/ActivityManager(  970): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5682 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Killing 4699:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4699
,I/jxcore-log( 4841): No internet connection,
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Killing 5355:com.google.android.apps.plus/u0a167 (adj 15): empty #17,
,I/ActivityManager(  970): Recipient 5355,
,I/ActivityManager(  970): Killing 5249:com.htc.sense.news/u0a74 (adj 15): empty #17,
,W/ActivityThread( 5647): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  970): Recipient 5249
,I/ActivityManager(  970): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5726 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5754 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/ActivityManager(  970): Killing 5409:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 5409,
,I/ActivityManager(  970): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5787 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,I/jxcore-log( 4841): No internet connection
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5813 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Killing 5431:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 5431,
,I/ActivityManager(  970): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5839 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Killing 5171:com.google.android.talk/u0a112 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 5171
,I/ActivityManager(  970): Killing 5477:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 5477
,I/ActivityManager(  970): Killing 5508:com.htc.backupreset/1000 (adj 15): empty #17
,I/jxcore-log( 4841): No internet connection,
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Recipient 5508,
,I/ActivityManager(  970): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5867 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/ActivityManager(  970): Killing 5553:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17,
,I/ActivityManager(  970): Recipient 5553
,I/ActivityManager(  970): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5905 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Killing 5530:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,I/ActivityManager(  970): Recipient 5530,
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4105): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  970): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4105): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  970): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5951 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/ActivityManager(  970): Killing 5454:com.htc.task/u0a69 (adj 15): empty #17
,I/jxcore-log( 4841): WiFi
I/jxcore-log( 4841): 
,I/ActivityManager(  970): Recipient 5454
,I/jxcore-log( 4841): Response status code was: 200
,I/jxcore-log( 4841): 
I/jxcore-log( 4841): ****TEST TOOK:  12566  ms ****
I/jxcore-log( 4841): 
I/jxcore-log( 4841): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4841): 
,W/ActivityThread( 5951): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  970): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5983 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ActivityThread( 5983): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  970): Killing 4647:com.htc.bgp/u0a11 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 4647,
,I/ActivityManager(  970): Killing 5100:com.htc.mobiledata/u0a46 (adj 15): empty #17
,I/ActivityManager(  970): Recipient 5100
,I/ActivityManager(  970): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6034 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/ActivityManager(  970): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,I/ActivityManager(  970): Killing 4841:com.example.hello/u0a373 (adj 0): stop com.example.hello
,I/ActivityManager(  970): Recipient 4841
,W/ActivityManager(  970): Force removing ActivityRecord{138c45 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  970): Force stopping com.example.hello appid=10373 user=0: pkg removed,
,W/ActivityManager(  970): Spurious death for ProcessRecord{57da539 4841:com.example.hello/u0a373}, curProc for 4841: null,
,E/ActivityManager(  970): App crashed! Process: com.google.android.gms
,I/ActivityManager(  970): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6085 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  970): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 6034 on display 0
,E/ActivityManager(  970): TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4052, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) }
,W/ActivityManager(  970): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  970): android.os.TransactionTooLargeException
W/ActivityManager(  970): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  970): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  970): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
W/ActivityManager(  970): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
W/ActivityManager(  970): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
W/ActivityManager(  970): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2014)
W/ActivityManager(  970): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1552)
W/ActivityManager(  970): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2536)
W/ActivityManager(  970): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:1065)
W/ActivityManager(  970): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:963)
W/ActivityManager(  970): 	,at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6882)
W/ActivityManager(  970): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:518)
W/ActivityManager(  970): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/ActivityManager(  970): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  970): Recipient 6034
,I/ActivityManager(  970): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=6110 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,W/ActivityManager(  970): Spurious death for ProcessRecord{417ec08 6110:com.google.android.apps.docs/u0a101}, curProc for 6034: null
,I/ActivityManager(  970): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6136 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  970): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6164 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/ActivityManager(  970): Killing 5603:com.htc.android.mail:sync/u0a62 (adj 15): empty #17


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  961): Waited long enough for: ServiceRecord{435e35b0 u0 com.lge.slideaside/.MainService}
I/ActivityManager(  961): Killing 3328:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2}
,I/ActivityManager(  961): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3859
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
V/ActivityManager(  961): Moving to PAUSING: ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  961): resumeTopActivityLocked: Pausing null
V/ActivityManager(  961): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  961): setFocusedStack: mFocusedStack=ActivityStack{43481f40 stackId=1, 2 tasks}
D/ActivityManager(  961): allPausedActivitiesComplete: r=ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
I/ActivityManager(  961): startService SlideAside
V/ActivityManager(  961): Moving to PAUSED: ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Restarting ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
I/ActivityManager(  961): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3877 uid=10311 gids={50311, 3003, 3001, 3002}
V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3} (starting new instance)
I/ActivityManager( 3877): Timeline: Activity_idle id: android.os.BinderProxy@42a98258 time:43420
I/ActivityManager(  961): Displayed com.example.hello/.MainActivity: +454ms
I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3} time:43740
D/ActivityManager(  961): no-history finish of ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  961): Finishing activity token=Token{434fbc40 ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  961): Moving to FINISHING: ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  961): Moving to STOPPING: ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  961): Moving to STOPPED: ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,W/jxcore-log( 3877): Initializing JXcore engine
,W/jxcore-log( 3877): JXcore engine is ready
,W/jxcore-log( 3877): Starting JXcore engine
,W/jxcore-log( 3877): Platform android
W/jxcore-log( 3877): 
,W/jxcore-log( 3877): Process ARCH arm
W/jxcore-log( 3877): 
,I/jxcore-log( 3877): JXcore Cordova bridge is ready!
I/jxcore-log( 3877): 
,W/jxcore-log( 3877): JXcore engine is started
,E/jxcore-log( 3877): >> LGE-LG-D802
E/jxcore-log( 3877): 
,I/jxcore-log( 3877): Total memory 1943035904
I/jxcore-log( 3877): 
I/jxcore-log( 3877): Free memory 462172160
I/jxcore-log( 3877): 
I/jxcore-log( 3877): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): userPath [ 'www' ]
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): Size 1080 1776
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): Screen Brightness 255
I/jxcore-log( 3877): 
,E/jxcore-log( 3877): Dummy Error Log.
E/jxcore-log( 3877): 
,I/jxcore-log( 3877): getBuffer is called!!!!
I/jxcore-log( 3877): 
,I/ActivityManager(  961): Killing 3394:com.google.android.gm/u0a68 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3877): Bluetooth turned on
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): WiFi turned off
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): WiFi turned on
I/jxcore-log( 3877): 
,I/ActivityManager(  961): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=3958 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  961): Killing 3271:com.google.android.music:main/u0a107 (adj 15): empty #17
,F/ActivityManager(  961): Service ServiceRecord{4346f4a8 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43529440 3271:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  961): Service ServiceRecord{432f50d0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43529440 3271:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  961): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4012 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  961): Killing 3193:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  961): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4029 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/ActivityManager(  961): Killing 2972:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  961): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4064 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/ActivityManager(  961): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4078 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  961): Killing 3732:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  961): Killing 3760:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
,I/jxcore-log( 3877): No internet connection
I/jxcore-log( 3877): 
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3877): No internet connection
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): No internet connection
I/jxcore-log( 3877): 
,I/ActivityManager(  961): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4160 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  961): Killing 3560:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 2 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}
,I/jxcore-log( 3877): No internet connection
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): No internet connection
I/jxcore-log( 3877): 
,E/ActivityThread(  961): Failed to find provider info for com.lge.ims.provisioning
,I/jxcore-log( 3877): WiFi
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): Response status code was: 200
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): ****TEST TOOK:  11332  ms ****
I/jxcore-log( 3877): 
,I/jxcore-log( 3877): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3877): 
,I/ActivityManager(  961): Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
I/ActivityManager(  961): Killing 3877:com.example.hello/u0a311 (adj 0): stop com.example.hello
W/ActivityManager(  961): Force removing ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3}: app died, no saved state
V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{42e83320 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{43481f40 stackId=1, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  961): moveHomeStack:
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e1d5d0 stackId=0, 1 tasks}
,V/ActivityManager(  961): Moving to RESUMED: ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  961): resumeTopActivityLocked: Resumed ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42e1d5d0 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1}
V/ActivityManager(  961): Moving to DESTROYING: ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
I/ActivityManager(  961): Force stopping com.example.hello appid=10311 user=0: pkg removed
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e1d5d0 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4309 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,I/ActivityManager(  961): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4321 uid=10090 gids={50090}
,V/ActivityManager(  961): Moving to DESTROYED: ActivityRecord{433d3fa0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e1d5d0 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Killing 3579:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e1d5d0 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4343 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  961): Killing 3786:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e1d5d0 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Killing 3593:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  961): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4360 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e1d5d0 stackId=0, 1 tasks}
D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  961): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4383 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  961): Killing 3808:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  961): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e1d5d0 stackId=0, 1 tasks}
,D/ActivityManager(  961): resumeTopActivityLocked: Top activity resumed ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@42a92ea8 time:57211
,I/ActivityManager(  961): Timeline: Activity_windows_visible id: ActivityRecord{42deb230 u0 com.lge.launcher2/.Launcher t1} time:57211


```

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.example.hello code:0 
child process exited with code 0 on device 4db5c8cc 
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  830): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6034 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
D/ActivityThread( 6034): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  830): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6054 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  830): Killing 4910:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
D/ActivityThread( 6054): Added TimaKeyStore provider
I/ActivityManager(  830): Killing 5233:com.wsomacp/u0a25 (adj 15): bgCount ##41
I/ActivityManager(  830): Killing 5330:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
V/ActivityManager(  830): Display changed displayId=0
I/ActivityManager(  830): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  830): mDVFSHelper.acquire()
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  830): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6096 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 6096): Added TimaKeyStore provider
V/ActivityManager(  830): Display changed displayId=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  830): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6129 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityThread( 6129): Added TimaKeyStore provider
W/ActivityManager(  830): getTasks: caller 10086 does not hold GET_TASKS; limiting output
W/ActivityManager(  830): getTasks: caller 10086 does not hold GET_TASKS; limiting output
I/ActivityManager(  830): Killing 5372:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
W/ActivityThread( 6129): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  830): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6179 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/ActivityThread( 6179): Added TimaKeyStore provider
D/ActivityManager(  830): post active user change for 0
W/ActivityManager(  830): mDVFSHelper.release()
I/ActivityManager(  830): Killing 5253:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
I/ActivityManager(  830): Process ACMS.Process (pid 5965)(adj 0) has died(79,586)
W/ActivityThread( 4263): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=6227 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/jxcore-log( 6096): Initializing JXcore engine
W/jxcore-log( 6096): JXcore engine is ready
,W/jxcore-log( 6096): Starting JXcore engine
,D/ActivityThread( 6227): Added TimaKeyStore provider
,W/jxcore-log( 6096): Platform android
W/jxcore-log( 6096): 
W/jxcore-log( 6096): Process ARCH arm
W/jxcore-log( 6096): 
,I/jxcore-log( 6096): JXcore Cordova bridge is ready!
I/jxcore-log( 6096): 
,W/jxcore-log( 6096): JXcore engine is started
,E/jxcore-log( 6096): >> samsung-SM-G900F
E/jxcore-log( 6096): 
,I/jxcore-log( 6096): Total memory 1787449344
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): Free memory 54599680
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6096): 
I/jxcore-log( 6096): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): Size 1080 1920
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): Screen Brightness 134
I/jxcore-log( 6096): 
,E/jxcore-log( 6096): Dummy Error Log.
E/jxcore-log( 6096): 
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=6263 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6263): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 5293:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=6284 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5175:com.google.android.music:main/u0a126 (adj 15): bgCount ##41
,I/jxcore-log( 6096): getBuffer is called!!!!
I/jxcore-log( 6096): 
,D/ActivityThread( 6284): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6309 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5433:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/ActivityThread( 6309): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6326 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5454:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,D/ActivityThread( 6326): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 5470:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=6356 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6356): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=6373 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6373): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=6395 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6395): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 4816:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6426 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6426): Added TimaKeyStore provider
,W/ActivityThread( 6426): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6474 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5122:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,D/ActivityThread( 6474): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6493): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 5596:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/ActivityThread( 6426): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1cb7f0e2 that was originally bound here
E/ActivityThread( 6426): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1cb7f0e2 that was originally bound here
E/ActivityThread( 6426): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 6426): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 6426): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 6426): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 6426): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6426): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 6426): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6426): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6426): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6426): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 6426): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 6426): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 6426): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 6426): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 6426): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 6426): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 6426): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 6426): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 6426): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6426): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6426): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 6426): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6426): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6426): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6426): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager(  830): Killing 5616:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6512 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5632:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,D/ActivityThread( 6512): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 4927:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6530 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6530): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=6547 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5353:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,D/ActivityThread( 6547): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 5021:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6567 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6567): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=6587 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5205:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/ActivityThread( 6587): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=6605 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5666:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/ActivityThread( 6605): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=6623 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,D/ActivityThread( 6623): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 5689:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/ActivityManager(  830): Process com.samsung.indexservice (pid 6605)(adj 11) has died(56,605)
,I/ActivityManager(  830): Killing 5731:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,W/ActivityManager(  830): Permission Denial: getCurrentUser() from pid=6096, uid=10374 requires android.permission.INTERACT_ACROSS_USERS
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6096): Bluetooth turned on
I/jxcore-log( 6096): 
,I/ActivityManager(  830): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6660 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 6096): WiFi turned off
I/jxcore-log( 6096): 
,W/ActivityManager(  830): Permission Denial: getCurrentUser() from pid=6096, uid=10374 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 6096): WiFi turned on
I/jxcore-log( 6096): 
,D/ActivityThread( 6660): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc tv.peel.smartremote for broadcast tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver: pid=6694 uid=10171 gids={50171, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/ActivityThread( 6694): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6731 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityThread( 6731): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6766 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,D/ActivityThread( 6766): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 5788:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/ActivityManager(  830): Killing 5765:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/ActivityManager(  830): Killing 5824:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,W/ActivityManager(  830): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/jxcore-log( 6096): No internet connection
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): No internet connection
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): No internet connection
I/jxcore-log( 6096): 
,I/ActivityManager(  830): Killing 5833:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/ActivityManager(  830): Waited long enough for: ServiceRecord{34cff3a1 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/jxcore-log( 6096): WiFi
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): Response status code was: 200
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): ****TEST TOOK:  9606  ms ****
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6096): 
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6945 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6945): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6984 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6984): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=7013 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7013): Added TimaKeyStore provider
,I/ActivityManager(  830): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  830): Killing 6096:com.example.hello/u0a374 (adj 0): stop com.example.hello
,I/ActivityManager(  830):   Force finishing activity ActivityRecord{3f9f8e43 u0 com.example.hello/.MainActivity t11}
,I/ActivityManager(  830): Force stopping com.example.hello appid=10374 user=0: pkg removed
,I/ActivityManager(  830): Killing 5851:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7058 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7058): Added TimaKeyStore provider
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7087 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 5877:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,D/ActivityThread( 7087): Added TimaKeyStore provider
,I/ActivityManager(  830): Killing 5944:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/ActivityManager(  830): Killing 5896:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  830): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  830): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7111 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  830): Killing 6014:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ActivityThread( 7111): Added TimaKeyStore provider


samsung-SM-A500FU: 
--------- beginning of main
D/ActivityThread( 3390): Added TimaKeyStore provider
--------- beginning of system
I/ActivityManager( 1016): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3411): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3433 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2677:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
D/ActivityThread( 3433): Added TimaKeyStore provider
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3462 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3462): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3499 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3499): Added TimaKeyStore provider
I/ActivityManager( 1016): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3517 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3517): Added TimaKeyStore provider
I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3532 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2812:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityThread( 3532): Added TimaKeyStore provider
D/ActivityThread( 3547): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 2832:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3575 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2851:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
I/ActivityManager( 1016): Killing 1582:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3585 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
D/ActivityThread( 3575): Added TimaKeyStore provider
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityThread( 3585): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3609 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3609): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3629 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3629): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3656 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
V/ActivityThread( 1489): updateVisibility : ActivityRecord{3ad4a2fd token=android.os.BinderProxy@29455070 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 3656): Added TimaKeyStore provider
V/ActivityThread( 1489): updateVisibility : ActivityRecord{3ad4a2fd token=android.os.BinderProxy@29455070 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Process com.sec.factory (pid 2548)(adj 0) has died(115,1089)
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3690 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2891:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 2921:com.policydm/1000 (adj 15): empty #31
,D/ActivityThread( 3690): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3725 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2942:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/ActivityThread( 3725): Added TimaKeyStore provider
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1016): Killing 2980:com.sec.factory.camera/1000 (adj 15): empty #31,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3759 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3759): Added TimaKeyStore provider
,I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3778 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3006:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s212ms
,W/ActivityManager( 1016): mDVFSHelper.release()
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 3778): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3802 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 3802): Added TimaKeyStore provider
,I/ActivityManager( 1016): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3821 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3079:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 3042:com.samsung.helphub/1000 (adj 15): empty #32
,D/ActivityThread( 3821): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3840 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/ActivityThread( 3840): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/ActivityManager( 1016): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3858 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3089:com.fmm.dm/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 3858): Added TimaKeyStore provider
,I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=3875 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Process com.android.email (pid 3585)(adj 11) has died(47,1129)
,D/ActivityThread( 3875): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=3891 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityThread( 3891): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3137:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,W/jxcore-log( 3656): Initializing JXcore engine
,W/jxcore-log( 3656): JXcore engine is ready
,W/jxcore-log( 3656): Starting JXcore engine
I/ActivityManager( 1016): Killing 2055:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=3914 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3154:com.sec.knox.foldercontainer/1000 (adj 15): empty #31,
,D/ActivityThread( 3914): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=3938 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3057:com.google.android.gms:car/u0a12 (adj 15): empty #31
,D/ActivityThread( 3938): Added TimaKeyStore provider
,W/jxcore-log( 3656): Platform android
W/jxcore-log( 3656): 
,W/jxcore-log( 3656): Process ARCH arm
W/jxcore-log( 3656): 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/jxcore-log( 3656): JXcore Cordova bridge is ready!
I/jxcore-log( 3656): 
,W/jxcore-log( 3656): JXcore engine is started
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=3960 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 10999ms
,W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 3778)(adj 0) has died(45,1130)
,D/ActivityThread( 3960): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3975 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,E/jxcore-log( 3656): >> samsung-SM-A500FU,
E/jxcore-log( 3656): 
,I/jxcore-log( 3656): Total memory 1983787008,
I/jxcore-log( 3656): 
I/jxcore-log( 3656): Free memory 46538752
I/jxcore-log( 3656): 
I/jxcore-log( 3656): execPath /data/data/com.example.hello/files/www/jxcore
,I/jxcore-log( 3656): 
I/jxcore-log( 3656): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3656): 
,I/jxcore-log( 3656): userPath [ 'rList-com.example.hello.MainActivity', 'www' ],
I/jxcore-log( 3656): 
,I/jxcore-log( 3656): Size 720 1280
I/jxcore-log( 3656): 
,I/jxcore-log( 3656): Screen Brightness 5
I/jxcore-log( 3656): 
,E/jxcore-log( 3656): Dummy Error Log.
E/jxcore-log( 3656): 
,D/ActivityThread( 3975): Added TimaKeyStore provider
,I/ActivityManager( 1016): Process com.android.exchange (pid 3821)(adj 13) has died(42,1130)
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3990 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 3173:com.fmm.ds/1000 (adj 15): empty #31
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 3990): Added TimaKeyStore provider
,I/ActivityManager( 1016): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4006 uid=1101 gids={41101, 9997} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2884:com.android.vending/u0a28 (adj 15): empty #31
,D/ActivityThread( 4006): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,I/ActivityManager( 1016): Killing 3195:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4036 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2269:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/ActivityThread( 4022): Added TimaKeyStore provider
,D/ActivityThread( 4036): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4057 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 3215:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4071 uid=10157 gids={50157, 9997} abi=armeabi-v7a,
,D/ActivityThread( 4057): Added TimaKeyStore provider
,D/ActivityThread( 4071): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 3656): getBuffer is called!!!!
I/jxcore-log( 3656): 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4092 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3254:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4104 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3275:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,D/ActivityThread( 4092): Added TimaKeyStore provider
,D/ActivityThread( 4104): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 2970:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=4127 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityThread( 4127): Added TimaKeyStore provider
,W/ActivityThread( 4057): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityThread( 4127): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager( 1016): Killing 3306:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/ActivityManager( 1016): Killing 3322:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 3290:com.wssnps/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4209 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 4209): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/ActivityManager( 1016): Killing 3358:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4244 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 4244): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1016): Killing 3390:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,E/ActivityThread( 4209): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@25ba5551 that was originally bound here
E/ActivityThread( 4209): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@25ba5551 that was originally bound here
E/ActivityThread( 4209): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 4209): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 4209): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 4209): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 4209): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 4209): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4209): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4209): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4209): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4209): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4209): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4209): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4209): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4209): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4209): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4209): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@1bdf2336
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4264 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 3341:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityThread( 4264): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityThread( 4244): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1016): Killing 3433:com.android.calendar/u0a135 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4301 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 3517:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,D/ActivityThread( 4301): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4322 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 4322): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1016): Killing 3547:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 3532:com.sec.android.app.camera/u0a139 (adj 15): empty #32
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
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
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
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
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4356 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 4356): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 4356): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = flipboard.app
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc flipboard.app for broadcast flipboard.app/flipboard.gcm.FlipboardGCMBroadcastReceiver: pid=4414 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 4414): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=3656, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 3656): Bluetooth turned on
I/jxcore-log( 3656): 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4480 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 3656): WiFi turned off,
I/jxcore-log( 3656): 
,W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=3656, uid=10174 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 3656): WiFi turned on
I/jxcore-log( 3656): 
,D/ActivityThread( 4480): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1016): retrieveServiceLocked(): component = flipboard.app/flipboard.gcm.FlipboardGCMIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = flipboard.app, destAppInfo.processName = flipboard.app
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4586 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/jxcore-log( 3656): No internet connection
I/jxcore-log( 3656): 
,D/ActivityThread( 4586): Added TimaKeyStore provider


```

####Node name: thali08
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/495261844451736/build_android/android_0_495261844451736.apk) to device 4325e43f protocol failure
- waiting for device -
rm: /data/local/tmp/android_0_495261844451736.apk: No such file or directory



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
I/ActivityManager(  906): Killing 2118:com.htc.contacts/u0a44 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2118
I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=2927 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  906): Killing 2558:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2558
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=2944 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  906): Killing 2570:com.htc.aurora/u0a49 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2570
I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2958 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
I/ActivityManager(  906): Killing 2584:com.htc.aurora:remote/u0a49 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2584
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2971
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3001 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=3032 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +355ms
I/ActivityManager(  906): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=3067 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/ActivityManager(  906): Killing 2600:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2600
I/ActivityManager(  906): Killing 2614:com.htc.musicenhancer/u0a53 (adj 15): empty #17
W/jxcore-log( 3001): Initializing JXcore engine
W/jxcore-log( 3001): JXcore engine is ready
W/jxcore-log( 3001): Starting JXcore engine
I/ActivityManager(  906): Recipient 2614
I/ActivityManager(  906): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3094 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 2627:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2627
W/jxcore-log( 3001): Platform android
W/jxcore-log( 3001): 
W/jxcore-log( 3001): Process ARCH arm
W/jxcore-log( 3001): 
I/ActivityManager(  906): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3111 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/jxcore-log( 3001): JXcore Cordova bridge is ready!
I/jxcore-log( 3001): 
W/jxcore-log( 3001): JXcore engine is started
I/ActivityManager(  906): Killing 2651:com.htc.video/u0a57 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2651
,I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3126 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,D/ActivityThread( 3111): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,E/jxcore-log( 3001): >> HTC-HTC Desire 820
E/jxcore-log( 3001): 
,I/jxcore-log( 3001): Total memory 1964650496
I/jxcore-log( 3001): 
I/jxcore-log( 3001): Free memory 664838144
I/jxcore-log( 3001): 
I/jxcore-log( 3001): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3001): 
,I/jxcore-log( 3001): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3001): 
,I/jxcore-log( 3001): userPath [ 'www' ]
I/jxcore-log( 3001): 
,I/jxcore-log( 3001): Size 720 1184
I/jxcore-log( 3001): 
I/jxcore-log( 3001): Screen Brightness 142
I/jxcore-log( 3001): 
,E/jxcore-log( 3001): Dummy Error Log.
E/jxcore-log( 3001): 
,I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3141 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  906): Killing 2667:com.htc.lmw/u0a60 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2667
,I/ActivityManager(  906): Killing 2770:com.htc.reportagent/u0a66 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2770
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3155 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 2787:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2787
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3168 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 2799:com.htc.showme/u0a83 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2799
,I/ActivityManager(  906): Killing 2813:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2813
I/ActivityManager(  906): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3183 uid=9987 gids={49987}
,I/jxcore-log( 3001): getBuffer is called!!!!
I/jxcore-log( 3001): 
,I/ActivityManager(  906): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3197 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
,I/ActivityManager(  906): Killing 2842:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2842
,I/ActivityManager(  906): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3213 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 2696:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2696
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 2893:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2893
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3309 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 2912:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2912
,I/ActivityManager(  906): Delay finish: com.android.settings/.NSReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3348 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Killing 2927:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2927
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3389 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3401 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 2958:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  906): Killing 3032:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3032
,I/ActivityManager(  906): Recipient 2958
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3417 uid=10041 gids={50041}
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3433 uid=10078 gids={50078}
I/ActivityManager(  906): Killing 2944:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3445 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  906): Killing 3067:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2944
,I/ActivityManager(  906): Killing 3094:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3067
,I/ActivityManager(  906): Recipient 3094
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3466 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3481 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3495 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3111:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3111
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3510 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  906): Killing 3141:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3141
,I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3522 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3534 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3183:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  906): Killing 3126:com.zoodles.kidmode/u0a149 (adj 15): empty #18
,I/ActivityManager(  906): Recipient 3126
,I/ActivityManager(  906): Recipient 3183
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3555 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Killing 3197:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3197
,I/jxcore-log( 3001): Bluetooth turned on
I/jxcore-log( 3001): 
,I/ActivityManager(  906): Killing 3213:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3213
,I/jxcore-log( 3001): WiFi turned off
I/jxcore-log( 3001): 
,I/jxcore-log( 3001): WiFi turned on
I/jxcore-log( 3001): 
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3572 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3593 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Killing 3309:com.android.vending/u0a74 (adj 15): empty #17
I/ActivityManager(  906): Killing 3348:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3348
,I/ActivityManager(  906): Recipient 3309
,I/jxcore-log( 3001): No internet connection
I/jxcore-log( 3001): 
,I/ActivityManager(  906): Killing 3389:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3389
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3615 uid=10079 gids={50079, 3003, 5012}
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3629 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3401:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3401
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3645 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3417:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3417
,I/jxcore-log( 3001): No internet connection
I/jxcore-log( 3001): 
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3682 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  906): Killing 3433:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3433
,I/ActivityManager(  906): Killing 3445:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3445
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3721 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Killing 3155:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3155
,I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3745 uid=10090 gids={50090, 3003, 5012, 1028}
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3758 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3775 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 3481:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Killing 2722:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2722
,I/ActivityManager(  906): Recipient 3481
,I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3789 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,I/jxcore-log( 3001): No internet connection
I/jxcore-log( 3001): 
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3805 uid=10041 gids={50041}
I/ActivityManager(  906): Killing 3510:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3510
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3818 uid=10078 gids={50078}
,I/ActivityManager(  906): Killing 3522:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=3830 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Killing 3534:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3522
,I/ActivityManager(  906): Recipient 3534
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3555:com.facebook.katana/u0a27 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3555
,I/ActivityManager(  906): Killing 3593:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3593
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3858 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3886 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/jxcore-log( 3001): No internet connection
I/jxcore-log( 3001): 
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3615:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3615
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3945 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3962 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/jxcore-log( 3001): WiFi
I/jxcore-log( 3001): 
,I/jxcore-log( 3001): Response status code was: 200
I/jxcore-log( 3001): 
I/jxcore-log( 3001): ****TEST TOOK:  10578  ms ****
I/jxcore-log( 3001): 
,I/jxcore-log( 3001): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3001): 
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4292cd88 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3982 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4026 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3629:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3629
,I/ActivityManager(  906): Killing 3645:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=4048 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Recipient 3645
I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4068 uid=10081 gids={50081, 5001, 1028, 1015}
I/ActivityManager(  906): Killing 3721:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Recipient 3721
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,I/ActivityManager(  906): Killing 3001:com.example.hello/u0a396 (adj 0): stop com.example.hello
,W/ActivityManager(  906): Force removing ActivityRecord{423feb30 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3745:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3745
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4097 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/ActivityManager(  906): App crashed! Process: com.google.android.music:main
,I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4137 uid=10068 gids={50068, 3003, 5012}
,I/ActivityManager(  906): Killing 3758:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3758
,I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings


LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
I/ActivityManager(  760): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.youtube/com.google.android.libraries.youtube.ads.preload.PreloadVideosTransferService$DeviceStateReceiver
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Killing 1568:com.google.android.configupdater/u0a2 (adj 15): empty #17
I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2117 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
I/ActivityManager(  760): Killing 1604:com.google.android.onetimeinitializer/u0a10 (adj 15): empty #17
I/ActivityManager(  760): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2131 uid=10058 gids={50058, 3003, 1028, 1015}
,I/ActivityManager(  760): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2157
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2197 uid=10115 gids={50115, 3003, 3001, 3002}
I/ActivityManager(  760): Killing 1233:com.google.android.partnersetup/u0a11 (adj 15): empty #17
I/ActivityManager(  760): Killing 1633:com.android.vending/u0a14 (adj 15): empty #17
I/ActivityManager(  760): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +276ms
,W/jxcore-log( 2197): Initializing JXcore engine
,W/jxcore-log( 2197): JXcore engine is ready
,W/jxcore-log( 2197): Starting JXcore engine
,W/jxcore-log( 2197): Platform android
W/jxcore-log( 2197): 
,W/jxcore-log( 2197): Process ARCH arm
W/jxcore-log( 2197): 
,I/jxcore-log( 2197): JXcore Cordova bridge is ready!
I/jxcore-log( 2197): 
,W/jxcore-log( 2197): JXcore engine is started
,E/jxcore-log( 2197): >> LGE-Nexus 5
E/jxcore-log( 2197): 
,I/jxcore-log( 2197): Total memory 1945137152
I/jxcore-log( 2197): 
I/jxcore-log( 2197): Free memory 894803968
I/jxcore-log( 2197): 
,I/jxcore-log( 2197): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2197): 
,I/jxcore-log( 2197): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2197): 
,I/jxcore-log( 2197): userPath [ 'www' ]
I/jxcore-log( 2197): 
,I/jxcore-log( 2197): Size 1080 1776
I/jxcore-log( 2197): 
,I/jxcore-log( 2197): Screen Brightness 82
I/jxcore-log( 2197): 
,E/jxcore-log( 2197): Dummy Error Log.
E/jxcore-log( 2197): 
,I/jxcore-log( 2197): getBuffer is called!!!!
I/jxcore-log( 2197): 
,I/ActivityManager(  760): Killing 1516:com.android.providers.calendar/u0a1 (adj 15): empty #17
,I/ActivityManager(  760): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2278 uid=10001 gids={50001, 3003, 1028, 1015}
,I/ActivityManager(  760): Killing 1726:com.android.cellbroadcastreceiver/u0a29 (adj 15): empty #17
,I/ActivityManager(  760): Delaying start of: ServiceRecord{42e7cfd0 u0 com.android.providers.calendar/.EmptyService}
,I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Killing 1752:com.google.android.deskclock/u0a33 (adj 15): empty #17
,I/jxcore-log( 2197): Bluetooth turned on
I/jxcore-log( 2197): 
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=2302 uid=10033 gids={50033, 1028}
,I/jxcore-log( 2197): WiFi turned off
I/jxcore-log( 2197): 
,I/jxcore-log( 2197): WiFi turned on
I/jxcore-log( 2197): 
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Killing 1784:com.google.android.apps.genie.geniewidget/u0a40 (adj 15): empty #17
,I/ActivityManager(  760): Delay finish: com.google.android.gms/.lockbox.LockboxAlarmReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=2360 uid=10011 gids={50011, 3003}
,I/ActivityManager(  760): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2376 uid=10013 gids={50013, 3003, 3002}
,I/ActivityManager(  760): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2393 uid=10014 gids={50014, 3003, 1028, 1015}
I/ActivityManager(  760): Killing 1092:com.android.printspooler/u0a64 (adj 15): empty #17
,I/ActivityManager(  760): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  760): Delaying start of: ServiceRecord{42c9b228 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,I/ActivityManager(  760): Killing 1136:com.google.android.keep/u0a52 (adj 15): empty #17
,I/jxcore-log( 2197): No internet connection
I/jxcore-log( 2197): 
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2459 uid=10063 gids={50063, 3003, 3002, 1028, 1015}
,I/jxcore-log( 2197): No internet connection
I/jxcore-log( 2197): 
,I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Killing 1855:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  760): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2499 uid=10065 gids={50065, 3003, 1028, 1015}
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2522 uid=10035 gids={50035, 1028, 3003, 1015}
,I/ActivityManager(  760): Killing 1910:com.google.android.exchange/u0a37 (adj 15): empty #17
,W/ActivityManager(  760): No permission grants found for com.quickoffice.android
,I/jxcore-log( 2197): No internet connection
I/jxcore-log( 2197): 
,I/ActivityManager(  760): Killing 1999:com.google.android.youtube/u0a71 (adj 15): empty #17
,I/ActivityManager(  760): Waited long enough for: ServiceRecord{42c72728 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService}
,F/ActivityManager(  760): Service ServiceRecord{42d96680 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42d8d290 1999:com.google.android.youtube/u0a71} not same as in map: null
,I/ActivityManager(  760): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.calendar/com.android.calendar.alerts.AlertReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2601 uid=10052 gids={50052, 3003, 1028, 1015}
,I/ActivityManager(  760): Delay finish: com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/jxcore-log( 2197): WiFi
I/jxcore-log( 2197): 
,I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  760): Resuming delayed broadcast
I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=2657 uid=10031 gids={50031, 3003, 1028, 1015}
W/ActivityThread(  953): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 2197): Response status code was: 200
I/jxcore-log( 2197): 
I/jxcore-log( 2197): ****TEST TOOK:  9222  ms ****
I/jxcore-log( 2197): 
,I/jxcore-log( 2197): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2197): 
,I/ActivityManager(  760): Killing 1771:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  760): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,E/ActivityThread( 1329): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  760): Force stopping com.example.hello appid=10115 user=-1: uninstall pkg
,I/ActivityManager(  760): Killing 2197:com.example.hello/u0a115 (adj 0): stop com.example.hello
,W/ActivityManager(  760): Force removing ActivityRecord{42e8ccb0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,I/ActivityManager(  760): Force stopping com.example.hello appid=10115 user=0: pkg removed
,I/ActivityManager(  760): Waited long enough for: ServiceRecord{42e2fa60 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2718 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  760): Resuming delayed broadcast
,I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2748 uid=10034 gids={50034}
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=2763 uid=10071 gids={50071, 3003, 1028, 1015}
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2775 uid=10006 gids={50006, 1028, 1015, 1023}
,I/ActivityManager(  760): Killing 2302:com.google.android.deskclock/u0a33 (adj 15): empty #17
,I/ActivityManager(  760): Killing 1885:com.google.android.email/u0a36 (adj 15): empty #17
,I/ActivityManager(  760): Killing 2360:com.google.android.partnersetup/u0a11 (adj 15): empty #17


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":18,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_495261844451736/Sub/serverApp/index.js',
  '{"devices":{"android":18}}' ]

JSON { devices: { android: 18 } }


```

