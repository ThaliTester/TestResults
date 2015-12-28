#### Test 503880191ec81a5_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
I/[AppShowMeDebug]BootCompletedReceiver( 4548): push flag is false, skip check
D/Process (  972): killProcessQuiet, pid=4029
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
--------- beginning of system
I/ActivityManager(  972): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=4573 uid=10083 gids={50083, 9997, 1007, 3003, 1028} abi=arm64-v8a
I/ActivityManager(  972): Killing 4029:com.htc.video/u0a29 (adj 15): empty #17
I/art     (  409): Explicit concurrent mark sweep GC freed 8636(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 191us total 27.992ms
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 211us total 23.453ms
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 182us total 23.018ms
,I/ActivityManager(  972): Recipient 4029
D/MyReportAgent( 4573): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
D/MyReportAgent( 4573): DatabaseHelper [DatabaseHelper constructor]
D/MyReportAgent( 4573): PolicyStore [Init] Get cached policy bundle
D/MyReportAgent( 4573): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
I/ActivityManager(  972): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4599 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a
D/MyReportAgent( 4573): ReportServiceHandler on boot complete event 
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=4573, uid=10083, userID:0
V/MyReportAgent( 4573): ReportServiceHandler unregister the PowerConnected Listener
I/ActivityManager(  972): Killing 4000:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4000
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/cutils-trace( 4596): Error opening trace file: Permission denied (13)
I/ActivityManager(  972): Recipient 4000
D/CustomizationManager( 4596): ====startRecUseTime====
D/htc.customization.log.level( 4596):  is 
W/CustomizationLogLevel( 4596): Level value is invalid, use default level 2
D/Messaging( 4449): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4449): networkCode: 
D/MmsConfig( 4449): SIE smsPri: null
D/MmsConfig( 4449): networkCode: 
D/UpdaterAPK | UpdaterBootCompleteReceiver( 4599): onReceive() - start htcCheckinService
D/Messaging( 4449): mNeedToUpdateDate2 start
D/MmsConfig( 4449): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4449): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4449): 
D/MmsAsyncWorkHandler( 4449): HM tk = 20001
D/ReportIndicatorCache( 4449): MSG_QUERY_REPORTS >>
I/htcCheckinService(  972): htcCheckinProvider V2.1
D/htcCheckinService(  972): htcCheckinService() the mIsServiceRunning = true
I/htcCheckinService(  972): Checkin service onCreate()!
D/DraftCache( 4449): [DraftCache/1] DraftCache.constructor
D/DraftCache( 4449): [DraftCache/1] refresh
I/Messaging( 4449): mccmnc> 
I/ActivityManager(  972): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4642 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a
D/MmsConfig( 4449): networkCode: 
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1434):  slotId = -1000
D/MmsSmsV2Provider( 1434): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/htcCheckinService(  972): onStartCommand()
D/htcCheckinService(  972): onStartCommand() the action name = null
D/htcCheckinService(  972): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  972): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/htcCheckinService(  972): InitThread start
D/Process (  972): killProcessQuiet, pid=4055
I/ActivityManager(  972): Killing 4055:com.htc.csrecommend/u0a31 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/Messaging( 4449): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1434): sku_id=118
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1434):  slotId = -1000
D/MmsSmsV2Provider( 1434): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4449): [DraftCache/112] rebuildCache
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/MmsSmsV2Provider( 1434):  slotId = -1000
D/MmsSmsV2Provider( 1434): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4449): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsSmsV2Provider( 1434):  slotId = -1000
D/MmsSmsV2Provider( 1434): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/CustomizationManager( 4596):  Read ACC file spent 0.046 (s)
D/Messaging( 4449): mNeedToUpdateDate2: false
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4596): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4596): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4596): Parsing tag category name = system
D/MessageCustFlag( 4449): sense_version=6.0
I/CustomizationCIDLoader( 4596): Parsing tag category name = application
I/CustomizationCIDLoader( 4596): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4596): Parsing tag category name = AutomotiveHome
D/Jerry   ( 4449): start to preload cursor >>>>>>>
I/CustomizationCIDLoader( 4596): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4596): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4596): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4596): add string-array item, value = 42507
I/CustomizationCIDLoader( 4596): add string-array item, value = 21902
I/CustomizationCIDLoader( 4596): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4596): add string-array item, value = 23420
I/CustomizationCIDLoader( 4596): add string-array item, value = 22299
I/CustomizationCIDLoader( 4596): add string-array item, value = 24002
I/CustomizationCIDLoader( 4596): add string-array item, value = 23210
I/CustomizationCIDLoader( 4596): add string-array item, value = 23205
I/CustomizationCIDLoader( 4596): add string-array item, value = 23806
I/CustomizationCIDLoader( 4596): add string-array item, value = 23430
I/CustomizationCIDLoader( 4596): add string-array item, value = 23408
I/CustomizationCIDLoader( 4596): add string-array item, value = 27205
I/CustomizationCIDLoader( 4596): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4596): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4596):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4596):  All configurations done spent 0.098 (s)
I/ActivityManager(  972): Recipient 4055
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4596 on display 0
D/PMS     (  972): acquireHCC(667fea8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 972 1000 null
D/PMS     (  972): acquireHCC(7cecdc1): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 972 1000 null
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/Jerry   ( 1434): URI_DRAFT
W/asset   (  972): Copying FileAsset 0x55626e9cd0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/DraftCache( 4449): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4449): [DraftCache/112] rebuildCache time: 8
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/MmsAsyncWorkHandler( 4449): 
D/MmsAsyncWorkHandler( 4449): HM tk = 20002
D/MmsSmsV2Provider( 1434):  slotId = -1000
D/PMS     (  972): acquireWL(2925d54): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 972 1000 null
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 94
D/AccFlag ( 1434): sku_id=118
I/FeedHostManager( 1488): [onPause]
I/FeedProviderManager( 1488): onPause
I/AnimationUtil(  972): isHTCRecent(HelloWorld/Recent screens.)/6
I/FeedHostManager( 1488): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2d6ed18c
I/SocialFeedProvider( 1488): +onPause
D/Messaging( 4449): ViewCache CreatePreload
D/Messaging( 4449): ViewCache CreatePreloadOnlyMultipleOpsList
I/SocialFeedProvider( 1488): -onPause
D/PhoneStorageUtil( 4449): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4449): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4449): createReceiver
W/HtcSystemUPManager(  972): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/Cust_MMSMS( 4449): _has_set_default_values_2=true
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=144
E/WifiTrafficPoller(  972): notifying of data activity 0
D/MsgPreferenceUtils( 4449): def_index: 0
D/WIFI_ICON( 1218): WifiActivity: 0
D/MsgPreferenceUtils( 4449): globalIndex = 1
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_3 (gone) T]
I/ActivityManager(  972): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4672 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/MsgPreferenceUtils( 4449): phone state: true
D/MsgPreferenceUtils( 4449): sd state: false
D/MsgPreferenceUtils( 4449): vIndex = 0
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1434): sku_id=118
D/PMS     (  972): acquireWL(33de008f): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 4642 10090 null
D/TelephUtils( 1434): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
V/MmsProvider( 1434): Update uri=content://mms, match=0
V/MmsProvider( 1434): selection=st=129 AND m_type!=134
W/asset   ( 4672): Copying FileAsset 0xac1c5060 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/Messaging( 4449): Reset downloading state: 0
V/MmsSystemEventReceiver( 4449): TransactionService is going to be woken up.
D/StatusBarManagerService(  972): setSystemUiVisibility(0x0)
V/TransactionService( 4449): 1-Creating TransactionService
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/WorldClock.Global( 4642): isHEPDevice = true
D/StatusBarManagerService(  972): hiding MENU key
W/SystemReader( 4642): Cannot find support_china_sense_feature, use default value instead
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl(  972): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
V/TransactionService( 4449): onStartCommand: 1
D/MmsSystemEventReceiver( 4449): unRegisterForConnectionStateChanges
V/TransactionService( 4449): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4449): Loading previous transactions.
I/TrimMemoryManager( 1488): [trimMemory] 20
I/WorldClock.AlarmUtils( 4642): saveSupportOffAlarmInPreference: isSupport = false
I/WorldClock.AlarmService( 4642): isDeviceEncryptionEnabled = false
I/ActivityManager(  972): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4712 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
D/PMS     (  972): releaseWL(33de008f): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
D/TelephUtils( 1434): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
D/AccFlag ( 1434): device_type: 1
I/ActivityManager(  972): Killing 4076:com.htc.home.personalize/1000 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4076
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/WorldClock.AlarmService( 4642): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
E/WifiStateMachine(  972): handleMessage: E msg.what=131155
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-71 f=2412 sc=60 link=43 tx=8.8, 0.0, 0.0  rx=15.2 bcn=0 [on:0 tx:0 rx:0 period:2919] from screen [on:0 period:-357493483] gl hn u24 rssi=-66 ag=0 ticks 0,0,8 ls-=0 [56,56,60,60,60] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-71 f=2412 sc=60 link=43 tx=8.8, 0.0, 0.0  rx=15.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-357493481] gl hn u24 rssi=-66 ag=0 ticks 0,0,8 ls-=0 [56,56,60,60,60] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SIGNAL_POLL'
I/WorldClock.AlarmUtils( 4642): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/wpa_supplicant( 1352): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -71 abnormalRssiCnt = 0 newLinkSpeed = 43
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-71 linkspeed=43
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-71 "NG700"WPA_PSK
E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=43 score=60 -> txbadrate=0.00 txgoodrate=4.40 txretriesrate=0.00 rxrate=9.08 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  972): calculateWifiScore() report new score 56
D/ConnectivityService(  972): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
D/ConnectivityService(  972): sending new Min Network Score(56): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  972): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  972):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  972):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  972): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  972): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  972): new score 56 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  972):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  972): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
I/SecurityController( 1218): onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/WebViewFactory( 4672): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/MediaProvider( 4383): [update][2]#1#
I/ActivityManager(  972): Recipient 4076
E/WifiStateMachine(  972): handleMessage: X
D/WIFI    (  972): new score 56 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  972): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/WifiWatchdogStateMachine(  972): RSSI current: 2 new: -71, 2
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 2 -> 2
D/TransactionService( 4449): Force clearing mTransactionList
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_3 (gone) T]
D/TransactionService( 4449): Force set service start id to 1
V/TransactionService( 4449): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4449): unRegisterForConnectionStateChanges
I/WorldClock.AlarmUtils( 4642): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4642): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
D/TransactionService( 4449): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4449): Destroying TransactionService
I/IntentController( 1218): receive(android.intent.action.ALARM_CHANGED,1,false)
V/TransactionService( 4449): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/WorldClock.AlarmUtils( 4642): isDeviceEncryptionEnabled = false
I/WorldClock.AlarmUtils( 4642): Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.AlarmService( 4642): resetStopwatchToDefault
I/WorldClock.DmdCmd( 4642): This version is general off mode alarm function
W/WorldClock.DmdCmd( 4642): Conn: fail e = java.io.IOException: No such file or directory
I/LibraryLoader( 4672): Time to load native libraries: 12 ms (timestamps 6784-6796)
I/LibraryLoader( 4672): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4672): Binding Chromium to main looper Looper (main, tid 1) {3d12e1a4}
I/LibraryLoader( 4672): Expected native library version number "",actual native library version number ""
I/chromium( 4672): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
E/UpdateRequestReceiver( 4712): ignoring update request
E/UpdateRequestReceiver( 4712): ignoring update request
I/WorldClock.AlarmService( 4642): resetTimerToDefault
I/BrowserStartupController( 4672): Initializing chromium process, singleProcess=true
E/UpdateRequestReceiver( 4712): ignoring update request
W/art     ( 4672): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4672): ApplicationContext is null in ApplicationStatus
E/UpdateRequestReceiver( 4712): ignoring update request
E/UpdateRequestReceiver( 4712): ignoring update request
E/UpdateRequestReceiver( 4712): ignoring update request
I/ActivityManager(  972): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4751 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
D/Process (  972): killProcessQuiet, pid=4098
I/ActivityManager(  972): Killing 4098:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
W/chromium( 4672): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4672): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4672): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4672): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4672): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4672): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4672): Local Branch: 
I/Adreno-EGL( 4672): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4672): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4672):                  d74aa161a12b9c6fc6332151
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d84604d:true
W/System.err(  972): java.lang.Throwable: stack dump
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4672): 539369683: getState(). Returning 12
D/MediaScanner( 4383):  prescan time: 1069ms
D/MediaScanner( 4383):     scan time: 1456ms
D/MediaScanner( 4383): postscan time: 3ms
D/MediaScanner( 4383):    total time: 2528ms
D/MediaScanner( 4383): -----------------------------------------------------------------
D/MediaScanner( 4383): firstscan(media) time: 1072ms
D/MediaScanner( 4383): secondscan(non-media) time: 384ms
D/MediaScanner( 4383):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4383):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4383):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4383):  [Total]    File(Image+Video+Audio+Others) in database : 1546
D/MediaProvider( 4383): [delete][9]
D/MediaProvider( 4383): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 4383): [recoverParentNodes] - 0
D/MediaProvider( 4383): [update][5]
D/MediaScannerServiceEx( 4383): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 4383): [updateImage]+
D/MediaScannerServiceEx( 4383): [updateImage]-0
I/ActivityManager(  972): Recipient 4098
D/MediaScannerServiceEx( 4383): [2] scan finished
D/PMS     (  972): releaseWL(9463556): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaProviderUtils( 4383): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4383): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4383): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4383): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 4383): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 4383): [disAliveExtStorageRows]+131073
I/DeviceManagement( 4751): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4751 dbg=false s=true
I/DeviceManagement( 4751): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/DeviceManagement( 4751): WorkflowService: Starting workflow service
I/DeviceManagement( 4751): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@e1f4ac2] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 4751): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 4751): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 4751): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 4751): ModelRegistry: Loading model meta data from resources...
E/WifiDataStallTracker(  972): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=86 rxSum=77} preTxRxSum={txSum=82 rxSum=75}
I/GoogleHttpClient( 1930): GMS http client unavailable, use old client
D/WifiDataStallTracker(  972): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/ActivityManager(  972): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4791 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/DeviceManagement( 4751): BackgroundController: *** Update after boot...
I/DeviceManagement( 4751): SessionStateController: Checking invariants...
I/htcbackup-core( 4791): ModelRegistry: Loading model meta data from resources...
I/art     (  972): Explicit concurrent mark sweep GC freed 20749(1067KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.442ms total 158.853ms
D/MediaProvider( 4383): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 4383): [update][8]#1#
D/MediaProvider( 4383): [update][17]#0#
D/MediaScannerServiceEx( 4383): [disAliveExtStorageRows]--1, 0
I/DeviceManagement( 4751): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
I/DeviceManagement( 4751): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
D/MediaProviderUtils( 4383): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4383): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4383): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4383): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 4383): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 4383): [disAliveExtStorageRows]+196609
I/DeviceManagement( 4751): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
D/MediaProvider( 4383): [sendStorageAddedIfNeed]: /storage/usb : unmounted
D/MediaProvider( 4383): [update][17]#1#
I/ActivityManager(  972): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4822 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActionCombine( 4791): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
V/SmsReceiverService( 4449): updateNotificationAndShortcutStatus: 
D/MessagingNotification( 4449): New incoming message, can't cancel notification now
D/MessagingNotification( 4449): newMsgCnt: 0, false
I/ActivityManager(  972): Killing 4123:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4123
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/DeviceManagement( 4751): BackgroundController: Invariants are unchanged.
D/MediaProvider( 4383): [update][27]#0#
D/MediaScannerServiceEx( 4383): [disAliveExtStorageRows]--1, 0
W/art     ( 4672): Attempt to remove local handle scope entry from IRT, ignoring
I/DeviceManagement( 4751): SessionStateController: Checking invariants...
W/AwContents( 4672): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4672): CordovaWebView is running on device made by: HTC
I/DeviceManagement( 4751): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
I/ActivityManager(  972): Recipient 4123
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=144
E/MediaScannerServiceEx( 4383): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 4383): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/PMS     (  972): releaseWL(2e07dd18): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
W/art     ( 4672): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4672): Attempt to remove local handle scope entry from IRT, ignoring
I/HtcModeClient( 3772): handler message = 4011
E/HtcModeClient( 3772): Check connection and retry 2 times.
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
D/MediaScannerServiceEx( 4383): [handleExternalVolume] ext storage
I/DeviceManagement( 4751): Perf: *** Cache update - start...
I/DeviceManagement( 4751): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4751): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4751): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 4751): Perf: Scan enabled apps - start...
D/MediaProviderUtils( 4383): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4383): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4383): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4383): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 4383): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 4383): [update][10]#0#
D/MediaProvider( 4383): [update][5]#0#
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
D/MediaProvider( 4383): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 4383): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 4383): [update][15]#1#
D/MediaScannerServiceEx( 4383): [AliveExtStorageRows]-0, 0
D/PMS     (  972): acquireWL(283c092d): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 4383 10017 null
D/MediaScanner( 4383): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
I/RemoteViews( 1218): apply : com.htc.backup 1 18 5 38
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/DeviceManagement( 4751): EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...
I/ActivityManager(  972): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4857 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
W/chromium( 4672): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  972): Killing 4146:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4146
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/RemoteViews( 1218): apply : com.htc.backup 1 9 3 5
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1218): apply : com.htc.backup 0 2 1 5
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1218): apply : com.htc.backup 1 1 1 5
I/RemoteViews( 1218): apply : com.htc.backup 0 13 22 50
I/DeviceManagement( 4751): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
W/ResourcesManager( 4751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/DeviceManagement( 4751): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159
I/DeviceManagement( 4751): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167
I/ActivityManager(  972): Recipient 4146
W/ResourcesManager( 4751): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/ResetNotifyBootCompleteReceiver( 1434): userSerialNumber = 0
D/ResetNotifyBootCompleteReceiver( 1434): Receive bootcomplete intent
D/ResetNotifyBootCompleteReceiver( 1434): isOwnerUser = true
D/FindExtension( 4672): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/DeviceManagement( 4751): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351
I/ActivityManager(  972): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4882 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/HtcCupdXmlParser( 4857): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
D/ActivityThread( 4857): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
W/ResourcesManager( 4751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4751): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4751): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/InputMethodManager( 4672): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@12853879, mServedView=org.apache.cordova.engine.SystemWebView{208419be VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3f0b0a1f
I/DeviceManagement( 4751): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193
I/InputMethodManagerService(  972): Disable input method client, pid=1488
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  972): Enable input method client, pid=4672
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
I/ActivityManager(  972): Displayed com.example.hello/.MainActivity: +1s632ms
D/PMS     (  972): releaseWL(2925d54): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/BindingManager( 4672): Cannot call determinedVisibility() - never saw a connection for the pid: 4672
W/ResourceType( 4751): ResTable_typeSpec entry count inconsistent: given 2, previously 1426
I/chromium( 4672): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/XT9_C   ( 1386): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1386): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1386): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1386): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/DeviceManagement( 4751): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019
D/QXDM2SD:HtcNative( 1434): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/HtcCupdXmlParser( 4857): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  972): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4910 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/JsMessageQueue( 4672): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4672): Unable to open asset URL: file:///android_asset/www/jxcore.js
W/ResourcesManager( 4751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ContactMessageStore( 1434): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1434): MSG_NOTIFY_CS_TO_SYNC <<
D/jxcore_app_log( 4672): JniHelper::setJavaVM(0xab0578f8), pthread_self() = -1405618808
D/JX-Cordova( 4672): jxcore cordova android initializing
W/ResourcesManager( 4751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AlarmManager(  972): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  972): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  972): [AlarmQueuing] init alarm queuing list
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4910): -onCreate()
I/DeviceManagement( 4751): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
D/PMS     (  972): releaseHCC(667fea8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  972): releaseHCC(7cecdc1): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
I/ActivityManager(  972): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4932 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
D/Process (  972): killProcessQuiet, pid=4168
I/ActivityManager(  972): Killing 4168:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 4751): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.,
,W/jxcore-log( 4672): Initializing JXcore engine
,W/jxcore-log( 4672): JXcore engine is ready
W/jxcore-log( 4672): Starting JXcore engine,
,W/ResourcesManager( 4751): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  972): Recipient 4168,
,W/ResourcesManager( 4751): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 4751): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/DeviceManagement( 4751): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686
I/DeviceManagement( 4751): EnabledAppBuilder: Found 8 DM enabled apps.
I/DeviceManagement( 4751): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 4751): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,W/jxcore-log( 4672): Platform android
W/jxcore-log( 4672): 
W/jxcore-log( 4672): Process ARCH arm
W/jxcore-log( 4672): 
I/DeviceManagement( 4751): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,V/Settings:HtcSettingsApplication( 4910): [4910/4910] onCreate(),
,I/DeviceManagement( 4751): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 4751): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,I/DeviceManagement( 4751): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
,I/DeviceManagement( 4751): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,W/ContextImpl( 4910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
,I/DeviceManagement( 4751): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 4751): Perf: Scan enabled apps - complete: 984 ms,
I/DeviceManagement( 4751): Perf: *** Enabled app cache update - complete: 987 ms
,I/DeviceManagement( 4751): Perf: *** Config cache update - start...
I/DeviceManagement( 4751): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4751): ConfigCacheController: *** Updating stale config cache entries...
I/ActivityManager(  972): Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4953 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/jxcore-log( 4672): JXcore Cordova bridge is ready!
I/jxcore-log( 4672): 
W/jxcore-log( 4672): JXcore engine is started
I/DeviceManagement( 4751): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 4751): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4751): AlarmController: Scheduling TTL alarm for: 2015.12.29 at 16:41:34.161 CET (due to: com.htc.launcher)
I/art     (  409): Explicit concurrent mark sweep GC freed 8686(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 170us total 21.841ms
,I/AlarmManager(  972): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@222f400c
,I/AlarmManager(  972): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@8ea1d55
,D/TetherSettings( 4910): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4910): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4910): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4910): Cust_ConnectToPC   : spcsc>false
D/        ( 4910): Cust_ConnectToPC   : IPT>true
D/        ( 4910): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4910): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 149us total 32.316ms
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 147us total 18.246ms
,E/jxcore-log( 4672): >> HTC-HTC One M8s,
E/jxcore-log( 4672): 
I/jxcore-log( 4672): Total memory 1931808768
I/jxcore-log( 4672): 
,I/jxcore-log( 4672): Free memory 93499392
I/jxcore-log( 4672): 
,I/jxcore-log( 4672): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4672): 
I/jxcore-log( 4672): process.cwd /data/data/com.example.hello/files/www/jxcore,
I/jxcore-log( 4672): 
,I/jxcore-log( 4672): userPath [ 'www' ]
I/jxcore-log( 4672): 
,I/jxcore-log( 4672): Size 1080 1776,
I/jxcore-log( 4672): 
I/AlarmManager(  972): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@b51405b
,I/jxcore-log( 4672): Screen Brightness 142
I/jxcore-log( 4672): 
E/jxcore-log( 4672): Dummy Error Log.
E/jxcore-log( 4672): 
E/SmartNS_Utility( 4910): hasRemovableStorageSlot: true
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.google.android.apps.maps
D/SmartNS_Utility( 4910): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.google.android.gsf
D/SmartNS_NSReceiver( 4910): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.google.android.location
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.facebook.katana
E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=144
I/AlarmManager(  972): [AlarmQueuing] add queuing package: jp.naver.line.android
,I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  972): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  972): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  972): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  972): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
D/Process (  972): killProcessQuiet, pid=4191
I/ActivityManager(  972): Killing 4191:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/SmartNS_Utility( 4910): setISNotification
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4751, uid=10099, userID:0
I/DeviceManagement( 4751): Perf: *** Config cache update - complete: 168 ms
D/SmartNS_Utility( 4910): usb_cable_connect = 1
D/SmartNS_Utility( 4910): usb_denied = 0
I/DeviceManagement( 4751): Perf: *** Cache update - complete: 1160 ms
I/SmartNS_PSService( 4910): usb notificaiton:true
I/DeviceManagement( 4751): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@e1f4ac2]
,E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,V/Settings:HtcSettingsApplication( 4953): [4953/4953] onCreate(),
,I/ActivityManager(  972): Recipient 4191
,I/ActionCombine( 4910): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/DeviceManagement( 4751): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@37a376cb] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 4751): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 4751): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4751): SessionStateController: Checking invariants...
D/Process (  972): killProcessQuiet, pid=3356
I/ActivityManager(  972): Killing 3356:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/SmartNS_Utility( 4910): usb_cable_connect = 1
,D/SmartNS_Utility( 4910): usb_denied = 0,
I/SmartNS_PSService( 4910): usb notificaiton:true
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false,
,I/DeviceManagement( 4751): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/ActivityManager(  972): Recipient 3356
,I/DeviceManagement( 4751): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@37a376cb]
,I/ActivityManager(  972): Killing 4214:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4214
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/DeviceManagement( 4751): WorkflowService: Stopping workflow service
,I/RemoteViews( 1218): reapply : com.android.settings 1 36
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,W/Atfwd_Sendcmd(  435): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  972): Recipient 4214
,D/Process (  972): killProcessQuiet, pid=4246,
I/ActivityManager(  972): Killing 4246:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17,
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 4246
,D/MediaScanner( 4383):  prescan time: 633ms
D/MediaScanner( 4383):     scan time: 972ms
D/MediaScanner( 4383): postscan time: 3ms
D/MediaScanner( 4383):    total time: 1608ms
D/MediaScanner( 4383): -----------------------------------------------------------------
D/MediaScanner( 4383): firstscan(media) time: 586ms
D/MediaScanner( 4383): secondscan(non-media) time: 386ms
D/MediaScanner( 4383):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4383):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4383):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 4383):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,D/MediaProvider( 4383): [delete][15]
,D/MediaProvider( 4383): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,I/jxcore-log( 4672): getBuffer is called!!!!
I/jxcore-log( 4672): 
,D/MediaProvider( 4383): [recoverParentNodes] - 0,
D/MediaProvider( 4383): [update][7]
D/MediaScannerServiceEx( 4383): [scan] Recover Parent Node is finished!
,D/MediaScannerServiceEx( 4383): [updateImage]+
,D/MediaScannerServiceEx( 4383): [updateImage]-0
,I/htcbackup-core( 4791): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
D/MediaScannerServiceEx( 4383): [3] scan finished
D/PMS     (  972): releaseWL(283c092d): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/MediaProviderUtils( 4383): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4383): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4383): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4383): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
,W/MediaScannerServiceEx( 4383): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 4383): [disAliveExtStorageRows]+131073
I/RemoteViews( 1218): reapply : com.android.settings 1 36
,D/Process (  972): killProcessQuiet, pid=4302
I/ActivityManager(  972): Killing 4302:com.htc.lmw/u0a58 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
V/AlarmManager(  972): sending alarm PendingIntent{1c5b84a4: PendingIntentRecord{3039a20d com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=7, w=1447326412457, Int=604800000
,D/MediaProvider( 4383): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 4383): [update][22]#1#
,D/MediaProvider( 4383): [update][20]#0#
,D/MediaScannerServiceEx( 4383): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  972): Recipient 4302,
,D/MediaProviderUtils( 4383): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 4383): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 4383): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 4383): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 4383): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 4383): [disAliveExtStorageRows]+196609
,D/MediaProvider( 4383): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 4383): [update][28]#1#
,D/MediaProvider( 4383): [update][17]#0#
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155,
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-71 f=2412 sc=56 link=43 tx=4.4, 0.0, 0.0  rx=9.1 bcn=0 [on:0 tx:0 rx:0 period:2815] from screen [on:0 period:-357490461] gl hn u24 rssi=-66 ag=0 ticks 0,0,9 ls-=0 [56,56,56,56,56] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-71 f=2412 sc=56 link=43 tx=4.4, 0.0, 0.0  rx=9.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-357490460] gl hn u24 rssi=-66 ag=0 ticks 0,0,9 ls-=0 [56,56,56,56,56] brc=0 lrc=0
E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1352): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -71 abnormalRssiCnt = 0 newLinkSpeed = 43
,E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-71 linkspeed=43
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-71 "NG700"WPA_PSK
E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=43 score=56 -> txbadrate=0.00 txgoodrate=2.20 txretriesrate=0.00 rxrate=4.54 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  972): handleMessage: X
,D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 2 -> 2
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_3 (gone) T]
,I/art     (  972): Explicit concurrent mark sweep GC freed 13206(653KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.309ms total 151.302ms
D/MediaScannerServiceEx( 4383): [disAliveExtStorageRows]--1, 0
,W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  972): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4980 uid=9987 gids={49987, 9997} abi=arm64-v8a,
,D/WifiWatchdogStateMachine(  972): RSSI current: 2 new: -71, 2,
,D/SmartDim(  972): Init customizeScreenOffDelayClass error
,I/SensorManager(  972): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@331e4710, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  972): enable: get sensor name = Accelerometer Sensor
,I/ActivityManager(  972): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5001 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
V/AlarmManager(  972): sending alarm PendingIntent{3a6c262f: PendingIntentRecord{20ee05c5 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=59637, Int=0
W/SensorService(  972): pid=972, uid=1000
W/BroadcastQueue(  972): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{678ab1a u0 ReceiverList{b08c43c 972 system/1000/u0 local:1a26dc0e}}
W/SensorService(  972): Active sensors: size = 3
W/SensorService(  972): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  972): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@331e4710, eanble = 1, strlen(mName) = 36
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  972): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3e3b7bde
W/SensorService(  972): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@143dec62
W/SensorService(  972): Listener[2] = com.htc.smartdim.sensor_eye@331e4710
W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  972): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@331e4710, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  972): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  972): enable: get sensor name = CM36686 Proximity sensor
W/SensorService(  972): pid=972, uid=1000
W/SensorService(  972): Active sensors: size = 4
W/SensorService(  972): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  972): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  972): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  972): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  972): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@331e4710, eanble = 1, strlen(mName) = 36
W/SensorService(  972): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  972): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3e3b7bde
W/SensorService(  972): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@143dec62
W/SensorService(  972): Listener[2] = com.htc.smartdim.sensor_eye@331e4710
W/SensorService(  972): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/RemoteViews( 1218): reapply : com.htc.backup 2 38
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1218): apply : com.htc.backup 1 1 0 5
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1218): apply : com.htc.backup 0 2 0 5
I/RemoteViews( 1218): setHTCTheme(com.htc.backup,true,33751145)
I/RemoteViews( 1218): apply : com.htc.backup 0 2 0 5
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
I/RemoteViews( 1218): reapply : com.htc.backup 10 50
,I/ActivityManager(  972): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=5026 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  972): killProcessQuiet, pid=4340
I/ActivityManager(  972): Killing 4340:com.android.managedprovisioning/u0a63 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  972): Recipient 4340
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=144
,I/SensorManager(  972): dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@331e4710
,I/ActivityManager(  972): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5048 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  972): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=5069 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  972): Killing 4490:com.htc.cs.pns/u0a71 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4490
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  972): Recipient 4490
,D/MdScBoot( 5001): [15b.1.] 30@-222345 -> 40
,D/MdScBootUi( 5001): [15b.1.2.] boot 118,
,D/MdScSimSt( 5001): [15b.1.2.] qry 118: 0+1 running 0,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5069, uid=10072, userID:0
,D/Process (  972): killProcessQuiet, pid=4526
,I/ActivityManager(  972): Killing 4526:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/global  ( 5069): [apache-http] Connection GC has been deprecated!
,I/ActivityManager(  972): Recipient 4526
,I/ActivityManager(  972): Killing 4548:com.htc.showme/u0a81 (adj 15): empty #17
,D/Process (  972): killProcessQuiet, pid=4548
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  972): Recipient 4548
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=144
,D/Finsky  ( 5069): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 5069): [apache-http] Connection GC has been deprecated!
,W/global  ( 5069): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5069): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  972): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5110 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5069): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5069): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 5110): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5110): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5069, uid=10072, userID:0
,I/MultiDex( 5110): VM with version 2.1.0 has multidex support,
I/MultiDex( 5110): install
I/MultiDex( 5110): VM has multidex support, MultiDex support library is disabled.
,D/Volley  ( 5069): [474] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 5069): [480] DiskBasedCache.clear: Cache cleared.
V/JNIHelp ( 5110): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 5069): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5069): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 5069): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityThread( 5110): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5110): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a746759: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5110): Installed default security provider GmsCore_OpenSSL,
,D/Finsky  ( 5069): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSUser ( 1930): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED,
,I/ActivityManager(  972): Killing 4573:com.htc.feedback/u0a83 (adj 15): empty #17,
D/Process (  972): killProcessQuiet, pid=4573
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  972): Recipient 4573
,D/PMS     (  972): acquireWL(3e620eca): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1930 10024 null,
,V/GmsCoreStatsServiceLauncher( 4268): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PMS     (  972): releaseWL(3e620eca): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/PersistentNotificationBroadcastReceiver( 1930): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/AutomaticBrightnessController(  972): setAmbientLux to brighter = 40.0,
D/HABCtrl (  972): lsvalue=10(0th)->40(1th), lValue=39->64
,W/InstanceID/Rpc( 4268): Found 10024
,D/FileApkUtils( 4268): Spent 29ms computing apk sha1.
,D/FileApkUtils( 4268): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 4268): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4268): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4268): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971
,V/Finsky  ( 5069): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5,
E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=145
E/WifiTrafficPoller(  972): notifying of data activity 1
D/WIFI_ICON( 1218): WifiActivity: 1
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_3 (gone) T]
,D/GmsModuleFndr( 4268): Beginning GMS chimera module scan,
,W/asset   ( 4268): Copying FileAsset 0x556225bd10 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.,
,D/GmsModuleFndr( 4268): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/PMS     (  972): acquireWL(20c688e9): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4268 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4268): Beginning module configuration check
,D/ChimeraCfgMgr( 4268): Module APKs unchanged, check complete
,D/PMS     (  972): acquireWL(39b3109c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4268 10024 null
,D/PMS     (  972): acquireWL(14f5caa5): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4268 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1930, uid=10024, userID:0
I/ActivityManager(  972): Delay finish: com.google.android.gms/.nearby.sharing.NearbySharingBroadcastReceiver
,D/PMS     (  972): acquireWL(efd762b): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4268 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(20c688e9): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): acquireWL(101d6c21): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4268 10024 null
,D/GCM     ( 4268): COMPAT: Multi user not supported,
,D/GCM     ( 1930): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/CheckinService( 4268): Disabling old GoogleServicesFramework version
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4268, uid=10024, userID:0
,I/GCoreUlr( 4268): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 4268): Checking schedule, now: 1451341457995 next: 1451878277261
I/CheckinService( 4268): active receiver: disabled
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4268, uid=10024, userID:0
,D/SystemUpdateService( 4268): onCreate
D/PMS     (  972): acquireWL(36d7a2d2): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4268 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0
,D/SystemUpdateService( 4268): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4268, uid=10024, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4268, uid=10024, userID:0
I/ConfigService( 1930): onCreate
I/art     ( 1930): Explicit concurrent mark sweep GC freed 7350(391KB) AllocSpace objects, 4(80KB) LOS objects, 49% free, 4MB/8MB, paused 1.146ms total 52.324ms
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4268, uid=10024, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4268, uid=10024, userID:0
D/PMS     (  972): releaseWL(39b3109c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4268, uid=10024, userID:0
D/PMS     (  972): releaseWL(36d7a2d2): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
I/ConfigFetchService( 4268): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/SystemUpdateService( 4268): cancelUpdate (empty URL)
I/SystemUpdateService( 4268): active receiver: disabled
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4268, uid=10024, userID:0
D/PMS     (  972): acquireWL(1308ba2a): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,V/AuthZen ( 4268): Handling intent: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4268, uid=10024, userID:0
,D/AuthZenEventHandler( 4268): Handling event: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4268, uid=10024, userID:0,
,I/GCoreUlr( 1873): DispatchingService.onCreate()
,D/PMS     (  972): acquireWL(16f87564): PARTIAL_WAKE_LOCK  Icing 0x1 4268 10024 WorkSource{10024 com.google.android.gms}
,I/ConfigFetchService( 4268): service connected
,W/BaseAppContext( 4268): Using Auth Proxy for data requests.
,I/ActivityManager(  972): Resuming delayed broadcast
,D/PMS     (  972): acquireWL(177983d0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(14f5caa5): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(16f87564): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(efd762b): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4268): onDestroy
,I/GLSUser ( 4268): [ChannelManager] Attempting to channel bind connection HttpClient.,
,D/ConfigFetchService( 4268): ConfigApi connection successful.
,I/GLSUser ( 4268): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GCoreUlr( 1873): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,E/WifiDataStallTracker(  972): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  972): updateDataStallInfo: mDataStallTxRxSum={txSum=86 rxSum=77} preTxRxSum={txSum=86 rxSum=77}
D/WifiDataStallTracker(  972): updateDataStallInfo: NONE
D/WifiDataStallTracker(  972): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/ChimeraCfgMgr( 4268): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  972): java.lang.Throwable: stack dump
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34b51a3d:true
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
,I/AuthZen ( 4268): Fetching signing key...
,D/ChimeraCfgMgr( 4268): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1873, uid=10024, userID:0
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AuthZen ( 4268): Signing key fetched successfully!
,W/BaseAppContext( 4268): Using Auth Proxy for data requests.
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=5207 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/AuthZen ( 4268): Starting Enrollment...
,I/GLSActivity( 1930): [ac] getting account id
,D/PMS     (  972): releaseWL(1308ba2a): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms}
,D/AuthZen ( 4268): getting auth token. Attempt 0,
,I/GLSUser ( 1930): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/GCoreUlr( 1873): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/PMS     (  972): acquireWL(1449b6bf): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  972): releaseWL(1449b6bf): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
I/GCoreUlr( 1873): Unbound from all location providers
I/GLSUser ( 1930): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1930): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1930): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1930): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  972): releaseWL(177983d0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5207): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1930): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1930): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1930): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1930): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1873): DispatchingService.onDestroy()
,D/PMS     (  972): acquireWL(4e8e1b6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  972): releaseWL(4e8e1b6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1873): Unbound from all location providers
,E/AuthZen ( 4268): Error getting auth token
E/AuthZen ( 4268): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4268): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
,E/AuthZen ( 4268): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4268): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4268): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4268): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4268): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4268): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4268): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4268): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4268): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/a       ( 4268): Opening database auth.proximity.permit_store...
,I/ActivityManager(  972): Waited long enough for: ServiceRecord{14e9f04 u0 com.htc.autobot/.htcmodeclient.HtcModeService},
,D/AuthZenTransactionCache( 4268): Initialized cache in: /data/data/com.google.android.gms/files,
D/AuthZenTransactionCache( 4268): Clearing transaction cache
,D/PMS     (  972): acquireWL(14b1beb7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 972 1000 null,
,D/PMS     (  972): acquireWL(30542624): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 972 1000 WorkSource{10024},
,D/PMS     (  972): releaseWL(14b1beb7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1218): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/PMS     (  972): acquireWL(515cd89): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 972 1000 null,
,D/PMS     (  972): releaseWL(515cd89): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,D/PhoneStatusBar( 1218): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,I/Babel_SMS( 5207): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5207): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 4449): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/art     (  972): Explicit concurrent mark sweep GC freed 20075(1070KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 16MB/24MB, paused 1.666ms total 159.444ms
,D/MmsCustomizationProvider( 4449): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 5207): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 5207): MmsConfig.loadFromDatabase
W/Kids    ( 4268): [AccountUtils] Account not ready
W/Kids    ( 4268): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4268): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4268): 	at com.google.android.gms.auth.p.d(SourceFile:599),
W/Kids    ( 4268): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4268): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4268): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4268): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4268): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4268): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4268): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4268): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4268): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 2 40
,E/Babel_SMS( 5207): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5207): MmsConfig.loadFromResources
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5207, uid=10112, userID:0
,E/Babel_SMS( 5207): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5207): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,E/WifiStateMachine(  972): handleMessage: E msg.what=131155,
E/WifiStateMachine(  972): processMsg: ConnectedState
,E/WifiStateMachine(  972):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-71 f=2412 sc=56 link=43 tx=2.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-357487443] gl hn u24 rssi=-66 ag=0 ls-=0 [56,56,56,56,56] brc=0 lrc=0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-71 f=2412 sc=56 link=43 tx=2.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-357487442] gl hn u24 rssi=-66 ag=0 ls-=0 [56,56,56,56,56] brc=0 lrc=0
,E/WifiStateMachine(  972):  get link layer stats 0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1352): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative RSSI = -71 abnormalRssiCnt = 0 newLinkSpeed = 43
E/WifiStateMachine(  972): fetchRssiLinkSpeedAndFrequencyNative rssi=-71 linkspeed=43
E/WifiConfigStore(  972): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-71 "NG700"WPA_PSK
,E/WifiStateMachine(  972): calculateWifiScore freq=2412 speed=43 score=56 -> txbadrate=0.00 txgoodrate=1.10 txretriesrate=0.00 rxrate=2.77 userTriggerdPenalty0
E/WifiStateMachine(  972):  good link -> stuck count =0
E/WifiStateMachine(  972):  badRSSI count0 lowRSSI count0 --> score 56
D/WifiWatchdogStateMachine(  972): RSSI current: 2 new: -71, 2
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 2 -> 2
E/WifiStateMachine(  972): handleMessage: X
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_3 (gone) T]
,W/Settings( 5207): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5207): startup - clean,
,D/PMS     (  972): acquireWL(a1f6054): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 972 1000 null
,D/PMS     (  972): releaseWL(30542624): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
,D/PMS     (  972): releaseWL(a1f6054): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1218): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,I/Babel   ( 5207): deleted: false for 0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5207, uid=10112, userID:0,
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5207, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5207, uid=10112, userID:0,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5207, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5207, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5207, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5207, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5207, uid=10112, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5207, uid=10112, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5207, uid=10112, userID:0
I/HtcModeClient( 3772): handler message = 4011
E/HtcModeClient( 3772): Check connection and retry 3 times.
,W/VideoCapabilities( 5207): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5207): Unsupported mime video/x-ms-wmv
,W/Utils   ( 5207): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 5207): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5207): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5207): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5207): Unsupported mime video/x-ms-wmv,
,I/VideoCapabilities( 5207): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5207): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5207): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5207): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5207): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5207): onServiceConnected,
W/Babel   ( 5207): Attempted to change video mute state without an active call.
,I/ActivityManager(  972): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=5244 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  972): killProcessQuiet, pid=4599
I/ActivityManager(  972): Killing 4599:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
D/WIFI_ICON( 1218): WifiActivity: 0
E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=145
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_3 (gone) T]
E/WifiTrafficPoller(  972): notifying of data activity 0
,I/ActivityManager(  972): Recipient 4599
,I/SocialFeedProvider( 1488): +disConnect socialManager,
I/SocialFeedProvider( 1488): disconnect socialManager,
,I/SocialFeedProvider( 1488): -disConnect socialManager
,W/ResourcesManager( 5244): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5244): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5244): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 5244): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5244): Installed default security provider GmsCore_OpenSSL
,W/art     ( 5244): Suspending all threads took: 5.713ms,
,W/ResourcesManager( 5244): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5244): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,E/cutils-trace( 5275): Error opening trace file: Permission denied (13)
I/dex2oat ( 5275): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2025994461.jar --oat-fd=32 --oat-location=/data/data/com.google.android.youtube/cache/ads-2025994461.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5275): dex2oat: override thread count:4
,E/YouTube MDX( 5244): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,D/libc    ( 5244): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
I/dex2oat ( 5275): dex2oat took 56.610ms (threads: 4)
,D/libc    ( 5244): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  972): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 5244): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL true Token 11 num clients 5
,E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=145
D/BluetoothManagerService(  972): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  972): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@bcd7a0c mBinding = false,
W/Settings:Agent(  972): MONITOR_LOG
W/Settings:Agent(  972): name: bluetooth_on
W/Settings:Agent(  972): value: 0
W/Settings:Agent(  972): >> traceCallingStack()
W/Settings:Agent(  972): Process.myPid(): 972,
W/Settings:Agent(  972): Process.myTid(): 1530
W/Settings:Agent(  972): Process.myUid(): 1000
W/Settings:Agent(  972): ,
W/Settings:Agent(  972): 
W/System.err(  972): java.lang.Throwable: stack dump
,W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  972): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  972): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  972): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  972): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  972): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  972): 
W/Settings:Agent(  972): << traceCallingStack(): 14(ms)
,D/BluetoothManagerService(  972): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  972): Sending off request.
,D/BluetoothAdapterState( 3627): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3627): Setting state to 13
I/BluetoothAdapterState( 3627): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  972): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3627): onBluetoothDisable()
I/bt-btif ( 3627): HAL bt_hal_cbacks->adapter_properties_cb,
I/BluetoothAdapterState( 3627): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/PMS     (  972): acquireWL(893aaa2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3627 1002 null
I/bt-btm  ( 3627): BTM_SetDiscoverability,
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  972): Bluetooth State Change Intent: 12 -> 13
I/bt-btm  ( 3627): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3627): disc_mode 0000
I/bt-btm  ( 3627): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3627): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3627): Scan Mode:21
D/BluetoothAdapterState( 3627): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,I/IntentController( 1218): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
I/bt-btif ( 3627): BTA_JvDeleteRecord
I/bt-btif ( 3627): BTM_SetConnectability
I/bt-btm  ( 3627): BTM_SetConnectability
D/bt-btm  ( 3627): btm_ble_set_
I/bt-btm  ( 3627): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3627): disc_mode 0000
I/bt-btm  ( 3627): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:14
I/bt-btif ( 3627): BTA_JvDeleteRecord
D/WifiService(  972): New client listening to asynchronous messages
I/bt-btif ( 3627): BTA_JvRfcommStopServer
,D/bt-btm  ( 3627): BTM_SEC_CLR[
I/bt-btm  ( 3627): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3627): BTM_SEC_CLR[14]: id 56
I/bt-btif ( 3627): BTA_JvDeleteRecord
I/bt-btif ( 3627): BTA_JvRfcommStopServer
D/bt-btm  ( 3627): BTM_FreeSCN 
I/bt-btif ( 3627): BTA_JvDeleteRecord
I/bt-btif ( 3627): BTA_JvRfcommStopServer
D/bt-btm  ( 3627): BTM_FreeSCN 
I/bt-btif ( 3627): BTA_JvDeleteRecord
I/bt-btif ( 3627): BTA_JvRfcommStopServer
D/bt-btm  ( 3627): BTM_FreeSCN 
E/BtOppRfcommListener( 3627): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btif ( 3627): BTA_JvDeleteRecord
I/bt-btif ( 3627): BTA_JvRfcommStopServer
D/bt-btm  ( 3627): BTM_FreeSCN 
E/bt-btif ( 3627): cmd socket is not created
,V/BluetoothSapService( 3627): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3627): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3627): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3627): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3627): BTM_SEC_CLR[18]: id 60
,D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3627): Write Extended Inquiry Response to controller
I/bt-btm  ( 3627): Write Extended Inquiry Response to controller
I/bt-btm  ( 3627): Write Extended Inquiry Response to controller
I/bt-btm  ( 3627): Write Extended Inquiry Response to controller
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3627): BTM_SetDiscoverability
I/bt-btm  ( 3627): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3627): disc_mode 0000
I/bt-btm  ( 3627): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3627): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3627): BTM_SetConnectability
I/bt-btm  ( 3627): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3627): disc_mode 0000
D/bt-btm  ( 3627): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3627): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3627): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3627): BTM_IsInquiryActive
I/bt-btm  ( 3627): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3627): btm_ble_clear_white_list
W/bt-btif ( 3627): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/NGFService( 4289): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/bt-btif ( 3627): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3627): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3627): BTM_FreeSCN 
I/bt-btm  ( 3627): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3627): BTM_FreeSCN 
I/bt-btm  ( 3627): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3627): AVRC_Close handle:0
D/bt-btif ( 3627): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/WifiManager( 4672): setWifiEnabled: Base Package Name=com.example.hello, uid=10374
D/bt-btif ( 3627): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3627): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3627): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3627): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3627): GATT_Deregister gatt_if=3
I/bt-att  ( 3627): GATT_Listen gatt_if=3
I/bt-btm  ( 3627): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3627): BTM_ReadConnectability
I/bt-btm  ( 3627): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3627): disc_mode 0000
I/bt-att  ( 3627): GATT_Deregister gatt_if=4
I/bt-att  ( 3627): GATT_Listen gatt_if=4
I/bt-btm  ( 3627): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3627): BTM_ReadConnectability
I/bt-btm  ( 3627): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3627): disc_mode 0000
E/bt-btif ( 3627): bta_gattc_deregister Deregister Failedm unknown client cif
E/WifiTrafficPoller(  972): ADD_CLIENT: 6
,E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  972): setWifiEnabled: false pid=4672, uid=10374
W/Settings:Agent(  972): MONITOR_LOG
E/WifiService(  972): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  972): name: wifi_on
I/WifiService(  972): isSprintWifiRestricted(): false
W/Settings:Agent(  972): value: 0
I/WifiService(  972): isMdmWifiRestricted(): false
W/Settings:Agent(  972): >> traceCallingStack()
W/Settings:Agent(  972): Process.myPid(): 972
W/Settings:Agent(  972): Process.myTid(): 1745
W/Settings:Agent(  972): Process.myUid(): 1000
W/Settings:Agent(  972): 
W/Settings:Agent(  972): 
W/System.err(  972): java.lang.Throwable: stack dump
V/BluetoothPbapReceiver( 3627): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3627): ***********state = 13
I/BtOppRfcommListener( 3627): stopping Accept Thread
I/BtOppRfcommListener( 3627): BluetoothSocket listen thread finished
I/bt-btm  ( 3627): btm_ble_clear_white_list_complete
V/BluetoothPbapService( 3627): Pbap Service closeService in
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/PMS     (  972): acquireWL(5a5ceee): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4910 1000 null
W/System.err(  972): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  972): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  972): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  972): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  972): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  972): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  972): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  972): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  972): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  972): 
W/Settings:Agent(  972): << traceCallingStack(): 21(ms)
V/BluetoothPbapService( 3627): successfully stopped pbap service
W/ContextImpl( 4910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/BluetoothPbapService( 3627): Pbap Service closeService out
V/BluetoothPbapService( 3627): Pbap Service onDestroy
V/BluetoothPbapService( 3627): Pbap Service closeService in
V/BluetoothPbapService( 3627): Pbap Service closeService out
I/QuickSettingBluetooth( 1218): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
,D/VoldConnector(  972): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 5244): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/PMS     (  972): releaseWL(5a5ceee): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/VoldConnector(  972): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
I/ActivityManager(  972): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5301 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
D/PMS     (  972): acquireWL(31f5221c): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4910 1000 null
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 5244): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,D/VoldConnector(  972): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 5244): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/System.err(  972): java.lang.Throwable: stack dump
W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36522187:true
,D/WifiController(  972): handleMessage: E msg.what=155656
,D/WifiController(  972): processMsg: DeviceActiveState,
D/WifiController(  972): processMsg: StaEnabledState
D/WifiController(  972): transitionTo: destState=ApStaDisabledState
D/WifiController(  972): handleMessage: new destination call exit/enter
D/WifiController(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null,
D/WifiController(  972): invokeExitMethods: DeviceActiveState
D/WifiController(  972): invokeExitMethods: StaEnabledState
D/WifiController(  972): moveTempStackToStateStack: i=0,j=1
D/WifiController(  972): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  972): invokeEnterMethods: ApStaDisabledState
I/jxcore-log( 4672): ****TEST TOOK:  5220  ms ****
I/jxcore-log( 4672): 
I/jxcore-log( 4672): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4672): 
D/WifiController(  972): handleMessage: X
,E/WifiStateMachine(  972): handleMessage: E msg.what=131084
E/WifiStateMachine(  972): processMsg: ConnectedState
E/WifiStateMachine(  972):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  972): processMsg: L2ConnectedState
E/WifiStateMachine(  972):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  972): processMsg: ConnectModeState
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
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
D/WifiPerfLock(  972): release()
E/WifiStateMachine(  972): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  972): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  972): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  972): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
W/InstanceID/Rpc( 5244): Found 10024
E/WifiStateMachine(  972): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  972): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1352): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1352): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1352): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1352): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1352): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/BluetoothAdapter( 4910): 689656078: getState(). Returning 13,
D/wpa_supplicant( 1352): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1352): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  972): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1352): Power_Mode_Type mode = 0
I/wpa_supplicant( 1352): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  972): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothInputDevice( 4910): BluetoothInputDevice()
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  972): setDhcpActive: false
,D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 9
V/NativeCrypto( 1930): Read error: ssl=0x55623dba10: I/O error during system call, Connection timed out
,D/libc    (  972): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  972): acquireWL(3373ba7f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1930 10024 WorkSource{10024 com.google.android.gms}
V/NativeCrypto( 1930): SSL shutdown failed: ssl=0x55623dba10: I/O error during system call, Broken pipe
E/WifiStateMachine(  972): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  972): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  972): NetworkAgent != null
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
V/NetworkPolicy(  972): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/BluetoothPan( 4910): BluetoothPan()
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
D/BluetoothManagerService(  972): registerStateChangeCallback+
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_3 (gone) T]
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 10
E/WifiTrafficPoller(  972):  packet count Tx=103 Rx=146
E/WifiTrafficPoller(  972): notifying of data activity 1
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  972): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/WIFI_ICON( 1218): WifiActivity: 1
D/libc    (  972): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  972): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_3 (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Forcing reevaluation
E/WifiStateMachine(  972): autoRoamSetBSSID any key="NG700"WPA_PSK
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiConfigStore(  972): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  972): QCOM Debug skip set_network part for security concern!
D/WifiDataStallTracker(  972): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  972): stopDataStallAlarm 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Validated
D/wpa_supplicant( 1352): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1352): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1352): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  972): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 13
,D/wpa_supplicant( 1352): wlan0: Control interface command 'SAVE_CONFIG'
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1352): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1352): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1352): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  972): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  972): invokeExitMethods: DriverStartedState
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  972): Unexpected BatchedScanResults :null
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  972): noteBatchedScanstop()
E/WifiStateMachine(  972): [1,451,341,460,029 ms] noteScanEnd no scan source
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  972): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService(  972): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  972): handleMessage: X
D/PMS     (  972): releaseWL(3373ba7f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/BluetoothMap( 4910): Create BluetoothMap proxy object
D/WifiP2pService(  972): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  972): NetworkAgent: NetworkAgent channel lost
D/WifiMonitor(  972): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@e994927
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 11
D/WifiScanningService(  972): SCAN_AVAILABLE : 1
D/WifiP2pService(  972): P2pDisablingState
D/RttService(  972): SCAN_AVAILABLE : 1
D/WifiDisplayController(  972): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiScanningService(  972): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
E/BluetoothMap( 4910): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WifiDisplayAdapter(  972): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  972):     Client/Owner: Client
D/WifiDisplayAdapter(  972):     GroupId: 
D/WifiDisplayAdapter(  972):     Passphrase: 
D/WifiDisplayAdapter(  972):     SessionId: 0
D/WifiDisplayAdapter(  972):     IP Address: }
D/RttService(  972): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): p2p socket connection lost
,D/WifiP2pService(  972): P2pDisabledState
V/AudioService(  972): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  972):     Client/Owner: Client
V/AudioService(  972):     GroupId: 
V/AudioService(  972):     Passphrase: 
V/AudioService(  972):     SessionId: 0
V/AudioService(  972):     IP Address: }
D/HtcEffectManagerBase(  972): onEventChanged id=5 status=false
D/HtcEffectManager(  972): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  972): convertEffect before=902
D/HtcEffectManager(  972): convertEffect after=902
E/WifiStateMachine(  972): handleMessage: E msg.what=131205
E/WifiStateMachine(  972): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  972):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
E/WifiStateMachine(  972): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  972): invokeExitMethods: WaitForP2pDisableState
,E/WifiStateMachine(  972): invokeExitMethods: SupplicantStartedState
D/WifiP2pService(  972): P2pDisabledState{ when=-1ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=1
D/WifiP2pService(  972): DefaultState{ when=-1ms what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/BluetoothManagerService(  972): registerStateChangeCallback+
E/WifiStateMachine(  972): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  972): Call handleNetworkDisconnect() in SupplicantStoppingState
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 12
D/BluetoothSap( 4910): BluetoothSap() call bindService
E/WifiStateMachine(  972): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
E/WifiStateMachine(  972): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1352): Power_Mode_Type mode = 0
I/wpa_supplicant( 1352): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  972): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  972): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  972): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/wpa_supplicant( 1352): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1352): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
,W/ContextImpl( 4910): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/WifiDataStallTracker(  972): setDhcpActive: false
,D/HtcBtWidget_BTWidgetProvider( 5301): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5301): updateWidget(context) for widget: 
D/VoldConnector(  972): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
W/ContextImpl( 5244): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/BluetoothPbap( 4910): BluetoothPbap()
D/BluetoothManagerService(  972): registerStateChangeCallback+
D/LocalBluetoothProfileManager( 4910): LocalBluetoothProfileManager construction complete
,D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  972): Registered receivers: 13
,D/BluetoothFtpService( 3627): ACTION_STATE_CHANGED: state: 13mHasStarted: true
,D/DockEventReceiver( 4910): finishStartingService: stopping service
E/BluetoothFtpService:RfcommSocketAcceptThread( 3627): Shutdown
D/BluetoothInputDevice( 4910): Proxy object connected
,D/BluetoothMasReceiver( 3627): Bluetooth STATE CHANGED to 13
,D/HidProfile( 4910): Bluetooth service connected
V/BluetoothSapReceiver( 3627): SapReceiver onReceive 
V/BluetoothSapReceiver( 3627): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 3627):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3627): startService = false
,D/BluetoothAdapter( 4910): 689656078: getState(). Returning 13
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
D/AuthorizationBluetoothService( 1930): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,D/BluetoothPan( 4910): BluetoothPAN Proxy object connected,
D/PanProfile( 4910): Bluetooth service connected
,D/SapServerProfile( 4910): Bluetooth service connected
D/PMS     (  972): releaseWL(31f5221c): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WISPrService( 4910): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiService(  972): New client listening to asynchronous messages
E/WifiTrafficPoller(  972): ADD_CLIENT: 7
,D/bt-btm  ( 3627): BTM_BleGetVendorCapabilities
,W/bt-btif ( 3627): ag scb idx 1 not allocated
,W/bt-btif ( 3627): ag scb idx 2 not allocated
E/bt-btif ( 3627): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3627): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3627): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3627): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3627): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3627): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3627): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3627): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3627): bta_gattc_deregister Deregister Failedm unknown client cif
,E/bt_userial_mct( 3627): pthread_join() FAILED result:3
,E/WifiStateMachine(  972): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false,
D/ConnectivityService(  972): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  972):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  972): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  972): Disconnected - quitting
D/Nat464Xlat(  972): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
E/WifiStateMachine(  972): stopping supplicant
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  972): QCOM Debug wifi_send_command "TERMINATE"
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1352): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/WIFI_ICON( 1218): updateWifiState: WIFI_STATE_CHANGED disabled
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524292
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1352): wlan0: Removing interface wlan0
D/ConnectivityService(  972): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SecurityController( 1218): onLost 100,
D/ConnectivityService(  972): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
E/WifiStateMachine(  972): setWifiState: disabling
D/NetworkManagementService(  972): Removing idletimer
D/wpa_supplicant( 1352): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
E/WifiStateMachine(  972): handleMessage: X
D/wpa_supplicant( 1352): TDLS: Tear down peers
D/wpa_supplicant( 1352): wpa_driver_nl80211_disconnect(reason_code=3)
E/WifiStateMachine(  972): handleMessage: E msg.what=131131
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 14
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  972):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  972): handleMessage: X
I/IntentController( 1218): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WISPrService( 4910): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4910): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/usbnet  (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  972):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WISPrService( 4910): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI    (  972): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WISPrService( 4910): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI    (  972):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  972): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/PMS     (  972): acquireWL(39d78114): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 972 1000 null
D/CSLegacyTypeTracker(  972): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  972): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  972): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/ConnectivityService(  972): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  972): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkPolicy(  972): ensureActiveMobilePolicyLocked()
D/Tethering(  972): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  972): acquireWL(338e3dbd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
E/ConnectivityService(  972): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Doma,ins: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{56} validated{true} created{true} explicitlySelected{false} }
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/WISPrService( 4910): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4910): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  972): releaseWL(338e3dbd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkPolicy(  972): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/Process (  972): killProcessQuiet, pid=4642
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
V/NetworkPolicy(  972): updateIfacesLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
I/ActivityManager(  972): Killing 4642:com.htc.android.worldclock/u0a90 (adj 15): empty #17
V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
D/NetworkManagementService(  972): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1218): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
,D/wpa_supplicant( 1352): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1352): wlan0: Deauthentication notification
D/wpa_supplicant( 1352): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1352): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1352): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1352): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1352): enter disconnect check
I/wpa_supplicant( 1352): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1352): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1352): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  972): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  972): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1352): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1352): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1352): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1352): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1352): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55ba234f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1352):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1352): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1352): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1352): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1352): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1352): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1352): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1352): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1352): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 1352): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1352): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1352): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1352): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1352): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1352): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1352): EAPOL: External notification - portValid=0
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  972): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine(  972): handleMessage: E msg.what=147460
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  972): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  972):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=64189
E/WifiStateMachine(  972): processMsg: DefaultState
,D/WifiMonitor(  972): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  972): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
E/WifiStateMachine(  972):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=64190
E/WifiStateMachine(  972): handleMessage: X
V/Tethering(  972): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  972): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  972): handleMessage: E msg.what=147462
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
E/WifiStateMachine(  972):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=64190  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=64191  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  972): handleMessage: X
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,E/cutils-trace( 5327): Error opening trace file: Permission denied (13)
,I/ActivityManager(  972): Recipient 4642
,D/CustomizationManager( 5327): ====startRecUseTime====,
D/htc.customization.log.level( 5327):  is 
W/CustomizationLogLevel( 5327): Level value is invalid, use default level 2
D/Tethering(  972): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  972): handleMessage: E msg.what=196614
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
E/WifiStateMachine(  972):  SupplicantStoppingState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  972): handleMessage: X
D/PMS     (  972): acquireWL(78e0fb2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 972 1000 null
,I/BatteryService(  972): n_update end
D/PMS     (  972): releaseWL(78e0fb2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  972): acquireWL(15f11b03): PARTIAL_WAKE_LOCK  NetworkStats 0x1 972 1000 null
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
E/WifiStateMachine(  972): handleMessage: E msg.what=131101
E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
E/WifiStateMachine(  972):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  972): processMsg: DefaultState
E/WifiStateMachine(  972):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  972): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  972): Default got CMD_TETHER_STATE_CHANGE
D/PMS     (  972): releaseWL(893aaa2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
E/WifiStateMachine(  972): handleMessage: X
,D/HtcPowerSaver(  972): updateBatteryInfo
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3627): Disconnected process message: 10, size: 0
,I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  972): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  972): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  972): BroadcastReceiver::onReceive-
D/UsbnetService(  972): BroadcastReceiver::onReceive+
D/NotificationService(  972): plugged=true pluggin=true
D/UsbnetService(  972): onReceive BATTERY_CHANGED
D/PMS     (  972): runPSCheck
D/UsbnetService(  972):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  972): Checking...
D/UsbnetService(  972): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  972): >> updateStatus
D/WifiController(  972): handleMessage: E msg.what=155652
,D/WifiController(  972): battery changed pluggedType: 2
D/WifiController(  972): processMsg: ApStaDisabledState
D/PMS     (  972): releaseWL(15f11b03): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiController(  972): processMsg: DefaultState
D/WifiController(  972): handleMessage: X
,V/NetworkPolicy(  972): updateNetworkEnabledLocked()
V/NetworkPolicy(  972): updateNotificationsLocked()
,I/HtcPowerSaver(  972): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  972): << updateStatus
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota,
,I/ActivityManager(  972): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=5373 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/CustomizationManager( 5327):  Read ACC file spent 0.052 (s)
,D/CIDMapFileReader( 5327): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5327): Parsing tag item name = HTC__102,
D/CIDMapFileReader( 5327): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5327): Parsing tag item name = HTC__032
D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/CIDMapFileReader( 5327): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5327): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5327): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5327): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5327): Parsing tag category name = system
I/CustomizationCIDLoader( 5327): Parsing tag category name = application
I/CustomizationCIDLoader( 5327): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5327): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5327): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5327): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5327): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5327): add string-array item, value = 42507
I/CustomizationCIDLoader( 5327): add string-array item, value = 21902
I/CustomizationCIDLoader( 5327): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5327): add string-array item, value = 23420
I/CustomizationCIDLoader( 5327): add string-array item, value = 22299
I/CustomizationCIDLoader( 5327): add string-array item, value = 24002
I/CustomizationCIDLoader( 5327): add string-array item, value = 23210
I/CustomizationCIDLoader( 5327): add string-array item, value = 23205
I/CustomizationCIDLoader( 5327): add string-array item, value = 23806
I/CustomizationCIDLoader( 5327): add string-array item, value = 23430
I/CustomizationCIDLoader( 5327): add string-array item, value = 23408
I/CustomizationCIDLoader( 5327): add string-array item, value = 27205
I/CustomizationCIDLoader( 5327): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5327): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5327):  Read CID file spent 0.098 (s)
D/CustomizationManager( 5327):  All configurations done spent 0.098 (s)
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/MdScPhnSt( 5001): [3e6.1.]  listen tmrbb8
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  972): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,E/wpa_supplicant( 1352): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1352): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1352): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1352): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1352): wlan0: Cancelling scan request
D/wpa_supplicant( 1352): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1352): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  972): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=26 dispatchEvent: BLACKLIST CLEAR 
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  972): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=29 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
,I/bt-btif ( 3627): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 3627): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3627): mProfilesStarted : true supportedProfileServices.length : 6
,D/HeadsetService( 3627): Received stop request...Stopping profile...
D/PackageManager(  972): deletePackageAsUser: pkg=com.example.hello, pid=5327, uid=2000 userid=0
D/wpa_supplicant( 1352): Remove interface wlan0 from radio phy0
,D/MdProvGlob( 5048): remove item 101 (p2d12in88) for 15:android.intent.action.ANY_DATA_STATE
D/BluetoothAdapterService( 3627): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa23b0d
D/MdScDataSum( 5001): [3e6.1.] summary 118:p2 ignore
D/HeadsetStateMachine( 3627): Exit Disconnected: -1
,D/BluetoothHeadset(  972): Proxy object disconnected
D/BluetoothHeadset( 1218): Proxy object disconnected
I/QuickSettingMiniLite( 1218): btListener.disconnect:HEADSET
D/BluetoothHeadset( 1434): Proxy object disconnected
D/BluetoothHeadset( 1434): Proxy object disconnected
,D/BluetoothHeadset( 1434): Proxy object disconnected
D/BluetoothPhoneService( 1434): BluetoothHeadset onServiceDisconnected
,D/BluetoothAdapterState( 3627): Stopping profile services that were post enabled
,D/BluetoothHeadset( 4289): Proxy object disconnected
D/NGFService( 4289): BluetoothHeadset onServiceDisconnected: main
,D/A2dpService( 3627): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3627): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa23b0d
D/MdProvGlob( 5048): remove item 101 (p2in6) for 15:android.intent.action.ANY_DATA_STATE
D/A2dpStateMachine( 3627): Exit Disconnected: -1
,D/HidService( 3627): Received stop request...Stopping profile...
D/BluetoothA2dp(  972): Proxy object disconnected
D/BluetoothAdapterService( 3627): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa23b0d
D/BluetoothInputDevice( 4910): Proxy object disconnected
D/HealthService( 3627): Received stop request...Stopping profile...
D/HidProfile( 4910): Bluetooth service disconnected
D/BluetoothA2dp( 4289): Proxy object disconnected
,D/NGFService( 4289): BluetoothA2dp onServiceDisconnected: main
D/BluetoothAdapterService( 3627): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa23b0d
,W/BluetoothHeadsetServiceJni( 3627): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3627): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 3627): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3627): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa23b0d
,D/BluetoothPan( 4910): BluetoothPAN Proxy object disconnected
D/PanProfile( 4910): Bluetooth service disconnected
D/BtGatt.DebugUtils( 3627): handleDebugAction() action=null
,I/ActivityManager(  972): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg,
I/ActivityManager(  972): Killing 4672:com.example.hello/u0a374 (adj 0): stop com.example.hello
,D/Process (  972): killProcessQuiet, pid=4672
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/BluetoothHeadset( 1218): Proxy not attached to service
,I/QuickSettingMiniLite( 1218): updateLiteState:no connect device!
,D/wpa_supplicant( 1352): nl80211: Remove monitor interface: refcount=0
I/ActivityManager(  972): Recipient 4672
D/wpa_supplicant( 1352): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
I/WindowState(  972): WIN DEATH: Window{17fd0b29 u0 com.example.hello/com.example.hello.MainActivity}
E/InputEventReceiver( 1386): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{242427dc uid 10374 pid 4672} (c)'
D/WifiService(  972): Client connection lost with reason: 4
,W/PackageSettings(  972): Skipping PackageSetting{222b8abe com.test.thalitest/10366} due to missing metadata
,W/ActivityManager(  972): Force removing ActivityRecord{3a049966 u0 com.example.hello/.MainActivity t8}: app died, no saved state
,D/BtGatt.GattService( 3627): Received stop request...Stopping profile...
D/BtGatt.GattService( 3627): stop()
D/BtGatt.AdvertiseManager( 3627): advertise clients cleared
,I/ActivityManager(  972): Force stopping com.example.hello appid=10374 user=0: pkg removed,
,D/wpa_supplicant( 1352): nl80211: Set mode ifindex 29 iftype 2 (STATION)
,D/wpa_supplicant( 1352): nl80211: Unsubscribe mgmt frames handle 0x888888dd32abe989 (mode change)
I/wpa_supplicant( 1352): htc_wext_command_deinit +
I/wpa_supplicant( 1352): htc_wext_command_deinit -
I/wpa_supplicant( 1352): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1352): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1352): p2p0: Removing interface p2p0
D/wpa_supplicant( 1352): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1352): TDLS: Tear down peers
D/wpa_supplicant( 1352): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1352): nl80211: Set p2p0 operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1352): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1352): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1352): EAPOL: External notification - portValid=0
D/Tethering(  972): interfaceLinkStateChanged wlan0, false
D/Tethering(  972): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  972): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  972): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor(  972): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  972): handleMessage: E msg.what=147458
,E/WifiStateMachine(  972): processMsg: SupplicantStoppingState
E/WifiStateMachine(  972):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 30 0
E/WifiStateMachine(  972): Supplicant connection lost
V/AlarmManager(  972): sending alarm PendingIntent{15ecaf3: PendingIntentRecord{2224a3b0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=62646, Int=259200000
,I/ActivityManager(  972): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5407 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  972): sending alarm PendingIntent{3d998229: PendingIntentRecord{14bb19ae com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1451341460591, Int=0
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/DotMatrix( 1310): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1310): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/ActivityManager(  972): Spurious death for ProcessRecord{2011234f 4672:com.example.hello/u0a374}, curProc for 4672: null
D/AccTypeManager( 1718): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  972): acquireWL(3e284adc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
D/BluetoothAdapterService( 3627): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa23b0d
W/GeofencerStateMachine( 1873): Ignoring removeGeofence because network location is disabled.
I/FeedHostManager( 1488): [onResume]
D/PMS     (  972): releaseWL(3e284adc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/FeedProviderManager( 1488): onResume
I/SocialFeedProvider( 1488): +onResume
I/SocialFeedProvider( 1488): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1488): -onResume
I/ConnectivityHelper( 1488): [getCurrentConnectionType] no network connection
W/SystemReader(  972): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1718): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/BluetoothHidServiceJni( 3627): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3627): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3627): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3627): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3627): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3627): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3627): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3627): Setting state to 10
I/BluetoothAdapterState( 3627): Bluetooth adapter state changed: 13-> 10
,D/MdProvGlob( 5048): remove item 101 (p2d2in268) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 5001): [3e6.a.] summary 118:p1 ignore
D/BluetoothManagerService(  972): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  972): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  972): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  972): Broadcasting onBluetoothStateChange(false) to 13 receivers.
I/BluetoothAdapterState( 3627): Entering OffState
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1434): onBluetoothStateChange: up=false
,W/ResourcesManager( 1434): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothA2dp(  972): onBluetoothStateChange: up=false
D/StatusBarManagerService(  972): setSystemUiVisibility(0x700)
D/BluetoothSap( 4910): onBluetoothStateChange on: false
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/InputMethodManagerService(  972): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/StatusBarManagerService(  972): hiding MENU key
,V/BluetoothSapService( 3627): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@3a746759
D/MdProvGlob( 5048): remove item 101 (p2in31) for 15:android.intent.action.ANY_DATA_STATE
,D/AccTypeManager( 1718): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/BluetoothHeadset( 4289): onBluetoothStateChange: up=false
D/BluetoothPbap( 4910): onBluetoothStateChange: up=false,
D/FindExtension( 1488): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/BluetoothHeadset( 1434): onBluetoothStateChange: up=false
,I/ThreadedRenderer( 1488): Defer allocateBuffers to drawing time
D/BluetoothHeadset( 1434): onBluetoothStateChange: up=false
I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/BluetoothPan( 4910): onBluetoothStateChange on: false
W/InputMethodManagerService(  972): Got RemoteException sending setActive(false) notification to pid 4672 uid 10374
D/StatusBarManagerService(  972): swetImeWindowStatus vis=0 backDisposition=0
D/BluetoothHeadset(  972): onBluetoothStateChange: up=false
D/BluetoothA2dp( 4289): onBluetoothStateChange: up=false
I/InputMethodManagerService(  972): Enable input method client, pid=1488
D/BluetoothMap( 4910): onBluetoothStateChange: up=false
E/ExternalAccountType( 1718): Unsupported attribute readOnly
E/BluetoothMap( 4910): 
E/BluetoothMap( 4910): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@3ce3e872
E/BluetoothMap( 4910): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 4910): 	,at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 4910): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 4910): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 4910): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 4910): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothInputDevice( 4910): onBluetoothStateChange: up=false
D/BluetoothManagerService(  972): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  972): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 4289): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3ce3e872
D/BluetoothAdapter( 4289): onBluetoothServiceDown: done
D/BluetoothAdapter( 1447): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@29638241
D/BluetoothAdapter( 1447): onBluetoothServiceDown: done
D/BluetoothAdapter( 4910): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1808e4c3
D/BluetoothAdapter( 4910): onBluetoothServiceDown: done
D/BluetoothAdapter( 3627): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@1ec47b09
D/BluetoothAdapter( 3627): onBluetoothServiceDown: done
D/BluetoothAdapter( 1218): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@26ff8775
D/BluetoothAdapter( 1218): onBluetoothServiceDown: done
D/BluetoothAdapter( 1434): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3a5c504
D/BluetoothAdapter( 1434): onBluetoothServiceDown: done
D/BluetoothAdapter( 1873): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@232042d2
D/BluetoothAdapter( 1873): onBluetoothServiceDown: done
D/BluetoothAdapter(  972): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@bcd7a0c
D/BluetoothAdapter(  972): onBluetoothServiceDown: done
D/BluetoothAdapter( 2387): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@692e00c
D/BluetoothAdapter( 2387): onBluetoothServiceDown: done
D/BluetoothManagerService(  972): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@bcd7a0c mBinding = false
D/BluetoothManagerService(  972): Sending unbind request.
D/BluetoothManagerService(  972): Bluetooth State Change Intent: 13 -> 10
I/bt-btif ( 3627): HAL bt_hal_cbacks->thread_evt_cb
D/NGFService( 4289): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 4289): Bluetooth Adapter: OFF
I/IntentController( 1218): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/LocalBluetoothProfileManager( 4910): setBluetoothStateOff
W/BluetoothEventManager( 4910): unregister mProfileBroadcastReceiver fail
D/PhoneApp( 1434): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/art     ( 3627): System.exit called, status: 0
D/TetherPref( 4910): persistRestoreBluetoothState false
D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,I/Gmail   ( 5373): getAccountsCursor
,D/BluetoothAdapter( 1218): 662386292: getState() :  mService = null. Returning STATE_OFF
,W/ResourcesManager(  972): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/QuickSettingBluetooth( 1218): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,W/PackageManager(  972): Unable to load service info ResolveInfo{353b02c3 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  972): Recipient 3627
I/ImageRamCache( 5407): create image Cache, size: 31457280.
I/ImageRamCache( 5407): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5407): create image Cache, size: 31457280.
D/MdProvGlob( 5048): remove item 101 (p2d9in130) for 15:android.intent.action.ANY_DATA_STATE
V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  972): Process com.android.bluetooth (pid 3627) has died
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
W/ActivityManager(  972): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 11000ms
,I/FeedSettings( 5407): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5407): GroupBudget 0.500000 0.380000
I/FeedSettings( 5407): GroupBudget 60 45 15
,I/BroadcastQueue(  972): Schedule to resend BroadcastRecord{167e804 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=972 callingUid=1000} for ResolveInfo{390731ed com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,I/Prism.ExternalStringMa_( 5407): changeLocale(): en_GB
,I/ActivityManager(  972): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5440 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,I/Prism.AllAppsOptionsMa_( 5407): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5407): loadGridSize() with Alternative
,I/art     (  972): Explicit concurrent mark sweep GC freed 36921(2MB) AllocSpace objects, 4(144KB) LOS objects, 33% free, 16MB/24MB, paused 5.812ms total 256.219ms
W/asset   (  972): Copying FileAsset 0x5562654bb0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,W/GAV2    ( 5373): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SocialManager[SocialBiLogHelper]( 5407): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 5407): last commit ulog time 1451195462404
I/SocialManager[SocialBiLogHelper]( 5407): do commit ulog
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5373, uid=10106, userID:0
,W/ActivityManager(  972): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ResourcesManager( 5440): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Gmail   ( 5373): Observing account changes for notifications
,I/ActivityManager(  972): Killing 4712:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4712
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/wpa_ctrl(  972): [wpa_ctrl_close] ctrl=0x5562520000
I/wpa_ctrl(  972): [wpa_ctrl_close] ctrl=0x55625201f0
,D/JobSchedulerService(  972): Receieved: android.intent.action.PACKAGE_REMOVED,
,I/ActivityManager(  972): Recipient 4712,
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
D/AdapterServiceConfig( 5440): Adding HeadsetService
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5373, uid=10106, userID:0
D/AdapterServiceConfig( 5440): Adding A2dpService
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5373, uid=10106, userID:0
D/AdapterServiceConfig( 5440): Adding HidService
D/PMS     (  972): acquireWL(76984c7): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4910 1000 null
E/WifiStateMachine(  972): setWifiState: disabled
W/ContextImpl( 4910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/AdapterServiceConfig( 5440): Adding HealthService
D/AdapterServiceConfig( 5440): Adding PanService
D/AdapterServiceConfig( 5440): Adding GattService
D/WifiStateMachine(  972): Enter handleNetworkDisconnect
E/WifiStateMachine(  972): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
V/BluetoothPbapReceiver( 5440): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5440): ***********state = 10
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL false Token 15 num clients 6
E/WifiTrafficPoller(  972): TRAFFIC_STATS_POLL false Token 15 num clients 6
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
E/BluetoothMasService( 5440): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/NfcHandover( 1447): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
E/WifiStateMachine(  972): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  972): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/BluetoothMasService( 5440): Add permission for SmsProvider.
,W/System.err(  972): java.lang.Throwable: stack dump
D/BluetoothManagerService(  972): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bf1421d:true
,W/System.err(  972): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  972): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  972): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
,V/BluetoothMasService( 5440): Starting MAS instances
,D/BluetoothAdapter( 5440): 463592952: getState() :  mService = null. Returning STATE_OFF
,I/MailMessageReceiver( 5440): reg:com.android.bluetooth.btservice.AdapterApp@3b5d42d1 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2fb75136
I/ActivityManager(  972): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=5472 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
D/WifiStateMachine(  972): Exit handleNetworkDisconnect,
E/WifiStateMachine(  972): [MLHD] Error! unhandled message 6 { when=-518ms what=147458 arg1=30 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  972): acquireWL(374c2c92): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 972 1000 null
E/WifiStateMachine(  972): transitionTo: destState=InitialState
E/WifiStateMachine(  972): handleMessage: new destination call exit/enter
E/WifiStateMachine(  972): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  972): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  972): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  972): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  972): invokeEnterMethods: InitialState
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/MailManager( 5440): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2fb75136
D/TaskPersister(  972): removeObsoleteFile: deleting file=8_task.xml
V/EmailUtils( 5440): Manager Instance is not NULL
D/PMS     (  972): releaseWL(76984c7): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
E/WifiTrafficPoller(  972): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/PMS     (  972): acquireWL(11d4148c): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4910 1000 null
W/Settings( 5207): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/IntentController( 1218): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
W/Settings( 1873): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  972): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5493 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/art     (  409): Explicit concurrent mark sweep GC freed 8656(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 225us total 33.828ms
,D/DockEventReceiver( 4910): finishStartingService: stopping service
,D/PMS     (  972): releaseWL(11d4148c): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WISPrService( 4910): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4910): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1218): updateWifiState: WIFI_STATE_CHANGED disabled
D/HtcBtWidget_BTWidgetProvider( 5301): onBTStateChanged() for widget: 
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/HtcBtWidget_BTWidgetProvider( 5301): updateWidget(context) for widget: 
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/AndroidHttpClient( 5069): Leak found
E/AndroidHttpClient( 5069): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5069): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5069): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5069): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5069): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5069): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5069): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5069): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5069): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5069): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5069): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5069): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5069): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5069): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5069): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5069): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5069): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/Gmail   ( 5373): Error finding the version of the Email provider.....
E/Gmail   ( 5373): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5373): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5373): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5373): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5373): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5373): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5373): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5373): We do not support migrating this version of the Email provider.
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 242us total 31.980ms,
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=5373, uid=10106, userID:0,
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=5373, uid=10106, userID:0
I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 311us total 23.100ms
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=5373, uid=10106, userID:0
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=5373, uid=10106, userID:0,
I/Gmail   ( 5373): getAccountsCursor
I/QuickSettingWifi( 1218): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  972): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=5524 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5373, uid=10106, userID:0,
D/HtcAdjCursorFactory( 5493): Set CursorWindow size to: 4194304 KB, Tid: 5517
I/ImageRamCache( 5472): create image Cache, size: 31457280.
I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5373, uid=10106, userID:0
,I/ImageRamCache( 5472): [resize] ImageRamCache resized to: 30Mb.
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ImageRamCache( 5472): create image Cache, size: 31457280.
,V/SocialManagerService( 1585): getDataSources
,I/SocialManagerService( 1585): plugin added: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1585): plugin added: com.google
I/SocialManagerService( 1585): plugin added: com.htc.opensense.htcnews
I/SocialManagerService( 1585): plugin added: com.htc.club
I/SocialManagerService( 1585): plugin added: com.twitter.android.auth.login
I/SocialManagerService( 1585): plugin added: com.htc.linkedin
I/SocialManagerService( 1585): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1585): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1585): plugin added: com.facebook.auth.login
I/SocialManagerService( 1585): plugin added: com.htc.drive.activator
I/SocialManagerService( 1585): plugin added: com.htc.venuesrecommend
I/SocialManagerService( 1585): device total memory: 1842M
I/SocialManagerService( 1585): groupAccounts
V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 5373): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1910b90f that was originally bound here
E/ActivityThread( 5373): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1910b90f that was originally bound here
E/ActivityThread( 5373): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 5373): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 5373): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 5373): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 5373): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5373): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 5373): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 5373): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 5373): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 5373): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 5373): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 5373): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 5373): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 5373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5373): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 5373): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  972): Unbind failed: could not find connection for android.os.BinderProxy@1c986354
I/FeedSettings( 5472): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
,I/FeedSettings( 5472): GroupBudget 0.500000 0.380000
I/FeedSettings( 5472): GroupBudget 60 45 15
W/OpenGLRenderer( 1488): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/Prism.ExternalStringMa_( 5472): changeLocale(): en_GB
,D/EmailUtils( 5440): ============NULL aList========
,V/EmailUtils( 5440): <-getEmailAccountIdList
V/BluetoothMasService( 5440): onCreate: mIsEmailEnabled: true
,D/Process (  972): killProcessQuiet, pid=4822
,I/ActivityManager(  972): Killing 4822:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/Prism.AllAppsOptionsMa_( 5472): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 5472): loadGridSize() with Alternative
,E/SocialManagerService( 1585): cannot find this plugin service: com.htc.drive.activator
E/SocialManagerService( 1585): error when get process name! process name is null!
E/SocialManagerService( 1585): skip binding the plugin without process namecom.htc.drive.activator
,I/SocialManagerService( 1585): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to pending queue!
I/SocialManagerService( 1585): add com.google to pending queue!
I/SocialManagerService( 1585): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1585): add com.htc.club to pending queue!
I/SocialManagerService( 1585): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1585): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1585): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1585): add com.facebook.auth.login to pending queue!
I/SocialManagerService( 1585): add com.htc.sense.socialnetwork.instagram to pending queue!
I/SocialManagerService( 1585): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1585): consume pending plugin session
I/SocialManagerService( 1585): add pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin to process map!
V/SocialManagerService( 1585): initiating bind to plugin type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
I/SocialManagerService( 1585): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connecting, adding msg, has message?true
,E/SQLiteLog( 5373): (283) recovered 864 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,E/SQLiteDBG( 5373): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gm/databases/XX@YY, handle: 0x5562326800
I/ActivityManager(  972): Recipient 4822
E/GmailIS ( 5373): Error handling intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gm/.GmailIntentService (has extras) }
E/GmailIS ( 5373): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/GmailIS ( 5373): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/GmailIS ( 5373): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/GmailIS ( 5373): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/GmailIS ( 5373): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/GmailIS ( 5373): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
E/GmailIS ( 5373): 	at com.google.android.gm.provider.bx.ac(SourceFile:1889)
E/GmailIS ( 5373): 	at com.google.android.gm.provider.bx.<init>(SourceFile:1313)
E/GmailIS ( 5373): 	at com.google.android.gm.provider.bx.a(SourceFile:993)
E/GmailIS ( 5373): 	at com.google.android.gm.provider.bx.b(SourceFile:1027)
E/GmailIS ( 5373): 	at com.google.android.gm.GmailIntentService.a(SourceFile:2276)
E/GmailIS ( 5373): 	at com.google.android.gm.GmailIntentService.onHandleIntent(SourceFile:73)
E/GmailIS ( 5373): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/GmailIS ( 5373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/GmailIS ( 5373): 	at android.os.Looper.loop(Looper.java:155)
E/GmailIS ( 5373): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Gmail   ( 5373): getAccountsCursor
,E/SQLiteDatabase( 5373): Failed to open database '/data/data/com.google.android.gm/databases/XX@YY'.
E/SQLiteDatabase( 5373): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5373): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5373): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5373): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5373): 	at com.google.android.gm.provider.bx.<init>(SourceFile:11961)
E/SQLiteDatabase( 5373): 	at com.google.android.gm.provider.bx.a(SourceFile:993)
E/SQLiteDatabase( 5373): 	at com.google.android.gm.provider.ck.run(SourceFile:1051)
E/SQLiteDatabase( 5373): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5373): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5373): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5373): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/GAV2    ( 5373): Thread[MailEngine creation,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,E/AndroidRuntime( 5373): FATAL EXCEPTION: MailEngine creation,
E/AndroidRuntime( 5373): Process: com.google.android.gm, PID: 5373
E/AndroidRuntime( 5373): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
,E/AndroidRuntime( 5373): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5373): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5373): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5373): 	at com.google.android.gm.provider.bx.<init>(SourceFile:11961)
E/AndroidRuntime( 5373): 	at com.google.android.gm.provider.bx.a(SourceFile:993)
E/AndroidRuntime( 5373): 	at com.google.android.gm.provider.ck.run(SourceFile:1051)
E/AndroidRuntime( 5373): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5373): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5373): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5373): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SocialManagerService( 1585): add com.google to process map!,
V/SocialManagerService( 1585): initiating bind to plugin type com.google
I/SocialManagerService( 1585): com.google connecting, adding msg, has message?true
,I/SocialManagerService( 1585): add com.twitter.android.auth.login to process map!
I/ActivityManager(  972): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.googleplus/com.htc.plugin.googleplus.GooglePlusSocialPluginService: pid=5558 uid=10021 gids={50021, 9997, 3003, 1028, 1015, 1023} abi=arm64-v8a
V/SocialManagerService( 1585): initiating bind to plugin type com.twitter.android.auth.login
I/SocialManagerService( 1585): com.twitter.android.auth.login connecting, adding msg, has message?true,
I/SocialManagerService( 1585): add com.htc.club to process map!,
V/SocialManagerService( 1585): initiating bind to plugin type com.htc.club
I/SocialManagerService( 1585): com.htc.club connecting, adding msg, has message?true
I/SocialManagerService( 1585): pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin connected, removed msg, has message?false
V/GLSActivity( 1930): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothMasReceiver( 5440): Bluetooth STATE CHANGED to 10
,D/BlinkFeedPluginService( 2387): Set icon to :2130837679,
D/BlinkFeedPluginService( 2387): class com.htc.blinkfeed.provider.DummyIdentityProvider
D/BlinkFeedPluginService( 2387): Not filterable
D/SocialManagerService( 1585): handling plugin: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin set result in bg
I/SocialManagerService( 1585): remove account type: pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin from process map!
I/SocialManagerService( 1585): remove process: pl.k2.droidoaudioteka from process map!
,I/ActivityManager(  972): Start proc com.htc.club for service com.htc.club/com.htc.blinkfeed.service.BlinkFeedPluginService: pid=5575 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/SocialManagerService( 1585): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1585): initiating bind to plugin type com.htc.opensense.htcnews
,I/SocialManagerService( 1585): com.htc.opensense.htcnews connecting, adding msg, has message?true
E/ActivityManager(  972): App crashed! Process: com.google.android.gm
V/BluetoothMasService( 5440): onDestroy: mIsEmailEnabled: true
,I/SocialManagerService( 1585): add com.htc.linkedin to process map!
V/SocialManagerService( 1585): initiating bind to plugin type com.htc.linkedin
I/SocialManagerService( 1585): com.htc.linkedin connecting, adding msg, has message?true
I/SocialManagerService( 1585): add com.htc.socialnetwork.rss.octopus to process map!
V/SocialManagerService( 1585): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1585): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
V/SocialManagerService( 1585): on plugin completed! plugin session type pl.k2.droidoaudioteka.blinkfeed.AudiotekaPlugin
,I/ActivityManager(  972): Killing 4857:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  972): killProcessQuiet, pid=4857
V/BluetoothSapReceiver( 5440): SapReceiver onReceive 
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
V/BluetoothSapReceiver( 5440): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5440):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5440): startService = false
,E/DropBoxManagerService(  972): Can't write: system_app_crash,
E/DropBoxManagerService(  972): java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
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
,W/System  ( 5407): DiskLruCache /data/data/com.htc.launcher/cache/http is corrupt: /data/data/com.htc.launcher/cache/http/journal: open failed: EROFS (Read-only file system), removing,
,E/SQLiteDatabase( 5472): Failed to open database '/data/data/com.htc.launcher/databases/BiLogClient'.,
E/SQLiteDatabase( 5472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5472): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5472): 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:155)
E/SQLiteDatabase( 5472): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5472): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5472): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 5472): FATAL EXCEPTION: IntentService[BiLogUploadService]
E/AndroidRuntime( 5472): Process: com.htc.launcher:biclient, PID: 5472
E/AndroidRuntime( 5472): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5472): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5472): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5472): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5472): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5472): 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:155)
E/AndroidRuntime( 5472): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5472): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5472): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  972): Recipient 4857
,D/StatusBarManagerService(  972): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  972): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  972): hiding MENU key
,E/ActivityManager(  972): App crashed! Process: com.htc.launcher:biclient,
,D/ErrorReport(  972): HtcErrorReportManager Begin---add error logs to dropbox,
I/SocialManagerService( 1585): com.htc.opensense.htcnews connected, removed msg, has message?false
I/SocialManagerService( 1585): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1585): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1585): add com.htc.venuesrecommend to process map!
V/SocialManagerService( 1585): initiating bind to plugin type com.htc.venuesrecommend
I/SocialManagerService( 1585): com.htc.venuesrecommend connecting, adding msg, has message?true
W/System.err(  972): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  972): 	,at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
I/SocialManagerService( 1585): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
,D/LocationSocialPlugin( 5407): onBind
,I/SocialManagerService( 1585): consume pending plugin session
I/SocialManagerService( 1585): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1585): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/StreamPluginService( 5407): getDataSources start
D/Process (  972): killProcessQuiet, pid=4932
I/ActivityManager(  972): Killing 4932:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/SocialManagerService( 1585): handling plugin: com.htc.opensense.htcnews set result in bg
D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
W/System.err(  972): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
I/SocialManagerService( 1585): remove account type: com.htc.opensense.htcnews from process map!
W/System.err(  972): 	at java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  972): com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  972): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  972): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  972): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  972): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  972): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  972): 	at 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  972): 	at libcore.io.Posix.open(Native Method)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  972): com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)	at 
W/System.err(  972): libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  972): 	... 	at 12 more
W/System.err(  972): android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  972): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  972): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  972): 	at libcore.io.Posix.open(Native Method)
W/System.err(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  972): 	... 14 more
,W/System.err(  972): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  972): Recipient 4932
,D/AuthorizationBluetoothService( 1930): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
I/SocialManagerService( 1585): com.htc.venuesrecommend connected, removed msg, has message?false
I/SocialManagerService( 1585): com.htc.club connected, removed msg, has message?false
V/SocialManagerService( 1585): on plugin completed! plugin session type com.htc.opensense.htcnews
I/SocialManagerService( 1585): consume pending plugin session
I/SocialManagerService( 1585): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1585): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1585): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
I/SocialManagerService( 1585): remove account type: com.htc.socialnetwork.rss.octopus from process map!
V/SocialManagerService( 1585): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1585): consume pending plugin session
I/SocialManagerService( 1585): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1585): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/LocationIdentityProvider( 5407): is_approved false
D/LocationSocialPlugin( 5407): account null
,E/ErrorReport(  972): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  972): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1451341462000.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  972): ,	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  972): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  972): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  972): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  972): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  972): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  972): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  972): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  972): 	... 4 more
D/LocationSocialPlugin( 5407): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
,D/SocialManagerService( 1585): handling plugin: com.htc.venuesrecommend set result in bg
I/SocialManagerService( 1585): remove account type: com.htc.venuesrecommend from process map!
I/SocialManagerService( 1585): remove process: com.htc.sense.news from process map!
,V/SocialManagerService( 1585): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1585): consume pending plugin session
I/SocialManagerService( 1585): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1585): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
,W/ActivityManager(  972): Can't addPackageDependency on system process
,D/BlinkFeedPluginService( 5575): Set icon to :2130837554
D/BlinkFeedPluginService( 5575): URI:
D/BlinkFeedPluginService( 5575): Not filterable
,D/SocialManagerService( 1585): handling plugin: com.htc.club set result in bg
I/SocialManagerService( 1585): remove account type: com.htc.club from process map!
I/SocialManagerService( 1585): remove process: com.htc.club from process map!
D/Tethering(  972): interfaceRemoved wlan0
E/Tethering(  972): attempting to remove unknown iface (wlan0), ignoring
,V/SocialManagerService( 1585): on plugin completed! plugin session type com.htc.club,
I/SocialManagerService( 1585): consume pending plugin session
I/SocialManagerService( 1585): skip to add com.facebook.auth.login, plugin per process full!
I/SocialManagerService( 1585): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/Process (  972): killProcessQuiet, pid=4953
I/ActivityManager(  972): Killing 4953:com.android.settings:remote/1000 (adj 15): empty #17
,D/Process (  972): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/LinkedIn( 5558): contentprovider oncreate getReadableDatabase
,E/SQLiteDatabase( 5558): Failed to open database '/data/data/com.htc.sense.linkedin/databases/linkedin.db'.,
E/SQLiteDatabase( 5558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5558): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5558): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5558): 	at com.htc.sense.linkedin.provider.a.a(Unknown Source)
E/SQLiteDatabase( 5558): 	at com.htc.sense.linkedin.provider.a.doInBackground(Unknown Source)
E/SQLiteDatabase( 5558): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5558): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5558): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5558): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5558): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5558): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5558): Couldn't open linkedin.db for writing (will try read-only):
E/SQLiteOpenHelper( 5558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5558): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5558): 	at com.htc.sense.linkedin.provider.a.a(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at com.htc.sense.linkedin.provider.a.doInBackground(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 5558): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5558): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 5558): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5558): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5558): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 5558): Opened linkedin.db in read-only mode
,D/Tethering(  972): interfaceLinkStateChanged p2p0, false,
D/Tethering(  972): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  972): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  972): Recipient 4953,
,D/Tethering(  972): interfaceRemoved p2p0,
E/Tethering(  972): attempting to remove unknown iface (p2p0), ignoring
,D/LocationManagerService(  972): getProviders()=[passive],
,I/Prism.ItemManager( 1488): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1488): loadItems() com.htc.launcher.pageview.WidgetManager@13e31637 +
I/Prism.WidgetManager( 1488): onLoadItems() +
,I/art     ( 1930): Explicit concurrent mark sweep GC freed 9973(559KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.244ms total 56.253ms
,W/ResourcesManager( 1488): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  972): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5617 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=5524, uid=10085, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=5524, uid=10085, userID:0
,I/PackageManager(  972):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=5524, uid=10085, userID:0
,D/GooglePlusSocialPluginService( 5558): Bind
,I/SocialManagerService( 1585): com.google connected, removed msg, has message?false,
,I/GooglePlusSocialPluginService( 5558): getDataSources start
,I/SocialManagerService( 1585): com.twitter.android.auth.login connected, removed msg, has message?false
,E/SQLiteDatabase( 5558): Failed to open database '/data/data/com.htc.sense.socialnetwork.googleplus/databases/googleplus.db'.
E/SQLiteDatabase( 5558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5558): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5558): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5558): 	at com.htc.socialnetwork.googleplus.provider.GooglePlusProvider.query(Unknown Source)
E/SQLiteDatabase( 5558): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5558): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5558): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5558): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5558): 	at com.htc.socialnetwork.googleplus.b.a.c(Unknown Source)
E/SQLiteDatabase( 5558): 	at com.htc.socialnetwork.googleplus.b.a.d(Unknown Source)
E/SQLiteDatabase( 5558): 	at com.htc.plugin.googleplus.GooglePlusSocialPluginService$a.a(Unknown Source)
E/SQLiteDatabase( 5558): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteDatabase( 5558): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 5558): Couldn't open googleplus.db for writing (will try read-only):
E/SQLiteOpenHelper( 5558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5558): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5558): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLoc,ked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5558): 	at com.htc.socialnetwork.googleplus.provider.GooglePlusProvider.query(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5558): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5558): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5558): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5558): 	at com.htc.socialnetwork.googleplus.b.a.c(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at com.htc.socialnetwork.googleplus.b.a.d(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at com.htc.plugin.googleplus.GooglePlusSocialPluginService$a.a(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 5558): Opened googleplus.db in read-only mode
I/GooglePlusSocialPluginService( 5558): getDataSources end
E/SQLiteDatabase( 5558): Failed to open database '/data/data/com.htc.sense.socialnetwork.twitter/databases/htcchirp.db'.
E/SQLiteDatabase( 5558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5558): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5558): 	at com.htc.htctwitter.TwitterProvider.query(Unknown Source)
E/SQLiteDatabase( 5558): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5558): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5558): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5558): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5558): 	at com.htc.htctwitter.b.d.<init>(Unknown Source)
E/SQLiteDatabase( 5558): 	at com.htc.htctwitter.d.d(Unknown Source)
E/SQLiteDatabase( 5558): 	at com.htc.plugin.twitter.TwitterSocialPluginService$a.a(Unknown Source)
E/SQLiteDatabase( 5558): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteDatabase( 5558): 	at java.lang.Thread.run(Thread.java:818)
D/SocialManagerService( 1585): handling plugin: com.google set result in bg
D/LinkedIn( 5558): service onBind
I/SocialManagerService( 1585): remove account type: com.google from process map!
E/SQLiteOpenHelper( 5558): Couldn't open htcchirp.db for writing (will try read-only):
E/SQLiteOpenHelper( 5558): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5558): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5558): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5558): 	at com.htc.htctwitter.TwitterProvider.query(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5558): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5558): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5558): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5558): 	at com.htc.htctwitter.b.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at com.htc.htctwitter.d.d(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at com.htc.plugin.twitter.TwitterSocialPluginService$a.a(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at com.htc.lib2.opensense.social.e.run(Unknown Source)
E/SQLiteOpenHelper( 5558): 	at java.lang.Thread.run(Thread.java:818)
V/SocialManagerService( 1585): on plugin completed! plugin session type com.google
I/SocialManagerService( 1585): consume pending plugin session
I/SocialManagerService( 1585): add com.facebook.auth.login to process map!
V/SocialManagerService( 1585): initiating bind to plugin type com.facebook.auth.login
I/SocialManagerService( 1585): com.facebook.auth.login connecting, adding msg, has message?true
W/SQLiteOpenHelper( 5558): Opened htcchirp.db in read-only mode
D/GooglePlusSocialPluginService( 5558): Unbind
I/SocialManagerService( 1585): com.htc.linkedin connected, removed msg, has message?false
I/SocialManagerService( 1585): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/SocialManagerService( 1585): handling plugin: com.twitter.android.auth.login set result in bg
I/SocialManagerService( 1585): remove account type: com.twitter.android.auth.login from process map!
V/SocialManagerService( 1585): on plugin completed! plugin session type com.twitter.android.auth.login
I/SocialManagerService( 1585): consume pending plugin session
I/SocialManagerService( 1585): add com.htc.sense.socialnetwork.instagram to process map!
V/SocialManagerService( 1585): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1585): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
I/SocialManagerService( 1585): com.facebook.auth.login connected, removed msg, has message?false
D/SocialManagerService( 1585): handling plugin: com.htc.linkedin set result in bg
I/SocialManagerService( 1585): remove account type: com.htc.linkedin from process map!
E/TaskRunnerFutureTask( 5524): Unchecked exception running task: VelvetBackgroundTasksImpl[schedule]
E/TaskRunnerFutureTask( 5524): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR attemptedsearchhistory
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.search.core.bf.H(SearchBackgroundTaskFactory.java:351)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.velvet.VelvetBackgroundTasksImpl.bPf(VelvetBackgroundTasksImpl.java:245)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.velvet.VelvetBackgroundTasksImpl$1.run(VelvetBackgroundTasksImpl.java:65)
E/TaskRunnerFutureTask( 5524): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/TaskRunnerFutureTask( 5524): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/TaskRunnerFutureTask( 5524): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/TaskRunnerFutureTask( 5524): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/TaskRunnerFutureTask( 5524): 	at java.lang.Thread.run(Thread.java:818)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/TaskRunnerFutureTask( 5524): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR attemptedsearchhistory
E/TaskRunnerFutureTask( 5524): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/TaskRunnerFutureTask( 5524): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
E/TaskRunnerFutureTask( 5524): 	... 10 more
E/TaskRunnerFutureTask( 5524): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR attemptedsearchhistory
E/TaskRunnerFutureTask( 5524): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/TaskRunnerFutureTask( 5524): 	... 5 more
E/TaskRunnerFutureTask( 5524): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/TaskRunnerFutureTask( 5524): 	at java.io.File.createNewFile(File.java:941)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/TaskRunnerFutureTask( 5524): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/TaskRunnerFutureTask( 5524): 	... 9 more
E/TaskRunnerFutureTask( 5524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/TaskRunnerFutureTask( 5524): 	at libcore.io.Posix.open(Native Method)
E/TaskRunnerFutureTask( 5524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/TaskRunnerFutureTask( 5524): 	at java.io.File.createNewFile(File.java:934)
E/TaskRunnerFutureTask( 5524): 	... 11 more
V/SocialManagerService( 1585): on plugin completed! plugin session type com.htc.linkedin
,I/ActivityManager(  972): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5656 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a

```
