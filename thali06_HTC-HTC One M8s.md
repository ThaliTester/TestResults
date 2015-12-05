#### Test 50388019f33194e_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1439):  slotId = -1000
D/MmsSmsV2Provider( 1439): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/DraftCache( 4413): [DraftCache/111] rebuildCache
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 234us total 28.040ms
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
D/MmsSmsV2Provider( 1439):  slotId = -1000
D/MmsSmsV2Provider( 1439): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MessageCustFlag( 4413): sense_version=6.0
D/Jerry   ( 4413): start to preload cursor >>>>>>>
D/Messaging( 4413): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 195us total 22.453ms
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  972):  packet count Tx=106 Rx=134
,--------- beginning of system
I/ActivityManager(  972): Recipient 4061
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/Jerry   ( 1439): URI_DRAFT
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
D/MmsSmsV2Provider( 1439):  slotId = -1000
D/MmsSmsV2Provider( 1439): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4413): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4413): [DraftCache/111] rebuildCache time: 9
D/MmsAsyncWorkHandler( 4413): 
D/MmsAsyncWorkHandler( 4413): HM tk = 20002
D/UpdaterAPK | UpdaterBootCompleteReceiver( 4579): onReceive() - start htcCheckinService
D/PhoneStorageUtil( 4413): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4413): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4413): createReceiver
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1439):  slotId = -1000
D/Messaging( 4413): mNeedToUpdateDate2: false
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
I/htcCheckinService(  972): htcCheckinProvider V2.1
D/AccFlag ( 1439): sku_id=118
D/htcCheckinService(  972): htcCheckinService() the mIsServiceRunning = true
I/htcCheckinService(  972): Checkin service onCreate()!
D/Messaging( 4413): ViewCache CreatePreload
D/Messaging( 4413): ViewCache CreatePreloadOnlyMultipleOpsList
D/Cust_MMSMS( 4413): _has_set_default_values_2=true
D/MsgPreferenceUtils( 4413): def_index: 0
D/MsgPreferenceUtils( 4413): globalIndex = 1
D/MsgPreferenceUtils( 4413): phone state: true
I/ActivityManager(  972): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4615 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a
D/MsgPreferenceUtils( 4413): sd state: false
D/MsgPreferenceUtils( 4413): vIndex = 0
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/AccFlag ( 1439): sku_id=118
D/htcCheckinService(  972): onStartCommand()
D/htcCheckinService(  972): onStartCommand() the action name = null
D/htcCheckinService(  972): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  972): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/ActivityManager(  972): Killing 4001:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4001
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/htcCheckinService(  972): InitThread start
I/ActivityManager(  972): Recipient 4001
D/TelephUtils( 1439): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
V/MmsProvider( 1439): Update uri=content://mms, match=0
V/MmsProvider( 1439): selection=st=129 AND m_type!=134
D/Messaging( 4413): Reset downloading state: 0
V/MmsSystemEventReceiver( 4413): TransactionService is going to be woken up.
V/TransactionService( 4413): 1-Creating TransactionService
V/TransactionService( 4413): onStartCommand: 1
D/MmsSystemEventReceiver( 4413): unRegisterForConnectionStateChanges
V/TransactionService( 4413): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4413): Loading previous transactions.
E/cutils-trace( 4610): Error opening trace file: Permission denied (13)
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1439): device_type: 1
D/TransactionService( 4413): Force clearing mTransactionList
D/TransactionService( 4413): Force set service start id to 1
V/TransactionService( 4413): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4413): unRegisterForConnectionStateChanges
D/TransactionService( 4413): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4413): Destroying TransactionService
V/TransactionService( 4413): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/PMS     (  972): acquireWL(22e44e99): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 4615 10090 null
I/WorldClock.Global( 4615): isHEPDevice = true
W/ContextImpl(  972): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
D/CustomizationManager( 4610): ====startRecUseTime====
D/htc.customization.log.level( 4610):  is 
W/CustomizationLogLevel( 4610): Level value is invalid, use default level 2
W/SystemReader( 4615): Cannot find support_china_sense_feature, use default value instead
I/ActivityManager(  972): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4670 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
I/WorldClock.AlarmUtils( 4615): saveSupportOffAlarmInPreference: isSupport = false
I/WorldClock.AlarmService( 4615): isDeviceEncryptionEnabled = false
D/PMS     (  972): releaseWL(22e44e99): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
D/Process (  972): killProcessQuiet, pid=4084
I/ActivityManager(  972): Killing 4084:com.htc.home.personalize/1000 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/WorldClock.AlarmService( 4615): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
I/WorldClock.AlarmUtils( 4615): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
D/CustomizationManager( 4610):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 4610): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4610): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4610): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4610): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4610): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4610): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4610): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4610): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4610): Parsing tag category name = system
I/CustomizationCIDLoader( 4610): Parsing tag category name = application
I/CustomizationCIDLoader( 4610): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4610): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4610): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4610): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4610): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4610): add string-array item, value = 42507
I/CustomizationCIDLoader( 4610): add string-array item, value = 21902
I/CustomizationCIDLoader( 4610): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4610): add string-array item, value = 23420
I/CustomizationCIDLoader( 4610): add string-array item, value = 22299
I/CustomizationCIDLoader( 4610): add string-array item, value = 24002
I/CustomizationCIDLoader( 4610): add string-array item, value = 23210
I/CustomizationCIDLoader( 4610): add string-array item, value = 23205
I/CustomizationCIDLoader( 4610): add string-array item, value = 23806
I/CustomizationCIDLoader( 4610): add string-array item, value = 23430
I/CustomizationCIDLoader( 4610): add string-array item, value = 23408
I/CustomizationCIDLoader( 4610): add string-array item, value = 27205
I/CustomizationCIDLoader( 4610): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4610): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4610):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4610):  All configurations done spent 0.089 (s)
D/MediaProvider( 4363): [update][5]#1#
I/ActivityManager(  972): Recipient 4084
I/WorldClock.AlarmUtils( 4615): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4615): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
D/PMS     (  972): acquireHCC(1697800d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 972 1000 null
D/PMS     (  972): acquireHCC(1e93abc2): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 972 1000 null
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4610 on display 0
W/asset   (  972): Copying FileAsset 0x55a62addb0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  972): acquireWL(15491009): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 972 1000 null
I/IntentController( 1218): receive(android.intent.action.ALARM_CHANGED,1,false)
I/FeedHostManager( 1506): [onPause]
I/FeedProviderManager( 1506): onPause
I/FeedHostManager( 1506): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3952c903
I/SocialFeedProvider( 1506): +onPause
I/SocialFeedProvider( 1506): -onPause
I/AnimationUtil(  972): isHTCRecent(HelloWorld/Recent screens.)/5
I/WorldClock.AlarmUtils( 4615): isDeviceEncryptionEnabled = false
I/WorldClock.AlarmUtils( 4615): Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.AlarmService( 4615): resetStopwatchToDefault
W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/WorldClock.DmdCmd( 4615): This version is general off mode alarm function
W/WorldClock.DmdCmd( 4615): Conn: fail e = java.io.IOException: No such file or directory
I/ActivityManager(  972): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4698 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/asset   ( 4698): Copying FileAsset 0xac42dd58 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/WorldClock.AlarmService( 4615): resetTimerToDefault
D/StatusBarManagerService(  972): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
E/UpdateRequestReceiver( 4670): ignoring update request
E/WifiStateMachine(  972): handleMessage: E msg.what=131155
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=9.0, 0.0, 0.0  rx=13.4 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:1871285085] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
I/TrimMemoryManager( 1506): [trimMemory] 20
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=9.0, 0.0, 0.0  rx=13.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1871285086] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1400): wlan0: Control interface command 'SIGNAL_POLL'
E/UpdateRequestReceiver( 4670): ignoring update request
E/UpdateRequestReceiver( 4670): ignoring update request
I/wpa_supplicant( 1400): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  972): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.48 txretriesrate=0.00 rxrate=7.19 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  972):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -57, 3
E/WifiStateMachine(  972): handleMessage: X
E/UpdateRequestReceiver( 4670): ignoring update request
E/UpdateRequestReceiver( 4670): ignoring update request
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/UpdateRequestReceiver( 4670): ignoring update request
I/ActivityManager(  972): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4732 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
D/Process (  972): killProcessQuiet, pid=2922
I/ActivityManager(  972): Killing 2922:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/WebViewFactory( 4698): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
V/SmsReceiverService( 4413): updateNotificationAndShortcutStatus: 
D/MessagingNotification( 4413): New incoming message, can't cancel notification now
D/MessagingNotification( 4413): newMsgCnt: 0, false
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  972):  packet count Tx=106 Rx=135
E/WifiTrafficPoller(  972): notifying of data activity 1
D/WIFI_ICON( 1218): WifiActivity: 1
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ActivityManager(  972): Recipient 2922
D/MediaScanner( 4363):  prescan time: 1272ms
D/MediaScanner( 4363):     scan time: 1665ms
D/MediaScanner( 4363): postscan time: 3ms
D/MediaScanner( 4363):    total time: 2940ms
D/MediaScanner( 4363): -----------------------------------------------------------------
D/MediaScanner( 4363): firstscan(media) time: 1263ms
D/MediaScanner( 4363): secondscan(non-media) time: 402ms
D/MediaScanner( 4363):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4363):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4363):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4363):  [Total]    File(Image+Video+Audio+Others) in database : 1546
I/ActivityManager(  972): Killing 4107:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4107
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/MediaProvider( 4363): [delete][40]
D/MediaProvider( 4363): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 4363): [recoverParentNodes] - 0
D/MediaProvider( 4363): [update][4]
D/MediaScannerServiceEx( 4363): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 4363): [updateImage]+
D/MediaScannerServiceEx( 4363): [updateImage]-0
I/LibraryLoader( 4698): Time to load native libraries: 9 ms (timestamps 7808-7817)
I/LibraryLoader( 4698): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4698): Binding Chromium to main looper Looper (main, tid 1) {841a83}
I/LibraryLoader( 4698): Expected native library version number "",actual native library version number ""
I/chromium( 4698): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  972): Recipient 4107
I/BrowserStartupController( 4698): Initializing chromium process, singleProcess=true
W/art     ( 4698): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4698): ApplicationContext is null in ApplicationStatus
D/MediaScannerServiceEx( 4363): [2] scan finished
D/PMS     (  972): releaseWL(c86e4ab): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/PMS     (  972): releaseWL(19c4f525): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
D/MediaProviderUtils( 4363): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4363): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4363): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4363): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 4363): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 4363): [disAliveExtStorageRows]+131073
I/DeviceManagement( 4732): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4732 dbg=false s=true
I/DeviceManagement( 4732): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/DeviceManagement( 4732): WorkflowService: Starting workflow service
I/DeviceManagement( 4732): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@39da1a7e] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 4732): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 4732): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 4732): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 4732): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  972): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4757 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/GoogleHttpClient( 1934): GMS http client unavailable, use old client
D/MediaProvider( 4363): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 4363): [update][49]#1#
I/DeviceManagement( 4732): BackgroundController: *** Update after boot...
I/DeviceManagement( 4732): SessionStateController: Checking invariants...
D/MediaProvider( 4363): [update][21]#0#
D/MediaScannerServiceEx( 4363): [disAliveExtStorageRows]--1, 0
D/MediaProviderUtils( 4363): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4363): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4363): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4363): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 4363): Process mounted intent for unmounted storage: /storage/usb
W/chromium( 4698): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4698): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4698): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/MediaScannerServiceEx( 4363): [disAliveExtStorageRows]+196609
I/Adreno-EGL( 4698): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4698): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4698): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4698): Local Branch: 
I/Adreno-EGL( 4698): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4698): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4698):                  d74aa161a12b9c6fc6332151
D/MediaProvider( 4363): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 4363): [update][11]#1#
D/MediaProvider( 4363): [update][18]#0#
D/MediaScannerServiceEx( 4363): [disAliveExtStorageRows]--1, 0
E/MediaScannerServiceEx( 4363): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 4363): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 4363): [handleExternalVolume] ext storage
D/MediaProviderUtils( 4363): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4363): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4363): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4363): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 4363): [AliveExtStorageRows]+65537, 11223344
I/htcbackup-core( 4757): ModelRegistry: Loading model meta data from resources...
D/MediaProvider( 4363): [update][6]#0#
D/MediaProvider( 4363): [update][2]#0#
D/MediaProvider( 4363): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 4363): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 4363): [update][12]#1#
D/MediaScannerServiceEx( 4363): [AliveExtStorageRows]-0, 0
W/System.err(  972): java.lang.Throwable: stack dump
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32540835:true
D/BluetoothAdapter( 4698): 33341484: getState(). Returning 12
I/DeviceManagement( 4732): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/DeviceManagement( 4732): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
I/DeviceManagement( 4732): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
I/ActivityManager(  972): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4803 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActionCombine( 4757): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/DeviceManagement( 4732): BackgroundController: Invariants are unchanged.
W/art     ( 4698): Attempt to remove local handle scope entry from IRT, ignoring
I/DeviceManagement( 4732): SessionStateController: Checking invariants...
I/art     (  972): Explicit concurrent mark sweep GC freed 22362(1115KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.213ms total 155.963ms
D/PMS     (  972): acquireWL(2ce5669c): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4363 10017 null
D/MediaScanner( 4363): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
E/WifiDataStallTracker(  972): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=89 rxSum=79} preTxRxSum={txSum=85 rxSum=77}
D/WifiDataStallTracker(  972): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
W/AwContents( 4698): onDetachedFromWindow called when already detached. Ignoring
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
D/SystemWebViewEngine( 4698): CordovaWebView is running on device made by: HTC
I/RemoteViews( 1218): apply : com.htc.backup 0 13 4 38
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/ActivityManager(  972): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4837 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
I/ActivityManager(  972): Killing 4128:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4128
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/DeviceManagement( 4732): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
I/RemoteViews( 1218): apply : com.htc.backup 0 20 3 5
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1218): apply : com.htc.backup 0 2 1 5
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1218): apply : com.htc.backup 0 2 1 5
I/RemoteViews( 1218): apply : com.htc.backup 1 13 32 50
I/ActivityManager(  972): Recipient 4128
W/art     ( 4698): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4698): Attempt to remove local handle scope entry from IRT, ignoring
I/DeviceManagement( 4732): Perf: *** Cache update - start...
I/DeviceManagement( 4732): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4732): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4732): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 4732): Perf: Scan enabled apps - start...
D/ResetNotifyBootCompleteReceiver( 1439): userSerialNumber = 0
D/ResetNotifyBootCompleteReceiver( 1439): Receive bootcomplete intent
D/ResetNotifyBootCompleteReceiver( 1439): isOwnerUser = true
I/DeviceManagement( 4732): EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...
I/ActivityManager(  972): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4866 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/chromium( 4698): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/DeviceManagement( 4732): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
D/FindExtension( 4698): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/ResourcesManager( 4732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/HtcCupdXmlParser( 4837): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/HtcModeClient( 3731): handler message = 4011
E/HtcModeClient( 3731): Check connection and retry 2 times.
D/ActivityThread( 4837): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
I/DeviceManagement( 4732): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159
I/DeviceManagement( 4732): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167
W/ResourcesManager( 4732): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/InputMethodManager( 4698): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@27c68c5c, mServedView=org.apache.cordova.engine.SystemWebView{1975fb65 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1ef3003a
I/InputMethodManagerService(  972): Disable input method client, pid=1506
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  972): Enable input method client, pid=4698
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
I/ActivityManager(  972): Displayed com.example.hello/.MainActivity: +1s214ms
I/DeviceManagement( 4732): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351
D/PMS     (  972): releaseWL(15491009): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  972):  packet count Tx=106 Rx=135
E/WifiTrafficPoller(  972): notifying of data activity 0
D/WIFI_ICON( 1218): WifiActivity: 0
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/ResourcesManager( 4732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/QXDM2SD:HtcNative( 1439): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
W/XT9_C   ( 1364): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1364): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1364): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1364): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 4698): Cannot call determinedVisibility() - never saw a connection for the pid: 4698
I/ActivityManager(  972): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4895 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/chromium( 4698): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/ResourcesManager( 4732): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4732): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/HtcCupdXmlParser( 4837): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
I/DeviceManagement( 4732): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193
D/JsMessageQueue( 4698): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4698): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/ContactMessageStore( 1439): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1439): MSG_NOTIFY_CS_TO_SYNC <<
I/AlarmManager(  972): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  972): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  972): [AlarmQueuing] init alarm queuing list
D/jxcore_app_log( 4698): JniHelper::setJavaVM(0xab2c08f8), pthread_self() = -1403153080
D/JX-Cordova( 4698): jxcore cordova android initializing
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4895): -onCreate()
I/ActivityManager(  972): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4918 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
I/ActivityManager(  972): Killing 4151:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4151
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ResourceType( 4732): ResTable_typeSpec entry count inconsistent: given 2, previously 1426
W/jxcore-log( 4698): Initializing JXcore engine
W/jxcore-log( 4698): JXcore engine is ready
W/jxcore-log( 4698): Starting JXcore engine
I/DeviceManagement( 4732): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019
I/ActivityManager(  972): Recipient 4151
W/ResourcesManager( 4732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/Settings:HtcSettingsApplication( 4895): [4895/4895] onCreate()
D/Process (  972): killProcessQuiet, pid=4174
I/ActivityManager(  972): Killing 4174:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/ContextImpl( 4895): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
W/ResourcesManager( 4732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/DeviceManagement( 4732): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
W/ResourcesManager( 4732): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
W/ResourcesManager( 4732): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  972): Recipient 4174
W/jxcore-log( 4698): Platform android
W/jxcore-log( 4698): 
W/jxcore-log( 4698): Process ARCH arm
W/jxcore-log( 4698): 
I/ActivityManager(  972): Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4939 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/AlarmManager(  972): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@28a807ef
D/TetherSettings( 4895): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4895): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4895): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4895): Cust_ConnectToPC   : spcsc>false
D/        ( 4895): Cust_ConnectToPC   : IPT>true
D/        ( 4895): Cust_ConnectToPC   : Singel_USB>false
I/jxcore-log( 4698): JXcore Cordova bridge is ready!
I/jxcore-log( 4698): 
W/jxcore-log( 4698): JXcore engine is started
I/AlarmManager(  972): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@13d062fc
W/ResourcesManager( 4732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Settings( 4895): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4895): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4895): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4895): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/AlarmManager(  972): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@38cb1d85
I/SmartNS_Utility( 4895): setISNotification
D/SmartNS_Utility( 4895): usb_cable_connect = 1
D/SmartNS_Utility( 4895): usb_denied = 0
I/SmartNS_PSService( 4895): usb notificaiton:true
E/jxcore-log( 4698): >> HTC-HTC One M8s
E/jxcore-log( 4698): 
I/jxcore-log( 4698): Total memory 1931808768
I/jxcore-log( 4698): 
I/jxcore-log( 4698): Free memory 92459008
I/jxcore-log( 4698): 
I/jxcore-log( 4698): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4698): 
I/jxcore-log( 4698): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4698): 
I/jxcore-log( 4698): userPath [ 'www' ]
I/jxcore-log( 4698): 
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  972): [AlarmQueuing] add queuing package: jp.naver.line.android
I/jxcore-log( 4698): Size 1080 1776
I/jxcore-log( 4698): 
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.sina.weibo
D/Process (  972): killProcessQuiet, pid=4196
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.facebook.orca
I/ActionCombine( 4895): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/AlarmManager(  972): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
I/AlarmManager(  972): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/jxcore-log( 4698): Screen Brightness 142
I/jxcore-log( 4698): 
I/AlarmManager(  972): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
E/jxcore-log( 4698): Dummy Error Log.
E/jxcore-log( 4698): 
I/ActivityManager(  972): Killing 4196:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/SmartNS_Utility( 4895): usb_cable_connect = 1
D/SmartNS_Utility( 4895): usb_denied = 0
I/SmartNS_PSService( 4895): usb notificaiton:true
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
W/ResourcesManager( 4732): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 4732): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,V/Settings:HtcSettingsApplication( 4939): [4939/4939] onCreate()
,I/DeviceManagement( 4732): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686,
,I/DeviceManagement( 4732): EnabledAppBuilder: Found 8 DM enabled apps.
,I/ActivityManager(  972): Recipient 4196
I/DeviceManagement( 4732): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/PMS     (  972): releaseHCC(1697800d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  972): releaseHCC(1e93abc2): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
I/RemoteViews( 1218): reapply : com.android.settings 1 36
I/DeviceManagement( 4732): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1218): reapply : com.android.settings 0 36
D/Process (  972): killProcessQuiet, pid=4228
I/ActivityManager(  972): Killing 4228:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/DeviceManagement( 4732): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 4732): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 4732): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,I/DeviceManagement( 4732): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
,I/DeviceManagement( 4732): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,I/DeviceManagement( 4732): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 4732): Perf: Scan enabled apps - complete: 1131 ms,
I/DeviceManagement( 4732): Perf: *** Enabled app cache update - complete: 1132 ms
I/DeviceManagement( 4732): Perf: *** Config cache update - start...
,I/DeviceManagement( 4732): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4732): ConfigCacheController: *** Updating stale config cache entries...
,I/DeviceManagement( 4732): ConfigCacheController: *** Update config cache: updating 0 entries...,
,I/DeviceManagement( 4732): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4732): AlarmController: Scheduling TTL alarm for: 2015.12.05 at 11:31:55.333 CET (due to: com.htc.launcher)
,I/ActivityManager(  972): Recipient 4228,
,D/Process (  972): killProcessQuiet, pid=4264,
I/ActivityManager(  972): Killing 4264:com.htc.lmw/u0a58 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4732, uid=10099, userID:0
I/DeviceManagement( 4732): Perf: *** Config cache update - complete: 83 ms
I/DeviceManagement( 4732): Perf: *** Cache update - complete: 1223 ms
,I/DeviceManagement( 4732): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@39da1a7e]
,W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  972): Recipient 4264
,I/DeviceManagement( 4732): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@27c2df57] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 4732): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
,I/DeviceManagement( 4732): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 4732): SessionStateController: Checking invariants...
,I/ActivityManager(  972): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4965 uid=9987 gids={49987, 9997} abi=arm64-v8a
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  972):  packet count Tx=106 Rx=135
,D/SmartDim(  972): Init customizeScreenOffDelayClass error
,I/art     (  407): Explicit concurrent mark sweep GC freed 8660(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 297us total 31.747ms,
W/BroadcastQueue(  972): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{18c01594 u0 ReceiverList{40305e7 972 system/1000/u0 local:1e0307a6}}
I/SensorManager(  972): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@223eb2e8, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  972): enable: get sensor name = Accelerometer Sensor
W/SensorService(  972): pid=972, uid=1000
W/SensorService(  972): Active sensors: size = 3
W/SensorService(  972): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  972): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@223eb2e8, eanble = 1, strlen(mName) = 36
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  972): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@21b9cc5a
W/SensorService(  972): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@b78b2f6
W/SensorService(  972): Listener[2] = com.htc.smartdim.sensor_eye@223eb2e8
W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  972): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@223eb2e8, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  972): enable: get sensor name = CM36686 Proximity sensor
W/SensorService(  972): pid=972, uid=1000
W/SensorService(  972): Active sensors: size = 4
W/SensorService(  972): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  972): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  972): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@223eb2e8, eanble = 1, strlen(mName) = 36
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  972): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@21b9cc5a
W/SensorService(  972): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@b78b2f6
W/SensorService(  972): Listener[2] = com.htc.smartdim.sensor_eye@223eb2e8
W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 25.011ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 169us total 27.117ms
,I/DeviceManagement( 4732): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4732): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@27c2df57],
I/ActivityManager(  972): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4988 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  972): Killing 3355:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=3355
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/jxcore-log( 4698): getBuffer is called!!!!
I/jxcore-log( 4698): 
,I/ActivityManager(  972): Recipient 3355
,I/DeviceManagement( 4732): WorkflowService: Stopping workflow service
,I/SensorManager(  972): dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@223eb2e8
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4
,D/MediaScanner( 4363):  prescan time: 731ms
D/MediaScanner( 4363):     scan time: 1041ms
D/MediaScanner( 4363): postscan time: 153ms
D/MediaScanner( 4363):    total time: 1925ms
D/MediaScanner( 4363): -----------------------------------------------------------------
,D/MediaScanner( 4363): firstscan(media) time: 625ms
D/MediaScanner( 4363): secondscan(non-media) time: 416ms
D/MediaScanner( 4363):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0,
D/MediaScanner( 4363):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4363):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4363):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,I/ActivityManager(  972): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5009 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,V/AlarmManager(  972): sending alarm PendingIntent{1f52f700: PendingIntentRecord{27955b39 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60173, Int=0
,I/ActivityManager(  972): Killing 4301:com.android.managedprovisioning/u0a63 (adj 15): empty #17
,D/Process (  972): killProcessQuiet, pid=4301
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 4363): [delete][62]
D/MediaProvider( 4363): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 4363): [recoverParentNodes] - 0
,D/MediaProvider( 4363): [update][5]
D/MediaScannerServiceEx( 4363): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 4363): [updateImage]+
,D/MediaScannerServiceEx( 4363): [updateImage]-0
,I/ActivityManager(  972): Recipient 4301
,I/htcbackup-core( 4757): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
,D/PMS     (  972): releaseWL(2ce5669c): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 4363): [3] scan finished,
,V/AlarmManager(  972): sending alarm PendingIntent{1510cadf: PendingIntentRecord{1d70832c com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=4, w=1447326412457, Int=604800000,
,D/MediaProviderUtils( 4363): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 4363): calcVolumeId: /storage/ext_sd,
D/MediaProviderUtils( 4363): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4363): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 4363): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 4363): [disAliveExtStorageRows]+131073
,D/MediaProvider( 4363): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 4363): [update][26]#1#
,D/Process (  972): killProcessQuiet, pid=4448
I/ActivityManager(  972): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=5032 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  972): Killing 4448:com.htc.cs.pns/u0a71 (adj 15): empty #17
,D/MediaProvider( 4363): [update][30]#0#
,D/MediaScannerServiceEx( 4363): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  972): Recipient 4448
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.htc.backup 3 38
,I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145),
,I/RemoteViews( 1218): apply : com.htc.backup 1 3 0 5
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/ActivityManager(  972): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5054 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
I/RemoteViews( 1218): apply : com.htc.backup 1 3 0 5
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1218): apply : com.htc.backup 1 3 1 5
I/RemoteViews( 1218): reapply : com.htc.backup 19 50
D/MediaProviderUtils( 4363): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4363): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 4363): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4363): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 4363): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 4363): [disAliveExtStorageRows]+196609
,D/MediaProvider( 4363): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 4363): [update][7]#1#
,D/MediaProvider( 4363): [update][18]#0#
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155
E/WifiStateMachine(  972): processMsg: ConnectedState
,E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=7.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1871288105] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  972): processMsg: L2ConnectedState
,E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=7.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1871288106] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1400): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1400): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
,E/WifiStateMachine(  972): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.24 txretriesrate=0.00 rxrate=4.10 userTriggerdPenalty0
,E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  972):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -57, 3
,E/WifiStateMachine(  972): handleMessage: X
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/art     (  972): Explicit concurrent mark sweep GC freed 15073(798KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.449ms total 151.407ms
,D/MediaScannerServiceEx( 4363): [disAliveExtStorageRows]--1, 0
,D/MdScBoot( 5009): [6e7.1.] 30@-002716 -> 40
,D/MdScBootUi( 5009): [6e7.1.2.] boot 118
,D/MdScSimSt( 5009): [6e7.1.2.] qry 118: 0+1 running 0
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  972):  packet count Tx=106 Rx=136,
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5032, uid=10072, userID:0
E/WifiTrafficPoller(  972): notifying of data activity 1
D/WIFI_ICON( 1218): WifiActivity: 1
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/global  ( 5032): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5032): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 5032): [apache-http] Connection GC has been deprecated!
,I/ActivityManager(  972): Killing 4507:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4507
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/global  ( 5032): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5032): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  972): Recipient 4507
,I/ActivityManager(  972): Killing 4530:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4530
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 4530
,I/ActivityManager(  972): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5097 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5032): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5032): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 5097): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5097): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5032, uid=10072, userID:0
,I/MultiDex( 5097): VM with version 2.1.0 has multidex support,
I/MultiDex( 5097): install
I/MultiDex( 5097): VM has multidex support, MultiDex support library is disabled.
,D/Volley  ( 5032): [464] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 5032): [470] DiskBasedCache.clear: Cache cleared.
V/JNIHelp ( 5097): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 5032): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5032): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 5032): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityThread( 5097): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5097): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33691045: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5097): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 5032): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSUser ( 1934): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/Process (  972): killProcessQuiet, pid=4554
I/ActivityManager(  972): Killing 4554:com.htc.feedback/u0a83 (adj 15): empty #17
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 4554
,D/PMS     (  972): acquireWL(5310f5c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1934 10024 null
,V/GmsCoreStatsServiceLauncher( 4478): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PMS     (  972): releaseWL(5310f5c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/PersistentNotificationBroadcastReceiver( 1934): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) },
,W/InstanceID/Rpc( 4478): Found 10024
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  972):  packet count Tx=106 Rx=136
E/WifiTrafficPoller(  972): notifying of data activity 0
,D/WIFI_ICON( 1218): WifiActivity: 0
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/FileApkUtils( 4478): Spent 19ms computing apk sha1.,
D/FileApkUtils( 4478): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 4478): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4478): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4478): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,I/art     ( 1934): Explicit concurrent mark sweep GC freed 9386(507KB) AllocSpace objects, 5(292KB) LOS objects, 32% free, 4MB/6MB, paused 614us total 63.561ms
D/GmsModuleFndr( 4478): Beginning GMS chimera module scan
,V/Finsky  ( 5032): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,W/asset   ( 4478): Copying FileAsset 0x55a6076ad0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
,D/GmsModuleFndr( 4478): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping,
D/ChimeraCfgMgr( 4478): Beginning module configuration check
,D/ChimeraCfgMgr( 4478): Module APKs unchanged, check complete,
,D/PMS     (  972): acquireWL(14b09563): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4478 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(26e97ade): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4478 10024 null,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1934, uid=10024, userID:0
,D/PMS     (  972): acquireWL(1a8d24bf): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4478 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(14b09563): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(3a05078c): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4478 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(d794ddb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4478 10024 null
,D/GCM     ( 4478): COMPAT: Multi user not supported
,I/CheckinService( 4478): Disabling old GoogleServicesFramework version,
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4478, uid=10024, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4478, uid=10024, userID:0
,D/GCM     ( 1934): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/CheckinService( 4478): Checking schedule, now: 1449275268334 next: 1449812088962
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4478, uid=10024, userID:0
I/CheckinService( 4478): active receiver: disabled
,I/GCoreUlr( 4478): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}],
,D/PMS     (  972): acquireWL(2132bc24): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4478 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(26e97ade): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  972): releaseWL(2132bc24): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(3fc5438d): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4478, uid=10024, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
,D/SystemUpdateService( 4478): onCreate
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/ActivityManager(  972): Delay finish: com.google.android.gms/.tron.AlarmReceiver
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4478, uid=10024, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4478, uid=10024, userID:0
,D/SystemUpdateService( 4478): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/GCoreUlr( 1836): DispatchingService.onCreate()
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4478, uid=10024, userID:0
,I/ConfigService( 1934): onCreate
,I/ConfigFetchService( 4478): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/SystemUpdateService( 4478): cancelUpdate (empty URL)
I/SystemUpdateService( 4478): active receiver: disabled
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4478, uid=10024, userID:0
V/AuthZen ( 4478): Handling intent: android.intent.action.BOOT_COMPLETED
,D/PMS     (  972): acquireWL(93568f9): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
,D/AuthZenEventHandler( 4478): Handling event: android.intent.action.BOOT_COMPLETED
,D/PMS     (  972): acquireWL(25da9bb5): PARTIAL_WAKE_LOCK  Icing 0x1 4478 10024 WorkSource{10024 com.google.android.gms},
,I/GCoreUlr( 1836): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED,
,W/System.err(  972): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ebad5bb:true
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
,W/BaseAppContext( 4478): Using Auth Proxy for data requests.,
,D/PMS     (  972): releaseWL(25da9bb5): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(1a8d24bf): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/ConfigFetchService( 4478): service connected
,I/ActivityManager(  972): Resuming delayed broadcast
I/GLSUser ( 4478): [ChannelManager] Attempting to channel bind connection HttpClient.
,D/PMS     (  972): releaseWL(3a05078c): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4478): onDestroy
,I/GLSUser ( 4478): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true,
D/ChimeraCfgMgr( 4478): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/AuthZen ( 4478): Fetching signing key...,
,I/AuthZen ( 4478): Signing key fetched successfully!
,I/art     ( 1836): Explicit concurrent mark sweep GC freed 23323(1401KB) AllocSpace objects, 6(120KB) LOS objects, 46% free, 4MB/8MB, paused 4.405ms total 66.635ms,
W/BaseAppContext( 4478): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 4478): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PMS     (  972): releaseWL(3fc5438d): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms}
,I/AuthZen ( 4478): Starting Enrollment...
,D/ConfigFetchService( 4478): ConfigApi connection successful.
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1836, uid=10024, userID:0,
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=5194 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/AuthZen ( 4478): getting auth token. Attempt 0
,I/GLSActivity( 1934): [ac] getting account id
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1934): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227,
,I/GLSUser ( 1934): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1934): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1934): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1934): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ResourcesManager( 5194): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1934): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm,
I/GLSUser ( 1934): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1934): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1934): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1934): Explicit concurrent mark sweep GC freed 8462(469KB) AllocSpace objects, 2(40KB) LOS objects, 49% free, 4MB/8MB, paused 1.235ms total 39.013ms,
,I/GCoreUlr( 1836): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/PMS     (  972): acquireWL(37c9538b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1836 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  972): releaseWL(37c9538b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
E/AuthZen ( 4478): Error getting auth token
E/AuthZen ( 4478): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4478): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122),
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4478): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4478): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4478): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4478): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4478): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GCoreUlr( 1836): Unbound from all location providers
,D/PMS     (  972): releaseWL(93568f9): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
W/Kids    ( 4478): [AccountUtils] Account not ready
W/Kids    ( 4478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4478): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4478): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4478): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4478): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4478): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4478): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4478): 	at java.lang.Thread.run(Thread.java:818)
,I/RemoteViews( 1218): reapply : com.google.android.gms 1 40
,D/a       ( 4478): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4478): Initialized cache in: /data/data/com.google.android.gms/files
,D/PMS     (  972): acquireWL(af1c68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 972 1000 null
D/AuthZenTransactionCache( 4478): Clearing transaction cache
,I/GCoreUlr( 1836): DispatchingService.onDestroy()
,D/PMS     (  972): acquireWL(5a6f881): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(5a6f881): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(3c954d26): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 972 1000 WorkSource{10024}
,I/GCoreUlr( 1836): Unbound from all location providers
I/IntentController( 1218): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  972): releaseWL(af1c68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  972): acquireWL(21d6a903): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 972 1000 null
,D/PMS     (  972): releaseWL(21d6a903): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Babel_SMS( 5194): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5194): MmsConfig.loadMmsSettings
,D/PhoneStatusBar( 1218): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/MmsCustomizationProvider( 4413): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4413): query uri: content://htc-mms-customization/mms-ua/ua_profile
,W/art     ( 5194): No such thread id for suspend: 22,
,I/Babel_SMS( 5194): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 5194): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5194): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5194): MmsConfig.loadFromResources
,E/Babel_SMS( 5194): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5194): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5194, uid=10112, userID:0
,I/art     (  972): Explicit concurrent mark sweep GC freed 17642(961KB) AllocSpace objects, 6(184KB) LOS objects, 33% free, 16MB/24MB, paused 1.848ms total 150.047ms,
,D/PMS     (  972): acquireWL(3b9a357b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 972 1000 null
,D/PMS     (  972): releaseWL(3c954d26): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
,W/Settings( 5194): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  972): releaseWL(3b9a357b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/IntentController( 1218): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,I/Babel_Crash( 5194): startup - clean
,I/Babel   ( 5194): deleted: false for 0,
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5,
,E/WifiTrafficPoller(  972):  packet count Tx=106 Rx=136
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5194, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5194, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5194, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5194, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5194, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5194, uid=10112, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5194, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5194, uid=10112, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5194, uid=10112, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5194, uid=10112, userID:0
,W/VideoCapabilities( 5194): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5194): Unsupported mime video/x-ms-wmv
,W/Utils   ( 5194): could not parse size range '64x64-1920X1080',
,W/AudioCapabilities( 5194): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5194): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5194): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5194): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 5194): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 5194): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5194): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5194): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5194): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 5194): onServiceConnected
W/Babel   ( 5194): Attempted to change video mute state without an active call.
,I/ActivityManager(  972): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=5228 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  972): killProcessQuiet, pid=4579
,I/ActivityManager(  972): Killing 4579:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  972): Recipient 4579
,E/WifiDataStallTracker(  972): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=89 rxSum=79} preTxRxSum={txSum=89 rxSum=79}
D/WifiDataStallTracker(  972): updateDataStallInfo: NONE
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/ResourcesManager( 5228): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5228): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5228): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/ActivityManager(  972): Waited long enough for: ServiceRecord{9a358d7 u0 com.htc.autobot/.htcmodeclient.HtcModeService},
,W/System  ( 5228): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5228): Installed default security provider GmsCore_OpenSSL
,W/art     ( 5228): Suspending all threads took: 5.720ms
,W/ResourcesManager( 5228): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5228): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,I/HtcModeClient( 3731): handler message = 4011,
E/HtcModeClient( 3731): Check connection and retry 3 times.
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155,
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1871291127] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1871291129] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0,
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1400): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1400): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  972): updateConfiguration freq=2462 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
,E/WifiStateMachine(  972): calculateWifiScore freq=2462 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.12 txretriesrate=0.00 rxrate=2.55 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
,E/WifiStateMachine(  972):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  972): RSSI current: 3 new: -57, 3
E/WifiStateMachine(  972): handleMessage: X
,D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/cutils-trace( 5260): Error opening trace file: Permission denied (13)
I/dex2oat ( 5260): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2035322571.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads-2035322571.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
I/dex2oat ( 5260): dex2oat: override thread count:4
,I/SocialFeedProvider( 1506): +disConnect socialManager,
I/SocialFeedProvider( 1506): disconnect socialManager,
I/SocialFeedProvider( 1506): -disConnect socialManager
,I/dex2oat ( 5260): dex2oat took 39.207ms (threads: 4),
,E/YouTube MDX( 5228): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,D/libc    ( 5228): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
D/libc    ( 5228): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  972): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 5228): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  972):  packet count Tx=106 Rx=137
E/WifiTrafficPoller(  972): notifying of data activity 1
,D/WIFI_ICON( 1218): WifiActivity: 1
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/VoldConnector(  972): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 5228): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  972): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 5228): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  972): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 5228): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 5228): Found 10024,
,D/VoldConnector(  972): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
W/ContextImpl( 5228): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  972): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=5308 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/libc    ( 5228): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 5228): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5228): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5228): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5228): [NET] android_getaddrinfo_proxy+
D/libc    ( 5228): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/Process (  972): killProcessQuiet, pid=4615
I/ActivityManager(  972): Killing 4615:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5228): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 5228): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 5228): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  972): Recipient 4615,
,D/libc    ( 5228): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5228): [NET] android_getaddrinfofornet-, err=8
,D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  972): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2a6337fb mBinding = false
W/Settings:Agent(  972): MONITOR_LOG
W/Settings:Agent(  972): name: bluetooth_on
W/Settings:Agent(  972): value: 0
W/Settings:Agent(  972): >> traceCallingStack()
W/Settings:Agent(  972): Process.myPid(): 972
W/Settings:Agent(  972): Process.myTid(): 1769
W/Settings:Agent(  972): Process.myUid(): 1000
,W/Settings:Agent(  972): 
W/Settings:Agent(  972): 
W/System.err(  972): java.lang.Throwable: stack dump
,W/System.err(  972): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  972): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  972): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  972): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  972): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  972): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  972): 
W/Settings:Agent(  972): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  972): Message: MESSAGE_DISABLE,
,D/BluetoothManagerService(  972): Sending off request.
,D/BluetoothAdapterState( 3628): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3628): Setting state to 13
I/BluetoothAdapterState( 3628): Bluetooth adapter state changed: 12-> 13,
D/PMS     (  972): acquireWL(3d3c8927): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3628 1002 null
D/BluetoothManagerService(  972): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 3628): onBluetoothDisable()
I/BluetoothAdapterState( 3628): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiService(  972): New client listening to asynchronous messages
I/bt-btif ( 3628): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3628): BTM_SetDiscoverability
I/bt-btm  ( 3628): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
,D/bt-btm  ( 3628): disc_mode 0000
I/bt-btm  ( 3628): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3628): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/WifiService(  972): setWifiEnabled: false pid=4698, uid=10373
D/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
E/WifiService(  972): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService(  972): Bluetooth State Change Intent: 12 -> 13
I/WifiService(  972): isSprintWifiRestricted(): false
D/WifiManager( 4698): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
I/WifiService(  972): isMdmWifiRestricted(): false
D/BluetoothAdapterProperties( 3628): Scan Mode:21
D/BluetoothAdapterState( 3628): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btm  ( 3628): BTM_SetConnectability
I/bt-btm  ( 3628): btm_ble_set_connectability mode=0x0 combined_mode=0x1
,D/bt-btm  ( 3628): disc_mode 0000
I/bt-btm  ( 3628): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3628): BTA_JvDeleteRecord
I/bt-btif ( 3628): BTA_JvRfcommStopServer
D/bt-btm  ( 3628): BTM_FreeSCN 
I/bt-btif ( 3628): BTA_JvDeleteRecord
I/bt-btif ( 3628): BTA_JvRfcommStopServer
D/bt-btm  ( 3628): BTM_FreeSCN 
I/bt-btif ( 3628): BTA_JvDeleteRecord
I/bt-btif ( 3628): BTA_JvRfcommStopServer
,D/bt-btm  ( 3628): BTM_FreeSCN 
I/bt-btif ( 3628): BTA_JvDeleteRecord
I/bt-btif ( 3628): BTA_JvRfcommStopServer
D/bt-btm  ( 3628): BTM_FreeSCN 
I/bt-btif ( 3628): BTA_JvDeleteRecord
I/bt-btif ( 3628): BTA_JvRfcommStopServer
D/bt-btm  ( 3628): BTM_FreeSCN 
I/bt-btif ( 3628): BTA_JvDeleteRecord
I/bt-btif ( 3628): BTA_JvRfcommStopServer
D/bt-btm  ( 3628): BTM_FreeSCN 
E/bt-btif ( 3628): cmd socket is not created
V/BluetoothSapService( 3628): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/WifiTrafficPoller(  972): ADD_CLIENT: 6
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:14
I/bt-btm  ( 3628): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3628): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3628): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3628): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3628): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3628): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3628): Write Extended Inquiry Response to controller
I/bt-btm  ( 3628): Write Extended Inquiry Response to controller
I/bt-btm  ( 3628): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3628): Write Extended Inquiry Response to controller
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3628): BTM_SetDiscoverability
I/bt-btm  ( 3628): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3628): disc_mode 0000
I/bt-btm  ( 3628): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3628): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3628): BTM_SetConnectability
I/bt-btm  ( 3628): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3628): disc_mode 0000
D/bt-btm  ( 3628): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3628): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3628): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
,I/bt-btm  ( 3628): BTM_IsInquiryActive
I/bt-btm  ( 3628): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3628): btm_ble_clear_white_list
W/bt-btif ( 3628): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
I/IntentController( 1218): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 4250): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
W/Settings:Agent(  972): MONITOR_LOG
W/Settings:Agent(  972): name: wifi_on
W/Settings:Agent(  972): value: 0
W/Settings:Agent(  972): >> traceCallingStack()
W/Settings:Agent(  972): Process.myPid(): 972
W/Settings:Agent(  972): Process.myTid(): 1703
W/Settings:Agent(  972): Process.myUid(): 1000
W/Settings:Agent(  972): 
W/Settings:Agent(  972): 
E/BtOppRfcommListener( 3628): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/System.err(  972): java.lang.Throwable: stack dump
,D/bt-btif ( 3628): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3628): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3628): BTM_FreeSCN 
I/bt-btm  ( 3628): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3628): BTM_FreeSCN 
I/bt-btm  ( 3628): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3628): AVRC_Close handle:0
D/bt-btif ( 3628): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, : event=BTA_AG_DISABLE_EVT
D/bt-btif ( 3628): SDP_DeleteRecord ok, : event=BTA_AG_DISABLE_EVT
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3628): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3628): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3628): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3628): GATT_Deregister gatt_if=3
I/bt-att  ( 3628): GATT_Listen gatt_if=3
I/bt-btm  ( 3628): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3628): BTM_ReadConnectability
I/bt-btm  ( 3628): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3628): disc_mode 0000
I/bt-att  ( 3628): GATT_Deregister gatt_if=4
I/bt-att  ( 3628): GATT_Listen gatt_if=4
I/bt-btm  ( 3628): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3628): BTM_ReadConnectability
I/bt-btm  ( 3628): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3628): disc_mode 0000
E/bt-btif ( 3628): bta_gattc_deregister Deregister Failedm unknown client cif
,I/bt-btm  ( 3628): btm_ble_clear_white_list_complete
,W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  972): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,W/System.err(  972): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  972): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  972): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  972): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  972): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  972): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  972): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  972): 
W/Settings:Agent(  972): << traceCallingStack(): 23(ms)
,V/BluetoothPbapReceiver( 3628): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3628): ***********state = 13
,I/BtOppRfcommListener( 3628): stopping Accept Thread
,I/BtOppRfcommListener( 3628): BluetoothSocket listen thread finished
,V/BluetoothPbapService( 3628): Pbap Service closeService in
,V/BluetoothPbapService( 3628): successfully stopped pbap service
V/BluetoothPbapService( 3628): Pbap Service closeService out
,V/BluetoothPbapService( 3628): Pbap Service onDestroy
V/BluetoothPbapService( 3628): Pbap Service closeService in
V/BluetoothPbapService( 3628): Pbap Service closeService out
,D/PMS     (  972): acquireWL(3fba77d4): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4895 1000 null
W/ContextImpl( 4895): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/WifiController(  972): handleMessage: E msg.what=155656
,D/WifiController(  972): processMsg: DeviceActiveState
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
D/WifiController(  972): processMsg: StaEnabledState
,D/WifiController(  972): transitionTo: destState=ApStaDisabledState
D/WifiController(  972): handleMessage: new destination call exit/enter
D/WifiController(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  972): invokeExitMethods: DeviceActiveState
D/WifiController(  972): invokeExitMethods: StaEnabledState
D/WifiController(  972): moveTempStackToStateStack: i=0,j=1
D/WifiController(  972): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  972): invokeEnterMethods: ApStaDisabledState
I/QuickSettingBluetooth( 1218): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/WifiController(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=131084
E/WifiStateMachine(  972): processMsg: ConnectedState
I/jxcore-log( 4698): ****TEST TOOK:  5201  ms ****
I/jxcore-log( 4698): 
E/WifiStateMachine(  972):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
I/jxcore-log( 4698): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4698): 
E/WifiStateMachine(  972):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  972): processMsg: DriverStartedState
E/WifiStateMachine(  972):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  972): processMsg: SupplicantStartedState
E/WifiStateMachine(  972):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  972): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  972): invokeExitMethods: ConnectedState
E/WifiStateMachine(  972): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  972): release()
E/WifiStateMachine(  972): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  972): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  972): invokeExitMethods: L2ConnectedState
,D/PMS     (  972): releaseWL(3fba77d4): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  972): acquireWL(1f94c472): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4895 1000 null
E/WifiStateMachine(  972): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  972): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  972): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1400): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1400): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1400): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1400): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1400): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1400): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1400): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  972): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1400): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1400): Power_Mode_Type mode = 0
I/wpa_supplicant( 1400): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1400): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  972): setDhcpActive: false
D/WifiP2pService(  972): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1934): Read error: ssl=0x55a6111f40: I/O error during system call, Connection timed out
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/PMS     (  972): acquireWL(1366b5be): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1934 10024 WorkSource{10024 com.google.android.gms}
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2720c479:true
E/WifiStateMachine(  972): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  972): setDetailed state send new extra info<unknown ssid>
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/System.err(  972): java.lang.Throwable: stack dump
V/NativeCrypto( 1934): SSL shutdown failed: ssl=0x55a6111f40: I/O error during system call, Broken pipe
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
I/ActivityManager(  972): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5336 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,E/WifiStateMachine(  972): NetworkAgent != null
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL true Token 11
V/NetworkPolicy(  972): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  972):  packet count Tx=119 Rx=149
E/WifiTrafficPoller(  972): notifying of data activity 3
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WIFI_ICON( 1218): WifiActivity: 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  972): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  972): stopDataStallAlarm 
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  972): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiStateMachine(  972): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1400): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1400): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1400): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 13
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1400): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1400): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1400): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1400): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  972): invokeExitMethods: ConnectModeState
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  972): invokeExitMethods: DriverStartedState
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1400): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  972): Unexpected BatchedScanResults :null
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1400): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  972): noteBatchedScanstop()
E/WifiStateMachine(  972): [1,449,275,270,873 ms] noteScanEnd no scan source
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiP2pService(  972): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  972): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService(  972): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  972): SCAN_AVAILABLE : 1
,E/WifiStateMachine(  972): handleMessage: X
D/WifiNetworkAgent(  972): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService(  972): P2pDisablingState
D/RttService(  972): SCAN_AVAILABLE : 1
D/RttService(  972): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  972): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@3a4e1673
D/WifiDisplayController(  972): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiScanningService(  972): DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
D/ConnectivityService(  972): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  972): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
V/AudioService(  972): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  972):     Client/Owner: Client
V/AudioService(  972):     GroupId: 
V/AudioService(  972):     Passphrase: 
V/AudioService(  972):     SessionId: 0
V/AudioService(  972):     IP Address: }
D/WifiP2pService(  972): p2p socket connection lost
D/HtcEffectManagerBase(  972): onEventChanged id=5 status=false
D/WifiP2pService(  972): P2pDisabledState
D/HtcEffectManager(  972): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  972): convertEffect before=902
D/HtcEffectManager(  972): convertEffect after=902
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  972): handleMessage: E msg.what=131205
E/WifiStateMachine(  972): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  972):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  972): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  972): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  972): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  972): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  972): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
D/WifiP2pService(  972): P2pDisabledState{ when=-2ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  972): DefaultState{ when=-2ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  972): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/PMS     (  972): releaseWL(1366b5be): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/BluetoothAdapter( 4895): 603545738: getState(). Returning 13
D/wpa_supplicant( 1400): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1400): Power_Mode_Type mode = 0
I/wpa_supplicant( 1400): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1400): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/WifiP2pService(  972): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiP2pService(  972): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  972): setDhcpActive: false
D/BluetoothInputDevice( 4895): BluetoothInputDevice()
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 9
E/WifiStateMachine(  972): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  972): stopping supplicant
W/WifiHW  (  972): QCOM Debug wifi_send_command "TERMINATE"
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/wpa_supplicant( 1400): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 1400): wlan0: Removing interface wlan0
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  972): setWifiState: disabling
E/WifiStateMachine(  972): handleMessage: X
D/wpa_supplicant( 1400): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1400): TDLS: Tear down peers
D/wpa_supplicant( 1400): wpa_driver_nl80211_disconnect(reason_code=3)
I/IntentController( 1218): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Validated
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1218): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothPan( 4895): BluetoothPan()
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 10
,D/BluetoothMap( 4895): Create BluetoothMap proxy object
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 11
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,D/HtcBtWidget_BTWidgetProvider( 5336): onBTStateChanged() for widget: 
E/BluetoothMap( 4895): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/HtcBtWidget_BTWidgetProvider( 5336): updateWidget(context) for widget: 
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/wpa_supplicant( 1400): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1400): wlan0: Deauthentication notification
D/wpa_supplicant( 1400): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1400): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1400): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1400): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
,E/wpa_supplicant( 1400): enter disconnect check
I/wpa_supplicant( 1400): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  972): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/BluetoothSap( 4895): BluetoothSap() call bindService
D/HTCRequest(  972): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/WifiMonitor(  972): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,E/WifiStateMachine(  972): handleMessage: E msg.what=147460
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
D/wpa_supplicant( 1400): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1400): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  972):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=64668
D/BluetoothManagerService(  972): Registered receivers: 12
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=64669
E/WifiStateMachine(  972): handleMessage: X
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1400): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1400): wlan0: Disconnect event - remove keys
D/Tethering(  972): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  972): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  972): TetherInterfaceSM: wlan0: enter UnavailableState
D/wpa_supplicant( 1400): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1400): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbDeviceManager(  972): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1400): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x557fa1df88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/PMS     (  972): acquireWL(2dae7670): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
D/wpa_supplicant( 1400):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1400): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1400): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1400): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
D/wpa_supplicant( 1400): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1400): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1400): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1400): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1400): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1400): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1400): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1400): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 1400): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1400): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1400): EAPOL: External notification - portEnabled=0
D/Tethering(  972): sendTetherStateChangedBroadcast 0, 0, 0
D/wpa_supplicant( 1400): EAPOL: External notification - portValid=0
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/UsbnetService(  972): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  972): handleMessage: E msg.what=131101
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
E/WifiStateMachine(  972):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  972): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
E/WifiStateMachine(  972):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=64675  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=64675  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  972): handleMessage: X
,D/BluetoothFtpService( 3628): ACTION_STATE_CHANGED: state: 13mHasStarted: true
E/BluetoothFtpService:RfcommSocketAcceptThread( 3628): Shutdown
,W/ContextImpl( 4895): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothMasReceiver( 3628): Bluetooth STATE CHANGED to 13
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
D/BluetoothPbap( 4895): BluetoothPbap()
D/BluetoothManagerService(  972): registerStateChangeCallback+
,V/BluetoothSapReceiver( 3628): SapReceiver onReceive 
V/BluetoothSapReceiver( 3628): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3628):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3628): startService = false
,D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  972): Registered receivers: 13
I/QuickSettingWifi( 1218): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
,D/AuthorizationBluetoothService( 1934): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LocalBluetoothProfileManager( 4895): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4895): finishStartingService: stopping service
,D/BluetoothInputDevice( 4895): Proxy object connected
,D/WISPrService( 4895): >>>>>WISPrService start isConnected = true<<<<<
,D/HidProfile( 4895): Bluetooth service connected,
,E/WifiTrafficPoller(  972): ADD_CLIENT: 7
D/WifiService(  972): New client listening to asynchronous messages
D/BluetoothAdapter( 4895): 603545738: getState(). Returning 13
D/PMS     (  972): releaseWL(1f94c472): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothPan( 4895): BluetoothPAN Proxy object connected
D/PanProfile( 4895): Bluetooth service connected
E/WifiStateMachine(  972): handleMessage: E msg.what=131131
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
D/SapServerProfile( 4895): Bluetooth service connected
E/WifiStateMachine(  972):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): handleMessage: X
,D/bt-btm  ( 3628): BTM_BleGetVendorCapabilities
,W/bt-btif ( 3628): ag scb idx 1 not allocated
W/bt-btif ( 3628): ag scb idx 2 not allocated
E/bt-btif ( 3628): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3628): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3628): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3628): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3628): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3628): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3628): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3628): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3628): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3628): pthread_join() FAILED result:3
D/WISPrService( 4895): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4895): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4895): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4895): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4895): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4895): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/ActivityManager(  972): Killing 4670:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4670
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/ConnectivityService(  972): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  972): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Disconnected - quitting
D/NetworkManagementService(  972): Removing idletimer
D/usbnet  (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/PMS     (  972): acquireWL(13505f7a): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 972 1000 null
D/usbnet  (  972):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/usbnet  (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  972): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false,
I/SecurityController( 1218): onLost 100
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
D/WIFI    (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released,
E/WifiStateMachine(  972): enter WifiNetworkFactory startNetwork. mIPTStart:false
I/Gmail   ( 5308): getAccountsCursor
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5308, uid=10106, userID:0
,I/ActivityManager(  972): Recipient 4670
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL false Token 15 num clients 7,
,D/Tethering(  972): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  972): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  972): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/ConnectivityService(  972): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
V/NetworkPolicy(  972): ensureActiveMobilePolicyLocked()
,E/WifiStateMachine(  972): handleMessage: E msg.what=196614
D/PMS     (  972): releaseWL(2dae7670): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
D/PMS     (  972): acquireWL(3876a388): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
E/WifiStateMachine(  972):  SupplicantStoppingState !CMD_ON_QUIT 0 0
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/WifiStateMachine(  972): processMsg: DefaultState
D/PMS     (  972): releaseWL(3d3c8927): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
E/WifiStateMachine(  972):  DefaultState !CMD_ON_QUIT 0 0
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
E/WifiStateMachine(  972): handleMessage: X
D/NetworkPolicy(  972): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NetworkPolicy(  972): updateIfacesLocked()
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  972): updateNotificationsLocked()
W/ActivityManager(  972): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/PMS     (  972): releaseWL(3876a388): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
D/NetworkManagementService(  972): isBandwidthControlEnabled: doneSignal.getCount()= 0
,V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,I/Gmail   ( 5308): Observing account changes for notifications
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/wpa_supplicant( 1400): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1400): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1400): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush
D/wpa_supplicant( 1400): wlan0: BSS: Remove id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1400): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1400): wlan0: Cancelling scan request
D/wpa_supplicant( 1400): wlan0: Cancelling authentication timeout
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
E/wpa_supplicant( 1400): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  972): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5308, uid=10106, userID:0
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=27 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c0:ff:d4:d3:aa:48
D/WifiMonitor(  972): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=31 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5308, uid=10106, userID:0
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/wpa_supplicant( 1400): Remove interface wlan0 from radio phy0
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,W/GAV2    ( 5308): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs,
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/MdScPhnSt( 5009): [7d7.2.]  listen tmrbb8
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/cutils-trace( 5357): Error opening trace file: Permission denied (13)
,D/wpa_supplicant( 1400): nl80211: Remove monitor interface: refcount=0
,D/wpa_supplicant( 1400): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
,E/Gmail   ( 5308): Error finding the version of the Email provider.....
E/Gmail   ( 5308): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5308): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5308): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5308): 	,at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5308): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5308): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5308): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5308): We do not support migrating this version of the Email provider.
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=5308, uid=10106, userID:0,
,I/Gmail   ( 5308): getAccountsCursor
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=5308, uid=10106, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=5308, uid=10106, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=5308, uid=10106, userID:0
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/MdProvGlob( 5054): remove item 101 (p2d15in95) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 5009): [7d7.2.] summary 118:p2 ignore
,I/ActivityManager(  972): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=5405 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/MdProvGlob( 5054): remove item 101 (p2in13) for 15:android.intent.action.ANY_DATA_STATE
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5308, uid=10106, userID:0
V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5308, uid=10106, userID:0
,D/CustomizationManager( 5357): ====startRecUseTime====
D/htc.customization.log.level( 5357):  is 
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/CustomizationLogLevel( 5357): Level value is invalid, use default level 2
,E/ActivityThread( 5308): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1090eedb that was originally bound here
E/ActivityThread( 5308): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1090eedb that was originally bound here
E/ActivityThread( 5308): 	,at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 5308): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 5308): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 5308): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889),
E/ActivityThread( 5308): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5308): 	at com.android.emailcommon.service.ak.a(SourceFile:181),
E/ActivityThread( 5308): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 5308): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 5308): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 5308): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 5308): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 5308): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 5308): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 5308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5308): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 5308): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  972): Unbind failed: could not find connection for android.os.BinderProxy@3fdd56ef
,I/bt-btif ( 3628): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 3628): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterService( 3628): mProfilesStarted : true supportedProfileServices.length : 6
,D/HeadsetService( 3628): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca56400
,D/HeadsetStateMachine( 3628): Exit Disconnected: -1
D/BluetoothAdapterState( 3628): Stopping profile services that were post enabled
D/BluetoothHeadset( 1439): Proxy object disconnected
D/BluetoothPhoneService( 1439): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1439): Proxy object disconnected
D/BluetoothHeadset( 1439): Proxy object disconnected
D/BluetoothHeadset(  972): Proxy object disconnected
D/BluetoothHeadset( 4250): Proxy object disconnected
D/NGFService( 4250): BluetoothHeadset onServiceDisconnected: main
D/A2dpService( 3628): Received stop request...Stopping profile...
D/BluetoothHeadset( 1218): Proxy object disconnected
I/QuickSettingMiniLite( 1218): btListener.disconnect:HEADSET
D/A2dpStateMachine( 3628): Exit Disconnected: -1
D/BluetoothAdapterService( 3628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca56400
,D/BluetoothA2dp( 4250): Proxy object disconnected
,D/NGFService( 4250): BluetoothA2dp onServiceDisconnected: main
D/BluetoothA2dp(  972): Proxy object disconnected
D/HidService( 3628): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca56400
,D/BluetoothInputDevice( 4895): Proxy object disconnected
D/HidProfile( 4895): Bluetooth service disconnected
D/HealthService( 3628): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca56400
,D/PanService( 3628): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca56400
D/BtGatt.DebugUtils( 3628): handleDebugAction() action=null,
D/BluetoothPan( 4895): BluetoothPAN Proxy object disconnected
D/BtGatt.GattService( 3628): Received stop request...Stopping profile...
D/PanProfile( 4895): Bluetooth service disconnected
D/BtGatt.GattService( 3628): stop()
D/BtGatt.AdvertiseManager( 3628): advertise clients cleared
,D/BluetoothAdapterService( 3628): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca56400
,W/BluetoothHeadsetServiceJni( 3628): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3628): Cleaning up Bluetooth Handsfree callback object
D/wpa_supplicant( 1400): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1400): nl80211: Unsubscribe mgmt frames handle 0x888888ddf7297989 (mode change)
,I/wpa_supplicant( 1400): htc_wext_command_deinit +
I/wpa_supplicant( 1400): htc_wext_command_deinit -
I/wpa_supplicant( 1400): wlan0: CTRL-EVENT-TERMINATING 
,D/wpa_supplicant( 1400): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1400): p2p0: Removing interface p2p0
D/wpa_supplicant( 1400): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1400): TDLS: Tear down peers
D/wpa_supplicant( 1400): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1400): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1400): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1400): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1400): EAPOL: External notification - portValid=0
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  972): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  972): handleMessage: E msg.what=147458
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
W/BluetoothHidServiceJni( 3628): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3628): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3628): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3628): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3628): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3628): Cleaning up Bluetooth PAN callback object
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
E/WifiStateMachine(  972):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 32 0
E/WifiStateMachine(  972): Supplicant connection lost
D/BluetoothAdapterState( 3628): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3628): Setting state to 10
I/BluetoothAdapterState( 3628): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  972): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 3628): Entering OffState
D/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  972): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothHeadset( 1439): onBluetoothStateChange: up=false
E/SQLiteLog( 5308): (283) recovered 567 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/BluetoothInputDevice( 4895): onBluetoothStateChange: up=false
,D/BluetoothMap( 4895): onBluetoothStateChange: up=false
,E/BluetoothMap( 4895): 
E/BluetoothMap( 4895): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@1a001f2e
E/BluetoothMap( 4895): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 4895): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 4895): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 4895): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 4895): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 4895): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=false
D/BluetoothPan( 4895): onBluetoothStateChange on: false
,D/BluetoothA2dp( 4250): onBluetoothStateChange: up=false
,D/BluetoothSap( 4895): onBluetoothStateChange on: false
V/BluetoothSapService( 3628): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@1eb768bc
,D/BluetoothHeadset( 1439): onBluetoothStateChange: up=false
,D/CustomizationManager( 5357):  Read ACC file spent 0.043 (s)
,D/CIDMapFileReader( 5357): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 5357): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5357): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5357): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5357): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5357): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5357): Parsing tag item name = HTC__031
,D/BluetoothPbap( 4895): onBluetoothStateChange: up=false
V/CustomizationCIDLoader( 5357): full path : /system/customize/CID/HTC__102.xml
D/MdProvGlob( 5054): remove item 101 (p2d7in111) for 15:android.intent.action.ANY_DATA_STATE
,D/BluetoothHeadset( 4250): onBluetoothStateChange: up=false
I/CustomizationCIDLoader( 5357): Parsing tag category name = system
,D/BluetoothHeadset(  972): onBluetoothStateChange: up=false
I/CustomizationCIDLoader( 5357): Parsing tag category name = application
,D/BluetoothHeadset( 1439): onBluetoothStateChange: up=false
,I/CustomizationCIDLoader( 5357): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5357): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5357): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5357): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5357): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5357): add string-array item, value = 42507
I/CustomizationCIDLoader( 5357): add string-array item, value = 21902
I/CustomizationCIDLoader( 5357): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5357): add string-array item, value = 23420
I/CustomizationCIDLoader( 5357): add string-array item, value = 22299
I/CustomizationCIDLoader( 5357): add string-array item, value = 24002
I/CustomizationCIDLoader( 5357): add string-array item, value = 23210
I/CustomizationCIDLoader( 5357): add string-array item, value = 23205
I/CustomizationCIDLoader( 5357): add string-array item, value = 23806
I/CustomizationCIDLoader( 5357): add string-array item, value = 23430
I/CustomizationCIDLoader( 5357): add string-array item, value = 23408
I/CustomizationCIDLoader( 5357): add string-array item, value = 27205
I/CustomizationCIDLoader( 5357): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5357): add string-array item, value = 27205:C:1:0
,D/BluetoothA2dp(  972): onBluetoothStateChange: up=false
D/CustomizationManager( 5357):  Read CID file spent 0.098 (s)
D/CustomizationManager( 5357):  All configurations done spent 0.098 (s)
D/BluetoothManagerService(  972): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  972): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 2387): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3d6f540b
D/BluetoothAdapter( 2387): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1460): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@176b03ad
D/BluetoothAdapter( 1460): onBluetoothServiceDown: done
D/BluetoothAdapter( 1836): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3e431690
D/BluetoothAdapter( 1836): onBluetoothServiceDown: done
D/BluetoothAdapter( 4250): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@27612da9
D/BluetoothAdapter( 4250): onBluetoothServiceDown: done
D/BluetoothAdapter( 1439): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@23ef9560
D/BluetoothAdapter( 1439): onBluetoothServiceDown: done
D/BluetoothAdapter( 4698): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@a95b894
D/BluetoothAdapter( 4698): onBluetoothServiceDown: done
D/BluetoothAdapter(  972): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2a6337fb
D/BluetoothAdapter(  972): onBluetoothServiceDown: done
,D/BluetoothAdapter( 4895): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@27217acf
D/BluetoothAdapter( 4895): onBluetoothServiceDown: done
D/BluetoothAdapter( 3628): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@1fcc02c
D/BluetoothAdapter( 3628): onBluetoothServiceDown: done
D/BluetoothAdapter( 1218): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@cf4232b
D/BluetoothAdapter( 1218): onBluetoothServiceDown: done
,D/BluetoothManagerService(  972): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2a6337fb mBinding = false
D/BluetoothManagerService(  972): Sending unbind request.
,D/BluetoothManagerService(  972): Bluetooth State Change Intent: 13 -> 10
D/NfcHandover( 1460): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,I/IntentController( 1218): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/LocalBluetoothProfileManager( 4895): setBluetoothStateOff
D/NGFService( 4250): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
W/BluetoothEventManager( 4895): unregister mProfileBroadcastReceiver fail
D/NGFService( 4250): Bluetooth Adapter: OFF
,I/bt-btif ( 3628): HAL bt_hal_cbacks->thread_evt_cb
,D/MdProvGlob( 5054): remove item 101 (p2d2in34) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 5009): [7d7.e.] summary 118:p1 ignore
,D/TetherPref( 4895): persistRestoreBluetoothState false,
I/art     ( 3628): System.exit called, status: 0
,W/BluetoothHeadset( 1218): Proxy not attached to service
,I/QuickSettingMiniLite( 1218): updateLiteState:no connect device!
,D/PackageManager(  972): deletePackageAsUser: pkg=com.example.hello, pid=5357, uid=2000 userid=0
,D/BluetoothAdapter( 1218): 729225680: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1218): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,I/Gmail   ( 5308): notifyAccountChanged,
,I/Gmail   ( 5308): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5308): getAccountsCursor
,V/AlarmManager(  972): sending alarm PendingIntent{d9505fc: PendingIntentRecord{d2e8485 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=62817, Int=259200000
,I/Gmail   ( 5308): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  972): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5437 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a,
V/AlarmManager(  972): sending alarm PendingIntent{1dd2730b: PendingIntentRecord{172a85e8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449275271475, Int=0
,I/ActivityManager(  972): Recipient 3628,
,W/PackageSettings(  972): Skipping PackageSetting{2933c13a com.test.thalitest/10366} due to missing metadata,
,D/PMS     (  972): acquireWL(b57e401): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5308 10106 null
I/ActivityManager(  972): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,D/Process (  972): killProcessQuiet, pid=4698
I/ActivityManager(  972): Killing 4698:com.example.hello/u0a373 (adj 0): stop com.example.hello
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,D/PMS     (  972): acquireWL(375dbf3d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end
I/Gmail   ( 5308): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  972): releaseWL(375dbf3d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/Gmail   ( 5308): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  972): Recipient 4698
I/WindowState(  972): WIN DEATH: Window{627801e u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  972): Client connection lost with reason: 4
E/InputEventReceiver( 1364): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1d0ee0ff uid 10373 pid 4698} (c)'
,I/wpa_ctrl(  972): [wpa_ctrl_close] ctrl=0x55a6229b80,
,I/wpa_ctrl(  972): [wpa_ctrl_close] ctrl=0x55a6229c70
W/ActivityManager(  972): Force removing ActivityRecord{1d416dd3 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/art     (  972): Explicit concurrent mark sweep GC freed 32971(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 16MB/25MB, paused 2.532ms total 165.301ms,
I/ActivityManager(  972): Force stopping com.example.hello appid=10373 user=0: pkg removed
,E/AndroidHttpClient( 5032): Leak found
E/AndroidHttpClient( 5032): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5032): 	,at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5032): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5032): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5032): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5032): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5032): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5032): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5032): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5032): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5032): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5032): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5032): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5032): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5032): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5032): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5032): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/ActivityManager(  972): Spurious death for ProcessRecord{3f23e62c 4698:com.example.hello/u0a373}, curProc for 4698: null
,E/WifiStateMachine(  972): setWifiState: disabled
D/WifiStateMachine(  972): Enter handleNetworkDisconnect
E/WifiStateMachine(  972): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
I/ActivityManager(  972): Process com.android.bluetooth (pid 3628) has died
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
,I/BroadcastQueue(  972): Schedule to resend BroadcastRecord{17a0cf71 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=972 callingUid=1000} for ResolveInfo{3112f156 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
E/WifiStateMachine(  972): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/LocationManagerService(  972): getProviders()=[passive]
,I/Gmail   ( 5308): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  972): acquireWL(291d25d7): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 972 1000 null
D/WifiStateMachine(  972): Exit handleNetworkDisconnect
E/WifiStateMachine(  972): [MLHD] Error! unhandled message 6 { when=-480ms what=147458 arg1=32 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  972): transitionTo: destState=InitialState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  972): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  972): invokeEnterMethods: InitialState
,I/FeedHostManager( 1506): [onResume]
I/FeedProviderManager( 1506): onResume
I/ConnectivityHelper( 1506): [getCurrentConnectionType] no network connection
I/SocialFeedProvider( 1506): +onResume
I/SocialFeedProvider( 1506): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1506): -onResume
,D/DotMatrix( 1309): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/PMS     (  972): acquireWL(b57e401): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5308 10106 null
D/DotMatrix( 1309): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): closing low battery warning: level=97
I/IntentController( 1218): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,W/Settings( 5194): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  972): acquireWL(170f8cf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1836 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/SystemReader(  972): Cannot find grip_rejection_width, use default value instead,
W/GeofencerStateMachine( 1836): Ignoring removeGeofence because network location is disabled.
D/WIFI_ICON( 1218): updateWifiState: WIFI_STATE_CHANGED disabled
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/Settings( 1836): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/AccTypeManager( 1705): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  972): releaseWL(170f8cf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/HtcPowerSaver(  972): updateBatteryInfo
,W/ResourcesManager( 1439): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AccTypeManager( 1705): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/InputMethodManagerService(  972): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/ActivityManager(  972): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5462 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
I/Gmail   ( 5308): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/WISPrService( 4895): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4895): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/PMS     (  972): acquireWL(b57e401): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 5308 10106 null
,D/AccTypeManager( 1705): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/StatusBarManagerService(  972): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,I/BatteryController( 1218): status:2 level:97 unsupport:false plugged:true
,I/QuickSettingWifi( 1218): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
D/FindExtension( 1506): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/Gmail   ( 5308): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,I/ThreadedRenderer( 1506): Defer allocateBuffers to drawing time
I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=5308, uid=10106, userID:0
,W/InputMethodManagerService(  972): Got RemoteException sending setActive(false) notification to pid 4698 uid 10373
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  972): Enable input method client, pid=1506
,E/ExternalAccountType( 1705): Unsupported attribute readOnly
W/ResourcesManager(  972): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneApp( 1439): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,W/ResourcesManager( 5462): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/ActivityManager(  972): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5488 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
I/art     (  407): Explicit concurrent mark sweep GC freed 8673(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 263us total 30.036ms
,D/Process (  972): killProcessQuiet, pid=4803
,I/ActivityManager(  972): Killing 4803:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ImageRamCache( 5437): create image Cache, size: 31457280.
I/ImageRamCache( 5437): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5437): create image Cache, size: 31457280.
I/FeedSettings( 5437): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5437): GroupBudget 0.500000 0.380000
I/FeedSettings( 5437): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5437): changeLocale(): en_GB
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 176us total 25.435ms
,I/Prism.AllAppsOptionsMa_( 5437): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 5437): loadGridSize() with Alternative
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=5405, uid=10085, userID:0
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 153us total 16.777ms
,I/art     (  972): Explicit concurrent mark sweep GC freed 8622(445KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 10.414ms total 226.990ms
,D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=5405, uid=10085, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=5405, uid=10085, userID:0,
,W/asset   (  972): Copying FileAsset 0x55a62ce200 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,W/PackageManager(  972): Unable to load service info ResolveInfo{c64c2b5 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  972): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  972): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  972): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  972): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  972): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  972): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  972): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  972): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  972): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  972): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  972): Recipient 4803
,D/AdapterServiceConfig( 5462): Adding HeadsetService
D/AdapterServiceConfig( 5462): Adding A2dpService
D/AdapterServiceConfig( 5462): Adding HidService
,D/AdapterServiceConfig( 5462): Adding HealthService
D/AdapterServiceConfig( 5462): Adding PanService
D/AdapterServiceConfig( 5462): Adding GattService
V/BluetoothPbapReceiver( 5462): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5462): ***********state = 10
E/BluetoothMasService( 5462): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/PMS     (  972): acquireWL(1f85e15f): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4895 1000 null
W/ContextImpl( 4895): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,I/SocialManager[SocialBiLogHelper]( 5437): action: com.htc.sense.hsp.HANDLE_ULOG
D/PMS     (  972): releaseWL(1f85e15f): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
I/SocialManager[SocialBiLogHelper]( 5437): last commit ulog time 1449151159265
I/SocialManager[SocialBiLogHelper]( 5437): do commit ulog
,D/PMS     (  972): acquireWL(320796d6): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4895 1000 null
,D/BluetoothMasService( 5462): Add permission for SmsProvider.
,D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  972): java.lang.Throwable: stack dump
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fa4f52d:true
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/DockEventReceiver( 4895): finishStartingService: stopping service
D/HtcBtWidget_BTWidgetProvider( 5336): onBTStateChanged() for widget: 
V/BluetoothMasService( 5462): Starting MAS instances
D/BluetoothAdapter( 5462): 833156839: getState() :  mService = null. Returning STATE_OFF
D/HtcBtWidget_BTWidgetProvider( 5336): updateWidget(context) for widget: 
,D/PMS     (  972): releaseWL(320796d6): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
I/MailMessageReceiver( 5462): reg:com.android.bluetooth.btservice.AdapterApp@3dd5b294 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@22de513d
,I/MailManager( 5462): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@22de513d
,V/EmailUtils( 5462): Manager Instance is not NULL
,D/JobSchedulerService(  972): Receieved: android.intent.action.PACKAGE_REMOVED,
,I/ActivityManager(  972): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5529 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL false Token 15 num clients 6
D/PMS     (  972): runPSCheck
,D/HtcPowerSaver(  972): Checking...
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: ApStaDisabledState
D/TaskPersister(  972): removeObsoleteFile: deleting file=8_task.xml
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,I/HtcPowerSaver(  972): updateStatus (8000,97,-1,false,false,false,-1)
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/HtcPowerSaver(  972): << updateStatus
,I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
,D/WifiService(  972): New client listening to asynchronous messages
,I/Gmail   ( 5308): master sync=false, engine sync=true
,E/WifiTrafficPoller(  972): ADD_CLIENT: 7
,W/BroadcastQueue(  972): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/ActivityManager(  972): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=5555 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  972): Killing 4918:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4918
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/VelvetNetworkClient( 5405): Network connection not availble
I/SearchBackgroundTaskFac( 5405): refreshing internal icing corpora
,I/SearchBackgroundTaskFac( 5405): Checking for language pack updates
,I/ActivityManager(  972): Recipient 4918
,D/Process (  972): killProcessQuiet, pid=4837
I/ActivityManager(  972): Killing 4837:com.htc.htccupd/u0a13 (adj 15): empty #18
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 4837
,D/Tethering(  972): interfaceRemoved wlan0,
E/Tethering(  972): attempting to remove unknown iface (wlan0), ignoring
,W/OpenGLRenderer( 1506): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ActivityManager(  972): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=5582 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,I/VelvetNetworkClient( 5405): Network connection not availble
I/GservicesUpdateTask( 5405): Updating Gservices keys
,D/HtcAdjCursorFactory( 5529): Set CursorWindow size to: 4194304 KB, Tid: 5554
,I/VelvetNetworkClient( 5405): Network connection not availble
,I/VelvetNetworkClient( 5405): Network connection not availble
,W/FileUtils( 5529): Failed to chmod(/data/user/0/com.htc.android.mail/databases/mail.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,I/UpdateIcingCorporaServi( 5405): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,I/Gmail   ( 5308): getAccountsCursor
,V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/EmailUtils( 5462): ============NULL aList========
V/EmailUtils( 5462): <-getEmailAccountIdList
,V/BluetoothMasService( 5462): onCreate: mIsEmailEnabled: true
D/AuthorizationBluetoothService( 1934): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/Gmail   ( 5308): master sync=false, engine sync=true,
D/GCM     ( 1934): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GmsCoreStatsServiceLauncher( 4478): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/BluetoothMasReceiver( 5462): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 5462): onDestroy: mIsEmailEnabled: true
E/SQLiteDatabase( 5405): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 5405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/SQLiteDatabase( 5405): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/SQLiteDatabase( 5405): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/SQLiteDatabase( 5405): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5405): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/BluetoothSapReceiver( 5462): SapReceiver onReceive 
V/BluetoothSapReceiver( 5462): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5462):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5462): startService = false
,I/ActivityManager(  972): Killing 4939:com.android.settings:remote/1000 (adj 15): empty #17
,D/Process (  972): killProcessQuiet, pid=4939
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
E/SharedPreferencesImpl( 5405): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/ThrottlingLogger.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/ThrottlingLogger.xml.bak
E/SharedPreferencesImpl( 5405): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/ThrottlingLogger.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/ThrottlingLogger.xml.bak
,V/SocialManagerService( 1586): getDataSources
,E/Search.SharedPreferencesProto( 5405): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ImageRamCache( 5582): create image Cache, size: 31457280.
I/SocialManagerService( 1586): plugin added: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
,I/SocialManagerService( 1586): plugin added: com.google
I/ImageRamCache( 5582): [resize] ImageRamCache resized to: 30Mb.
I/SocialManagerService( 1586): plugin added: com.htc.opensense.htcnews
I/SocialManagerService( 1586): plugin added: com.htc.club
I/ImageRamCache( 5582): create image Cache, size: 31457280.
I/SocialManagerService( 1586): plugin added: com.twitter.android.auth.login
I/SocialManagerService( 1586): plugin added: com.htc.linkedin
I/SocialManagerService( 1586): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1586): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1586): plugin added: com.facebook.auth.login
I/SocialManagerService( 1586): plugin added: com.htc.drive.activator
I/SocialManagerService( 1586): plugin added: com.htc.venuesrecommend
D/Tethering(  972): interfaceLinkStateChanged p2p0, false
D/Tethering(  972): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,I/SocialManagerService( 1586): device total memory: 1842M
,I/SocialManagerService( 1586): groupAccounts
,I/FeedSettings( 5582): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5582): GroupBudget 0.500000 0.380000
I/FeedSettings( 5582): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5582): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 5582): loadSortType() with Custom,
,I/Prism.AllAppsOptionsMa_( 5582): loadGridSize() with Alternative
E/SQLiteDatabase( 5405): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
E/SQLiteDatabase( 5405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5405): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5405): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteDatabase( 5405): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteDatabase( 5405): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteDatabase( 5405): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteDatabase( 5405): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteDatabase( 5405): 	at com.google.android.apps.gsa.velour.r.aJq(VelourReleaseState.java:213)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.s.d(SearchUrlHelper.java:1789)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.s.c(SearchUrlHelper.java:1482)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1671)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1690)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1614)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1402)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.s.as(SearchUrlHelper.java:1123)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.a.b.b(GwsSuggestionFetcher.java:171)
E/SQLiteDatabase( 5405): 	at com.google.android.search.core.google.a.b.a(GwsSuggestionFetcher.java:108)
E/SQLiteDatabase( 5405): 	at com.google.android.c.a.a.a.b.run(RefreshZeroPrefixSuggestionsTask.java:65)
E/SQLiteDatabase( 5405): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5405): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5405): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5405): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/SQLiteOpenHelper( 5405): Couldn't open jar_store.db for writing (will try read-only):
E/SQLiteOpenHelper( 5405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5405): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5405): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteOpenHelper( 5405): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteOpenHelper( 5405): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteOpenHelper( 5405): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteOpenHelper( 5405): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteOpenHelper( 5405): 	at com.google.android.apps.gsa.velour.r.aJq(VelourReleaseState.java:213)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.s.d(SearchUrlHelper.java:1789)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.s.c(SearchUrlHelper.java:1482)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1671)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1690)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1614)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.s.a(SearchUrlHelper.java:1402)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.s.as(SearchUrlHelper.java:1123)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.a.b.b(GwsSuggestionFetcher.java:171)
E/SQLiteOpenHelper( 5405): 	at com.google.android.search.core.google.a.b.a(GwsSuggestionFetcher.java:108)
E/SQLiteOpenHelper( 5405): 	at com.google.android.c.a.a.a.b.run(RefreshZeroPrefixSuggestionsTask.java:65)
E/SQLiteOpenHelper( 5405): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5405): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5405): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5405): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/SocialManagerService( 1586): cannot find this plugin service: com.htc.drive.activator
E/SocialManagerService( 1586): error when get process name! process name is null!
E/SocialManagerService( 1586): skip binding the plugin without process namecom.htc.drive.activator
I/ActivityManager(  972): Recipient 4939
W/SQLiteOpenHelper( 5405): Opened jar_store.db in read-only mode
D/Tethering(  972): interfaceRemoved p2p0
E/Tethering(  972): attempting to remove unknown iface (p2p0), ignoring
I/SocialManagerService( 1586): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to pending queue!
I/SocialManagerService( 1586): add com.google to pending queue!
I/SocialManagerService( 1586): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1586): add com.htc.club to pending queue!
I/SocialManagerService( 1586): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1586): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1586): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1586): add com.facebook.auth.login to pending queue!
I/SocialManagerService( 1586): add com.htc.sense.socialnetwork.instagram to pending queue!
I/SocialManagerService( 1586): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1586): consume pending plugin session
I/SocialManagerService( 1586): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to process map!
V/SocialManagerService( 1586): initiating bind to plugin type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1586): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connecting, adding msg, has message?true
I/WebViewFactory( 5405): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/AuthorizationBluetoothService( 1934): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  972): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5633 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/SocialManagerService( 1586): add com.google to process map!
V/SocialManagerService( 1586): initiating bind to plugin type com.google
I/SocialManagerService( 1586): com.google connecting, adding msg, has message?true
,I/ActivityManager(  972): Delay finish: com.google.android.gms/.wearable.service.AutoStarterReceiver
,E/SharedPreferencesImpl( 5405): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,E/AndroidRuntime( 5405): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5405): Process: com.google.android.googlequicksearchbox:search, PID: 5405
E/AndroidRuntime( 5405): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5405): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5405): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5405): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5405): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/AndroidRuntime( 5405): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/AndroidRuntime( 5405): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 5405): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 5405): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 5405): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 5405): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 5405): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 5405): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 5405): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5405): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5405): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5405): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  972): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.googleplus/com.htc.plugin.googleplus.GooglePlusSocialPluginService: pid=5652 uid=10021 gids={50021, 9997, 3003, 1028, 1015, 1023} abi=arm64-v8a
I/SocialManagerService( 1586): add com.twitter.android.auth.login to process map!
V/SocialManagerService( 1586): initiating bind to plugin type com.twitter.android.auth.login
I/SocialManagerService( 1586): com.twitter.android.auth.login connecting, adding msg, has message?true
E/Search.SharedPreferencesProto( 5405): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
E/ActivityManager(  972): App crashed! Process: com.google.android.googlequicksearchbox:search
,I/SocialManagerService( 1586): add com.htc.club to process map!
,E/DropBoxManagerService(  972): Can't write: system_app_crash
E/DropBoxManagerService(  972): java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  972): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  972): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  972): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  972): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  972): 	... 5 more
V/SocialManagerService( 1586): initiating bind to plugin type com.htc.club
I/SocialManagerService( 1586): com.htc.club connecting, adding msg, has message?true
,I/SocialManagerService( 1586): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connected, removed msg, has message?false
,I/SocialManagerService( 1586): skip to add com.htc.opensense.htcnews, process full!
,I/SocialManagerService( 1586): add com.htc.linkedin to process map!
V/SocialManagerService( 1586): initiating bind to plugin type com.htc.linkedin
I/SocialManagerService( 1586): com.htc.linkedin connecting, adding msg, has message?true
,D/BlinkFeedPluginService( 2387): Set icon to :2130837679
D/BlinkFeedPluginService( 2387): class com.htc.blinkfeed.provider.DummyIdentityProvider
D/BlinkFeedPluginService( 2387): Not filterable
D/SocialManagerService( 1586): handling plugin: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin set result in bg
I/SocialManagerService( 1586): remove account type: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin from process map!
,I/SocialManagerService( 1586): remove process: pl.k2.droidoaudioteka from process map!
,I/LibraryLoader( 5405): Time to load native libraries: 2 ms (timestamps 6518-6520),
I/LibraryLoader( 5405): Expected native library version number "",actual native library version number ""
,D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000000),
I/SocialManagerService( 1586): add com.htc.socialnetwork.rss.octopus to process map!,
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/SocialManagerService( 1586): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
D/StatusBarManagerService(  972): hiding MENU key
I/SocialManagerService( 1586): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
,W/art     ( 5405): Attempt to remove local handle scope entry from IRT, ignoring
,I/SocialManagerService( 1586): skip to add com.facebook.auth.login, plugin per process full!
V/SocialManagerService( 1586): on plugin completed! plugin session type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1586): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1586): add com.htc.venuesrecommend to process map!
V/SocialManagerService( 1586): initiating bind to plugin type com.htc.venuesrecommend
I/SocialManagerService( 1586): com.htc.venuesrecommend connecting, adding msg, has message?true
,I/SocialManagerService( 1586): consume pending plugin session
I/SocialManagerService( 1586): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1586): initiating bind to plugin type com.htc.opensense.htcnews
I/SocialManagerService( 1586): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
I/SocialManagerService( 1586): com.htc.opensense.htcnews connecting, adding msg, has message?true
,I/SocialManagerService( 1586): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1586): skip to add com.facebook.auth.login, plugin per process full!
,D/StreamPluginService( 5437): getDataSources start
,D/LocationSocialPlugin( 5437): onBind
,D/SocialManagerService( 1586): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
I/SocialManagerService( 1586): remove account type: com.htc.socialnetwork.rss.octopus from process map!
I/SocialManagerService( 1586): com.htc.venuesrecommend connected, removed msg, has message?false
V/SocialManagerService( 1586): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1586): consume pending plugin session
I/SocialManagerService( 1586): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1586): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/LocationIdentityProvider( 5437): is_approved false
D/LocationSocialPlugin( 5437): account null
,D/LocationSocialPlugin( 5437): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
D/SocialManagerService( 1586): handling plugin: com.htc.venuesrecommend set result in bg
I/SocialManagerService( 1586): remove account type: com.htc.venuesrecommend from process map!
V/SocialManagerService( 1586): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1586): consume pending plugin session
I/SocialManagerService( 1586): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1586): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,E/Search.SharedPreferencesProto( 5405): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/SharedPreferencesImpl( 5405): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,E/SQLiteDatabase( 5582): Failed to open database '/data/data/com.htc.launcher/databases/BiLogClient'.
E/SQLiteDatabase( 5582): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5582): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5582): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5582): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5582): 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:155)
E/SQLiteDatabase( 5582): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5582): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5582): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5582): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5582): FATAL EXCEPTION: IntentService[BiLogUploadService]
E/AndroidRuntime( 5582): Process: com.htc.launcher:biclient, PID: 5582
E/AndroidRuntime( 5582): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5582): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5582): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5582): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5582): 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:155)
E/AndroidRuntime( 5582): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5582): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Andr,oidRuntime( 5582): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5582): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  972): HtcErrorReportManager Begin---add error logs to dropbox
E/ActivityManager(  972): App crashed! Process: com.htc.launcher:biclient
E/SQLiteDatabase( 1934): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 1934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 1934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1934): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1934): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 1934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 1934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1934): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1934): Opened phenotype.db in read-only mode
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(  972): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
I/SocialManagerService( 1586): com.htc.club connected, removed msg, has message?false
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  972): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  972): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(  972): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  972): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(  972): 	at libcore.io.Posix.open(Native Method)
W/System.err(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  972): 	... 14 more
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(  972): 	at libcore.io.Posix.open(Native Method)
W/System.err(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  972): 	... 12 more
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1934): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1934): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/ClearcutLoggerIntentService( 1934): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1934): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1934): 	at java.lang.Thread.run(Thread.java:818)
,W/System  ( 5437): DiskLruCache /data/data/com.htc.launcher/cache/http is corrupt: /data/data/com.htc.launcher/cache/http/journal: open failed: EROFS (Read-only file system), removing
W/System.err(  972): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  972): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  972): 	at libcore.io.Posix.open(Native Method)
W/System.err(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  972): 	... 14 more
I/GLSUser ( 1934): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1934): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1934): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1934): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/SharedPreferencesImpl( 1934): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LockboxOptInSettings.xml to backup file /data/data/com.google.android.gms/shared_prefs/LockboxOptInSettings.xml.bak
I/SocialManagerService( 1586): com.htc.opensense.htcnews connected, removed msg, has message?false
V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SocialManagerService( 1586): handling plugin: com.htc.opensense.htcnews set result in bg
I/SocialManagerService( 1586): remove account type: com.htc.opensense.htcnews from process map!
I/SocialManagerService( 1586): remove process: com.htc.sense.news from process map!
E/ErrorReport(  972): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  972): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449275272917.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  972): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  972): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  972): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  972): 	... 4 more
V/SocialManagerService( 1586): on plugin completed! plugin session type com.htc.opensense.htcnews
I/SocialManagerService( 1586): consume pending plugin session
I/SocialManagerService( 1586): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1586): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/BlinkFeedPluginService( 5555): Set icon to :2130837554
D/BlinkFeedPluginService( 5555): URI:
D/BlinkFeedPluginService( 5555): Not filterable
D/SocialManagerService( 1586): handling plugin: com.htc.club set result in bg
I/SocialManagerService( 1586): remove account type: com.htc.club from process map!
I/SocialManagerService( 1586): remove process: com.htc.club from process map!
V/SocialManagerService( 1586): on plugin completed! plugin session type com.htc.club
I/SocialManagerService( 1586): consume pending plugin session
I/SocialManagerService( 1586): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1586): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
W/ActivityManager(  972): Can't addPackageDependency on system process
,D/LinkedIn( 5652): contentprovider oncreate getReadableDatabase
,E/SQLiteDatabase( 5652): Failed to open database '/data/data/com.htc.sense.linkedin/databases/linkedin.db'.
E/SQLiteDatabase( 5652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5652): 	at com.htc.sense.linkedin.provider.a.a(Unknown Source)
E/SQLiteDatabase( 5652): 	at com.htc.sense.linkedin.provider.a.doInBackground(Unknown Source)
E/SQLiteDatabase( 5652): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5652): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5652): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5652): 	at java.lang.Thread.run(Thread.java:818)
W/FileUtils( 1934): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteOpenHelper( 5652): Couldn't open linkedin.db for writing (will try read-only):
E/SQLiteOpenHelper( 5652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5652): 	at com.htc.sense.linkedin.provider.a.a(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at com.htc.sense.link,edin.provider.a.doInBackground(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 5652): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5652): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 5652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5652): 	at java.lang.Thread.run(Thread.java:818)
I/GLSUser ( 1934): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1934): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1934): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1934): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/Search.LoginHelper( 5405): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5405): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5405): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/SQLiteOpenHelper( 5652): Opened linkedin.db in read-only mode
W/Search.LoginHelper( 5405): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5405): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5405): 	at com.google.android.ap,ps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5405): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/RemoteViews( 1218): reapply : com.google.android.gms 3 40
V/GLSActivity( 1934): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Search.SharedPreferencesProto( 5405): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  972): Resuming delayed broadcast
,I/ActivityManager(  972): Killing 4965:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4965
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/art     ( 5405): Attempt to remove local handle scope entry from IRT, ignoring,
,W/RefreshDomainCookieTask( 5405): Search parameters fetch failed: com.google.android.apps.gsa.shared.api.io.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
W/RefreshDomainCookieTask( 5405): Search parameters fetch failed
,E/Search.SharedPreferencesProto( 5405): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  972): Recipient 4965,
,W/BroadcastQueue(  972): Skipping deliver [background] BroadcastRecord{21853678 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{11de42bf 5405 com.google.android.googlequicksearchbox:search/10085/u0 remote:1e7450de}: process crashing
W/BroadcastQueue(  972): Skipping deliver [background] BroadcastRecord{3520f151 u-1 android.net.wifi.RSSI_CHANGED callingPid=-1 callingUid=-1} to ReceiverList{11de42bf 5405 com.google.android.googlequicksearchbox:search/10085/u0 remote:1e7450de}: process crashing
,W/FileUtils( 1934): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
W/Search.LoginHelper( 5405): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5405): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5405): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 5405): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5405): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/Search.LoginHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5405): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5405): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 5405): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/GFEEDBACK_SendErrorReportOperation( 4478): Error doing instant send: java.io.IOException: failed to create reports directory
,E/GFEEDBACK_SendErrorReportOperation( 4478): Error saving report: java.io.IOException: failed to create reports directory
E/Search.SharedPreferencesProto( 5405): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/RemoteViews( 1218): reapply : com.google.android.gms 4 40
,I/ActivityManager(  972): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5713 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/GooglePlusSocialPluginService( 5652): Bind
,I/SocialManagerService( 1586): com.google connected, removed msg, has message?false,
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4478, uid=10024, userID:0
I/GooglePlusSocialPluginService( 5652): getDataSources start
,E/SQLiteDatabase( 5652): Failed to open database '/data/data/com.htc.sense.socialnetwork.googleplus/databases/googleplus.db'.,
E/SQLiteDatabase( 5652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5652): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5652): ,	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5652): 	at com.htc.socialnetwork.googleplus.provider.GooglePlusProvider.query(Unknown Source)
E/SQLiteDatabase( 5652): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5652): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5652): 	at com.htc.socialnetwork.googleplus.b.a.c(Unknown Source)
E/SQLiteDatabase( 5652): 	at com.htc.socialnetwork.googleplus.b.a.d(Unknown Source)
E/SQLiteDatabase( 5652): 	at com.htc.plugin.googleplus.GooglePlusSocialPluginService$a.a(Unknown Source)
E/SQLiteDatabase( 5652): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteDatabase( 5652): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5652): Couldn't open googleplus.db for writing (will try read-only):
E/SQLiteOpenHelper( 5652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5652): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5652): 	at com.htc.socialnetwork.googleplus.provider.GooglePlusProvider.query(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:49,1)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5652): 	at com.htc.socialnetwork.googleplus.b.a.c(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at com.htc.socialnetwork.googleplus.b.a.d(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at com.htc.plugin.googleplus.GooglePlusSocialPluginService$a.a(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 5652): Opened googleplus.db in read-only mode
I/SocialManagerService( 1586): com.twitter.android.auth.login connected, removed msg, has message?false
,D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
,D/AccFlag ( 1439): sku_id=118
E/SQLiteDatabase( 5652): Failed to open database '/data/data/com.htc.sense.socialnetwork.twitter/databases/htcchirp.db'.
E/SQLiteDatabase( 5652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5652): 	at com.htc.htctwitter.TwitterProvider.query(Unknown Source)
E/SQLiteDatabase( 5652): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5652): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5652): 	at com.htc.htctwitter.b.d.<init>(Unknown Source)
E/SQLiteDatabase( 5652): 	at com.htc.htctwitter.d.d(Unknown Source)
E/SQLiteDatabase( 5652): 	at com.htc.plugin.twitter.TwitterSocialPluginService$a.a(Unknown Source)
E/SQLiteDatabase( 5652): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteDatabase( 5652): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5652): Couldn't open htcchirp.db for writing (will try read-only):
E/SQLiteOpenHelper( 5652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5652): 	at com.htc.htctwitter.TwitterProvider.query(Unknown Source)
E/SQLite,OpenHelper( 5652): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5652): 	at com.htc.htctwitter.b.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at com.htc.htctwitter.d.d(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at com.htc.plugin.twitter.TwitterSocialPluginService$a.a(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 5652): Opened htcchirp.db in read-only mode
W/ResourcesManager( 5713): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5713): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LinkedIn( 5652): service onBind
I/MultiDex( 5713): VM with version 2.1.0 has multidex support
I/MultiDex( 5713): install
I/MultiDex( 5713): VM has multidex support, MultiDex support library is disabled.
,I/Prism.ItemManager( 1506): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1506): loadItems() com.htc.launcher.pageview.WidgetManager@3674df3d +
I/Prism.WidgetManager( 1506): onLoadItems() +
,W/ResourcesManager( 1506): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/art     (  972): Explicit concurrent mark sweep GC freed 22639(1216KB) AllocSpace objects, 2(168KB) LOS objects, 33% free, 17MB/25MB, paused 1.660ms total 145.468ms,
I/GooglePlusSocialPluginService( 5652): getDataSources end
D/SocialManagerService( 1586): handling plugin: com.google set result in bg
I/SocialManagerService( 1586): remove account type: com.google from process map!
,I/SocialManagerService( 1586): com.htc.linkedin connected, removed msg, has message?false
,V/SocialManagerService( 1586): on plugin completed! plugin session type com.google
,I/SocialManagerService( 1586): consume pending plugin session
I/SocialManagerService( 1586): add com.facebook.auth.login to process map!
V/SocialManagerService( 1586): initiating bind to plugin type com.facebook.auth.login
I/SocialManagerService( 1586): com.facebook.auth.login connecting, adding msg, has message?true
D/GooglePlusSocialPluginService( 5652): Unbind
,I/SocialManagerService( 1586): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1586): handling plugin: com.twitter.android.auth.login set result in bg
I/SocialManagerService( 1586): remove account type: com.twitter.android.auth.login from process map!
,D/LocationInitializer( 4478): Restart initialization of location
V/SocialManagerService( 1586): on plugin completed! plugin session type com.twitter.android.auth.login
I/SocialManagerService( 1586): consume pending plugin session
I/SocialManagerService( 1586): add com.htc.sense.socialnetwork.instagram to process map!
V/SocialManagerService( 1586): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1586): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
,D/CustomHighlightReceiver( 5437): [custom highlight] onReceive
,D/SocialManagerService( 1586): handling plugin: com.htc.linkedin set result in bg
,D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1439): sku_id=118
I/SocialManagerService( 1586): remove account type: com.htc.linkedin from process map!
,V/SocialManagerService( 1586): on plugin completed! plugin session type com.htc.linkedin
I/SocialManagerService( 1586): com.facebook.auth.login connected, removed msg, has message?false
,D/CustomHighlightService( 5437): [custom highlight] onHandleIntent
,I/ActivityManager(  972): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5750 uid=10035 gids={50035, 9997} abi=arm64-v8a
V/JNIHelp ( 5713): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/ErrorReport(  972): HtcErrorReportManager Begin---add error logs to dropbox
D/NewsDB  ( 5437): set custom highlight []
E/SQLiteLog( 5437): (3850) statement aborts at 3: [DELETE FROM tag_custom_highlight] disk I/O error
E/SQLiteDBG( 5437): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.launcher/databases/news.db, handle: 0x55a5fcb650
E/AndroidRuntime( 5437): FATAL EXCEPTION: IntentService[CustomHighlightkService]
E/AndroidRuntime( 5437): Process: com.htc.sense.news, PID: 5437
E/AndroidRuntime( 5437): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5437): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5437): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 5437): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5437): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5437): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 5437): 	at com.htc.lib2.opensense.social.SelectionBuilder.delete(SelectionBuilder.java:235)
E/AndroidRuntime( 5437): 	at com.htc.plugin.news.provider.NewsProvider.delete(NewsProvider.java:487)
E/AndroidRuntime( 5437): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 5437): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 5437): 	at com.htc.plugin.news.provider.NewsDbHelper.clearCustomHighlightTagIds(NewsDbHelper.java:3465)
E/AndroidRuntime( 5437): 	at com.htc.plugin.news.provider.NewsDbHelper.setCustomHighlightTagIds(NewsDbHelper.java:3482)
E/AndroidRuntime( 5437): 	at com.htc.plugin.news.remote.CustomHighlightService.onHandleIntent(CustomHighlightService.java:36)
E/AndroidRuntime( 5437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5437): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SocialManagerService( 1586): com.htc.sense.socialnetwork.instagram connected, removed msg, has message?false
E/ActivityManager(  972): App crashed! Process: com.htc.sense.news
W/System.err(  972): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
D/d       ( 5652): get htcisdemo: false
D/FacebookSocialPluginService( 5652): get htcisdemo: false
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  972): 	at android.o,s.Looper.loop(Looper.java:155)
W/System.err(  972): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  972): 	at libcore.io.Posix.open(Native Method)
W/System.err(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  972): 	... 12 more
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
D/AccFlag ( 1439): sku_id=118
D/SocialManagerService( 1586): handling plugin: com.htc.sense.socialnetwork.instagram set result in bg
I/SocialManagerService( 1586): remove account type: com.htc.sense.socialnetwork.instagram from process map!
V/SocialManagerService( 1586): on plugin completed! plugin session type com.htc.sense.socialnetwork.instagram
W/System.err(  972): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
D/Facebook_Session( 5652): MSG_QUERY_ACCOUNT
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
D/Facebook_Session( 5652): queryAccount
D/Facebook_Session( 5652): queryAccount enter lock
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  972): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  972): 	at libcore.io.Posix.open(Native Method)
W/System.err(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  972): 	... 14 more
D/Facebook_Session( 5652): Facebook Session created
D/TelephUtils( 1439): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92
D/AccFlag ( 1439): sku_id=118
W/System.err(  972): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/ActivityThread( 5713): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5713): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33691045: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
I/ProviderInstaller( 5713): Installed default security provider GmsCore_OpenSSL
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  972): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/SQLiteDatabase( 5652): Failed to open database '/data/data/com.htc.sense.socialnetwork.facebook/databases/facebook.db'.
E/SQLiteDatabase( 5652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5652): 	at com.htc.socialnetwork.facebook.FacebookDB.query(Unknown Source)
E/SQLiteDatabase( 5652): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5652): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5652): 	at com.htc.socialnetwork.facebook.a.a.a(Unknown Source)
E/SQLiteDatabase( 5652): 	at com.htc.socialnetwork.facebook.a.a$b.handleMessage(Unknown Source)
E/SQLiteDatabase( 5652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5652): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5652): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  972): 	at libcore.io.Posix.open(Native Method)
W/ActivityManager(  972): Process com.htc.launcher has crashed too many times: killing!
W/System.err(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  972): 	... 14 more
E/SQLiteOpenHelper( 5652): Couldn't open facebook.db for writing (will try read-only):
E/SQLiteOpenHelper( 5652): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5652): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5652): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5652): 	at com.htc.socialnetwork.facebook.FacebookDB.query(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5652): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5652): 	at com.htc.socialnetwork.facebook.a.a.a(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at com.htc.socialnetwork.facebook.a.a$b.handleMessage(Unknown Source)
E/SQLiteOpenHelper( 5652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5652): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteOpenHelper( 5652): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Facebook_Session( 5652): queryAccount
W/SQLiteOpenHelper( 5652): Opened facebook.db in read-only mode
I/ActivityManager(  972): Killing 5437:com.htc.sense.news/u0a74 (adj 6): crash
D/Process (  972): killProcessQuiet, pid=5437
E/ErrorReport(  972): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  972): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449275273606.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  972): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  972): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  972): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  972): 	... 4 more
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12134 
D/Facebook_Session( 5652): Query Facebook account complete
D/Facebook_Session( 5652): queryAccount enter lock
D/Facebook_Session( 5652): Query Facebook account complete
,D/SocialManagerService( 1586): handling plugin: com.facebook.auth.login set result in bg
I/SocialManagerService( 1586): remove account type: com.facebook.auth.login from process map!
I/SocialManagerService( 1586): remove process: com.htc.sense.socialplugins from process map!

```
