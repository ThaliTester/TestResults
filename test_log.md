#### Test 49526184549c368 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":14,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184549c368/Sub/serverApp/index.js',
  '{"devices":{"android":14}}' ]

JSON { devices: { android: 14 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.example.hello code:0 
child process exited with code 0 on device f56ad48d 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
Android task is completed 
```

Logcat output:
```
LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager( 1280): Start proc 9327:com.google.android.setupwizard/u0a54 for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver
I/ActivityManager( 1280): Killing 8682:com.google.android.music:main/u0a123 (adj 15): empty #22
I/ActivityManager( 1280): Start proc 9370:com.lge.sizechangable.weather/u0a136 for broadcast com.lge.sizechangable.weather/.lgbackup.StartBackupOnBoot
I/ActivityManager( 1280): Killing 8843:com.lge.myplace/u0a30 (adj 15): empty #22
I/ActivityManager( 1280): Killing 8789:com.lge.sizechangable.weather.platform/u0a96 (adj 15): empty #23
I/ActivityManager( 1280): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1280): setTaskToReturnTo : TaskRecord{57e3bc6 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1280): setTaskToReturnTo : TaskRecord{57e3bc6 #47 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1280): Start proc 9397:com.example.hello/u0a360 for activity com.example.hello/.MainActivity
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10136 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1280): Killing 8874:com.google.android.partnersetup/u0a5 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 9427:com.lge.lifetracker/u0a137 for broadcast com.lge.lifetracker/.widgets.HealthWidgetProvider
I/ActivityManager( 1280): Start proc 9462:com.lge.lgaccount/u0a107 for content provider com.lge.lgaccount/.provider.LGAccountProvider
I/ActivityManager( 1280): Displayed com.example.hello/.MainActivity: +637ms (total +35s90ms)
I/ActivityManager( 1280): Start proc 9494:com.lge.bioitplatform.sdservice.service/u0a4 for content provider com.lge.bioitplatform.sdservice.service/com.lge.bioitplatform.sdservice.provider.BioDataProvider
I/ActivityManager( 1280): Killing 8897:com.lge.appbox.client/u0a9 (adj 15): empty #22
W/jxcore-log( 9397): Initializing JXcore engine
W/jxcore-log( 9397): JXcore engine is ready
W/jxcore-log( 9397): Starting JXcore engine
I/ActivityManager( 1280): Killing 8438:com.lge.formmanager/u0a49 (adj 15): empty #22
W/jxcore-log( 9397): Platform android
W/jxcore-log( 9397): 
W/jxcore-log( 9397): Process ARCH arm
W/jxcore-log( 9397): 
I/jxcore-log( 9397): JXcore Cordova bridge is ready!
I/jxcore-log( 9397): 
W/jxcore-log( 9397): JXcore engine is started
I/ActivityManager( 1280): Killing 8662:com.lge.bnr/1000 (adj 15): empty #22
E/jxcore-log( 9397): >> LGE-LG-H815
E/jxcore-log( 9397): 
I/jxcore-log( 9397): Total memory 2968948736
I/jxcore-log( 9397): 
I/jxcore-log( 9397): Free memory 83300352
I/jxcore-log( 9397): 
I/jxcore-log( 9397): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9397): 
I/jxcore-log( 9397): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 9397): 
I/jxcore-log( 9397): userPath [ 'www' ]
I/jxcore-log( 9397): 
I/jxcore-log( 9397): Size 1440 2392
I/jxcore-log( 9397): 
I/jxcore-log( 9397): Screen Brightness 255
I/jxcore-log( 9397): 
E/jxcore-log( 9397): Dummy Error Log.
E/jxcore-log( 9397): 
I/ActivityManager( 1280): Start proc 9520:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
I/ActivityManager( 1280): Start proc 9542:com.lge.appbox.client/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper
I/ActivityManager( 1280): Start proc 9571:com.lge.eodengine/1000 for broadcast com.lge.eodengine/.EodEngineReceiver
I/ActivityManager( 1280): Start proc 9594:com.google.android.music:main/u0a123 for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
I/jxcore-log( 9397): getBuffer is called!!!!
I/jxcore-log( 9397): 
W/ActivityManager( 1280): getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
I/ActivityManager( 1280): Killing 8923:com.lge.exchange/u0a22 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 8944:com.lge.email/u0a56 (adj 15): empty #22
,I/jxcore-log( 9397): Bluetooth turned on
I/jxcore-log( 9397): 
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): WiFi turned off
I/jxcore-log( 9397): 
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): WiFi turned on
I/jxcore-log( 9397): 
,I/ActivityManager( 1280): Start proc 9657:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
,I/ActivityManager( 1280): Start proc 9679:com.android.settings/1000 for broadcast com.lge.bluetoothsetting/.DockEventReceiver
,I/ActivityManager( 1280): Killing 8995:com.lge.NfcSettings/1000 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Start proc 9705:com.lge.ia.task.smartsetting/u0a21 for broadcast com.lge.ia.task.smartsetting/.detector.ContextDetector
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Killing 9035:com.lge.eula/u0a105 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 9055:com.google.android.apps.docs/u0a118 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 9735:com.lge.wifisettings/1000 for broadcast com.lge.wifisettings/.wifioffload.WiFiOffLoadBroadcast
,I/ActivityManager( 1280): Killing 9139:com.uei.lg.quicksetsdk.irblaster/1000 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): No internet connection,
I/jxcore-log( 9397): 
,I/ActivityManager( 1280): Killing 9327:com.google.android.setupwizard/u0a54 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 9770:com.lge.settings.easy/1000 for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Start proc 9829:com.google.android.apps.maps/u0a119 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/ActivityManager( 1280): Killing 9370:com.lge.sizechangable.weather/u0a136 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 9865:com.lge.lgdmsclient/1000 for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver
,I/ActivityManager( 1280): Killing 9462:com.lge.lgaccount/u0a107 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 9427:com.lge.lifetracker/u0a137 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): No internet connection
I/jxcore-log( 9397): 
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Start proc 9909:com.lge.qremote/u0a138 for broadcast com.lge.qremote/.settings.WiFiStateReceiver
,I/ActivityManager( 1280): Start proc 9935:com.uei.lg.quicksetsdk.irblaster/1000 for service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service
,I/ActivityManager( 1280): Start proc 9968:com.lge.bnr/1000 for broadcast com.lge.bnr/.service.BNRBootReceiver
,I/ActivityManager( 1280): Killing 9494:com.lge.bioitplatform.sdservice.service/u0a4 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 9542:com.lge.appbox.client/u0a9 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): No internet connection
I/jxcore-log( 9397): 
,I/ActivityManager( 1280): Killing 8967:com.android.contacts/u0a18 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): No internet connection
I/jxcore-log( 9397): 
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): No internet connection
I/jxcore-log( 9397): 
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): No internet connection
I/jxcore-log( 9397): 
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
I/jxcore-log( 9397): No internet connection
I/jxcore-log( 9397): 
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Killing 8758:com.android.gallery3d/u0a55 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 10049:com.google.android.youtube/u0a124 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,I/ActivityManager( 1280): Start proc 10069:com.lge.appbox.client/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor
,I/ActivityManager( 1280): Start proc 10092:com.android.gallery3d/u0a55 for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
W/ActivityManager( 1280): getRunningAppProcesses: caller 10360 does not hold REAL_GET_TASKS; limiting output
,I/jxcore-log( 9397): WiFi
I/jxcore-log( 9397): 
,I/ActivityManager( 1280): Start proc 10132:com.lge.email/u0a56 for broadcast com.lge.email/.adapter.event.receiver.EmailEngineReceiver
,I/ActivityManager( 1280): Start proc 10154:com.lge.cic.eden.service/u0a7 for broadcast com.lge.cic.eden.service/com.lge.cic.eden.receiver.EdenBroadcastReceiver
,I/ActivityManager( 1280): Start proc 10186:com.lge.clock/u0a16 for broadcast com.lge.clock/.alarmclock.AlarmInitReceiver
,I/ActivityManager( 1280): Killing 9092:com.google.android.googlequicksearchbox:search/u0a63 (adj 15): empty #22
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Start proc 10252:com.lge.exchange/u0a22 for broadcast com.lge.exchange/.receiver.NetworkStatusReceiver
,I/jxcore-log( 9397): Response status code was: 200
I/jxcore-log( 9397): 
I/jxcore-log( 9397): ****TEST TOOK:  14716  ms ****
I/jxcore-log( 9397): 
I/jxcore-log( 9397): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9397): 
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Killing 9233:com.google.android.gms:car/u0a6 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 10301:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/ActivityManager( 1280): Start proc 10326:com.google.android.setupwizard/u0a54 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,I/ActivityManager( 1280): Force stopping com.example.hello appid=10360 user=0: pkg removed
,I/ActivityManager( 1280): Killing 9397:com.example.hello/u0a360 (adj 0): stop com.example.hello
,W/ActivityManager( 1280): Force removing ActivityRecord{e19f787 u0 com.example.hello/.MainActivity t47}: app died, no saved state
,I/ActivityManager( 1280): Start proc 10373:com.lge.sizechangable.weather.platform/u0a96 for broadcast com.lge.sizechangable.weather.platform/.receiver.WeatherPlatformCommonReceiver
,I/ActivityManager( 1280): Killing 8811:com.google.android.talk/u0a121 (adj 15): empty #22
,W/ActivityManager( 1280): Spurious death for ProcessRecord{1b43b8c1 9397:com.example.hello/u0a360}, curProc for 9397: null
,W/ActivityManager( 1280): getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,I/ActivityManager( 1280): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
,I/ActivityManager( 1280): Start proc 10401:com.lge.provider.lockscreensettings/u0a84 for content provider com.lge.provider.lockscreensettings/.LockSettingsDBProvider
,I/ActivityManager( 1280): Killing 9265:com.google.android.gm/u0a113 (adj 15): empty #22
,I/ActivityManager( 1280): Killing 7541:com.android.providers.calendar/u0a19 (adj 15): empty #22
,I/ActivityManager( 1280): Start proc 10426:com.lge.myplace/u0a30 for broadcast com.lge.myplace/.Receiver
,I/ActivityManager( 1280): Killing 9705:com.lge.ia.task.smartsetting/u0a21 (adj 15): empty #22


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/ActivityManager( 2926): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/ActivityManager( 2926): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,W/jxcore-log( 6825): Initializing JXcore engine
W/jxcore-log( 6825): JXcore engine is ready
,W/jxcore-log( 6825): Starting JXcore engine
,W/jxcore-log( 6825): Platform android
W/jxcore-log( 6825): 
W/jxcore-log( 6825): Process ARCH arm
W/jxcore-log( 6825): 
,I/jxcore-log( 6825): JXcore Cordova bridge is ready!
I/jxcore-log( 6825): 
W/jxcore-log( 6825): JXcore engine is started
,E/jxcore-log( 6825): >> HUAWEI-ALE-L21
E/jxcore-log( 6825): 
,I/jxcore-log( 6825): Total memory 1949741056
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): Free memory 17752064
I/jxcore-log( 6825): 
I/jxcore-log( 6825): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6825): 
I/jxcore-log( 6825): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): userPath [ 'www' ]
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): Size 720 1184
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): Screen Brightness 242
I/jxcore-log( 6825): 
,E/jxcore-log( 6825): Dummy Error Log.
E/jxcore-log( 6825): 
,I/ActivityManager( 2926): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2926): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/jxcore-log( 6825): getBuffer is called!!!!
I/jxcore-log( 6825): 
,I/ActivityManager( 2926): filter receiver for action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager( 2926): filter receiver for action = com.google.android.music.START_DOWNLOAD_SCHEDULING
,I/jxcore-log( 6825): Bluetooth turned on
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): WiFi turned off
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): WiFi turned on
I/jxcore-log( 6825): 
,I/ActivityManager( 2926): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/jxcore-log( 6825): No internet connection
I/jxcore-log( 6825): 
,I/ActivityManager( 2926): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager( 2926): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/jxcore-log( 6825): No internet connection
I/jxcore-log( 6825): 
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.p2p.THIS_DEVICE_CHANGED
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.SCAN_RESULTS
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/jxcore-log( 6825): No internet connection
I/jxcore-log( 6825): 
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,I/jxcore-log( 6825): No internet connection
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): No internet connection
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): No internet connection
I/jxcore-log( 6825): 
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2926): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/jxcore-log( 6825): WiFi
I/jxcore-log( 6825): 
,I/jxcore-log( 6825): Response status code was: 200
I/jxcore-log( 6825): 
I/jxcore-log( 6825): ****TEST TOOK:  12561  ms ****
I/jxcore-log( 6825): 
I/jxcore-log( 6825): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6825): 
,I/ActivityManager( 2926): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2926): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/ActivityManager( 2926): filter receiver for action = android.net.conn.CONNECTIVITY_CHANGE


samsung-SM-A500FU: 
--------- beginning of main
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
--------- beginning of system
D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4149 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3312:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
D/ActivityThread( 4132): Added TimaKeyStore provider
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityThread( 4149): Added TimaKeyStore provider
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4167 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityThread( 4167): Added TimaKeyStore provider
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4190 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3368:com.fmm.dm/1000 (adj 15): empty #31
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4190): Added TimaKeyStore provider
I/ActivityManager( 1015): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4206 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3248:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4206): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 3397:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4242 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3352:com.google.android.configupdater/u0a86 (adj 15): empty #31
D/ActivityThread( 4242): Added TimaKeyStore provider
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4262 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3435:com.dropbox.android/u0a92 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4262): Added TimaKeyStore provider
I/ActivityManager( 1015): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4279 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 4279): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 3452:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
I/ActivityManager( 1015): Killing 2669:com.google.android.apps.plus/u0a120 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4317 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3467:com.fmm.ds/1000 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityThread( 4317): Added TimaKeyStore provider
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 3490:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4338 uid=10116 gids={50116, 9997} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3268:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4338): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4354 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
D/ActivityThread( 4354): Added TimaKeyStore provider
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4369 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 4369): Added TimaKeyStore provider
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4389 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3510:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4389): Added TimaKeyStore provider
D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4417 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
D/ActivityThread( 4417): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 3526:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
I/ActivityManager( 1015): Killing 3570:com.wssnps/1000 (adj 15): empty #31
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4434 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3541:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
D/ActivityThread( 4434): Added TimaKeyStore provider
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4457 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityThread( 4457): Added TimaKeyStore provider
D/ActivityManager( 1015): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
I/ActivityManager( 1015): Killing 3590:com.samsung.android.sm/1000 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 3330:com.google.android.partnersetup/u0a15 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/ActivityManager( 1015): Killing 3680:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): getTasks: caller 10145 does not hold GET_TASKS; limiting output
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Process com.android.email (pid 4434)(adj 9) has died(117,1129)
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): mDVFSHelper.acquire()
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
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4513 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4513): Added TimaKeyStore provider
V/ActivityThread( 1480): updateVisibility : ActivityRecord{13089062 token=android.os.BinderProxy@3ffe1978 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
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
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=4536 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/ActivityThread( 4536): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4575 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 4575): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 3698:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 3738:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1015): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/ActivityManager( 1015): Displayed Component not be shown by security: +813ms
,W/ActivityManager( 1015): mDVFSHelper.release()
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,V/ActivityThread( 3160): updateVisibility : ActivityRecord{3b4faa3 token=android.os.BinderProxy@381913e5 {com.wssyncmldm/com.wssyncmldm.ui.XUIDialogActivity}} show : false
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4608 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4619 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityThread( 4608): Added TimaKeyStore provider
,D/ActivityThread( 4619): Added TimaKeyStore provider
,W/jxcore-log( 4513): Initializing JXcore engine
W/jxcore-log( 4513): JXcore engine is ready
,W/jxcore-log( 4513): Starting JXcore engine
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 4513): Platform android
W/jxcore-log( 4513): 
,W/jxcore-log( 4513): Process ARCH arm
W/jxcore-log( 4513): 
,I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4654 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 4654): Added TimaKeyStore provider
,I/jxcore-log( 4513): JXcore Cordova bridge is ready!
I/jxcore-log( 4513): 
,W/jxcore-log( 4513): JXcore engine is started
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/jxcore-log( 4513): >> samsung-SM-A500FU
E/jxcore-log( 4513): 
,I/jxcore-log( 4513): Total memory 1983791104
I/jxcore-log( 4513): 
,I/jxcore-log( 4513): Free memory 32088064
I/jxcore-log( 4513): 
I/jxcore-log( 4513): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4513): 
I/jxcore-log( 4513): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4513): 
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4674 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/jxcore-log( 4513): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4513): 
I/ActivityManager( 1015): Killing 3759:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/jxcore-log( 4513): Size 720 1280
I/jxcore-log( 4513): 
I/jxcore-log( 4513): Screen Brightness 5
I/jxcore-log( 4513): 
E/jxcore-log( 4513): Dummy Error Log.
E/jxcore-log( 4513): 
,D/ActivityThread( 4674): Added TimaKeyStore provider
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/jxcore-log( 4513): getBuffer is called!!!!
I/jxcore-log( 4513): 
,W/ActivityThread( 4608): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/ActivityManager( 1015): Killing 3808:com.sec.factory.camera/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{127e9b81 u0 com.samsung.android.providers.context/.ContextService}
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4742 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3789:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
I/ActivityManager( 1015): Killing 3825:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #32
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,D/ActivityThread( 4742): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4757 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 4757): Added TimaKeyStore provider
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 3288:com.google.android.youtube/u0a166 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4778 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{2e58bdc8 u0 com.android.settings/.wifi.WifiCredService}
,D/ActivityThread( 4778): Added TimaKeyStore provider
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{131fee74 u0 com.sec.bcservice/.BroadcastService}
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4797 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3840:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/ActivityThread( 4797): Added TimaKeyStore provider
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4817 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityThread( 4817): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4839 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 4839): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 3862:com.google.android.gm/u0a101 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4132:com.samsung.helphub/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4206:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4855 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityThread( 4855): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4874 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityThread( 4874): Added TimaKeyStore provider
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=4891 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4904 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 4891): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,D/ActivityThread( 4904): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4922 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4242:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4262:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 4922): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 4167:com.android.vending/u0a28 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4317:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4938 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4369:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/ActivityThread( 4938): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 4417:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4958 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4575:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,D/ActivityThread( 4958): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4979 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3202:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/ActivityThread( 4979): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 3715:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4999 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3416:com.sec.pcw.device/1000 (adj 15): empty #31
,D/ActivityThread( 4999): Added TimaKeyStore provider
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5014 uid=10025 gids={50025, 9997} abi=armeabi-v7a,
,D/ActivityThread( 5014): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 3923:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5035 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/ActivityThread( 5035): Added TimaKeyStore provider


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
LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  836): Killing 2520:com.android.defcontainer/u0a4 (adj 15): empty #11
,I/ActivityManager(  836): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3970 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager(  836): Killing 2282:com.google.android.gms/u0a6 (adj 15): empty #11
I/ActivityManager(  836): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3990 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager(  836): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4020 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  836): Killing 3676:com.lge.settings.easy/1000 (adj 15): empty #11
I/ActivityManager(  836): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  836): setTaskToReturnTo : TaskRecord{14f3ab37 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  836): setTaskToReturnTo : TaskRecord{14f3ab37 #219 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager(  836): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4042 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  836): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4061 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  836): Killing 3743:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/ActivityManager(  836): Killing 3779:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/ActivityManager(  836): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4080 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  836): Killing 3801:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/ActivityManager(  836): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4105 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/ActivityManager(  836): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=4136 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 3825:com.lge.clock/u0a10 (adj 15): empty #11
,I/ActivityManager(  836): Killing 3855:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/ActivityManager(  836): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4155 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  836): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4176 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  836): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/ActivityManager(  836): Killing 3878:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  836): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4197 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  836): Killing 3329:com.android.settings/1000 (adj 15): empty #11
,I/ActivityManager(  836): Displayed com.example.hello/.MainActivity: +1s397ms
,I/ActivityManager(  836): Process com.lge.defaultaccount (pid 4105) has died
,I/ActivityManager(  836): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4219 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  836): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4236 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  836): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4267 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 3929:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,I/ActivityManager(  836): Killing 3970:com.lge.voicerecorder/u0a34 (adj 15): empty #11
,W/jxcore-log( 4042): Initializing JXcore engine
W/jxcore-log( 4042): JXcore engine is ready
,W/jxcore-log( 4042): Starting JXcore engine
,I/ActivityManager(  836): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=4285 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/jxcore-log( 4042): Platform android
W/jxcore-log( 4042): 
W/jxcore-log( 4042): Process ARCH arm
W/jxcore-log( 4042): 
,I/ActivityManager(  836): Waited long enough for: ServiceRecord{901f510 u0 com.google.android.gms/.gcm.GcmService}
I/jxcore-log( 4042): JXcore Cordova bridge is ready!
I/jxcore-log( 4042): 
W/jxcore-log( 4042): JXcore engine is started
,E/jxcore-log( 4042): >> LGE-LG-D722
E/jxcore-log( 4042): 
I/jxcore-log( 4042): Total memory 906309632
I/jxcore-log( 4042): 
I/jxcore-log( 4042): Free memory 28827648
I/jxcore-log( 4042): 
I/jxcore-log( 4042): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4042): 
I/jxcore-log( 4042): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4042): 
,I/jxcore-log( 4042): userPath [ 'www' ]
I/jxcore-log( 4042): 
I/jxcore-log( 4042): Size 720 1196
I/jxcore-log( 4042): 
I/jxcore-log( 4042): Screen Brightness 255
I/jxcore-log( 4042): 
E/jxcore-log( 4042): Dummy Error Log.
E/jxcore-log( 4042): 
W/ActivityThread( 4285): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 4042): getBuffer is called!!!!
I/jxcore-log( 4042): 
,I/ActivityManager(  836): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4370 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  836): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4400 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 3990:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/ActivityManager(  836): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4503 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 4020:com.lge.cloudhub/u0a49 (adj 15): empty #11
,W/ActivityManager(  836): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  836): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  836): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4554 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/ActivityManager(  836): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  836): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  836): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  836): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4586 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  836): Killing 4061:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
W/ActivityManager(  836): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 4503): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@d450cf3 that was originally bound here
E/ActivityThread( 4503): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@d450cf3 that was originally bound here
E/ActivityThread( 4503): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4503): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4503): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4503): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4503): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4503): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4503): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4503): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4503): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4503): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4503): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4503): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4503): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4503): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4503): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4503): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  836): Unbind failed: could not find connection for android.os.BinderProxy@32a61367
I/ActivityManager(  836): Killing 4080:com.lge.lgfota.permission/1000 (adj 15): empty #11
,I/ActivityManager(  836): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4630 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  836): Killing 4136:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/jxcore-log( 4042): Bluetooth turned on
I/jxcore-log( 4042): 
,I/jxcore-log( 4042): WiFi turned off
I/jxcore-log( 4042): 
,I/jxcore-log( 4042): WiFi turned on
I/jxcore-log( 4042): 
,I/ActivityManager(  836): Waited long enough for: ServiceRecord{e5fba4e u0 com.android.mms/.service.SwitchedService}
,I/ActivityManager(  836): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4669 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  836): Killing 4155:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  836): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4687 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 4176:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/jxcore-log( 4042): No internet connection
I/jxcore-log( 4042): 
,W/ActivityManager(  836): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,W/ActivityManager(  836): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/ActivityManager(  836): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4715 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  836): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=4736 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 4197:com.lge.springcleaning/1000 (adj 15): empty #11
,I/ActivityManager(  836): Killing 4267:com.lge.eula/1000 (adj 15): empty #11
I/ActivityManager(  836): Killing 4236:com.google.android.configupdater/u0a3 (adj 15): empty #12
,I/ActivityManager(  836): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4760 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  836): Killing 4370:com.google.android.talk/u0a61 (adj 15): empty #11
,I/jxcore-log( 4042): No internet connection
I/jxcore-log( 4042): 
,I/ActivityManager(  836): Killing 4400:com.google.android.youtube/u0a100 (adj 15): empty #11
,I/ActivityManager(  836): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4834 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/jxcore-log( 4042): WiFi
I/jxcore-log( 4042): 
,I/jxcore-log( 4042): Response status code was: 200
I/jxcore-log( 4042): 
I/jxcore-log( 4042): ****TEST TOOK:  8371  ms ****
I/jxcore-log( 4042): 
I/jxcore-log( 4042): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4042): 
,I/ActivityManager(  836): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4887 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  836): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  836): Killing 4042:com.example.hello/u0a30 (adj 0): stop com.example.hello
,W/ActivityManager(  836): Force removing ActivityRecord{d74d8a4 u0 com.example.hello/.MainActivity t219}: app died, no saved state
,W/ActivityManager(  836): Spurious death for ProcessRecord{361ae3e8 4042:com.example.hello/u0a30}, curProc for 4042: null
,I/ActivityManager(  836): Force stopping com.example.hello appid=10030 user=0: pkg removed
,I/ActivityManager(  836): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4915 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 4503:com.google.android.gm/u0a53 (adj 15): empty #11
,I/ActivityManager(  836): Waited long enough for: ServiceRecord{37cc51c1 u0 com.lge.mlt/.MltMonitorService}
,I/ActivityManager(  836): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4953 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 4586:com.android.vending/u0a36 (adj 15): empty #11
,D/ActivityManager(  836): enqueue in BackgroundQueue #73 Intent=Intent { act=com.google.android.intent.action.GCM_RECONNECT flg=0x14 (has extras) }
,I/ActivityManager(  836): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4979 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  836): Killing 4630:com.lge.qmemoplus/1000 (adj 15): empty #11


LGE-Nexus 5: 
--------- beginning of main
--------- beginning of system
W/ActivityThread( 2750): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  735): Killing 2253:com.android.managedprovisioning/u0a14 (adj 15): empty #17
I/ActivityManager(  735): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2823 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  735): Killing 1985:com.android.providers.calendar/u0a2 (adj 15): empty #17
,I/ActivityManager(  735): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2852 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2886 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  735): Displayed com.example.hello/.MainActivity: +480ms (total +18s125ms)
,W/jxcore-log( 2886): Initializing JXcore engine
W/jxcore-log( 2886): JXcore engine is ready
,W/jxcore-log( 2886): Starting JXcore engine
,I/ActivityManager(  735): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2955 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  735): Killing 2284:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/jxcore-log( 2886): Platform android
W/jxcore-log( 2886): 
W/jxcore-log( 2886): Process ARCH arm
W/jxcore-log( 2886): 
,I/jxcore-log( 2886): JXcore Cordova bridge is ready!
I/jxcore-log( 2886): 
W/jxcore-log( 2886): JXcore engine is started
,E/jxcore-log( 2886): >> LGE-Nexus 5
E/jxcore-log( 2886): 
,I/jxcore-log( 2886): Total memory 1946181632
I/jxcore-log( 2886): 
I/jxcore-log( 2886): Free memory 290922496
I/jxcore-log( 2886): 
I/jxcore-log( 2886): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2886): 
I/jxcore-log( 2886): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2886): 
,I/jxcore-log( 2886): userPath [ 'www' ]
I/jxcore-log( 2886): 
,I/jxcore-log( 2886): Size 1080 1776
I/jxcore-log( 2886): 
,I/jxcore-log( 2886): Screen Brightness 82
I/jxcore-log( 2886): 
,E/jxcore-log( 2886): Dummy Error Log.
E/jxcore-log( 2886): 
,I/ActivityManager(  735): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2984 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 2886): getBuffer is called!!!!
I/jxcore-log( 2886): 
,I/ActivityManager(  735): Killing 1252:com.google.android.keep/u0a71 (adj 15): empty #17
,I/jxcore-log( 2886): Bluetooth turned on
I/jxcore-log( 2886): 
,I/jxcore-log( 2886): WiFi turned off
I/jxcore-log( 2886): 
,I/jxcore-log( 2886): WiFi turned on
I/jxcore-log( 2886): 
,I/ActivityManager(  735): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3144 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2318:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,I/ActivityManager(  735): Killing 2419:com.google.android.youtube/u0a80 (adj 15): empty #17
,I/jxcore-log( 2886): No internet connection
I/jxcore-log( 2886): 
,I/jxcore-log( 2886): No internet connection
I/jxcore-log( 2886): 
,I/jxcore-log( 2886): No internet connection
I/jxcore-log( 2886): 
,I/ActivityManager(  735): Waited long enough for: ServiceRecord{25ca2ef1 u0 com.google.android.calendar/com.android.calendar.alerts.InitAlarmsService},
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3240 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  735): Waited long enough for: ServiceRecord{33d6abf3 u0 com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelService}
,I/ActivityManager(  735): Killing 2026:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/jxcore-log( 2886): No internet connection
I/jxcore-log( 2886): 
,I/ActivityManager(  735): Killing 2601:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/jxcore-log( 2886): WiFi
I/jxcore-log( 2886): 
,I/jxcore-log( 2886): Response status code was: 200
I/jxcore-log( 2886): 
I/jxcore-log( 2886): ****TEST TOOK:  10243  ms ****
I/jxcore-log( 2886): 
I/jxcore-log( 2886): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2886): 
,I/ActivityManager(  735): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 2886:com.example.hello/u0a277 (adj 0): stop com.example.hello
,W/ActivityManager(  735): Force removing ActivityRecord{1c8a6fb u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  735): Spurious death for ProcessRecord{979cc25 2886:com.example.hello/u0a277}, curProc for 2886: null
,I/ActivityManager(  735): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3415 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3450 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2548:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3482 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2724:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/ActivityManager(  735): Killing 1512:com.google.android.partnersetup/u0a13 (adj 15): empty #17


```

####Node name: thali03
Console output:
```
Error! Unexpected exit on device 320414cd475f91e3 app:com.example.hello code:0 
child process exited with code 0 on device 320414cd475f91e3 
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3933
I/ActivityManager( 1021): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3949 uid=10360 gids={50360, 3003, 3001, 3002}
,I/ActivityManager( 1021): Displayed com.example.hello/.MainActivity: +275ms (total +307ms)
,W/jxcore-log( 3949): Initializing JXcore engine
,W/jxcore-log( 3949): JXcore engine is ready
,W/jxcore-log( 3949): Starting JXcore engine
,W/jxcore-log( 3949): Platform android
W/jxcore-log( 3949): 
,W/jxcore-log( 3949): Process ARCH arm
W/jxcore-log( 3949): 
,I/jxcore-log( 3949): JXcore Cordova bridge is ready!
I/jxcore-log( 3949): 
,W/jxcore-log( 3949): JXcore engine is started
,E/jxcore-log( 3949): >> motorola-XT1039
E/jxcore-log( 3949): 
,I/jxcore-log( 3949): Total memory 893136896
I/jxcore-log( 3949): 
I/jxcore-log( 3949): Free memory 51625984
I/jxcore-log( 3949): 
I/jxcore-log( 3949): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3949): 
I/jxcore-log( 3949): userPath [ 'www' ]
I/jxcore-log( 3949): 
I/jxcore-log( 3949): Size 720 1184
I/jxcore-log( 3949): 
I/jxcore-log( 3949): Screen Brightness 10
I/jxcore-log( 3949): 
E/jxcore-log( 3949): Dummy Error Log.
E/jxcore-log( 3949): 
,I/jxcore-log( 3949): getBuffer is called!!!!
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): Bluetooth turned on
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): WiFi turned off
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): WiFi turned on
I/jxcore-log( 3949): 
,I/ActivityManager( 1021): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4037 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1021): Killing 3694:com.android.calendar/u0a7 (adj 15): empty #9
,I/jxcore-log( 3949): No internet connection
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): No internet connection
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): No internet connection
I/jxcore-log( 3949): 
,I/ActivityManager( 1021): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4102 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,E/ActivityThread( 1559): Failed to find provider info for com.motorola.blur.setupprovider
,E/ActivityThread( 1559): Failed to find provider info for com.motorola.blur.setupprovider
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4130 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3452:android.process.acore/u0a10 (adj 15): empty #9
,I/ActivityManager( 1021): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4149 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1021): Killing 3807:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4162 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3469:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4175 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3834:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,I/ActivityManager( 1021): Killing 3785:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/jxcore-log( 3949): No internet connection
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): No internet connection
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): No internet connection
I/jxcore-log( 3949): 
,E/ActivityThread( 1436): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager( 1021): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4292 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,I/jxcore-log( 3949): WiFi
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): Response status code was: 200
I/jxcore-log( 3949): 
I/jxcore-log( 3949): ****TEST TOOK:  12334  ms ****
I/jxcore-log( 3949): 
,I/jxcore-log( 3949): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3949): 
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10360 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 3949:com.example.hello/u0a360 (adj 0): stop com.example.hello
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{4211f8f0 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10360 user=0: pkg removed
,I/ActivityManager( 1021): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4352 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1021): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4371 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1021): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4389 uid=10059 gids={50059, 3003, 1028, 1015}
,I/ActivityManager( 1021): Killing 3507:com.android.vending/u0a38 (adj 15): empty #9
,I/ActivityManager( 1021): Killing 4037:com.android.settings/1000 (adj 15): empty #9


LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{e6f5b56 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{e6f5b56 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/ActivityManager( 1038): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6529 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityManager( 1038): Display changed displayId=0
I/ActivityManager( 1038): Killing 5089:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,I/ActivityManager( 1038): Displayed com.example.hello/.MainActivity: +624ms (total +726ms)
W/jxcore-log( 6529): Initializing JXcore engine
W/jxcore-log( 6529): JXcore engine is ready
,W/jxcore-log( 6529): Starting JXcore engine
,W/jxcore-log( 6529): Platform android
W/jxcore-log( 6529): 
,W/jxcore-log( 6529): Process ARCH arm
W/jxcore-log( 6529): 
,I/jxcore-log( 6529): JXcore Cordova bridge is ready!
I/jxcore-log( 6529): 
W/jxcore-log( 6529): JXcore engine is started
,E/jxcore-log( 6529): >> LGE-LG-D855
E/jxcore-log( 6529): 
I/jxcore-log( 6529): Total memory 2995761152
I/jxcore-log( 6529): 
I/jxcore-log( 6529): Free memory 571301888
I/jxcore-log( 6529): 
I/jxcore-log( 6529): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6529): 
I/jxcore-log( 6529): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6529): 
,I/jxcore-log( 6529): userPath [ 'www' ]
I/jxcore-log( 6529): 
I/jxcore-log( 6529): Size 1440 2392
I/jxcore-log( 6529): 
I/jxcore-log( 6529): Screen Brightness 50
I/jxcore-log( 6529): 
E/jxcore-log( 6529): Dummy Error Log.
E/jxcore-log( 6529): 
,I/jxcore-log( 6529): getBuffer is called!!!!
I/jxcore-log( 6529): 
,I/ActivityManager( 1038): Waited long enough for: ServiceRecord{181d93b3 u0 com.google.android.music/.wear.WearMetadataSyncService}
,I/ActivityManager( 1038): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6608 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1038): Killing 5228:com.android.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager( 1038): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6653 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1038): Killing 6174:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/jxcore-log( 6529): Bluetooth turned on
I/jxcore-log( 6529): 
I/jxcore-log( 6529): WiFi turned off
I/jxcore-log( 6529): 
I/jxcore-log( 6529): WiFi turned on
I/jxcore-log( 6529): 
,I/ActivityManager( 1038): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6707 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/jxcore-log( 6529): No internet connection
I/jxcore-log( 6529): 
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6747 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 5624:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/ActivityThread( 6707): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6777 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6285:com.lge.eula/1000 (adj 15): empty #17
,I/jxcore-log( 6529): No internet connection
I/jxcore-log( 6529): 
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6813 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 5905:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager( 1038): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6867 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,I/jxcore-log( 6529): WiFi
I/jxcore-log( 6529): 
,I/ActivityManager( 1038): Killing 6441:com.google.android.talk/u0a72 (adj 15): empty #17
,I/jxcore-log( 6529): Response status code was: 200
I/jxcore-log( 6529): 
,I/jxcore-log( 6529): ****TEST TOOK:  8299  ms ****
I/jxcore-log( 6529): 
I/jxcore-log( 6529): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6529): 
,I/ActivityManager( 1038): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6915 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6107:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6951 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a,
,I/ActivityManager( 1038): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 6529:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{dc247d7 u0 com.example.hello/.MainActivity t2}
,I/ActivityManager( 1038): Force stopping com.example.hello appid=10318 user=0: pkg removed
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{dc247d7 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{dc247d7 u0 com.example.hello/.MainActivity t2 f}
,W/ActivityManager( 1038): Spurious death for ProcessRecord{1cf7461 6529:com.example.hello/u0a318}, curProc for 6529: null
,W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,I/ActivityManager( 1038): Killing 6124:com.android.contacts/u0a19 (adj 15): empty #17
,I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6984 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7017 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6147:com.android.gallery3d/u0a27 (adj 15): empty #17


samsung-SM-G800F: 
--------- beginning of /dev/log/main
D/ActivityThread( 5177): Added TimaKesytore provider
--------- beginning of /dev/log/system
I/ActivityManager( 2419): Waited long enough for: ServiceRecord{42e3f168 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/ActivityManager( 2419): Killing 3411:com.google.android.partnersetup/u0a14 (adj 15): empty #43
W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityThread( 5204): Added TimaKesytore provider
W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 2419): Process com.android.email (pid 5177) (adj 9) has died.
D/ActivityThread( 5217): Added TimaKesytore provider
D/ActivityThread( 5222): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 4358:com.sec.android.app.mss/u0a21 (adj 15): empty #43
D/ActivityThread( 5243): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 4372:com.sec.android.app.msa/u0a23 (adj 15): empty #43
I/ActivityManager( 2419): Process com.android.exchange (pid 5204) (adj 9) has died.
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityThread( 5263): Added TimaKesytore provider
D/ActivityThread( 5285): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 4386:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
D/ActivityThread( 5298): Added TimaKesytore provider
D/ActivityThread( 5320): Added TimaKesytore provider
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/ActivityManager( 2419): Killing 4399:com.android.onetimeinitializer/u0a28 (adj 15): empty #43
D/ActivityThread( 5334): Added TimaKesytore provider
,D/ActivityThread( 5338): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 4413:com.sec.pcw.device/1000 (adj 15): empty #43
,D/ActivityThread( 5363): Added TimaKesytore provider
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/ActivityThread( 5404): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 4290:com.android.chrome/u0a85 (adj 15): empty #43
,D/ActivityThread( 5421): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 4442:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/ActivityThread( 5435): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 4478:com.sec.android.service.health/u0a16 (adj 15): empty #43
,W/jxcore-log( 5334): Initializing JXcore engine
,W/jxcore-log( 5334): JXcore engine is ready
,I/ActivityManager( 2419): Killing 4621:com.policydm/1000 (adj 15): empty #43
,W/jxcore-log( 5334): Starting JXcore engine
,D/ActivityThread( 5448): Added TimaKesytore provider
,W/jxcore-log( 5334): Platform android
W/jxcore-log( 5334): 
,W/jxcore-log( 5334): Process ARCH arm
W/jxcore-log( 5334): 
,I/jxcore-log( 5334): JXcore Cordova bridge is ready!
I/jxcore-log( 5334): 
,W/jxcore-log( 5334): JXcore engine is started
,E/jxcore-log( 5334): >> samsung-SM-G800F
E/jxcore-log( 5334): 
,I/jxcore-log( 5334): Total memory 1319530496
I/jxcore-log( 5334): 
I/jxcore-log( 5334): Free memory 36302848
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): Size 720 1280
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): Screen Brightness 134
I/jxcore-log( 5334): 
E/jxcore-log( 5334): Dummy Error Log.
E/jxcore-log( 5334): 
,I/ActivityManager( 2419): Killing 4637:com.osp.app.signin/u0a44 (adj 15): empty #43
,D/ActivityThread( 5471): Added TimaKesytore provider
,I/jxcore-log( 5334): getBuffer is called!!!!
I/jxcore-log( 5334): 
,I/ActivityManager( 2419): Killing 4654:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/ActivityThread( 5586): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 3804:com.android.mms/u0a49 (adj 15): empty #43
D/ActivityThread( 5611): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 4677:com.sec.android.app.safetyassurance/u0a51 (adj 15): empty #43
,D/ActivityThread( 5631): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 4723:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/ActivityThread( 5644): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 3391:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty #43
,D/ActivityThread( 5656): Added TimaKesytore provider
,I/jxcore-log( 5334): Bluetooth turned on
I/jxcore-log( 5334): 
,I/jxcore-log( 5334): WiFi turned off
I/jxcore-log( 5334): 
,W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=5334, uid=10429 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 5334): WiFi turned on
I/jxcore-log( 5334): 
,D/ActivityThread( 5691): Added TimaKesytore provider
,I/jxcore-log( 5334): No internet connection
I/jxcore-log( 5334): 


```

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of system
,--------- beginning of main
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6520 uid=10281 gids={50281, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Displayed com.example.hello/.MainActivity: +963ms
,W/jxcore-log( 6520): Initializing JXcore engine
W/jxcore-log( 6520): JXcore engine is ready
,W/jxcore-log( 6520): Starting JXcore engine
,W/jxcore-log( 6520): Platform android
W/jxcore-log( 6520): 
,W/jxcore-log( 6520): Process ARCH arm
W/jxcore-log( 6520): 
,I/jxcore-log( 6520): JXcore Cordova bridge is ready!
I/jxcore-log( 6520): 
,W/jxcore-log( 6520): JXcore engine is started
,E/jxcore-log( 6520): >> motorola-XT1072
E/jxcore-log( 6520): 
I/jxcore-log( 6520): Total memory 916258816
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): Free memory 34254848
I/jxcore-log( 6520): 
I/jxcore-log( 6520): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6520): 
I/jxcore-log( 6520): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): userPath [ 'www' ]
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): Size 720 1184
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): Screen Brightness 82
I/jxcore-log( 6520): 
,E/jxcore-log( 6520): Dummy Error Log.
E/jxcore-log( 6520): 
,I/jxcore-log( 6520): getBuffer is called!!!!
I/jxcore-log( 6520): 
,V/ActivityManager(  881): Display changed displayId=0
,I/jxcore-log( 6520): Bluetooth turned on
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): WiFi turned off
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): WiFi turned on
I/jxcore-log( 6520): 
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6642 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6668 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6181:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/jxcore-log( 6520): No internet connection
I/jxcore-log( 6520): 
,I/ActivityManager(  881): Killing 6262:android.process.acore/u0a7 (adj 15): empty #7
,I/jxcore-log( 6520): No internet connection
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): No internet connection
I/jxcore-log( 6520): 
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6733 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 6733): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6780 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6314:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/jxcore-log( 6520): No internet connection
I/jxcore-log( 6520): 
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6814 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6358:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,I/ActivityManager(  881): Killing 6367:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6836 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6860 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6642:com.motorola.context/u0a8 (adj 15): empty #7
,I/jxcore-log( 6520): No internet connection
I/jxcore-log( 6520): 
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6917 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6733:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6948 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6780:com.android.mms/u0a23 (adj 15): empty #7
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6981 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6814:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  881): Killing 6836:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/jxcore-log( 6520): No internet connection
I/jxcore-log( 6520): 
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7005 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 7005): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7041 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6668:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7094 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6860:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/jxcore-log( 6520): No internet connection
I/jxcore-log( 6520): 
,I/ActivityManager(  881): Killing 6917:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7124 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1964): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7146 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7165 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityThread( 7146): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 6520): WiFi
I/jxcore-log( 6520): 
,I/jxcore-log( 6520): Response status code was: 200
I/jxcore-log( 6520): 
I/jxcore-log( 6520): ****TEST TOOK:  13319  ms ****
I/jxcore-log( 6520): 
I/jxcore-log( 6520): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6520): 
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7205 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Force stopping com.example.hello appid=10281 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6520:com.example.hello/u0a281 (adj 0): stop com.example.hello
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{35b55bed u0 com.example.hello/.MainActivity t29}
,V/ActivityManager(  881): Display changed displayId=0
,W/ActivityManager(  881): Spurious death for ProcessRecord{378559e1 6520:com.example.hello/u0a281}, curProc for 6520: null
,I/ActivityManager(  881): Force stopping com.example.hello appid=10281 user=0: pkg removed
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{35b55bed u0 com.example.hello/.MainActivity t29 f}
,W/ActivityManager(  881): Duplicate finish request for ActivityRecord{35b55bed u0 com.example.hello/.MainActivity t29 f}
,I/ActivityManager(  881): Killing 6948:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7291 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6981:android.process.acore/u0a7 (adj 15): empty #7
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7316 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7005:com.google.android.music:main/u0a80 (adj 15): empty #7


samsung-SM-N910C: 
--------- beginning of main
--------- beginning of system
,I/ActivityManager( 3523): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager( 3523): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager( 3523): mDVFSHelper.acquire()
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 3523): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11729 uid=10388 gids={50388, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread(11729): Added TimaKeyStore provider
V/ActivityManager( 3523): Display changed displayId=0
,D/ActivityManager( 3523): post active user change for 0
I/ActivityManager( 3523): Displayed com.example.hello/.MainActivity: +429ms
W/jxcore-log(11729): Initializing JXcore engine
W/jxcore-log(11729): JXcore engine is ready
W/jxcore-log(11729): Starting JXcore engine
W/jxcore-log(11729): Platform android
W/jxcore-log(11729): 
W/jxcore-log(11729): Process ARCH arm
W/jxcore-log(11729): 
I/jxcore-log(11729): JXcore Cordova bridge is ready!
I/jxcore-log(11729): 
W/jxcore-log(11729): JXcore engine is started
E/jxcore-log(11729): >> samsung-SM-N910C
E/jxcore-log(11729): 
I/jxcore-log(11729): Total memory 2970812416
I/jxcore-log(11729): 
I/jxcore-log(11729): Free memory 128102400
I/jxcore-log(11729): 
I/jxcore-log(11729): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11729): 
I/jxcore-log(11729): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11729): 
I/jxcore-log(11729): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(11729): 
I/jxcore-log(11729): Size 1440 2560
I/jxcore-log(11729): 
I/jxcore-log(11729): Screen Brightness 134
I/jxcore-log(11729): 
E/jxcore-log(11729): Dummy Error Log.
E/jxcore-log(11729): 
W/ActivityManager( 3523): mDVFSHelper.release()
V/ActivityThread( 4000): updateVisibility : ActivityRecord{31ac6f77 token=android.os.BinderProxy@14189d75 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,I/jxcore-log(11729): getBuffer is called!!!!
I/jxcore-log(11729): 
,I/jxcore-log(11729): Bluetooth turned on
I/jxcore-log(11729): 
,I/jxcore-log(11729): WiFi turned off
I/jxcore-log(11729): 
,W/ActivityManager( 3523): Permission Denial: getCurrentUser() from pid=11729, uid=10388 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log(11729): WiFi turned on
I/jxcore-log(11729): 
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=11814 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(11814): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11003:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11843 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(11843): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=11859 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10844:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/ActivityThread(11859): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11043:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): do not start freezing screen for locked container getKeyguardshowstate = false
,I/ActivityManager( 3523): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11875 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3523): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
W/ActivityManager( 3523): mDVFSHelper.acquire()
D/ActivityThread(11875): Added TimaKeyStore provider
,E/ActivityManager( 3523): Invalid thumbnail dimensions: 768x768
,D/ActivityManager( 3523): post active user change for 0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11899 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11117:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ActivityThread(11899): Added TimaKeyStore provider
,I/jxcore-log(11729): No internet connection
I/jxcore-log(11729): 
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11957 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11099:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/ActivityThread(11957): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11973 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11067:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/ActivityThread(11973): Added TimaKeyStore provider
,W/ActivityThread(11973): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11999 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(11999): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11191:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3523): Killing 11213:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12019 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread(12019): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12035 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(12035): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11230:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/ActivityManager( 3523): Killing 11174:com.android.providers.calendar/u0a47 (adj 15): bgCount ##32
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12051 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread(12051): Added TimaKeyStore provider
,I/jxcore-log(11729): No internet connection
I/jxcore-log(11729): 
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12068 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11245:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/ActivityThread(12068): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12084 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11300:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/ActivityThread(12084): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12107 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11318:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/ActivityThread(12107): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12125 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11358:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/ActivityThread(12125): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11373:com.android.calendar/u0a164 (adj 13): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12148 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread(12148): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11400:com.google.android.gms:car/u0a14 (adj 13): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12164 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread(12164): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12179 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10481:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,D/ActivityThread(12179): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12195 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10624:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/ActivityThread(12195): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=12262 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10508:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/ActivityThread(12262): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12290 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread(12290): Added TimaKeyStore provider
,I/jxcore-log(11729): No internet connection
I/jxcore-log(11729): 
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12310 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11583:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/ActivityThread(12310): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11601:com.sec.android.app.camera/u0a168 (adj 13): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12336 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread(12336): Added TimaKeyStore provider
,W/ActivityManager( 3523): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 3523): Killing 11616:com.sec.android.widgetapp.digitalclock/u0a97 (adj 13): bgCount ##31
,W/ActivityManager( 3523): mDVFSHelper.release()
,I/jxcore-log(11729): WiFi
I/jxcore-log(11729): 
,I/jxcore-log(11729): Response status code was: 200
I/jxcore-log(11729): 
,I/jxcore-log(11729): ****TEST TOOK:  9387  ms ****
I/jxcore-log(11729): 
I/jxcore-log(11729): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11729): 
,I/ActivityManager( 3523): Force stopping com.example.hello appid=10388 user=-1: uninstall pkg
I/ActivityManager( 3523): Killing 11729:com.example.hello/u0a388 (adj 0): stop com.example.hello
,W/ActivityManager( 3523): Force removing ActivityRecord{2dc98589 u0 com.example.hello/.MainActivity t27}: app died, no saved state
,W/ActivityManager( 3523): mDVFSHelper.acquire()
,I/ActivityManager( 3523): Force stopping com.example.hello appid=10388 user=0: pkg removed
,D/ActivityManager( 3523): handle home activity for 0
D/ActivityManager( 3523): post active user change for 0
,W/ActivityManager( 3523): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12446 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(12446): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12464 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12464): Added TimaKeyStore provider
,I/ActivityManager( 3523): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12479 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12490 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread(12479): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12490): Added TimaKeyStore provider
,I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12512 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityThread(12512): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11635:com.sec.android.widgetapp.dualclockdigital/u0a105 (adj 13): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12533 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,W/ActivityManager( 3523): mDVFSHelper.release()
,I/ActivityManager( 3523): Killing 11654:com.android.mms/u0a52 (adj 13): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12533): Added TimaKeyStore provider
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12553 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11695:com.wsomacp/u0a28 (adj 13): bgCount ##31
,D/ActivityThread(12553): Added TimaKeyStore provider
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3523): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12582 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11463:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31


samsung-SM-G900F: 
--------- beginning of main
,--------- beginning of system
I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  887): mDVFSHelper.acquire()
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  887): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=7534 uid=10191 gids={50191, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/ActivityThread( 7534): Added TimaKeyStore provider
V/ActivityManager(  887): Display changed displayId=0
,D/ActivityManager(  887): post active user change for 0
W/ActivityManager(  887): mDVFSHelper.release()
,W/jxcore-log( 7534): Initializing JXcore engine
W/jxcore-log( 7534): JXcore engine is ready
W/jxcore-log( 7534): Starting JXcore engine
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  887): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7610 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/jxcore-log( 7534): Platform android
W/jxcore-log( 7534): 
W/jxcore-log( 7534): Process ARCH arm
W/jxcore-log( 7534): 
D/ActivityThread( 7610): Added TimaKeyStore provider
I/jxcore-log( 7534): JXcore Cordova bridge is ready!
I/jxcore-log( 7534): 
W/jxcore-log( 7534): JXcore engine is started
I/ActivityManager(  887): Killing 5751:com.android.mms/u0a49 (adj 15): bgCount ##41
,E/jxcore-log( 7534): >> samsung-SM-G900F
E/jxcore-log( 7534): 
,I/jxcore-log( 7534): Total memory 1787449344
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): Free memory 73355264
I/jxcore-log( 7534): 
I/jxcore-log( 7534): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7534): 
I/jxcore-log( 7534): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): Size 1080 1920
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): Screen Brightness 134
I/jxcore-log( 7534): 
,E/jxcore-log( 7534): Dummy Error Log.
E/jxcore-log( 7534): 
,I/jxcore-log( 7534): getBuffer is called!!!!
I/jxcore-log( 7534): 
,D/ActivityManager(  887): post active user change for 0
,V/ActivityManager(  887): Display changed displayId=0
,I/jxcore-log( 7534): Bluetooth turned on
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): WiFi turned off
I/jxcore-log( 7534): 
,W/ActivityManager(  887): Permission Denial: getCurrentUser() from pid=7534, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 7534): WiFi turned on
I/jxcore-log( 7534): 
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7715 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 7715): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7739 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6563:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,D/ActivityThread( 7739): Added TimaKeyStore provider
,I/jxcore-log( 7534): No internet connection
I/jxcore-log( 7534): 
,I/ActivityManager(  887): Killing 6595:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7763 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7763): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7778 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6637:com.google.android.apps.docs/u0a97 (adj 15): bgCount ##41
,D/ActivityThread( 7778): Added TimaKeyStore provider
,I/ActivityManager(  887): Killing 6699:com.vlingo.midas/u0a32 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7793 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 7793): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7809 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6667:com.sec.android.automotive.drivelink/u0a98 (adj 15): bgCount ##41
,D/ActivityThread( 7809): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7829 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6732:com.sec.android.provider.logsprovider/u0a19 (adj 15): bgCount ##41
,D/ActivityThread( 7829): Added TimaKeyStore provider
,I/ActivityManager(  887): Killing 6745:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7857 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActivityThread( 7857): Added TimaKeyStore provider
,I/jxcore-log( 7534): No internet connection
I/jxcore-log( 7534): 
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7877 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6766:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ActivityThread( 7877): Added TimaKeyStore provider
,I/ActivityManager(  887): Killing 6784:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7896 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7896): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7953 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6802:com.samsung.android.magazine.service/u0a117 (adj 15): bgCount ##41
,D/ActivityThread( 7953): Added TimaKeyStore provider
,I/jxcore-log( 7534): No internet connection
I/jxcore-log( 7534): 
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7969 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6818:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/ActivityThread( 7969): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7999 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6888:com.sec.kidsplat.installer/u0a165 (adj 15): bgCount ##41
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 7999): Added TimaKeyStore provider
,I/ActivityManager(  887): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8019 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6906:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): bgCount ##41
,D/ActivityThread( 8019): Added TimaKeyStore provider
,I/ActivityManager(  887): Killing 6994:com.sec.spp.push:RemoteDlcProcess/u0a37 (adj 15): bgCount ##41
,W/ActivityManager(  887): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/jxcore-log( 7534): No internet connection
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): No internet connection
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): WiFi
I/jxcore-log( 7534): 
,W/ActivityManager(  887): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/jxcore-log( 7534): Response status code was: 200
I/jxcore-log( 7534): 
,I/jxcore-log( 7534): ****TEST TOOK:  11283  ms ****
I/jxcore-log( 7534): 
I/jxcore-log( 7534): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7534): 
,I/ActivityManager(  887): Force stopping com.example.hello appid=10191 user=-1: uninstall pkg
I/ActivityManager(  887): Killing 7534:com.example.hello/u0a191 (adj 0): stop com.example.hello
,W/ActivityManager(  887): Force removing ActivityRecord{6b24689 u0 com.example.hello/.MainActivity t4}: app died, no saved state
,W/ActivityManager(  887): mDVFSHelper.acquire()
,V/ActivityManager(  887): Display changed displayId=0
,I/ActivityManager(  887): Force stopping com.example.hello appid=10191 user=0: pkg removed
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=8141 uid=10178 gids={50178, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,D/ActivityThread( 8141): Added TimaKeyStore provider
,D/ActivityManager(  887): post active user change for 0
,W/ActivityManager(  887): mDVFSHelper.release()
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8162 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7013:com.sec.spp.push:RemoteNotiProcess/u0a37 (adj 15): bgCount ##41
,D/ActivityThread( 8162): Added TimaKeyStore provider
,E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  887): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  887): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8180 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6322:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ActivityThread( 8180): Added TimaKeyStore provider
,E/ActivityThread( 8180): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  887): Process com.sec.android.service.health (pid 8180)(adj 0) has died(88,610)
,I/ActivityManager(  887): Process com.osp.app.signin (pid 7829)(adj 15) has died(93,610)
,I/ActivityManager(  887): Process com.sec.android.app.shealth (pid 4871)(adj 0) has died(119,611)
,W/ActivityManager(  887): Scheduling restart of crashed service com.sec.android.app.shealth/.service.HandleAppDataService in 1000ms


```

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on SH47FWM00508 
Device test finished on 1d6a772d 
Android task is completed 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of main
,I/ActivityManager(  745): do not start freezing screen for locked container getKeyguardshowstate = false
--------- beginning of system
I/ActivityManager(  745): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
W/ActivityManager(  745): mDVFSHelper.acquire()
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  745): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6568 uid=10182 gids={50182, 9997, 1028, 1015} abi=armeabi-v7a
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 6568): Added TimaKeyStore provider
I/ActivityManager(  745): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6581 uid=10220 gids={50220, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ActivityThread( 1463): updateVisibility : ActivityRecord{3231f1f6 token=android.os.BinderProxy@33fc0589 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 6581): Added TimaKeyStore provider
V/ActivityThread( 1463): updateVisibility : ActivityRecord{3231f1f6 token=android.os.BinderProxy@33fc0589 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/ActivityManager(  745): Killing 5771:com.sec.spp.push:RemoteDlcProcess/u0a43 (adj 15): bgCount ##41
D/ActivityManager(  745): post active user change for 0
I/ActivityManager(  745): Displayed com.example.hello/.MainActivity: +549ms
W/jxcore-log( 6581): Initializing JXcore engine
W/jxcore-log( 6581): JXcore engine is ready
W/jxcore-log( 6581): Starting JXcore engine
W/ActivityManager(  745): mDVFSHelper.release()
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6642 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/jxcore-log( 6581): Platform android
W/jxcore-log( 6581): 
W/jxcore-log( 6581): Process ARCH arm
W/jxcore-log( 6581): 
D/ActivityThread( 6642): Added TimaKeyStore provider
I/ActivityManager(  745): Killing 5790:com.sec.spp.push:RemoteNotiProcess/u0a43 (adj 15): bgCount ##41
I/jxcore-log( 6581): JXcore Cordova bridge is ready!
I/jxcore-log( 6581): 
W/jxcore-log( 6581): JXcore engine is started
E/jxcore-log( 6581): >> samsung-SM-N9005
E/jxcore-log( 6581): 
I/jxcore-log( 6581): Total memory 2971471872
I/jxcore-log( 6581): 
I/jxcore-log( 6581): Free memory 352632832
I/jxcore-log( 6581): 
I/jxcore-log( 6581): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6581): 
I/jxcore-log( 6581): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6581): 
I/jxcore-log( 6581): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6581): 
I/jxcore-log( 6581): Size 1080 1920
I/jxcore-log( 6581): 
I/jxcore-log( 6581): Screen Brightness 162
I/jxcore-log( 6581): 
E/jxcore-log( 6581): Dummy Error Log.
E/jxcore-log( 6581): 
,I/jxcore-log( 6581): getBuffer is called!!!!
I/jxcore-log( 6581): 
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6692 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6692): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6709 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6709): Added TimaKeyStore provider
,I/ActivityManager(  745): Killing 5807:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/ActivityManager(  745): Killing 3334:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=6725 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,D/ActivityThread( 6725): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6745 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 5926:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,D/ActivityThread( 6745): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6764 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 4247:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/ActivityThread( 6764): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6779 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 5969:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,D/ActivityThread( 6779): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6797 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 5648:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,D/ActivityThread( 6797): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6828 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 6828): Added TimaKeyStore provider
,I/ActivityManager(  745): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6845 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 6845): Added TimaKeyStore provider
,I/ActivityManager(  745): Killing 5430:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,I/ActivityManager(  745): Killing 5500:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6881 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 6066:flipboard.app/u0a125 (adj 15): bgCount ##41
,D/ActivityThread( 6881): Added TimaKeyStore provider
,I/ActivityManager(  745): Killing 5607:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/jxcore-log( 6581): Bluetooth turned on
I/jxcore-log( 6581): 
,I/jxcore-log( 6581): WiFi turned off
I/jxcore-log( 6581): 
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=6581, uid=10220 requires android.permission.INTERACT_ACROSS_USERS
,I/jxcore-log( 6581): WiFi turned on
I/jxcore-log( 6581): 
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6915 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/ActivityThread( 6915): Added TimaKeyStore provider
,V/ActivityThread( 6581): updateVisibility : ActivityRecord{2814c887 token=android.os.BinderProxy@1ea1e250 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/ActivityManager(  745): Killing 6191:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,V/ActivityManager(  745): Display changed displayId=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6972 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 6972): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6988 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 6209:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,I/jxcore-log( 6581): No internet connection
I/jxcore-log( 6581): 
,D/ActivityThread( 6988): Added TimaKeyStore provider
,I/ActivityManager(  745): Killing 5856:sstream.app/u0a25 (adj 15): bgCount ##41
,W/ActivityManager(  745): getTasks: caller 10102 does not hold GET_TASKS; limiting output
,W/ActivityManager(  745): getTasks: caller 10102 does not hold GET_TASKS; limiting output
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7007 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7007): Added TimaKeyStore provider
,I/ActivityManager(  745): Killing 5904:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 7027): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6581): No internet connection
I/jxcore-log( 6581): 
,I/ActivityManager(  745): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7044 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 6262:com.policydm/1000 (adj 15): bgCount ##41
,D/ActivityThread( 7044): Added TimaKeyStore provider
,I/ActivityManager(  745): Killing 4903:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7065 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread( 7065): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7089 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  745): Killing 6283:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,I/jxcore-log( 6581): No internet connection
I/jxcore-log( 6581): 
,D/ActivityThread( 7089): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7108 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 5447:com.sec.android.gallery3d/u0a53 (adj 13): bgCount ##41
,D/ActivityThread( 7108): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7129 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 6334:com.sec.android.app.soundalive/u0a64 (adj 13): bgCount ##41
,D/ActivityThread( 7129): Added TimaKeyStore provider
,I/jxcore-log( 6581): No internet connection
I/jxcore-log( 6581): 
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7161 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 5666:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##41
,D/ActivityThread( 7161): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7179 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 6354:com.google.android.apps.docs/u0a112 (adj 13): bgCount ##41
,D/ActivityThread( 7179): Added TimaKeyStore provider
,I/jxcore-log( 6581): No internet connection
I/jxcore-log( 6581): 
,I/ActivityManager(  745): Killing 6379:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##41
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7275 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread( 7275): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7295 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  745): Killing 6403:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): bgCount ##41
,I/jxcore-log( 6581): WiFi
I/jxcore-log( 6581): 
,D/ActivityThread( 7295): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7317 uid=10112 gids={50112, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6581): Response status code was: 200
I/jxcore-log( 6581): 
I/jxcore-log( 6581): ****TEST TOOK:  11414  ms ****
I/jxcore-log( 6581): 
I/jxcore-log( 6581): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6581): 
D/ActivityThread( 7317): Added TimaKeyStore provider
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7345 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,D/ActivityThread( 7345): Added TimaKeyStore provider
,I/ActivityManager(  745): Killing 6418:com.samsung.helphub/1000 (adj 13): bgCount ##41
,I/ActivityManager(  745): Killing 6435:com.sec.kidsplat.installer/u0a189 (adj 13): bgCount ##41
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7368 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread( 7368): Added TimaKeyStore provider
,I/ActivityManager(  745): Force stopping com.example.hello appid=10220 user=-1: uninstall pkg
,I/ActivityManager(  745): Killing 6581:com.example.hello/u0a220 (adj 0): stop com.example.hello
,I/ActivityManager(  745):   Force finishing activity ActivityRecord{16383628 u0 com.example.hello/.MainActivity t2}
,W/ActivityManager(  745): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager(  745): Spurious death for ProcessRecord{2f0f9a4e 6581:com.example.hello/u0a220}, curProc for 6581: null
,I/ActivityManager(  745): Force stopping com.example.hello appid=10220 user=0: pkg removed
,V/ActivityThread( 1463): updateVisibility : ActivityRecord{3231f1f6 token=android.os.BinderProxy@33fc0589 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,I/ActivityManager(  745): Killing 5216:com.sec.android.app.samsungapps/u0a45 (adj 13): bgCount ##41
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7432 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread( 7432): Added TimaKeyStore provider
,I/ActivityManager(  745): Process com.google.android.apps.plus (pid 5165)(adj 9) has died(415,1396)
,E/ActivityThread( 7432): Unable to setupGraphicsSupport due to missing cache directory
,I/ActivityManager(  745): Process com.sec.android.app.samsungapps (pid 7432)(adj 9) has died(413,1396)
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7450 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,D/ActivityThread( 7450): Added TimaKeyStore provider
,E/ActivityThread( 7450): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  745): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7466 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityThread( 7466): Added TimaKeyStore provider
,I/ActivityManager(  745): Process com.sec.android.service.health (pid 7450)(adj 0) has died(409,1396)
,E/ActivityThread( 7466): Unable to setupGraphicsSupport due to missing cache directory
,E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  745): checkUser: useridlist=null, currentuser=0


motorola-Nexus 6: 
--------- beginning of main
--------- beginning of system
I/ActivityManager(  821): Start proc 3580:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
I/ActivityManager(  821): Killing 3153:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
I/ActivityManager(  821): Start proc 3620:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,I/ActivityManager(  821): Start proc 3646:com.google.android.gm/u0a78 for broadcast com.google.android.gm/.widget.GmailWidgetProvider
I/ActivityManager(  821): Killing 3213:com.android.chrome/u0a40 (adj 15): empty #17
D/ActivityThread( 3646): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
I/ActivityManager(  821): Killing 3273:com.google.android.apps.photos/u0a71 (adj 15): empty #17
I/ActivityManager(  821): Start proc 3688:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  821): Start proc 3708:com.example.hello/u0a272 for activity com.example.hello/.MainActivity
W/ActivityManager(  821): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  821): Killing 3297:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3769:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver
I/ActivityManager(  821): Displayed com.example.hello/.MainActivity: +459ms
W/jxcore-log( 3708): Initializing JXcore engine
W/jxcore-log( 3708): JXcore engine is ready
W/jxcore-log( 3708): Starting JXcore engine
I/ActivityManager(  821): Killing 3339:com.google.android.deskclock/u0a44 (adj 15): empty #17
W/jxcore-log( 3708): Platform android
W/jxcore-log( 3708): 
W/jxcore-log( 3708): Process ARCH arm
W/jxcore-log( 3708): 
I/ActivityManager(  821): Killing 3319:com.qualcomm.timeservice/1000 (adj 15): empty #18
I/jxcore-log( 3708): JXcore Cordova bridge is ready!
I/jxcore-log( 3708): 
W/jxcore-log( 3708): JXcore engine is started
E/jxcore-log( 3708): >> motorola-Nexus 6
E/jxcore-log( 3708): 
I/jxcore-log( 3708): Total memory 3113791488
I/jxcore-log( 3708): 
I/jxcore-log( 3708): Free memory 986181632
I/jxcore-log( 3708): 
I/jxcore-log( 3708): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3708): 
I/jxcore-log( 3708): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3708): 
I/jxcore-log( 3708): userPath [ 'www' ]
I/jxcore-log( 3708): 
I/jxcore-log( 3708): Size 1440 2392
I/jxcore-log( 3708): 
I/jxcore-log( 3708): Screen Brightness 82
I/jxcore-log( 3708): 
E/jxcore-log( 3708): Dummy Error Log.
E/jxcore-log( 3708): 
,I/ActivityManager(  821): Start proc 3830:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.InternalReceiver
,I/jxcore-log( 3708): getBuffer is called!!!!
I/jxcore-log( 3708): 
,I/ActivityManager(  821): Killing 3094:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,I/jxcore-log( 3708): Bluetooth turned on
I/jxcore-log( 3708): 
,I/jxcore-log( 3708): WiFi turned off
I/jxcore-log( 3708): 
,I/jxcore-log( 3708): WiFi turned on
I/jxcore-log( 3708): 
,I/ActivityManager(  821): Start proc 3899:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/ActivityManager(  821): Start proc 3925:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  821): Killing 2847:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3362:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3954:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  821): Killing 3380:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3487:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/jxcore-log( 3708): No internet connection
I/jxcore-log( 3708): 
,I/ActivityManager(  821): Killing 3508:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3974:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/jxcore-log( 3708): No internet connection
I/jxcore-log( 3708): 
,I/ActivityManager(  821): Start proc 4031:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  821): Killing 3538:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3688:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/jxcore-log( 3708): No internet connection
I/jxcore-log( 3708): 
,I/jxcore-log( 3708): No internet connection
I/jxcore-log( 3708): 
,I/jxcore-log( 3708): WiFi
I/jxcore-log( 3708): 
,I/jxcore-log( 3708): Response status code was: 200
I/jxcore-log( 3708): 
,I/jxcore-log( 3708): ****TEST TOOK:  10351  ms ****
I/jxcore-log( 3708): 
,I/jxcore-log( 3708): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3708): 
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3708:com.example.hello/u0a272 (adj 0): stop com.example.hello
,W/ActivityManager(  821): Force removing ActivityRecord{12665224 u0 com.example.hello/.MainActivity t20}: app died, no saved state
,I/ActivityManager(  821): Force stopping com.example.hello appid=10272 user=0: pkg removed
,W/ActivityManager(  821): Spurious death for ProcessRecord{3e9e4b76 3708:com.example.hello/u0a272}, curProc for 3708: null
,I/ActivityManager(  821): Start proc 4134:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  821): Start proc 4155:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ActivityManager(  821): Killing 3620:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{1b4aada6 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,--------- beginning of crash
,I/ActivityManager(  821): Start proc 4205:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/ActivityManager(  821): Start proc 4224:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,I/ActivityManager(  821): Process com.google.android.gms (pid 1771) has died
,W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 11000ms
,W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.mdm.services.NetworkQualityAndroidService in 30999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 40999ms
,I/ActivityManager(  821): Start proc 4247:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService


HTC-HTC One_M8: 
--------- beginning of system
--------- beginning of main
I/ActivityManager(  892): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4418 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  892): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4437 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
I/ActivityManager(  892): Killing 3822:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  892): Recipient 3822
I/ActivityManager(  892): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4455 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  892): Start proc com.htc.bgp for content provider com.android.providers.calendar/com.htc.providers.calendar.HtcCalendarProvider: pid=4472 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
I/ActivityManager(  892): Killing 3860:com.htc.HTCSpeaker/u0a57 (adj 15): empty #17
I/ActivityManager(  892): Recipient 3860
I/ActivityManager(  892): Killing 2169:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
I/ActivityManager(  892): Recipient 2169
I/ActivityManager(  892): Killing 3896:com.htc.lmw/u0a61 (adj 15): empty #17
I/ActivityManager(  892): Recipient 3896
I/ActivityManager(  892): Killing 3981:com.android.managedprovisioning/u0a66 (adj 15): empty #17
I/ActivityManager(  892): Recipient 3981
I/ActivityManager(  892): Killing 2063:com.google.android.gms/u0a25 (adj 15): empty #17
I/ActivityManager(  892): Recipient 2063
I/ActivityManager(  892): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4498 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
I/ActivityManager(  892): Killing 4067:com.htc.cs.pns/u0a74 (adj 15): empty #17
I/ActivityManager(  892): Recipient 4067
I/ActivityManager(  892): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4519 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  892): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4555 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  892): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4575 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  892): Killing 4100:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
I/ActivityManager(  892): Recipient 4100
W/ActivityThread( 4555): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  892): Killing 4123:com.htc.showme/u0a85 (adj 15): empty #17
I/ActivityManager(  892): Recipient 4123
,I/ActivityManager(  892): Killing 4142:com.htc.feedback/u0a87 (adj 15): empty #17
W/ActivityThread( 4575): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  892): Recipient 4142
I/ActivityManager(  892): Killing 4182:com.htc.updater/u0a88 (adj 15): empty #17
I/ActivityManager(  892): Recipient 4182
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  892): Delay finish: com.google.android.gms/.tron.AlarmReceiver
I/ActivityManager(  892): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4643 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  892): Resuming delayed broadcast
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4721 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  892): Displayed com.example.hello/.MainActivity: +673ms
,W/jxcore-log( 4643): Initializing JXcore engine
W/jxcore-log( 4643): JXcore engine is ready
,W/jxcore-log( 4643): Starting JXcore engine
,W/jxcore-log( 4643): Platform android,
W/jxcore-log( 4643): 
W/jxcore-log( 4643): Process ARCH arm
W/jxcore-log( 4643): 
,I/jxcore-log( 4643): JXcore Cordova bridge is ready!
I/jxcore-log( 4643): 
,W/jxcore-log( 4643): JXcore engine is started
,I/ActivityManager(  892): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4768 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/jxcore-log( 4643): >> HTC-HTC One_M8
E/jxcore-log( 4643): 
I/jxcore-log( 4643): Total memory 1912020992
I/jxcore-log( 4643): 
I/jxcore-log( 4643): Free memory 137486336
I/jxcore-log( 4643): 
I/jxcore-log( 4643): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4643): 
I/jxcore-log( 4643): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4643): 
,I/jxcore-log( 4643): userPath [ 'www' ]
I/jxcore-log( 4643): 
,I/jxcore-log( 4643): Size 1080 1776,
I/jxcore-log( 4643): 
,I/jxcore-log( 4643): Screen Brightness 142
I/jxcore-log( 4643): 
E/jxcore-log( 4643): Dummy Error Log.
E/jxcore-log( 4643): 
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{2ce1c94a u0 com.google.android.gms/.gcm.GcmService},
,I/jxcore-log( 4643): getBuffer is called!!!!,
I/jxcore-log( 4643): 
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4856 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 4253:com.htc.android.worldclock/u0a96 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4253
,I/ActivityManager(  892): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4882 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 4220:com.htc.videocenter/u0a91 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4220
,I/ActivityManager(  892): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4917 uid=10115 gids={50115, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 4294:com.htc.tiber2/u0a91 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4294
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  892): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4958 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ActivityManager(  892): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  892): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 4917): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@12a0181f that was originally bound here
E/ActivityThread( 4917): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@12a0181f that was originally bound here
E/ActivityThread( 4917): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4917): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4917): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4917): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
E/ActivityThread( 4917): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4917): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4917): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4917): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4917): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4917): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4917): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4917): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4917): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4917): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/ActivityThread( 4917): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4917): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  892): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4991 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  892): Unbind failed: could not find connection for android.os.BinderProxy@126afc28
,W/ActivityThread( 4958): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  892): Killing 4312:com.google.android.configupdater/u0a104 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4312,
,W/ActivityThread( 4991): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  892): Start proc com.fitbit.FitbitMobile for broadcast com.fitbit.FitbitMobile/.NetworkStateReceiver: pid=5031 uid=10023 gids={50023, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 4200:com.htc.cs.dm/u0a105 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4200,
,I/ActivityManager(  892): Killing 4357:com.htc.backupreset/1000 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 4357
,I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5078 uid=10080 gids={50080, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  892): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.NetworkChangeReceiver: pid=5097 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a,
I/ActivityManager(  892): Killing 4376:com.htc.htccupd/u0a13 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4376,
,I/ActivityManager(  892): Start proc com.twitter.android for broadcast com.twitter.android/.client.AppBroadcastReceiver: pid=5127 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 4575): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  892): Killing 4437:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4437
,I/ActivityManager(  892): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5168 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4418:com.android.settings:remote/1000 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 4418
,W/ActivityThread( 5168): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  892): Killing 4498:com.android.smith/1000 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4498,
,I/ActivityManager(  892): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5204 uid=10169 gids={50169, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{394a7753 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  892): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5273 uid=10102 gids={50102, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager(  892): Killing 4455:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4455,
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5300 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 4555:com.google.android.gms:car/u0a25 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4555,
,I/jxcore-log( 4643): Bluetooth turned on,
I/jxcore-log( 4643): 
,I/jxcore-log( 4643): WiFi turned off
I/jxcore-log( 4643): 
,I/jxcore-log( 4643): WiFi turned on
I/jxcore-log( 4643): 
,I/ActivityManager(  892): Start proc com.android.settings for service com.android.settings/.wifi.WISPrService: pid=5347 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5365 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5384 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4519:com.android.vending/u0a75 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4519,
,I/ActivityManager(  892): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=5411 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4037:com.htc.sense.mms/u0a67 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4037,
,I/ActivityManager(  892): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=5433 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4768:com.google.android.youtube/u0a186 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4768
,I/ActivityManager(  892): Killing 4882:com.google.android.partnersetup/u0a28 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4882
,I/ActivityManager(  892): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5456 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.dm2.ConfigChangeReceiver: pid=5482 uid=10032 gids={50032, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 4856:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 4856
,I/ActivityManager(  892): Killing 4917:com.google.android.gm/u0a115 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 4917
,I/ActivityManager(  892): Killing 4991:com.google.android.music:main/u0a167 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 4991
,W/ActivityManager(  892): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  892): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,I/jxcore-log( 4643): No internet connection,
I/jxcore-log( 4643): 
,I/ActivityManager(  892): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5512 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=armeabi-v7a,
,I/ActivityManager(  892): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5552 uid=10037 gids={50037, 9997} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 5031:com.fitbit.FitbitMobile/u0a23 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5031
,I/ActivityManager(  892): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5585 uid=10079 gids={50079, 9997} abi=armeabi-v7a
I/ActivityManager(  892): Killing 5078:com.google.android.setupwizard/u0a80 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5078,
,I/ActivityManager(  892): Killing 5097:com.htc.cs.dm/u0a105 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5097
,I/ActivityManager(  892): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5609 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 5127:com.twitter.android/u0a181 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5127,
,I/ActivityManager(  892): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 5347): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  892): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 5347): Failed to find provider info for com.htc.vowifi
,I/jxcore-log( 4643): No internet connection,
I/jxcore-log( 4643): 
,I/ActivityManager(  892): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5650 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 3915:com.android.defcontainer/u0a15 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 3915
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5674 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/ActivityThread( 5650): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  892): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5706 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Waited long enough for: ServiceRecord{2db4bafd u0 com.htc.HTCSpeaker/.NGFService},
,I/ActivityManager(  892): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=5733 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5204:com.google.android.apps.magazines/u0a169 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5204
,I/ActivityManager(  892): Killing 5273:com.android.chrome/u0a102 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5273
,I/ActivityManager(  892): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5764 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5783 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5809 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 5365:com.htc.mobiledata/u0a48 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5365,
,I/ActivityManager(  892): Killing 5433:com.htc.sense.news/u0a77 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5433,
,I/ActivityManager(  892): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5854 uid=10029 gids={50029, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a,
,I/jxcore-log( 4643): No internet connection,
I/jxcore-log( 4643): 
,I/ActivityManager(  892): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5886 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5384:com.htc.mobiledata:remote/u0a48 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5384
,I/ActivityManager(  892): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5935 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager(  892): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5960 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 5482:com.htc.csrecommend/u0a32 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5482
,I/ActivityManager(  892): Killing 5512:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5512
,I/ActivityManager(  892): Killing 4721:com.google.android.talk/u0a120 (adj 15): empty #18
,I/ActivityManager(  892): Recipient 4721,
,W/ActivityThread( 5960): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  892): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5992 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=6013 uid=10051 gids={50051, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 5552:com.htc.widget.hmsproc1/u0a37 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5552
,I/jxcore-log( 4643): WiFi,
I/jxcore-log( 4643): 
,I/ActivityManager(  892): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=6035 uid=10082 gids={50082, 9997, 5001, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 5585:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5585,
,I/ActivityManager(  892): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver,
,I/ActivityManager(  892): Resuming delayed broadcast,
,I/ActivityManager(  892): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver,
,I/ActivityManager(  892): Resuming delayed broadcast,
,I/jxcore-log( 4643): Response status code was: 200
I/jxcore-log( 4643): 
,I/jxcore-log( 4643): ****TEST TOOK:  9344  ms ****
I/jxcore-log( 4643): 
I/jxcore-log( 4643): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4643): 
,I/ActivityManager(  892): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  892): Resuming delayed broadcast
,I/ActivityManager(  892): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  892): Resuming delayed broadcast
,I/ActivityManager(  892): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  892): Resuming delayed broadcast
,I/ActivityManager(  892): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6068 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4958:com.google.android.gms.wearable/u0a25 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 4958
,I/ActivityManager(  892): Killing 5674:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5674
,I/ActivityManager(  892): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=6096 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5300:com.google.android.apps.plus/u0a176 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5300,
,I/ActivityManager(  892): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg,
I/ActivityManager(  892): Killing 4643:com.example.hello/u0a380 (adj 0): stop com.example.hello
,I/ActivityManager(  892): Recipient 4643
,W/ActivityManager(  892): Force removing ActivityRecord{3cf5a57d u0 com.example.hello/.MainActivity t27}: app died, no saved state
,I/ActivityManager(  892): Force stopping com.example.hello appid=10380 user=0: pkg removed
,W/ActivityManager(  892): Spurious death for ProcessRecord{2d19cb8c 4643:com.example.hello/u0a380}, curProc for 4643: null
,I/ActivityManager(  892): Killing 5706:com.htc.calendar/u0a10 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5706
,I/ActivityManager(  892): Killing 5733:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  892): Recipient 5733,
,I/ActivityManager(  892): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6119 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,W/ActivityThread( 6119): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/ActivityManager(  892): Killing 5764:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5764,
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6143 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a,
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6164 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5809:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5809,
,E/ActivityManager(  892): App crashed! Process: com.google.android.gms
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6208 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  892): Killing 5411:com.htc.task/u0a72 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5411
,I/ActivityManager(  892): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0,
,E/ActivityManager(  892): TransactionSize: scheduleLaunchActivity(), TransactionTooLargeException, data size = 4300, Intent = Intent { act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras) },
W/ActivityManager(  892): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  892): android.os.TransactionTooLargeException
W/ActivityManager(  892): 	at android.os.BinderProxy.transactNative(Native Method),
W/ActivityManager(  892): 	at android.os.BinderProxy.transact(Binder.java:504)
W/ActivityManager(  892): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:851)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1203)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1303)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:1327)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:2989)
W/ActivityManager(  892): 	at com.android.server.am.ActivityStackSupervisor.attachApplicationLocked(ActivityStackSupervisor.java:550)
,W/ActivityManager(  892): 	at com.android.server.am.ActivityManagerService.attachApplicationLocked(ActivityManagerService.java:6576)
W/ActivityManager(  892): 	at com.android.server.am.ActivityManagerService.attachApplication(ActivityManagerService.java:6638)
W/ActivityManager(  892): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:486)
W/ActivityManager(  892): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
W/ActivityManager(  892): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  892): Recipient 6164,
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for activity com.google.android.apps.docs/.app.ErrorNotificationActivity: pid=6226 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/ActivityManager(  892): Spurious death for ProcessRecord{1ad444b3 6226:com.google.android.apps.docs/u0a107}, curProc for 6164: null
,E/ActivityThread( 1500): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
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
,I/ActivityManager(  892): Activity reported stop, but no longer stopping: ActivityRecord{26bf5322 u0 com.htc.launcher/.Launcher t26}
,I/ActivityManager(  892): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=6258 uid=10088 gids={50088, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5886:com.htc.android.mail:sync/u0a65 (adj 15): empty #17,
,I/ActivityManager(  892): Recipient 5886
,I/ActivityManager(  892): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6296 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
,I/ActivityManager(  892): Recipient 6226
,I/ActivityManager(  892): Process com.google.android.apps.docs (pid 6226) has died
,W/ActivityManager(  892): Force removing ActivityRecord{3127c37a u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t28}: app died, no saved state


```

####Node name: thali06
Console output:
```
Error: problem deploying Android apk(/home/pi/test/builder/builds/49526184549c368/build_android/android_0_49526184549c368.apk) to device 7970f88c error: device not found
- waiting for device -
rm: /data/local/tmp/android_0_49526184549c368.apk: No such file or directory



Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.

```



#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":14,"cancel":1}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184549c368/Sub/serverApp/index.js',
  '{"devices":{"android":14}}' ]

JSON { devices: { android: 14 } }


```

