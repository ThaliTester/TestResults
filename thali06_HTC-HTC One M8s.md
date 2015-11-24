#### Test 50388019b17f598_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/MediaProvider( 4150): [update][34]#0#
D/MediaScannerServiceEx( 4150): [disAliveExtStorageRows]--1, 0
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4629): -onCreate()
--------- beginning of system
W/ResourcesManager( 4479): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  917): Recipient 4014
,W/ResourcesManager( 4479): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
E/MediaScannerServiceEx( 4150): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 4150): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 4150): [handleExternalVolume] ext storage
D/MediaProviderUtils( 4150): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4150): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4150): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4150): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 4150): [AliveExtStorageRows]+65537, 11223344
W/ResourcesManager( 4479): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
D/MediaProvider( 4150): [update][5]#0#
D/MediaProvider( 4150): [update][2]#0#
D/MediaProvider( 4150): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 4150): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 4150): [update][10]#1#
D/MediaScannerServiceEx( 4150): [AliveExtStorageRows]-0, 0
D/PMS     (  917): acquireWL(4d4f927): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4150 10017 null
D/MediaScanner( 4150): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
I/DeviceManagement( 4479): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686
V/Settings:HtcSettingsApplication( 4629): [4629/4629] onCreate()
W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
I/DeviceManagement( 4479): EnabledAppBuilder: Found 8 DM enabled apps.
I/DeviceManagement( 4479): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 4479): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/ActivityManager(  917): Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4657 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/DeviceManagement( 4479): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 4479): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 4479): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
I/DeviceManagement( 4479): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
D/TetherSettings( 4629): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4629): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4629): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4629): Cust_ConnectToPC   : spcsc>false
D/        ( 4629): Cust_ConnectToPC   : IPT>true
D/        ( 4629): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4629): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/DeviceManagement( 4479): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
E/SmartNS_Utility( 4629): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4629): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4629): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 4629): setISNotification
I/DeviceManagement( 4479): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
D/SmartNS_Utility( 4629): usb_cable_connect = 1
D/SmartNS_Utility( 4629): usb_denied = 0
I/DeviceManagement( 4479): Perf: Scan enabled apps - complete: 1160 ms
I/DeviceManagement( 4479): Perf: *** Enabled app cache update - complete: 1161 ms
I/DeviceManagement( 4479): Perf: *** Config cache update - start...
I/DeviceManagement( 4479): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4479): ConfigCacheController: *** Updating stale config cache entries...
I/SmartNS_PSService( 4629): usb notificaiton:true
E/WifiStateMachine(  917): WiFiDisplay: getWifidisplayApEnabled=false
I/ActionCombine( 4629): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/DeviceManagement( 4479): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 4479): ConfigCacheController: No changes need to be broadcasted.
V/Settings:HtcSettingsApplication( 4657): [4657/4657] onCreate()
D/SmartNS_Utility( 4629): usb_cable_connect = 1
D/SmartNS_Utility( 4629): usb_denied = 0
I/SmartNS_PSService( 4629): usb notificaiton:true
E/WifiStateMachine(  917): WiFiDisplay: getWifidisplayApEnabled=false
I/DeviceManagement( 4479): AlarmController: Scheduling TTL alarm for: 2015.11.25 at 07:32:26.664 CET (due to: com.htc.launcher)
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1219): reapply : com.android.settings 1 36
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4479, uid=10099, userID:0
I/DeviceManagement( 4479): Perf: *** Config cache update - complete: 35 ms
I/DeviceManagement( 4479): Perf: *** Cache update - complete: 1200 ms
I/DeviceManagement( 4479): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@4f47ad8]
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/ActivityManager(  917): Killing 4046:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
D/Process (  917): killProcessQuiet, pid=4046
I/DeviceManagement( 4479): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3640cde9] args=[Bundle[mParcelledData.dataSize=132]]
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/DeviceManagement( 4479): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 4479): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/RemoteViews( 1219): reapply : com.android.settings 1 36
I/DeviceManagement( 4479): SessionStateController: Checking invariants...
E/cutils-trace( 4655): Error opening trace file: Permission denied (13)
I/ActivityManager(  917): Recipient 4046
D/CustomizationManager( 4655): ====startRecUseTime====
D/htc.customization.log.level( 4655):  is 
W/CustomizationLogLevel( 4655): Level value is invalid, use default level 2
I/DeviceManagement( 4479): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 4479): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3640cde9]
I/DeviceManagement( 4479): WorkflowService: Stopping workflow service
D/Process (  917): killProcessQuiet, pid=4082
I/ActivityManager(  917): Killing 4082:com.htc.lmw/u0a58 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ContextImpl(  917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
D/CustomizationManager( 4655):  Read ACC file spent 0.043 (s)
D/CIDMapFileReader( 4655): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4655): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4655): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4655): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4655): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4655): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4655): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4655): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4655): Parsing tag category name = system
I/CustomizationCIDLoader( 4655): Parsing tag category name = application
I/CustomizationCIDLoader( 4655): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4655): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4655): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4655): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4655): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4655): add string-array item, value = 42507
I/CustomizationCIDLoader( 4655): add string-array item, value = 21902
I/CustomizationCIDLoader( 4655): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4655): add string-array item, value = 23420
I/CustomizationCIDLoader( 4655): add string-array item, value = 22299
I/CustomizationCIDLoader( 4655): add string-array item, value = 24002
I/CustomizationCIDLoader( 4655): add string-array item, value = 23210
I/CustomizationCIDLoader( 4655): add string-array item, value = 23205
I/CustomizationCIDLoader( 4655): add string-array item, value = 23806
I/CustomizationCIDLoader( 4655): add string-array item, value = 23430
I/CustomizationCIDLoader( 4655): add string-array item, value = 23408
I/CustomizationCIDLoader( 4655): add string-array item, value = 27205
I/CustomizationCIDLoader( 4655): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4655): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4655):  Read CID file spent 0.092 (s)
D/CustomizationManager( 4655):  All configurations done spent 0.092 (s)
I/ActivityManager(  917): Recipient 4082
D/Process (  917): killProcessQuiet, pid=4116
I/ActivityManager(  917): Killing 4116:com.android.managedprovisioning/u0a63 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  917): acquireHCC(1875b479): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 917 1000 null
D/PMS     (  917): acquireHCC(15b0e5be): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 917 1000 null
I/ActivityManager(  917): Recipient 4116
E/WifiStateMachine(  917): handleMessage: E msg.what=131155
E/WifiStateMachine(  917): processMsg: ConnectedState
E/WifiStateMachine(  917):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:2958] from screen [on:0 period:982015235] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  917): processMsg: L2ConnectedState
E/WifiStateMachine(  917):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:982015236] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  917):  get link layer stats 0
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1350): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1350): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  917): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  917): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  917): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-55 "NG700"WPA_PSK
E/WifiStateMachine(  917): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.78 txretriesrate=0.00 rxrate=4.50 userTriggerdPenalty0
E/WifiStateMachine(  917):  good link -> stuck count =0
E/WifiStateMachine(  917):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  917):  isHighRSSI       ---> score=61
I/ActivityManager(  917): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4655 on display 0
W/asset   (  917): Copying FileAsset 0x5565a5df10 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  917): acquireWL(13941f35): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 917 1000 null
I/AnimationUtil(  917): isHTCRecent(HelloWorld/Recent screens.)/4
I/htcbackup-core( 4503): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
I/FeedHostManager( 1599): [onPause]
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  917): handleMessage: X
I/FeedProviderManager( 1599): onPause
I/FeedHostManager( 1599): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@28e530b1
I/SocialFeedProvider( 1599): +onPause
I/SocialFeedProvider( 1599): -onPause
I/ActivityManager(  917): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4698 uid=9987 gids={49987, 9997} abi=arm64-v8a
W/HtcSystemUPManager(  917): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  917): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4718 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/AlarmManager(  917): sending alarm PendingIntent{2811ee96: PendingIntentRecord{24587a17 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=2, w=1447326412457, Int=604800000
D/SmartDim(  917): Init customizeScreenOffDelayClass error
D/WifiWatchdogStateMachine(  917): RSSI current: 3 new: -56, 3
I/TrimMemoryManager( 1599): [trimMemory] 20
W/BroadcastQueue(  917): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{e6fade9 u0 ReceiverList{3e8d2670 917 system/1000/u0 local:2360a0b3}}
I/SensorManager(  917): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2625ffed, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  917): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  917): enable: get sensor name = Accelerometer Sensor
W/SensorService(  917): pid=917, uid=1000
W/SensorService(  917): Active sensors: size = 3
W/SensorService(  917): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  917): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  917): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  917): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2625ffed, eanble = 1, strlen(mName) = 36
W/SensorService(  917): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  917): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@936cac3
W/SensorService(  917): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3a91dfc1
W/SensorService(  917): Listener[2] = com.htc.smartdim.sensor_eye@2625ffed
W/SensorService(  917): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  917): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2625ffed, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  917): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  917): enable: get sensor name = CM36686 Proximity sensor
W/SensorService(  917): pid=917, uid=1000
W/SensorService(  917): Active sensors: size = 4
W/SensorService(  917): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  917): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  917): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  917): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  917): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2625ffed, eanble = 1, strlen(mName) = 36
W/SensorService(  917): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  917): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@936cac3
W/SensorService(  917): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3a91dfc1
W/SensorService(  917): Listener[2] = com.htc.smartdim.sensor_eye@2625ffed
W/SensorService(  917): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  917):  packet count Tx=54 Rx=78
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
I/RemoteViews( 1219): reapply : com.htc.backup 3 38
I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1219): apply : com.htc.backup 1 1 1 5
I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1219): apply : com.htc.backup 0 2 0 5
I/RemoteViews( 1219): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1219): apply : com.htc.backup 1 3 0 5
I/RemoteViews( 1219): reapply : com.htc.backup 11 50
,I/art     (  917): Explicit concurrent mark sweep GC freed 16221(835KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.305ms total 156.636ms
D/StatusBarManagerService(  917): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  917): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  917): hiding MENU key
W/asset   ( 4718): Copying FileAsset 0xac284a10 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  917): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4745 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  917): killProcessQuiet, pid=4266
I/ActivityManager(  917): Killing 4266:com.htc.cs.pns/u0a71 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/SensorManager(  917): dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@2625ffed
D/MediaScanner( 4150):  prescan time: 570ms
D/MediaScanner( 4150):     scan time: 492ms
D/MediaScanner( 4150): postscan time: 1ms
D/MediaScanner( 4150):    total time: 1063ms
D/MediaScanner( 4150): -----------------------------------------------------------------
D/MediaScanner( 4150): firstscan(media) time: 309ms
D/MediaScanner( 4150): secondscan(non-media) time: 183ms
D/MediaScanner( 4150):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4150):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4150):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4150):  [Total]    File(Image+Video+Audio+Others) in database : 1546
D/MediaProvider( 4150): [delete][8]
D/MediaProvider( 4150): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 4150): [recoverParentNodes] - 0
D/MediaProvider( 4150): [update][4]
D/MediaScannerServiceEx( 4150): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 4150): [updateImage]+
D/MediaScannerServiceEx( 4150): [updateImage]-0
I/ActivityManager(  917): Recipient 4266
D/PMS     (  917): releaseWL(4d4f927): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 4150): [3] scan finished
D/MediaProviderUtils( 4150): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4150): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4150): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4150): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 4150): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 4150): [disAliveExtStorageRows]+131073
D/MediaProvider( 4150): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 4150): [update][7]#1#
E/WifiDataStallTracker(  917): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  917): updateDataStallInfo: mDataStallTxRxSum={txSum=40 rxSum=29} preTxRxSum={txSum=40 rxSum=29}
D/WifiDataStallTracker(  917): updateDataStallInfo: NONE
D/WifiDataStallTracker(  917): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/ActivityManager(  917): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4767 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  917): Killing 4299:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  917): killProcessQuiet, pid=4299
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/WebViewFactory( 4718): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/MediaProvider( 4150): [update][104]#0#
D/MediaScannerServiceEx( 4150): [disAliveExtStorageRows]--1, 0
I/ActivityManager(  917): Recipient 4299
D/MediaProviderUtils( 4150): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4150): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4150): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4150): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 4150): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 4150): [disAliveExtStorageRows]+196609
D/MediaProvider( 4150): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 4150): [update][33]#1#
I/LibraryLoader( 4718): Time to load native libraries: 18 ms (timestamps 8743-8761)
I/LibraryLoader( 4718): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4718): Binding Chromium to main looper Looper (main, tid 1) {8548bec}
I/LibraryLoader( 4718): Expected native library version number "",actual native library version number ""
I/chromium( 4718): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4718): Initializing chromium process, singleProcess=true
W/art     ( 4718): Attempt to remove local handle scope entry from IRT, ignoring
D/MediaProvider( 4150): [update][84]#0#
D/MediaScannerServiceEx( 4150): [disAliveExtStorageRows]--1, 0
E/SysUtils( 4718): ApplicationContext is null in ApplicationStatus
W/chromium( 4718): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4718): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4718): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4718): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4718): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4718): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4718): Local Branch: 
I/Adreno-EGL( 4718): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4718): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4718):                  d74aa161a12b9c6fc6332151
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4767, uid=10072, userID:0
W/global  ( 4767): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 4767): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 4767): [apache-http] Connection GC has been deprecated!
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  917): java.lang.Throwable: stack dump
D/BluetoothManagerService(  917): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30531ca3:true
W/System.err(  917): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  917): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  917): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4718): 448293142: getState(). Returning 12
W/art     ( 4718): Attempt to remove local handle scope entry from IRT, ignoring
W/global  ( 4767): [apache-http] Connection GC has been deprecated!
W/AwContents( 4718): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4718): CordovaWebView is running on device made by: HTC
D/Finsky  ( 4767): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/art     ( 4718): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4718): Attempt to remove local handle scope entry from IRT, ignoring
E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  917):  packet count Tx=54 Rx=79
I/ActivityManager(  917): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4830 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/chromium( 4718): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/Settings( 4767): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4767): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 4830): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4830): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4767, uid=10072, userID:0
D/FindExtension( 4718): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/MultiDex( 4830): VM with version 2.1.0 has multidex support
I/MultiDex( 4830): install
I/MultiDex( 4830): VM has multidex support, MultiDex support library is disabled.
D/Volley  ( 4767): [435] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4767): [429] DiskBasedCache.clear: Cache cleared.
V/JNIHelp ( 4830): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 4767): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4767): [1] 2.run: Finished loading 1 libraries.
V/GLSUser ( 1971): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
D/Finsky  ( 4767): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PMS     (  917): acquireWL(3b4ec2a6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1971 10024 null
W/ActivityThread( 4830): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4830): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@361a2d67: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4830): Installed default security provider GmsCore_OpenSSL
V/GmsCoreStatsServiceLauncher( 2208): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/PersistentNotificationBroadcastReceiver( 1971): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
D/PMS     (  917): releaseWL(3b4ec2a6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/Finsky  ( 4767): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/Process (  917): killProcessQuiet, pid=3346
I/ActivityManager(  917): Killing 3346:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/InputMethodManager( 4718): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@302625a1, mServedView=org.apache.cordova.engine.SystemWebView{1b3b43c6 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@18065f87
I/InputMethodManagerService(  917): Disable input method client, pid=1599
D/StatusBarManagerService(  917): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  917): Enable input method client, pid=4718
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
W/XT9_C   ( 1397): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1397): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1397): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1397): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 4718): Cannot call determinedVisibility() - never saw a connection for the pid: 4718
I/ActivityManager(  917): Recipient 3346
I/chromium( 4718): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC <<
D/PMS     (  917): releaseWL(13941f35): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  917): Displayed com.example.hello/.MainActivity: +1s518ms
D/JsMessageQueue( 4718): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4718): Unable to open asset URL: file:///android_asset/www/jxcore.js
W/art     ( 4830): Suspending all threads took: 9.550ms
W/InstanceID/Rpc( 2208): Found 10024
D/jxcore_app_log( 4718): JniHelper::setJavaVM(0xab1298f8), pthread_self() = -1404695792
D/JX-Cordova( 4718): jxcore cordova android initializing
D/PMS     (  917): releaseHCC(1875b479): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  917): releaseHCC(15b0e5be): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
D/FileApkUtils( 2208): Spent 21ms computing apk sha1.
D/FileApkUtils( 2208): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2208): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
W/jxcore-log( 4718): Initializing JXcore engine
W/jxcore-log( 4718): JXcore engine is ready
W/jxcore-log( 4718): Starting JXcore engine
D/DexOptUtils( 2208): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 2208): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
D/GmsModuleFndr( 2208): Beginning GMS chimera module scan
D/PMS     (  917): acquireWL(8be7ec4): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2208 10024 WorkSource{10024 com.google.android.gms}
W/asset   ( 2208): Copying FileAsset 0x556527b0a0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
D/GmsModuleFndr( 2208): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 2208): Beginning module configuration check
D/ChimeraCfgMgr( 2208): Module APKs unchanged, check complete
D/PMS     (  917): acquireWL(3ced052e): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2208 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  917): acquireWL(11dc9965): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2208 10024 null
V/Finsky  ( 4767): [1] GearheadStateMonitor.onReady: sIsProjecting:false
I/ActivityManager(  917): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
D/PMS     (  917): acquireWL(3787c2eb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 2208 10024 null
D/PMS     (  917): acquireWL(2ef3c848): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2208 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  917): releaseWL(8be7ec4): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/GCM     ( 2208): COMPAT: Multi user not supported
D/SystemUpdateService( 2208): onCreate
D/GCM     ( 1971): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/CheckinService( 2208): Checking schedule, now: 1448385995958 next: 1448922815158
I/CheckinService( 2208): active receiver: disabled
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2208, uid=10024, userID:0
D/SystemUpdateService( 2208): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/GCoreUlr( 2208): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/SystemUpdateService( 2208): cancelUpdate (empty URL)
I/SystemUpdateService( 2208): active receiver: disabled
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2208, uid=10024, userID:0
D/PMS     (  917): acquireWL(2c0623bf): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2208 10024 WorkSource{10024 com.google.android.gms}
I/ConfigService( 1971): onCreate
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2208, uid=10024, userID:0
I/ConfigFetchService( 2208): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
V/AuthZen ( 2208): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 2208): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2208, uid=10024, userID:0
W/jxcore-log( 4718): Platform android
W/jxcore-log( 4718): 
W/jxcore-log( 4718): Process ARCH arm
W/jxcore-log( 4718): 
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2208, uid=10024, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2208, uid=10024, userID:0
I/art     ( 1787): Explicit concurrent mark sweep GC freed 21982(1354KB) AllocSpace objects, 8(160KB) LOS objects, 48% free, 4MB/8MB, paused 2.991ms total 58.223ms
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2208, uid=10024, userID:0
D/PMS     (  917): releaseWL(11dc9965): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  917): releaseWL(2c0623bf): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  917): acquireWL(3ddeb1ea): PARTIAL_WAKE_LOCK  Icing 0x1 2208 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  917): acquireWL(37033cdb): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1787 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  917): releaseWL(3ced052e): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
I/jxcore-log( 4718): JXcore Cordova bridge is ready!
I/jxcore-log( 4718): 
W/jxcore-log( 4718): JXcore engine is started
I/ConfigFetchService( 2208): service connected
I/GCoreUlr( 1787): DispatchingService.onCreate()
W/BaseAppContext( 2208): Using Auth Proxy for data requests.
D/PMS     (  917): releaseWL(2ef3c848): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 2208): onDestroy
,I/GLSUser ( 2208): [ChannelManager] Attempting to channel bind connection HttpClient.
D/PMS     (  917): acquireWL(10cf9442): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1787 10024 WorkSource{10024 com.google.android.gms}
,D/ConfigFetchService( 2208): ConfigApi connection successful.
,D/PMS     (  917): releaseWL(3ddeb1ea): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  917): Resuming delayed broadcast
,E/jxcore-log( 4718): >> HTC-HTC One M8s
E/jxcore-log( 4718): 
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1971, uid=10024, userID:0
I/jxcore-log( 4718): Total memory 1931808768
I/jxcore-log( 4718): 
I/jxcore-log( 4718): Free memory 83865600
I/jxcore-log( 4718): 
I/jxcore-log( 4718): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4718): 
,I/jxcore-log( 4718): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4718): 
,I/jxcore-log( 4718): userPath [ 'www' ]
I/jxcore-log( 4718): 
,I/jxcore-log( 4718): Size 1080 1776
I/jxcore-log( 4718): 
,I/jxcore-log( 4718): Screen Brightness 142
I/jxcore-log( 4718): 
,E/jxcore-log( 4718): Dummy Error Log.
E/jxcore-log( 4718): 
,I/art     ( 1971): Explicit concurrent mark sweep GC freed 6234(348KB) AllocSpace objects, 4(80KB) LOS objects, 49% free, 4MB/8MB, paused 953us total 51.138ms
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  917): java.lang.Throwable: stack dump
W/System.err(  917): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  917): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  917): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  917): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3158e9c1:true
D/ChimeraCfgMgr( 2208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2208): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GCoreUlr( 1787): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  917):  packet count Tx=54 Rx=79
E/WifiTrafficPoller(  917): notifying of data activity 0
I/GLSUser ( 2208): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/WIFI_ICON( 1219): WifiActivity: 0
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AuthZen ( 2208): Fetching signing key...,
,I/ActivityManager(  917): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4919 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/AuthZen ( 2208): Signing key fetched successfully!
,I/GLSActivity( 1971): [ac] getting account id
,W/BaseAppContext( 2208): Using Auth Proxy for data requests.
I/GLSUser ( 1971): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/GLSUser ( 1971): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1971): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1971): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1971): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AuthZen ( 2208): Starting Enrollment...
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1787, uid=10024, userID:0
,D/PMS     (  917): releaseWL(37033cdb): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms},
,W/ResourcesManager( 4919): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/Kids    ( 2208): [AccountUtils] Account not ready,
W/Kids    ( 2208): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2208): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2208): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2208): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2208): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2208): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2208): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2208): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2208): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40,
,I/GCoreUlr( 1787): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/PMS     (  917): acquireWL(229e6520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1787 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  917): releaseWL(229e6520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1787): Unbound from all location providers
,D/PMS     (  917): releaseWL(10cf9442): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4
,I/GCoreUlr( 1787): DispatchingService.onDestroy()
,D/PMS     (  917): acquireWL(1700fed9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1787 10024 WorkSource{10024 com.google.android.gms},
,I/GCoreUlr( 1787): Unbound from all location providers
D/PMS     (  917): releaseWL(1700fed9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/art     (  917): Explicit concurrent mark sweep GC freed 17009(890KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 16MB/24MB, paused 2.699ms total 177.051ms
,I/art     (  917): WaitForGcToComplete blocked for 152.335ms for cause HeapTrim
,D/AuthZen ( 2208): getting auth token. Attempt 0
,D/PMS     (  917): acquireWL(2a3fb838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 917 1000 null
,I/GLSUser ( 1971): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1971): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1971): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1971): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Babel_SMS( 4919): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4919): MmsConfig.loadMmsSettings,
I/ActivityManager(  917): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=4947 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,V/AlarmManager(  917): sending alarm PendingIntent{1a92b011: PendingIntentRecord{405576 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60454, Int=0
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MmsCustomizationProvider( 4228): query uri: content://htc-mms-customization/mms-ua/ua_string
D/PMS     (  917): acquireWL(39d45302): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 917 1000 WorkSource{10024}
,D/PMS     (  917): releaseWL(2a3fb838): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/IntentController( 1219): receive(android.intent.action.SYNC_STATE_CHANGED,1,false),
,D/PMS     (  917): acquireWL(16dcee6f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 917 1000 null
D/PMS     (  917): releaseWL(16dcee6f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/MmsCustomizationProvider( 4228): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4919, uid=10112, userID:0
,E/AuthZen ( 2208): Error getting auth token
E/AuthZen ( 2208): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 2208): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 2208): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 2208): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 2208): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 2208): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 2208): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Babel_SMS( 4919): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 4919): MmsConfig.loadFromDatabase
E/Babel_SMS( 4919): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4919): MmsConfig.loadFromResources
E/Babel_SMS( 4919): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4919): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,D/PhoneStatusBar( 1219): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true,
D/a       ( 2208): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 2208): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2208): Clearing transaction cache
,W/Settings( 4919): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4919): startup - clean
,I/jxcore-log( 4718): getBuffer is called!!!!
I/jxcore-log( 4718): 
,I/ActivityManager(  917): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4977 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/Babel   ( 4919): deleted: false for 0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4919, uid=10112, userID:0,
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4919, uid=10112, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4919, uid=10112, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4919, uid=10112, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4919, uid=10112, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4919, uid=10112, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4919, uid=10112, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4919, uid=10112, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4919, uid=10112, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4919, uid=10112, userID:0
,W/VideoCapabilities( 4919): Unrecognized profile 2130706433 for video/avc
,D/MdScBoot( 4947): [8f9.1.] 30@-172606 -> 40,
,D/PMS     (  917): acquireWL(10b80b2): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 917 1000 null
,D/PMS     (  917): releaseWL(39d45302): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
,D/PMS     (  917): releaseWL(10b80b2): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1219): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/MdScBootUi( 4947): [8f9.1.2.] boot 118
,W/VideoCapabilities( 4919): Unsupported mime video/x-ms-wmv
,W/Utils   ( 4919): could not parse size range '64x64-1920X1080'
,D/MdScSimSt( 4947): [8f9.1.2.] qry 118: 0+1 running 0
,W/AudioCapabilities( 4919): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 4919): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4919): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4919): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 4919): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4919): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4919): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4919): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4919): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4919): onServiceConnected,
W/Babel   ( 4919): Attempted to change video mute state without an active call.
,I/ActivityManager(  917): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=5002 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  917): killProcessQuiet, pid=4321
I/ActivityManager(  917): Killing 4321:com.htc.showme/u0a81 (adj 15): empty #17
,D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  410): Explicit concurrent mark sweep GC freed 8672(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 315us total 23.347ms
,E/WifiStateMachine(  917): handleMessage: E msg.what=131155
E/WifiStateMachine(  917): processMsg: ConnectedState
,E/WifiStateMachine(  917):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:2939] from screen [on:0 period:982018250] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  917): processMsg: L2ConnectedState
,E/WifiStateMachine(  917):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:982018251] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  917):  get link layer stats 0
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1350): wlan0: Control interface command 'SIGNAL_POLL'
,I/art     (  410): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 122us total 19.031ms
,I/wpa_supplicant( 1350): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  917): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  917): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  917): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-55 "NG700"WPA_PSK
,E/WifiStateMachine(  917): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.39 txretriesrate=0.00 rxrate=2.75 userTriggerdPenalty0
E/WifiStateMachine(  917):  good link -> stuck count =0
E/WifiStateMachine(  917):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  917):  isHighRSSI       ---> score=61
,I/art     (  410): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 131us total 16.206ms
,I/ActivityManager(  917): Recipient 4321
,E/WifiStateMachine(  917): handleMessage: X
,I/ActivityManager(  917): Waited long enough for: ServiceRecord{10e61af4 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,I/ActivityManager(  917): Killing 4344:com.htc.feedback/u0a83 (adj 15): empty #17
D/Process (  917): killProcessQuiet, pid=4344
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 ,
,I/ActivityManager(  917): Recipient 4344,
,E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  917):  packet count Tx=54 Rx=79
,D/WifiWatchdogStateMachine(  917): RSSI current: 3 new: -56, 3,
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  917): Killing 4366:com.htc.updater/u0a84 (adj 15): empty #17
,D/Process (  917): killProcessQuiet, pid=4366
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 5002): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5002): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2208, uid=10024, userID:0,
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2208, uid=10024, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2208, uid=10024, userID:0,
I/CheckinService( 2208): Done disabling old GoogleServicesFramework version
,I/HtcModeClient( 3553): handler message = 4011,
,E/HtcModeClient( 3553): Check connection and retry 3 times.
,I/ActivityManager(  917): Recipient 4366,
,V/JNIHelp ( 5002): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 5002): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 5002): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 5002): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5002): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,E/cutils-trace( 5034): Error opening trace file: Permission denied (13),
I/dex2oat ( 5034): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-550848808.jar --oat-fd=29 --oat-location=/data/data/com.google.android.youtube/cache/ads-550848808.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5034): dex2oat: override thread count:4
,E/YouTube MDX( 5002): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 5002): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
D/libc    ( 5002): [NET] android_getaddrinfofornet-, SUCCESS,
I/dex2oat ( 5034): dex2oat took 57.229ms (threads: 4)
,D/VoldConnector(  917): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 5002): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  917): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
W/ContextImpl( 5002): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,D/VoldConnector(  917): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 5002): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  917): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 5002): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files,
,E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  917):  packet count Tx=54 Rx=79
,W/InstanceID/Rpc( 5002): Found 10024
,D/VoldConnector(  917): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 5002): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/libc    ( 5002): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5002): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  917): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=5082 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/libc    ( 5002): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5002): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5002): [NET] android_getaddrinfo_proxy+
D/libc    ( 5002): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024,
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/Process (  917): killProcessQuiet, pid=4399
I/ActivityManager(  917): Killing 4399:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5002): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 5002): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 5002): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5002): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5002): [NET] android_getaddrinfofornet-, err=8
,I/ActivityManager(  917): Recipient 4399,
,V/AlarmManager(  917): sending alarm PendingIntent{1515d1c2: PendingIntentRecord{1e3f9bd3 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=60703, Int=259200000,
V/AlarmManager(  917): sending alarm PendingIntent{135ee09: PendingIntentRecord{1673480e com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1448385998642, Int=0
,I/iu.UploadsManager( 2208): End new media; added: 0, uploading: 0, time: 42 ms
,W/ActivityManager(  917): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5082): getAccountsCursor,
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5082): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5082, uid=10106, userID:0
,W/ActivityManager(  917): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5082): Observing account changes for notifications,
,W/ActivityManager(  917): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5082, uid=10106, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5082, uid=10106, userID:0
,W/ActivityManager(  917): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,E/Gmail   ( 5082): Error finding the version of the Email provider.....
E/Gmail   ( 5082): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5082): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5082): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5082): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5082): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5082): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5082): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5082): We do not support migrating this version of the Email provider.
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=5082, uid=10106, userID:0
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=5082, uid=10106, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=5082, uid=10106, userID:0
,I/Gmail   ( 5082): getAccountsCursor
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=5082, uid=10106, userID:0
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/ActivityManager(  917): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=5126 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,W/ActivityManager(  917): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5082, uid=10106, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5082, uid=10106, userID:0
,W/ActivityManager(  917): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 5082): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2b98d54d that was originally bound here
E/ActivityThread( 5082): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2b98d54d that was originally bound here
E/ActivityThread( 5082): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 5082): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 5082): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 5082): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 5082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5082): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 5082): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 5082): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 5082): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 5082): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 5082): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 5082): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 5082): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 5082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5082): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 5082): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  917): Unbind failed: could not find connection for android.os.BinderProxy@311810b1
V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 5082): (283) recovered 460 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,I/Gmail   ( 5082): notifyAccountChanged
,I/Gmail   ( 5082): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5082): getAccountsCursor
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5082): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PMS     (  917): acquireWL(1f8f24e9): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5082 10106 null
,E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL true Token 11 num clients 6
I/Gmail   ( 5082): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
E/WifiTrafficPoller(  917):  packet count Tx=64 Rx=87
,E/WifiTrafficPoller(  917): notifying of data activity 3
D/WIFI_ICON( 1219): WifiActivity: 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  917): acquireWL(1f8f24e9): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5082 10106 null
,I/Gmail   ( 5082): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) },
I/Gmail   ( 5082): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5082): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PMS     (  917): acquireWL(1f8f24e9): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5082 10106 null
,I/Gmail   ( 5082): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=5082, uid=10106, userID:0,
,D/Process (  917): killProcessQuiet, pid=4442
I/ActivityManager(  917): Killing 4442:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  917): Recipient 4442
,D/LocationManagerService(  917): getProviders()=[passive]
,I/Gmail   ( 5082): master sync=false, engine sync=true
,I/ActivityManager(  917): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5157 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=5126, uid=10085, userID:0,
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=5126, uid=10085, userID:0
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=5126, uid=10085, userID:0
,W/BroadcastQueue(  917): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000),
,E/WifiTrafficPoller(  917): ADD_CLIENT: 7
D/WifiService(  917): New client listening to asynchronous messages
,I/art     (  917): Explicit concurrent mark sweep GC freed 17231(926KB) AllocSpace objects, 5(164KB) LOS objects, 33% free, 16MB/24MB, paused 1.818ms total 176.950ms,
,I/ActivityManager(  917): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=5193 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  917): killProcessQuiet, pid=4531
I/ActivityManager(  917): Killing 4531:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/WifiDataStallTracker(  917): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  917): updateDataStallInfo: mDataStallTxRxSum={txSum=49 rxSum=35} preTxRxSum={txSum=40 rxSum=29}
D/WifiDataStallTracker(  917): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  917): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/ActivityManager(  917): Recipient 4531,
,I/Gmail   ( 5082): getAccountsCursor
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5082): master sync=false, engine sync=true,
,E/AndroidHttpClient( 4767): Leak found
E/AndroidHttpClient( 4767): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4767): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4767): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4767): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4767): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4767): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4767): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4767): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4767): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4767): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4767): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4767): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4767): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4767): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/GCM     ( 1971): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1971): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 2208): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/libc    ( 5193): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 5193): [NET] android_getaddrinfofornet-, err=8
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2208, uid=10024, userID:0
D/libc    ( 5193): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 5193): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5193): [NET] android_getaddrinfo_proxy+
D/libc    ( 5193): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
,D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ActivityManager(  917): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5223 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,D/LocationInitializer( 2208): Restart initialization of location
,I/ActivityManager(  917): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5245 uid=10035 gids={50035, 9997} abi=arm64-v8a
,E/WifiStateMachine(  917): handleMessage: E msg.what=131155
E/WifiStateMachine(  917): processMsg: ConnectedState
,E/WifiStateMachine(  917):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:2933] from screen [on:0 period:982021270] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  917): processMsg: L2ConnectedState
E/WifiStateMachine(  917):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:982021272] gl hn u24 rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  917):  get link layer stats 0
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1350): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1350): environment dirty rate=0 [11][0][0]
E/WifiStateMachine(  917): fetchRssiLinkSpeedAndFrequencyNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  917): fetchRssiLinkSpeedAndFrequencyNative rssi=-56 linkspeed=72
E/WifiConfigStore(  917): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-55 "NG700"WPA_PSK
E/WifiStateMachine(  917): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.70 txretriesrate=0.00 rxrate=5.37 userTriggerdPenalty0
E/WifiStateMachine(  917):  good link -> stuck count =0
E/WifiStateMachine(  917):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  917):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  917): RSSI current: 3 new: -56, 3
,E/WifiStateMachine(  917): handleMessage: X
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
,I/WebViewFactory( 5126): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ResourcesManager( 5223): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5223): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SocialFeedProvider( 1599): +disConnect socialManager
I/SocialFeedProvider( 1599): disconnect socialManager
,I/SocialFeedProvider( 1599): -disConnect socialManager
,I/LibraryLoader( 5126): Time to load native libraries: 4 ms (timestamps 3962-3966)
I/LibraryLoader( 5126): Expected native library version number "",actual native library version number ""
,I/MultiDex( 5223): VM with version 2.1.0 has multidex support
I/MultiDex( 5223): install
I/MultiDex( 5223): VM has multidex support, MultiDex support library is disabled.
,W/art     ( 5126): Attempt to remove local handle scope entry from IRT, ignoring
,V/JNIHelp ( 5223): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Process (  917): killProcessQuiet, pid=4560,
,I/ActivityManager(  917): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5277 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  917): Killing 4560:com.htc.htccupd/u0a13 (adj 15): empty #17
,W/ActivityThread( 5223): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5223): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@361a2d67: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5223): Installed default security provider GmsCore_OpenSSL
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5193): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 5193): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 5193): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL true Token 11 num clients 7
I/ActivityManager(  917): Recipient 4560
E/WifiTrafficPoller(  917):  packet count Tx=66 Rx=88
,I/ActivityManager(  917): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5298 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
V/AlarmManager(  917): sending alarm PendingIntent{1d8f2dda: PendingIntentRecord{68b220b com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448386000096, Int=0
,D/libc    ( 5193): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4,
D/libc    ( 5193): [NET] android_getaddrinfofornet-, err=8
,D/SMSBackup( 5277): Got a database change event
,I/GLSUser ( 1971): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow,
I/GLSUser ( 1971): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1971): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1971): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Process (  917): killProcessQuiet, pid=4607
,I/ActivityManager(  917): Killing 4607:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/WearableService( 5223): callingUid 10024, callindPid: 5223
,W/art     ( 5126): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  917): Recipient 4607
,V/GLSActivity( 1971): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/MDM     ( 1787): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DotMatrix( 1308): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
,W/Search.LoginHelper( 5126): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5126): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 5126): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5126): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5126): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5126): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5126): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
,W/Search.LoginHelper( 5126): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5126): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5126): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5126): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5126): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5126): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5126): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5126): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5126): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5126): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 5126): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 5126): Failed to get auth token
,D/libc    ( 5126): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    ( 5126): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5126): [NET] android_getaddrinfo_proxy+
D/libc    ( 5126): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 13(0x7777772e676f6f),sn(),hints(known),family 2,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    ( 5193): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 5193): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5193): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 5193): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5193): [NET] android_getaddrinfo_proxy+
D/libc    ( 5193): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/ImageRamCache( 5298): create image Cache, size: 31457280.
,I/ImageRamCache( 5298): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5298): create image Cache, size: 31457280.
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5126): [NET] android_getaddrinfo_proxy-, success
,I/FeedSettings( 5298): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5298): GroupBudget 0.500000 0.380000
I/FeedSettings( 5298): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5298): changeLocale(): en_GB,
,I/Prism.AllAppsOptionsMa_( 5298): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5298): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 5298): action: com.htc.sense.hsp.HANDLE_ULOG,
I/SocialManager[SocialBiLogHelper]( 5298): last commit ulog time 1448344804793,
I/SocialManager[SocialBiLogHelper]( 5298): skip commit this time
,D/CustomHighlightReceiver( 5298): [custom highlight] onReceive
,D/CustomHighlightService( 5298): [custom highlight] onHandleIntent
,D/NewsDB  ( 5298): set custom highlight []
,D/MessagingShortcutReceiver( 4228): keep hiding shortcut bubble,
,D/MessagingShortcut( 4228): updateMsgShortcut, msg count> -1,
D/MessagingShortcut( 4228): After query: 0
D/MessagingShortcut( 4228): mPresentUnreadCount: -1
,D/MessageUtils( 4228): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
D/MessagingShortcut( 4228): setMsgShortcutDrawable> 0, false
D/MessagingShortcut( 4228): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1308): [EventService] reorderNotification, total:0,
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5193): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 5193): [NET] android_getaddrinfofornet+,hn 13(0x32332e35392e31),sn(),hints(known),family 0,flags 4,
D/libc    ( 5193): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  917): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5339 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,D/CustomHighlightService( 5298): [custom highlight] set tags 
,D/Process (  917): killProcessQuiet, pid=4657
I/ActivityManager(  917): Killing 4657:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  917): Recipient 4657,
,W/ResourcesManager( 5339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/Process (  917): killProcessQuiet, pid=4479
I/ActivityManager(  917): Killing 4479:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  917): Recipient 4479,
,D/TodoTaskshortcut( 5339): update TASK shortcut>,
,D/PMS     (  917): acquireWL(14e862a9): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5339 10069 null
,D/PMS     (  917): acquireWL(2cb7b02e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5339 10069 null
D/PMS     (  917): releaseWL(14e862a9): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 5339): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5339): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5339): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 5339): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5339): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PMS     (  917): releaseWL(2cb7b02e): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/Process (  917): killProcessQuiet, pid=4698
,I/ActivityManager(  917): Killing 4698:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/NotifyReceiver( 5339): stopSelfResult true
,E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  917):  packet count Tx=114 Rx=146
,D/PMS     (  917): releaseWL(1f8f24e9): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,I/art     ( 1971): Explicit concurrent mark sweep GC freed 14610(817KB) AllocSpace objects, 6(504KB) LOS objects, 49% free, 4MB/8MB, paused 1.023ms total 44.700ms
D/PMS     (  917): acquireWL(44b055c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  917): Recipient 4698
,D/BluetoothManagerService(  917): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  917): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2abf9439 mBinding = false
W/Settings:Agent(  917): MONITOR_LOG
W/Settings:Agent(  917): name: bluetooth_on
W/Settings:Agent(  917): value: 0
W/Settings:Agent(  917): >> traceCallingStack()
W/Settings:Agent(  917): Process.myPid(): 917
W/Settings:Agent(  917): Process.myTid(): 1763
W/Settings:Agent(  917): Process.myUid(): 1000,
W/Settings:Agent(  917): 
W/Settings:Agent(  917): 
W/System.err(  917): java.lang.Throwable: stack dump
D/PMS     (  917): releaseWL(44b055c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/System.err(  917): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  917): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  917): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  917): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  917): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  917): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  917): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  917): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
,W/System.err(  917): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  917): 
W/Settings:Agent(  917): << traceCallingStack(): 18(ms)
,D/GCM     ( 1971): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1971): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2208): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/BluetoothManagerService(  917): Message: MESSAGE_DISABLE,
,D/BluetoothManagerService(  917): Sending off request.
D/BluetoothAdapterState( 3467): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3467): Setting state to 13
I/BluetoothAdapterState( 3467): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  917): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3467): onBluetoothDisable()
I/bt-btm  ( 3467): BTM_SetDiscoverability
I/bt-btm  ( 3467): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3467): disc_mode 0000
I/bt-btm  ( 3467): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3467): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/BluetoothAdapterState( 3467): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
,I/bt-btif ( 3467): HAL bt_hal_cbacks->adapter_properties_cb
D/PMS     (  917): acquireWL(30bb8065): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3467 1002 null
I/bt-btm  ( 3467): BTM_SetConnectability
I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2208, uid=10024, userID:0
I/bt-btm  ( 3467): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3467): disc_mode 0000
I/bt-btm  ( 3467): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3467): Scan Mode:21
D/BluetoothManagerService(  917): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothAdapterState( 3467): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService(  917): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  917): Bluetooth State Change Intent: 12 -> 13
I/bt-btif ( 3467): BTA_JvDeleteRecord
I/bt-btif ( 3467): BTA_JvRfcommStopServer
D/bt-btm  ( 3467): BTM_FreeSCN 
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:14
I/bt-btm  ( 3467): BTM_SEC_CLR[13]: id 55
I/bt-btif ( 3467): BTA_JvDeleteRecord
I/bt-btif ( 3467): BTA_JvRfcommStopServer
D/bt-btm  ( 3467): BTM_FreeSCN 
I/bt-btif ( 3467): BTA_JvDeleteRecord
I/bt-btif ( 3467): BTA_JvRfcommStopServer
D/bt-btm  ( 3467): BTM_FreeSCN 
I/bt-btif ( 3467): BTA_JvDeleteRecord
I/bt-btif ( 3467): BTA_JvRfcommStopServer
D/bt-btm  ( 3467): BTM_FreeSCN 
I/bt-btif ( 3467): BTA_JvDeleteRecord
I/bt-btif ( 3467): BTA_JvRfcommStopServer
D/bt-btm  ( 3467): BTM_FreeSCN 
E/BtOppRfcommListener( 3467): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btif ( 3467): BTA_JvDeleteRecord
I/bt-btif ( 3467): BTA_JvRfcommStopServer
D/bt-btm  ( 3467): BTM_FreeSCN 
E/bt-btif ( 3467): cmd socket is not created
V/BluetoothSapService( 3467): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/IntentController( 1219): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3467): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3467): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3467): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3467): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3467): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3467): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3467): Write Extended Inquiry Response to controller
I/bt-btm  ( 3467): Write Extended Inquiry Response to controller
I/bt-btm  ( 3467): Write Extended Inquiry Response to controller
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x000f
D/NGFService( 4068): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/bt-btm  ( 3467): BTM_SetDiscoverability
I/bt-btm  ( 3467): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3467): disc_mode 0000
I/bt-btm  ( 3467): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3467): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3467): BTM_SetConnectability
I/bt-btm  ( 3467): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3467): disc_mode 0000
D/bt-btm  ( 3467): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3467): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3467): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3467): BTM_IsInquiryActive
I/bt-btm  ( 3467): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3467): btm_ble_clear_white_list
W/bt-btif ( 3467): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-btif ( 3467): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3467): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3467): BTM_FreeSCN 
I/bt-btm  ( 3467): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3467): BTM_FreeSCN 
,I/bt-btm  ( 3467): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3467): AVRC_Close handle:0
D/bt-btif ( 3467): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3467): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0017
D/bt-btif ( 3467): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3467): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3467): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3467): GATT_Deregister gatt_if=3
I/bt-att  ( 3467): GATT_Listen gatt_if=3
I/bt-btm  ( 3467): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3467): BTM_ReadConnectability
I/bt-btm  ( 3467): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3467): disc_mode 0000
I/bt-att  ( 3467): GATT_Deregister gatt_if=4
I/bt-att  ( 3467): GATT_Listen gatt_if=4
D/WifiService(  917): setWifiEnabled: false pid=4718, uid=10373
I/bt-btm  ( 3467): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3467): BTM_ReadConnectability
I/bt-btm  ( 3467): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3467): disc_mode 0000
E/bt-btif ( 3467): bta_gattc_deregister Deregister Failedm unknown client cif
D/WifiManager( 4718): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
,E/WifiStateMachine(  917): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiService(  917): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  917): MONITOR_LOG
I/WifiService(  917): isSprintWifiRestricted(): false
W/Settings:Agent(  917): name: wifi_on
I/WifiService(  917): isMdmWifiRestricted(): false
W/Settings:Agent(  917): value: 0
D/WifiService(  917): New client listening to asynchronous messages
W/Settings:Agent(  917): >> traceCallingStack()
W/Settings:Agent(  917): Process.myPid(): 917
W/Settings:Agent(  917): Process.myTid(): 1383
W/Settings:Agent(  917): Process.myUid(): 1000
W/Settings:Agent(  917): 
W/Settings:Agent(  917): 
E/WifiTrafficPoller(  917): ADD_CLIENT: 8
,E/MDM     ( 1787): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/System.err(  917): java.lang.Throwable: stack dump
,W/System.err(  917): 	at java.lang.Thread.dumpStack(Thread.java:490)
,I/ActivityManager(  917): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=5371 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/System.err(  917): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  917): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  917): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  917): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  917): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  917): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  917): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
,W/System.err(  917): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  917): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  917): 
W/Settings:Agent(  917): << traceCallingStack(): 25(ms)
,D/LocationInitializer( 2208): Restart initialization of location
,I/bt-btm  ( 3467): btm_ble_clear_white_list_complete
V/BluetoothPbapReceiver( 3467): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3467): ***********state = 13
,I/BtOppRfcommListener( 3467): stopping Accept Thread
,I/BtOppRfcommListener( 3467): BluetoothSocket listen thread finished,
,I/QuickSettingBluetooth( 1219): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PMS     (  917): acquireWL(3f311b48): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4629 1000 null
V/BluetoothPbapService( 3467): Pbap Service closeService in
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/BluetoothPbapService( 3467): successfully stopped pbap service
V/BluetoothPbapService( 3467): Pbap Service closeService out
D/WifiController(  917): handleMessage: E msg.what=155656
D/WifiController(  917): processMsg: DeviceActiveState
D/WifiController(  917): processMsg: StaEnabledState
I/jxcore-log( 4718): ****TEST TOOK:  5257  ms ****
I/jxcore-log( 4718): 
D/WifiController(  917): transitionTo: destState=ApStaDisabledState
,D/WifiController(  917): handleMessage: new destination call exit/enter
D/WifiController(  917): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  917): invokeExitMethods: DeviceActiveState
D/WifiController(  917): invokeExitMethods: StaEnabledState
D/WifiController(  917): moveTempStackToStateStack: i=0,j=1
D/WifiController(  917): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  917): invokeEnterMethods: ApStaDisabledState
V/BluetoothPbapService( 3467): Pbap Service onDestroy
V/BluetoothPbapService( 3467): Pbap Service closeService in
V/BluetoothPbapService( 3467): Pbap Service closeService out
I/jxcore-log( 4718): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4718): 
,D/WifiController(  917): handleMessage: X
E/WifiStateMachine(  917): handleMessage: E msg.what=131084
E/WifiStateMachine(  917): processMsg: ConnectedState
E/WifiStateMachine(  917):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  917): processMsg: L2ConnectedState
E/WifiStateMachine(  917):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  917): processMsg: ConnectModeState
D/WifiDisplayAdapter(  917): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  917):     Client/Owner: Client
D/WifiDisplayAdapter(  917):     GroupId: 
D/WifiDisplayAdapter(  917):     Passphrase: 
D/WifiDisplayAdapter(  917):     SessionId: 0
D/WifiDisplayAdapter(  917):     IP Address: }
E/WifiStateMachine(  917):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  917): processMsg: DriverStartedState
E/WifiStateMachine(  917):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  917): processMsg: SupplicantStartedState
E/WifiStateMachine(  917):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  917): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  917): handleMessage: new destination call exit/enter
E/WifiStateMachine(  917): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  917): invokeExitMethods: ConnectedState
E/WifiStateMachine(  917): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  917): release()
E/WifiStateMachine(  917): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  917): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  917): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  917): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  917): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  917): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  917): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  917): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1350): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1350): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1350): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1350): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1350): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1350): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1350): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/PMS     (  917): releaseWL(3f311b48): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  917): acquireWL(1cf99706): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4629 1000 null
,W/System.err(  917): java.lang.Throwable: stack dump
,W/System.err(  917): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  917): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  917): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  917): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38e0a3f4:true
E/WifiStateMachine(  917): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1350): Power_Mode_Type mode = 0
I/wpa_supplicant( 1350): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1350): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  917): setDhcpActive: false
V/NativeCrypto( 1971): Read error: ssl=0x556531f500: I/O error during system call, Connection timed out
D/libc    (  917): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  917): [NET] android_getaddrinfofornet-, SUCCESS
W/System.err( 5193): javax.net.ssl.SSLException: Read error: ssl=0x55651bdb50: I/O error during system call, Connection timed out
I/ActivityManager(  917): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5393 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
W/System.err( 5193): 	at com.android.org.conscrypt.NativeCrypto.SSL_read(Native Method)
D/WifiP2pService(  917): InactiveState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/System.err( 5193): 	at com.android.org.conscrypt.OpenSSLSocketImpl$SSLInputStream.read(OpenSSLSocketImpl.java:674)
D/WifiP2pService(  917): P2pEnabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/System.err( 5193): 	at org.apache.http.impl.io.AbstractSessionInputBuffer.fillBuffer(AbstractSessionInputBuffer.java:103)
D/PMS     (  917): acquireWL(2c52571d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1971 10024 WorkSource{10024 com.google.android.gms}
W/System.err( 5193): 	at org.apache.http.impl.io.AbstractSessionInputBuffer.readLine(AbstractSessionInputBuffer.java:191)
W/System.err( 5193): 	at org.apache.http.impl.conn.DefaultResponseParser.parseHead(DefaultResponseParser.java:82)
W/System.err( 5193): 	at org.apache.http.impl.io.AbstractMessageParser.parse(AbstractMessageParser.java:174)
W/System.err( 5193): 	at org.apache.http.impl.AbstractHttpClientConnection.receiveResponseHeader(AbstractHttpClientConnection.java:180)
W/System.err( 5193): 	at org.apache.http.impl.conn.DefaultClientConnection.receiveResponseHeader(DefaultClientConnection.java:235)
W/System.err( 5193): 	at org.apache.http.impl.conn.AbstractClientConnAdapter.receiveResponseHeader(AbstractClientConnAdapter.java:259)
W/System.err( 5193): 	at org.apache.http.protocol.HttpRequestExecutor.doReceiveResponse(HttpRequestExecutor.java:279)
W/System.err( 5193): 	at org.apache.http.protocol.HttpRequestExecutor.execute(HttpRequestExecutor.java:121)
W/System.err( 5193): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:440)
W/System.err( 5193): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:754)
W/System.err( 5193): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:519)
W/System.err( 5193): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:497)
W/System.err( 5193): 	at com.mcrm.autonotification.NotificationService.loadFromServer(NotificationService.java:113)
W/System.err( 5193): 	at com.mcrm.autonotification.NotificationService.tryServerCall(NotificationService.java:79)
W/System.err( 5193): 	at com.mcrm.autonotification.NotificationService.onCreate(NotificationService.java:271)
W/System.err( 5193): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2894)
W/System.err( 5193): 	at android.app.Acti,vityThread.access$1800(ActivityThread.java:144)
W/System.err( 5193): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
W/System.err( 5193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5193): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 5193): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
W/System.err( 5193): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5193): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5193): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/System.err( 5193): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
V/NativeCrypto( 1971): SSL shutdown failed: ssl=0x556531f500: I/O error during system call, Broken pipe
D/libc    (  917): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  917): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  917): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  917): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  917): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  917): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  917): [NET] android_getaddrinfofornet-, SUCCESS
D/BluetoothAdapter( 4629): 614624388: getState(). Returning 13
E/WifiStateMachine(  917): NetworkAgent != null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  917): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  917): DefaultState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  917): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  917): Forcing reevaluation
E/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  917): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  917): Validated
E/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  917): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiDataStallTracker(  917): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/WifiStateMachine(  917): autoRoamSetBSSID any key="NG700"WPA_PSK
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  917): stopDataStallAlarm 
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiConfigStore(  917): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  917): QCOM Debug skip set_network part for security concern!
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  917): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1350): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1350): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1350): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
V/NetworkPolicy(  917): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  917):  packet count Tx=114 Rx=148
E/WifiTrafficPoller(  917): notifying of data activity 1
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1350): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1350): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1350): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1350): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  917): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  917): invokeExitMethods: DriverStartedState
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1350): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  917): Unexpected BatchedScanResults :null
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1350): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  917): noteBatchedScanstop()
E/WifiTrafficPoller(  917): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  917): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  917): ENABLE_TRAFFIC_STATS_POLL false Token 13
I/art     (  410): Explicit concurrent mark sweep GC freed 8637(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 32.326ms
E/WifiStateMachine(  917): [1,448,386,001,464 ms] noteScanEnd no scan source
E/WifiStateMachine(  917): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  917): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  917): invokeEnterMethods: WaitForP2pDisableState
D/WifiScanningService(  917): SCAN_AVAILABLE : 1
E/WifiStateMachine(  917): handleMessage: X
E/WifiStateMachine(  917): handleMessage: E msg.what=131212
D/RttService(  917): SCAN_AVAILABLE : 1
E/WifiStateMachine(  917): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  917):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  917): processMsg: SupplicantStartedState
E/WifiStateMachine(  917):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/PMS     (  917): releaseWL(2c52571d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  917): processMsg: DefaultState
D/WifiScanningService(  917): DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  917): InactiveState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  917):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiP2pService(  917): P2pEnabledState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothInputDevice( 4629): BluetoothInputDevice()
D/RttService(  917): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  917): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  917): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  917): handleMessage: X
E/WifiStateMachine(  917): handleMessage: E msg.what=131212
E/WifiStateMachine(  917): processMsg: WaitForP2pDisableState
D/WIFI_ICON( 1219): WifiActivity: 1
D/BluetoothManagerService(  917): registerStateChangeCallback+
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/WifiStateMachine(  917):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  917): processMsg: SupplicantStartedState
D/BluetoothManagerService(  917): Registered receivers: 9
E/WifiStateMachine(  917):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  917): processMsg: DefaultState
E/WifiStateMachine(  917):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  917): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  917): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  917): handleMessage: X
E/WifiStateMachine(  917): handleMessage: E msg.what=131212
E/WifiStateMachine(  917): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  917):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  917): processMsg: SupplicantStartedState
E/WifiStateMachine(  917):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  917): processMsg: DefaultState
E/WifiStateMachine(  917):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  917): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  917): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  917): handleMessage: X
D/WifiNetworkAgent(  917): NetworkAgent: NetworkAgent channel lost
D/WifiMonitor(  917): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@446c608
,D/WifiP2pService(  917): P2pDisablingState
D/WifiP2pService(  917): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  917): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiP2pService(  917): p2p socket connection lost
D/WifiP2pService(  917): P2pDisabledState
E/WifiStateMachine(  917): handleMessage: E msg.what=131205
D/WifiDisplayAdapter(  917): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  917):     Client/Owner: Client
D/WifiDisplayAdapter(  917):     GroupId: 
D/WifiDisplayAdapter(  917):     Passphrase: 
D/WifiDisplayAdapter(  917):     SessionId: 0
D/WifiDisplayAdapter(  917):     IP Address: }
E/WifiStateMachine(  917): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  917):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  917): transitionTo: destState=SupplicantStoppingState
D/WifiP2pService(  917): P2pDisabledState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  917): handleMessage: new destination call exit/enter
D/WifiP2pService(  917): DefaultState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  917): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  917): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  917): invokeExitMethods: SupplicantStartedState
V/AudioService(  917): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  917):     Client/Owner: Client
V/AudioService(  917):     GroupId: 
V/AudioService(  917):     Passphrase: 
V/AudioService(  917):     SessionId: 0
V/AudioService(  917):     IP Address: }
E/WifiStateMachine(  917): moveTempStackToStateStack: i=0,j=1
D/HtcEffectManagerBase(  917): onEventChanged id=5 status=false
E/WifiStateMachine(  917): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  917): invokeEnterMethods: SupplicantStoppingState
D/HtcEffectManager(  917): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  917): convertEffect before=902
E/WifiStateMachine(  917): Call handleNetworkDisconnect() in SupplicantStoppingState
D/HtcEffectManager(  917): convertEffect after=902
I/art     (  410): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 160us total 18.963ms
E/WifiStateMachine(  917): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
E/WifiStateMachine(  917): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1350): Power_Mode_Type mode = 0
I/wpa_supplicant( 1350): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/BluetoothPan( 4629): BluetoothPan()
W/WifiHW  (  917): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  917): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1350): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  917): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1350): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  917): setDhcpActive: false
D/BluetoothManagerService(  917): registerStateChangeCallback+
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  917): Registered receivers: 10
D/BluetoothMap( 4629): Create BluetoothMap proxy object
D/BluetoothManagerService(  917): registerStateChangeCallback+
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  917): Registered receivers: 11
E/BluetoothMap( 4629): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  917): registerStateChangeCallback+
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  917): Registered receivers: 12
D/BluetoothSap( 4629): BluetoothSap() call bindService
D/HtcBtWidget_BTWidgetProvider( 5393): onBTStateChanged() for widget: 
W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/HtcBtWidget_BTWidgetProvider( 5393): updateWidget(context) for widget: 
I/art     (  410): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 137us total 16.282ms
D/BluetoothPbap( 4629): BluetoothPbap()
D/BluetoothManagerService(  917): registerStateChangeCallback+
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  917): Registered receivers: 13
D/LocalBluetoothProfileManager( 4629): LocalBluetoothProfileManager construction complete
I/QuickSettingWifi( 1219): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
D/BluetoothFtpService( 3467): ACTION_STATE_CHANGED: state: 13mHasStarted: true
E/BluetoothFtpService:RfcommSocketAcceptThread( 3467): Shutdown
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0
D/BluetoothMasReceiver( 3467): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 3467): SapReceiver onReceive 
V/BluetoothSapReceiver( 3467): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3467):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3467): startService = false
D/DockEventReceiver( 4629): finishStartingService: stopping service
,D/BluetoothInputDevice( 4629): Proxy object connected
,D/HidProfile( 4629): Bluetooth service connected
D/WISPrService( 4629): >>>>>WISPrService start isConnected = true<<<<<
,D/BluetoothAdapter( 4629): 614624388: getState(). Returning 13
D/BluetoothPan( 4629): BluetoothPAN Proxy object connected
,D/PanProfile( 4629): Bluetooth service connected
D/SapServerProfile( 4629): Bluetooth service connected
,D/PMS     (  917): releaseWL(1cf99706): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/WifiService(  917): New client listening to asynchronous messages
,E/WifiTrafficPoller(  917): ADD_CLIENT: 9
,D/AuthorizationBluetoothService( 1971): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt-btm  ( 3467): BTM_BleGetVendorCapabilities
W/bt-btif ( 3467): ag scb idx 1 not allocated
W/bt-btif ( 3467): ag scb idx 2 not allocated
E/bt-btif ( 3467): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3467): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3467): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3467): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3467): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3467): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3467): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3467): L2CAP - PSM: 0x0017 not found for deregistration
,E/bt-btif ( 3467): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3467): pthread_join() FAILED result:3
,D/PMS     (  917): acquireWL(43b0c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 917 1000 null,
I/BatteryService(  917): n_update end
D/PMS     (  917): releaseWL(43b0c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  917): BroadcastReceiver::onReceive+
D/NotificationService(  917): plugged=true pluggin=true
D/UsbnetService(  917): onReceive BATTERY_CHANGED
D/UsbnetService(  917):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  917): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  917): updateBatteryInfo
,D/HeadsetStateMachine( 3467): Disconnected process message: 10, size: 0
D/PMS     (  917): runPSCheck
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  917): Checking...
D/WifiController(  917): handleMessage: E msg.what=155652
I/HtcPowerSaver(  917): >> updateStatus
D/WifiController(  917): processMsg: ApStaDisabledState
D/WifiController(  917): battery changed pluggedType: 2
D/WifiController(  917): processMsg: DefaultState
D/PowerUI ( 1219): closing low battery warning: level=100
D/WifiController(  917): handleMessage: X
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1308): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  917): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  917): << updateStatus
,D/ConnectivityService(  917): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  917): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  917): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  917): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  917): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  917): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1219): CM callback handler got msg 524292
E/WifiStateMachine(  917): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/SecurityController( 1219): onLost 100
E/WifiStateMachine(  917): stopping supplicant
W/WifiHW  (  917): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1350): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 1350): wlan0: Removing interface wlan0
,E/WifiTrafficPoller(  917): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/wpa_supplicant( 1350): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
,D/wpa_supplicant( 1350): TDLS: Tear down peers
D/ConnectivityService(  917): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/wpa_supplicant( 1350): wpa_driver_nl80211_disconnect(reason_code=3)
D/ConnectivityService(  917): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  917): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  917): Removing idletimer
D/usbnet  (  917):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  917): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  917): setWifiState: disabling
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/WifiStateMachine(  917): handleMessage: X
D/WIFI_ICON( 1219): updateWifiState: WIFI_STATE_CHANGED disabled
E/WifiStateMachine(  917): handleMessage: E msg.what=131131
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  917): processMsg: SupplicantStoppingState
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  917):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  917): processMsg: DefaultState
E/WifiStateMachine(  917):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  917): handleMessage: X
D/WIFI    (  917): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/IntentController( 1219): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI    (  917):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  917): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  917): enter WifiNetworkFactory startNetwork. mIPTStart:false
,D/WISPrService( 4629): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4629): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/PMS     (  917): acquireWL(12586989): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 917 1000 null
,D/CSLegacyTypeTracker(  917): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/WISPrService( 4629): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4629): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  917): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,E/ConnectivityService(  917): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  917): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  917): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  917): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
V/NetworkPolicy(  917): ensureActiveMobilePolicyLocked()
D/PMS     (  917): acquireWL(28c2dd8e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 917 1000 null
D/DATA_ICON( 1219): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WISPrService( 4629): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WISPrService( 4629): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  917): handleMessage: E msg.what=196614
E/WifiStateMachine(  917): processMsg: SupplicantStoppingState
D/NetworkPolicy(  917): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/DATA_ICON( 1219): dataConnected: false/false
E/WifiStateMachine(  917):  SupplicantStoppingState !CMD_ON_QUIT 0 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  917): processMsg: DefaultState
V/NetworkPolicy(  917): updateNetworkEnabledLocked()
V/NetworkPolicy(  917): updateIfacesLocked()
E/WifiStateMachine(  917):  DefaultState !CMD_ON_QUIT 0 0
V/NetworkPolicy(  917): updateNotificationsLocked()
,E/WifiStateMachine(  917): handleMessage: X
D/NetworkManagementService(  917): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/PMS     (  917): releaseWL(28c2dd8e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  917): updateNetworkEnabledLocked()
V/NetworkPolicy(  917): updateNotificationsLocked()
D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota,
,D/PMS     (  917): releaseWL(30bb8065): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/wpa_supplicant( 1350): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1350): wlan0: Deauthentication notification
,D/wpa_supplicant( 1350): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1350): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1350): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1350): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1350): enter disconnect check
I/wpa_supplicant( 1350): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  917): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  917): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  917): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  917): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/Tethering(  917): interfaceLinkStateChanged wlan0, false
D/Tethering(  917): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  917): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1350): wlan0: Auto connect disabled: do not try to re-connect
E/WifiMonitor(  917): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/wpa_supplicant( 1350): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  917): interfaceLinkStateChanged wlan0, false
D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri,
D/Tethering(  917): interfaceStatusChanged wlan0, false
D/PMS     (  917): acquireWL(14ec61bc): PARTIAL_WAKE_LOCK  NetworkStats 0x1 917 1000 null
,E/WifiStateMachine(  917): WiFiDisplay: getWifidisplayApEnabled=false
,D/UsbDeviceManager(  917): [USBNET] bCheckSuppFunc: cdc_network
I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
I/QuickSettingWifi( 1219): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
D/PMS     (  917): releaseWL(14ec61bc): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/Tethering(  917): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/NetworkPolicy(  917): updateNetworkEnabledLocked()
V/Tethering(  917): TetherInterfaceSM: wlan0: exit InitialState
V/NetworkPolicy(  917): updateNotificationsLocked()
V/Tethering(  917): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  917): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  917): sendTetherStateChangedBroadcast 0, 0, 0
D/wpa_supplicant( 1350): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1350): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1350): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 1350): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1350): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x557e30ff88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1350):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1350): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1350): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1350): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1350): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1350): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1350): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1350): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1350): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1350): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1350): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1350): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1350): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1350): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1350): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1350): EAPOL: External notification - portValid=0
D/UsbnetService(  917): BroadcastReceiver::onReceive+
D/UsbnetService(  917): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  917): BroadcastReceiver::onReceive-
D/WifiMonitor(  917): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  917): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  917): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  917): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  917): handleMessage: E msg.what=147460
E/WifiStateMachine(  917): processMsg: SupplicantStoppingState
D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
E/WifiStateMachine(  917):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65575
E/WifiStateMachine(  917): processMsg: DefaultState
E/WifiStateMachine(  917):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65576
E/WifiStateMachine(  917): handleMessage: X
E/WifiStateMachine(  917): handleMessage: E msg.what=131101
E/WifiStateMachine(  917): processMsg: SupplicantStoppingState
E/WifiStateMachine(  917):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  917): processMsg: DefaultState
E/WifiStateMachine(  917):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  917): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  917): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  917): handleMessage: X
E/WifiStateMachine(  917): handleMessage: E msg.what=147462
E/WifiStateMachine(  917): processMsg: SupplicantStoppingState
E/WifiStateMachine(  917):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=65577  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  917): processMsg: DefaultState
E/WifiStateMachine(  917):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=65578  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  917): handleMessage: X
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  917): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/MdScPhnSt( 4947): [1fa.2.]  listen tmrbb8
,I/MusicStore( 5371): Database version: 120
,D/MdProvGlob( 4977): remove item 101 (p2d22in115) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 4947): [1fa.2.] summary 118:p2 ignore
,D/MdProvGlob( 4977): remove item 101 (p2in8) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 4977): remove item 101 (p2d1in12) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 4977): remove item 101 (p2in9) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 4977): remove item 101 (p2in10) for 15:android.intent.action.ANY_DATA_STATE
,E/cutils-trace( 5416): Error opening trace file: Permission denied (13),
,I/ActivityManager(  917): Killing 4745:com.android.smith/1000 (adj 15): empty #17,
D/Process (  917): killProcessQuiet, pid=4745
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/CustomizationManager( 5416): ====startRecUseTime====,
D/htc.customization.log.level( 5416):  is 
W/CustomizationLogLevel( 5416): Level value is invalid, use default level 2
,E/wpa_supplicant( 1350): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1350): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush
D/wpa_supplicant( 1350): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1350): wlan0: Cancelling scan request
D/wpa_supplicant( 1350): wlan0: Cancelling authentication timeout
D/WifiMonitor(  917): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/wpa_supplicant( 1350): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
E/WifiMonitor(  917): WifiMonitor:wlan0 cnt=27 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  917): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  917): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  917): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,E/WifiMonitor(  917): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  917): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  917): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
D/WifiMonitor(  917): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  917): WifiMonitor:wlan0 cnt=31 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
,I/ActivityManager(  917): Recipient 4745
,D/CustomizationManager( 5416):  Read ACC file spent 0.031 (s),
D/wpa_supplicant( 1350): Remove interface wlan0 from radio phy0
D/CIDMapFileReader( 5416): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5416): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5416): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5416): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5416): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 5416): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5416): Parsing tag item name = HTC__031
I/bt-btif ( 3467): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3467): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3467): mProfilesStarted : true supportedProfileServices.length : 6
,V/CustomizationCIDLoader( 5416): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5416): Parsing tag category name = system
,I/CustomizationCIDLoader( 5416): Parsing tag category name = application
I/CustomizationCIDLoader( 5416): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5416): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 5416): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5416): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5416): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5416): add string-array item, value = 42507
I/CustomizationCIDLoader( 5416): add string-array item, value = 21902
I/CustomizationCIDLoader( 5416): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5416): add string-array item, value = 23420
I/CustomizationCIDLoader( 5416): add string-array item, value = 22299
I/CustomizationCIDLoader( 5416): add string-array item, value = 24002
I/CustomizationCIDLoader( 5416): add string-array item, value = 23210
I/CustomizationCIDLoader( 5416): add string-array item, value = 23205
I/CustomizationCIDLoader( 5416): add string-array item, value = 23806
I/CustomizationCIDLoader( 5416): add string-array item, value = 23430
I/CustomizationCIDLoader( 5416): add string-array item, value = 23408
I/CustomizationCIDLoader( 5416): add string-array item, value = 27205
I/CustomizationCIDLoader( 5416): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5416): add string-array item, value = 27205:C:1:0
,D/CustomizationManager( 5416):  Read CID file spent 0.070 (s)
D/CustomizationManager( 5416):  All configurations done spent 0.070 (s)
,D/HeadsetService( 3467): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3329abb5
D/BluetoothAdapterState( 3467): Stopping profile services that were post enabled
,D/HeadsetStateMachine( 3467): Exit Disconnected: -1
D/BluetoothHeadset(  917): Proxy object disconnected
D/BluetoothHeadset( 4068): Proxy object disconnected
D/BluetoothHeadset( 1543): Proxy object disconnected
D/NGFService( 4068): BluetoothHeadset onServiceDisconnected: main
D/A2dpService( 3467): Received stop request...Stopping profile...
D/BluetoothHeadset( 1543): Proxy object disconnected
,D/BluetoothHeadset( 1219): Proxy object disconnected
D/A2dpStateMachine( 3467): Exit Disconnected: -1,
I/QuickSettingMiniLite( 1219): btListener.disconnect:HEADSET
D/BluetoothAdapterService( 3467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3329abb5
D/BluetoothHeadset( 1543): Proxy object disconnected
D/BluetoothPhoneService( 1543): BluetoothHeadset onServiceDisconnected
D/BluetoothA2dp(  917): Proxy object disconnected
D/HidService( 3467): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3329abb5
D/BluetoothInputDevice( 4629): Proxy object disconnected
D/HidProfile( 4629): Bluetooth service disconnected
D/HealthService( 3467): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3329abb5
,D/BluetoothA2dp( 4068): Proxy object disconnected
D/NGFService( 4068): BluetoothA2dp onServiceDisconnected: main
D/PanService( 3467): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3329abb5
D/BluetoothPan( 4629): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 3467): handleDebugAction() action=null
D/PanProfile( 4629): Bluetooth service disconnected
,D/BtGatt.GattService( 3467): Received stop request...Stopping profile...
D/BtGatt.GattService( 3467): stop()
D/BtGatt.AdvertiseManager( 3467): advertise clients cleared
,D/BluetoothAdapterService( 3467): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3329abb5
,W/BluetoothHeadsetServiceJni( 3467): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3467): Cleaning up Bluetooth Handsfree callback object
,W/BluetoothHidServiceJni( 3467): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3467): Cleaning up Bluetooth GID callback object
,D/wpa_supplicant( 1350): nl80211: Remove monitor interface: refcount=0
D/wpa_supplicant( 1350): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
W/BluetoothHealthServiceJni( 3467): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3467): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3467): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3467): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterState( 3467): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3467): Setting state to 10
I/BluetoothAdapterState( 3467): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  917): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  917): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  917): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  917): Broadcasting onBluetoothStateChange(false) to 13 receivers.
I/BluetoothAdapterState( 3467): Entering OffState
D/BluetoothHeadset( 4068): onBluetoothStateChange: up=false
,D/BluetoothPan( 4629): onBluetoothStateChange on: false
D/BluetoothHeadset( 1543): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  917): onBluetoothStateChange: up=false
D/BluetoothMap( 4629): onBluetoothStateChange: up=false
E/BluetoothMap( 4629): 
E/BluetoothMap( 4629): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@1f684a08
E/BluetoothMap( 4629): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 4629): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 4629): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 4629): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 4629): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 4629): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothA2dp(  917): onBluetoothStateChange: up=false
,D/BluetoothSap( 4629): onBluetoothStateChange on: false
V/BluetoothSapService( 3467): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@10430881
,D/PackageManager(  917): deletePackageAsUser: pkg=com.example.hello, pid=5416, uid=2000 userid=0
D/BluetoothInputDevice( 4629): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1543): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 4068): onBluetoothStateChange: up=false
,D/BluetoothPbap( 4629): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1543): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1219): onBluetoothStateChange: up=false
D/VoldConnector(  917): SND -> {24 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5371): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/BluetoothManagerService(  917): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  917): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 4718): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@243ae6f9
D/BluetoothAdapter( 4718): onBluetoothServiceDown: done
D/BluetoothAdapter( 2393): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1bfeaaa8
D/BluetoothAdapter( 2393): onBluetoothServiceDown: done
D/BluetoothAdapter(  917): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2abf9439
D/BluetoothAdapter(  917): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1219): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3d920de
D/BluetoothAdapter( 1219): onBluetoothServiceDown: done
D/BluetoothAdapter( 3467): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@34964e31
D/BluetoothAdapter( 3467): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1561): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@25c4d8f
D/BluetoothAdapter( 1561): onBluetoothServiceDown: done
D/BluetoothAdapter( 1543): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3b2fd011
D/BluetoothAdapter( 1543): onBluetoothServiceDown: done
,D/BluetoothAdapter( 4068): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3a0f01fa
D/BluetoothAdapter( 4068): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1787): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3bfb47f3
D/BluetoothAdapter( 1787): onBluetoothServiceDown: done
,D/BluetoothAdapter( 4629): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@302625a1
D/BluetoothAdapter( 4629): onBluetoothServiceDown: done
I/ActivityManager(  917): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
D/BluetoothManagerService(  917): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2abf9439 mBinding = false
,I/ActivityManager(  917): Killing 4718:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  917): killProcessQuiet, pid=4718
,D/BluetoothManagerService(  917): Sending unbind request.
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  917): Skipping PackageSetting{d73b7b4 com.test.thalitest/10366} due to missing metadata
,W/BluetoothHeadset( 1219): Proxy not attached to service
,I/QuickSettingMiniLite( 1219): updateLiteState:no connect device!
,I/ActivityManager(  917): Recipient 4718
I/WindowState(  917): WIN DEATH: Window{a767485 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  917): Client connection lost with reason: 4
,E/InputEventReceiver( 1397): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2293a883 uid 10373 pid 4718} (c)'
,D/wpa_supplicant( 1350): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1350): nl80211: Unsubscribe mgmt frames handle 0x888888ddf6b99989 (mode change)
I/wpa_supplicant( 1350): htc_wext_command_deinit +
I/wpa_supplicant( 1350): htc_wext_command_deinit -
I/wpa_supplicant( 1350): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1350): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1350): p2p0: Removing interface p2p0
D/wpa_supplicant( 1350): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1350): TDLS: Tear down peers
D/wpa_supplicant( 1350): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1350): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1350): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1350): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1350): EAPOL: External notification - portValid=0
D/WifiMonitor(  917): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  917): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  917): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  917): handleMessage: E msg.what=147458
E/WifiStateMachine(  917): processMsg: SupplicantStoppingState
E/WifiStateMachine(  917):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 32 0
E/WifiStateMachine(  917): Supplicant connection lost
,D/Tethering(  917): interfaceLinkStateChanged wlan0, false
D/Tethering(  917): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  917): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL false Token 15 num clients 8
,W/ActivityManager(  917): Force removing ActivityRecord{1145e61f u0 com.example.hello/.MainActivity t8}: app died, no saved state,
,D/BluetoothManagerService(  917): Bluetooth State Change Intent: 13 -> 10,
I/ActivityManager(  917): Force stopping com.example.hello appid=10373 user=0: pkg removed
,W/ActivityManager(  917): Spurious death for ProcessRecord{967c63e 4718:com.example.hello/u0a373}, curProc for 4718: null
,D/DotMatrix( 1308): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1308): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1308): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/IntentController( 1219): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 4068): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 4068): Bluetooth Adapter: OFF
D/LocalBluetoothProfileManager( 4629): setBluetoothStateOff
W/BluetoothEventManager( 4629): unregister mProfileBroadcastReceiver fail
,D/PMS     (  917): acquireWL(318a7c9f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1787 10024 WorkSource{10024 com.google.android.gms}
I/bt-btif ( 3467): HAL bt_hal_cbacks->thread_evt_cb
,D/AccTypeManager( 1740): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/TetherPref( 4629): persistRestoreBluetoothState false
W/GeofencerStateMachine( 1787): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 5298): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/art     ( 3467): System.exit called, status: 0
W/SystemReader(  917): Cannot find grip_rejection_width, use default value instead
D/PMS     (  917): releaseWL(318a7c9f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/Prism.ItemManager( 5298): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/FeedHostManager( 1599): [onResume]
I/FeedProviderManager( 1599): onResume
I/SocialFeedProvider( 1599): +onResume
I/SocialFeedProvider( 1599): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1599): -onResume
,I/ConnectivityHelper( 1599): [getCurrentConnectionType] no network connection
W/ResourcesManager( 1543): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Prism.ItemManager( 1599): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1599): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1740): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/StatusBarManagerService(  917): setSystemUiVisibility(0x700)
,D/BluetoothAdapter( 1219): 524552602: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService(  917): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/QuickSettingBluetooth( 1219): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
D/StatusBarManagerService(  917): hiding MENU key
,D/FindExtension( 1599): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1599): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  917): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/VoldConnector(  917): SND -> {25 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
W/ContextImpl( 5371): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  917): SND -> {26 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5371): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/AccTypeManager( 1740): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/HtcModeClient( 3553): handler message = 4011
,E/HtcModeClient( 3553): Check connection and retry 4 times.
,W/InputMethodManagerService(  917): Got RemoteException sending setActive(false) notification to pid 4718 uid 10373
,D/StatusBarManagerService(  917): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  917): Enable input method client, pid=1599
,D/PhoneApp( 1543): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  917): Recipient 3467
I/ActivityManager(  917): Process com.android.bluetooth (pid 3467) has died
W/ActivityManager(  917): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  917): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
I/BroadcastQueue(  917): Schedule to resend BroadcastRecord{2942e8dd u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=917 callingUid=1000} for ResolveInfo{2c5eac52 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,E/ExternalAccountType( 1740): Unsupported attribute readOnly
,I/ActivityManager(  917): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5460 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
W/ResourcesManager( 5371): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5371): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager(  917): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/StatusBarManagerService(  917): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  917): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  917): hiding MENU key
W/PackageManager(  917): Unable to load service info ResolveInfo{1552f677 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  917): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  917): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  917): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  917): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  917): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  917): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  917): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  917): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  917): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  917): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  917): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  917): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
V/JNIHelp ( 5371): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     (  917): Explicit concurrent mark sweep GC freed 40476(2MB) AllocSpace objects, 3(124KB) LOS objects, 33% free, 16MB/25MB, paused 11.269ms total 222.395ms,
I/art     (  917): WaitForGcToComplete blocked for 18.238ms for cause Explicit,
,W/asset   (  917): Copying FileAsset 0x5565585dd0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,W/ActivityThread( 5371): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5371): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@121a9599: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5371): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5371): GMSCore installation verified
,I/wpa_ctrl(  917): [wpa_ctrl_close] ctrl=0x556544cda0
,I/wpa_ctrl(  917): [wpa_ctrl_close] ctrl=0x556544ce90
D/WIFI_ICON( 1219): updateWifiState: WIFI_STATE_CHANGED disabled
E/WifiStateMachine(  917): setWifiState: disabled
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  917): Enter handleNetworkDisconnect
D/PMS     (  917): acquireWL(1559b21a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 917 1000 null
W/Settings( 4919): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI_ICON( 1219): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  917): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1219): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
E/WifiStateMachine(  917): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  917): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  917): Exit handleNetworkDisconnect
E/WifiStateMachine(  917): [MLHD] Error! unhandled message 6 { when=-416ms what=147458 arg1=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  917): transitionTo: destState=InitialState
E/WifiStateMachine(  917): handleMessage: new destination call exit/enter
E/WifiStateMachine(  917): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  917): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  917): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  917): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  917): invokeEnterMethods: InitialState
W/Settings( 1787): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/IntentController( 1219): receive(android.net.wifi.STATE_CHANGE,1,false)
I/ConfigStore( 5371): Config Database version: 1
,D/NfcHandover( 1561): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false,
,I/QuickSettingWifi( 1219): receive.wifiState:WIFI_STATE_DISABLED setEnable:true,
,I/QuickSettingWifi( 1219): receive.wifiConnect:false wifiAPname:null elapse:0,
,D/JobSchedulerService(  917): Receieved: android.intent.action.PACKAGE_REMOVED,
,D/TaskPersister(  917): removeObsoleteFile: deleting file=8_task.xml
,E/WifiTrafficPoller(  917): TRAFFIC_STATS_POLL false Token 15 num clients 8
E/WifiTrafficPoller(  917): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
,I/art     (  917): Explicit concurrent mark sweep GC freed 8907(493KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.285ms total 166.548ms
,D/WISPrService( 4629): >>>>>WISPrService start isConnected = false<<<<<
W/ResourcesManager( 5460): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/WISPrService( 4629): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
,I/ActivityManager(  917): Waited long enough for: ServiceRecord{1ce27548 u0 com.htc.HTCSpeaker/.NGFService},
,D/AdapterServiceConfig( 5460): Adding HeadsetService,
D/AdapterServiceConfig( 5460): Adding A2dpService
D/AdapterServiceConfig( 5460): Adding HidService
D/AdapterServiceConfig( 5460): Adding HealthService
D/AdapterServiceConfig( 5460): Adding PanService
D/AdapterServiceConfig( 5460): Adding GattService
,V/BluetoothPbapReceiver( 5460): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5460): ***********state = 10
,E/BluetoothMasService( 5460): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/PMS     (  917): acquireWL(3e185340): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4629 1000 null
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PMS     (  917): releaseWL(3e185340): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  917): acquireWL(1c6abbbe): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4629 1000 null
,D/BluetoothMasService( 5460): Add permission for SmsProvider.
,D/HtcBtWidget_BTWidgetProvider( 5393): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5393): updateWidget(context) for widget: 
D/BluetoothManagerService(  917): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  917): java.lang.Throwable: stack dump
W/System.err(  917): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  917): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  917): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:454)
D/DockEventReceiver( 4629): finishStartingService: stopping service
,V/BluetoothMasService( 5460): Starting MAS instances
D/PMS     (  917): releaseWL(1c6abbbe): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothAdapter( 5460): 826536896: getState() :  mService = null. Returning STATE_OFF
I/MailMessageReceiver( 5460): reg:com.android.bluetooth.btservice.AdapterApp@34b378f9 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@28dc903e
D/BluetoothManagerService(  917): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3acf636c:true,
I/MailManager( 5460): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@28dc903e
V/EmailUtils( 5460): Manager Instance is not NULL
,I/ActivityManager(  917): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5484 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5371, uid=10159, userID:0
,D/WifiDisplayAdapter(  917): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  917):     Client/Owner: Client
D/WifiDisplayAdapter(  917):     GroupId: 
D/WifiDisplayAdapter(  917):     Passphrase: 
D/WifiDisplayAdapter(  917):     SessionId: 0
D/WifiDisplayAdapter(  917):     IP Address: }
,D/MediaRouterService(  917): Client com.google.android.music (pid 5371): Registered
,D/WifiDisplayAdapter(  917): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  917):     Client/Owner: Client
D/WifiDisplayAdapter(  917):     GroupId: 
D/WifiDisplayAdapter(  917):     Passphrase: 
D/WifiDisplayAdapter(  917):     SessionId: 0
D/WifiDisplayAdapter(  917):     IP Address: }
,I/MediaRouter( 5371): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/HtcAdjCursorFactory( 5484): Set CursorWindow size to: 4194304 KB, Tid: 5504,
,D/PMS     (  917): acquireWL(2150df21): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5371 10159 null
,D/EmailUtils( 5460): ============NULL aList========
,V/EmailUtils( 5460): <-getEmailAccountIdList
V/BluetoothMasService( 5460): onCreate: mIsEmailEnabled: true
,D/BluetoothMasReceiver( 5460): Bluetooth STATE CHANGED to 10,
,V/BluetoothMasService( 5460): onDestroy: mIsEmailEnabled: true,
D/Process (  917): killProcessQuiet, pid=4830
I/ActivityManager(  917): Killing 4830:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/OpenGLRenderer( 1599): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ActivityManager(  917): Recipient 4830
,V/BluetoothSapReceiver( 5460): SapReceiver onReceive 
V/BluetoothSapReceiver( 5460): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5460):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5460): startService = false
,I/ActivityManager(  917): Killing 4767:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  917): killProcessQuiet, pid=4767
,D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  917): Recipient 4767
,D/Tethering(  917): interfaceRemoved wlan0
E/Tethering(  917): attempting to remove unknown iface (wlan0), ignoring
,D/AuthorizationBluetoothService( 1971): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
V/AlarmManager(  917): sending alarm PendingIntent{20d06cd: PendingIntentRecord{272c8b82 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=67081, Int=0
,D/Tethering(  917): interfaceLinkStateChanged p2p0, false,
D/Tethering(  917): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  917): WiFiDisplay: getWifidisplayApEnabled=false
,D/MtpReceiver( 4150): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 4150): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 4150): [MTP][handleUsbState]+
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5371, uid=10159, userID:0
I/ActivityManager(  917): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5517 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
D/MtpReceiver( 4150): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpReceiver( 4150): [MTP][handleUsbState]-
D/MtpReceiver( 4150): [MTP][handleMessage]-
,D/MtpService( 4150): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 4150): TotalSize=1886532,MediaCacheLimit=6000
,D/PMS     (  917): acquireWL(993fbfc): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2208 10024 null
,I/MusicLeanback( 5371): Stop autocaching.
,I/MusicLeanback( 5371): Stop autocaching.
,D/MtpService( 4150): [isMtpConnected] connected: true
,I/PackageManager(  917):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5371, uid=10159, userID:0,
D/Tethering(  917): interfaceRemoved p2p0
E/Tethering(  917): attempting to remove unknown iface (p2p0), ignoring
,D/PMS     (  917): releaseWL(2150df21): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 5371): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5371): Stop autocaching.
,I/MusicLeanback( 5371): Stop autocaching.
I/GHttpClientFactory( 5371): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5371): Using platform SSLCertificateSocketFactory
,I/iu.UploadsManager( 2208): End new media; added: 0, uploading: 0, time: 53 ms
,D/PMS     (  917): releaseWL(993fbfc): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,E/MediaScannerService( 4150): [onStartCommand] --- Should not be here, redirect request. ----,
E/MediaScannerService( 4150): [handleMessage] --- Should not be here, ignore request. ----
,W/FileUtils( 5223): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system),
E/SQLiteDatabase( 5517): Failed to open database '/data/data/com.nero.android.htc.sync/databases/nccontentprovider.db'.
,E/SQLiteDatabase( 5517): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5517): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5517): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5517): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5517): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/SQLiteDatabase( 5517): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 5517): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 5517): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
,E/SQLiteDatabase( 5517): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 5517): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 5517): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 5517): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 5517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5517): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5517): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 5517): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5517): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5517): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 5517): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 5517): FATAL EXCEPTION: main
E/AndroidRuntime( 5517): Process: com.nero.android.htc.sync, PID: 5517
E/AndroidRuntime( 5517): java.lang.RuntimeException: Unable to get provider com.nero.android.neroconnect.contentprovider.NCContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5517): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 5517): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 5517): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 5517): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 5517): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 5517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5517): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5517): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 5517): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5517): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5517): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 5517): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 5517): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5517): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5517): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5517): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5517): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5517): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/AndroidRuntime( 5517): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 5517): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 5517): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 5517): 	... 11 more
E/ActivityManager(  917): App crashed! Process: com.nero.android.htc.sync
D/ErrorReport(  917): HtcErrorReportManager Begin---add error logs to dropbox
E/GmsUtils( 5371): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/ServiceConnection( 5223): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 5223): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 5223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 5223): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1114)
W/ServiceConnection( 5223): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
W/ServiceConnection( 5223): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 5223): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 5223): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 5223): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 5223): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 5223): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 5223): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 5223): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 5223): 	... 7 more
E/GmsUtils( 5371): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/FileUtils( 5223): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/ServiceConnection( 5223): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 5223): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 5223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 5223): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1114)
W/ServiceConnection( 5223): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
W/ServiceConnection( 5223): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 5223): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 5223): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 5223): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 5223): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 5223): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 5223): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 5223): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 5223): 	... 7 more
I/ActivityManager(  917): Killing 5002:com.google.android.youtube/u0a176 (adj 15): empty #17
W/System.err(  917): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
D/Process (  917): killProcessQuiet, pid=5002
,D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/System.err(  917): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  917): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  917): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  917): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  917): 	,at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  917): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  917): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  917): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  917): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  917): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  917): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  917): 	at libcore.io.Posix.open(Native Method)
W/System.err(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  917): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  917): 	... 12 more
W/System.err(  917): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  917): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  917): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  917): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  917): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  917): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  917): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  917): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  917): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  917): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  917): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  917): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  917): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  917): 	at libcore.io.Posix.open(Native Method)
W/System.err(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  917): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  917): 	... 14 more
,W/System.err(  917): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,W/System.err(  917): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  917): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  917): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  917): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  917): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  917): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  917): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  917): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
,W/System.err(  917): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  917): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  917): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  917): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  917): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  917): 	at libcore.io.Posix.open(Native Method)
W/System.err(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  917): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  917): 	... 14 more
,E/MediaScannerServiceEx( 4150): [getStorageMaskIdFromPath] path is null,
,D/MediaScannerServiceEx( 4150): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 4150): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 4150): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4150): calcVolumeId: /storage/ext_sd,
,D/MediaProviderUtils( 4150): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4150): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 4150): [AliveExtStorageRows]+65537, 11223344
,I/ActivityManager(  917): Recipient 5002
,E/ErrorReport(  917): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  917): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448386003716.dbox_tmp: open failed: EROFS (Read-only file system),
E/ErrorReport(  917): 	,at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  917): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  917): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  917): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  917): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  917): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  917): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  917): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  917): 	... 4 more
,W/ActivityManager(  917): Can't addPackageDependency on system process
,D/StatusBarManagerService(  917): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  917): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  917): hiding MENU key
,I/Prism.ItemManager( 5298): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 5298): loadItems() com.htc.launcher.pageview.WidgetManager@21e79269 +
I/Prism.WidgetManager( 5298): onLoadItems() +
,I/Prism.ItemManager( 1599): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1599): loadItems() com.htc.launcher.pageview.WidgetManager@313be0c1 +
I/Prism.WidgetManager( 1599): onLoadItems() +
,D/Process (  917): killProcessQuiet, pid=5082
,I/ActivityManager(  917): Killing 5082:com.google.android.gm/u0a106 (adj 15): empty #17
,D/Process (  917): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
,W/ResourcesManager( 1599): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5298): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  917): Recipient 5082,
,I/GAv4-SVC( 2208): Google Analytics 7.8.99 is starting up.

```
