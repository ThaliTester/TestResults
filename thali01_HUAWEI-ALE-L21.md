#### Test 503880197c51433_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/GCoreUlr( 4080): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 6394): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
I/art     ( 6394): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 6394): Can not find class: Lcom/google/android/gms/common/h/c;
I/art     ( 6394): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/HwCust  ( 6698): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 4080): Explicit concurrent mark sweep GC freed 30363(2015KB) AllocSpace objects, 18(360KB) LOS objects, 40% free, 17MB/29MB, paused 1.219ms total 80.393ms
I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/HwSystemManager( 3621): ContactsObserverHelper:Receive contacts change broadcast
I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/GCoreUlr( 4080): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 4080): Unbound from all location providers
I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/BaseAppContext( 6394): Using Auth Proxy for data requests.
I/GCoreUlr( 4080): DispatchingService.onDestroy()
I/GCoreUlr( 4080): Stopping handler for UlrDispSvcFast
I/ActivityManager( 2933): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
I/GCoreUlr( 4080): Unbound from all location providers
I/art     ( 6394): Explicit concurrent mark sweep GC freed 48118(3MB) AllocSpace objects, 35(700KB) LOS objects, 40% free, 17MB/29MB, paused 5.216ms total 178.753ms
I/wpa_supplicant( 3317): wlan0: HEART-BEAT-ACK: 1
E/WifiMonitor( 2933): WifiMonitor:wlan0 cnt=18 dispatchEvent: HEART-BEAT-ACK: 1
E/WifiStateMachine( 2933):  ConnectedState !what:147506 0 0
E/WifiStateMachine( 2933):  L2ConnectedState !what:147506 0 0
E/WifiStateMachine( 2933):  ConnectModeState !what:147506 0 0
E/WifiStateMachine( 2933):  DriverStartedState !what:147506 0 0
E/WifiStateMachine( 2933):  SupplicantStartedState !what:147506 0 0
W/Kids    ( 6394): [AbstractKidsOperation] Invalid device state 3
I/AuthZen ( 6394): Fetching signing key...
I/AuthZen ( 6394): Signing key fetched successfully!
W/BaseAppContext( 6394): Using Auth Proxy for data requests.
I/art     ( 4154): Explicit concurrent mark sweep GC freed 6987(398KB) AllocSpace objects, 3(60KB) LOS objects, 40% free, 17MB/29MB, paused 2.244ms total 79.381ms
W/GCoreFlp( 4080): No location to return for getLastLocation()
W/Auth    ( 4154): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
W/FusedLocationProvider( 6394): location=null
W/GCoreFlp( 4080): No location to return for getLastLocation()
I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/FusedLocationProvider( 6394): location=null
I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 6772): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/System.err( 2933): java.lang.SecurityException: WifiService: Neither user 10025 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2933): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2933): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2933): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2933): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2933): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2933): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2933): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 6772): WifiServiceMessenger == null
W/Settings( 6772): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6772): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PG Utils( 6772): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 6772): acquire_providerpkg:[com.android.providers.downloads] pid:[]  maybe timeout , send to PG
I/appproc ( 6802): CLASSPATH=/system/framework/am.jar
I/appproc ( 6802): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 6802): app_process:number,5,0
I/AndroidRuntime( 6802): readDownloadBoosterConfig: 'false'
I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10040
I/HwSystemManager( 3621): HoldService:uid:10040 pid:5976 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10040,5976
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10040, pid: 5976
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10040, pid: 5976
I/        ( 6802): power log dlsym ok
E/android_hardware_fm.cpp( 6802): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6802): ========64bit long size = 8
E/FM_HAL  ( 6802): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6802): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6802): 
I/fm_hisi ( 6802): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6802): 
I/fm_hisi ( 6802): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6802): 
E/android_hardware_fm.cpp( 6802): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 2933): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2933): Explicit concurrent mark sweep GC freed 19157(1052KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 28MB/42MB, paused 9.777ms total 238.087ms
I/art     ( 2933): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2933): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2933): Can not find class: Lcom/android/server/wm/StartingData;
I/art     ( 2933): Can not find class: Landroid/widget/ViewStub;
I/art     ( 2933): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 2933): Can not find class: Landroid/app/ViewStub;
I/HwLauncher( 3786): Launcher onPause()
I/HwLauncher( 3786): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3786): Launcher.MotionManager stopMotionAppsReco 403
W/HwLauncher( 3786): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
W/HwLauncher( 3786): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
I/PG Utils( 6818): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 2324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 451us total 31.662ms
I/art     ( 3786): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3786): Can not find class: Lhuawei/android/widget/EditText;
I/art     ( 2933): Can not find class: Lcom/android/server/am/ActivityStack$2;
E/textview( 3786): initAddtionalStyle default
I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 425us total 22.865ms
I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 458us total 23.515ms
I/PhoneStatusBar( 3268): shouldTranslucent:true
I/PhoneStatusBar( 3268): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwSystemManager( 3621): AppLockService:applock password not initial or function is closed
E/WifiStateMachine( 2933):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=58 tx=6.7, 0.0, 0.0  rx=12.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:894990854] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 2933):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=58 tx=6.7, 0.0, 0.0  rx=12.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:894990855] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
W/PGApi_client( 3655): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@cb46b11 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3655): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3655): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@22fffe25, action = com.huawei.pgmng.PGAction@cb46b11 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3655): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@cb46b11 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3655): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3655): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
E/WifiStateMachine( 2933): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=58 SSID="NG700"
E/WifiStateMachine( 2933): calculateWifiScore freq=2462 speed=58 score=100 highRSSI  -> txbadrate=0.00 txgoodrate=3.37 txretriesrate=0.00 rxrate=11.82 userTriggerdPenalty0
E/WifiStateMachine( 2933):  good link -> stuck count =0
E/WifiStateMachine( 2933):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine( 2933):  isHighRSSI       ---> score=61
W/AudioEffectLowPowerImpl jhh( 3655): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3655): return for smartPAOn and mLowAudioEffectEnable both = false
I/HwLauncher( 3786): Launcher onStop()
I/HwLauncher( 3786): Launcher dismissDialog
I/HwLauncher( 3786): Launcher dynamicIconsUnregister
I/HwLauncher( 3786): DynamicUpdater unregisterReceiver
I/HwLauncher( 3786): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3786): DynamicUpdater unregisterReceiver
I/HwLauncher( 3786): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3786): DynamicUpdater unregisterReceiver
I/HwLauncher( 3786): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3786): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3786): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3786): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3786): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3786): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/PG Utils( 6818): acquire_providerpkg:[com.google.android.partnersetup] pid:[]  maybe timeout , send to PG
E/WifiStateMachine( 2933):  ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):0 dur:279 rssi=-64 f=2462 sc=100 link=58 tx=3.4, 0.0, 0.0  rx=11.8 fiv=30000 [on:0 tx:0 rx:0 period:43] from screen [on:0 period:894990921]
E/WifiStateMachine( 2933):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=2 proc(ms):1 dur:279 rssi=-64 f=2462 sc=100 link=58 tx=3.4, 0.0, 0.0  rx=11.8 fiv=30000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:894990922]
E/WifiStateMachine( 2933): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.37 rxSuccessRate=11.82 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-64
E/WifiStateMachine( 2933): WifiStateMachine CMD_START_SCAN with age=23415 interval=30000 maxinterval=300000
E/WifiStateMachine( 2933): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine( 2933): WifiStateMachine starting scan for "NG700"WPA_PSK with 2462
I/wpa_supplicant( 3317): set current WIFI status to BT!
I/bluetooth-coex( 5313): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5313): set_bt_coex_mode_ext: wlan common protect scheduling
I/bluetooth-coex( 5313): btcoex_set_a2dp_priority: bdaddr: 000000000000
I/bluetooth-coex( 5313): btcoex_set_a2dp_priority: A2DP - no link control block
I/bluetooth-coex( 5313): set_bt_coex_mode_ext: wlan common protect, no need to set bt priority
I/wpa_supplicant( 3317): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2933): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2933): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 2933): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 2933): [1,448,298,969,677 ms] noteScanstart no scan source
I/wpa_supplicant( 3317): set current WIFI status to BT!
I/bluetooth-coex( 5313): btcoex_socket_server: accept socket success
I/bluetooth-coex( 5313): set_bt_coex_mode_ext: wlan common protect cancelled, nothing to do
E/WifiMonitor( 2933): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 2933): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine( 2933):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
E/WifiStateMachine( 2933):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
E/WifiStateMachine( 2933):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
E/WifiStateMachine( 2933):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
E/WifiStateMachine( 2933):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=2 known=1 got=2 bcn=0
E/WifiStateMachine( 2933): [1,448,298,969,704 ms] noteScanEnd no scan source
E/WifiStateMachine( 2933): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@13425bfa sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController ( 2933): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController ( 2933): 01ABC c2:ff:d4:d3:aa:48 rssi=-67 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController ( 2933): ageScanResultsOut delay 40000 size 2 now 1448298969706
E/WifiAutoJoinController ( 2933): newSupplicantResults size=2 known=1 true
E/WifiAutoJoinController ( 2933): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController ( 2933): ssid=NG700
E/WifiAutoJoinController ( 2933): id=0
E/WifiAutoJoinController ( 2933): mode=station
E/WifiAutoJoinController ( 2933): pairwise_cipher=CCMP
E/WifiAutoJoinController ( 2933): group_cipher=CCMP
E/WifiAutoJoinController ( 2933): key_mgmt=WPA2-PSK
E/WifiAutoJoinController ( 2933): wpa_state=COMPLETED
E/WifiAutoJoinController ( 2933): ip_address=192.168.1.118
E/WifiAutoJoinController ( 2933): p2p_device_address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 2933): address=58:2a:f7:ed:a4:6c
E/WifiAutoJoinController ( 2933): uuid=fc3e6a12-87ef-50cc-87ec-720c7386849f split=12
E/WifiAutoJoinController ( 2933): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController ( 2933): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController ( 2933): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController ( 2933): look up all configurations network done, candidate = null
E/WifiAutoJoinController ( 2933): attemptRoam() BSSID is set c0:ff:d4:d3:aa:48 -> bail
E/WifiAutoJoinController ( 2933): Done attemptAutoJoin status=0
I/WebViewFactory( 6866): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
E/        ( 2933): open /proc/5829/smaps fail errno 2
E/        ( 2933): open /proc/5908/smaps fail errno 2
E/        ( 2933): open /proc/5947/smaps fail errno 2
E/        ( 2933): open /proc/5976/smaps fail errno 2
E/        ( 2933): open /proc/6006/smaps fail errno 2
I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10052
I/HwSystemManager( 3621): HoldService:uid:10052 pid:6006 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10052,6006
I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10032
I/HwSystemManager( 3621): HoldService:uid:10032 pid:5829 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10032,5829
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10052, pid: 6006
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10052, pid: 6006
I/PG Utils( 6908): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10032, pid: 5829
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10032, pid: 5829
I/HwSystemManager( 3621): AppLockService:applock password not initial or function is closed
I/PG Utils( 6908): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
E/MDM     ( 4080): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/LibraryLoader( 6866): Loading: webviewchromium
I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/LibraryLoader( 6866): Time to load native libraries: 54 ms (timestamps 8109-8163)
I/LibraryLoader( 6866): Expected native library version number "",actual native library version number ""
I/ActivityManager( 2933): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/LibraryLoader( 6866): Expected native library version number "",actual native library version number ""
I/chromium( 6866): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/BrowserStartupController( 6866): Initializing chromium process, renderers=0
W/art     ( 6866): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6866): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6866): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 6866): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/GCoreFlp( 4080): No location to return for getLastLocation()
W/FusedLocationProvider( 4154): location=null
W/StubController( 6986): calendar access!
,W/chromium( 6866): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6866): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/chromium( 6866): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,I/PG Utils( 6986): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 7019): calendar access!
,W/StubController( 6986): calendar access!
,I/PG Utils( 6986): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 6986): calendar access!
,I/CalendarSimpleUiPRovider( 6986): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6986): onConfigurationChanged
,W/StubController( 6986): calendar access!
,I/CalendarSimpleUiPRovider( 6986): initParams20151123T181610Europe/Warsaw(1,326,3600,0,1448298970)
,W/StubController( 6986): calendar access!
,I/GAV2    ( 6482): Thread[GAThread,5,main]: No campaign data found.
,W/StubController( 6986): calendar access!
,I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/art     ( 6866): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6866): onDetachedFromWindow called when already detached. Ignoring
,I/art     ( 6866): Can not find class: Landroid/widget/ViewStub;
,I/art     ( 6866): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6866): Can not find class: Landroid/app/ViewStub;
,W/art     ( 6866): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6866): Attempt to remove local handle scope entry from IRT, ignoring
,I/GAv4-SVC( 6394): Google Analytics 8.3.01 is starting up.
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 3621): HoldService:uid:10050 pid:6030 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10050,6030
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10050, pid: 6030
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10050, pid: 6030
,I/ActivityManager( 2933): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/CalendarSimpleUiPRovider( 6986): loadEvent end update UI0
,I/HwEmailTag( 7057): MailAppProvider->onCreate->begin, consuming 1448298970821ms->-prefixstartupperformance-
,I/HwEmailTag( 7057): MailAppProvider->onCreate->end, consuming 1448298970846ms->-prefixstartupperformance-
,I/HwCust  ( 7057): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 7057): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 7057): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwCust  ( 7057): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/HwEmailTag( 7057): EmailProvider->onCreate->start. -prefixstartupperformance-
,I/HwEmailTag( 7057): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 7057): HwUtils->initStaticVarsAsync
I/HwEmailTag( 7057): HwUtils->initStaticVarsAsync
,I/HwCust  ( 7057): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 7057): EmailContent->init->consuming:17ms->;-prefixstartupperformance-
,I/HwEmailTag( 7057): EmailProvider->sURIMatcher is initialized
,I/HwEmailTag( 7057): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 7057): EmailProvider->onCreate->end, consuming 30ms->-prefixstartupperformance-
I/HwEmailTag( 7057): EmailProvider->onCreate->end, consuming 30ms->-prefixstartupperformance-
,I/HwEmailTag( 7057): EmailProvider->resetVisibleLimits->start:1448298970904 ->-prefixstartupperformance-
I/HwEmailTag( 7057): EmailProvider->resetVisibleLimits->start:1448298970905 ->-prefixstartupperformance-
,I/HwCust  ( 7057): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 7057): EmailApplication->onCreate->begin, consuming 47ms->-prefixstartupperformance-
,I/HwEmailTag( 7057): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/HwEmailTag( 7057): DBHelper->onOpen-> EmailProvider.db
,I/HwCust  ( 7057): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwCust  ( 7057): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
,I/HwEmailTag( 7057): EmailApplication->onCreate->end, consuming 54ms->-prefixstartupperformance-
,I/HwEmailTag( 7057): EmailBroadcastReceiver->onReceive->action:android.net.conn.CONNECTIVITY_CHANGE
,I/HwEmailTag( 7057): HwUtils->notifyNetworkChanged->
,I/HwEmailTag( 7057): EmailProvider->notifyNetworkChanged->
,I/HwEmailTag( 7057): HwUtils->initStaticVarsAsync->run:consuming:53ms; bidiFormatter:android.support.v4.text.BidiFormatter@39b78f8f;accountsProjSize:42
I/HwEmailTag( 7057): HwUtils->initStaticVarsAsync->run:consuming:52ms; bidiFormatter:android.support.v4.text.BidiFormatter@39b78f8f;accountsProjSize:42
,I/HwEmailTag( 7057): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 26ms.
,I/HwEmailTag( 7057): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7057): EmailProvider->initBuildCache->start->1448298971019->-prefixstartupperformance-
,I/HwEmailTag( 7057): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 7057): EmailProvider->initBuildCache->start->1448298971019; consuming:1->-prefixstartupperformance-
,I/HwEmailTag( 7057): EmailProvider->uiAccounts->start:1448298971021
,I/HwEmailTag( 7057): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7057): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 13ms.
,I/HwEmailTag( 7057): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 7057): EmailProvider->resetVisibleLimits->getDatabase, consuming:153ms;-prefixstartupperformance-
I/HwEmailTag( 7057): EmailProvider->resetVisibleLimits->getDatabase, consuming:154ms;-prefixstartupperformance-
I/HwEmailTag( 7057): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 7057): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 7057): EmailProvider->uiAccounts->start:1448298971021;end,consuming:40
I/HwEmailTag( 7057): EmailProvider->query->1448298970903;end;;consuming:159ms;
,I/ActivityManager( 2933): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10056
I/HwSystemManager( 3621): HoldService:uid:10056 pid:6066 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10056,6066
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10056, pid: 6066
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10056, pid: 6066
,I/OpenGLRenderer( 6866): Initialized EGL, version 1.4
,I/MusicStore( 7099): Database version: 120
,I/art     ( 2933): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
,I/ActivityManager( 2933): Displayed com.example.hello/.MainActivity: +2s12ms
,I/CalendarProvider2( 7019): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 7019): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/chromium( 6866): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6866): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3621): HoldService:uid:1000 pid:6094 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:1000,6094
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
W/MediaProcessHandler( 2933): processOp uid 1000 is not concerned!
,I/PG Utils( 7099): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/ContextImpl( 7099): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/chromium( 6866): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6866): 
,W/ContextImpl( 7099): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ContextImpl( 7099): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/jxcore-log( 6866): Initializing JXcore engine
W/jxcore-log( 6866): JXcore engine is ready
,W/jxcore-log( 6866): Starting JXcore engine
,I/art     ( 7099): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 7099): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2bc20799: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7099): Installed default security provider GmsCore_OpenSSL
,I/ConfigStore( 7099): Config Database version: 1
,I/MediaRouter( 7099): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=6, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 7099): type=WIFI subType= reason=null isConnected=true
,W/jxcore-log( 6866): Platform android
W/jxcore-log( 6866): 
W/jxcore-log( 6866): Process ARCH arm
W/jxcore-log( 6866): 
,I/DownloadManager( 3245): enter DownloadReceiver::onReceive(action:android.net.conn.CONNECTIVITY_CHANGE intent:Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.providers.downloads/.DownloadReceiver (has extras) })
,I/NetworkMonitor( 7099): type=WIFI subType= reason=null isConnected=true
,I/jxcore-log( 6866): JXcore Cordova bridge is ready!
I/jxcore-log( 6866): 
,W/jxcore-log( 6866): JXcore engine is started
,I/PG Utils( 7099): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GHttpClientFactory( 7099): Using our fixed implementation of GMSCore's GoogleHttpClient
,E/jxcore-log( 6866): >> HUAWEI-ALE-L21
E/jxcore-log( 6866): 
,I/jxcore-log( 6866): Total memory 1949741056
I/jxcore-log( 6866): 
,I/GoogleURLConnFactory( 7099): Using platform SSLCertificateSocketFactory
I/jxcore-log( 6866): Free memory 27521024
I/jxcore-log( 6866): 
I/jxcore-log( 6866): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6866): 
I/jxcore-log( 6866): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6866): 
,I/jxcore-log( 6866): userPath [ 'www' ]
I/jxcore-log( 6866): 
,W/System.err( 2933): java.lang.SecurityException: WifiService: Neither user 10084 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2933): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2933): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2933): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2933): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2933): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2933): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2933): 	at android.os.Binder.execTransact(Binder.java:446)
I/jxcore-log( 6866): Size 720 1184
I/jxcore-log( 6866): 
E/WifiManager( 7099): WifiServiceMessenger == null
,I/jxcore-log( 6866): Screen Brightness 242
I/jxcore-log( 6866): 
,E/jxcore-log( 6866): Dummy Error Log.
E/jxcore-log( 6866): 
,I/HwCust  ( 7158): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
,W/HWContacts( 7158): ProviderFeatureChcker - cootek package not installed
,E/TmoMonitor( 7158): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@1f4a6e6d
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 3621): HoldService:uid:10065 pid:6127 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10065,6127
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10065, pid: 6127
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10065, pid: 6127
,I/HwCust  ( 7158): Constructor found for class com.android.mms.data.HwCustConversationImpl
,I/Mms_threadcache( 7158): [RecipientIdCache] fill: begin
,I/art     ( 2933): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/art     ( 2933): Explicit concurrent mark sweep GC freed 16452(887KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.335ms total 188.883ms
,I/EmuiFeatureManager( 7158): loadEmailAnrSupportFlag:true
,E/CSP_RADAR( 7158): Message execute too long time.{ when=-210ms what=1 target=com.huawei.mms.util.HwBackgroundLoader$3 }
,I/SimFactoryManager( 7158): Inside init method of SimFactoryManger the combination is:-1
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 7158): isSIM1CardPresent:1
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 7158): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 7158): isSIM2CardPresent:1
,E/MmsConfig( 7158): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 7158): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,E/WifiStateMachine( 2933):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=58 tx=3.4, 0.0, 0.0  rx=11.8 bcn=0 [on:0 tx:0 rx:0 period:2934] from screen [on:0 period:894993860] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 2933):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=58 tx=3.4, 0.0, 0.0  rx=11.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:894993861] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 2933): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=58 SSID="NG700"
E/WifiStateMachine( 2933): calculateWifiScore freq=2462 speed=58 score=100 highRSSI  -> txbadrate=0.00 txgoodrate=1.69 txretriesrate=0.00 rxrate=7.91 userTriggerdPenalty0
E/WifiStateMachine( 2933):  good link -> stuck count =0
E/WifiStateMachine( 2933):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine( 2933):  isHighRSSI       ---> score=61
,I/HwCust  ( 7158): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
,I/MagazineUtils( 3160): is magazine unlock on, now is lock screen diabled mode
,I/HwCust  ( 7158): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
,I/HwCust  ( 7158): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
,I/art     ( 7158): Can not find class: Lhuawei/android/view/TableLayout;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/TableLayout;
,I/art     ( 7158): Can not find class: Lhuawei/android/view/View;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/View;
,I/art     ( 7158): Can not find class: Landroid/widget/View;
I/art     ( 7158): Can not find class: Landroid/webkit/View;
,I/art     ( 7158): Can not find class: Landroid/app/View;
,I/HwCust  ( 7158): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
,I/art     ( 7158): Can not find class: Lhuawei/android/view/TableRow;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/TableRow;
,I/art     ( 7158): Can not find class: Lhuawei/android/view/LinearLayout;
I/art     ( 7158): Can not find class: Lhuawei/android/widget/LinearLayout;
,I/art     ( 7158): Can not find class: Lhuawei/android/view/ImageButton;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/ImageButton;
,I/art     ( 7158): Can not find class: Lhuawei/android/view/TextView;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/TextView;
,I/jxcore-log( 6866): getBuffer is called!!!!
I/jxcore-log( 6866): 
,I/art     ( 7158): Can not find class: Lhuawei/android/view/RelativeLayout;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/RelativeLayout;
,I/art     ( 7158): Can not find class: Lhuawei/android/view/ImageView;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/ImageView;
,E/HwOUC   ( 7203): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,E/CSP_RADAR( 7158): Runnable execute too long time
,I/art     ( 7203): Can not find class: Lcom/huawei/pad/Product;
E/HwOUC   ( 7203): [main-1]method invoke failed(/HwOucUtility.java:471)
I/HwOUC   ( 7203): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 7203): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 7203): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/HwOUC   ( 7203): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
,I/HwOUC   ( 7203): [main-1]Network available(hwouc/DownloadReceiver.java:142)
,I/HwOUC   ( 7203): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
,I/HwOUC   ( 7203): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
I/HwOUC   ( 7203): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
,I/HwOUC   ( 7203): [Thread-99-99]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995)
,I/HwOUC   ( 7203): [Thread-99-99]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
,I/art     ( 7158): Can not find class: Lhuawei/android/view/ViewStub;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/ViewStub;
,I/art     ( 7158): Can not find class: Landroid/widget/ViewStub;
,I/art     ( 7158): Can not find class: Landroid/webkit/ViewStub;
,I/art     ( 7158): Can not find class: Landroid/app/ViewStub;
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 262us total 25.916ms
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 196us total 24.943ms
,I/HwEmailTag( 7057): EmailProvider->query->1448298972917;end;;consuming:1ms;
,I/art     ( 7158): Can not find class: Lhuawei/android/view/FrameLayout;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/FrameLayout;
,I/HwEmailTag( 7057): EmailApplication->handleMessage->startService CleanRecipientAddressService
I/art     ( 7158): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 7158): Can not find class: Lhuawei/android/widget/EditText;
,E/textview( 7158): initAddtionalStyle default
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 251us total 25.342ms
,I/art     ( 7158): Can not find class: Lhuawei/android/view/ProgressBar;
,I/art     ( 7158): Can not find class: Lhuawei/android/widget/ProgressBar;
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 7158): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,I/HwEmailTag( 7057): Device->updateDeviceIdIfNeeded
,I/Process ( 7203): Sending signal. PID: 7203 SIG: 9
I/HwEmailTag( 7057): CleanRecipient->onCreate
I/HwEmailTag( 7057): Device->updateDeviceIdIfNeeded->doInBackground
I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 1050
I/HwSystemManager( 3621): HoldService:uid:1050 pid:6164 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:1050,6164
,I/HwEmailTag( 7057): Device->getDeviceId->
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
W/MediaProcessHandler( 2933): processOp uid 1050 is not concerned!
,I/HwEmailTag( 7057): CleanRecipient->onStartCommand->action is null
,I/HwCust  ( 7158): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
,I/HwEmailTag( 7057): Device->getDeviceIdInternal->isUpdate:false
I/HwEmailTag( 7057): CleanRecipient->onHandleIntent->action is null
I/HwCust  ( 7158): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
,I/Mms_TXM_SVC( 7158): onStartCommand send EVENT_NEW_INTENT. service-id 1
,I/HwEmailTag( 7057): Device->getDeviceIdInternal->get id from deviceName, return successfully.
,I/HwEmailTag( 7057): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,W/Mms_TXM_SVC( 7158): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
,W/asset   ( 7227): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwEmailTag( 7057): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 7057): CleanRecipient->onDestroy
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10052
I/HwSystemManager( 3621): HoldService:uid:10052 pid:7203 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10052,7203
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10052, pid: 7203
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10052, pid: 7203
,I/HwEmailTag( 7057): AccountReconciler->reconcileAccountsInternal->consuming:234ms
,I/HwEmailTag( 7057): EmailProvider->query->1448298973157;end;;consuming:1ms;
I/HwCust  ( 7227): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
,I/art     ( 7227): Can not find class: Landroid/provider/Settings$Systemex;
,E/HwThemeManager( 7227): ThemeHelperretry to get Settings
,I/HwEmailTag( 7057): AccountReconciler->reconcileAccountsInternal->consuming:4ms
,I/HwCust  ( 7254): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 7254): EmailContent->init->consuming:19ms->;-prefixstartupperformance-
,I/HwEmailTag( 7254): Exchange->onCreate
,I/PG Utils( 7254): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7254): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7057): EmailProvider->query->1448298973257;end;;consuming:2ms;
,I/HwEmailTag( 7254): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,W/asset   ( 7278): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3621): HoldService:uid:1000 pid:6216 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:1000,6216
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
W/MediaProcessHandler( 2933): processOp uid 1000 is not concerned!
,I/HwCust  ( 7278): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10090
I/HwSystemManager( 3621): HoldService:uid:10090 pid:6267 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10090,6267
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10090, pid: 6267
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10090, pid: 6267
,W/asset   ( 7306): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwSystemManager( 7306): SystemManagerApplication:onCreate
,I/HwSystemManager( 3621): MainService:on startCommand,flags:0,startId:5
,I/System.out( 7306): [ls, -l, /system/app/HwSystemManager/HwSystemManager.apk]
I/System.out( 7306): null
I/System.out( 7306): null
I/System.out( 7306): Calling by::className:bkk  MethodName:yw
,I/HwSystemManager( 3621): LocalService:Received start id 5: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
,I/HwSystemManager( 3621): BgPowerManagerService:onStartCommand
,I/HwSystemManager( 3621): AppLockService:onStartCommand
,I/HwSystemManager( 7306): check push opration, match idx:-1
,I/HwSystemManager( 3621): AppCleanUpService:onStartCommand() in!
,I/HwSystemManager( 7306): HsmStat_info:feature enable:false
,I/HwSystemManager( 7306): ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, com.test.thalitest]
,I/HwSystemManager( 7306): OverseaCfgHelper:permissionStatus is 0
,E/HwSystemManager( 7306): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
,I/YhdsEngine( 7306): [EngineIntentService] Received: com.huawei.dianxinos.optimizer.engine.action.APP_START
I/HwSystemManager( 7306): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
I/HwSystemManager( 7306): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 7306): SimCardManager:getOperatorNameFromService mNameServSlot0 = null
I/HwSystemManager( 7306): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
I/HwSystemManager( 7306): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 7306): SimCardManager:getOperatorNameFromService mNameServSlot1 = null
I/HwSystemManager( 7306): SimCardManager:/onReceive: action =android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 7306): SimCardManager:action:android.provider.Telephony.SPN_STRINGS_UPDATED
,I/YhdsEngine( 7306): [AlarmEventMgr] event scheduled: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
,I/YhdsEngine( 7306): [EngineIntentService] Received: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10092
I/HwSystemManager( 3621): HoldService:uid:10092 pid:6295 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10092,6295
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10092, pid: 6295
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10092, pid: 6295
,I/HwEmailTag( 7057): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
,I/HwEmailTag( 7057): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 7057): EmailProvider->triggerPeroidSync->accountId:-1
,I/HwEmailTag( 7057): EmailConnectivityTask->syncOutbox
,I/HwEmailTag( 7057): EmailProvider->query->1448298973940;end;;consuming:4ms;
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10095
I/HwSystemManager( 3621): HoldService:uid:10095 pid:6319 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10095,6319
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10095, pid: 6319
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10095, pid: 6319
,W/ContextImpl( 7359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 7359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7359): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7359):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7359):   adb logcat -s GAv4
,W/ContextImpl( 7359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ContextImpl( 7359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7359): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7359): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7359): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PG Utils( 7359): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 7359): Can not find class: Ljava/util/ConcurrentNavigableMap;
,I/HwSystemManager( 3621): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3621): BgPowerManagerService: mTimes = 33968 firstTime = 28683 firstmBatteryCapacity =2203
,I/ContactsAppilcation( 7158): intent:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,I/CommonUtilMethods( 7158): action:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 7158): intent:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
,I/CommonUtilMethods( 7158): action:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 7158): intent:android.provider.Telephony.SPN_STRINGS_UPDATED
,I/WebViewFactory( 7359): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 7359): Loading: webviewchromium
,I/LibraryLoader( 7359): Time to load native libraries: 4 ms (timestamps 2721-2725)
,I/LibraryLoader( 7359): Expected native library version number "",actual native library version number ""
,I/LibraryLoader( 7359): Expected native library version number "",actual native library version number ""
,I/chromium( 7359): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7359): Initializing chromium process, renderers=0
,W/art     ( 7359): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid( 7359): Requires BLUETOOTH permission
,W/chromium( 7359): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7359): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
I/chromium( 7359): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
,I/NSApplication( 7359): Starting up...
,I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/System  ( 6540): core_booster, getBoosterConfig = false
,I/iu.SyncManager( 6394): SYNC; picasa accounts
I/iu.Environment( 6394): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 6394): num queued entries: 0
I/iu.UploadsManager( 6394): num updated entries: 0
I/iu.SyncManager( 6394): NEXT; no task
I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Babel   ( 6540): connection state changed from UNKNOWN to CONNECTED
,I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10087
I/HwSystemManager( 3621): HoldService:uid:10087 pid:6341 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10087,6341
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10087, pid: 6341
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10087, pid: 6341
,I/PG Utils( 7432): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7432): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 7057): PeakSchedulingService->onHandleIntent : intent.getAction() -> com.huawei.email.service.PEAK_TIME_SET
,I/HwEmailTag( 7057): EmailProvider->query->1448298975280;end;;consuming:2ms;
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10041
I/HwSystemManager( 3621): HoldService:uid:10041 pid:6482 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10041,6482
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10041, pid: 6482
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10041, pid: 6482
,E/WifiStateMachine( 2933):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2462 sc=100 link=58 tx=1.7, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:894996867] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 2933):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2462 sc=100 link=58 tx=1.7, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:894996868] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 2933): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=58 SSID="NG700"
,E/WifiStateMachine( 2933): calculateWifiScore freq=2462 speed=58 score=100 highRSSI  -> txbadrate=0.00 txgoodrate=2.84 txretriesrate=0.00 rxrate=9.95 userTriggerdPenalty0
E/WifiStateMachine( 2933):  good link -> stuck count =0
E/WifiStateMachine( 2933):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine( 2933):  isHighRSSI       ---> score=61
,I/HwSystemManager( 3621): HoldService:uid:10025 pid:6772 died
I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10025
I/HwSystemManager( 3621): HoldService:oldVersionKey:10025,6772
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10025, pid: 6772
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10025, pid: 6772
,I/art     ( 2933): Explicit concurrent mark sweep GC freed 15196(829KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 1.895ms total 196.740ms
,I/HwSystemManager( 7306): HsmStat_info:service connect
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExchangeAccountType@2d4121d4 in the cache
,W/StubController( 6986): calendar access!
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:1
,I/HwCust  ( 7158): Constructor found for class com.android.contacts.model.account.HwCustAccountModelCustomizationImpl
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExternalAccountType@22147e72 in the cache
,W/ResourceType( 7158): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 7158): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
,W/ResourceType( 7158): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 7158): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExternalAccountType@a788740 in the cache
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.GoogleAccountType@a074679 in the cache
,E/ExternalAccountType( 7158): Unsupported attribute readOnly
,I/AccountTypeManager( 7158): AccountManager, account size is: 2
,I/AccountTypeManager( 7158): Loaded meta-data for 5 account types, 3 accounts in 78ms(wall) 56ms(cpu)
,I/PG Utils( 6986): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10026
,I/HwSystemManager( 3621): HoldService:uid:10026 pid:6818 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10026,6818
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10026, pid: 6818
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10026, pid: 6818
,I/HwEmailTag( 7057): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 7057): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 7057): EmailProvider->triggerPeroidSync->accountId:-1
,I/Process ( 7493): Sending signal. PID: 7493 SIG: 9
,I/DeskClockApplication( 7517): onCreate
,I/AlarmInitReceiver( 7517): AlarmInitReceiver->OnReceive->AsyncHandler : needSetSnoozeAlert = false alarmnow = false
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 1001
I/HwSystemManager( 3621): HoldService:uid:1001 pid:7493 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:1001,7493
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
W/MediaProcessHandler( 2933): processOp uid 1001 is not concerned!
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10010
I/HwSystemManager( 3621): HoldService:uid:10010 pid:6908 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10010,6908
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10010, pid: 6908
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10010, pid: 6908
,E/HwOUC   ( 7541): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 7541): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 7541): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 7541): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 7541): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
I/HwOUC   ( 7541): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
I/HwOUC   ( 7541): [main-1]Intent.ACTION_TIME_CHANGED nextInstallRemindTime:Thu Jan 01 00:59:59 GMT+01:00 1970(hwouc/DownloadReceiver.java:370)
I/HwOUC   ( 7541): [main-1]Intent.ACTION_TIME_CHANGED alarmRegistTime:Thu Jan 01 00:59:59 GMT+01:00 1970(hwouc/DownloadReceiver.java:372)
I/HwOUC   ( 7541): [main-1]Intent.ACTION_TIME_CHANGED nextCheckNewVersionTime:Tue Nov 24 07:58:52 GMT+01:00 2015(hwouc/DownloadReceiver.java:400)
I/HwOUC   ( 7541): [main-1]Intent.ACTION_TIME_CHANGED startTime:Mon Nov 23 07:58:52 GMT+01:00 2015(hwouc/DownloadReceiver.java:402)
I/HwOUC   ( 7541): [main-1]Intent.ACTION_TIME_CHANGED currentTime:Mon Nov 23 18:16:16 GMT+01:00 2015(hwouc/DownloadReceiver.java:404)
I/HwSystemManager( 7306): PreventReceiver:RreventReceiver receive the action :android.intent.action.TIME_SET
,I/HwSystemManager( 7306): PreventReceiver:TriggerAgainTask-doInBackground: time switch = false, time list size = 0
,I/PG Utils( 6394): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/CheckinService( 6394): Checkin interval check for package: unspecified last checkin: 1448013111636 min interval config: 0 actual interval: 285864646
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10032
I/HwSystemManager( 3621): HoldService:uid:10032 pid:7019 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10032,7019
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10032, pid: 7019
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10032, pid: 7019
,I/HwLauncher( 3786): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwLauncher( 3786): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
I/HwLauncher( 3786): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3786): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3786): Model STK reName intent is received.
,I/HwLauncher( 3786): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3786): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3786): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3786): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3786): Model STK reName intent is received.
,I/HwLauncher( 3786): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3786): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3786): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3786): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3786): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwEmailTag( 7057): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwLauncher( 3786): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3786): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3786): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3786): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3786): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3786): Launcher.Folder childCount: 5
I/HwLauncher( 3786): Launcher.Folder childCount: 5
I/HwLauncher( 3786): Launcher.Folder childCount: 7
I/HwLauncher( 3786): Launcher.Folder childCount: 7
I/HwLauncher( 3786): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
I/HwLauncher( 3786): Launcher.Folder childCount: 6
I/HwLauncher( 3786): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3786): Launcher.Folder childCount: 6
I/HwLauncher( 3786): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3786): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3786): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3786): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3786): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3786): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3786): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3786): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3786): Model shortcutInfo.title = SIM Toolkit
,I/HwLauncher( 3786): Launcher.Folder childCount: 7
I/HwLauncher( 3786): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3786):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3786):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3786):  createAddIcon count = 0
,I/HwLauncher( 3786):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3786): Launcher Deferring update until onResume
I/HwLauncher( 3786): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3786): Launcher.Folder childCount: 5
I/HwLauncher( 3786): Launcher.Folder childCount: 5
I/HwLauncher( 3786): Launcher.Folder childCount: 7
I/HwLauncher( 3786): Launcher.Folder childCount: 7
I/HwLauncher( 3786): Launcher.Folder childCount: 6
I/HwLauncher( 3786): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3786): Launcher.Folder childCount: 6
I/HwLauncher( 3786): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3786): Launcher.Folder childCount: 7
I/HwLauncher( 3786): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3786):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3786):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3786):  createAddIcon count = 0
,I/HwLauncher( 3786):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3786): Launcher Deferring update until onResume
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10084
I/HwSystemManager( 3621): HoldService:uid:10084 pid:7099 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10084,7099
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10084, pid: 7099
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10084, pid: 7099
,E/SQLiteLog( 7611): (284) automatic index on view_events(_id)
,W/StubController( 7611): calendar access!
,W/StubController( 7611): calendar access!
,W/BluetoothAdapter( 5313): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 5313): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 5313): Accept thread started.
,I/BluetoothAdapter( 6866): Start to disable Bluetooth!
,I/art     ( 2933): Can not find class: Lcom/android/server/DropBoxManagerService$1$1;
,I/BluetoothAdapterState( 5313): Bluetooth adapter state changed: 12-> 13
,I/bluedroid( 5313): bt interface: [set_adapter_property]
W/bt-btm  ( 5313): BTM_SetDiscoverability
I/BluetoothAdapterState( 5313): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
W/bt-btm  ( 5313): BTM_SetConnectability
W/bt-btif ( 5313): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 5313): adapterPropertyChangedCallback with type:7 len:4
,I/bluedroid( 5313): bt interface: [disable]
W/bt-btif ( 5313): btif_disable_bluetooth, btif_core_radio_ref_count=0
W/bt-btif ( 5313): BTIF DISABLE BLUETOOTH
,W/bt-btif ( 5313): bta_sys_disable: module 0
W/bt-btm  ( 5313): BTM_SetDiscoverability
W/bt-btm  ( 5313): BTM_SetConnectability
W/bt-btif ( 5313): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 5313): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5313): L2CAP - PSM: 0x0017 not found for deregistration
,I/ActivityManager( 2933): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,I/bluetooth-coex( 5313): bt_coex_deinit: bt_coex_deinit
,I/bluetooth-coex( 5313): btcoex_send_msg: send bt_state(0) to wifi, sock_fd(72)
I/bluetooth-coex( 5313): btcoex_socket_server: accept socket success
,I/bluetooth-coex( 5313): btcoex_send_msg: bt closing, exit coex server, sock_fd(72)
I/bluetooth-coex( 5313): btcoex_socket_server: BT_COEX_PTHREAD_EXIT
,I/bluetooth-coex( 5313): bt_coex_deinit: clear coex timer list entry
I/bluetooth-coex( 5313): bt_coex_deinit: free g_bt_coex_cb
,E/BtOppRfcommListener( 5313): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BtOppRfcommListener( 5313): stopping Accept Thread
,I/BtOppRfcommListener( 5313): BluetoothSocket listen thread finished
,W/View    ( 3268): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{31be6613 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/HwSystemManager( 3621): HoldService:checkBeforeShowDialog: uid:10302 pid:6866, permissionType:2097152
I/HwSystemManager( 3621): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2933): allowOpenWifi blocked:false
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10064
I/jxcore-log( 6866): ****TEST TOOK:  5256  ms ****
I/jxcore-log( 6866): 
I/HwSystemManager( 3621): HoldService:uid:10064 pid:7278 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10064,7278
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10064, pid: 7278
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10064, pid: 7278
E/WifiStateMachine( 2933):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6866): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6866): 
,E/WifiStateMachine( 2933):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2933):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2933):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
W/bt-btif ( 5313): bta_sys_hw_api_disable for 0, active modules: 0x0001
W/bt-btif ( 5313): bta_sys_disable: module 0
W/bt-btif ( 5313): call bta_sys_hw_co_disable
W/bt-btif ( 5313): sending BTA_SYS_EVT_DISABLED_EVT
W/bt-btif ( 5313): bta_sys_hw_evt_disabled - module 0x0
W/bt-btif ( 5313):  bta_dm_sys_hw_cback with event: 0
W/bt-btif ( 5313): btif_disable_bluetooth_evt
W/bt-btif ( 5313): btif_disable_bluetooth_evt, btif_core_is_radio_req = 0
W/bt-btif ( 5313): btif_dm_disable_bt_services
E/bt-btif ( 5313): BTA AG is already disabled, ignoring ...
W/bt-btif ( 5313): btif_dm_disable_bt_services i=6
W/bt-btif ( 5313): btif_dm_disable_bt_ not found for deregistration
W/bt-l2cap( 5313): btif_dm_disable_bt_ not found for deregistration
W/bt-btif ( 5313): btif_dm_disable_bt_ not found for deregistration
W/bt-l2cap( 5313): btif_dm_disable_bt_ not found for deregistration
W/bt-btif ( 5313): btif_dm_disable_bt_services i=25
W/bt-l2cap( 5313): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5313): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5313): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-btif ( 5313): L2CAP - PSM: 0x0017
W/bt-l2cap( 5313): bte_main_disable
W/bt-btif ( 5313): bte_main_disable
W/bt-btif ( 5313): ag scb idx 1 not allocated
E/bt-btif ( 5313): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 5313): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5313): L2CAP - PSM: 0x0017 not found for deregistration
W/bt_lpm  ( 5313): Still busy on processing prior LPM enable/disable request...
W/bt-l2cap( 5313): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5313): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5313): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5313): L2CAP - PSM: 0x0017 not found for deregistration
W/bt_userial( 5313): select_read return size <=0:-1, exiting userial_read_thread
,E/WifiStateMachine( 2933):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 2933): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 2933): setScanAlarm false period 20000 initial delay 0
E/WifiStateMachine( 2933): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 2933): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 2933): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 3317): set current WIFI status to BT!
,W/View    ( 3268): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{31be6613 V.E..... ........ 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/ActivityManager( 2933): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 2933): filter receiver for action = com.google.android.gcm.DISCONNECTED
,I/ActivityManager( 2933): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/HwSystemManager( 3621): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3621): NotificationManagerReceiver:onReceive, send action to background
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10005
I/HwSystemManager( 3621): HoldService:uid:10005 pid:7254 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10005,7254
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10005, pid: 7254
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10005, pid: 7254
,I/ActivityManager( 2933): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 2933): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ArpVerifier( 2933): current SSID is empty.
,I/HwSystemManager( 3621): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@2ba28455
I/HwSystemManager( 3621): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3621): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,E/WifiStateMachine( 2933): Unexpected BatchedScanResults :OK
,I/HwSystemManager( 3621): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings]
,E/WifiStateMachine( 2933): noteBatchedScanstop()
I/HwSystemManager( 3621): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
,I/HwSystemManager( 7306): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3621): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
I/HwSystemManager( 3621): NmCenterDefValueXmlHelper:getConfigs: Starts
I/HwSystemManager( 7306): ProcPolicy:begin get procName.
,E/WifiStateMachine( 2933): [1,448,298,977,548 ms] noteScanEnd no scan source
,I/HwSystemManager( 3621): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33
,I/HwSystemManager( 3621): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
E/WifiStateMachine( 2933):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2933):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2933):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 2933): Can not find class: Lcom/android/server/wifi/RttService$RttServiceImpl$ClientInfo;
E/WifiStateMachine( 2933): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 2933):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2933):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
I/HwSystemManager( 7306): ProcPolicy:this proc is:com.huawei.systemmanager
I/HwSystemManager( 7306): ProcPolicy:end get procName.
E/WifiStateMachine( 2933):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2933): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2933):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2933):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 2933):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 2933): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 2933):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
,I/art     ( 2933): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
,I/HwSystemManager( 7306): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@3cb70408
I/HwSystemManager( 3621): aor:Network Stats Updated
I/HwSystemManager( 3621): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/HwSystemManager( 3621): aor:Network Stats Updated
I/HwSystemManager( 3621): aoi:onNetworkStatsUpdated
,I/wpa_supplicant( 3317): set current WIFI status to BT!
,I/HwSystemManager( 3621): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg,
,I/HwSystemManager( 3621): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 3621): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 3621): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3621): HsmIntentService:last work complete! lets stop service.
,I/ActivityManager( 2933): filter receiver for action = android.net.wifi.STATE_CHANGE
E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
,I/wpa_supplicant( 3317): set current WIFI status to BT!
I/wpa_supplicant( 3317): WIFI closed already, cancel
I/wpa_supplicant( 3317): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 3317): check_associate_result func start
I/HwSystemManager( 7306): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,E/HI110X_CHR_LOGD( 2657): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
,E/WifiMonitor( 2933): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 2933): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/ActivityManager( 2933): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
W/System.err( 2933): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 2933): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2933): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2933): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 2933): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
E/WifiStateMachine( 2933):  SupplicantStoppingState !CMD_ON_QUIT 0 0
,W/System.err( 2933): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 2933): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 2933): ,	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 2933): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 2933): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 2933): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 2933): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 2933): This is not beta user build
E/WifiStateMachine( 2933):  DefaultState !CMD_ON_QUIT 0 0
I/HwSystemManager( 7306): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
I/HwSystemManager( 7306): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,I/ActivityManager( 2933): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null,
,E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3621): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 7306): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
I/HwSystemManager( 7306): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 7306): OverseaCfgHelper:permissionStatus is 0
I/HwSystemManager( 3621): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 3621): AppCleanUpService:onStartCommand() out!
E/HwSystemManager( 3621): AppCleanUpService:msg is 0
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
,I/HwCust  ( 7306): Constructor found for class com.huawei.systemmanager.optimize.process.HwCustProtectAppControlImpl
,I/NetworkSpeedManagerEx( 3268): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3268): wifiManager = android.net.wifi.WifiManager@1e68903a
,I/NetworkSpeedManagerEx( 3268): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3268): stop
I/HwSystemManager( 7306): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3621): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/HwSystemManager( 7306): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 7306): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,W/HwSystemManager( 7306): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 7306): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 7306): HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:3, queue size:0
,I/HwSystemManager( 7306): HsmPackageManager:begin to scan apks.
I/appproc ( 7715): CLASSPATH=/system/framework/pm.jar
I/appproc ( 7715): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 7715): app_process:number,5,0
,I/AndroidRuntime( 7715): readDownloadBoosterConfig: 'false'
,E/WifiMonitor( 2933): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,I/HwSystemManager( 7306): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 7306): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
E/WifiStateMachine( 2933):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65716
I/HwSystemManager( 7306): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
E/WifiStateMachine( 2933):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=65716
I/HwSystemManager( 7306): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 7306): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorL,istRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 3621): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@2ba28455
I/HwSystemManager( 7306): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 7306): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], applock=[Rule AppLockNotMonitorListRule post: match[0], mismatch[2], Rule HomeCategoryRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
I/HwSystemManager( 7306): XmlRuleBase:parseAndCacheList permission_black_list_match :[]
I/HwSystemManager( 7306): anf:packageCanAccessInternet com.example.hellohas INTERNET permission
I/HwSystemManager( 7306): anf:packageCanAccessInternet component enable
I/HwSystemManager( 7306): XmlRuleBase:parseAndCacheList black_match :[]
I/HwSystemManager( 7306): XmlRuleBase:parseAndCacheList permission_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 7306): XmlRuleBase:parseAndCacheList white_match :[com.baidu.map.location, com.cootek.smartdialer_oem_module, com.sohu.inputmethod.sogou.huawei, com.huawei.hisuite, com.nuance.swype.emui, com.huawei.remoteassistant, com.iflytek.speechcloud, com.huawei.phoneservice, com.huawei.phonediagnose, com.nqmobile.antivirus20.hw, com.baidu.input_huawei]
I/YhdsEngine( 7306): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
I/HwSystemManager( 7306): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello, replacing: false
E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3621): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
I/HwSystemManager( 7306): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
I/HwSystemManager( 7306): AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
I/HwSystemManager( 7306): XmlRuleBase:parseAndCacheList dropzone_black_list_match :[]
,I/        ( 5313): [vendor/huawei_platform/connectivity/hisi/hisi_connectivity/bt/hal/src/bt_vendor_hisi.c: hisi_cleanup 354][bt_vendor] cleanup
W/wpa_supplicant( 3317): STA MODE: Set shutdown wlan cmd SUCCESS
I/GKI_LINUX( 5313): gki_task task_id=0 [BTU] terminating
I/HwSystemManager( 7306): XmlRuleBase:parseAndCacheList dropzone_white_list_match :[com.huawei.intelligent]
W/wpa_supplicant( 3317): check_associate_result func start
E/WifiMonitor( 2933): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 2933):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=65753  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 2933):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=65753  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/GKI_LINUX( 5313): GKI_exit_task 0 done
I/GKI_LINUX( 5313): GKI_shutdown(): task [BTU] terminated
W/bt-btif ( 5313): HAL bt_hal_cbacks->adapter_state_changed_cb
E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3621): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
W/BluetoothHeadsetServiceJni( 5313): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5313): Cleaning up Bluetooth Handsfree callback object
E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3621): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
I/HwSystemManager( 7306): HsmPackageManager:end to scan apks. size:150 + 0
I/GKI_LINUX( 5313): gki_task task_id=2 [A2DP-MEDIA] terminating
I/HwSystemManager( 7306): HsmPackageManager:init locale:en_US,
I/GKI_LINUX( 5313): GKI_exit_task 2 done
I/GKI_LINUX( 5313): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 5313): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5313): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5313): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 5313): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5313): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 5313): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5313): Cleaning up Bluetooth PAN callback object
I/BluetoothAdapterState( 5313): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 5313): Entering OffState
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PACKAGE_CHANGED
I/HwSystemManager( 7306): AppManager:insert to db: name = com.example.hello uid = 10302 app type = false
I/HwSystemManager( 7306): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 7306): ProtectAppControl:handleMessage:6
I/HwSystemManager( 7306): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:2, queue size:0
I/HwSystemManager( 7306): ProtectAppControl:begin install app inner:com.example.hello
W/ResourceType( 2933): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
I/HwLauncher( 3786): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/HwLauncher( 3786): Model replacing = false package = com.google.android.gms,
I/HwSystemManager( 7306): PermissionDBAdapter:DBAdapter created!
,I/HwSystemManager( 3621): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwSystemManager( 3621): HsmPackageManager:replacing:false
I/HwSystemManager( 3621): HsmPackageManager:pkgName:com.google.android.gms
I/HwSystemManager( 3621): HsmPackageManager:doAppChanged, put com.google.android.gms, path:/data/app/com.google.android.gms-2
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null,
,W/HwSystemManager( 7306): AddViewAppManager:Current installed app not apply system_alert_window or applicationInfo null!
I/HwSystemManager( 7306): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwLauncher( 3786): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.google.android.gms]
I/HwSystemManager( 7306): PermissionDbHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/permission.db
I/HwSystemManager( 7306): HsmPackageManager:replacing:false
I/HwLauncher( 3786): SimpleLauncherModeaction= android.intent.action.PACKAGE_CHANGEDpackageName = com.google.android.gms
I/HwSystemManager( 7306): HsmPackageManager:pkgName:com.google.android.gms
I/HwLauncher( 3786): SimpleLauncherModemAllAppsList.updatePackage com.google.android.gms
,I/HwSystemManager( 7306): HsmPackageManager:doAppChanged, put com.google.android.gms, path:/data/app/com.google.android.gms-2
I/HwSystemManager( 7306): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 7306): PermissionDBAdapter:appcationsList size:150,
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExchangeAccountType@1bcec81f in the cache
,I/HwLauncher( 3786): SimpleAllAppsList  updatePackage : package[com.google.android.gms] matched activity's size is 1 and data List size is 0
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3621): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:0,
,I/InputReader( 2933): Reconfiguring input devices.  changes=0x00000010
I/HwLauncher( 3786): SimpleAllAppsList  findAndUpdateInfoInDB : found 0 shortcutInfo for package[com.google.android.gms] in db,
I/HwLauncher( 3786): SimpleAllAppsList  updatePackage do not add new SimpleApplicationInfo,It's in normal now. package = com.google.android.gms
W/HwLauncher( 3786): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
,I/HwLauncher( 3786): Model mAllAppsList.updatePackage com.google.android.gms,
I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:1
I/HwLauncher( 3786): AllIdleAppsList  updatePackage : package[com.google.android.gms] matched activity's size is 1 and data List size is 61,
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExternalAccountType@3efed76c in the cache
,I/NetworkSpeedManagerEx( 3268): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3268): wifiManager = android.net.wifi.WifiManager@1e68903a,
,I/NetworkSpeedManagerEx( 3268): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
,I/NetworkSpeedManagerEx( 3268): stop,
I/HwLauncher( 3786): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114,
,I/HwLauncher( 3786): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = Google Settings,
I/HwLauncher( 3786): Model shortcutInfo.title = Google Settings
,I/HwLauncher( 3786): Workspace updateShortcuts apps.size() 1
I/HwLauncher( 3786): Launcher.Folder childCount: 9
,I/HwLauncher( 3786): Launcher.Folder childCount: 5
,I/HwLauncher( 3786): Workspace updateShortcuts shortcutInfo = Google Settings
,I/HwLauncher( 3786): Launcher.Folder childCount: 7
,I/HwLauncher( 3786): Launcher.Folder childCount: 9
,I/HwLauncher( 3786): Launcher.Folder childCount: 6,
,I/HwLauncher( 3786): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3786):  syncPages mCurrentPage = 0,
,I/        ( 7715): power log dlsym ok,
,W/ResourceType( 7158): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769),
W/ResourceType( 7158): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
,W/ResourceType( 7158): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769),
W/ResourceType( 7158): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExternalAccountType@225169ca in the cache
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.GoogleAccountType@721c73b in the cache
,I/WifiTracker( 3268): STATE =0
,E/HideAppsPagedView( 3786):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
,E/HideAppsPagedView( 3786):  createAddIcon count = 0
I/HwLauncher( 3786):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550,
I/HwLauncher( 3786): Launcher Deferring update until onResume
,E/RegisteredServicesCache( 3707): invalidateCache set mNeedToastTableFull
W/HwSystemManager( 7306): ProtectAppControl:com.example.hello already exist!
,E/ExternalAccountType( 7158): Unsupported attribute readOnly
,E/WifiMonitor( 2933): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2933): handleEvent 13  CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48
E/WifiMonitor( 2933): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
E/WifiMonitor( 2933): handleEvent 13  CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:48
,I/AccountTypeManager( 7158): AccountManager, account size is: 2
I/art     ( 2323): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 383us total 38.242ms
,I/AccountTypeManager( 7158): Loaded meta-data for 5 account types, 3 accounts in 100ms(wall) 34ms(cpu)
,E/android_hardware_fm.cpp( 7715): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 7715): ========64bit long size = 8
E/FM_HAL  ( 7715): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 7715): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 7715): 
I/fm_hisi ( 7715): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 7715): 
I/fm_hisi ( 7715): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 7715): 
,E/android_hardware_fm.cpp( 7715): register_android_hardware_fm_fmradio, ret is 0
,I/ActivityManager( 2933): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
I/bluedroid( 5313): bt interface: [cleanup]
,W/bt-btif ( 5313): HAL bt_hal_cbacks->thread_evt_cb
,I/GKI_LINUX( 5313): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 5313): GKI_exit_task 1 done
I/GKI_LINUX( 5313): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 5313): cleanupNative: return from cleanup
I/BluetoothServiceJni( 5313): OoO sJniCallbacksObj has init before clean? 1
,I/art     ( 5313): System.exit called, status: 0
I/AndroidRuntime( 5313): VM exiting with result code 0, cleanup skipped.
,I/NetworkSpeedManagerEx( 3268): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3268): wifiManager = android.net.wifi.WifiManager@1e68903a
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 698us total 31.335ms
,I/NetworkSpeedManagerEx( 3268): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3268): stop
,W/asset   ( 2933): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 270us total 28.033ms
,W/wpa_supplicant( 3317): ioctl error:ret = -1
E/wpa_supplicant( 3317): wpa_driver_set_wps_p2p_ie failed ret=-1
I/HwSystemManager( 3621): ContactsObserverHelper:onContactsChanged: Start to handle contacts change message
I/HwSystemManager( 3621): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3621): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3621): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 3621): bbe:onPreContactsChange: Starts
I/HwSystemManager( 3621): ContactsObserver:onPreContactsChange: Starts
I/HwSystemManager( 3621): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3621): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3621): NotificationDBProvider:query starts, matchCode = 1
I/PhoneStatusBar( 3268): notification pkg =com.android.settings
I/PhoneStatusBar( 3268): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3268): notification pkg =android
I/PhoneStatusBar( 3268): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/HwSystemManager( 3621): ContactsObserver:loadLocalContacts: No contacts
,I/CalendarProvider2( 7611): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 7611): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     ( 2933): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/art     ( 2933): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,I/wpa_supplicant( 3317): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiMonitor( 2933): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3317): ELOOP: remaining timeout: 0.352847 eloop_data=0x558e89afb0 user_data=0x0 handler=0x555d6576c0
,E/WifiStateMachine( 2933):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 25 0
,I/HwSystemManager( 7306): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 7306): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 7306): PermissionDBAdapter:appcationsList size:150
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 1002
I/HwSystemManager( 3621): HoldService:uid:1002 pid:5313 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:1002,5313
,E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
W/MediaProcessHandler( 2933): processOp uid 1002 is not concerned!
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10302
I/HwSystemManager( 3621): HoldService:uid:10302 pid:6866 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10302,6866
I/PG Utils( 3621): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10302, pid: 6866
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10302, pid: 6866
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/HwLauncher( 3786): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3786): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3786): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,I/HwSystemManager( 7306): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2933): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,E/TEST-APN( 3731): query for APN: check-permission succ 
E/TEST-APN( 3731): Telephony query SQL: SELECT type, proxy, port FROM carriers WHERE (numeric = ',' and carrier_enabled = 1)
I/art     ( 2933): Can not find class: Lcom/android/server/usb/UsbSettingsManager$AccessoryFilter;
,I/HwSystemManager( 7306): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 7306): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 7306): HsmIntentService:last work complete! lets stop service.
,I/ActivityManager( 2933): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/HwLauncher( 3786): Launcher onStart()
I/HwLauncher( 3786): Launcher dynamicIconsRegister
I/HwLauncher( 3786): DynamicUpdater registerReceiver
,I/NetworkSpeedManagerEx( 3268): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3268): wifiManager = android.net.wifi.WifiManager@1e68903a
,W/PGApi_client( 3655): recv actoionId = 10010, action = com.huawei.pgmng.PGAction@196f476 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3655): in handleAction method, action = 10010
W/PGMiddleWare jhh( 3655): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@22fffe25, action = com.huawei.pgmng.PGAction@196f476 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3655): jhh handle default mActionId = 10010, action = com.huawei.pgmng.PGAction@196f476 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3655): enter into the safetyguard Scene.
W/AudioEffectLowPowerImpl jhh( 3655): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
,W/AudioEffectLowPowerImpl jhh( 3655): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3655): return for smartPAOn and mLowAudioEffectEnable both = false
,I/System.out( 3756): Stale Location error
W/Settings( 6540): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/SUPL20_SPIMESLP-SENDING( 3756): m_bPacket.length 119
I/SUPL20_SPIMESLP-SENDING( 3756): bBrokenPipe = false
,W/System.err( 2933): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 2933): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 2933): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 2933): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 2933): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2933): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2933): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/HwLauncher( 3786): DynamicUpdater call updateFolder
,I/HwLauncher( 3786): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3786): DynamicUpdater registerReceiver
I/HwSystemManager( 3621): ContactsObserverHelper:applyContactsUpdate: Starts
I/HwSystemManager( 3621): bbe:onContactsChange: Starts
I/HwSystemManager( 3621): ContactsObserverHelper:applyContactsUpdate: Ends
,W/Settings( 4080): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NetworkSpeedManagerEx( 3268): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3268): stop
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExchangeAccountType@1be64bb1 in the cache
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:0
,I/InputReader( 2933): Reconfiguring input devices.  changes=0x00000010
,I/SimFactoryManager( 7158): Get SIM state from SIM factory manager: 1,For slotId:1
I/HwSystemManager( 3621): AppLockService:applock password not initial or function is closed
I/HwSystemManager( 3621): AppManager:getNetAppInfoFromDB cursor lenth = 1
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExternalAccountType@8045896 in the cache
,I/HwLauncher( 3786): DynamicUpdater call updateFolder
I/HwLauncher( 3786): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3786): DynamicUpdater registerReceiver
I/HwSystemManager( 7306): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 7306): HsmPackageManager:replacing:false
I/HwSystemManager( 7306): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 7306): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwSystemManager( 7306): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@3cb70408
,I/art     ( 3621): Explicit concurrent mark sweep GC freed 94124(6MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 14MB/23MB, paused 6.190ms total 185.060ms
,I/HwSystemManager( 3621): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/HwSystemManager( 3621): HsmPackageManager:replacing:false
I/HwSystemManager( 3621): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 3621): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwSystemManager( 3621): ww:deleteLockData:com.example.hello
,W/ResourceType( 7158): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 7158): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 7158): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 7158): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.ExternalAccountType@16db9c17 in the cache
,I/AccountTypeManager( 7158): Adding account type = com.android.contacts.model.account.GoogleAccountType@35daa804 in the cache
,E/ExternalAccountType( 7158): Unsupported attribute readOnly
,I/AccountTypeManager( 7158): AccountManager, account size is: 2
,E/WifiStateMachine( 2933): could not open wifi state sys nodejava.io.FileNotFoundException: /sys/devices/platform/bcmdhd_wlan.1/wifi_open_state: open failed: ENOENT (No such file or directory)
,I/AccountTypeManager( 7158): Loaded meta-data for 5 account types, 3 accounts in 78ms(wall) 20ms(cpu)
,E/RegisteredServicesCache( 3707): invalidateCache set mNeedToastTableFull
,I/Choreographer( 3268): Skipped 45 frames!  The application may be doing too much work on its main thread.
,I/WifiTracker( 3268): STATE =0
,W/View    ( 3268): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{31be6613 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
,I/HwLauncher( 3786): DynamicUpdater call updateFolder
I/HwLauncher( 3786): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
I/HwLauncher( 3786): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3786): Launcher onResume()
I/HwLauncher( 3786): Launcher doResumeWork()
,I/HwLauncher( 3786): Launcher.MotionManager startMotionAppsReco 402
,I/HwLauncher( 3786): Launcher  onResume mIsToUninstallApp = false
,I/ActivityManager( 2933): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
,I/WifiTracker( 3268): STATE =0
,I/art     ( 2933): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,I/art     ( 2933): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,I/art     ( 2933): Can not find class: Lhuawei/com/android/server/util/ReportTool;
,I/art     ( 2933): Can not find class: Lcom/huawei/report/ReporterInterface;
,E/ReportTools( 2933): Can't find sReporterClazz
,I/art     ( 2933): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/art     ( 2933): Can not find class: Lhuawei/com/android/server/util/AppInfo;
,W/System.err( 2933): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 2933): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2933): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2933): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2933): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2933): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 2933): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 2933): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 2933): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 2933): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 2933): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 2933): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2933): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2933): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2933): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 2933): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 2933): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2933): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2933): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 2933): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 2933): This is not beta user build
,I/HwLauncher( 3786): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3786): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,W/GeofencerStateMachine( 4080): Ignoring removeGeofence because network location is disabled.
,E/WifiStateMachine( 2933):  InitialState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 2933):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10060
I/HwSystemManager( 3621): HoldService:uid:10060 pid:7227 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10060,7227
,E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10060, pid: 7227
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10060, pid: 7227
,E/WifiStateMachine( 2933):  InitialState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:894999873] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 2933):  DefaultState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:894999874] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,I/art     ( 2933): Explicit concurrent mark sweep GC freed 49227(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 4.129ms total 421.730ms
,I/Choreographer( 3786): Skipped 32 frames!  The application may be doing too much work on its main thread.
I/HwLauncher( 3786): Launcher  onWindowVisibilityChanged visibility = 0
,I/HwLauncher( 3786): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3786): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,W/asset   ( 7830): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/GCoreNlp( 4080): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/HwLauncher( 3786): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3786): Model replacing = false package = com.example.hello
I/HwLauncher( 3786): Model  ACTION_PACKAGE_REMOVED replacing = false
I/HwLauncher( 3786): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
,I/HwLauncher( 3786): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
I/HwLauncher( 3786): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
,I/HwLauncher( 3786): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3786): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3786): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3786): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
,I/HwLauncher( 3786): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,I/WifiTracker( 3268): STATE =0
,I/PG Utils( 4080): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3621): aor:Network Stats Updated
I/HwSystemManager( 3621): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10043
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10043, pid: 7334
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10043, pid: 7334
I/HwSystemManager( 3621): HoldService:uid:10043 pid:7334 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10043,7334
,I/HwCust  ( 7830): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,I/HwCust  ( 7830): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/PG Utils( 3786): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized,
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3621): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.,
,I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
I/HwLauncher( 3786): Model mAllAppsList.removePackage com.example.hello,
,W/ResourceType( 2933): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,I/PhoneStatusBar( 3268): shouldTranslucent:true
,I/PhoneStatusBar( 3268): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/WifiTracker( 3268): STATE =0
,I/HwLauncher( 3786): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,I/HwLauncher( 3786): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3786):  stringArray[] [unknown]
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
E/HwSystemManager( 3621): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3621): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3621): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3621): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3621): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3621): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,W/View    ( 3268): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{31be6613 V.E..... ........ 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,W/asset   ( 2933): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,E/HideAppsPagedView( 3786): removeItems begin 
E/HideAppsPagedView( 3786): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3786): removeItems end 
,I/HwLauncher( 3786): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
,I/HwSystemManager( 3621): BgPowerManagerService:onProcessDied uid = 10078
I/HwSystemManager( 3621): HoldService:uid:10078 pid:7359 died
I/HwSystemManager( 3621): HoldService:oldVersionKey:10078,7359
W/System.err( 3786): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
E/HsmCoreServiceImpl( 2933): onTransact in code is: 102
I/MediaProcessHandler( 2933): processOp opType: 1, uid: 10078, pid: 7359
W/MediaProcessHandler( 2933): remove target not exist, maybe the UI process: uid: 10078, pid: 7359
W/System.err( 3786): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3786): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3786): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3786): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3786): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3786): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3786): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3786): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3786): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
W/System.err( 3786): java.lang.NullPointerException: null receiver
W/System.err( 3786): 	at java.lang.reflect.Field.get(Native Method)
W/System.err( 3786): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3786): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3786): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3786): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3786): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3786): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3786): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3786): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3786): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwLauncher( 3786): CellLayout rearrangeAfterRmItem isAutoAlign = false
,I/WifiTracker( 3268): STATE =0
,I/GAv4    ( 7771): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7771):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7771):   adb logcat -s GAv4
,E/HideAppsPagedView( 3786): removeHideApps  begin 
,E/HideAppsPagedView( 3786): removeHideApps  end 
E/HideAppsPagedView( 3786):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3786):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3786):  createAddIcon count = 0
,I/HwLauncher( 3786):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,W/MotionDetectionManager( 3786): startMotionAppsReco motionApps: 402 disabled
W/HwLauncher( 3786): Launcher.MotionManager startMotionAppsReco service flg 402 is unavailable
,W/GAv4    ( 7771): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7771): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7771): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7771): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.44
,I/HwSystemManager( 7306): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 7306): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 7306): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,E/SQLiteLog( 7771): (3850) statement aborts at 2: [PRAGMA journal_mode=PERSIST] 
,E/SQLiteDatabase( 7771): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7771): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForString(Native Method)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:641)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:323)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:294)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:215)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/SQLiteDatabase( 7771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/SQLiteDatabase( 7771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7771): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7771): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7771): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7771): 	at aen.run(PG:536)
,I/HwSystemManager( 7306): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 7306): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 7306): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,W/ContextImpl( 7771): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,E/SQLiteDatabase( 7771): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7771): android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/SQLiteDatabase( 7771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/SQLiteDatabase( 7771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7771): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7771): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7771): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7771): 	at aej.c(PG:139)
E/SQLiteDatabase( 7771): 	at aej.b(PG:398)
E/SQLiteDatabase( 7771): 	at agf.f(PG:417)
E/SQLiteDatabase( 7771): 	at oe.run(PG:1112)
E/SQLiteDatabase( 7771): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7771): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7771): 	at java.lang.Thread.run(Thread.java:831)
,E/AbstractDatabaseInstance( 7771): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7771): android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/AbstractDatabaseInstance( 7771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/AbstractDatabaseInstance( 7771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7771): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7771): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7771): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7771): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7771): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7771): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7771): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7771): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7771): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7771): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7771): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7771): 	at java.lang.Thread.run(Thread.java:831)
,E/SQLiteLog( 7771): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error - SQLITE_IOERR_LOCK
,E/GAv4    ( 7771): Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
,E/SharedPreferencesImpl( 7771): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7771): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteLog( 7771): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error - SQLITE_IOERR_LOCK
,E/GAv4    ( 7771): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
,E/SharedPreferencesImpl( 7771): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 7771): android.database.sqlite.SQLiteDiskIOException: disk I/O error - SQLITE_IOERR_LOCK(Sqlite code 3850),(OS error - 9:Bad file number)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForString(Native Method)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:641)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:323)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:294)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:215)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/CAKEMIX_CRASHED( 7771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/CAKEMIX_CRASHED( 7771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7771): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7771): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7771): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7771): 	at aen.run(PG:536)
,W/OpenGLRenderer( 3786): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 3786): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/HwLauncher( 3786): Launcher onPause()
I/HwLauncher( 3786): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3786): Launcher.MotionManager stopMotionAppsReco 403
I/Process ( 7771): Sending signal. PID: 7771 SIG: 9
,W/HwLauncher( 3786): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
W/HwLauncher( 3786): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
,E/lowmemorykiller( 2290): Error writing /proc/7771/oom_score_adj; errno=22
,E/JavaBinder( 2933): !!! FAILED BINDER TRANSACTION !!!
,E/WifiStateMachine( 2933):  InitialState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 2933):  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/hwcomposer( 2293): setTopResource:1220: set top resource failed!! ret:-1 
E/hwcomposer( 2293): comp_mode= 0
E/hwcomposer( 2293): disp_ch_res = 0x0 
E/hwcomposer( 2293): res_info.ovly1_res = 0x0 
E/hwcomposer( 2293): res_info.ovly2_res = 0x205 
E/hwcomposer( 2293): res_info.ovly3_res = 0x46
E/hwcomposer( 2293): res_info.rot_res = 0x0
E/hwcomposer( 2293): res_info.scl2_res = 0x21
E/hwcomposer( 2293): res_info.compose_ch_res[0] = 0x408
E/hwcomposer( 2293): res_info.compose_ch_res[1] = 0x409
E/hwcomposer( 2293): res_info.compose_ch_res[2] = 0x40a
E/hwcomposer( 2293): res_info.compose_ch_res[3] = 0x80b
E/hwcomposer( 2293): res_info.compose_ch_res[4] = 0x52c
E/hwcomposer( 2293): res_info.compose_ch_res[5] = 0x4ad
E/hwcomposer( 2293): ade_reg_res = 0x0
E/hwcomposer( 2293): setGlobal:234: setTopResource fail!! 
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(34)
E/hwcomposer( 2293): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2293): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2293): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(57)
E/hwcomposer( 2293): phy_addr(0x2a2e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2293): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2293): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(2)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(5),  	 height(50),  	 width(720),  	 rotation(0), 	 sharefd(47)
E/hwcomposer( 2293): phy_addr(0x3136000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2293): stride(2880),  	 dst_height(50),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2293): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): commit:654: commit failed!! ret:-1, frame_number:497, 
E/hwcomposer( 2293): is_finished  (0), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2293): dst_rotation (0), 	 dst_rect xywh (0,0,720,50), 	 src_rect xywh (0,0,720,50) 
E/hwcomposer( 2293): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2293): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2293): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2293): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2293): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2293): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2293): finishOneArea:142: finishOneArea commit error
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(34)
E/hwcomposer( 2293): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovl,y_surf_num(0)
E/hwcomposer( 2293): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,50,720,1134),  	 dst_rect xywh(0,50,720,1134)
E/hwcomposer( 2293): ovly_output_rect xywh(0,50,720,1134),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(57)
E/hwcomposer( 2293): phy_addr(0x2a2e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2293): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,50,720,1134),  	 dst_rect xywh(0,50,720,1134)
E/hwcomposer( 2293): ovly_output_rect xywh(0,50,720,1134),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): commit:654: commit failed!! ret:-1, frame_number:497, 
E/hwcomposer( 2293): is_finished  (0), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2293): dst_rotation (0), 	 dst_rect xywh (0,50,720,1134), 	 src_rect xywh (0,50,720,1134) 
E/hwcomposer( 2293): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2293): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2293): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2293): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2293): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2293): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2293): finishOneArea:142: finishOneArea commit error
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(34)
E/hwcomposer( 2293): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2293): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,1184,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2293): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(57)
E/hwcomposer( 2293): phy_addr(0x2a2e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2293): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,1184,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2293): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(2)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(5),  	 height(96),  	 width(720),  	 rotation(0), 	 sharefd(55)
E/hwcomposer( 2293): phy_addr(0x31a2000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2293): stride(2880),  	 dst_height(96),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,0,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2293): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): commit:654: commit failed!! ret:-1, frame_number:498, 
E/hwcomposer( 2293): is_finished  (1), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2293): dst_rotation (0), 	 dst_rect xywh (0,1184,720,96), 	 src_rect xywh (0,1184,720,96) 
E/hw,composer( 2293): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2293): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2293): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2293): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2293): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2293): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2293): play:197: play commit error
E/hwcomposer( 2293): enableVsync:1073: vsync ioctl failed 
E/hwcomposer( 2293): EventControl:120: vsync ioctl failed
E/SurfaceFlinger( 2293): eventControl(0, 1) failed Operation not permitted
E/hwcomposer( 2293): setTopResource:1220: set top resource failed!! ret:-1 
E/hwcomposer( 2293): comp_mode= 0
E/hwcomposer( 2293): disp_ch_res = 0x3 
E/hwcomposer( 2293): res_info.ovly1_res = 0xc 
E/hwcomposer( 2293): res_info.ovly2_res = 0x0 
E/hwcomposer( 2293): res_info.ovly3_res = 0x0
E/hwcomposer( 2293): res_info.rot_res = 0x0
E/hwcomposer( 2293): res_info.scl2_res = 0x0
E/hwcomposer( 2293): res_info.compose_ch_res[0] = 0x0
E/hwcomposer( 2293): res_info.compose_ch_res[1] = 0x0
E/hwcomposer( 2293): res_info.compose_ch_res[2] = 0x0
E/hwcomposer( 2293): res_info.compose_ch_res[3] = 0x0
E/hwcomposer( 2293): res_info.compose_ch_res[4] = 0x0
E/hwcomposer( 2293): res_info.compose_ch_res[5] = 0x0
E/hwcomposer( 2293): ade_reg_res = 0x0
E/hwcomposer( 2293): setGlobal:234: setTopResource fail!! 
E/hwcomposer( 2293): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2293): compose_mode(0), 	 ch_index(6)
E/hwcomposer( 2293): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2293): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2293): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(21)
E/hwcomposer( 2293): phy_addr(0x402000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2293): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2293): src_rect xywh(0,0,720,1280),  	 dst_rect xywh(0,0,720,1280)
E/hwcomposer( 2293): ovly_output_rect xywh(0,0,720,1280),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2293): commit:654: commit failed!! ret:-1, frame_number:499, 
E/hwcomposer( 2293): is_finished  (1), 	 compose mode (0), 	 compose pattern num (3072) 
E/hwcomposer( 2293): dst_rotation (0), 	 dst_rect xywh (0,0,720,1280), 	 src_rect xywh (0,0,720,1280) 
E/hwcomposer( 2293): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2293): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2293): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2293): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2293): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2293): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2293): play:197: play commit error

```
