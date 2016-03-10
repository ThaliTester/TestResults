#### Test 60124347d1a8dac_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  945): Recipient 3925
--------- beginning of main
D/Finsky  ( 5956): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/OcrUtils( 4493): Updating ocr activity enabled=false
,D/Finsky  ( 5956): [1] DailyHygiene.reschedule: Giving up. (failures=6)
I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=4493, uid=10024, userID:0
D/PMS     (  945): releaseWL(24ee087e): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
D/Process (  945): killProcessQuiet, pid=5736
I/ActivityManager(  945): Killing 5736:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  945): releaseWL(375e2e8a): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
D/DeviceConnectionService( 1777): client connected with version: 7571000
I/ActivityManager(  945): Recipient 5736
D/Process (  945): killProcessQuiet, pid=5686
I/ActivityManager(  945): Killing 5686:com.htc.updater/u0a84 (adj 15): empty #18
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiStateMachine(  945): handleMessage: E msg.what=131155
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=10.7, 0.0, 0.0  rx=15.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1625822997] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=10.7, 0.0, 0.0  rx=15.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625822998] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.33 txretriesrate=0.00 rxrate=8.14 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  945):  isHighRSSI       ---> score=65
I/ActivityManager(  945): Recipient 5686
I/Prism.ItemManager( 1620): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1620): loadItems() com.htc.launcher.pageview.WidgetManager@374cfd15 +
I/Prism.WidgetManager( 1620): onLoadItems() +
E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  945):  packet count Tx=186 Rx=224
E/WifiTrafficPoller(  945): notifying of data activity 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/HtcModeClient( 3303): handler message = 4011
E/HtcModeClient( 3303): Check connection and retry 7 times.
E/WifiStateMachine(  945): handleMessage: X
V/AlarmManager(  945): sending alarm PendingIntent{eb8d2e: PendingIntentRecord{8e350cf com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457619736234, Int=0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/SystemUpdateService( 4493): onDestroy
V/AlarmManager(  945): sending alarm PendingIntent{141b14e7: PendingIntentRecord{21907894 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1457619729122, Int=20000
I/GCoreUlr( 1777): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
I/GAV2    ( 5790): Thread[GAThread,5,main]: No campaign data found.
E/cutils-trace( 6162): Error opening trace file: Permission denied (13)
I/GCoreUlr( 1777): DispatchingService.onCreate()
D/PMS     (  945): acquireWL(19828ac7): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.copresence.service.ProximitySettingInjectorService, state=2, flag=1, pid=1777, uid=10024, userID:0
I/iu.UploadsManager( 4493): End new media; added: 0, uploading: 0, time: 56 ms
I/GCoreUlr( 1777): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
D/CustomizationManager( 6162): ====startRecUseTime====
D/htc.customization.log.level( 6162):  is 
W/CustomizationLogLevel( 6162): Level value is invalid, use default level 2
D/CustomizationManager( 6162):  Read ACC file spent 0.037 (s)
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6162): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6162): Parsing tag category name = system
I/CustomizationCIDLoader( 6162): Parsing tag category name = application
I/CustomizationCIDLoader( 6162): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6162): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6162): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6162): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6162): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6162): add string-array item, value = 42507
I/CustomizationCIDLoader( 6162): add string-array item, value = 21902
I/CustomizationCIDLoader( 6162): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6162): add string-array item, value = 23420
I/CustomizationCIDLoader( 6162): add string-array item, value = 22299
I/CustomizationCIDLoader( 6162): add string-array item, value = 24002
I/CustomizationCIDLoader( 6162): add string-array item, value = 23210
I/CustomizationCIDLoader( 6162): add string-array item, value = 23205
I/CustomizationCIDLoader( 6162): add string-array item, value = 23806
I/CustomizationCIDLoader( 6162): add string-array item, value = 23430
I/CustomizationCIDLoader( 6162): add string-array item, value = 23408
I/CustomizationCIDLoader( 6162): add string-array item, value = 27205
I/CustomizationCIDLoader( 6162): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6162):  Read CID file spent 0.082 (s)
D/CustomizationManager( 6162):  All configurations done spent 0.082 (s)
I/ActivityManager(  945): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6162 on display 0
E/Prism.WidgetManager( 1620): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1620): onLoadItems() -
I/Prism.ItemManager( 1620): loadItems() com.htc.launcher.pageview.WidgetManager@374cfd15 -
D/PMS     (  945): acquireHCC(3fc7e8f4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 945 1000 null
D/PMS     (  945): acquireHCC(31d0b81d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 945 1000 null
I/art     ( 1919): Explicit concurrent mark sweep GC freed 10040(531KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 808us total 38.061ms
W/asset   (  945): Copying FileAsset 0x55a6e7af50 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/GCoreUlr( 1777): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  945): acquireWL(cf4a060): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 945 1000 null
D/PMS     (  945): acquireWL(96b9dde): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
I/AnimationUtil(  945): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1620): [onPause]
I/FeedProviderManager( 1620): onPause
D/PMS     (  945): releaseWL(96b9dde): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/GCoreUlr( 1777): Unbound from all location providers
D/PMS     (  945): releaseWL(19828ac7): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
I/FeedHostManager( 1620): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@280b325a
I/SocialFeedProvider( 1620): +onPause
I/SocialFeedProvider( 1620): -onPause
W/HtcSystemUPManager(  945): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  945): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6190 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/GCoreUlr( 1777): DispatchingService.onDestroy()
D/StatusBarManagerService(  945): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
D/PMS     (  945): acquireWL(35b17724): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
W/asset   ( 6190): Copying FileAsset 0xac3e3aa0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  945): releaseWL(35b17724): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/GCoreUlr( 1777): Unbound from all location providers
I/TrimMemoryManager( 1620): [trimMemory] 20
D/PhoneApp( 1558): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1558): -- N1 =0
D/PhoneApp( 1558): -- N2 =0
D/PhoneApp( 1558): -- N3 =0
,I/art     ( 4493): Explicit concurrent mark sweep GC freed 16665(1198KB) AllocSpace objects, 11(220KB) LOS objects, 44% free, 4MB/8MB, paused 1.463ms total 47.551ms
I/ActivityManager(  945): Killing 5763:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=5763
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/WebViewFactory( 6190): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/ActivityManager(  945): Recipient 5763
D/Process (  945): killProcessQuiet, pid=5790
I/ActivityManager(  945): Killing 5790:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/LibraryLoader( 6190): Time to load native libraries: 13 ms (timestamps 7609-7622)
I/LibraryLoader( 6190): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6190): Binding Chromium to main looper Looper (main, tid 1) {35158785}
I/LibraryLoader( 6190): Expected native library version number "",actual native library version number ""
I/chromium( 6190): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6190): Initializing chromium process, singleProcess=true
W/art     ( 6190): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6190): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  945): Recipient 5790
W/chromium( 6190): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6190): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6190): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6190): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6190): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6190): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6190): Local Branch: 
I/Adreno-EGL( 6190): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6190): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6190):                  d74aa161a12b9c6fc6332151
E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  945):  packet count Tx=186 Rx=224
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  945): notifying of data activity 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/System.err(  945): java.lang.Throwable: stack dump
W/System.err(  945): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  945): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  945): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  945): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  945): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  945): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@480d645:true
D/BluetoothAdapter( 6190): 506205953: getState(). Returning 12
W/art     ( 6190): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6190): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6190): CordovaWebView is running on device made by: HTC
I/art     (  945): Explicit concurrent mark sweep GC freed 19633(1022KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.752ms total 140.002ms
I/art     (  945): WaitForGcToComplete blocked for 18.831ms for cause HeapTrim
W/art     ( 6190): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6190): Attempt to remove local handle scope entry from IRT, ignoring
D/PMS     (  945): acquireWL(b0e559f): PARTIAL_WAKE_LOCK  Icing 0x1 4493 10024 WorkSource{10024 com.google.android.gms}
,E/Icing   ( 4493): Loading extension by file descriptor -1 failed,
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1777, uid=10024, userID:0,
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1919, uid=10024, userID:0,
,D/PMS     (  945): acquireWL(3cd6d31): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 945 1000 null
,D/PMS     (  945): acquireWL(1aa29c16): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 945 1000 null
,D/PMS     (  945): releaseWL(3cd6d31): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  945): releaseWL(1aa29c16): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
D/PMS     (  945): releaseWL(b0e559f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
W/chromium( 6190): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  945): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6245 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,I/art     (  428): Explicit concurrent mark sweep GC freed 8648(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 193us total 20.755ms
,I/GservicesUpdateTask( 5877): Updating Gservices keys
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 175us total 17.244ms
D/PMS     (  945): acquireWL(3e25f833): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 945 1000 null
,D/PMS     (  945): acquireWL(323c67f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 945 1000 WorkSource{10024}
,I/IntentController( 1223): receive(android.intent.action.SYNC_STATE_CHANGED,1,false),
D/PMS     (  945): releaseWL(3e25f833): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/FindExtension( 6190): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 157us total 16.820ms,
D/PMS     (  945): acquireWL(313adb25): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 945 1000 null
D/PhoneMonitor( 6245): Register our PhoneStateListener
D/PMS     (  945): releaseWL(313adb25): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,V/SetupWizard( 6245): Connected to Gservices successfully
,D/PhoneMonitor( 6245): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/ChimeraCfgMgr( 4493): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4493): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
D/PhoneMonitor( 6245): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/PhoneStatusBar( 1223): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020653 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
I/ActivityManager(  945): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6281 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/GCM     ( 1919): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/Process (  945): killProcessQuiet, pid=5837
I/ActivityManager(  945): Killing 5837:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/InputMethodManager( 6190): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@6514ad, mServedView=org.apache.cordova.engine.SystemWebView{2224b3e2 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3b3ba373
,I/InputMethodManagerService(  945): Disable input method client, pid=1620
,D/StatusBarManagerService(  945): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  945): Enable input method client, pid=6190
,I/ActivityManager(  945): Recipient 5837,
,I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
,W/BindingManager( 6190): Cannot call determinedVisibility() - never saw a connection for the pid: 6190,
,W/XT9_C   ( 1397): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/XT9_C   ( 1397): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1397): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1397): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/ActivityManager(  945): Displayed com.test.thalitest/.MainActivity: +1s270ms
,D/PMS     (  945): releaseWL(cf4a060): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/PMS     (  945): acquireWL(3bf1ad20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 945 1000 null,
,D/PMS     (  945): releaseWL(323c67f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10024}
,D/PMS     (  945): releaseWL(3bf1ad20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1223): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/JsMessageQueue( 6190): Set native->JS mode to OnlineEventsBridgeMode,
,W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/Gmail   ( 6281): getAccountsCursor
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1919): Explicit concurrent mark sweep GC freed 3892(160KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 1.108ms total 40.007ms
,W/GAV2    ( 6281): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=6281, uid=10106, userID:0
W/ActivityManager(  945): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 6281): Observing account changes for notifications,
,W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=6281, uid=10106, userID:0
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=6281, uid=10106, userID:0
,D/jxcore_app_log( 6190): JniHelper::setJavaVM(0xab2778f8), pthread_self() = -1403387792
,W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6190): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6190):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6190):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6190):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6190):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6190): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24a1831d added. We now have 1 listener(s)
D/BluetoothManagerService(  945): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190): setBluetoothMacAddress: 90:E7:C4:F6:69:77
,E/Gmail   ( 6281): Error finding the version of the Email provider.....
E/Gmail   ( 6281): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6281): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6281): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6281): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6281): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6281): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 6281): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6281): We do not support migrating this version of the Email provider.
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6190): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6190): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dd83419 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6190): addListener: New listener added - the number of listeners is now 1
,I/Gmail   ( 6281): getAccountsCursor
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/WifiService(  945): New client listening to asynchronous messages
,E/WifiTrafficPoller(  945): ADD_CLIENT: 7
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/GCM     ( 1919): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
D/BluetoothAdapter( 6190): 506205953: getState(). Returning 12
E/WifiTrafficPoller(  945):  packet count Tx=186 Rx=224
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6190): setDiscoveryMode: Discovery mode BLE is supported
,I/ActivityManager(  945): Killing 4589:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=4589
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/BluetoothAdapter( 6190): 506205953: getState(). Returning 12
,I/chromium( 6190): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  945): Recipient 4589,
,D/AuthorizationBluetoothService( 1919): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 4493): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4493, uid=10024, userID:0
,D/WearableService( 4863): callingUid 10024, callindPid: 4863
,D/LocationInitializer( 4493): Restart initialization of location
,D/PMS     (  945): acquireWL(158fa003): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5531 10159 null
,E/SQLiteLog( 6281): (283) recovered 1551 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5531, uid=10159, userID:0,
D/PMS     (  945): releaseWL(158fa003): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 5531): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5531): Stop autocaching.
,I/art     ( 1777): Explicit concurrent mark sweep GC freed 15146(791KB) AllocSpace objects, 4(80KB) LOS objects, 46% free, 4MB/8MB, paused 1.155ms total 56.122ms
,E/DataBuffer( 1777): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@53047fe)
E/MDM     ( 1777): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ActivityManager(  945): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=6338 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/PMS     (  945): releaseHCC(3fc7e8f4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  945): releaseHCC(31d0b81d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/GmsUtils( 5531): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5531): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,I/Gmail   ( 6281): notifyAccountChanged
,D/SyncApplication( 6338): Loading default preferences,
,I/Gmail   ( 6281): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6281): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/Resources( 6338): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/Gmail   ( 6281): getAccountsCursor
,I/Gmail   ( 6281): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6281): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiDataStallTracker(  945): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  945): updateDataStallInfo: mDataStallTxRxSum={txSum=168 rxSum=170} preTxRxSum={txSum=166 rxSum=169},
D/WifiDataStallTracker(  945): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  945): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiService(  945): New client listening to asynchronous messages
,E/WifiTrafficPoller(  945): ADD_CLIENT: 8
,D/SyncApplication( 6338): Overriding preferences with custom values
,D/SyncApplication( 6338): Updating preferences succeeded,
,E/SyncApplication( 6338): Application created.,
,I/CalendarDefines( 6338): getNewCalendarAuthority()...
,I/Gmail   ( 6281): master sync=false, engine sync=true
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=6338, uid=10005, userID:0
W/VolumeInfo( 6338): Unable to read mount points,
W/VolumeInfo( 6338): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 6338): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 6338): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 6338): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 6338): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 6338): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 6338): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 6338): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 6338): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 6338): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 6338): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 6338): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 6338): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 6338): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 6338): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 6338): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 6338): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 6338): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 6338): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 6338): 	... 13 more
W/PackageManager(  945): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync,
V/VolumeInfo( 6338): Found 0 mount point(s)
I/PackageManager(  945):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=6338, uid=10005, userID:0
V/VolumeInfo( 6338): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
W/PackageManager(  945): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 6338): enableAppOperation()+
D/SyncApplication( 6338): enableAppOperation()-
D/HTCUtilities( 6338): isNeorSinged() + 
D/VolumeInfo( 6338): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 6338): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 6338): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 6338): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 6338): isNeorSinged() return false
,D/CDMountReceiver( 6338): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 6338): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 6338): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true,
D/CDMountReceiver( 6338): enable CD Auto-mount: true
,D/HTCUtilities( 6338): enable auto-mount
,D/HTCUtilities( 6338): enable auto-mount
,I/HtcMountManagerAdapter( 6338): mHtcMountManager is  null,
D/VoldConnector(  945): SND -> {28 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
I/HtcMountManagerAdapter( 6338): mStorageManager is  not null
D/MountService(  945): mountISO: /system/etc/PCTOOL.ISO
I/HtcMountManagerAdapter( 6338): mHtcMountManager is  null
D/VoldConnector(  945): SND -> {29 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,I/HtcMountManagerAdapter( 6338): mStorageManager is  not null
I/RemoteViews( 1223): apply : com.nero.android.htc.sync 0 13 4 38
,D/MountService(  945): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews( 1223): apply : com.nero.android.htc.sync 0 12 3 53
,I/[PluginManager]RegisterService( 1538): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest,
I/[PluginManager]RegisterService( 1538): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1620): action: android.intent.action.PACKAGE_ADDED,
,I/ActivityManager(  945): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6381 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6381): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6381 dbg=false s=true,
,I/DeviceManagement( 6381): PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,I/ActivityManager(  945): Killing 5104:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=5104
,D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  945): Recipient 5104,
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
,E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=5.3, 0.0, 0.0  rx=8.1 bcn=0 [on:0 tx:0 rx:0 period:2826] from screen [on:0 period:1625826021] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
I/ActivityManager(  945): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=6404 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=5.3, 0.0, 0.0  rx=8.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625826022] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1345): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.17 txretriesrate=0.00 rxrate=5.07 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
E/WifiStateMachine(  945): handleMessage: X
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 8,
E/WifiTrafficPoller(  945):  packet count Tx=190 Rx=227
E/WifiTrafficPoller(  945): notifying of data activity 3
,D/WIFI_ICON( 1223): WifiActivity: 3
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/art     (  945): Explicit concurrent mark sweep GC freed 15041(808KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.523ms total 146.955ms
,D/HtcCupdReceiver(Provider)( 6404):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,D/Process (  945): killProcessQuiet, pid=6030
I/ActivityManager(  945): Killing 6030:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/jxcore-log( 6190): Initializing JXcore engine,
W/jxcore-log( 6190): JXcore engine is ready
,I/ActivityManager(  945): Recipient 6030
,W/jxcore-log( 6190): Starting JXcore engine
,D/ChimeraCfgMgr( 4493): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/PackageBroadcastService( 4493): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,W/jxcore-log( 6190): Platform android
W/jxcore-log( 6190): 
W/jxcore-log( 6190): Process ARCH arm
W/jxcore-log( 6190): 
D/ChimeraModuleLdr( 4493): Loading module APK com.google.android.play.games
,D/PMS     (  945): acquireWL(cdc540c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4493 10024 null
,I/ConfigFetchService( 4493): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,I/ConfigFetchService( 4493): launchTask
D/PMS     (  945): acquireWL(1f00a4f8): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4493 10024 WorkSource{10366 com.test.thalitest}
,D/PMS     (  945): releaseWL(cdc540c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  945): acquireWL(3559fdd1): PARTIAL_WAKE_LOCK  Icing 0x1 4493 10024 WorkSource{10024 com.google.android.gms},
,D/ChimeraCfgMgr( 4493): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4493): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4493): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 4493): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VqUgoxY2XaTC9EzoyMlCnN-r9_5ft8z5jLNddgVuqVyrjKuVE9cRTqNUFQRYCFLfkgKG0w_IxA42zXEC-a04izZ9o8QAv5LPemlByrMm0N-iTDzGoxV6OIcTKxPSZYNv5u_8364hYyMuSBlzAc5B41jYFIRyCGq31V2UXzQjEW4GtDjzpE199ZR9CVoltecNoh0A2Qa1CEuFNeIAQASiqWQPK_wmAm9YH1TcFjt8y4mGhegCc,
D/PMS     (  945): releaseWL(3559fdd1): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/Vision  ( 4493): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4493): Failed to find package metadata for com.test.thalitest
D/Vision  ( 4493): No vision deps
I/GoogleURLConnFactory( 4493): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  945): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6434 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/PeopleContactsSync( 4493): CP2 sync disabled
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4493, uid=10024, userID:0,
,D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4493): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4493): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4493): [NET] android_getaddrinfo_proxy+
D/libc    ( 4493): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  413): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    (  413): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  413): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  413): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4493): [NET] android_getaddrinfo_proxy-, success
,I/jxcore-log( 6190): JXcore Cordova bridge is ready!
I/jxcore-log( 6190): 
W/jxcore-log( 6190): JXcore engine is started
,W/BaseAppContext( 4493): Using Auth Proxy for data requests.
,W/BaseAppContext( 4493): Using Auth Proxy for data requests.
,I/org.thaliproject.p2p.ThaliPermissions( 6190): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 6190): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6190): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6190): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/PluginManager( 6190): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 37ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  945): acquireWL(251718a4): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 945 1000 null
W/HtcSystemUPManager(  945): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/BaseAppContext( 4493): Using Auth Proxy for data requests.
I/FeedHostManager( 1620): [onResume]
I/FeedProviderManager( 1620): onResume
I/SocialFeedProvider( 1620): +onResume
I/SocialFeedProvider( 1620): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1620): -onResume
D/StatusBarManagerService(  945): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
W/BaseAppContext( 4493): Using Auth Proxy for data requests.
D/FindExtension( 1620): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1620): Defer allocateBuffers to drawing time
,W/BaseAppContext( 4493): Using Auth Proxy for data requests.
,I/InputMethodManagerService(  945): Disable input method client, pid=6190,
I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/StatusBarManagerService(  945): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 6190): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  945): Enable input method client, pid=1620
,W/BaseAppContext( 4493): Using Auth Proxy for data requests.
,D/PMS     (  945): releaseWL(251718a4): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4493): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4493): [NET] android_getaddrinfofornet-, err=8
,D/StatusBarManagerService(  945): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  945): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  945): hiding MENU key
,I/ActivityManager(  945): Killing 5609:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=5609
,D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ConfigFetchService( 4493): fetch service done; releasing wakelock,
I/ConfigFetchService( 4493): stopping self
D/PMS     (  945): releaseWL(1f00a4f8): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10366 com.test.thalitest},
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 8
,I/ActivityManager(  945): Recipient 5609
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=236
,I/GAv4    ( 6434): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6434):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6434):   adb logcat -s GAv4
,W/GAv4    ( 6434): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6434): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6434): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6434): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,W/OpenGLRenderer( 1620): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,D/AccTypeManager( 1742): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 1620): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1620): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1620): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader(  945): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1742): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  945): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneApp( 1558): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AccTypeManager( 1742): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/VoldConnector(  945): SND -> {30 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 6434): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  945): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6473 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/ExternalAccountType( 1742): Unsupported attribute readOnly,
I/ActivityManager(  945): Killing 5660:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=5660
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ResourcesManager( 6434): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6434): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 4493): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4493): Module APK com.google.android.play.games already loaded
,W/PackageManager(  945): Unable to load service info ResolveInfo{115c06a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  945): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data,
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  945): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  945): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  945): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  945): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  945): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  945): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  945): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  945): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  945): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  945): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  945): Recipient 5660
,I/BackupManagerService(  945): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,W/ResourcesManager( 6473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GCoreNlp( 1777): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/JNIHelp ( 6434): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/LocationProviderProxy(  945): applying state to connected service,
,V/GmsNetworkLocationProvi( 1777): DISABLE
D/PMS     (  945): acquireWL(2bdb68c1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): releaseWL(2bdb68c1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  945): applying state to connected service
,D/PMS     (  945): acquireWL(c9c9866): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): acquireWL(1a0027a7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(c9c9866): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(304ff454): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
W/System  ( 6434): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6434): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  945): releaseWL(304ff454): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(1a0027a7): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  945): acquireWL(201c4e3e): PARTIAL_WAKE_LOCK  AsyncService 0x1 6473 10167 null,
,D/PMS     (  945): releaseWL(201c4e3e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  945): acquireWL(5c579ec): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6473 10167 null
,D/PMS     (  945): releaseWL(5c579ec): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,D/GCM     ( 1919): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 4493): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/WifiDisplayAdapter(  945): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  945):     Client/Owner: Client
D/WifiDisplayAdapter(  945):     GroupId: 
D/WifiDisplayAdapter(  945):     Passphrase: 
D/WifiDisplayAdapter(  945):     SessionId: 0
D/WifiDisplayAdapter(  945):     IP Address: }
I/Kids    ( 4493): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
E/WifiStateMachine(  945): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  945): handleMessage: E msg.what=131143
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):1 dur:83 rssi=-53 f=2442 sc=60 link=150 tx=4.2, 0.0, 0.0  rx=5.1 list=2442 [on:0 tx:0 rx:0 period:2054] from screen [on:0 period:1625828086]
E/WifiStateMachine(  945): processMsg: L2ConnectedState
,E/WifiStateMachine(  945):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=3 proc(ms):2 dur:83 rssi=-53 f=2442 sc=60 link=150 tx=4.2, 0.0, 0.0  rx=5.1 list=2442 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625828087]
D/PMS     (  945): releaseWL(38d3f4d2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
I/UpdateIcingCorporaServi( 5877): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.17 rxSuccessRate=5.07 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-53
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN with age=1457619741431 interval=40000 maxinterval=300000
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN try full band scan age=1457619741431 interval=40000 maxinterval=300000
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN bump interval =60000
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1345): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1345): wpa_supplicant_scan enter
D/wpa_supplicant( 1345): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1345): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1345): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1345): WPS:  * Request Type
D/wpa_supplicant( 1345): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1345): WPS:  * UUID-E
D/wpa_supplicant( 1345): WPS:  * Primary Device Type
D/wpa_supplicant( 1345): WPS:  * RF Bands (3)
D/wpa_supplicant( 1345): WPS:  * Association State
D/wpa_supplicant( 1345): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1345): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1345): WPS:  * Manufacturer
D/wpa_supplicant( 1345): WPS:  * Model Name
D/wpa_supplicant( 1345): WPS:  * Model Number
D/wpa_supplicant( 1345): WPS:  * Device Name
D/wpa_supplicant( 1345): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1345): P2P: * P2P IE header
D/wpa_supplicant( 1345): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1345): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1345): wlan0: Add radio work 'scan'@0x55a9a60860
D/wpa_supplicant( 1345): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1345): wlan0: Starting radio work 'scan'@0x55a9a60860 after 0.000035 second wait
D/wpa_supplicant( 1345): wlan0: nl80211: scan request
D/wpa_supplicant( 1345): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1345): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1345): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1345): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1345): wlan0: Own scan request started a scan in 0.000077 seconds
I/wpa_supplicant( 1345): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  945): [1,457,619,741,436 ms] noteScanstart no scan source
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  945): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  945): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  945): handleMessage: X
D/PMS     (  945): acquireWL(3c8b104a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  945): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=6510 uid=10035 gids={50035, 9997} abi=arm64-v8a
D/PMS     (  945): releaseWL(3c8b104a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/asset   ( 5877): Copying FileAsset 0x55a67c39b0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/UpdateIcingCorporaServi( 5877): UpdateCorporaTask done [took 77 ms] updated apps [took 77 ms] 
,D/Process (  945): killProcessQuiet, pid=6085
I/ActivityManager(  945): Killing 6085:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 8
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=236
D/WIFI_ICON( 1223): WifiActivity: 0,
E/WifiTrafficPoller(  945): notifying of data activity 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 3303): handler message = 4011
E/HtcModeClient( 3303): Check connection and retry 8 times.
,I/ActivityManager(  945): Recipient 6085
,I/ActivityManager(  945): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6535 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,I/ActivityManager(  945): Killing 6117:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=6117
,D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  429): Explicit concurrent mark sweep GC freed 8664(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 378us total 27.148ms
,I/art     (  429): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 294us total 20.354ms
,I/art     (  429): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 296us total 20.489ms
,I/ActivityManager(  945): Recipient 6117
,W/ResourcesManager( 6535): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/Babel_SMS( 6535): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6535): MmsConfig.loadMmsSettings
,I/ActivityManager(  945): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6564 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6535, uid=10112, userID:0
,W/HtcWrapAdjustableCursorFactory( 6564): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 6564): onCreate
,W/Settings( 6535): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GetPrviateResource( 6564): GetPrviateResource,
V/GetPrviateResource( 6564): GetPrviateResource
I/Babel_Crash( 6535): startup - clean
D/MmsCustomizationProvider( 6564): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MessageCustFlag( 6564): sense_version=6.0,
,D/BTAccessoryUtil( 6564): createReceiver
,D/BTAccessoryUtil( 6564): registerReceiver return intent = null,
D/MmsCustomizationProvider( 6564): query uri: content://htc-mms-customization/mms-ua/ua_profile,
,D/MessageCustFlag( 6564): sku_id=118
,I/Babel_SMS( 6535): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 6535): MmsConfig.loadFromDatabase
,I/Babel   ( 6535): deleted: false for 0
D/HtcBuildUtils( 6564): getRATByHtcTelephonyCapability:1
,W/SystemReader( 6564): Cannot find qct_8960_interface, use default value instead
,E/Babel_SMS( 6535): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6535): MmsConfig.loadFromResources
,E/Babel_SMS( 6535): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6535): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6535, uid=10112, userID:0
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6535, uid=10112, userID:0
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6535, uid=10112, userID:0
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6535, uid=10112, userID:0
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6535, uid=10112, userID:0,
,D/PMS     (  945): acquireWL(3f5041c6): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6535 10112 null
,I/[PluginManager]RegisterService( 1538): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1538): handle notify Blinkfeed plugin client changed
,W/VideoCapabilities( 6535): Unrecognized profile 2130706433 for video/avc,
,D/PackageBroadcastService( 4493): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4493): Null package name or gms related package.  Ignoreing.
,D/PMS     (  945): acquireWL(8fddd9): PARTIAL_WAKE_LOCK  Icing 0x1 4493 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): acquireWL(1afc39e): PARTIAL_WAKE_LOCK  AsyncService 0x1 6473 10167 null
,D/PMS     (  945): releaseWL(1afc39e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/Icing   ( 4493): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  945): acquireWL(69c5e4c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6473 10167 null
,D/PMS     (  945): releaseWL(69c5e4c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5877): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  945): releaseWL(8fddd9): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/VideoCapabilities( 6535): Unsupported mime video/x-ms-wmv,
,W/Utils   ( 6535): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 6535): Unsupported mime audio/qcelp
W/AudioCapabilities( 6535): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6535): Unsupported mime audio/qcelp
W/VideoCapabilities( 6535): Unsupported mime video/x-ms-wmv
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155
E/WifiStateMachine(  945): processMsg: ConnectedState
,E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=4.2, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:940] from screen [on:0 period:1625829033] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=4.2, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625829034] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL',
,I/UpdateIcingCorporaServi( 5877): UpdateCorporaTask done [took 79 ms] updated apps [took 79 ms] ,
,I/VideoCapabilities( 6535): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6535): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6535): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6535): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6535): Unrecognized profile 2130706433 for video/avc
,D/Process (  945): killProcessQuiet, pid=5176
I/ActivityManager(  945): Killing 5176:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/Prism.ItemManager( 1620): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1620): loadItems() com.htc.launcher.pageview.WidgetManager@374cfd15 +
I/Prism.WidgetManager( 1620): onLoadItems() +
,I/ActivityManager(  945): Recipient 5176
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 8
,E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=236
,I/vclib   ( 6535): onServiceConnected,
,W/Babel   ( 6535): Attempted to change video mute state without an active call.
,D/PMS     (  945): releaseWL(3f5041c6): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null,
,W/ResourcesManager( 6535): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6535): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 6535): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/Prism.WidgetManager( 1620): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1620): onLoadItems() -
I/Prism.ItemManager( 1620): loadItems() com.htc.launcher.pageview.WidgetManager@374cfd15 -
,W/System  ( 6535): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6535): Installed default security provider GmsCore_OpenSSL
,D/PhoneApp( 1558): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1558): -- N1 =0,
D/PhoneApp( 1558): -- N2 =0
,D/PhoneApp( 1558): -- N3 =0
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.08 txretriesrate=0.00 rxrate=7.53 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  945):  isHighRSSI       ---> score=65
E/WifiStateMachine(  945): handleMessage: X
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
,I/GAV2    ( 6281): Thread[GAThread,5,main]: No campaign data found.
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 8
,E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=236
,D/wpa_supplicant( 1345): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1345): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1345): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1345): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1345): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1345): wlan0: Scan completed in 2.189641 seconds
D/wpa_supplicant( 1345): nl80211: Associated on 2442 MHz
D/wpa_supplicant( 1345): nl80211: Associated with f4:f2:6d:22:99:3e
D/wpa_supplicant( 1345): nl80211: Received scan results (14 BSSes)
D/wpa_supplicant( 1345): nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
I/wpa_supplicant( 1345): [NULL] f0:f2:6d:22:99:3e freq=2442 level=-48
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:6b freq=5320 level=-53
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:6f freq=5320 level=-53
I/wpa_supplicant( 1345): [NULL] f4:f2:6d:22:99:3e freq=2442 level=-53
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:70:c3 freq=2462 level=-64
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:62 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:64 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:60 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:dd:e0 freq=2437 level=-72
I/wpa_supplicant( 1345): [NULL] 00:16:a6:1f:06:5c freq=2462 level=-81
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:63 freq=2412 level=-64
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:70:c5 freq=2462 level=-65
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-72
I/wpa_supplicant( 1345): [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-82
D/wpa_supplicant( 1345): wlan0: BSS: Start scan result update 4
D/wpa_supplicant( 1345): wlan0: BSS: Add new id 8 BSSID 00:1e:4a:8f:e3:6b SSID '\x00'
D/wpa_supplicant( 1345): wlan0: BSS: Add new id 9 BSSID 00:1e:4a:8f:e3:6f SSID '\x00'
D/wpa_supplicant( 1345): wlan0: BSS: Add new id 10 BSSID 00:1e:4a:8f:e3:62 SSID '\x00'
D/wpa_supplicant( 1345): wlan0: BSS: Add new id 11 BSSID 00:1e:4a:8f:e3:64 SSID '\x00'
D/wpa_supplicant( 1345): wlan0: BSS: Add new id 12 BSSID 00:1e:4a:8f:e3:60 SSID '\x00'
D/wpa_supplicant( 1345): wlan0: BSS: Add new id 13 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS'
D/wpa_supplicant( 1345): BSS: last_scan_res_used=14/32
D/wpa_supplicant( 1345): wlan0: Scan-only results received
D/wpa_supplicant( 1345): wlan0: Radio work 'scan'@0x55a9a60860 done in 2.191332 seconds
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 00:1e:4a:8f:e3:6b]
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 00:1e:4a:8f:e3:6f]
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 00:1e:4a:8f:e3:62]
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 00:1e:4a:8f:e3:64]
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 00:1e:4a:8f:e3:60]
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 00:22:0d:46:1c:a3]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  945): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  945): handleMessage: E msg.what=147461
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !SCAN_RESULT,S_EVENT 0 0 found=8 known=1 got=8 bcn=0
E/WifiStateMachine(  945): processMsg: ConnectModeState
E/WifiStateMachine(  945):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
E/WifiStateMachine(  945): processMsg: DriverStartedState
E/WifiStateMachine(  945):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
E/WifiStateMachine(  945): processMsg: SupplicantStartedState
E/WifiStateMachine(  945):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=8 known=1 got=8 bcn=0
D/WifiStateMachine(  945): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1345): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  945): [1,457,619,743,629 ms] noteScanEnd no scan source
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1345): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  945): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@305b6b26 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  945): NG700 f4:f2:6d:22:99:3e rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  945): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  945): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  945):         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-53 freq=2442
E/WifiAutoJoinController (  945): NG700_GUEST f0:f2:6d:22:99:3e rssi=-48 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1f:27:54:70:c3 rssi=-64 cap [WPA-PSK-TKIP][WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1f:27:54:dd:e0 rssi=-72 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:16:a6:1f:06:5c rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:1e:4a:8f:e3:63 rssi=-64 cap [ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:1f:27:54:70:c5 rssi=-65 cap [ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:1f:27:54:dd:e3 rssi=-72 cap [ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:6b rssi=-53 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:6f rssi=-53 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:62 rssi=-66 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:64 rssi=-66 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:60 rssi=-66 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:22:0d:46:1c:a3 rssi=-82 cap [ESS] is not scored
E/WifiAutoJoinController (  945): ageScanResultsOut delay 40000 size 14 now 1457619743634
E/WifiAutoJoinController (  945): newSupplicantResults size=14 known=1 true
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1345): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  945): attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
E/WifiAutoJoinController (  945): ssid=NG700
E/WifiAutoJoinController (  945): id=0
E/WifiAutoJoinController (  945): mode=station
E/WifiAutoJoinController (  945): pairwise_cipher=CCMP
E/WifiAutoJoinController (  945): group_cipher=CCMP
E/WifiAutoJoinController (  945): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  945): wpa_state=COMPLETED
E/WifiAutoJoinController (  945): ip_address=192.168.1.102
E/WifiAutoJoinController (  945): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  945): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  945): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  945): attemptAutoJoin() num recent con,fig 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  945): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-53,-127) num=(1,0)
E/WifiAutoJoinController (  945): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  945): attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-53 freq=2442 Current: f4:f2:6d:22:99:3e
D/HtcWifiControlRoamOffload: (  945): roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
E/WifiStateMachine(  945): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  945): Done attemptAutoJoin status=0
E/WifiConfigStore(  945):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  945): handleMessage: X
,D/WifiManager( 1777): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,D/Process (  945): killProcessQuiet, pid=5531
I/ActivityManager(  945): Killing 5531:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiDataStallTracker(  945): DATA_MONITOR_POLL true Token 1,
I/ActivityManager(  945): Recipient 5531
D/MediaRouterService(  945): Client com.google.android.music (pid 5531): Died!
,D/WifiDataStallTracker(  945): updateDataStallInfo: mDataStallTxRxSum={txSum=181 rxSum=180} preTxRxSum={txSum=168 rxSum=170}
D/WifiDataStallTracker(  945): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  945): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/Messaging( 6564): supportCMAS(SIE)/init? false/true,
,D/MmsConfig( 6564): networkCode: 
,D/MessageCustFlag( 6564): sku_id=118
,D/MmsConfig( 6564): SIE smsPri: null
D/MmsConfig( 6564): networkCode: 
,D/MmsConfig( 6564): packageName: com.htc.vvm.att does not exist
,D/Messaging( 6564): mNeedToUpdateDate2 start,
,D/ReportIndicatorCache( 6564): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6564): 
D/MmsAsyncWorkHandler( 6564): HM tk = 20001
,D/ReportIndicatorCache( 6564): MSG_QUERY_REPORTS >>
D/SettingsManager( 6564): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@35158785
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 100
D/AccFlag ( 1558): sku_id=118
,D/DraftCache( 6564): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6564): [DraftCache/1] refresh
,I/Messaging( 6564): mccmnc> ,
,D/DraftCache( 6564): [DraftCache/156] rebuildCache
,D/MmsConfig( 6564): networkCode: ,
,D/Messaging( 6564): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 6564): sense_version=6.0,
D/Jerry   ( 6564): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 6564): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 6564): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6564): createReceiver
,I/ActivityManager(  945): Waited long enough for: ServiceRecord{1fd813e0 u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService},
,D/TelephUtils( 1558): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 97,
V/MmsProvider( 1558): Update uri=content://mms, match=0
V/MmsProvider( 1558): selection=st=129 AND m_type!=134
D/Messaging( 6564): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6564): TransactionService is going to be woken up.,
,V/TransactionService( 6564): 1-Creating TransactionService,
,V/TransactionService( 6564): onStartCommand: 1
D/MmsSystemEventReceiver( 6564): unRegisterForConnectionStateChanges
,V/TransactionService( 6564): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6564): Loading previous transactions.
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55,
,D/AccFlag ( 1558): device_type: 1
D/TransactionService( 6564): Force clearing mTransactionList
D/TransactionService( 6564): Force set service start id to 1
V/TransactionService( 6564): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6564): unRegisterForConnectionStateChanges
D/TransactionService( 6564): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6564): Destroying TransactionService
,V/TransactionService( 6564): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,I/art     (  945): Explicit concurrent mark sweep GC freed 27673(1581KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 18MB/28MB, paused 1.751ms total 179.375ms
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/MmsSmsV2Provider( 1558):  slotId = -1000
D/MmsSmsV2Provider( 1558): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 100
D/MmsSmsV2Provider( 1558):  slotId = -1000
D/MmsSmsV2Provider( 1558): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54,
D/Jerry   ( 1558): URI_DRAFT
,D/DraftCache( 6564): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 6564): [DraftCache/156] rebuildCache time: 12
D/MmsAsyncWorkHandler( 6564): 
D/MmsAsyncWorkHandler( 6564): HM tk = 20002
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97,
D/MmsSmsV2Provider( 1558):  slotId = -1000
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/MmsSmsV2Provider( 1558):  slotId = -1000
D/MmsSmsV2Provider( 1558): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6564): mNeedToUpdateDate2: false
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 97
D/MmsSmsV2Provider( 1558):  slotId = -1000
D/MmsSmsV2Provider( 1558): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 6564): ViewCache CreatePreload
D/Messaging( 6564): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 6564): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/AccFlag ( 1558): sku_id=118
,D/Cust_MMSMS( 6564): _has_set_default_values_2=true
,D/TelephUtils( 1558): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/AccFlag ( 1558): sku_id=118
,D/MsgPreferenceUtils( 6564): def_index: 0
,D/MsgPreferenceUtils( 6564): globalIndex = 1,
,I/ActivityManager(  945): Waited long enough for: ServiceRecord{177c0d37 u0 com.htc.musicenhancer/.EnhancerService}
,D/MsgPreferenceUtils( 6564): phone state: true,
D/MsgPreferenceUtils( 6564): sd state: false
D/MsgPreferenceUtils( 6564): vIndex = 0
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 8,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=236
,W/MediaManager( 5478): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  945): killProcessQuiet, pid=6338
I/ActivityManager(  945): Killing 6338:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6338
D/WifiService(  945): Client connection lost with reason: 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/PackageSettings(  945): Skipping PackageSetting{df716c4 com.example.hello/10374} due to missing metadata
,D/PMS     (  945): acquireWL(35237d62): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{c1c6ef3: PendingIntentRecord{14db77b0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=85691, Int=0
D/PMS     (  945): releaseWL(35237d62): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=237
E/WifiTrafficPoller(  945): notifying of data activity 1
D/WIFI_ICON( 1223): WifiActivity: 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ConfigService( 1919): onDestroy,
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=8.1, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1625832835] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=8.1, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625832836] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [12][0][0],
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 150
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-52 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.04 txretriesrate=0.00 rxrate=4.27 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
E/WifiStateMachine(  945): handleMessage: X
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -52, 3
,D/Process (  945): killProcessQuiet, pid=5910,
I/ActivityManager(  945): Killing 5910:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 5910,
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=237
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  945): notifying of data activity 0
,I/HtcModeClient( 3303): handler message = 4011,
E/HtcModeClient( 3303): Check connection and retry 9 times.
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=237
,I/ActivityManager(  945): Killing 6381:com.htc.cs.dm/u0a99 (adj 15): empty #17,
,D/Process (  945): killProcessQuiet, pid=6381
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6381
,E/WifiStateMachine(  945): handleMessage: E msg.what=131326
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !what:131326 1 0
,E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !what:131326 1 0
,E/WifiStateMachine(  945): handleMessage: X,
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=243
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  945): notifying of data activity 1
,E/WifiDataStallTracker(  945): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  945): updateDataStallInfo: mDataStallTxRxSum={txSum=181 rxSum=180} preTxRxSum={txSum=181 rxSum=180}
D/WifiDataStallTracker(  945): updateDataStallInfo: NONE
D/WifiDataStallTracker(  945): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/ContactMessageStore( 1558): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1558): MSG_NOTIFY_CS_TO_SYNC <<
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2442 sc=60 link=150 tx=4.0, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1625835855] gl hn u24 rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-52 f=2442 sc=60 link=150 tx=4.0, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1625835857] gl hn u24 rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.02 txretriesrate=0.00 rxrate=8.63 userTriggerdPenalty0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  945):  good link -> stuck count =0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
E/WifiStateMachine(  945): handleMessage: X
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=251
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=251
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  945): notifying of data activity 0
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1538): service - handleMessage() stop self,
,D/AutoSetting( 1538): service - handleMessage() quit looper,
D/AutoSetting( 1538): service - onDestroy() END
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=251
,I/HtcModeClient( 3303): handler message = 4011,
E/HtcModeClient( 3303): Check connection and retry 10 times.
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=2.0, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1625838879] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
,E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=2.0, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625838880] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.01 txretriesrate=0.00 rxrate=4.82 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
E/WifiStateMachine(  945): handleMessage: X
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=251
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=251
,E/WifiDataStallTracker(  945): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  945): updateDataStallInfo: mDataStallTxRxSum={txSum=181 rxSum=180} preTxRxSum={txSum=181 rxSum=180}
D/WifiDataStallTracker(  945): updateDataStallInfo: NONE
D/WifiDataStallTracker(  945): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=252
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  945): notifying of data activity 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=1.0, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1625841901] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=1.0, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625841902] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
,E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.51 txretriesrate=0.00 rxrate=2.91 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
E/WifiStateMachine(  945): handleMessage: X
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
,D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1223): WifiActivity: 0
,E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=252
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  945): notifying of data activity 0
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=252
,I/HtcModeClient( 3303): handler message = 4011,
E/HtcModeClient( 3303): Check connection and retry 11 times.
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
,D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=253
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  945): notifying of data activity 1
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.5, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1625844923] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState,
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.5, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625844924] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-52 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.25 txretriesrate=0.00 rxrate=1.95 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  945): handleMessage: X
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=253
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  945): notifying of data activity 0
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiDataStallTracker(  945): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  945): updateDataStallInfo: mDataStallTxRxSum={txSum=181 rxSum=180} preTxRxSum={txSum=181 rxSum=180}
D/WifiDataStallTracker(  945): updateDataStallInfo: NONE
D/WifiDataStallTracker(  945): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=253,
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=254
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  945): notifying of data activity 1
,W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,D/PMS     (  945): acquireWL(5400dae): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{10072}
,V/AlarmManager(  945): sending alarm PendingIntent{305074f: PendingIntentRecord{7785edc com.android.vending startService}}, i=null, t=0, cnt=1, w=1457619754602, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{154f9be5: PendingIntentRecord{c8356ba com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457619760879, Int=536832000
V/AlarmManager(  945): sending alarm PendingIntent{141b14e7: PendingIntentRecord{21907894 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1457619749122, Int=20000
V/CheckinService( 4493): unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,D/PMS     (  945): acquireWL(2634c96b): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4493 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  945): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  945): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  945):     Client/Owner: Client
D/WifiDisplayAdapter(  945):     GroupId: 
D/WifiDisplayAdapter(  945):     Passphrase: 
D/WifiDisplayAdapter(  945):     SessionId: 0
D/WifiDisplayAdapter(  945):     IP Address: }
E/WifiStateMachine(  945): handleMessage: E msg.what=131143
E/WifiStateMachine(  945): processMsg: ConnectedState
D/PMS     (  945): releaseWL(5400dae): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  945):  ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):1 dur:2193 rssi=-53 f=2442 sc=60 link=150 tx=0.3, 0.0, 0.0  rx=2.0 fiv=60000 [on:0 tx:0 rx:0 period:2625] from screen [on:0 period:1625847567]
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=4 proc(ms):2 dur:2193 rssi=-53 f=2442 sc=60 link=150 tx=0.3, 0.0, 0.0  rx=2.0 fiv=60000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625847568]
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.25 rxSuccessRate=1.95 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-53
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN with age=19481 interval=60000 maxinterval=300000
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN full=false
,E/WifiConfigStore(  945): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  945): has f4:f2:6d:22:99:3e freq=2442 age=2631 ?=true
E/WifiStateMachine(  945): WifiStateMachine starting scan for "NG700"WPA_PSK with 2442
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2442"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2442'
D/wpa_supplicant( 1345): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1345): wpa_supplicant_scan enter
D/wpa_supplicant( 1345): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1345): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1345): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1345): WPS:  * Request Type
D/wpa_supplicant( 1345): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1345): WPS:  * UUID-E
D/wpa_supplicant( 1345): WPS:  * Primary Device Type
D/wpa_supplicant( 1345): WPS:  * RF Bands (3)
D/wpa_supplicant( 1345): WPS:  * Association State
D/wpa_supplicant( 1345): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1345): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1345): WPS:  * Manufacturer
D/wpa_supplicant( 1345): WPS:  * Model Name
D/wpa_supplicant( 1345): WPS:  * Model Number
D/wpa_supplicant( 1345): WPS:  * Device Name
D/wpa_supplicant( 1345): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1345): P2P: * P2P IE header
D/wpa_supplicant( 1345): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1345): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1345): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1345): wlan0: Add radio work 'scan'@0x55a9a840f0
D/wpa_supplicant( 1345): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1345): wlan0: Starting radio work 'scan'@0x55a9a840f0 after 0.000046 second wait
D/wpa_supplicant( 1345): wlan0: nl80211: scan request
E/WifiStateMachine(  945): [1,457,619,760,914 ms] noteScanstart no scan source
D/wpa_supplicant( 1345): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1345): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1345): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1345): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1345): wlan0: Own scan request started a scan in 0.000134 seconds
I/wpa_supplicant( 1345): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  945): handleMessage: X
D/PMS     (  945): acquireWL(c631161): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4493 10024 WorkSource{10024 com.google.android.gms}
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  945): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  945): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/PMS     (  945): releaseWL(2634c96b): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4493): Checking schedule, now: 1457619760933 next: 1457619760879
,I/CheckinService( 4493): active receiver: enabled
I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4493, uid=10024, userID:0
,I/CheckinService( 4493): Preparing to send checkin request
I/EventLogService( 4493): Accumulating logs since 1457619721782,
,D/wpa_supplicant( 1345): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1345): wlan0: nl80211: New scan results available
,D/wpa_supplicant( 1345): nl80211: Scan included frequencies: 2442
D/wpa_supplicant( 1345): wlan0: Event SCAN_RESULTS (3) received
W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/wpa_supplicant( 1345): Got an original EVENT_SCAN_RESULTS
I/ActivityManager(  945): Cannot resolve ContentProvider=com.google.android.wearable.settings
D/wpa_supplicant( 1345): wlan0: Scan completed in 0.085419 seconds
D/wpa_supplicant( 1345): nl80211: Associated on 2442 MHz
D/wpa_supplicant( 1345): nl80211: Associated with f4:f2:6d:22:99:3e
D/wpa_supplicant( 1345): nl80211: Received scan results (14 BSSes)
D/wpa_supplicant( 1345): nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
I/wpa_supplicant( 1345): [NULL] f0:f2:6d:22:99:3e freq=2442 level=-48
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:6b freq=5320 level=-53
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:6f freq=5320 level=-53
I/wpa_supplicant( 1345): [NULL] f4:f2:6d:22:99:3e freq=2442 level=-53
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:70:c3 freq=2462 level=-64
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:62 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:64 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:60 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:dd:e0 freq=2437 level=-72
I/wpa_supplicant( 1345): [NULL] 00:16:a6:1f:06:5c freq=2462 level=-81
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:63 freq=2412 level=-64
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:70:c5 freq=2462 level=-65
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-72
I/wpa_supplicant( 1345): [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-82
D/wpa_supplicant( 1345): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1345): BSS: last_scan_res_used=14/32
D/wpa_supplicant( 1345): wlan0: Scan-only results received
D/wpa_supplicant( 1345): wlan0: Radio work 'scan'@0x55a9a840f0 done in 0.086835 seconds
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  945): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  945): handleMessage: E msg.what=147461
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
E/WifiStateMachine(  945): processMsg: ConnectModeState
E/WifiStateMachine(  945):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
E/WifiStateMachine(  945): processMsg: DriverStartedState
E/WifiStateMachine(  945):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
E/WifiStateMachine(  945): processMsg: SupplicantStartedState
E/WifiStateMachine(  945):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
D/WifiStateMachine(  945): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1345): wlan0: Control interface command 'LIST_DONGLES'
I/CheckinRequestBuilder( 4493): Checkin reason type: 11 attempt count: 1
E/WifiStateMachine(  945): [1,457,619,761,005 ms] noteScanEnd no scan source
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1345): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  945): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@305b6b26 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinContr,oller (  945): NG700 f4:f2:6d:22:99:3e rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  945): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  945): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  945):         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-53 freq=2442
E/WifiAutoJoinController (  945): NG700_GUEST f0:f2:6d:22:99:3e rssi=-48 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1f:27:54:70:c3 rssi=-64 cap [WPA-PSK-TKIP][WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1f:27:54:dd:e0 rssi=-72 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:16:a6:1f:06:5c rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/ActivityThread( 4493): Failed to find provider info for com.google.android.wearable.settings
E/WifiAutoJoinController (  945): RA-WINGS 00:1e:4a:8f:e3:63 rssi=-64 cap [ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:1f:27:54:70:c5 rssi=-65 cap [ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:1f:27:54:dd:e3 rssi=-72 cap [ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:6b rssi=-53 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:6f rssi=-53 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:62 rssi=-66 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:64 rssi=-66 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:60 rssi=-66 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:22:0d:46:1c:a3 rssi=-82 cap [ESS] is not scored
E/WifiAutoJoinController (  945): ageScanResultsOut delay 40000 size 14 now 1457619761010
E/WifiAutoJoinController (  945): newSupplicantResults size=14 known=1 true
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1345): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  945): attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
E/WifiAutoJoinController (  945): ssid=NG700
E/WifiAutoJoinController (  945): id=0
E/WifiAutoJoinController (  945): mode=station
E/WifiAutoJoinController (  945): pairwise_cipher=CCMP
E/WifiAutoJoinController (  945): group_cipher=CCMP
E/WifiAutoJoinController (  945): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  945): wpa_state=COMPLETED
E/WifiAutoJoinController (  945): ip_address=192.168.1.102
E/WifiAutoJoinController (  945): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  945): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  945): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  945): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  945): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-53,-127) num=(1,0)
E/WifiAutoJoinController (  945): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  945): attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-53 freq=2442 Current: f4:f2:6d:22:99:3e
D/HtcWifiControlRoamOffload: (  945): roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
E/WifiStateMachine(  945): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  945): Done attemptAutoJoin status=0
E/WifiConfigStore(  945):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  945): handleMessage: X
,I/GLSUser ( 1919): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1919): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1919): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1919): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4493): awaiting user notification for token
,D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1326): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
,I/ActivityManager(  945): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6638 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 6638): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6638): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:369] from screen [on:0 period:1625847940] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
,E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625847941] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
I/MultiDex( 6638): VM with version 2.1.0 has multidex support
I/MultiDex( 6638): install
I/MultiDex( 6638): VM has multidex support, MultiDex support library is disabled.
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.13 txretriesrate=0.00 rxrate=1.48 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
E/WifiStateMachine(  945): handleMessage: X
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
,D/Finsky  ( 5956): [607] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5956): [1] 5.onFinished: Installation state replication succeeded.
,I/art     ( 1919): Explicit concurrent mark sweep GC freed 9727(519KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 974us total 52.031ms,
,V/JNIHelp ( 6638): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6638): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5ccc9b6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 6638): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 6638): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1919): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1919): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4493): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 4863): callingUid 10024, callindPid: 4863
,I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4493, uid=10024, userID:0
,E/MDM     ( 1777): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=254
E/WifiTrafficPoller(  945): notifying of data activity 0
D/WIFI_ICON( 1223): WifiActivity: 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/WVCdm   (  421): CdmEngine::OpenSession,
I/WVCdm   (  421): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  421): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/LocationInitializer( 4493): Restart initialization of location,
,D/DrmWidevineDash(  421): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  421): Service_Initialize: starts!
D/QSEECOMAPI: (  421): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  421): App is not loaded in QSEE
E/QSEECOMAPI: (  421): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  421): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  421): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  421): App is not loaded in QSEE
,I/HtcModeClient( 3303): handler message = 4011
,E/HtcModeClient( 3303): Check connection and retry 12 times.
,D/QSEECOMAPI: (  421): Loaded image: APP id = 8,
D/DrmWidevineDash(  421): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  421): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  421): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  421): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf45bc000
E/DrmWidevineDash(  421): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf45bc000
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  505): got the req here! ret=0
D/DrmLibTime(  505): command id, time_cmd_id = 770
D/DrmLibTime(  505): time_getutcsec starts!
D/DrmLibTime(  505): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  505): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  505): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  505): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  505): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  505): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  505): QSEE Time Listener: Retrieved Android system time: 1457619761
D/DrmLibTime(  505): time_getutcsec returns 0, sec = 1457619761; nsec = 0
D/DrmLibTime(  505): time_getutcsec finished! 
E/QC-time-services(  472): Daemon: Time-services: Waiting to acceptconnection
D/DrmLibTime(  505): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  505): before calling ioctl to read the next time_cmd
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  421): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  421): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): hlos api version =  9
D/DrmWidevineDash(  421): tz api version =  9
D/DrmWidevineDash(  421): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  421): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  421): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  421): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  421): OEMCrypto_OpenSession: starts! SID=0xf34a5928
D/DrmWidevineDash(  421): OEMCrypto_OpenSession Session ID = 0,
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  421): OEMCrypto_OpenSession: ends! returns 0,
D/DrmWidevineDash(  421): OEMCrypto_GetRandom: starts! randomData=0xaae87050, dataLength=8
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaae5cf50, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  421): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  421): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  421): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  421): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  421): OEMCrypto_GetDeviceID: starts! deviceID=0xaae557d8, idLength=0xffa82c08
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  421): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  421): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  421): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_GetHDCPCapability: starts!, current = 0xffa82c1e, maximum = 0xffa82c1f
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): hlos api version =  9
D/DrmWidevineDash(  421): tz api version =  9
,D/DrmWidevineDash(  421): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  421): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffa82c8c
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  421): PrepareKeyRequest: nonce=2955258381
D/DrmWidevineDash(  421): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaae6bd58
D/DrmWidevineDash(  421): message_length=1611, signature=0xaae6c3a8, signature_length=0xffa82bec
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  421): CdmEngine::CloseSession
D/DrmWidevineDash(  421): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  421): L3 Terminate.
D/DrmWidevineDash(  421): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): Service_Uninitialize: starts!
D/QSEECOMAPI: (  421): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  421): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  421): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  421): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  421): CdmEngine::OpenSession,
I/WVCdm   (  421): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  421): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  421): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
,D/DrmWidevineDash(  421): Service_Initialize: starts!
D/QSEECOMAPI: (  421): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  421): App is not loaded in QSEE
E/QSEECOMAPI: (  421): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  421): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  421): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  421): App is not loaded in QSEE
,D/QSEECOMAPI: (  421): Loaded image: APP id = 9
,D/DrmWidevineDash(  421): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  421): qsapps_get_capabilities: Capability from secure side: 0x0
,D/QSAPPSVER(  421): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  421): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf45bc000
E/DrmWidevineDash(  421): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf45bc000
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  505): got the req here! ret=0,
D/DrmLibTime(  505): command id, time_cmd_id = 770
D/DrmLibTime(  505): time_getutcsec starts!
D/DrmLibTime(  505): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  505): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  505): QSEE Time Listener: time_get_modem_time,
D/DrmLibTime(  505): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  505): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  505): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  505): QSEE Time Listener: Retrieved Android system time: 1457619762
,D/DrmLibTime(  505): time_getutcsec returns 0, sec = 1457619762; nsec = 0
D/DrmLibTime(  505): time_getutcsec finished! 
D/DrmLibTime(  505): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  505): before calling ioctl to read the next time_cmd
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
E/QC-time-services(  472): Daemon: Time-services: Waiting to acceptconnection
,D/DrmWidevineDash(  421): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): hlos api version =  9
D/DrmWidevineDash(  421): tz api version =  9
D/DrmWidevineDash(  421): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  421): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  421): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  421): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  421): OEMCrypto_OpenSession: starts! SID=0xf34a5928
D/DrmWidevineDash(  421): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  421): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_GetRandom: starts! randomData=0xaaf73958, dataLength=8
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaae5d440, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  421): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  421): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  421): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  421): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  421): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  421): OEMCrypto_GetDeviceID: starts! deviceID=0xaae557f8, idLength=0xf48316f8
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  421): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  421): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  421): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_GetHDCPCapability: starts!, current = 0xf483170e, maximum = 0xf483170f,
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  421): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  421): hlos api version =  9
D/DrmWidevineDash(  421): tz api version =  9
D/DrmWidevineDash(  421): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  421): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf483177c
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  421): PrepareKeyRequest: nonce=1426046194
D/DrmWidevineDash(  421): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaae6bd58
D/DrmWidevineDash(  421): message_length=1642, signature=0xaae6c3c8, signature_length=0xf48316dc
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  421): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  421): CdmEngine::CloseSession,
D/DrmWidevineDash(  421): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  421): L3 Terminate.,
D/DrmWidevineDash(  421): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  421): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  421): Service_Uninitialize: starts!,
D/QSEECOMAPI: (  421): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  421): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  421): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  421): OEMCrypto_Terminate: ends! returns 0
,E/cutils-trace( 6671): Error opening trace file: Permission denied (13),
I/dex2oat ( 6671): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6671): dex2oat: override thread count:4
,I/dex2oat ( 6671): dex2oat took 40.229ms (threads: 4),
,I/Adreno-EGL( 6638): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6638): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6638): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6638): Local Branch: 
I/Adreno-EGL( 6638): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6638): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6638):                  d74aa161a12b9c6fc6332151
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=201 Rx=254
,I/Adreno-EGL( 6638): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6638): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6638): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6638): Local Branch: 
I/Adreno-EGL( 6638): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6638): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6638):                  d74aa161a12b9c6fc6332151
,I/CheckinRequestBuilder( 4493): Classify the device as Phone.
,D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4493): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4493): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4493): [NET] android_getaddrinfo_proxy+
D/libc    ( 4493): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  413): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  413): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  413): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  413): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4493): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4493): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4493): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4493): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4493): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4493): Sending checkin request (9981 bytes),
,I/CheckinRequestBuilder( 4493): Checkin reason type: 11 attempt count: 1,
I/ActivityManager(  945): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 4493): Failed to find provider info for com.google.android.wearable.settings
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=268
E/WifiTrafficPoller(  945): notifying of data activity 3
D/WIFI_ICON( 1223): WifiActivity: 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/GLSUser ( 1919): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1919): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1919): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1919): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1326): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 4493): awaiting user notification for token
,I/CheckinRequestBuilder( 4493): Classify the device as Phone.
,I/CheckinTask( 4493): Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,I/CheckinService( 4493): Checking schedule, now: 1457619763740 next: 1458156595730
,I/CheckinService( 4493): active receiver: disabled
I/PackageManager(  945):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4493, uid=10024, userID:0
,D/PMS     (  945): releaseWL(c631161): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4493): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4493): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/GCM     ( 1919): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,I/art     (  945): Explicit concurrent mark sweep GC freed 33530(2MB) AllocSpace objects, 7(268KB) LOS objects, 33% free, 18MB/27MB, paused 2.028ms total 196.159ms,
,I/RemoteViews( 1223): reapply : com.google.android.gms 2 40
,E/WifiDataStallTracker(  945): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  945): updateDataStallInfo: mDataStallTxRxSum={txSum=198 rxSum=193} preTxRxSum={txSum=181 rxSum=180}
,D/WifiDataStallTracker(  945): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  945): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1625850962] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1625850964] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0,
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=11 [17][2][0]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
,E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.56 txretriesrate=0.00 rxrate=7.74 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  945):  isHighRSSI       ---> score=65
E/WifiStateMachine(  945): handleMessage: X
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=268
E/WifiTrafficPoller(  945): notifying of data activity 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=268
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
D/WIFI_ICON( 1223): WifiActivity: 1
E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=269
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  945): notifying of data activity 1
,I/HtcModeClient( 3303): handler message = 4011
,D/Process (  945): killProcessQuiet, pid=6404
I/ActivityManager(  945): Killing 6404:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/HtcModeClient( 3303): Check connection and retry 12 times. Stop service and kill this process.
,I/ActivityManager(  945): Recipient 6404
,D/HtcModeClient( 3303): Don't start project servcice
,D/HtcModeClient( 3303): setEject: MEDIA_EJECT_STATE = true,
D/HtcModeClient( 3303): connectState: CONNECTION_READY = false
D/SilentMusic( 3303): call stop
D/HtcModeClient( 3303): close connection
,W/HtcModeClient( 3303): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3303): read the terminate packet, so break
I/ActivityManager(  945): Killing 3303:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=3303
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 3303
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=8.6, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1625853984] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=8.6, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1625853986] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=4.28 txretriesrate=0.00 rxrate=4.37 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
,E/WifiStateMachine(  945): handleMessage: X
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=269
D/WIFI_ICON( 1223): WifiActivity: 0
E/WifiTrafficPoller(  945): notifying of data activity 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=269
,I/ActivityManager(  945): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6683 uid=10076 gids={50076, 9997} abi=arm64-v8a
,D/PMS     (  945): acquireWL(29e0d441): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{10076}
V/AlarmManager(  945): sending alarm PendingIntent{ac5de6: PendingIntentRecord{13e43f27 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457619768865, Int=60000
D/PMS     (  945): releaseWL(29e0d441): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,E/WifiDataStallTracker(  945): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  945): updateDataStallInfo: mDataStallTxRxSum={txSum=198 rxSum=193} preTxRxSum={txSum=198 rxSum=193}
D/WifiDataStallTracker(  945): updateDataStallInfo: NONE
D/WifiDataStallTracker(  945): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/SMSBackup( 6683): SMSBackupAgentService started
D/SMSBackup( 6683): Checking restore status
,D/SMSBackup( 6683): Restore complete
,D/SMSBackup( 6683): cancelCheckAlarm
,D/SMSBackup( 6683): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  945): killProcessQuiet, pid=5998
I/ActivityManager(  945): Killing 5998:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 5998
,E/WifiStateMachine(  945): WiFiStateMachine SCAN ALARM
D/PMS     (  945): acquireWL(f25737d): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{1000}
E/WifiStateMachine(  945): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  945): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  945):     Client/Owner: Client
D/WifiDisplayAdapter(  945):     GroupId: 
D/WifiDisplayAdapter(  945):     Passphrase: 
D/WifiDisplayAdapter(  945):     SessionId: 0
D/WifiDisplayAdapter(  945):     IP Address: }
E/WifiStateMachine(  945): processMsg: ConnectedState
V/AlarmManager(  945): sending alarm PendingIntent{141b14e7: PendingIntentRecord{21907894 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1457619769122, Int=20000
,E/WifiStateMachine(  945):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):0 dur:91 rssi=-53 f=2442 sc=60 link=150 tx=4.3, 0.0, 0.0  rx=4.4 list=2442 [on:0 tx:0 rx:0 period:1810] from screen [on:0 period:1625855813]
D/PMS     (  945): releaseWL(f25737d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:91 rssi=-53 f=2442 sc=60 link=150 tx=4.3, 0.0, 0.0  rx=4.4 list=2442 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625855814]
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.28 rxSuccessRate=4.37 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-53
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN with age=27727 interval=60000 maxinterval=300000
E/WifiStateMachine(  945): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  945): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  945): has f4:f2:6d:22:99:3e freq=2442 age=1814 ?=true
E/WifiStateMachine(  945): WifiStateMachine starting scan for "NG700"WPA_PSK with 2442
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2442"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2442'
D/wpa_supplicant( 1345): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1345): wpa_supplicant_scan enter
D/wpa_supplicant( 1345): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1345): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1345): WPS:  * Version (hardcoded 0x10),
D/wpa_supplicant( 1345): WPS:  * Request Type
D/wpa_supplicant( 1345): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1345): WPS:  * UUID-E
D/wpa_supplicant( 1345): WPS:  * Primary Device Type
D/wpa_supplicant( 1345): WPS:  * RF Bands (3)
D/wpa_supplicant( 1345): WPS:  * Association State
D/wpa_supplicant( 1345): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1345): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1345): WPS:  * Manufacturer
D/wpa_supplicant( 1345): WPS:  * Model Name
D/wpa_supplicant( 1345): WPS:  * Model Number
D/wpa_supplicant( 1345): WPS:  * Device Name
,D/wpa_supplicant( 1345): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1345): P2P: * P2P IE header
D/wpa_supplicant( 1345): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1345): P2P: * Listen Channel: Regulatory Class 81 Channel 6
D/wpa_supplicant( 1345): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1345): wlan0: Add radio work 'scan'@0x55a9a60860
D/wpa_supplicant( 1345): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1345): wlan0: Starting radio work 'scan'@0x55a9a60860 after 0.000040 second wait
D/wpa_supplicant( 1345): wlan0: nl80211: scan request
D/wpa_supplicant( 1345): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1345): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1345): wlan0: nl80211: Scan trigger
,D/wpa_supplicant( 1345): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1345): wlan0: Own scan request started a scan in 0.000083 seconds
I/wpa_supplicant( 1345): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  945): [1,457,619,769,160 ms] noteScanstart no scan source
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  945): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  945): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  945): handleMessage: X
,D/wpa_supplicant( 1345): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/wpa_supplicant( 1345): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1345): nl80211: Scan included frequencies: 2442
D/wpa_supplicant( 1345): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1345): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1345): wlan0: Scan completed in 0.081318 seconds
D/wpa_supplicant( 1345): nl80211: Associated on 2442 MHz
D/wpa_supplicant( 1345): nl80211: Associated with f4:f2:6d:22:99:3e
D/wpa_supplicant( 1345): nl80211: Received scan results (14 BSSes)
D/wpa_supplicant( 1345): nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
I/wpa_supplicant( 1345): [NULL] f0:f2:6d:22:99:3e freq=2442 level=-48
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:6b freq=5320 level=-53
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:6f freq=5320 level=-53
I/wpa_supplicant( 1345): [NULL] f4:f2:6d:22:99:3e freq=2442 level=-53
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:70:c3 freq=2462 level=-64
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:62 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:64 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:60 freq=2412 level=-66
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:dd:e0 freq=2437 level=-72
I/wpa_supplicant( 1345): [NULL] 00:16:a6:1f:06:5c freq=2462 level=-81
I/wpa_supplicant( 1345): [NULL] 00:1e:4a:8f:e3:63 freq=2412 level=-64
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:70:c5 freq=2462 level=-65
I/wpa_supplicant( 1345): [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-72
I/wpa_supplicant( 1345): [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-82
D/wpa_supplicant( 1345): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1345): BSS: last_scan_res_used=14/32
D/wpa_supplicant( 1345): wlan0: Scan-only results received
D/wpa_supplicant( 1345): wlan0: Radio work 'scan'@0x55a9a60860 done in 0.082491 seconds
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  945): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  945): handleMessage: E msg.what=147461
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
E/WifiStateMachine(  945): processMsg: ConnectModeState
E/WifiStateMachine(  945):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
E/WifiStateMachine(  945): processMsg: DriverStartedState
E/WifiStateMachine(  945):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
E/WifiStateMachine(  945): processMsg: SupplicantStartedState
E/WifiStateMachine(  945):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=14 known=1 got=14 bcn=0
D/WifiStateMachine(  945): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1345): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  945): [1,457,619,769,246 ms] noteScanEnd no scan source
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1345): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  945): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@305b6b26 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  945): NG700 f4:f2:6d:22:99:3e rssi=-53 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/Wif,iConfigStore(  945): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  945): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  945):         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-53 freq=2442
E/WifiAutoJoinController (  945): NG700_GUEST f0:f2:6d:22:99:3e rssi=-48 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1f:27:54:70:c3 rssi=-64 cap [WPA-PSK-TKIP][WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1f:27:54:dd:e0 rssi=-72 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:16:a6:1f:06:5c rssi=-81 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:1e:4a:8f:e3:63 rssi=-64 cap [ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:1f:27:54:70:c5 rssi=-65 cap [ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:1f:27:54:dd:e3 rssi=-72 cap [ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:6b rssi=-53 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:6f rssi=-53 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:62 rssi=-66 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:64 rssi=-66 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945):  00:1e:4a:8f:e3:60 rssi=-66 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  945): RA-WINGS 00:22:0d:46:1c:a3 rssi=-82 cap [ESS] is not scored
E/WifiAutoJoinController (  945): ageScanResultsOut delay 40000 size 14 now 1457619769252
E/WifiAutoJoinController (  945): newSupplicantResults size=14 known=1 true
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1345): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  945): attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
E/WifiAutoJoinController (  945): ssid=NG700
E/WifiAutoJoinController (  945): id=0
E/WifiAutoJoinController (  945): mode=station
E/WifiAutoJoinController (  945): pairwise_cipher=CCMP
E/WifiAutoJoinController (  945): group_cipher=CCMP
E/WifiAutoJoinController (  945): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  945): wpa_state=COMPLETED
E/WifiAutoJoinController (  945): ip_address=192.168.1.102
E/WifiAutoJoinController (  945): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  945): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  945): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  945): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  945): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-53,-127) num=(1,0)
E/WifiAutoJoinController (  945): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  945): attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-53 freq=2442 Current: f4:f2:6d:22:99:3e
D/HtcWifiControlRoamOffload: (  945): roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
E/WifiStateMachine(  945): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  945): Done attemptAutoJoin status=0
E/WifiConfigStore(  945):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  945): handleMessage: X
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=277
,E/WifiTrafficPoller(  945): notifying of data activity 1
D/WIFI_ICON( 1223): WifiActivity: 1
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=4.3, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:1188] from screen [on:0 period:1625857005] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=4.3, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625857006] gl hn u24 rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0],
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
,E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.14 txretriesrate=0.00 rxrate=9.68 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
E/WifiStateMachine(  945): handleMessage: X
D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7,
E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=284
,I/Prism.ItemManager( 1620): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1620): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1620): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/AccTypeManager( 1742): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/PMS     (  945): acquireWL(20cba6c3): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6535 10112 null
W/SystemReader(  945): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1742): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  945): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PMS     (  945): releaseWL(20cba6c3): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PhoneApp( 1558): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AccTypeManager( 1742): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1538): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1538): handle notify Blinkfeed plugin client changed
W/ResourcesManager( 6535): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6535): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ExternalAccountType( 1742): Unsupported attribute readOnly,
,D/PackageBroadcastService( 4493): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
I/PackageBroadcastService( 4493): Null package name or gms related package.  Ignoreing.
,D/PMS     (  945): acquireWL(1f5de5ff): PARTIAL_WAKE_LOCK  Icing 0x1 4493 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(1948cfcc): PARTIAL_WAKE_LOCK  AsyncService 0x1 6473 10167 null,
I/Icing   ( 4493): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  945): releaseWL(1948cfcc): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,D/PMS     (  945): acquireWL(16d2092a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6473 10167 null
,I/UpdateIcingCorporaServi( 5877): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
,D/PMS     (  945): releaseWL(1f5de5ff): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(16d2092a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,W/PackageManager(  945): Unable to load service info ResolveInfo{cf665ce com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  945): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  945): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  945): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  945): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  945): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  945): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  945): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  945): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  945): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  945): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  945): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  945): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/UpdateIcingCorporaServi( 5877): UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
,V/GmsNetworkLocationProvi( 1777): DISABLE,
,I/GCoreNlp( 1777): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  945): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,D/PMS     (  945): acquireWL(2b4d3216): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(2b4d3216): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): acquireWL(8253797): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  945): releaseWL(8253797): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  945): applying state to connected service
,D/LocationProviderProxy(  945): applying state to connected service
,D/PMS     (  945): acquireWL(27b06dee): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(27b06dee): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  945): acquireWL(1bb1828f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): releaseWL(1bb1828f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1223): WifiActivity: 0
,E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=284
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  945): notifying of data activity 0
,I/Prism.ItemManager( 1620): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1620): loadItems() com.htc.launcher.pageview.WidgetManager@374cfd15 +,
I/Prism.WidgetManager( 1620): onLoadItems() +
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=286
E/WifiTrafficPoller(  945): notifying of data activity 1
D/WIFI_ICON( 1223): WifiActivity: 1
,D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/Prism.WidgetManager( 1620): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1620): onLoadItems() -
I/Prism.ItemManager( 1620): loadItems() com.htc.launcher.pageview.WidgetManager@374cfd15 -
,D/PhoneApp( 1558): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1558): -- N1 =0
,D/PhoneApp( 1558): -- N2 =0
,D/PhoneApp( 1558): -- N3 =0,
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155,
E/WifiStateMachine(  945): processMsg: ConnectedState
,E/WifiStateMachine(  945):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=2.1, 0.0, 0.0  rx=9.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1625860029] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=2.1, 0.0, 0.0  rx=9.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1625860031] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945):  get link layer stats 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
E/WifiStateMachine(  945): calculateWifiScore freq=2442 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.07 txretriesrate=0.00 rxrate=5.84 userTriggerdPenalty0
E/WifiStateMachine(  945):  good link -> stuck count =0
E/WifiStateMachine(  945):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  945):  isHighRSSI       ---> score=61
E/WifiStateMachine(  945): handleMessage: X
,D/WifiWatchdogStateMachine(  945): RSSI current: 3 new: -53, 3
D/WIFI_ICON( 1223): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL true Token 11 num clients 7
E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=286
E/WifiTrafficPoller(  945): notifying of data activity 0
D/WIFI_ICON( 1223): WifiActivity: 0
D/StatusBar.NetworkController( 1223): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  945): Going to sleep due to screen timeout (uid 1000)...,
I/SensorManager(  945): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2ebb4b1e
D/ActivityManager(  945): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{29f6591c #11 A=.Prism U=0 sz=1},
W/SensorService(  945): Following SensorService logs are not warning, just make sure they are printed
W/PMS     (  945): mWirelessDisplayManager is null
W/SensorService(  945): disable: get sensor name = Accelerometer Sensor
W/PMS     (  945): mWirelessDisplayManager is still null
,W/SensorService(  945): pid=945, uid=1000
W/PMN     (  945): goingToSleep
W/SensorService(  945): Active sensors: size = 4
W/SensorService(  945): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  945): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  945): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  945): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  945): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2ebb4b1e, eanble = 0, strlen(mName) = 91
W/SensorService(  945): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  945): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3c77cc77
W/SensorService(  945): Listener[1] = com.htc.smartdim.sensor_eye@375e23a
W/SensorService(  945): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/PMS     (  945): Sleeping (uid 1000)...
D/XAN-DPS (  945): prepareColorFade 1
,D/PMS     (  945): acquireWL(34b2a925): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 945 1000 null
,W/PMN     (  945): goingToSleep done,
,I/FeedHostManager( 1620): [onPause]
I/FeedProviderManager( 1620): onPause
I/FeedHostManager( 1620): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@280b325a
I/SocialFeedProvider( 1620): +onPause
I/SocialFeedProvider( 1620): -onPause
I/Adreno-EGL(  945): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  945): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  945): Build Date: 03/09/15 Mon
I/Adreno-EGL(  945): Local Branch: 
I/Adreno-EGL(  945): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  945): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  945):                  d74aa161a12b9c6fc6332151
,W/HtcLockScreen( 1223): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/HtcSystemUPManager(  945): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
I/ActivityManager(  945): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6719 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/AlarmManager(  945): ACTION_SCREEN_ON
,D/PMS     (  945): releaseWL(34b2a925): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null,
,I/AlarmManager(  945): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  945): [AlarmQueuing] done recovering
I/AlarmManager(  945): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  945): [AlarmQueuing] done EPS screen off alarm recovering
E/WifiTrafficPoller(  945): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  945):  packet count Tx=218 Rx=286
,E/WifiDataStallTracker(  945): ENABLE_DATA_MONITOR_POLL true Token 1,
,E/WifiStateMachine(  945): handleMessage: E msg.what=131167
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
D/WifiDataStallTracker(  945): updateDataStallInfo: mDataStallTxRxSum={txSum=198 rxSum=193} preTxRxSum={txSum=198 rxSum=193}
D/WifiDataStallTracker(  945): updateDataStallInfo: NONE
D/WifiDisplayAdapter(  945): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  945):     Client/Owner: Client
D/WifiDisplayAdapter(  945):     GroupId: 
D/WifiDisplayAdapter(  945):     Passphrase: 
D/WifiDisplayAdapter(  945):     SessionId: 0
D/WifiDisplayAdapter(  945):     IP Address: }
D/WifiDataStallTracker(  945): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  945): processMsg: ConnectModeState
E/WifiStateMachine(  945):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  945): processMsg: DriverStartedState
E/WifiStateMachine(  945):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  945): processMsg: SupplicantStartedState
E/WifiStateMachine(  945):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  945): processMsg: DefaultState
E/WifiStateMachine(  945):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  945):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1345): SET_SCREEN_ON:On
I/wpa_supplicant( 1345): htc_wext_set_keepalive +
I/wpa_supplicant( 1345): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1345): getPrivFuncNum +	
I/wpa_supplicant( 1345): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1345): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1345): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1345): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1345): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  945): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  945): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  945): handleScreenStateChanged Exit: true
E/WifiStateMachine(  945): handleMessage: X
E/WifiStateMachine(  945): handleMessage: E msg.what=131154
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
V/SRS_Proc(  421): ParamSet string: screen_state=on
E/audio_a2dp_hw(  421): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  945):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1345): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1345): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  945): fetchRssiLinkSpeedAndFrequencyNative rssi=-53 linkspeed=150
E/WifiConfigStore(  945): updateConfiguration freq=2442 BSSID=f4:f2:6d:22:99:3e RSSI=-53 "NG700"WPA_PSK
E/WifiStateMachine(  945): handleMessage: X
E/WifiStateMachine(  945): handleMessage: E msg.what=131127
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  945): processMsg: ConnectModeState
E/WifiStateMachine(  945):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  945): handleMessage: X
E/WifiStateMachine(  945): handleMessage: E msg.what=131129
E/WifiStateMachine(  945): processMsg: ConnectedState
D/WifiController(  945): handleMessage: E msg.what=155650
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
E/WifiStateMachine(  945):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  945): processMsg: ConnectModeState
E/WifiStateMachine(  945):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1345): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1345): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  945): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=43 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  945): handleMessage: X
,D/NetworkPolicy(  945): updateScreenOn: false
,V/NetworkPolicy(  945): updateIfacesLocked()
D/NetworkManagementService(  945): isBandwidthControlEnabled: doneSignal.getCount()= 0
,W/ResourcesManager( 6719): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/GpsLocationProvider(  945): receive broadcast intent, action: android.intent.action.SCREEN_ON,
,E/WifiDataStallTracker(  945): DATA_MONITOR_POLL true Token 2,
,I/IntentController( 1223): receive(android.intent.action.SCREEN_ON,1,false),
,D/XAN-DPS (  945): prepareColorFade done
,D/XAN-DPS (  945): setBrightness to 0
,I/SensorManager(  945): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@3c77cc77,
W/SensorService(  945): Following SensorService logs are not warning, just make sure they are printed
D/PMS     (  945): acquireWL(1509b2a1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1326): [EventService]  onDisplayChanged: 0
I/DisplayManagerService(  945): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DotMatrix( 1326): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  945): Display changed displayId=0
W/SensorService(  945): disable: get sensor name = CM32181 Light sensor
D/PMS     (  945): acquireWL(33144cc6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
W/SensorService(  945): pid=945, uid=1000
W/SensorService(  945): Active sensors: size = 3
W/SensorService(  945): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  945): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  945): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  945): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@3c77cc77, eanble = 0, strlen(mName) = 67
W/SensorService(  945): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  945): Listener[0] = com.htc.smartdim.sensor_eye@375e23a
W/SensorService(  945): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  945): releaseWL(1509b2a1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(33144cc6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/CalendarProvider2( 6719): Created com.android.providers.calendar.CalendarAlarmManager@67a34fc(com.htc.providers.calendar.HtcCalendarProvider@35158785)
,D/AlarmManager(  945): ACTION_SCREEN_OFF,
I/AlarmManager(  945): [AlarmQueuing] screen off now: 
I/AlarmManager(  945): [AlarmQueuing] data connection: true
,I/AlarmManager(  945): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  945): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  945): stopDataStallAlarm 
E/WifiDataStallTracker(  945): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  945): handleMessage: E msg.what=131167
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  945): processMsg: ConnectModeState
E/WifiStateMachine(  945):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  945): processMsg: DriverStartedState
E/WifiStateMachine(  945):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  945): processMsg: SupplicantStartedState
E/WifiStateMachine(  945):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  945): processMsg: DefaultState
V/SRS_Proc(  421): ParamSet string: screen_state=off
,E/WifiStateMachine(  945):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  945):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  945): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
E/audio_a2dp_hw(  421): adev_set_parameters: ERROR: set param called even when stream out is null
D/wpa_supplicant( 1345): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1345): SET_SCREEN_ON:Off
I/wpa_supplicant( 1345): htc_wext_set_keepalive +
I/wpa_supplicant( 1345): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1345): getPrivFuncNum +	
I/wpa_supplicant( 1345): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1345): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1345): get_ip_address source addr = c0a80166
I/wpa_supplicant( 1345): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1345): htc_wext_set_keepalive - ret = 0
D/WifiDisplayAdapter(  945): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  945):     Client/Owner: Client
D/WifiDisplayAdapter(  945):     GroupId: 
D/WifiDisplayAdapter(  945):     Passphrase: 
D/WifiDisplayAdapter(  945):     SessionId: 0
D/WifiDisplayAdapter(  945):     IP Address: }
,E/WifiStateMachine(  945): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiController(  945): handleMessage: E msg.what=155651
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
D/WifiStateMachine(  945): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  945): handleScreenStateChanged Exit: false
E/WifiStateMachine(  945): handleMessage: X
E/WifiStateMachine(  945): handleMessage: E msg.what=131154
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  945): handleMessage: X
,D/NetworkPolicy(  945): updateScreenOn: false
V/NetworkPolicy(  945): updateIfacesLocked()
D/NetworkManagementService(  945): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/CalendarProvider2( 6719): wait start:true
,I/SensorManager( 1223): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@1baf323c, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  945): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  945): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  945): pid=1223, uid=10041,
W/SensorService(  945): Active sensors: size = 4
W/SensorService(  945): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  945): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  945): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  945): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  945): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@1baf323c, eanble = 1, strlen(mName) = 57
W/SensorService(  945): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  945): Listener[0] = com.htc.smartdim.sensor_eye@375e23a
W/SensorService(  945): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@1baf323c
W/SensorService(  945): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1326): [EventService] getTotalRam: 1842 Mb,
D/GpsLocationProvider(  945): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/IntentController( 1223): receive(android.intent.action.SCREEN_OFF,1,false)
D/ContactMessageStore( 1558): start background delete task...,
,D/ContactMessageStore( 1558): size: 0 , 0
D/ContactMessageStore( 1558): Background delete complete
,D/PMS     (  945): acquireWL(1112229b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(1112229b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): acquireWL(2a262638): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1777 10024 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6719): wait end:false,
D/PMS     (  945): releaseWL(2a262638): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/RemoteViews( 1223): setHTCTheme(com.htc.updater,true,33751145),
,I/ActivityManager(  945): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6750 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/RemoteViews( 1223): apply : com.htc.updater 1 11 0 36
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  945): Setting HAL interactive mode to false,
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  945): Excessive delay in setPowerMode(): 287ms
D/PMS     (  945): Setting HAL interactive mode to false done
,D/PMS     (  945): Setting HAL auto-suspend mode to true
D/PMS     (  945): Setting HAL auto-suspend mode done
,W/HtcSystemUPManager(  945): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/PMS     (  945): acquireWL(19338611): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(19338611): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/InputMethodManagerService(  945): screenObserver, isScreenOn=false
D/StatusBarManagerService(  945): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  945): Disable input method client, pid=1620
,D/HABCtrl (  945): TPE algorithm. remove timeout.
,D/PMS     (  945): OOBE c monitor 11
,I/InputManager(  945): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
I/IntentController( 1223): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1573): ScreenObserver: OFF
,D/HtcPowerSaver(  945): updateBatteryInfo
,I/PhoneStatusBar( 1223): setImeWindowStatus(false,false)
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): runPSCheck
,D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  945): >> updateStatus
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): handleMessage: E msg.what=155652
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  945): processMsg: DeviceActiveState
D/PMS     (  945): acquireWL(2fef7376): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1573 1027 null
D/WifiController(  945): processMsg: StaEnabledState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): processMsg: DefaultState
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  945): handleMessage: X
I/HtcPowerSaver(  945): << updateStatus
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1573): applyRouting - 0
D/NfcService( 1573): applyRouting -2
D/NfcService( 1573): applyRouting
D/NfcService( 1573): Ignore this applyRouting...
,D/PMS     (  945): releaseWL(2fef7376): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/ContextImpl( 6750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6750): MY_DEBUG = false,
,W/ContextImpl( 6750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,I/ClockController( 1223): stop clock update:screen off
,D/SmartSyncUtils( 6750): isEpsOn(), nState = 0,
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
D/PMS     (  945): acquireWL(4b9724d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6750 1000 null
,W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  945): Init customizeScreenOffDelayClass error
,W/ContextImpl( 6750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  945): releaseWL(4b9724d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 6750): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6750): isEpsOn(), nState = 0
,W/ContextImpl( 6750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 6750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 ,
I/SensorManager(  945): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@375e23a
W/SensorService(  945): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  945): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  945): pid=945, uid=1000,
W/SensorService(  945): Active sensors: size = 3
W/SensorService(  945): CM36686 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  945): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  945): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  945): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@375e23a, eanble = 0, strlen(mName) = 35
W/SensorService(  945): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  945): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1baf323c
W/SensorService(  945): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  945): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  945): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  945): pid=945, uid=1000
W/SensorService(  945): Active sensors: size = 2
W/SensorService(  945): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  945): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  945): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@375e23a, eanble = 0, strlen(mName) = 35
W/SensorService(  945): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  945): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1baf323c
W/SensorService(  945): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/ActivityThread(  945): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@16fb2eeb that was originally registered here. Are you missing a call to unregisterReceiver()?
,E/ActivityThread(  945): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@16fb2eeb that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  945): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  945): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  945): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  945): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  945): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  945): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  945): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  945): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  945): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  945): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  945): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  945): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  945): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  945): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  945): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  945): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  945): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  945): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/SensorManager(  945): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@375e23a
,D/TetherSettings( 5934): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5934): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5934): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5934): Cust_ConnectToPC   : spcsc>false
D/        ( 5934): Cust_ConnectToPC   : IPT>true
D/        ( 5934): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5934): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5934): Index of the first 1 = -1
W/ContextImpl( 5934): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  945): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6783 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,W/ContextImpl( 5934): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5934): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5934): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5934): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5934): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/art     (  428): Explicit concurrent mark sweep GC freed 8663(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 212us total 25.331ms
,D/SmartNS_Utility( 5934): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5934): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,I/PowerUsageList:PowerUsageHelper( 6750): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 187us total 21.375ms,
,D/PowerUsageList:BatterySipperExt( 6750): gen(), null == sipper.uidObj, userId = 0
,I/art     (  428): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 202us total 27.507ms,
,D/PowerUsageService( 6750): calcPower(), no data
,D/SmartSyncUtils( 6750): getMobilePolicyEnabled, result = true
,D/PowerUsageList:PowerUsageHelper( 6750): MY_DEBUG = false
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL false Token 13 num clients 7
,E/WifiTrafficPoller(  945): ADD_CLIENT: 8
,D/WifiService(  945): New client listening to asynchronous messages
,E/WifiTrafficPoller(  945): TRAFFIC_STATS_POLL false Token 13 num clients 8,
,I/CalendarProvider2( 6719): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,W/ContentResolver( 6719): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  945): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6808 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
D/Process (  945): killProcessQuiet, pid=6434
I/ActivityManager(  945): Killing 6434:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6434
,W/ResourcesManager( 6808): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6808): onCreate
D/ProviderChangeReceiver( 6808): ---------------------------------------------------
D/PMS     (  945): releaseWL(1cf98aec): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
D/ProviderChangeReceiver( 6808): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  945): killProcessQuiet, pid=6190
I/ActivityManager(  945): Killing 6190:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6808): start to updateAlertNotification!
,I/ActivityManager(  945): Recipient 6190
,D/WifiService(  945): Client connection lost with reason: 4
E/InputEventReceiver( 1397): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{f89a9b4 uid 10366 pid 6190} (c)'
,D/HtcAlertService( 6808): No fired or scheduled alerts
,D/HtcAlertUtils( 6808): -- cancelReminderNotification --
,D/HtcAlertUtils( 6808): broadcastExistReminder!
,D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  945): killProcessQuiet, pid=6510
I/ActivityManager(  945): Killing 6510:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6510
,D/Process (  945): killProcessQuiet, pid=6281
,I/ActivityManager(  945): Killing 6281:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1625863051] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
E/WifiStateMachine(  945):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1625863052] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): handleMessage: X
,I/ActivityManager(  945): Recipient 6281
,E/WifiStateMachine(  945): handleMessage: E msg.what=131155
E/WifiStateMachine(  945): processMsg: ConnectedState
E/WifiStateMachine(  945):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:495] from screen [on:0 period:1625863548] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): processMsg: L2ConnectedState
,E/WifiStateMachine(  945):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2442 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1625863552] gl hn u24 rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  945): handleMessage: X
,D/HtcUPManager( 1223): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  945): DATA_MONITOR_POLL false Token 3
,D/ContactMessageStore( 1558): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1558): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/Process (  945): killProcessQuiet, pid=5634,
I/ActivityManager(  945): Killing 5634:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 5634
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  945): acquireWL(3dab8450): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
,V/AlarmManager(  945): sending alarm PendingIntent{3af62d51: PendingIntentRecord{3a4629b6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120247, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{2a37e649: PendingIntentRecord{276d7b4e com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144346, Int=0
,D/PMS     (  945): releaseWL(3dab8450): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  945): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  945): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  945): acquireWL(1183746f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 945 1000 null,
,D/libc    (  945): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  945): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  945): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  945): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  945): [NET] android_getaddrinfo_proxy+
D/libc    (  945): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  413): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  413): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  413): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  413): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  945): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  945): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4,
,D/libc    (  945): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  945): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  945): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  945): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  945): acquireWL(237ce88b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 945 1000 null
D/GpsLocationProvider(  945):  [handleDownloadXtraData]inject done.
D/PMS     (  945): releaseWL(1183746f): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  945): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  945): releaseWL(237ce88b): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  945): acquireWL(118b8d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null,
I/BatteryService(  945): n_update end
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): releaseWL(118b8d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/PMS     (  945): runPSCheck
D/WifiController(  945): handleMessage: E msg.what=155652
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): processMsg: DeviceActiveState
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: StaEnabledState
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  945): processMsg: DefaultState
I/HtcPowerSaver(  945): << updateStatus
D/WifiController(  945): handleMessage: X
D/NotificationService(  945): plugged=true pluggin=true
D/WifiController(  945): battery changed pluggedType: 2
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  945): acquireWL(3f11581): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{1000},
V/AlarmManager(  945): sending alarm PendingIntent{4f9a626: PendingIntentRecord{164f8267 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457619831271, Int=0
D/PMS     (  945): acquireWL(3c401814): PARTIAL_WAKE_LOCK  *backup* 0x1 945 1000 null
D/PMS     (  945): releaseWL(3f11581): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  945): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  945): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  945): releaseWL(3c401814): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/TelephonyReceiver( 1558): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  945): acquireWL(221888bd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{3af62d51: PendingIntentRecord{3a4629b6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180247, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{3d49feb2: PendingIntentRecord{13c7de03 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=198151, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{b10a180: PendingIntentRecord{3049f3b9 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190664, Int=0
,D/PMS     (  945): acquireWL(11d553fe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(221888bd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On,
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  945): acquireWL(be0575f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): releaseWL(11d553fe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  945): releaseWL(be0575f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(2fa960f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(2fa960f1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(120de4d6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(120de4d6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(3f27d357): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(12a3ae44): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(3fdfb1ba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(3f27d357): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/Procstats( 4493): User is not opted-in to Usage & Diagnostics.
D/Diskstats( 4493): User is not opted-in to Usage & Diagnostics.
,D/PMS     (  945): releaseWL(3fdfb1ba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): releaseWL(12a3ae44): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): acquireWL(a41886b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(a41886b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(339dfc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(339dfc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(1e836861): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(1e836861): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(23c72f86): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(23c72f86): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  945): plugged=true pluggin=true
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  945): battery changed pluggedType: 2
D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  945): >> updateStatus
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/WifiController(  945): handleMessage: E msg.what=155652
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1223): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1538): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@24b58ba7
I/ActivityManager(  945): Killing 6564:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  945): killProcessQuiet, pid=6564
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6564
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1345): wlan0: BSS: Remove id 1 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 8 BSSID 00:1e:4a:8f:e3:6b SSID '\x00' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1345): wlan0: BSS: Remove id 9 BSSID 00:1e:4a:8f:e3:6f SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c3 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 10 BSSID 00:1e:4a:8f:e3:62 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 11 BSSID 00:1e:4a:8f:e3:64 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 12 BSSID 00:1e:4a:8f:e3:60 SSID '\x00' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:dd:e0 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 f0:f2:6d:22:99:3e]
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 4 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 f0:f2:6d:22:99:3e
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 5 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:e3:6b]
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:70:c5 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:e3:6b
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1e:4a:8f:e3:6f]
D/wpa_supplicant( 1345): wlan0: BSS: Remove id 13 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1e:4a:8f:e3:6f
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c3]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c3
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:1e:4a:8f:e3:62]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:1e:4a:8f:e3:62
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:1e:4a:8f:e3:64]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:1e:4a:8f:e3:64
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:60]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:60
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:e0]
,E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:e0
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:16:a6:1f:06:5c]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:16:a6:1f:06:5c
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1e:4a:8f:e3:63]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1e:4a:8f:e3:63
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:70:c5]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:70:c5
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:dd:e3]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:dd:e3
D/WifiMonitor(  945): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:22:0d:46:1c:a3]
E/WifiMonitor(  945): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:22:0d:46:1c:a3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  945): acquireWL(33ee4047): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
,I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(33ee4047): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/PMS     (  945): runPSCheck
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  945): >> updateStatus
,D/WifiController(  945): handleMessage: E msg.what=155652
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): handleMessage: X
,I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  945): acquireWL(31f13074): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{3af62d51: PendingIntentRecord{3a4629b6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240247, Int=0
,V/AlarmManager(  945): sending alarm PendingIntent{3856be12: PendingIntentRecord{3ec499e3 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457620001661, Int=0
,D/PMS     (  945): releaseWL(31f13074): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,I/art     ( 1620): Background sticky concurrent mark sweep GC freed 66646(4MB) AllocSpace objects, 6(632KB) LOS objects, 12% free, 32MB/37MB, paused 17.025ms total 76.457ms,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1919): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1919): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1919): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1919): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1919): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1326): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1326): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1223): reapply : com.google.android.gms 3 40,
,W/GLSActivity( 1919): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1919): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1919): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1919): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1919): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1919): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1919): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5956): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5956): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5956): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5956): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5956): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5956): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5956): 	at android.os.Binder.execTransact(Binder.java:454)
,I/art     (  945): Explicit concurrent mark sweep GC freed 48495(2MB) AllocSpace objects, 5(668KB) LOS objects, 33% free, 18MB/27MB, paused 2ms total 188.242ms
,W/System  ( 5956): Ignoring header User-Agent because its value was null.
,D/libc    ( 5956): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5956): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5956): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5956): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5956): [NET] android_getaddrinfo_proxy+
D/libc    ( 5956): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  413): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  413): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  413): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  413): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5956): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  945): acquireWL(2bd0b40d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000},
,V/AlarmManager(  945): sending alarm PendingIntent{3af62d51: PendingIntentRecord{3a4629b6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=360247, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{fc3bf1f: PendingIntentRecord{b8e026c android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=378212, Int=0
D/PMS     (  945): acquireWL(dc6cfc2): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 945 1000 null
D/PMS     (  945): acquireWL(22ffc1d3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 945 1000 null
,D/PMS     (  945): releaseWL(dc6cfc2): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  945): releaseWL(22ffc1d3): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  945): releaseWL(2bd0b40d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1558): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1558): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1558): sku_id=118
D/ContactMessageStore( 1558): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1558): start background delete task...
,D/ContactMessageStore( 1558): size: 0 , 0
,D/ContactMessageStore( 1558): Background delete complete
,D/PMS     (  945): acquireWL(10260110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(10260110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  945): updateBatteryInfo
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
I/HtcPowerSaver(  945): >> updateStatus
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): handleMessage: E msg.what=155652
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  945): processMsg: DeviceActiveState
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  945): processMsg: StaEnabledState
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  945): processMsg: DefaultState
I/HtcPowerSaver(  945): << updateStatus
D/WifiController(  945): handleMessage: X
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  945): acquireWL(16e18409): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{3af62d51: PendingIntentRecord{3a4629b6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=420247, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{1c36260e: PendingIntentRecord{3f7aa82f com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941992, Int=0
,I/bt-btm  ( 3145): Received oneshot timer event complete
D/PMS     (  945): acquireWL(29d21e3c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3145 1002 null
I/bt-btm  ( 3145): btm_ble_timeout
I/bt-btm  ( 3145): btm_gen_resolvable_private_addr
,D/bt-btm  ( 3145): btm_ble_rand_enc_complete
I/bt-btm  ( 3145): btm_gen_resolve_paddr_low
D/bt-smp  ( 3145): smp_encrypt_data
W/bt-smp  ( 3145): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3145): Plain text(LSB ~ MSB) = f3 5b 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3145): Encrypted text(LSB ~ MSB) = 61 88 03 b1 1b 6d 6c 2d 66 fb bb 06 d7 00 51 72 
I/bt-btm  ( 3145): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3145): Stopping oneshot timer
D/bt-btm  ( 3145): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  945): releaseWL(16e18409): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  945): releaseWL(29d21e3c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  945): acquireWL(321557c5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{3af62d51: PendingIntentRecord{3a4629b6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=960247, Int=0,
V/AlarmManager(  945): sending alarm PendingIntent{3b32951a: PendingIntentRecord{a13984b com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457620674426, Int=0
,D/SmartSyncUtils( 6750): isEpsOn(), nState = 0
,D/WeatherUtility( 1223): Weather sync is On
D/PMS     (  945): acquireWL(17c0e228): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6750 1000 null
W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data
,D/PMS     (  945): releaseWL(321557c5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6750): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6750): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6750): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6750): SettingOnTime = 1457676000000, randomSettingOnTime = 1457672412000
D/SmartSyncScreenOnOffTimeReceiver( 6750): SettingOffTime = 1457654400000, randomSettingOffTime = 1457657856000
,D/SmartSyncScreenOnOffTimeReceiver( 6750): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6750): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6750): bNightModeTurnOffOnce = false
,D/PMS     (  945): releaseWL(17c0e228): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  945): acquireWL(34f8ab41): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null,
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(34f8ab41): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  945): updateBatteryInfo
,D/PowerUI ( 1223): closing low battery warning: level=100,
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  945): plugged=true pluggin=true
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  945): runPSCheck
,I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  945): Checking...
D/UsbnetService(  945): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  945): >> updateStatus
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/WifiController(  945): battery changed pluggedType: 2
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  945): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  945): << updateStatus
D/WifiController(  945): handleMessage: E msg.what=155652
D/WifiController(  945): processMsg: DeviceActiveState
,D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  945): acquireWL(754e8e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 945 1000 WorkSource{1000}
V/AlarmManager(  945): sending alarm PendingIntent{c1c6ef3: PendingIntentRecord{14db77b0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805702, Int=0
,V/AlarmManager(  945): sending alarm PendingIntent{3af62d51: PendingIntentRecord{3a4629b6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1020247, Int=0
V/AlarmManager(  945): sending alarm PendingIntent{6016e27: PendingIntentRecord{1755f8d4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=938008, Int=0
,V/AlarmManager(  945): sending alarm PendingIntent{2963ba7d: PendingIntentRecord{3bf6ad72 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1457620716890, Int=1800000
,I/ActivityManager(  945): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6846 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  945): sending alarm PendingIntent{90cc5c3: PendingIntentRecord{3683ce40 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457620561110, Int=0
,V/AlarmManager(  945): sending alarm PendingIntent{24768179: PendingIntentRecord{35104b6f com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457620627914, Int=0,
,D/PMS     (  945): acquireWL(3e7e2ebe): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(3e7e2ebe): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  945): acquireWL(32ebfb1f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(2df78e6c): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4493 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1223): Weather sync is On
,W/WeatherTimeKeeper( 1223): [refreshWeatherData] no weather data,
,W/ContextImpl( 6750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  945): acquireWL(3e5f2a3b): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4493 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(2df78e6c): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(754e8e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6750): MY_DEBUG = false
,D/PowerUsageService( 6750): repeat time = 1457621617000
,I/EventLogService( 4493): Aggregate from 1457619760978 (log), 1457618916840 (data),
,D/PMS     (  945): acquireWL(26533f04): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(338fea0f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1919): Message class com.google.f.a.a.i
,D/PMS     (  945): releaseWL(338fea0f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(3e5f2a3b): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(24316a9c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 6750): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PMS     (  945): releaseWL(32ebfb1f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1919): Vacuum at: now=1457620717101 tag=VacuumService,
,D/PowerUsageList:BatterySipperExt( 6750): gen(), null == sipper.uidObj, userId = 0,
,D/Batterystats( 4493): User is not opted-in to Usage & Diagnostics.,
D/PMS     (  945): releaseWL(26533f04): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): acquireWL(14faa87a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(24316a9c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,E/cutils-trace( 6871): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6871): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6871): dex2oat: override thread count:4
,D/PowerUsageService( 6750): calcPower(), no data
,D/PMS     (  945): releaseWL(14faa87a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): acquireWL(166b182b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  945): releaseWL(166b182b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  945): acquireWL(9389488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1919 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  945): releaseWL(9389488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/dex2oat ( 6871): dex2oat took 925.323ms (threads: 4),
,I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6846): ApplicationMonitor {138e49a6}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6846): PnsModel {1e2c1701}: update(): Update registration caused by: alarm,
,I/PushClient( 6846): PnsConfigModel {1f32d52c}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6846): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6846): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6846): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6846): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  945): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6878 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6878): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6878 dbg=false s=true,
,I/DeviceManagement( 6878): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6878): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6878): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6878): WorkflowService: Starting workflow service
,I/DeviceManagement( 6878): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1e2c1701] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6878): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6878): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6878): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6878): SessionStateController: Checking invariants...
,I/DeviceManagement( 6878): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6878): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6878): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6878): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1e2c1701]
,I/DeviceManagement( 6878): WorkflowService: Stopping workflow service,
,D/Process (  945): killProcessQuiet, pid=5478
I/ActivityManager(  945): Killing 5478:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 5478
,I/PushClient( 6846): PnsModel {1e2c1701}: update(): The registration record has not expired yet. No need to update.
,D/Process (  945): killProcessQuiet, pid=6245
,I/ActivityManager(  945): Killing 6245:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  945): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  945): Recipient 6245,
,D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PMS     (  945): acquireWL(2072b2cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  945): n_update end
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  945): releaseWL(2072b2cc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): closing low battery warning: level=100
D/HtcPowerSaver(  945): updateBatteryInfo
D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
D/UsbnetService(  945): BroadcastReceiver::onReceive+
,D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): >> updateStatus
,D/WifiController(  945): processMsg: DeviceActiveState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: StaEnabledState
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  945): processMsg: DefaultState,
I/HtcPowerSaver(  945): << updateStatus
D/WifiController(  945): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  945): acquireWL(19187915): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
D/PMS     (  945): releaseWL(19187915): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  945): battery changed pluggedType: 2
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/PMS     (  945): runPSCheck
D/WifiController(  945): handleMessage: E msg.what=155652
D/HtcPowerSaver(  945): Checking...
D/WifiController(  945): processMsg: DeviceActiveState
I/HtcPowerSaver(  945): >> updateStatus
D/WifiController(  945): processMsg: StaEnabledState
D/PowerUI ( 1223): closing low battery warning: level=100
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  945): << updateStatus
,D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  945): User[0] Flushing usage stats to disk,
,D/PMS     (  945): acquireWL(1f8e242a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 945 1000 null
I/BatteryService(  945): n_update end
,D/PMS     (  945): releaseWL(1f8e242a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/HtcPowerSaver(  945): updateBatteryInfo
D/UsbnetService(  945): BroadcastReceiver::onReceive+
D/UsbnetService(  945): onReceive BATTERY_CHANGED
D/NotificationService(  945): plugged=true pluggin=true
D/UsbnetService(  945):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  945): runPSCheck
D/UsbnetService(  945): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  945): Checking...
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  945): >> updateStatus
D/DotMatrix( 1326): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1223): closing low battery warning: level=100
D/DotMatrix( 1326): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1223): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1223): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3145): Disconnected process message: 10, size: 0
D/WifiController(  945): handleMessage: E msg.what=155652
I/HtcPowerSaver(  945): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  945): processMsg: DeviceActiveState,
,I/HtcPowerSaver(  945): << updateStatus
D/WifiController(  945): processMsg: StaEnabledState
D/WifiController(  945): battery changed pluggedType: 2
D/WifiController(  945): processMsg: DefaultState
D/WifiController(  945): handleMessage: X
,I/BatteryController( 1223): status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1200000ms)
```
