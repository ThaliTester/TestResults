#### Test 50388019aa1a16d_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/art     ( 3071): Explicit concurrent mark sweep GC freed 17236(900KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 1.838ms total 180.705ms
I/PG Utils( 6527): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/GHttpClientFactory( 6527): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6527): Using platform SSLCertificateSocketFactory
W/System.err( 3071): java.lang.SecurityException: WifiService: Neither user 10084 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 3071): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 3071): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 3071): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 3071): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 3071): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 3071): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 3071): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 6527): WifiServiceMessenger == null
I/HwCust  ( 6570): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
W/HWContacts( 6570): ProviderFeatureChcker - cootek package not installed
E/TmoMonitor( 6570): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@f87b8e8
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10056
I/HwSystemManager( 3714): HoldService:uid:10056 pid:5784 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10056,5784
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10056, pid: 5784
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10056, pid: 5784
I/HwCust  ( 6570): Constructor found for class com.android.mms.data.HwCustConversationImpl
I/EmuiFeatureManager( 6570): loadEmailAnrSupportFlag:true
I/Mms_threadcache( 6570): [RecipientIdCache] fill: begin
I/SimFactoryManager( 6570): Inside init method of SimFactoryManger the combination is:-1
I/SimFactoryManager( 6570): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6570): isSIM1CardPresent:1
I/SimFactoryManager( 6570): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6570): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6570): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
I/SimFactoryManager( 6570): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6570): isSIM2CardPresent:1
E/MmsConfig( 6570): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
I/SimFactoryManager( 6570): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6570): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6570): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
I/HwCust  ( 6570): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
I/MagazineUtils( 3352): is magazine unlock on, now is lock screen diabled mode
I/HwCust  ( 6570): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
I/art     ( 6570): Can not find class: Lhuawei/android/view/TableLayout;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/TableLayout;
I/art     ( 6570): Can not find class: Lhuawei/android/view/View;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/View;
I/art     ( 6570): Can not find class: Landroid/widget/View;
I/art     ( 6570): Can not find class: Landroid/webkit/View;
I/art     ( 6570): Can not find class: Landroid/app/View;
I/art     ( 6570): Can not find class: Lhuawei/android/view/TableRow;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/TableRow;
I/art     ( 6570): Can not find class: Lhuawei/android/view/LinearLayout;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/LinearLayout;
I/art     ( 6570): Can not find class: Lhuawei/android/view/ImageButton;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/ImageButton;
I/art     ( 6570): Can not find class: Lhuawei/android/view/TextView;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/TextView;
I/HwCust  ( 6570): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
I/HwCust  ( 6570): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
I/art     ( 2325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 441us total 24.480ms
I/art     ( 6570): Can not find class: Lhuawei/android/view/RelativeLayout;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/RelativeLayout;
I/art     ( 6570): Can not find class: Lhuawei/android/view/ImageView;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/ImageView;
I/GAV2    ( 6167): Thread[GAThread,5,main]: No campaign data found.
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/GAv4-SVC( 6041): Google Analytics 8.3.01 is starting up.
I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 425us total 44.266ms
I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 555us total 32.395ms
E/HwOUC   ( 6609): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
I/art     ( 6570): Can not find class: Lhuawei/android/view/ViewStub;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/ViewStub;
I/art     ( 6570): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6570): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6570): Can not find class: Landroid/app/ViewStub;
I/art     ( 6609): Can not find class: Lcom/huawei/pad/Product;
E/HwOUC   ( 6609): [main-1]method invoke failed(/HwOucUtility.java:471)
I/HwOUC   ( 6609): [main-1]isTablet() = false(/HwOucUtility.java:474)
I/HwOUC   ( 6609): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
I/HwOUC   ( 6609): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
I/HwOUC   ( 6609): [main-1]Network changed(hwouc/DownloadReceiver.java:138)
I/HwOUC   ( 6609): [main-1]Network available(hwouc/DownloadReceiver.java:142)
I/HwOUC   ( 6609): [main-1]Push apk is not exists !(hwouc/DownloadReceiver.java:454)
I/HwOUC   ( 6609): [main-1]checkRequestSendSuccessFlag is true(hwouc/DownloadReceiver.java:163)
I/HwOUC   ( 6609): [main-1]is6HourReportedFlag is true(hwouc/DownloadReceiver.java:178)
I/HwOUC   ( 6609): [Thread-94-94]isExternalSdcardExist, no External SDCard(hwouc/HwOucUtility.java:995)
I/HwOUC   ( 6609): [Thread-94-94]isCheckAutoAndReport is true(hwouc/KillMyselfProcessCheckThread.java:370)
I/art     ( 6570): Can not find class: Lhuawei/android/view/FrameLayout;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/FrameLayout;
I/art     ( 6570): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/EditText;
E/textview( 6570): initAddtionalStyle default
I/art     ( 6570): Can not find class: Lhuawei/android/view/ProgressBar;
I/art     ( 6570): Can not find class: Lhuawei/android/widget/ProgressBar;
I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 6570): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
I/Process ( 6609): Sending signal. PID: 6609 SIG: 9
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 3714): HoldService:uid:10065 pid:5843 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10065,5843
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10065, pid: 5843
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10065, pid: 5843
W/asset   ( 6638): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
I/HwCust  ( 6570): Constructor found for class com.huawei.mms.util.HwCustUpdateUserBehaviorImpl
I/HwCust  ( 6570): Constructor found for class com.huawei.mms.util.HwCustHwMessageUtilsImpl
I/Mms_TXM_SVC( 6570): onStartCommand send EVENT_NEW_INTENT. service-id 1
W/Mms_TXM_SVC( 6570): ConnectivityBroadcastReceiver.onReceive() action: android.net.conn.CONNECTIVITY_CHANGE
I/HwCust  ( 6638): Constructor found for class com.huawei.android.thememanager.common.HwCustThemeHelperImpl
I/art     ( 6638): Can not find class: Landroid/provider/Settings$Systemex;
E/HwThemeManager( 6638): ThemeHelperretry to get Settings
E/WifiStateMachine( 3071):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=65 tx=4.1, 0.0, 0.0  rx=13.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:616229754] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 3071):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=65 tx=4.1, 0.0, 0.0  rx=13.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:616229754] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 3071): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=65 SSID="NG700"
E/WifiStateMachine( 3071): calculateWifiScore freq=2462 speed=65 score=100 highRSSI  -> txbadrate=0.00 txgoodrate=2.03 txretriesrate=0.00 rxrate=13.25 userTriggerdPenalty0
E/WifiStateMachine( 3071):  good link -> stuck count =0
E/WifiStateMachine( 3071):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine( 3071):  isHighRSSI       ---> score=61
I/HwEmailTag( 6497): EmailProvider->query->1448020208539;end;;consuming:2ms;
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10052
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 1050
I/HwSystemManager( 3714): HoldService:uid:10052 pid:6609 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10052,6609
I/HwSystemManager( 3714): HoldService:uid:1050 pid:5867 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:1050,5867
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10052, pid: 6609
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10052, pid: 6609
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
W/MediaProcessHandler( 3071): processOp uid 1050 is not concerned!
I/HwEmailTag( 6497): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/HwEmailTag( 6497): Device->updateDeviceIdIfNeeded
I/HwEmailTag( 6497): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 6497): CleanRecipient->onCreate
I/HwEmailTag( 6497): Device->getDeviceId->
I/HwEmailTag( 6497): Device->getDeviceIdInternal->isUpdate:false
I/HwEmailTag( 6497): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 6497): CleanRecipient->onStartCommand->action is null
I/HwEmailTag( 6497): CleanRecipient->onHandleIntent->action is null
I/HwEmailTag( 6497): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
I/HwEmailTag( 6497): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
I/HwEmailTag( 6497): CleanRecipient->onDestroy
I/HwEmailTag( 6497): AccountReconciler->reconcileAccountsInternal->consuming:131ms
W/asset   ( 6665): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
I/HwEmailTag( 6497): EmailProvider->query->1448020208677;end;;consuming:2ms;
I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 190us total 28.071ms
I/HwEmailTag( 6497): AccountReconciler->reconcileAccountsInternal->consuming:8ms
I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 219us total 27.835ms
I/HwCust  ( 6665): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 230us total 24.560ms
I/HwCust  ( 6690): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
I/HwEmailTag( 6690): EmailContent->init->consuming:30ms->;-prefixstartupperformance-
I/HwEmailTag( 6690): Exchange->onCreate
E/HwSystemManager( 5806): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
I/PG Utils( 6690): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
I/PG Utils( 6690): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
I/HwEmailTag( 6497): EmailProvider->query->1448020208842;end;;consuming:2ms;
I/HwEmailTag( 6690): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
I/StagefrightMediaScannerEx( 3420): StagefrightMediaScanner destructor
I/StagefrightMediaScannerEx( 3420): StagefrightMediaScanner destructor
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10090
I/HwSystemManager( 3714): HoldService:uid:10090 pid:5912 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10090,5912
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10090, pid: 5912
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10090, pid: 5912
I/appproc ( 6688): CLASSPATH=/system/framework/am.jar
I/appproc ( 6688): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 6688): app_process:number,5,0
I/AndroidRuntime( 6688): readDownloadBoosterConfig: 'false'
I/        ( 6688): power log dlsym ok
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10092
I/HwSystemManager( 3714): HoldService:uid:10092 pid:5945 died
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/HwSystemManager( 3714): HoldService:oldVersionKey:10092,5945
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10092, pid: 5945
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10092, pid: 5945
E/android_hardware_fm.cpp( 6688): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6688): ========64bit long size = 8
E/FM_HAL  ( 6688): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6688): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6688): 
I/fm_hisi ( 6688): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6688): 
I/fm_hisi ( 6688): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6688): 
E/android_hardware_fm.cpp( 6688): register_android_hardware_fm_fmradio, ret is 0
W/ContextImpl( 6741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/ContextImpl( 6741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/ContextImpl( 6741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6741): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6741):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6741):   adb logcat -s GAv4
W/ContextImpl( 6741): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/art     ( 3071): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 3071): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 3071): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 3071): Can not find class: Lcom/android/server/wm/StartingData;
I/HwLauncher( 3889): Launcher onPause()
I/HwLauncher( 3889): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3889): Launcher.MotionManager stopMotionAppsReco 403
I/art     ( 3071): Can not find class: Landroid/widget/ViewStub;
I/art     ( 3071): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 3071): Can not find class: Landroid/app/ViewStub;
W/HwLauncher( 3889): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
W/HwLauncher( 3889): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
W/GAv4    ( 6741): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6741): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 3071): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwLauncher( 3889): Launcher onStop()
I/HwLauncher( 3889): Launcher dismissDialog
I/HwLauncher( 3889): Launcher dynamicIconsUnregister
I/HwLauncher( 3889): DynamicUpdater unregisterReceiver
W/GAv4    ( 6741): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/HwEmailTag( 6497): EmailProvider->handleNetworkChanged->network is good, start new EmailConnectivityTask
I/HwEmailTag( 6497): EmailProvider->triggerAllPeriodSync
I/HwEmailTag( 6497): EmailProvider->triggerPeroidSync->accountId:-1
I/HwEmailTag( 6497): EmailConnectivityTask->syncOutbox
I/HwEmailTag( 6497): EmailProvider->query->1448020209566;end;;consuming:2ms;
W/PGApi_client( 3777): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@1920b55c actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3777): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3777): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@3ff6bd00, action = com.huawei.pgmng.PGAction@1920b55c actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3777): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@1920b55c actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3777): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3777): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3777): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3777): return for smartPAOn and mLowAudioEffectEnable both = false
I/PhoneStatusBar( 3441): shouldTranslucent:true
I/PhoneStatusBar( 3441): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwLauncher( 3889): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3889): DynamicUpdater unregisterReceiver
I/HwLauncher( 3889): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3889): DynamicUpdater unregisterReceiver
I/HwLauncher( 3889): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3889): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwSystemManager( 3714): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3889): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3889): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3889): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3889): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 3714): AppLockService:applock password not initial or function is closed
I/PG Utils( 6741): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/WebViewFactory( 6787): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/art     ( 6741): Can not find class: Ljava/util/ConcurrentNavigableMap;
I/LibraryLoader( 6787): Loading: webviewchromium
I/LibraryLoader( 6787): Time to load native libraries: 57 ms (timestamps 8787-8844)
I/LibraryLoader( 6787): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 6787): Expected native library version number "",actual native library version number ""
I/chromium( 6787): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/WebViewFactory( 6741): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/LibraryLoader( 6741): Loading: webviewchromium
I/LibraryLoader( 6741): Time to load native libraries: 4 ms (timestamps 8897-8901)
I/LibraryLoader( 6741): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 6787): Initializing chromium process, renderers=0
I/LibraryLoader( 6741): Expected native library version number "",actual native library version number ""
I/chromium( 6741): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 6787): Attempt to remove local handle scope entry from IRT, ignoring
I/ContactsAppilcation( 6570): intent:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
I/BrowserStartupController( 6741): Initializing chromium process, renderers=0
W/art     ( 6741): Attempt to remove local handle scope entry from IRT, ignoring
I/CommonUtilMethods( 6570): action:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6570): intent:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
I/CommonUtilMethods( 6570): action:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6570): intent:android.provider.Telephony.SPN_STRINGS_UPDATED
W/AudioManagerAndroid( 6741): Requires BLUETOOTH permission
W/chromium( 6741): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6741): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=46092 len=2953
I/chromium( 6741): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:45 off:228796 len:643667
W/chromium( 6787): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6787): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 6787): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
I/NSApplication( 6741): Starting up...
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/iu.SyncManager( 6041): SYNC; picasa accounts
I/System  ( 6116): core_booster, getBoosterConfig = false
I/iu.Environment( 6041): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 6041): num queued entries: 0
I/iu.UploadsManager( 6041): num updated entries: 0
I/iu.SyncManager( 6041): NEXT; no task
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/Babel   ( 6116): connection state changed from UNKNOWN to CONNECTED
W/chromium( 6787): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6787): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6787): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10095
I/HwSystemManager( 3714): HoldService:uid:10095 pid:5968 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10095,5968
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10095, pid: 5968
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10095, pid: 5968
W/art     ( 6787): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6787): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 6787): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6787): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6787): Can not find class: Landroid/app/ViewStub;
,W/art     ( 6787): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6787): Attempt to remove local handle scope entry from IRT, ignoring
,I/PG Utils( 6879): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/art     ( 3071): Explicit concurrent mark sweep GC freed 14610(828KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 28MB/42MB, paused 2.826ms total 260.174ms
,I/PG Utils( 6879): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/OpenGLRenderer( 6787): Initialized EGL, version 1.4
,I/art     ( 3071): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
,I/ActivityManager( 3071): Displayed com.example.hello/.MainActivity: +1s436ms
,I/HwEmailTag( 6497): PeakSchedulingService->onHandleIntent : intent.getAction() -> com.huawei.email.service.PEAK_TIME_SET
,I/HwEmailTag( 6497): EmailProvider->query->1448020210816;end;;consuming:1ms;
,I/chromium( 6787): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6787): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10001
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/HwSystemManager( 3714): HoldService:uid:10001 pid:5223 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10001,5223
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10001, pid: 5223
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10001, pid: 5223
,I/AccountTypeManager( 6570): Adding account type = com.android.contacts.model.account.ExchangeAccountType@9d7ab9b in the cache
,I/SimFactoryManager( 6570): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6570): Get SIM state from SIM factory manager: 1,For slotId:1
,I/HwCust  ( 6570): Constructor found for class com.android.contacts.model.account.HwCustAccountModelCustomizationImpl
,I/AccountTypeManager( 6570): Adding account type = com.android.contacts.model.account.ExternalAccountType@28a2b711 in the cache
,W/ResourceType( 6570): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6570): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6570): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6570): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6570): Adding account type = com.android.contacts.model.account.ExternalAccountType@1b7b6677 in the cache
I/AccountTypeManager( 6570): Adding account type = com.android.contacts.model.account.GoogleAccountType@3cd12e4 in the cache
,E/ExternalAccountType( 6570): Unsupported attribute readOnly
,I/chromium( 6787): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6787): 
,I/AccountTypeManager( 6570): AccountManager, account size is: 2
,I/AccountTypeManager( 6570): Loaded meta-data for 5 account types, 3 accounts in 86ms(wall) 54ms(cpu)
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10087
I/HwSystemManager( 3714): HoldService:uid:10087 pid:5990 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10087,5990
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10087, pid: 5990
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10087, pid: 5990
,W/jxcore-log( 6787): Initializing JXcore engine
W/jxcore-log( 6787): JXcore engine is ready
,W/jxcore-log( 6787): Starting JXcore engine
,I/Process ( 6947): Sending signal. PID: 6947 SIG: 9
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 1001
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10041
I/HwSystemManager( 3714): HoldService:uid:1001 pid:6947 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:1001,6947
I/HwSystemManager( 3714): HoldService:uid:10041 pid:6167 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10041,6167
,E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
W/MediaProcessHandler( 3071): processOp uid 1001 is not concerned!
,E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10041, pid: 6167
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10041, pid: 6167
,W/StubController( 6974): calendar access!
,W/jxcore-log( 6787): Platform android
W/jxcore-log( 6787): 
W/jxcore-log( 6787): Process ARCH arm
W/jxcore-log( 6787): 
,E/WifiStateMachine( 3071):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=65 tx=2.0, 0.0, 0.0  rx=13.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:616232761] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 3071):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=65 tx=2.0, 0.0, 0.0  rx=13.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:616232762] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 3071): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=65 SSID="NG700"
,E/WifiStateMachine( 3071): calculateWifiScore freq=2462 speed=65 score=100 highRSSI  -> txbadrate=0.00 txgoodrate=3.02 txretriesrate=0.00 rxrate=12.62 userTriggerdPenalty0
E/WifiStateMachine( 3071):  good link -> stuck count =0
E/WifiStateMachine( 3071):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine( 3071):  isHighRSSI       ---> score=61
,I/jxcore-log( 6787): JXcore Cordova bridge is ready!
I/jxcore-log( 6787): 
,W/jxcore-log( 6787): JXcore engine is started
,I/HwEmailTag( 6497): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 6497): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 6497): EmailProvider->triggerPeroidSync->accountId:-1
,E/jxcore-log( 6787): >> HUAWEI-ALE-L21
E/jxcore-log( 6787): 
,I/jxcore-log( 6787): Total memory 1949741056
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Free memory 23601152
I/jxcore-log( 6787): 
I/jxcore-log( 6787): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6787): 
I/jxcore-log( 6787): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6787): 
,I/PG Utils( 6974): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/jxcore-log( 6787): userPath [ 'www' ]
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Size 720 1184
I/jxcore-log( 6787): 
,I/jxcore-log( 6787): Screen Brightness 242
I/jxcore-log( 6787): 
,E/jxcore-log( 6787): Dummy Error Log.
E/jxcore-log( 6787): 
,W/StubController( 6997): calendar access!
,W/StubController( 6974): calendar access!
,I/PG Utils( 6974): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10026
I/HwSystemManager( 3714): HoldService:uid:10026 pid:6378 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10026,6378
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10026, pid: 6378
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10026, pid: 6378
,I/DeskClockApplication( 7025): onCreate
,W/StubController( 6974): calendar access!
,I/AlarmInitReceiver( 7025): AlarmInitReceiver->OnReceive->AsyncHandler : needSetSnoozeAlert = false alarmnow = false
,I/ActivityManager( 3071): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10010
I/HwSystemManager( 3714): HoldService:uid:10010 pid:6409 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10010,6409
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10010, pid: 6409
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10010, pid: 6409
,E/HwOUC   ( 7051): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
,I/art     ( 7051): Can not find class: Lcom/huawei/pad/Product;
,E/HwOUC   ( 7051): [main-1]method invoke failed(/HwOucUtility.java:471)
,I/HwOUC   ( 7051): [main-1]isTablet() = false(/HwOucUtility.java:474)
,I/HwOUC   ( 7051): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
,I/HwOUC   ( 7051): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
,I/jxcore-log( 6787): getBuffer is called!!!!
I/jxcore-log( 6787): 
,I/HwOUC   ( 7051): [main-1]Intent.ACTION_TIME_CHANGED nextInstallRemindTime:Thu Jan 01 00:59:59 GMT+01:00 1970(hwouc/DownloadReceiver.java:370)
,I/HwOUC   ( 7051): [main-1]Intent.ACTION_TIME_CHANGED alarmRegistTime:Thu Jan 01 00:59:59 GMT+01:00 1970(hwouc/DownloadReceiver.java:372)
,I/HwOUC   ( 7051): [main-1]Intent.ACTION_TIME_CHANGED nextCheckNewVersionTime:Sat Nov 21 10:51:39 GMT+01:00 2015(hwouc/DownloadReceiver.java:400)
,I/HwOUC   ( 7051): [main-1]Intent.ACTION_TIME_CHANGED startTime:Fri Nov 20 10:51:39 GMT+01:00 2015(hwouc/DownloadReceiver.java:402)
,I/HwOUC   ( 7051): [main-1]Intent.ACTION_TIME_CHANGED currentTime:Fri Nov 20 12:50:12 GMT+01:00 2015(hwouc/DownloadReceiver.java:404)
,I/HwSystemManager( 5806): PreventReceiver:RreventReceiver receive the action :android.intent.action.TIME_SET
,I/HwSystemManager( 5806): PreventReceiver:TriggerAgainTask-doInBackground: time switch = false, time list size = 0
,I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/CheckinService( 6041): Checkin interval check for package: unspecified last checkin: 1448013111636 min interval config: 0 actual interval: 7100580
,I/ActivityManager( 3071): filter receiver for action = com.google.android.music.START_DOWNLOAD_SCHEDULING
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10025
I/HwSystemManager( 3714): HoldService:uid:10025 pid:6435 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10025,6435
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10025, pid: 6435
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10025, pid: 6435
,I/art     ( 3071): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,W/StubController( 6974): calendar access!
,W/StubController( 6974): calendar access!
,I/CalendarSimpleUiPRovider( 6974): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6974): onConfigurationChanged
,I/CalendarSimpleUiPRovider( 6974): initParams20151120T125012Europe/Warsaw(5,323,3600,0,1448020212)
,I/PG Utils( 6974): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 6974): calendar access!
,W/StubController( 6974): calendar access!
,W/StubController( 6974): calendar access!
,I/CalendarSimpleUiPRovider( 6974): loadEvent end update UI0
,I/HwLauncher( 3889): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwEmailTag( 6497): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/HwLauncher( 3889): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3889): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3889): Model STK reName intent is received.
,I/HwLauncher( 3889): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3889): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3889): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwLauncher( 3889): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3889): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3889): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3889): Model STK reName intent is received.
,I/HwLauncher( 3889): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3889): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3889): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3889): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3889): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3889): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3889): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3889): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3889): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3889): Launcher.Folder childCount: 5
I/HwLauncher( 3889): Launcher.Folder childCount: 5
I/HwLauncher( 3889): Launcher.Folder childCount: 7
I/HwLauncher( 3889): Launcher.Folder childCount: 7
I/HwLauncher( 3889): Launcher.Folder childCount: 6
I/HwLauncher( 3889): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3889): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3889): Launcher.Folder childCount: 6
I/HwLauncher( 3889): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3889): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3889): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3889): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3889): Launcher.Folder childCount: 7
I/HwLauncher( 3889): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3889):  syncPages mCurrentPage = 0
,I/HwLauncher( 3889): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3889): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3889): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3889): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3889): Model shortcutInfo.title = SIM Toolkit
E/HideAppsPagedView( 3889):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3889):  createAddIcon count = 0
,I/CalendarProvider2( 6997): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar },
I/HwLauncher( 3889):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
W/ContentResolver( 6997): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 3071): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/HwLauncher( 3889): Launcher Deferring update until onResume
,I/HwLauncher( 3889): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3889): Launcher.Folder childCount: 5
I/HwLauncher( 3889): Launcher.Folder childCount: 5
I/HwLauncher( 3889): Launcher.Folder childCount: 7
I/HwLauncher( 3889): Launcher.Folder childCount: 7
I/HwLauncher( 3889): Launcher.Folder childCount: 6
I/HwLauncher( 3889): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3889): Launcher.Folder childCount: 6
,I/HwLauncher( 3889): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3889): Launcher.Folder childCount: 7,
I/HwLauncher( 3889): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3889):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3889):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
,E/HideAppsPagedView( 3889):  createAddIcon count = 0
,I/HwLauncher( 3889):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3889): Launcher Deferring update until onResume
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10084
,I/HwSystemManager( 3714): HoldService:uid:10084 pid:6527 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10084,6527
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10084, pid: 6527
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10084, pid: 6527
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10004
I/HwSystemManager( 3714): HoldService:uid:10004 pid:6570 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10004,6570
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10004, pid: 6570
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10004, pid: 6570
,W/BluetoothAdapter( 4980): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 4980): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 4980): Accept thread started.
,I/HwCust  ( 7118): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
,W/HWContacts( 7118): ProviderFeatureChcker - cootek package not installed
,E/TmoMonitor( 7118): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@f87b8e8
,I/HwCust  ( 7118): Constructor found for class com.android.mms.data.HwCustConversationImpl
,I/EmuiFeatureManager( 7118): loadEmailAnrSupportFlag:true
,I/Mms_threadcache( 7118): [RecipientIdCache] fill: begin
,I/SimFactoryManager( 7118): Inside init method of SimFactoryManger the combination is:-1
,I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 7118): isSIM1CardPresent:1
,I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:0
,E/MmsConfig( 7118): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
,I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 7118): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 7118): isSIM2CardPresent:1
,I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:0
,I/HwCust  ( 7118): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
,E/Thermal-daemon( 2332): [ap] temp_new :34  temp_old :33
,I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 7118): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,E/CSP_RADAR( 7118): Message execute too long time.{ when=-97ms what=1 target=com.huawei.mms.util.HwBackgroundLoader$3 }
,I/HwCust  ( 7118): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
,I/art     ( 7118): Can not find class: Lhuawei/android/view/TableLayout;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/TableLayout;
,I/art     ( 7118): Can not find class: Lhuawei/android/view/View;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/View;
,I/art     ( 7118): Can not find class: Landroid/widget/View;
,I/art     ( 7118): Can not find class: Landroid/webkit/View;
,I/art     ( 7118): Can not find class: Landroid/app/View;
,I/HwCust  ( 7118): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
,I/art     ( 7118): Can not find class: Lhuawei/android/view/TableRow;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/TableRow;
,I/art     ( 7118): Can not find class: Lhuawei/android/view/LinearLayout;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/LinearLayout;
,I/HwCust  ( 7118): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
,I/art     ( 7118): Can not find class: Lhuawei/android/view/ImageButton;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/ImageButton;
,I/art     ( 7118): Can not find class: Lhuawei/android/view/TextView;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/TextView;
,I/art     ( 7118): Can not find class: Lhuawei/android/view/RelativeLayout;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/RelativeLayout;
,I/art     ( 7118): Can not find class: Lhuawei/android/view/ImageView;
I/art     ( 7118): Can not find class: Lhuawei/android/widget/ImageView;
,I/art     ( 7118): Can not find class: Lhuawei/android/view/ViewStub;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/ViewStub;
I/art     ( 7118): Can not find class: Landroid/widget/ViewStub;
I/art     ( 7118): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 7118): Can not find class: Landroid/app/ViewStub;
,I/ActivityManager( 3071): filter receiver for action = android.intent.action.PACKAGE_CHANGED
,I/HwLauncher( 3889): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwSystemManager( 3714): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HwLauncher( 3889): Model replacing = false package = com.google.android.gms
I/HwSystemManager( 3714): HsmPackageManager:replacing:false
,I/HwSystemManager( 3714): HsmPackageManager:pkgName:com.google.android.gms
,I/HwLauncher( 3889): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.google.android.gms]
I/HwLauncher( 3889): Model mAllAppsList.updatePackage com.google.android.gms
I/HwLauncher( 3889): SimpleLauncherModeaction= android.intent.action.PACKAGE_CHANGEDpackageName = com.google.android.gms
E/RegisteredServicesCache( 3819): invalidateCache set mNeedToastTableFull
I/HwSystemManager( 3714): HsmPackageManager:doAppChanged, put com.google.android.gms, path:/data/app/com.google.android.gms-2
,I/HwLauncher( 3889): AllIdleAppsList  updatePackage : package[com.google.android.gms] matched activity's size is 1 and data List size is 61
I/InputReader( 3071): Reconfiguring input devices.  changes=0x00000010
,I/HwLauncher( 3889): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3889): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = Google Settings
I/HwLauncher( 3889): Model shortcutInfo.title = Google Settings
I/HwLauncher( 3889): SimpleLauncherModemAllAppsList.updatePackage com.google.android.gms
I/HwLauncher( 3889): Workspace updateShortcuts apps.size() 1
I/HwLauncher( 3889): Launcher.Folder childCount: 9
I/HwLauncher( 3889): Launcher.Folder childCount: 5
I/HwLauncher( 3889): Workspace updateShortcuts shortcutInfo = Google Settings
,W/ResourceType( 3071): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
I/HwLauncher( 3889): SimpleAllAppsList  updatePackage : package[com.google.android.gms] matched activity's size is 1 and data List size is 0
,I/HwLauncher( 3889): Launcher.Folder childCount: 7
I/HwLauncher( 3889): Launcher.Folder childCount: 9
I/HwLauncher( 3889): Launcher.Folder childCount: 6
I/HwLauncher( 3889): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3889):  syncPages mCurrentPage = 0
I/art     ( 7118): Can not find class: Lhuawei/android/view/FrameLayout;
I/art     ( 7118): Can not find class: Lhuawei/android/widget/FrameLayout;
I/art     ( 7118): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 7118): Can not find class: Lhuawei/android/widget/EditText;
I/HwLauncher( 3889): SimpleAllAppsList  findAndUpdateInfoInDB : found 0 shortcutInfo for package[com.google.android.gms] in db
I/HwLauncher( 3889): SimpleAllAppsList  updatePackage do not add new SimpleApplicationInfo,It's in normal now. package = com.google.android.gms
W/HwLauncher( 3889): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
E/HideAppsPagedView( 3889):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3889):  createAddIcon count = 0
E/textview( 7118): initAddtionalStyle default
I/HwLauncher( 3889):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3889): Launcher Deferring update until onResume
,I/art     ( 7118): Can not find class: Lhuawei/android/view/ProgressBar;
,I/art     ( 7118): Can not find class: Lhuawei/android/widget/ProgressBar;
,W/asset   ( 3071): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 7118): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,I/art     ( 3071): Can not find class: Lcom/android/server/usb/UsbSettingsManager$AccessoryFilter;
,I/HwSystemManager( 3714): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3714): BgPowerManagerService: mTimes = 36497 firstTime = 26237 firstmBatteryCapacity =2205
,I/art     ( 3071): Explicit concurrent mark sweep GC freed 24732(1336KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.985ms total 170.345ms
,I/GCoreNlp( 4108): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/PG Utils( 4108): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10064
I/HwSystemManager( 3714): HoldService:uid:10064 pid:6665 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10064,6665
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10064, pid: 6665
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10064, pid: 6665
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10005
I/HwSystemManager( 3714): HoldService:uid:10005 pid:6690 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10005,6690
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10005, pid: 6690
I/HwSystemManager( 3714): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10005, pid: 6690
I/HwSystemManager( 3714): NotificationManagerReceiver:onReceive, send action to background
,I/HwSystemManager( 3714): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@20d2c2f0
,I/HwSystemManager( 3714): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3714): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
I/HwSystemManager( 5806): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 3714): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings]
,I/HwSystemManager( 3714): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
I/HwSystemManager( 5806): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@1256f1c4
I/HwSystemManager( 5806): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
I/HwSystemManager( 5806): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
I/HwSystemManager( 3714): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
,I/HwSystemManager( 3714): NmCenterDefValueXmlHelper:getConfigs: Starts
,I/HwSystemManager( 5806): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,I/HwSystemManager( 5806): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 5806): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 5806): OverseaCfgHelper:permissionStatus is 0
,I/HwSystemManager( 3714): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33
I/HwCust  ( 5806): Constructor found for class com.huawei.systemmanager.optimize.process.HwCustProtectAppControlImpl
,I/HwSystemManager( 3714): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
,I/HwSystemManager( 3714): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 3714): AppCleanUpService:onStartCommand() out!
E/HwSystemManager( 3714): AppCleanUpService:msg is 0
,I/HwSystemManager( 5806): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,I/HwSystemManager( 5806): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
W/HwSystemManager( 5806): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 5806): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 5806): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 5806): HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:3, queue size:0
I/HwSystemManager( 5806): HsmPackageManager:begin to scan apks.
,I/HwSystemManager( 3714): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3714): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3714): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 3714): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3714): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 3714): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3714): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3714): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 5806): anf:packageCanAccessInternet com.example.hellohas INTERNET permission
,I/PhoneStatusBar( 3441): notification pkg =com.android.settings
I/PhoneStatusBar( 3441): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3441): notification pkg =android
I/PhoneStatusBar( 3441): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,I/HwSystemManager( 5806): anf:packageCanAccessInternet component enable
,I/HwSystemManager( 3714): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3714): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3714): HsmIntentService:last work complete! lets stop service.
,I/HwSystemManager( 5806): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello, replacing: false
,I/YhdsEngine( 5806): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
,I/HwSystemManager( 5806): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
I/HwSystemManager( 5806): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 5806): AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 5806): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 5806): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 5806): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 5806): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 5806): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 5806): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], applock=[Rule AppLockNotMonitorListRule post: match[0], mismatch[2], Rule HomeCategoryRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 5806): XmlRuleBase:parseAndCacheList dropzone_black_list_match :[]
I/HwSystemManager( 5806): XmlRuleBase:parseAndCacheList permission_black_list_match :[]
I/HwSystemManager( 5806): XmlRuleBase:parseAndCacheList black_match :[]
I/HwSystemManager( 5806): XmlRuleBase:parseAndCacheList dropzone_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 5806): XmlRuleBase:parseAndCacheList permission_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 5806): XmlRuleBase:parseAndCacheList white_match :[com.baidu.map.location, com.cootek.smartdialer_oem_module, com.sohu.inputmethod.sogou.huawei, com.huawei.hisuite, com.nuance.swype.emui, com.huawei.remoteassistant, com.iflytek.speechcloud, com.huawei.phoneservice, com.huawei.phonediagnose, com.nqmobile.antivirus20.hw, com.baidu.input_huawei]
I/HwSystemManager( 5806): HsmPackageManager:end to scan apks. size:150 + 0
I/HwSystemManager( 3714): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@20d2c2f0
I/HwSystemManager( 5806): HsmPackageManager:init locale:en_US
I/HwSystemManager( 5806): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 5806): HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:2, queue size:0
I/HwSystemManager( 5806): ProtectAppControl:handleMessage:6
,I/HwSystemManager( 5806): ProtectAppControl:begin install app inner:com.example.hello
I/HwSystemManager( 5806): AppManager:insert to db: name = com.example.hello uid = 10302 app type = false
I/HwSystemManager( 5806): PermissionDBAdapter:DBAdapter created!
W/HwSystemManager( 5806): AddViewAppManager:Current installed app not apply system_alert_window or applicationInfo null!
W/HwSystemManager( 5806): ProtectAppControl:com.example.hello already exist!
I/HwSystemManager( 5806): PermissionDbHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/permission.db
I/HwSystemManager( 5806): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 5806): PermissionDBAdapter:appcationsList size:150
,E/WifiStateMachine( 3071):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=65 tx=3.0, 0.0, 0.0  rx=12.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:616235771] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 3071):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2462 sc=100 link=65 tx=3.0, 0.0, 0.0  rx=12.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:616235772] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 3071): fetchRssiLinkSpeedAndFrequencyNative rssi=-64 linkspeed=65 SSID="NG700"
,E/WifiStateMachine( 3071): calculateWifiScore freq=2462 speed=65 score=100 highRSSI  -> txbadrate=0.00 txgoodrate=1.51 txretriesrate=0.00 rxrate=8.31 userTriggerdPenalty0
E/WifiStateMachine( 3071):  good link -> stuck count =0
E/WifiStateMachine( 3071):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine( 3071):  isHighRSSI       ---> score=61
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 362us total 39.435ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 220us total 31.484ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 178us total 23.967ms
,I/HwSystemManager( 5806): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 5806): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 5806): PermissionDBAdapter:appcationsList size:150
,I/HwSystemManager( 3714): ContactsObserverHelper:onContactsChanged: Start to handle contacts change message
,I/HwSystemManager( 3714): bbe:onPreContactsChange: Starts
,I/HwSystemManager( 3714): ContactsObserver:onPreContactsChange: Starts
,I/HwSystemManager( 3714): ContactsObserver:loadLocalContacts: No contacts
,I/PG Utils( 3714): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3714): ContactsObserverHelper:applyContactsUpdate: Starts
I/HwSystemManager( 3714): bbe:onContactsChange: Starts
I/HwSystemManager( 3714): ContactsObserverHelper:applyContactsUpdate: Ends
,I/HwSystemManager( 5806): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 5806): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 5806): HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 5806): HsmIntentService:last work complete! lets stop service.
,I/HwSystemManager( 5806): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@1256f1c4
,I/GAv4    ( 7224): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7224):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7224):   adb logcat -s GAv4
,W/GAv4    ( 7224): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7224): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7224): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7224): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.44
,W/ContextImpl( 7224): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/ContactsAppilcation( 7118): intent:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,I/CommonUtilMethods( 7118): action:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 7118): intent:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
,I/CommonUtilMethods( 7118): action:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 7118): intent:android.provider.Telephony.SPN_STRINGS_UPDATED
,E/WifiStateMachine( 3071):  ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 3071):  L2ConnectedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 3071):  ConnectModeState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 3071):  DriverStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 3071):  SupplicantStartedState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 3071):  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10043
I/HwSystemManager( 3714): HoldService:uid:10043 pid:6714 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10043,6714
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10043, pid: 6714
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10043, pid: 6714
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/GmsModuleInitializer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/app/GmsApplicationContext;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue;
,I/art     ( 6041): Can not find class: Lcom/google/android/flib/pref/PreferenceFile;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/PlatformVersion;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils$1;
,I/art     ( 6041): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/Asserts;
,I/art     ( 7224): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 7224): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReaderImpl;
,I/ProviderInstaller( 7224): Installed default security provider GmsCore_OpenSSL
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReader;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/receiver/PlaySystemBroadcastReceiver;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/UserAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/GamesSyncAdapter;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/sync/BaseGmsSyncAdapter;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/config/G;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesLog;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/VersionUtils;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/GamesSharedPrefs;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$AsyncOperationQueue;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/Preconditions;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/AsyncOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$OperationTask;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService$PooledAsyncOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/WrappedGamesCallbacks;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/quests/AcceptQuestOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractDataHolderOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$Operation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/requests/AcceptRequestOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/AcceptTurnBasedMatchInvitationOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/AcknowledgeNotificationsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/AddNearbyPlayerOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractStatusReportingOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CancelTurnBasedMatchOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/quests/ClaimMilestoneOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/ClearDataOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/ClearNotificationsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/events/ClearPendingEventsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/ApiClientTracker;
I/art     ( 3071): Can not find class: Lcom/android/server/accounts/AccountManagerService$TestFeaturesSession;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveContents;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/CommitSnapshotOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomEnteredCallback;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/ConnectionInfo;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/safeparcel/SafeParcelable;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/CreateRoomOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CreateTurnBasedMatchOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DeclineInvitationOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/DeleteSnapshotOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DismissInvitationOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/DismissTurnBasedMatchOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/DismissPlayerSuggestionOperation;,
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/requests/DismissRequestOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/multiplayer/ParticipantResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/FinishTurnBasedMatchOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/GetGamesAuthTokenOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/GetInboxActivityCountsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/GetScoreOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$GamesThreadFactory;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/GetTurnBasedMatchOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/AccountsChangedOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/PackageModifiedOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/PeopleChangedOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/PopupManager$PopupLocationInfo;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/IncrementAchievementOperation;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/events/EventIncrementEntry;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/events/IncrementEventsOperation;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/InitializeGamesOperation;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/InvalidateAppContentOperation;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/IsGameMutedOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/JoinRoomOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/video/VideoConfiguration;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/video/LaunchGameForRecordingOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/client/IPlayGamesCallbacks;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/ClientContext;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomLeftCallback;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveDiagnostics;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/response/FastMapJsonResponse;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/response/FastJsonResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/LeaveRoomOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LeaveTurnBasedMatchOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/video/ListVideosOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsInternalOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AppContentContext;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/LoadAppContentOperation;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractMultiDataHolderOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadCircledPlayersOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameCollectionComparisonOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadConnectedPlayersOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/LoadContactSettingsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsByIdOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/LoadExperimentsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadFirstPartyPlayersOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameFirstPartyOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameInstancesOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameSearchSuggestionsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGamesCollectionOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadInvitablePlayersOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/LoadInvitationsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadLeaderboardsOperation;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadMoreScoresOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpStreamOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/acls/LoadNotifyAclOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadPlayGamesRecentlyPlayedOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayerOperation;,
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadScoresOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/stats/LoadPlayerStatsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersInternalOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadProfileSettingsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/quests/LoadQuestsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestSummariesOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/LoadSnapshotsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LoadTurnBasedMatchesOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpForGameCategoriesOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/NotificationOpenedOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/RecordApplicationSessionOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/RecordPlayerSuggestionActionOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/RematchTurnBasedMatchOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$P2pStatusReportCallback;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/ReportP2pStatusOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/ResolveSnapshotConflictOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/UpdateAchievementOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/SearchForGamesOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/SearchForPlayersOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/requests/SendRequestOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/SetAchievementStepsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/SetGameMuteStatusOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/SetIdentitySharingConfirmedOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/quests/QuestStateChangedPopupOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/SignOutOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/AndroidUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$OperationAdapter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/video/StopRecordingOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/SubmitScoreOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/UpdateContactSettingsOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/acls/UpdateNotifyAclOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/games/UpdatePlayedOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/players/UpdateProfileSettingsOperation;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/UpdateTurnBasedMatchOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/IGmsCallbacks;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/GetServiceRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/ValidatePlayServiceConnectionOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/ValidateServiceConnectionOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/VerifySnapshotFolderOperation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$2;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/DataBroker;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/Lockable;
,I/HwSystemManager( 5806): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 5806): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 5806): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/service/OperationException;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/auth/GoogleAuthException;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/Lockable$LockableLock;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/GamesServer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/AbstractServer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/auth/appcert/AppCertServiceClient;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/auth/AuthSessionAuthenticator;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/error/ErrorUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/auth/GoogleAuthUtil;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer$DefaultApiaryRetryPolicy;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$1;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$Batch;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/response/FieldMappingDictionary;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/ApiaryRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/VolleyInterruptedError;
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/NoResponseRequest;
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/ImageRequest;
,I/PeopleContactsSync( 6041): CP2 sync disabled
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/GamesRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GamesExperiments;
,I/art     ( 6041): Can not find class: Lcom/google/android/play/experiments/PlayExperiments;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/Base64Utils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/config/GamesOptions;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/error/ErrorInstanceResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/error/GamesException$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/error/GamesException;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$6;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$1;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$3;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$4;,
,I/art     ( 6041): Can not find class: Lcom/google/android/gsf/Gservices;
,I/art     ( 6041): Can not find class: Lcom/google/android/gsf/Gservices$1;
,I/art     ( 6041): Can not find class: Lcom/google/android/gsf/Gservices$1$1;,
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/GamesServerFactory;,
,W/BaseAppContext( 6041): Using Auth Proxy for data requests.
,W/BaseAppContext( 6041): Using Auth Proxy for data requests.
I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/server/PlusServer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/config/G;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/SpamAndAbuseHeaders;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/server/ContainerParam;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/auth/AuthTokenTimeCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/server/SocialClient;
,W/BaseAppContext( 6041): Using Auth Proxy for data requests.
,W/BaseAppContext( 6041): Using Auth Proxy for data requests.
,I/art     ( 4139): Explicit concurrent mark sweep GC freed 11531(744KB) AllocSpace objects, 8(160KB) LOS objects, 40% free, 17MB/29MB, paused 1.076ms total 73.572ms
,W/BaseAppContext( 6041): Using Auth Proxy for data requests.,
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryServer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/utils/Log;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/G;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$5;,
,I/HwSystemManager( 5806): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!,
,I/HwSystemManager( 5806): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 5806): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/Icing   ( 6041): Storage manager: low false usage 1.72MB avail 7.14GB capacity 8.84GB
,W/Icing   ( 6041): Received bad json for section weights override -- ignoring.
,W/Icing   ( 6041): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 6041): Received bad json for section weights override -- ignoring.
W/Icing   ( 6041): Received bad json for corpus context scoring override -- ignoring.
,I/art     ( 6041): Explicit concurrent mark sweep GC freed 35017(2MB) AllocSpace objects, 20(400KB) LOS objects, 40% free, 19MB/31MB, paused 8.296ms total 150.830ms
,W/BaseAppContext( 6041): Using Auth Proxy for data requests.
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/TransientCacheOwner;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/InboxCounter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$Builder;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$DataType;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/utils/GamesDataUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/DefaultClock;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/Clock;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/BaseApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApi;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/AchievementCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/Agents$QueryBuilder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementDefinitions;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementDefinitionsColumns;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/DataHolder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/DataHolder$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Players;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayersColumns;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$1;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementFlushData;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleRequest;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/ApiRateLimitUtil;
,I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/error/ErrorResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementInstances;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementInstancesColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/provider/QuerySpec;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/achievement/AchievementBuffer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/AbstractDataBuffer;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/DataBuffer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/Releasable;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/achievement/Achievement;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/Freezable;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/Agents;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$TypeQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementStepData;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$IncrementQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/ui/popup/AchievementPopup;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/ui/popup/BasePopup;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlayGamesUploadService;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/GcmTaskService;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinition;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/response/FastContentValuesJsonResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievement;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/GamePlayerCacheKey;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementPendingOps;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementPendingOpsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$PendingOpsQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/constants/AchievementState;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/util/AccountUtils;
I/art     ( 6041): Can not find class: Landroid/support/v4/util/ArrayMap;
I/art     ( 6041): Can not find class: Landroid/support/v4/util/SimpleArrayMap;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementSetStepsAtLeast;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementIncrement;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementUpdateResult;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementIncrementResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationFetchList;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementGetMultipleResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementListResponse;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementSetStepsAtLeastResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUnlockResponse;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AchievementRevealResponse;
,I/art     ( 6041): Can not find class: Landroid/support/v4/util/ContainerHelpers;
,I/art     ( 6041): Can not find class: Landroid/support/v4/util/ArrayMap$1;
,I/art     ( 6041): Can not find class: Landroid/support/v4/util/MapCollections;
I/art     ( 6041): Can not find class: Landroid/support/v4/util/MapCollections$KeySet;
,I/art     ( 6041): Can not find class: Landroid/support/v4/util/MapCollections$ArrayIterator;
,I/PG Utils( 6879): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/Icing   ( 6041): Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache$OwnerCache;
,I/art     ( 6041): Can not find class: Landroid/support/v4/util/LruCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/BaseGmsContentProvider;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/Objects;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$UriType;
,I/art     ( 6041): Can not find class: Lcom/android/common/content/ProjectionMap;
,I/art     ( 6041): Can not find class: Lcom/android/common/content/ProjectionMap$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/provider/TableJoiner;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerLevels;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerLevelColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerStats;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerStatsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ClientContexts;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ClientContextsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestPendingOps;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestPendingOpsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ApplicationSessions;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ApplicationSessionColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AppContents;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AppContentColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Images;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ImagesColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardPendingScores;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Requests;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Matches;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchesPendingOps;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesPendingOpsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesDataStore;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesDatabaseHelper;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/utils/UriUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$ImageCleaner;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$3;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/ImageStore;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/ImageStore$Entry;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$GamesProjectionMapBuilder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameInstances;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameInstancesColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventInstances;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventInstancesColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventPendingOps;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventPendingOpsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ExperienceEvents;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ExperienceEventColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Invitations;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$InvitationsColumns;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Participants;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ParticipantsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardInstances;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardInstancesColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardScores;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardScoresColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Notifications;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$NotificationsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Milestones;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MilestoneColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestRecipients;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestRecipientsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Snapshots;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$SnapshotColumns;
,I/art     ( 6041): Can not find class: Lcom/android/common/SharedPreferencesCompat;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Games;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GamesColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventDefinitions;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventDefinitionColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Leaderboards;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/constants/OfflineMatchAction;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Quests;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$QuestsColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$1;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleterAssociatedQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$2;
,W/CursorWrapperInner( 6974): Cursor finalized without prior close()
,I/PG Utils( 7308): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7277): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/AccountTypeManager( 7118): Adding account type = com.android.contacts.model.account.ExchangeAccountType@fd325d9 in the cache
,I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:1
,I/HwCust  ( 7118): Constructor found for class com.android.contacts.model.account.HwCustAccountModelCustomizationImpl
,I/PG Utils( 7277): acquire_providerpkg:[com.google.android.partnersetup] pid:[]  maybe timeout , send to PG
,I/AccountTypeManager( 7118): Adding account type = com.android.contacts.model.account.ExternalAccountType@3b8d267f in the cache
,I/PG Utils( 7166): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/ResourceType( 7118): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 7118): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
,W/ResourceType( 7118): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
,W/ResourceType( 7118): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
,I/AccountTypeManager( 7118): Adding account type = com.android.contacts.model.account.ExternalAccountType@4474695 in the cache
,I/AccountTypeManager( 7118): Adding account type = com.android.contacts.model.account.GoogleAccountType@3618a3aa in the cache
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AppContentsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/AppContentSectionAndCardCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/AppContentBaseCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/AppContentActionCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/AppContentAnnotationCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/AppContentConditionCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/AppContentTupleCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$CardImageInsertHelper;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ContentEntry;
E/ExternalAccountType( 7118): Unsupported attribute readOnly
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Section;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Card;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/CardAnnotation;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ImageAsset;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/CardCondition;
I/AccountTypeManager( 7118): AccountManager, account size is: 2
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/CardAction;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/response/FastParser$ParseException;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/GamesCardScreenFirstPartyResponse;
I/AccountTypeManager( 7118): Loaded meta-data for 5 account types, 3 accounts in 98ms(wall) 57ms(cpu)
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$ServerCookieQuery;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/constants/DeviceType;
I/UpdateIcingCorporaServi( 7277): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/EventAgent;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/EventResolver;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventsApi;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$WindowInfo;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodRange;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodUpdate;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$PendingOpsQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$EventDefinitionRefreshInfo;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinition;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinitionListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$UnresolvedException;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEvent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEventListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventRecordRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/GameCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/GameSearchCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/BaseSearchCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplication;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Application;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/MarketApplication;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/MarketBadge;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ImageConfig;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/converter/ImageUrlBuilder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/MarketInstance;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameBadges;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameBadgesColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Instance;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/InstanceAndroidDetails;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/util/PackageUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Snapshot;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/util/PanoUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationCategory;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/GameBuffer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/Game;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationList;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchContext;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchList;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetUpdatesMultipleFirstPartyResponse;
,I/BluetoothAdapter( 6787): Start to disable Bluetooth!
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsFlushData;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/SessionBatch;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetMultipleFirstPartyResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$FirstPartyGameListProcessor;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationListFirstPartyResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$GameRefreshRecord;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/TransientDataHolder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$VersionQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplicationUpdates;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/constants/AppUpdateType;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/ArrayUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/InvalidId;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCacheKey;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$StoreGamesProcessor;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameSearchSuggestions;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameSearchSuggestionsColumns;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestion;
,I/art     ( 3071): Can not find class: Lcom/android/server/DropBoxManagerService$1$1;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/DataUtils;
,I/BluetoothAdapterState( 4980): Bluetooth adapter state changed: 12-> 13
,I/bluedroid( 4980): bt interface: [set_adapter_property]
W/bt-btm  ( 4980): BTM_SetDiscoverability
I/BluetoothAdapterState( 4980): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/ActivityManager( 3071): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
,W/bt-btm  ( 4980): BTM_SetConnectability
W/bt-btif ( 4980): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4980): adapterPropertyChangedCallback with type:7 len:4
I/bluedroid( 4980): bt interface: [disable]
W/bt-btif ( 4980): btif_disable_bluetooth, btif_core_radio_ref_count=0
W/bt-btif ( 4980): BTIF DISABLE BLUETOOTH
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationSearchFirstPartyResponse;
W/bt-btif ( 4980): bta_sys_disable: module 0
W/bt-btm  ( 4980): BTM_SetDiscoverability
W/bt-btm  ( 4980): BTM_SetConnectability
W/bt-btif ( 4980): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 4980): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0017 not found for deregistration
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsQuery;
W/System.err( 3071): java.lang.SecurityException: WifiService: Neither user 10025 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 3071): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 3071): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 3071): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 3071): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 3071): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 3071): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 3071): 	at android.os.Binder.execTransact(Binder.java:446)
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Session;
,E/WifiManager( 7308): WifiServiceMessenger == null
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$InstanceQuery;
,E/BtOppRfcommListener( 4980): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApiInternal;
,I/BtOppRfcommListener( 4980): stopping Accept Thread
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/LeaderboardScoreCache;
I/BtOppRfcommListener( 4980): BluetoothSocket listen thread finished
I/UpdateIcingCorporaServi( 7277): UpdateCorporaTask done [took 151 ms] updated apps [took 150 ms] 
,W/View    ( 3441): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{982d206 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Leaderboard;
I/bluetooth-coex( 4980): bt_coex_deinit: bt_coex_deinit
I/bluetooth-coex( 4980): btcoex_send_msg: send bt_state(0) to wifi, sock_fd(72)
I/bluetooth-coex( 4980): btcoex_socket_server: accept socket success
I/bluetooth-coex( 4980): btcoex_send_msg: bt closing, exit coex server, sock_fd(72)
I/bluetooth-coex( 4980): btcoex_socket_server: BT_COEX_PTHREAD_EXIT
I/bluetooth-coex( 4980): bt_coex_deinit: clear coex timer list entry
I/bluetooth-coex( 4980): bt_coex_deinit: free g_bt_coex_cb
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScores;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardEntry;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Player;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/constants/LeaderboardCollection;,
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/constants/TimeSpan;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PageTokensQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheKey;
,I/HwSystemManager( 3714): HoldService:checkBeforeShowDialog: uid:10302 pid:6787, permissionType:2097152
I/HwSystemManager( 3714): OverseaCfgHelper:permissionStatus is 0
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheOwner;
,I/ConnectPermission( 3071): allowOpenWifi blocked:false
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PendingScoreQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/provider/SelectionArgs;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ScoreSubmission;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreSubmissionList;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListFirstPartyResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScoreListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScore;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScoreRank;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GamesDroidGuard;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScore;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData$Result;
,W/Settings( 7308): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7308): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10078
I/HwSystemManager( 3714): HoldService:uid:10078 pid:6741 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10078,6741
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10078, pid: 6741
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10078, pid: 6741
,I/PG Utils( 7308): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 7308): acquire_providerpkg:[com.android.providers.downloads] pid:[]  maybe timeout , send to PG
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/NotificationAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/PlayCommonAgent;
,E/WifiStateMachine( 3071):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 3071):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6787): ****TEST TOOK:  5248  ms ****
I/jxcore-log( 6787): 
E/WifiStateMachine( 3071):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 3071):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6787): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6787): 
E/WifiStateMachine( 3071):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 3071): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 3071): setScanAlarm false period 20000 initial delay 0
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/NonListener;
E/WifiStateMachine( 3071): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid c0:ff:d4:d3:aa:48
E/WifiStateMachine( 3071): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3071): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApiInternal;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleApi;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/PeopleApi;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/MetagameApiInternal;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ExperiencesApiInternal;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/PlayerCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/PlayerSearchCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/ContactSettingsCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/ProfileSettingsCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/cache/XpEventStreamCache;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/PlayerBuffer;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/Player;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$CircledStateQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p$Builder;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient$Builder;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/People;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/Api;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions$HasOptions;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions;
I/wpa_supplicant( 3531): set current WIFI status to BT!
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/ConnectionResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyPlayer;
,W/bt-btif ( 4980): bta_sys_hw_api_disable for 0, active modules: 0x0001
W/bt-btif ( 4980): bta_sys_disable: module 0
W/bt-btif ( 4980): call bta_sys_hw_co_disable
W/bt-btif ( 4980): sending BTA_SYS_EVT_DISABLED_EVT
W/bt-btif ( 4980): bta_sys_hw_evt_disabled - module 0x0
W/bt-btif ( 4980):  bta_dm_sys_hw_cback with event: 0
W/bt-btif ( 4980): btif_disable_bluetooth_evt, btif_core_is_radio_req = 0
W/bt-btif ( 4980): btif_dm_disable_bt_services
,W/bt-btif ( 4980): btif_dm_disable_bt_services i=6
W/bt-btif ( 4980): btif_dm_disable_bt_services i=18
W/bt-btif ( 4980): btif_dm_disable_bt_services i=20
W/bt-btif ( 4980): btif_dm_disable_bt_services i=25
W/bt-btif ( 4980): bte_main_enable_lpm
W/bt-btif ( 4980): bte_main_disable
W/bt_lpm  ( 4980): Still busy on processing prior LPM enable/disable request...
W/bt-btif ( 4980): ag scb idx 1 not allocated
W/bt_userial( 4980): select_read return size <=0:-1, exiting userial_read_thread
E/bt-btif ( 4980): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 4980): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 4980): ag scb idx 1 not allocated
E/bt-btif ( 4980): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 4980): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4980): L2CAP - PSM: 0x0017 not found for deregistration
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Played;,
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListFirstPartyResponse;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$PeopleNetworkData;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/PlayerLevel;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Experience;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PeopleFeed;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/response/FastSafeParcelableJsonResponse;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person$Image;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleFeed;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/model/people/Person;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/model/people/Person$Image;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$TrimExperiencesQuery;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ProfileSettings;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleOptions;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/internal/PeopleUtils;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/Graph;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/PendingResult;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/Result;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleResult;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/People$ReleasableResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/Status;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/model/PersonBuffer;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/model/DataBufferWithSyncInfo;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/people/model/Person;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/logging/GamesPlayLogger;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/data/GamesDataChangeUris;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity$ImageEntity;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/images/ImageBroker;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$LevelQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/GamesStatusCodes;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ContactSettings;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ContactChannelSetting;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/constants/NotificationChannel;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/CategoryListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Category;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/MetagameConfig;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLevel;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceSyncFirstPartyResponse;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$SyncNetworkResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AccountMetadata;
,I/ActivityManager( 3071): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3071): filter receiver for action = android.net.wifi.STATE_CHANGE
,I/ActivityManager( 3071): filter receiver for action = com.google.android.gcm.DISCONNECTED
,I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 3071): filter receiver for action = android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 3071): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/AlarmInitReceiver( 7025): handleMessage : AlarmInitReceiver, will exit app. Config.exit_count: 0
,I/art     ( 7025): System.exit called, status: 0
I/AndroidRuntime( 7025): VM exiting with result code 0, cleanup skipped.
,E/WifiStateMachine( 3071): Unexpected BatchedScanResults :OK
,E/ArpVerifier( 3071): current SSID is empty.
E/WifiStateMachine( 3071): noteBatchedScanstop()
,E/WifiStateMachine( 3071): [1,448,020,216,975 ms] noteScanEnd no scan source
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent;
,E/WifiStateMachine( 3071):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3071):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApi;
E/WifiStateMachine( 3071):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3071): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApiInternal;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataApiInternal;
E/WifiStateMachine( 3071):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestonesApi;
E/WifiStateMachine( 3071):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 3071):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 3071): Can not find class: Lcom/android/server/wifi/RttService$RttServiceImpl$ClientInfo;
E/WifiStateMachine( 3071): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3071):  WaitForP2pDisableState !CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Quest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestone;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestCriterion;
E/WifiStateMachine( 3071):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 3071):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestContribution;
,E/WifiStateMachine( 3071): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/quest/QuestBuffer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/EntityBuffer;
E/WifiStateMachine( 3071):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/quest/Quest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$QuestsEntities;
,I/wpa_supplicant( 3531): set current WIFI status to BT!
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/Joiner;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/GameEventListenerRegistry;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/ui/popup/QuestPopup;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$SyncNetworkResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$NotifyDataHolder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$MilestoneClaimedQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestListFirstPartyResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataSyncFirstPartyResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/QuestSyncFirstPartyResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/RevisionAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RevisionsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyRevisionCheckResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AclAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AclsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMember;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingRoster;
I/art     ( 6041): Can not find class: Lcom/google/protobuf/micro/MessageMicro;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingTargetId;
I/art     ( 6041): Can not find class: Lcom/google/protobuf/micro/InvalidProtocolBufferMicroException;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Acl;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMemberConversions;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Acls;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AclsColumns;
,I/ActivityManager( 3071): filter receiver for action = android.net.wifi.STATE_CHANGE
I/art     ( 3071): Can not find class: Lcom/android/server/NetworkManagementService$IdleTimerParams;
I/wpa_supplicant( 3531): set current WIFI status to BT!
I/wpa_supplicant( 3531): WIFI closed already, cancel
I/wpa_supplicant( 3531): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/AclUpdateRequest;
W/wpa_supplicant( 3531): check_associate_result func start
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent;
E/WifiMonitor( 3071): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/ActivityManager( 3071): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
E/WifiMonitor( 3071): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestSummaryColumns;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RequestsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/OutboundRequestInfo;
I/ActivityManager( 3071): filter receiver for action = android.net.wifi.supplicant.STATE_CHANGE
,W/System.err( 3071): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
E/HI110X_CHR_LOGD( 2693): [chr_log_do_rotate:2346]cur_num is zero:errono:No such file or directory
W/System.err( 3071): 	at com.huawei.android.server.wifi.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3071): 	at com.huawei.android.server.wifi.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3071): 	at com.huawei.android.server.wifi.ReportTool.report(ReportTool.java:58)
W/System.err( 3071): 	at com.huawei.android.server.wifi.DataUploader.e(DataUploader.java:57)
W/System.err( 3071): 	at com.android.server.wifi.WifiMonitor.handleNetworkStateChange(WifiMonitor.java:1420)
W/System.err( 3071): 	at com.android.server.wifi.WifiMonitor.handleEvent(WifiMonitor.java:1018)
W/System.err( 3071): 	at com.android.server.wifi.WifiMonitor.dispatchEvent(WifiMonitor.java:988)
W/System.err( 3071): 	at com.android.server.wifi.WifiMonitor.access$500(WifiMonitor.java:55)
W/System.err( 3071): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.dispatchEvent(WifiMonitor.java:701)
W/System.err( 3071): 	at com.android.server.wifi.WifiMonitor$WifiMonitorSingleton.access$700(WifiMonitor.java:586)
W/System.err( 3071): 	at com.android.server.wifi.WifiMonitor$MonitorThread.run(WifiMonitor.java:759)
E/ReportTools( 3071): This is not beta user build
,E/lowmemorykiller( 2292): Error writing /proc/7025/oom_score_adj; errno=22
I/HwSystemManager( 3714): aor:Network Stats Updated
I/HwSystemManager( 3714): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RequestRecipient;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestEntities;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/request/GameRequestBuffer;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/request/GameRequest;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$RequestSummariesData;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/PlayerRef;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/DataBufferRef;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/GameRef;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateList;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdate;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$SyncNetworkResponse;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RequestEntity;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Request;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyNotification;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/InboundRequestInfo;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$TrimRequestsQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$PendingOpsQuery;
E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/SendRequest;
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/constants/RequestType;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RequestSyncResponseFirstParty;
,E/HwSystemManager( 3714): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResultList;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResult;
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/service/FilesApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/Drive;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveApi;
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveApi$ResourceIdSetResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet$Builder;
,E/HwSystemManager( 3714): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/MetadataBundle;
I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/MetadataField;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/CustomPropertyKey;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/data/BitmapTeleporter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/Query;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveApi$MetadataBufferResult;
I/appproc ( 7370): CLASSPATH=/system/framework/pm.jar
I/appproc ( 7370): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 7370): app_process:number,5,0
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$ResultPair;
E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/MetadataBuffer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/Api$ClientKey;
,I/AndroidRuntime( 7370): readDownloadBoosterConfig: 'false'
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/Api$Client;
E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/GmsClient;
E/HwSystemManager( 3714): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/GmsClientEventManager$GmsClientEventState;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/LogicalFilter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/AbstractFilter;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/Filter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl$6;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/internal/DriveBaseApiMethodImpl;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ApiMethodImpl;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/internal/BasePendingResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ResultHolder;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/api/internal/GoogleApiClientImpl$Runner;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/FullTextSearchDetector;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/FilterVisitor;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/Metadata;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveId;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/mdm/DeviceManager;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi$DeviceNameResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$DriveIdQuery;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveIdResult;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveFile;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveResource;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveResource$MetadataResult;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$TitleMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/StringMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/BaseMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/SortableMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$ModifiedMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/DateMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/OrderedMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableOrderedMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$MimeTypeMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/internal/model/File;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/postprocessor/PostProcessorHelper;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveContentsResult;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation$SnapshotOpenData;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties$Builder;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/Agents$TwoColumnMapper;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange$Builder;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/service/PlaySnapshotEventService;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/chimera/DriveEventService;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/ImageUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveFolder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/internal/DriveFolderImpl;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/internal/DriveResourceImpl;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFolderResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotListResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFileResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/Query$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/SearchableField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableCollectionMetadataField;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/InFilter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/ComparisonFilter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/Operator;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/HasFilter;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/SortOrder$Builder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$CreatedMetadataField;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/internal/FieldWithSortOrder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/drive/query/SortOrder;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/util/IOUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/StatsAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/StatsApi;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/StatsResponse;
,E/WifiStateMachine( 3071):  SupplicantStoppingState !CMD_ON_QUIT 0 0
,E/WifiStateMachine( 3071):  DefaultState !CMD_ON_QUIT 0 0
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitiesApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchEntities;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyMultiplayerEntity;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/Room;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatch;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/multiplayer/InvitationBuffer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/multiplayer/Invitation;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/multiplayer/Participatable;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/multiplayer/Participant;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$SyncNetworkResponse;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$VersionInfo;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerUtils;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitySyncFirstParty;
,E/WifiMonitor( 3071): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,E/WifiStateMachine( 3071):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=66165
E/WifiStateMachine( 3071):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=66166
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApi;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/NetworkDiagnostics;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent$RoomCache;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomJoinRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/constants/Capability;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomClientAddress;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomCreateRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomAutoMatchingCriteria;
,I/Icing   ( 6041): updateResources: need to parse f{com.google.android.gms}
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveRequest;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomP2PStatuses;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/RoomStatus;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent;
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApi;,
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApiInternal;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchResults;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/MatchParticipantResult;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent$PendingOpsQuery;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/server/response/FastParser;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchTurn;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchDataRequest;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchCreateRequest;,
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedAutoMatchingCriteria;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/internal/constants/TurnBasedMatchStatus;,
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/multiplayer/turnbased/TurnBasedMatchBuffer;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchRematch;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController$CaptureStateCallback;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay$CaptureOverlayListener;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GamesUris;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent$MetadataQuery;
,I/        ( 7370): power log dlsym ok
,I/        ( 4980): [vendor/huawei_platform/connectivity/hisi/hisi_connectivity/bt/hal/src/bt_vendor_hisi.c: hisi_cleanup 354][bt_vendor] cleanup
W/wpa_supplicant( 3531): STA MODE: Set shutdown wlan cmd SUCCESS
,I/GKI_LINUX( 4980): gki_task task_id=0 [BTU] terminating
W/wpa_supplicant( 3531): check_associate_result func start
I/GKI_LINUX( 4980): GKI_exit_task 0 done
I/GKI_LINUX( 4980): GKI_shutdown(): task [BTU] terminated
W/bt-btif ( 4980): HAL bt_hal_cbacks->adapter_state_changed_cb
E/WifiMonitor( 3071): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 3071):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=66262  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 3071):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=66263  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/android_hardware_fm.cpp( 7370): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 7370): ========64bit long size = 8
E/FM_HAL  ( 7370): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 7370): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 7370): 
I/fm_hisi ( 7370): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 7370): 
I/fm_hisi ( 7370): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 7370): 
,E/android_hardware_fm.cpp( 7370): register_android_hardware_fm_fmradio, ret is 0
,I/art     ( 3071): Explicit concurrent mark sweep GC freed 37608(1999KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 22.157ms total 229.375ms
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/Agents$1;
,I/NetworkSpeedManagerEx( 3441): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3441): wifiManager = android.net.wifi.WifiManager@362a1279
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10045
I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10013
I/HwSystemManager( 3714): HoldService:uid:10045 pid:7025 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10045,7025
I/HwSystemManager( 3714): HoldService:uid:10013 pid:6922 died
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/HwSystemManager( 3714): HoldService:oldVersionKey:10013,6922
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10045, pid: 7025
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10045, pid: 7025
I/MusicStore( 7372): Database version: 120
,E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/HwSystemManager( 3714): aor:Network Stats Updated
I/HwSystemManager( 3714): aoi:onNetworkStatsUpdated
I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10013, pid: 6922
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10013, pid: 6922
,I/NetworkSpeedManagerEx( 3441): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3441): stop
I/art     ( 6041): Can not find class: Lcom/google/android/gms/games/broker/Agents$2;
,I/art     ( 6041): Can not find class: Lcom/google/android/gms/common/internal/ClientContextCreator;
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
,W/BluetoothHeadsetServiceJni( 4980): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 4980): Cleaning up Bluetooth Handsfree callback object
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3714): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/GKI_LINUX( 4980): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 4980): GKI_exit_task 2 done
,I/GKI_LINUX( 4980): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 4980): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 4980): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 4980): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 4980): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 4980): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 4980): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 4980): Cleaning up Bluetooth PAN callback object
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
I/BluetoothAdapterState( 4980): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 4980): Entering OffState
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3714): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/art     ( 3071): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/PG Utils( 7372): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3071): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3714): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,E/WifiMonitor( 3071): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
E/WifiMonitor( 3071): handleEvent 13  CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
E/WifiMonitor( 3071): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
E/WifiMonitor( 3071): handleEvent 13  CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
,I/HwLauncher( 3889): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3889): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3889): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Choreographer( 3441): Skipped 33 frames!  The application may be doing too much work on its main thread.
,W/View    ( 3441): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{982d206 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during layout: running second layout pass
I/ActivityManager( 3071): filter receiver for action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager( 3071): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/NetworkSpeedManagerEx( 3441): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3441): wifiManager = android.net.wifi.WifiManager@362a1279
,W/wpa_supplicant( 3531): ioctl error:ret = -1
E/wpa_supplicant( 3531): wpa_driver_set_wps_p2p_ie failed ret=-1
,E/WifiStateMachine( 3071):  SupplicantStoppingState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:616238785] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 3071):  DefaultState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:616238785] gl hn u24 rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,I/NetworkSpeedManagerEx( 3441): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3441): stop
I/HwLauncher( 3889): Launcher onStart()
I/HwLauncher( 3889): Launcher dynamicIconsRegister
I/HwLauncher( 3889): DynamicUpdater registerReceiver
,I/InputReader( 3071): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 3071): filter receiver for action = android.bluetooth.adapter.action.STATE_CHANGED
W/GeofencerStateMachine( 4108): Ignoring removeGeofence because network location is disabled.
I/bluedroid( 4980): bt interface: [cleanup]
,W/bt-btif ( 4980): HAL bt_hal_cbacks->thread_evt_cb
I/HwLauncher( 3889): DynamicUpdater call updateFolder
I/HwLauncher( 3889): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3889): DynamicUpdater registerReceiver
I/AccountTypeManager( 7118): Adding account type = com.android.contacts.model.account.ExchangeAccountType@3bff7b38 in the cache
,I/HwLauncher( 3889): DynamicUpdater call updateFolder
I/HwLauncher( 3889): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3889): DynamicUpdater registerReceiver
,I/art     ( 5806): Explicit concurrent mark sweep GC freed 30690(2MB) AllocSpace objects, 10(160KB) LOS objects, 25% free, 13MB/18MB, paused 1.514ms total 57.088ms
,I/HwSystemManager( 5806): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 5806): HsmPackageManager:replacing:false
I/HwSystemManager( 5806): HsmPackageManager:pkgName:com.example.hello
,I/HwLauncher( 3889): DynamicUpdater call updateFolder,
I/HwLauncher( 3889): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/GKI_LINUX( 4980): gki_task task_id=1 [BTIF] terminating
,I/HwLauncher( 3889): Launcher onResume(),
,I/HwLauncher( 3889): Launcher doResumeWork()
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10302,
I/GKI_LINUX( 4980): GKI_exit_task 1 done
I/GKI_LINUX( 4980): GKI_shutdown(): task [BTIF] terminated
,E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/HwLauncher( 3889): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10302, pid: 6787,
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10302, pid: 6787
I/BluetoothServiceJni( 4980): cleanupNative: return from cleanup
,I/BluetoothServiceJni( 4980): OoO sJniCallbacksObj has init before clean? 1
I/HwSystemManager( 3714): HoldService:uid:10302 pid:6787 died
,I/HwSystemManager( 3714): HoldService:oldVersionKey:10302,6787
,I/HwSystemManager( 3714): AppLockService:applock password not initial or function is closed,
I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:0
,I/HwLauncher( 3889): Launcher.MotionManager startMotionAppsReco 402
I/HwLauncher( 3889): Launcher  onResume mIsToUninstallApp = false,
E/RegisteredServicesCache( 3819): invalidateCache set mNeedToastTableFull
I/art     ( 4980): System.exit called, status: 0,
I/AndroidRuntime( 4980): VM exiting with result code 0, cleanup skipped.
,W/PGApi_client( 3777): recv actoionId = 10010, action = com.huawei.pgmng.PGAction@b577065 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1,
,W/PGMiddleWare jhh( 3777): in handleAction method, action = 10010
,W/PGMiddleWare jhh( 3777): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@3ff6bd00, action = com.huawei.pgmng.PGAction@b577065 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3777): jhh handle default mActionId = 10010, action = com.huawei.pgmng.PGAction@b577065 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
,W/AudioEffectLowPowerImpl jhh( 3777): enter into the safetyguard Scene.
W/AudioEffectLowPowerImpl jhh( 3777): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
I/HwSystemManager( 5806): HsmPackageManager:doAppRemoved, remove:com.example.hello,
,W/AudioEffectLowPowerImpl jhh( 3777): mAudioActive = false, mMusicPerceptible = false
,W/AudioEffectLowPowerImpl jhh( 3777): return for smartPAOn and mLowAudioEffectEnable both = false
I/SimFactoryManager( 7118): Get SIM state from SIM factory manager: 1,For slotId:1
I/HwSystemManager( 3714): AppManager:getNetAppInfoFromDB cursor lenth = 1,
,W/ResourceType( 3071): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,I/AccountTypeManager( 7118): Adding account type = com.android.contacts.model.account.ExternalAccountType@28a2b711 in the cache
,W/ResourceType( 7118): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 7118): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 7118): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 7118): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 7118): Adding account type = com.android.contacts.model.account.ExternalAccountType@9355076 in the cache
,I/AccountTypeManager( 7118): Adding account type = com.android.contacts.model.account.GoogleAccountType@1b7b6677 in the cache
,W/System.err( 3071): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 3071): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3071): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 3071): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 3071): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3071): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3071): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ExternalAccountType( 7118): Unsupported attribute readOnly
,I/HwLauncher( 3889): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3889): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,I/AccountTypeManager( 7118): AccountManager, account size is: 2
,I/AccountTypeManager( 7118): Loaded meta-data for 5 account types, 3 accounts in 86ms(wall) 21ms(cpu)
,I/art     ( 3714): Explicit concurrent mark sweep GC freed 94767(6MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 14MB/23MB, paused 3.011ms total 140.680ms
I/HwSystemManager( 3714): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 3714): HsmPackageManager:replacing:false
I/HwSystemManager( 3714): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 3714): HsmPackageManager:doAppRemoved, remove:com.example.hello
I/HwSystemManager( 3714): ww:deleteLockData:com.example.hello
,W/asset   ( 3071): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/wpa_supplicant( 3531): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiMonitor( 3071): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-TERMINATING 
,E/WifiStateMachine( 3071):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 27 0
I/wpa_supplicant( 3531): ELOOP: remaining timeout: -1.904026 eloop_data=0x5595fddfb0 user_data=0x0 handler=0x55867ba6c0
,I/art     ( 3071): Explicit concurrent mark sweep GC freed 15818(1153KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 5.645ms total 216.260ms
,I/HwLauncher( 3889): Launcher  onWindowVisibilityChanged visibility = 0
I/HwLauncher( 3889): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3889): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 1002
,E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
W/MediaProcessHandler( 3071): processOp uid 1002 is not concerned!
,I/HwSystemManager( 3714): HoldService:uid:1002 pid:4980 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:1002,4980
,E/TEST-APN( 3842): query for APN: check-permission succ 
E/TEST-APN( 3842): Telephony query SQL: SELECT type, proxy, port FROM carriers WHERE (numeric = ',' and carrier_enabled = 1)
,I/NetworkSpeedManagerEx( 3441): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3441): wifiManager = android.net.wifi.WifiManager@362a1279
,I/NetworkSpeedManagerEx( 3441): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3441): stop
,W/ContextImpl( 7372): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/HwLauncher( 3889): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3889): Model replacing = false package = com.example.hello
I/HwLauncher( 3889): Model  ACTION_PACKAGE_REMOVED replacing = false
I/HwLauncher( 3889): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
I/HwLauncher( 3889): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
,I/HwLauncher( 3889): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
,I/HwLauncher( 3889): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3889): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3889): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3889): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3889): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,W/asset   ( 7431): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 3071): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,I/art     ( 3071): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
I/art     ( 3071): Can not find class: Lhuawei/com/android/server/util/ReportTool;
I/art     ( 3071): Can not find class: Lcom/huawei/report/ReporterInterface;
E/ReportTools( 3071): Can't find sReporterClazz
I/art     ( 3071): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
I/art     ( 3889): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3071): Can not find class: Lhuawei/com/android/server/util/AppInfo;
I/art     ( 3889): Can not find class: Lhuawei/android/widget/EditText;
W/System.err( 3071): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 3071): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3071): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3071): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 3071): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 3071): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 3071): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 3071): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 3071): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 3071): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 3071): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 3071): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3071): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3071): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3071): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 3071): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 3071): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3071): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3071): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
E/textview( 3889): initAddtionalStyle default
W/System.err( 3071): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 3071): This is not beta user build
I/ActivityManager( 3071): filter receiver for action = android.net.conn.TETHER_STATE_CHANGED
,I/ActivityManager( 3071): filter receiver for action = android.net.wifi.WIFI_STATE_CHANGED
,I/System.out( 3864): Stale Location error
I/SUPL20_SPIMESLP-SENDING( 3864): m_bPacket.length 119
I/SUPL20_SPIMESLP-SENDING( 3864): bBrokenPipe = false
W/Settings( 6116): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/HwSystemManager( 3714): BgPowerManagerService:BgPowerManagerSerivce plugged =2 currentThreshold = 8 mRawLevel = 100mLastRawLevel100
I/HwSystemManager( 3714): BgPowerManagerService: mTimes = 40557 firstTime = 26237 firstmBatteryCapacity =2205
I/HwSystemManager( 3714): aor:Network Stats Updated
I/HwSystemManager( 3714): aoi:onNetworkStatsUpdated
,I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,W/Settings( 4108): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PG Utils( 3889): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 7431): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,I/HwCust  ( 7431): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,W/ContextImpl( 7372): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
,I/HwLauncher( 3889): Model mAllAppsList.removePackage com.example.hello
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
W/ContextImpl( 7372): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/HwSystemManager( 3714): TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,I/NetworkSpeedManagerEx( 3441): receive:android.net.wifi.STATE_CHANGE
I/NetworkSpeedManagerEx( 3441): wifiManager = android.net.wifi.WifiManager@362a1279
,I/NetworkSpeedManagerEx( 3441): mIsNetworkSpeedEnabled = false, mIsAirplaneMode = true, mIsWifiConnected = false, mIsHasIccCard = false, mIsDataSwitchEnabled = true
I/NetworkSpeedManagerEx( 3441): stop
,W/MotionDetectionManager( 3889): startMotionAppsReco motionApps: 402 disabled
W/HwLauncher( 3889): Launcher.MotionManager startMotionAppsReco service flg 402 is unavailable
E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3714): TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
I/HwSystemManager( 3714): TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
,E/HwSystemManager( 3714): getSimCardType:/getSimCardInfo: imsi is null
E/HwSystemManager( 3714): getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
W/HwSystemManager( 3714): TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,E/HwSystemManager( 3714): TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,W/View    ( 3441): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{982d206 V.E..... ........ 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/PhoneStatusBar( 3441): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/WifiTracker( 3441): STATE =0
,I/art     ( 7372): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
W/System  ( 7372): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cb60284: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7372): Installed default security provider GmsCore_OpenSSL
,I/WifiTracker( 3441): STATE =0
,I/HwLauncher( 3889): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,E/HideAppsPagedView( 3889): removeItems begin 
E/HideAppsPagedView( 3889): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3889): removeItems end 
I/WifiTracker( 3441): STATE =0
I/HwLauncher( 3889): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3889):  stringArray[] [unknown]
,E/WifiStateMachine( 3071): could not open wifi state sys nodejava.io.FileNotFoundException: /sys/devices/platform/bcmdhd_wlan.1/wifi_open_state: open failed: ENOENT (No such file or directory)
,E/WifiStateMachine( 3071):  InitialState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 3071):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
,I/HwLauncher( 3889): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
,I/ConfigStore( 7372): Config Database version: 1
,W/System.err( 3889): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 3889): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3889): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3889): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3889): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3889): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3889): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3889): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3889): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3889): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3889): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3889): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
W/System.err( 3889): java.lang.NullPointerException: null receiver
W/System.err( 3889): 	at java.lang.reflect.Field.get(Native Method)
W/System.err( 3889): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3889): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3889): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3889): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3889): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3889): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3889): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3889): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3889): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3889): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3889): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwLauncher( 3889): CellLayout rearrangeAfterRmItem isAutoAlign = false
,I/PhoneStatusBar( 3441): shouldTranslucent:true
,I/PhoneStatusBar( 3441): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,W/View    ( 3441): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{982d206 V.E..... ......I. 0,0-72,50 #7f0d0086 app:id/notificationIcons} during second layout pass: posting in next frame
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10052
,I/HwSystemManager( 3714): HoldService:uid:10052 pid:7051 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10052,7051
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10052, pid: 7051
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10052, pid: 7051
,I/WifiTracker( 3441): STATE =0
,I/WifiTracker( 3441): STATE =0
,I/WifiTracker( 3441): STATE =0
,E/HideAppsPagedView( 3889): removeHideApps  begin 
E/HideAppsPagedView( 3889): removeHideApps  end 
E/HideAppsPagedView( 3889):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3889):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3889):  createAddIcon count = 0
,I/HwLauncher( 3889):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,E/SharedPreferencesImpl( 6041): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,I/MediaRouter( 7372): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=6, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,E/SharedPreferencesImpl( 6041): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
I/HwEmailTag( 6497): EmailProvider->query->1448020218179;end;;consuming:1ms;
I/HwEmailTag( 6497): EmailProvider->query->1448020218182;end;;consuming:2ms;
I/PG Utils( 3071): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/Icing   ( 6041): Internal init done: storage state 0
I/PG Utils( 6041): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 7372): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Icing   ( 6041): Post-init done
,E/SharedPreferencesImpl( 7372): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
,E/Icing   ( 6041): Package com.example.hello not found
,E/Icing   ( 6041): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,I/GHttpClientFactory( 7372): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7372): Using platform SSLCertificateSocketFactory
,W/OpenGLRenderer( 3889): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 3889): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,E/hwcomposer( 2295): setTopResource:1220: set top resource failed!! ret:-1 
E/hwcomposer( 2295): comp_mode= 0
E/hwcomposer( 2295): disp_ch_res = 0x0 
E/hwcomposer( 2295): res_info.ovly1_res = 0x0 
E/hwcomposer( 2295): res_info.ovly2_res = 0x205 
E/hwcomposer( 2295): res_info.ovly3_res = 0x46
E/hwcomposer( 2295): res_info.rot_res = 0x0
E/hwcomposer( 2295): res_info.scl2_res = 0x21
E/hwcomposer( 2295): res_info.compose_ch_res[0] = 0x408
E/hwcomposer( 2295): res_info.compose_ch_res[1] = 0x409
E/hwcomposer( 2295): res_info.compose_ch_res[2] = 0x40a
E/hwcomposer( 2295): res_info.compose_ch_res[3] = 0x80b
E/hwcomposer( 2295): res_info.compose_ch_res[4] = 0x52c
E/hwcomposer( 2295): res_info.compose_ch_res[5] = 0x4ad
E/hwcomposer( 2295): ade_reg_res = 0x0
E/hwcomposer( 2295): setGlobal:234: setTopResource fail!! 
E/hwcomposer( 2295): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2295): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2295): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2295): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2295): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(37)
E/hwcomposer( 2295): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2295): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2295): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2295): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2295): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2295): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2295): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2295): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2295): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(26)
E/hwcomposer( 2295): phy_addr(0x26aa000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2295): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2295): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2295): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2295): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2295): compose_mode(0), 	 ch_index(2)
E/hwcomposer( 2295): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2295): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2295): format(5),  	 height(50),  	 width(720),  	 rotation(0), 	 sharefd(56)
E/hwcomposer( 2295): phy_addr(0x315a000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2295): stride(2880),  	 dst_height(50),  	 dst_width(720)
E/hwcomposer( 2295): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2295): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2295): commit:654: commit failed!! ret:-1, frame_number:492, 
E/hwcomposer( 2295): is_finished  (0), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2295): dst_rotation (0), 	 dst_rect xywh (0,0,720,50), 	 src_rect xywh (0,0,720,50) 
E/hwcomposer( 2295): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2295): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2295): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2295): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2295): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2295): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2295): finishOneArea:142: finishOneArea commit error
E/hwcomposer( 2295): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2295): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2295): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2295): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2295): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(37)
E/hwcomposer( 2295): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovl,y_surf_num(0)
E/hwcomposer( 2295): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2295): src_rect xywh(0,50,720,1134),  	 dst_rect xywh(0,50,720,1134)
E/hwcomposer( 2295): ovly_output_rect xywh(0,50,720,1134),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2295): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2295): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2295): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2295): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2295): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(26)
E/hwcomposer( 2295): phy_addr(0x26aa000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2295): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2295): src_rect xywh(0,50,720,1134),  	 dst_rect xywh(0,50,720,1134)
E/hwcomposer( 2295): ovly_output_rect xywh(0,50,720,1134),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2295): commit:654: commit failed!! ret:-1, frame_number:492, 
E/hwcomposer( 2295): is_finished  (0), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2295): dst_rotation (0), 	 dst_rect xywh (0,50,720,1134), 	 src_rect xywh (0,50,720,1134) 
E/hwcomposer( 2295): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2295): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2295): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2295): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2295): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2295): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2295): finishOneArea:142: finishOneArea commit error
E/hwcomposer( 2295): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2295): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2295): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2295): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2295): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(37)
E/hwcomposer( 2295): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2295): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2295): src_rect xywh(0,1184,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2295): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2295): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2295): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2295): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2295): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2295): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(26)
E/hwcomposer( 2295): phy_addr(0x26aa000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2295): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2295): src_rect xywh(0,1184,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2295): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2295): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2295): compose_mode(0), 	 ch_index(2)
E/hwcomposer( 2295): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2295): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2295): format(5),  	 height(96),  	 width(720),  	 rotation(0), 	 sharefd(64)
E/hwcomposer( 2295): phy_addr(0x31e6000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2295): stride(2880),  	 dst_height(96),  	 dst_width(720)
E/hwcomposer( 2295): src_rect xywh(0,0,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2295): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2295): commit:654: commit failed!! ret:-1, frame_number:493, 
E/hwcomposer( 2295): is_finished  (1), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2295): dst_rotation (0), 	 dst_rect xywh (0,1184,720,96), 	 src_rect xywh (0,1184,720,96) 
E/hw,composer( 2295): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2295): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2295): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2295): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2295): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2295): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2295): play:197: play commit error
E/hwcomposer( 2295): enableVsync:1073: vsync ioctl failed 
E/hwcomposer( 2295): EventControl:120: vsync ioctl failed
E/SurfaceFlinger( 2295): eventControl(0, 1) failed Operation not permitted
,I/HwSystemManager( 3714): BgPowerManagerService:onProcessDied uid = 10060
I/HwSystemManager( 3714): HoldService:uid:10060 pid:6638 died
I/HwSystemManager( 3714): HoldService:oldVersionKey:10060,6638
E/HsmCoreServiceImpl( 3071): onTransact in code is: 102
I/MediaProcessHandler( 3071): processOp opType: 1, uid: 10060, pid: 6638
W/MediaProcessHandler( 3071): remove target not exist, maybe the UI process: uid: 10060, pid: 6638

```
