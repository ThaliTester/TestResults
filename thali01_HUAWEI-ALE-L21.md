#### Test 502422852e23b2c_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/SUPL20_SCMService( 3721): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3721): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3721): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3721): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3721): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3721): network type:0 ,UNKNOWN
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10004
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10004, pid: 3774
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10004, pid: 3774
I/HwSystemManager( 3974): HoldService:uid:10004 pid:3774 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10004,3774
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10059
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10059, pid: 5338
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10059, pid: 5338
I/HwSystemManager( 3974): HoldService:uid:10059 pid:5338 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10059,5338
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3974): HoldService:uid:1000 pid:5316 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:1000,5316
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
W/MediaProcessHandler( 2983): processOp uid 1000 is not concerned!
I/PG Utils( 5763): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5763): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 5763): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5763): Installed default security provider GmsCore_OpenSSL
W/System.err( 2983): java.lang.SecurityException: WifiService: Neither user 10087 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2983): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2983): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2983): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2983): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2983): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2983): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2983): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 5763): WifiServiceMessenger == null
I/dex2oat ( 5797): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=default --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads119103114.jar --oat-fd=33 --oat-location=/data/data/com.google.android.youtube/cache/ads119103114.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/appproc ( 5789): CLASSPATH=/system/framework/am.jar
I/appproc ( 5789): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 5789): app_process:number,5,0
I/AndroidRuntime( 5789): readDownloadBoosterConfig: 'false'
I/dex2oat ( 5797): dex2oat took 35.456ms (threads: 8)
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/e;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/l;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/i;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/g;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/m;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/f;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/k;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/j;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/d;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/c;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/b;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/h;
I/art     ( 5763): Can not find class: Lcom/google/android/ads/zxxz/a;
I/art     ( 2983): Explicit concurrent mark sweep GC freed 15142(789KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.797ms total 171.488ms
I/HwSystemManager( 5580): HsmStat_info:service connect
I/        ( 5789): power log dlsym ok
E/YouTube MDX( 5763): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
E/android_hardware_fm.cpp( 5789): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 5789): ========64bit long size = 8
E/FM_HAL  ( 5789): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 5789): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 5789): 
I/fm_hisi ( 5789): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 5789): 
I/fm_hisi ( 5789): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 5789): 
E/android_hardware_fm.cpp( 5789): register_android_hardware_fm_fmradio, ret is 0
I/MultiDex( 5827): VM with version 2.1.0 has multidex support
I/MultiDex( 5827): install
I/MultiDex( 5827): MultiDexExtractor.load(/data/app/com.google.android.gms-2/base.apk, false)
W/ContextImpl( 5763): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
I/MultiDex( 5827): loading existing secondary dex files
I/MultiDex( 5827): load found 3 secondary dex files
I/MultiDex( 5827): install done
I/art     ( 2983): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2983): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2983): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2983): Can not find class: Lcom/android/server/wm/StartingData;
I/HwLauncher( 3746): Launcher onPause()
I/HwLauncher( 3746): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3746): Launcher.MotionManager stopMotionAppsReco 403
I/art     ( 2983): Can not find class: Landroid/widget/ViewStub;
I/art     ( 2983): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 2983): Can not find class: Landroid/app/ViewStub;
W/HwLauncher( 3746): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
I/System  ( 5763): core_booster, getBoosterConfig = false
W/HwLauncher( 3746): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
I/art     ( 3746): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3746): Can not find class: Lhuawei/android/widget/EditText;
E/textview( 3746): initAddtionalStyle default
I/art     ( 2983): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/PhoneStatusBar( 3219): shouldTranslucent:true
I/PhoneStatusBar( 3219): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwSystemManager( 3974): AppLockService:applock password not initial or function is closed
W/PGApi_client( 3620): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@13379ec2 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3620): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3620): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@3ae97347, action = com.huawei.pgmng.PGAction@13379ec2 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3620): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@13379ec2 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3620): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3620): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
I/HwLauncher( 3746): Launcher onStop()
I/HwSystemManager( 3974): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3746): Launcher dismissDialog
I/HwLauncher( 3746): Launcher dynamicIconsUnregister
I/HwLauncher( 3746): DynamicUpdater unregisterReceiver
I/HwLauncher( 3746): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3746): DynamicUpdater unregisterReceiver
I/HwLauncher( 3746): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3746): DynamicUpdater unregisterReceiver
W/AudioEffectLowPowerImpl jhh( 3620): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3620): return for smartPAOn and mLowAudioEffectEnable both = false
I/HwLauncher( 3746): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3746): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3746): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3746): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3746): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3746): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/ContextImpl( 5763): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
W/ContextImpl( 5763): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
W/ContextImpl( 5763): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 5763): Found 10007
I/WebViewFactory( 5868): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/LibraryLoader( 5868): Loading: webviewchromium
I/LibraryLoader( 5868): Time to load native libraries: 3 ms (timestamps 9253-9256)
I/LibraryLoader( 5868): Expected native library version number "",actual native library version number ""
I/art     ( 5827): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
W/System  ( 5827): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1df146: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5827): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.INITIALIZE
I/LibraryLoader( 5868): Expected native library version number "",actual native library version number ""
I/chromium( 5868): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
W/ContextImpl( 5763): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
I/BrowserStartupController( 5868): Initializing chromium process, renderers=0
W/art     ( 5868): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5868): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
W/chromium( 5868): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5868): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 5868): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/chromium( 5868): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5868): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/SUPL20_PCM( 3721): calling nc.connect for pcm
I/SUPL20_NC( 3721): Calling getLocalSocket for PCM
I/SUPL20_NC( 3721): deque initialized
I/SUPL20_NC( 3721): WriterThread initialize
I/SUPL20_NC( 3721): readerThread initialized
W/chromium( 5868): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/SUPL20_PCM( 3721): process icmdID: 0X101
I/SUPL20_PCM( 3721): process hello msg
I/SUPL20_PCM( 3721): init msg success
I/SUPL20_PCM( 3721): sendHelloMessage
I/SUPL20_PCM( 3721): process: process less then zero 0
I/SUPL20_LocMan( 3721): register the Emergency Receiver 
I/SUPL20_PCM( 3721): process icmdID: 0X103
I/SUPL20_PCM( 3721):  process MSG_PCM_GET_LOCATION_ID
I/SUPL20_PCM( 3721): process icmdID: 0X11a
I/SUPL20_PCM( 3721):  process MSG_PCM_GET_HIST_KEY
I/SUPL20_SCM( 3721): calling nc.connect for scm
I/SUPL20_NC( 3721): Calling getLocalSocket for SCM
I/SUPL20_NC( 3721): deque initialized
I/SUPL20_NC( 3721): WriterThread initialize
I/SUPL20_NC( 3721): readerThread initialized
I/SUPL20_SPIMESLP-SENDING( 3721): m_bPacket.length 12
I/SUPL20_SPIMESLP-SENDING( 3721): bBrokenPipe = false
I/SUPL20_SCM( 3721): buffer size:12writePosition: 12
I/SUPL20_SCM( 3721): process icmdID2: 0X201
I/SUPL20_SCM( 3721): process hello msg
I/SUPL20_SCM( 3721): init msg success
I/SUPL20_SPIMESLP-SENDING( 3721): m_bPacket.length 12
I/SUPL20_SPIMESLP-SENDING( 3721): bBrokenPipe = false
I/SUPL20_SCM( 3721): sendHelloMessage
I/SUPL20_LocMan( 3721): SIM state :1
I/SUPL20_LocMan( 3721): Registered MyPhoneStateListener
W/PhoneInterfaceManager( 3695): shouldBlockLocation running ...
I/PhoneInterfaceManager( 3695): shouldBlockLocation  ret:false
E/SUPL20_LocMan( 3721): tm.getCellLocation() returned null
I/SUPL20_LocMan( 3721):  sim is not enabled on the SET
I/SUPL20_LocMan( 3721): onServiceStateChanged ServiceState.STATE_POWER_OFF
E/PhoneInterfaceManager( 3695): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/SUPL20_LocMan( 3721): Phone type:GSM
I/SUPL20_LocMan( 3721): NULL Value received for network operator
I/SUPL20_LocMan( 3721):  cellInfo NetworkType:UNKNOWN,0
I/SUPL20_LocMan( 3721): onDataConnectionStateChanged networkType = 0
I/SUPL20_LocMan( 3721): onDataConnectionStateChanged state = -1
I/SUPL20_SPIMESLP-SENDING( 3721): m_bPacket.length 40
I/SUPL20_SPIMESLP-SENDING( 3721): bBrokenPipe = false
I/SUPL20_PCM( 3721): Fetching the historic secret key ...
I/SUPL20_PCM( 3721): process: process less then zero 0
I/SUPL20_SPIMESLP-SENDING( 3721): m_bPacket.length 24
I/SUPL20_SPIMESLP-SENDING( 3721): bBrokenPipe = false
W/art     ( 5868): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5868): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 5868): Can not find class: Landroid/widget/ViewStub;
I/art     ( 5868): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 5868): Can not find class: Landroid/app/ViewStub;
W/PhoneInterfaceManager( 3695): shouldBlockLocation running ...
I/PhoneInterfaceManager( 3695): shouldBlockLocation  ret:false
E/SUPL20_LocMan( 3721): tm.getCellLocation() returned null
I/SUPL20_LocMan( 3721): onDataConnectionStateChanged Unknown: -1
W/PhoneInterfaceManager( 3695): shouldBlockLocation running ...
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10052
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10052, pid: 5389
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10052, pid: 5389
I/HwSystemManager( 3974): HoldService:uid:10052 pid:5389 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10052,5389
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10047
I/HwSystemManager( 3974): HoldService:uid:10047 pid:5365 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10047,5365
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10047, pid: 5365
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10047, pid: 5365
I/PhoneInterfaceManager( 3695): shouldBlockLocation  ret:false
E/SUPL20_LocMan( 3721): tm.getCellLocation() returned null
I/ActivityManager( 2983): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
W/art     ( 5868): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5868): Attempt to remove local handle scope entry from IRT, ignoring
I/PG Utils( 5964): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/ActivityManager( 2983): filter receiver for action = com.google.android.gm.intent.ACTION_PROVIDER_CREATED
I/Gmail   ( 5964): getAccountsCursor
I/art     ( 2983): Can not find class: Lcom/android/server/accounts/AccountManagerService$GetAccountsByTypeAndFeatureSession;
I/art     ( 2983): Can not find class: Lcom/android/server/accounts/AccountManagerService$Session;
I/art     ( 5964): Can not find class: Lcom/google/ads/AdRequest;
W/GAV2    ( 5964): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/OpenGLRenderer( 5868): Initialized EGL, version 1.4
,I/Gmail   ( 5964): Observing account changes for notifications
,I/ActivityManager( 2983): Displayed com.example.hello/.MainActivity: +1s82ms
,I/art     ( 2983): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
,I/Gmail   ( 5964): getAccountsCursor
,E/Gmail   ( 5964): Error finding the version of the Email provider.....
E/Gmail   ( 5964): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5964): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:120)
E/Gmail   ( 5964): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5964): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5964): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5964): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5964): We do not support migrating this version of the Email provider.
,I/art     ( 2983): Can not find class: Lcom/android/server/wm/DisplayContentList;
,I/chromium( 5868): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5868): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/SQLiteLog( 5964): (283) recovered 26 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/SystemBroadcastReceiver( 6023): Boot has been completed
I/SystemBroadcastReceiver( 6023): toggleAppIcon() : FLAG_SYSTEM = true
,I/SystemBroadcastReceiver( 6023): Killing my process: pid=6023
I/Process ( 6023): Sending signal. PID: 6023 SIG: 9
,I/PG Utils( 5964): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 5964): notifyAccountChanged
,I/AlarmInitReceiver( 5429): handleMessage : AlarmInitReceiver, will exit app. Config.exit_count: 0
,I/Gmail   ( 5964): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5964): getAccountsCursor
I/art     ( 5429): System.exit called, status: 0
I/AndroidRuntime( 5429): VM exiting with result code 0, cleanup skipped.
,E/lowmemorykiller( 2289): Error writing /proc/5429/oom_score_adj; errno=22
,I/Gmail   ( 5964): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/chromium( 5868): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5868): 
,I/Gmail   ( 5964): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5964): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10077
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10077, pid: 6023
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10077, pid: 6023
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10045
I/HwSystemManager( 3974): HoldService:uid:10077 pid:6023 died
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/HwSystemManager( 3974): HoldService:oldVersionKey:10077,6023
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10045, pid: 5429
I/HwSystemManager( 3974): HoldService:uid:10045 pid:5429 died
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10045, pid: 5429
I/HwSystemManager( 3974): HoldService:oldVersionKey:10045,5429
,W/jxcore-log( 5868): Initializing JXcore engine
W/jxcore-log( 5868): JXcore engine is ready
,W/jxcore-log( 5868): Starting JXcore engine
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 213us total 24.404ms
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 224us total 41.765ms
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 249us total 24.251ms
,I/PG Utils( 5827): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5827): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5827): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/iu.UploadsManager( 5827): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/PG Utils( 5827): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5827): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5964): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/jxcore-log( 5868): Platform android
W/jxcore-log( 5868): 
,W/jxcore-log( 5868): Process ARCH arm
W/jxcore-log( 5868): 
,E/Fabric  ( 6056): Unknown error while loading Crashlytics settings. Crashes will be cached until settings can be retrieved.
,I/jxcore-log( 5868): JXcore Cordova bridge is ready!
I/jxcore-log( 5868): 
,W/jxcore-log( 5868): JXcore engine is started
,E/WearSyncService( 6056): Failed to connect to GoogleApiClient within the timeout
,E/jxcore-log( 5868): >> HUAWEI-ALE-L21
E/jxcore-log( 5868): 
,I/jxcore-log( 5868): Total memory 1949741056
I/jxcore-log( 5868): 
,I/jxcore-log( 5868): Free memory 17756160
I/jxcore-log( 5868): 
I/jxcore-log( 5868): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5868): 
I/jxcore-log( 5868): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5868): 
,I/jxcore-log( 5868): userPath [ 'www' ]
I/jxcore-log( 5868): 
,I/jxcore-log( 5868): Size 720 1184
I/jxcore-log( 5868): 
,I/jxcore-log( 5868): Screen Brightness 242
I/jxcore-log( 5868): 
,E/jxcore-log( 5868): Dummy Error Log.
E/jxcore-log( 5868): 
,I/art     ( 2983): Explicit concurrent mark sweep GC freed 16254(832KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.006ms total 213.866ms
,I/Gmail   ( 5964): getAccountsCursor
,I/PG Utils( 5827): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5827): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5827): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/iu.UploadsManager( 5827): End new media; added: 0, uploading: 0, time: 365 ms
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6121): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Babel_SMS( 6121): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6121): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6121): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
I/Babel_SMS( 6121): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6121): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6121): MmsConfig.loadFromResources
,E/Babel_SMS( 6121): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6121): MmsConfig.loadMmsSettings: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
,I/CameraHalInterface( 2626): Found a matching camera info for ID 0
,I/CameraHalInterface( 2626): Found a matching camera info for ID 1
,W/Settings( 6121): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/System.err( 2983): java.lang.SecurityException: WifiService: Neither user 10058 nor current process has android.permission.CHANGE_WIFI_STATE.
,W/System.err( 2983): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2983): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2983): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2983): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2983): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2983): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2983): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiManager( 6121): WifiServiceMessenger == null
,I/Babel_Crash( 6121): startup - clean
,I/Babel   ( 6121): deleted: false for 0
,I/jxcore-log( 5868): getBuffer is called!!!!
I/jxcore-log( 5868): 
,W/VideoCapabilities( 6121): Unsupported mime video/mpeg
,W/VideoCapabilities( 6121): Unsupported mime video/mpeg2
,W/VideoCapabilities( 6121): Unrecognized profile 32768 for video/3gpp
,W/VideoCapabilities( 6121): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6121): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6121): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6121): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6121): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6121): Unrecognized profile 32768 for video/3gpp
,W/VideoCapabilities( 6121): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6121): Unrecognized profile/level 0/0 for video/3gpp
W/VideoCapabilities( 6121): Unrecognized profile 0 for video/3gpp
,W/VideoCapabilities( 6121): Unsupported mime video/mp4
,I/VideoCapabilities( 6121): Unsupported profile 8 for video/mp4v-es
,I/VideoCapabilities( 6121): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6121): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6121): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6121): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6121): Unsupported profile 8 for video/mp4v-es
,I/VideoCapabilities( 6121): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6121): Unsupported profile 8 for video/mp4v-es
W/VideoCapabilities( 6121): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 6121): Unrecognized profile 0 for video/mp4v-es
,W/VideoCapabilities( 6121): Unsupported mime video/mpeg4
,W/VideoCapabilities( 6121): Unsupported mime video/x-flv
,W/VideoCapabilities( 6121): Unsupported mime video/vc1
,W/VideoCapabilities( 6121): Unsupported mime video/wvc1
,W/VideoCapabilities( 6121): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6121): Unsupported mime video/x-ms-wmv3
,W/VideoCapabilities( 6121): Unsupported mime video/x-pn-realvideo
,W/VideoCapabilities( 6121): Unsupported mime video/ffmpeg
,W/AudioCapabilities( 6121): Unsupported mime audio/ffmpeg
,I/VideoCapabilities( 6121): Unsupported profile 4 for video/mp4v-es
,I/vclib   ( 6121): onServiceConnected
,W/Babel   ( 6121): Attempted to change video mute state without an active call.
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10040
I/HwSystemManager( 3974): HoldService:uid:10040 pid:5460 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10040,5460
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10040, pid: 5460
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10040, pid: 5460
,I/art     ( 2983): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/PG Utils( 6156): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/System.err( 2983): java.lang.SecurityException: WifiService: Neither user 10025 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2983): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2983): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2983): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2983): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2983): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2983): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2983): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 6156): WifiServiceMessenger == null
,W/Settings( 6156): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6156): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PG Utils( 6156): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6156): acquire_providerpkg:[com.android.providers.downloads] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10032
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/HwSystemManager( 3974): HoldService:uid:10032 pid:5257 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10032,5257
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10032, pid: 5257
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10032, pid: 5257
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.partnersetup] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6235): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/VelvetNetworkClient( 6201): Network connection not availble
,I/art     ( 5827): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 3974): HoldService:uid:10050 pid:5494 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10050,5494
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10050, pid: 5494
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10050, pid: 5494
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/InstanceID/Rpc( 5827): Found 10007
,I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/WebViewFactory( 6201): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 6201): Loading: webviewchromium
,I/LibraryLoader( 6201): Time to load native libraries: 5 ms (timestamps 3198-3203)
I/LibraryLoader( 6201): Expected native library version number "",actual native library version number ""
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/art     ( 6201): Attempt to remove local handle scope entry from IRT, ignoring
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/CheckinService( 5827): Checkin interval check for package: unspecified last checkin: 1449217171307 min interval config: 0 actual interval: 280103381
,I/CheckinService( 5827): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 5827): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 3583): DispatchingService.onCreate()
,I/CheckinService( 5827): Checking schedule, now: 1449497274741 next: 1449807432251
I/CheckinService( 5827): active receiver: disabled
,W/art     ( 6201): Attempt to remove local handle scope entry from IRT, ignoring
,I/SystemUpdateService( 5827): cancelUpdate (empty URL)
I/SystemUpdateService( 5827): active receiver: disabled
,I/art     ( 5827): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,I/art     ( 5827): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 5827): Can not find class: Lcom/google/android/gms/common/h/c;
I/art     ( 5827): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.security.snet.BOOT_COMPLETED
,I/ActivityManager( 2983): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3861): Explicit concurrent mark sweep GC freed 8163(497KB) AllocSpace objects, 3(60KB) LOS objects, 40% free, 17MB/29MB, paused 1.155ms total 99.605ms
,I/art     ( 3583): Explicit concurrent mark sweep GC freed 26300(1612KB) AllocSpace objects, 6(120KB) LOS objects, 40% free, 17MB/29MB, paused 1.037ms total 96.445ms
,I/GCoreUlr( 3583): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5827): Explicit concurrent mark sweep GC freed 44699(3MB) AllocSpace objects, 33(660KB) LOS objects, 40% free, 17MB/29MB, paused 2.990ms total 114.906ms
,I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2983): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/GCoreUlr( 3583): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 3583): Unbound from all location providers
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/AuthZen ( 5827): Fetching signing key...
,I/GCoreUlr( 3583): DispatchingService.onDestroy()
I/GCoreUlr( 3583): Stopping handler for UlrDispSvcFast
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/GCoreFlp( 3583): No location to return for getLastLocation()
,W/FusedLocationProvider( 5827): location=null
,I/AuthZen ( 5827): Signing key fetched successfully!
,W/Kids    ( 5827): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 5827): [KidAccountFixer] No network connection
,W/GCoreFlp( 3583): No location to return for getLastLocation()
W/FusedLocationProvider( 5827): location=null
,W/Auth    ( 3861): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6325): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl
,I/PG Utils( 6325): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6325): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6325): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6325): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
,I/HwCust  ( 6325): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
,I/PG Utils( 6325): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6325): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
,E/ContactsProtector( 6325): getHiCloudAccountData query fail
I/PG Utils( 6325): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3555): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
I/art     ( 2983): Explicit concurrent mark sweep GC freed 17702(963KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 27MB/41MB, paused 2.127ms total 238.967ms
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GCoreUlr( 3583): Unbound from all location providers
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6325): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/StubController( 6364): calendar access!
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10104
I/HwSystemManager( 3974): HoldService:uid:10104 pid:5043 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10104,5043
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10104, pid: 5043
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10104, pid: 5043
,I/HwCust  ( 6325): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
,I/HwSystemManager( 3974): ContactsObserverHelper:Receive contacts change broadcast
,I/PG Utils( 6364): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,E/        ( 2983): open /proc/5043/smaps fail errno 2
E/        ( 2983): open /proc/5257/smaps fail errno 2
E/        ( 2983): open /proc/5429/smaps fail errno 2
E/        ( 2983): open /proc/5460/smaps fail errno 2
,E/        ( 2983): open /proc/5494/smaps fail errno 2
,W/StubController( 6386): calendar access!
,W/StubController( 6364): calendar access!
,I/PG Utils( 6364): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 6364): calendar access!
,I/CalendarSimpleUiPRovider( 6364): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6364): onConfigurationChanged
,W/StubController( 6364): calendar access!
,I/CalendarSimpleUiPRovider( 6364): initParams20151207T150755Europe/Warsaw(1,340,3600,0,1449497275)
,W/StubController( 6364): calendar access!
,W/StubController( 6364): calendar access!
,E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
W/MediaProcessHandler( 2983): processOp uid 1000 is not concerned!
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3974): HoldService:uid:1000 pid:5518 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:1000,5518
,I/ActivityManager( 2983): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/CalendarSimpleUiPRovider( 6364): loadEvent end update UI0
,I/HwLauncher( 3746): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwLauncher( 3746): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwLauncher( 3746): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3746): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3746): Model STK reName intent is received.
I/HwLauncher( 3746): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3746): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
I/HwLauncher( 3746): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3746): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3746): Model STK reName intent is received.
,I/HwLauncher( 3746): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3746): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3746): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3746): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3746): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3746): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3746): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3746): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3746): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3746): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3746): Launcher.Folder childCount: 5
I/HwLauncher( 3746): Launcher.Folder childCount: 5
I/HwLauncher( 3746): Launcher.Folder childCount: 7
I/HwLauncher( 3746): Launcher.Folder childCount: 7
I/HwLauncher( 3746): Launcher.Folder childCount: 6
I/HwLauncher( 3746): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3746): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3746): Launcher.Folder childCount: 6
I/HwLauncher( 3746): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3746): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3746): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3746): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3746): Launcher.Folder childCount: 7
I/HwLauncher( 3746): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3746):  syncPages mCurrentPage = 0
,I/HwLauncher( 3746): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
E/HideAppsPagedView( 3746):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3746):  createAddIcon count = 0
I/HwLauncher( 3746): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3746): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3746):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/HwLauncher( 3746): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3746): Model shortcutInfo.title = SIM Toolkit
,I/HwLauncher( 3746): Launcher Deferring update until onResume
,I/HwLauncher( 3746): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3746): Launcher.Folder childCount: 5
I/HwLauncher( 3746): Launcher.Folder childCount: 5
I/HwLauncher( 3746): Launcher.Folder childCount: 7
I/HwLauncher( 3746): Launcher.Folder childCount: 7
,I/HwLauncher( 3746): Launcher.Folder childCount: 6
I/HwLauncher( 3746): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwEmailTag( 6419): MailAppProvider->onCreate->begin, consuming 1449497276325ms->-prefixstartupperformance-
I/HwLauncher( 3746): Launcher.Folder childCount: 6
I/HwLauncher( 3746): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3746): Launcher.Folder childCount: 7
,I/HwLauncher( 3746): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3746):  syncPages mCurrentPage = 0
,I/GAV2    ( 5964): Thread[GAThread,5,main]: No campaign data found.
,I/PG Utils( 5827): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GAv4-SVC( 5827): Google Analytics 8.3.01 is starting up.
E/HideAppsPagedView( 3746):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3746):  createAddIcon count = 0
,I/HwLauncher( 3746):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3746): Launcher Deferring update until onResume
,I/HwEmailTag( 6419): MailAppProvider->onCreate->end, consuming 1449497276361ms->-prefixstartupperformance-
,I/HwCust  ( 6419): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 6419): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 6419): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwCust  ( 6419): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/HwEmailTag( 6419): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6419): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6419): HwUtils->initStaticVarsAsync
I/HwEmailTag( 6419): HwUtils->initStaticVarsAsync
,I/HwCust  ( 6419): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 6419): EmailContent->init->consuming:24ms->;-prefixstartupperformance-
,I/HwEmailTag( 6419): EmailProvider->sURIMatcher is initialized
I/HwEmailTag( 6419): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 6419): EmailProvider->onCreate->end, consuming 42ms->-prefixstartupperformance-
,I/HwEmailTag( 6419): EmailProvider->onCreate->end, consuming 42ms->-prefixstartupperformance-
,I/HwCust  ( 6419): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 6419): EmailProvider->resetVisibleLimits->start:1449497276435 ->-prefixstartupperformance-
,I/HwEmailTag( 6419): EmailProvider->resetVisibleLimits->start:1449497276436 ->-prefixstartupperformance-
,I/HwEmailTag( 6419): HwUtils->initStaticVarsAsync->run:consuming:44ms; bidiFormatter:android.support.v4.text.BidiFormatter@129358dc;accountsProjSize:42
I/HwEmailTag( 6419): HwUtils->initStaticVarsAsync->run:consuming:45ms; bidiFormatter:android.support.v4.text.BidiFormatter@129358dc;accountsProjSize:42
,I/HwEmailTag( 6419): EmailApplication->onCreate->begin, consuming 58ms->-prefixstartupperformance-
,I/HwEmailTag( 6419): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/HwCust  ( 6419): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwCust  ( 6419): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
I/HwEmailTag( 6419): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6419): EmailApplication->onCreate->end, consuming 63ms->-prefixstartupperformance-
,I/HwEmailTag( 6419): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 6419): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 25ms.
,I/HwEmailTag( 6419): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6419): EmailProvider->initBuildCache->start->1449497276501->-prefixstartupperformance-
,I/HwEmailTag( 6419): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 6419): EmailProvider->initBuildCache->start->1449497276501; consuming:1->-prefixstartupperformance-
,I/HwEmailTag( 6419): EmailProvider->resetVisibleLimits->getDatabase, consuming:68ms;-prefixstartupperformance-
I/HwEmailTag( 6419): EmailProvider->uiAccounts->start:1449497276503
I/HwEmailTag( 6419): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 6419): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6419): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 13ms.
,I/HwEmailTag( 6419): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6419): EmailProvider->resetVisibleLimits->getDatabase, consuming:104ms;-prefixstartupperformance-
I/HwEmailTag( 6419): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 6419): EmailProvider->uiAccounts->start:1449497276503;end,consuming:41
I/HwEmailTag( 6419): EmailProvider->query->1449497276434;end;;consuming:110ms;
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10001
I/HwSystemManager( 3974): HoldService:uid:10001 pid:4846 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10001,4846
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10001, pid: 4846
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10001, pid: 4846
,I/ActivityManager( 2983): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2983): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwCust  ( 6457): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
,W/HWContacts( 6457): ProviderFeatureChcker - cootek package not installed
,E/TmoMonitor( 6457): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@1227a94f
,I/HwCust  ( 6457): Constructor found for class com.android.mms.data.HwCustConversationImpl
,I/EmuiFeatureManager( 6457): loadEmailAnrSupportFlag:true
,I/Mms_threadcache( 6457): [RecipientIdCache] fill: begin
,I/CalendarProvider2( 6386): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6386): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 2983): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/SimFactoryManager( 6457): Inside init method of SimFactoryManger the combination is:-1
,I/SimFactoryManager( 6457): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6457): isSIM1CardPresent:1
,I/SimFactoryManager( 6457): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6457): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6457): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/SimFactoryManager( 6457): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 6457): isSIM2CardPresent:1
,E/MmsConfig( 6457): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
I/SimFactoryManager( 6457): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6457): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6457): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/HwCust  ( 6457): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
,I/HwCust  ( 6457): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
,I/art     ( 6457): Can not find class: Lhuawei/android/view/TableLayout;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/TableLayout;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/View;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/View;
I/art     ( 6457): Can not find class: Landroid/widget/View;
I/art     ( 6457): Can not find class: Landroid/webkit/View;
,I/art     ( 6457): Can not find class: Landroid/app/View;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/TableRow;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/TableRow;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/LinearLayout;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/LinearLayout;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/ImageButton;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/ImageButton;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/TextView;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/TextView;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/RelativeLayout;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/RelativeLayout;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/ImageView;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/ImageView;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/ViewStub;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/ViewStub;
I/art     ( 6457): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6457): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6457): Can not find class: Landroid/app/ViewStub;
,E/CSP_RADAR( 6457): Message execute too long time.{ when=-240ms what=1 target=com.huawei.mms.util.HwBackgroundLoader$3 }
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10056
I/HwSystemManager( 3974): HoldService:uid:10056 pid:5540 died
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/HwSystemManager( 3974): HoldService:oldVersionKey:10056,5540
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10056, pid: 5540
,W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10056, pid: 5540
,I/HwCust  ( 6457): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
,I/HwCust  ( 6457): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
,I/art     ( 6457): Can not find class: Lhuawei/android/view/FrameLayout;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/FrameLayout;
,I/art     ( 6457): Can not find class: Lhuawei/android/view/EditText;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/EditText;
,E/textview( 6457): initAddtionalStyle default
,E/CSP_RADAR( 6457): Runnable execute too long time
,I/art     ( 6457): Can not find class: Lhuawei/android/view/ProgressBar;
,I/art     ( 6457): Can not find class: Lhuawei/android/widget/ProgressBar;
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 6457): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,I/BluetoothAdapter( 5868): Start to disable Bluetooth!
,E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
W/MediaProcessHandler( 2983): processOp uid 1000 is not concerned!
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3974): HoldService:uid:1000 pid:5580 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:1000,5580
,I/HwSystemManager( 3974): HoldService:checkBeforeShowDialog: uid:10302 pid:5868, permissionType:2097152
I/HwSystemManager( 3974): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2983): allowOpenWifi blocked:false
,I/jxcore-log( 5868): ****TEST TOOK:  5150  ms ****
I/jxcore-log( 5868): 
,I/jxcore-log( 5868): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5868): 
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 3974): HoldService:uid:10065 pid:5619 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10065,5619
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10065, pid: 5619
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10065, pid: 5619
I/HwSystemManager( 3974): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3974): NotificationManagerReceiver:onReceive, send action to background
,I/HwSystemManager( 3974): ProcPolicy:begin get procName.
,I/HwSystemManager( 3974): ProcPolicy:this proc is:com.huawei.systemmanager:service
I/HwSystemManager( 3974): ProcPolicy:end get procName.
,I/HwSystemManager( 3974): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@2d2049cc
,I/HwSystemManager( 3974): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3974): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3974): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings]
,I/HwSystemManager( 3974): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
,I/HwSystemManager( 3974): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
I/HwSystemManager( 3974): NmCenterDefValueXmlHelper:getConfigs: Starts
,I/HwSystemManager( 3974): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33
,I/HwSystemManager( 3974): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
,I/HwSystemManager( 3974): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3974): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3974): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3974): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 3974): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 3974): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3974): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3974): NotificationDBProvider:query starts, matchCode = 1
,I/PhoneStatusBar( 3219): notification pkg =com.android.settings
I/PhoneStatusBar( 3219): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3219): notification pkg =android
I/PhoneStatusBar( 3219): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,I/HwSystemManager( 3974): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3974): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3974): HsmIntentService:last work complete! lets stop service.
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 408us total 22.557ms
,W/asset   ( 6527): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 387us total 22.031ms
,I/HwSystemManager( 3974): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@2d2049cc
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 426us total 20.538ms
,I/HwSystemManager( 6527): SystemManagerApplication:onCreate
,I/HwSystemManager( 3974): MainService:on startCommand,flags:0,startId:6
,I/appproc ( 6523): CLASSPATH=/system/framework/pm.jar
I/appproc ( 6523): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 6523): app_process:number,5,0
I/System.out( 6527): [ls, -l, /system/app/HwSystemManager/HwSystemManager.apk]
I/System.out( 6527): null
I/System.out( 6527): null
,I/System.out( 6527): Calling by::className:bkk  MethodName:yw
,I/AndroidRuntime( 6523): readDownloadBoosterConfig: 'false'
,I/HwSystemManager( 3974): LocalService:Received start id 6: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
,I/HwSystemManager( 3974): BgPowerManagerService:onStartCommand
,I/HwSystemManager( 3974): AppLockService:onStartCommand
,I/HwSystemManager( 6527): check push opration, match idx:-1
,I/HwSystemManager( 3974): AppCleanUpService:onStartCommand() in!
,I/HwSystemManager( 6527): HsmStat_info:feature enable:false
,I/HwSystemManager( 6527): ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.test.thalitest, com.example.hello]
,I/HwSystemManager( 6527): OverseaCfgHelper:permissionStatus is 0
,I/HwSystemManager( 6527): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6527): ProcPolicy:begin get procName.
,I/HwSystemManager( 6527): ProcPolicy:this proc is:com.huawei.systemmanager
I/HwSystemManager( 6527): ProcPolicy:end get procName.
,I/HwSystemManager( 6527): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
I/YhdsEngine( 6527): [EngineIntentService] Received: com.huawei.dianxinos.optimizer.engine.action.APP_START
,I/HwSystemManager( 6527): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 6527): SimCardManager:getOperatorNameFromService mNameServSlot0 = null
I/HwSystemManager( 6527): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
I/HwSystemManager( 6527): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 6527): SimCardManager:getOperatorNameFromService mNameServSlot1 = null
I/HwSystemManager( 6527): SimCardManager:/onReceive: action =android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 6527): SimCardManager:action:android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 6527): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@129358dc
I/HwSystemManager( 6527): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
I/HwSystemManager( 6527): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
I/HwSystemManager( 6527): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,I/HwSystemManager( 6527): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
,I/HwSystemManager( 6527): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6527): OverseaCfgHelper:permissionStatus is 0
I/YhdsEngine( 6527): [AlarmEventMgr] event scheduled: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
,I/HwSystemManager( 3974): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 3974): AppCleanUpService:onStartCommand() out!
E/HwSystemManager( 3974): AppCleanUpService:msg is 0
,I/HwCust  ( 6527): Constructor found for class com.huawei.systemmanager.optimize.process.HwCustProtectAppControlImpl
,I/HwSystemManager( 6527): HsmPackageManager:begin to scan apks.
,I/YhdsEngine( 6527): [EngineIntentService] Received: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
,I/HwSystemManager( 6527): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,I/HwSystemManager( 6527): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
I/HwSystemManager( 6527): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
W/HwSystemManager( 6527): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6527): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6527): HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:3, queue size:0
,I/HwSystemManager( 6527): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6527): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6527): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6527): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6527): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6527): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6527): anf:packageCanAccessInternet com.example.hellohas INTERNET permission
I/HwSystemManager( 6527): anf:packageCanAccessInternet component enable
I/HwSystemManager( 6527): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], applock=[Rule AppLockNotMonitorListRule post: match[0], mismatch[2], Rule HomeCategoryRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6527): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello, replacing: false
I/YhdsEngine( 6527): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
I/HwSystemManager( 6527): XmlRuleBase:parseAndCacheList permission_black_list_match :[]
I/HwSystemManager( 6527): XmlRuleBase:parseAndCacheList black_match :[]
I/HwSystemManager( 6527): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
I/HwSystemManager( 6527): AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6527): XmlRuleBase:parseAndCacheList permission_white_list_match :[com.huawei.intelligent]
,I/HwSystemManager( 6527): XmlRuleBase:parseAndCacheList dropzone_black_list_match :[]
I/HwSystemManager( 6527): XmlRuleBase:parseAndCacheList white_match :[com.baidu.map.location, com.cootek.smartdialer_oem_module, com.sohu.inputmethod.sogou.huawei, com.huawei.hisuite, com.nuance.swype.emui, com.huawei.remoteassistant, com.iflytek.speechcloud, com.huawei.phoneservice, com.huawei.phonediagnose, com.nqmobile.antivirus20.hw, com.baidu.input_huawei]
I/HwSystemManager( 6527): XmlRuleBase:parseAndCacheList dropzone_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 6527): HsmPackageManager:end to scan apks. size:150 + 0
I/HwSystemManager( 6527): HsmPackageManager:init locale:en_US
I/HwSystemManager( 6527): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6527): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:2, queue size:0
I/HwSystemManager( 6527): ProtectAppControl:handleMessage:6
I/HwSystemManager( 6527): ProtectAppControl:begin install app inner:com.example.hello
I/HwSystemManager( 6527): AppManager:insert to db: name = com.example.hello uid = 10302 app type = false
I/HwSystemManager( 6527): PermissionDBAdapter:DBAdapter created!
I/HwSystemManager( 6527): PermissionDbHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/permission.db
I/HwSystemManager( 6527): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6527): PermissionDBAdapter:appcationsList size:150
W/HwSystemManager( 6527): ProtectAppControl:com.example.hello already exist!
,W/HwSystemManager( 6527): AddViewAppManager:Current installed app not apply system_alert_window or applicationInfo null!
,I/        ( 6523): power log dlsym ok
,E/android_hardware_fm.cpp( 6523): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6523): ========64bit long size = 8
E/FM_HAL  ( 6523): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 6523): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6523): 
I/fm_hisi ( 6523): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6523): 
I/fm_hisi ( 6523): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6523): 
,E/android_hardware_fm.cpp( 6523): register_android_hardware_fm_fmradio, ret is 0
,I/art     ( 2983): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/art     ( 2983): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
I/HwSystemManager( 6527): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 6527): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6527): PermissionDBAdapter:appcationsList size:150
,I/HwEmailTag( 6419): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/HwEmailTag( 6419): EmailProvider->query->1449497278459;end;;consuming:2ms;
,I/HwLauncher( 3746): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3746): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3746): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10302
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10302, pid: 5868
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10302, pid: 5868
,I/HwSystemManager( 3974): HoldService:uid:10302 pid:5868 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10302,5868
,I/HwEmailTag( 6419): Device->updateDeviceIdIfNeeded
,I/HwEmailTag( 6419): CleanRecipient->onCreate
,I/HwEmailTag( 6419): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 6419): Device->getDeviceId->
,I/HwEmailTag( 6419): Device->getDeviceIdInternal->isUpdate:false
I/HwEmailTag( 6419): CleanRecipient->onStartCommand->action is null
,I/HwEmailTag( 6419): CleanRecipient->onHandleIntent->action is null
I/HwEmailTag( 6419): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 6419): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
,I/ActivityManager( 2983): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/HwLauncher( 3746): Launcher onStart()
I/HwLauncher( 3746): Launcher dynamicIconsRegister
I/HwLauncher( 3746): DynamicUpdater registerReceiver
,I/HwLauncher( 3746): DynamicUpdater call updateFolder
I/HwLauncher( 3746): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3746): DynamicUpdater registerReceiver
,I/HwEmailTag( 6419): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/ActivityManager( 2983): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/HwSystemManager( 3974): AppLockService:applock password not initial or function is closed
,I/HwSystemManager( 6527): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 6527): HsmPackageManager:replacing:false
I/HwSystemManager( 6527): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 6527): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwEmailTag( 6419): CleanRecipient->onDestroy
,I/HwLauncher( 3746): DynamicUpdater call updateFolder
I/HwLauncher( 3746): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3746): DynamicUpdater registerReceiver
,I/InputReader( 2983): Reconfiguring input devices.  changes=0x00000010
,I/HwSystemManager( 3974): AppManager:getNetAppInfoFromDB cursor lenth = 1
,E/RegisteredServicesCache( 3668): invalidateCache set mNeedToastTableFull
,W/GeofencerStateMachine( 3583): Ignoring removeGeofence because network location is disabled.
,I/HwLauncher( 3746): DynamicUpdater call updateFolder
I/HwLauncher( 3746): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
I/HwLauncher( 3746): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3746): Launcher onResume()
,I/HwLauncher( 3746): Launcher doResumeWork()
,I/HwLauncher( 3746): Launcher.MotionManager startMotionAppsReco 402
,W/PGApi_client( 3620): recv actoionId = 10010, action = com.huawei.pgmng.PGAction@2d19e4d3 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3620): in handleAction method, action = 10010
W/PGMiddleWare jhh( 3620): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@3ae97347, action = com.huawei.pgmng.PGAction@2d19e4d3 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3620): jhh handle default mActionId = 10010, action = com.huawei.pgmng.PGAction@2d19e4d3 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3620): enter into the safetyguard Scene.
W/AudioEffectLowPowerImpl jhh( 3620): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3620): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3620): return for smartPAOn and mLowAudioEffectEnable both = false
,I/HwLauncher( 3746): Launcher  onResume mIsToUninstallApp = false
,W/System.err( 2983): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/ResourceType( 2983): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,W/System.err( 2983): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 2983): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 2983): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 2983): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2983): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2983): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/HwLauncher( 3746): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3746): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,I/art     ( 3974): Explicit concurrent mark sweep GC freed 91617(6MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 14MB/23MB, paused 1.374ms total 121.408ms
,I/HwSystemManager( 3974): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/HwSystemManager( 3974): HsmPackageManager:replacing:false
,I/HwSystemManager( 3974): HsmPackageManager:pkgName:com.example.hello
,I/HwSystemManager( 3974): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwSystemManager( 3974): ww:deleteLockData:com.example.hello
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 294us total 48.814ms
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 205us total 26.411ms
,W/asset   ( 2983): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 216us total 24.263ms
,I/HwSystemManager( 6527): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwLauncher( 3746): Launcher  onWindowVisibilityChanged visibility = 0
,I/HwLauncher( 3746): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3746): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,I/art     ( 2983): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,I/art     ( 2983): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,I/art     ( 2983): Can not find class: Lhuawei/com/android/server/util/ReportTool;
,I/art     ( 2983): Can not find class: Lcom/huawei/report/ReporterInterface;
,E/ReportTools( 2983): Can't find sReporterClazz
,I/HwEmailTag( 6419): AccountReconciler->reconcileAccountsInternal->consuming:357ms
I/art     ( 2983): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/art     ( 2983): Can not find class: Lhuawei/com/android/server/util/AppInfo;
,W/asset   ( 6613): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,W/System.err( 2983): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,I/HwLauncher( 3746): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3746): Model replacing = false package = com.example.hello
W/System.err( 2983): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2983): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2983): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2983): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2983): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 2983): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
I/HwLauncher( 3746): Model  ACTION_PACKAGE_REMOVED replacing = false
W/System.err( 2983): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 2983): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 2983): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
I/HwLauncher( 3746): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
W/System.err( 2983): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 2983): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2983): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2983): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2983): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 2983): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 2983): 	at java.lang.reflect.Method.invoke(Native Method)
I/HwLauncher( 3746): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
W/System.err( 2983): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2983): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 2983): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 2983): This is not beta user build
I/HwLauncher( 3746): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
,I/PhoneStatusBar( 3219): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/HwSystemManager( 6527): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6527): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6527): HsmIntentService:last work complete! lets stop service.
,I/HwEmailTag( 6419): EmailProvider->query->1449497278835;end;;consuming:10ms;
I/HwLauncher( 3746): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3746): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3746): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3746): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3746): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,I/HwEmailTag( 6419): AccountReconciler->reconcileAccountsInternal->consuming:15ms
,I/art     ( 2983): Explicit concurrent mark sweep GC freed 28194(1796KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 27MB/41MB, paused 3.100ms total 366.875ms
I/art     ( 2983): WaitForGcToComplete blocked for 6.325ms for cause Explicit
,I/HwCust  ( 6613): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/HwCust  ( 6613): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,I/HwSystemManager( 6527): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@129358dc
,I/ContactsAppilcation( 6457): intent:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,I/CommonUtilMethods( 6457): action:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6457): intent:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
,I/CommonUtilMethods( 6457): action:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6457): intent:android.provider.Telephony.SPN_STRINGS_UPDATED
,I/GAv4    ( 6579): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6579):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6579):   adb logcat -s GAv4
,I/art     ( 2983): Explicit concurrent mark sweep GC freed 5681(341KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.848ms total 204.930ms
,I/PhoneStatusBar( 3219): shouldTranslucent:true
I/PhoneStatusBar( 3219): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 1050
I/HwSystemManager( 3974): HoldService:uid:1050 pid:5643 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:1050,5643
,I/HwLauncher( 3746): Model mAllAppsList.removePackage com.example.hello
,E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
W/MediaProcessHandler( 2983): processOp uid 1050 is not concerned!
,I/PG Utils( 3746): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,F/libc    ( 6523): Fatal signal 11 (SIGSEGV), code 1, fault addr 0x7f7eb3e1ac in tid 6601 (Binder_1)
,E/        ( 2307): tid 6601 does not exist in pid 6523. ignoring debug request
W/GAv4    ( 6579): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/HwLauncher( 3746): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
I/HwLauncher( 3746): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3746):  stringArray[] [unknown]
,I/HwCust  ( 6658): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 6658): EmailContent->init->consuming:27ms->;-prefixstartupperformance-
,W/GAv4    ( 6579): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6579): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6579): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.44
,E/HideAppsPagedView( 3746): removeItems begin 
E/HideAppsPagedView( 3746): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3746): removeItems end 
I/HwEmailTag( 6658): Exchange->onCreate
,I/HwLauncher( 3746): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
,W/System.err( 3746): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3746): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3746): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3746): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3746): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3746): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3746): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3746): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3746): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3746): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
W/System.err( 3746): java.lang.NullPointerException: null receiver
,W/System.err( 3746): 	at java.lang.reflect.Field.get(Native Method)
W/System.err( 3746): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3746): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3746): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3746): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3746): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3746): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3746): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3746): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3746): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwLauncher( 3746): CellLayout rearrangeAfterRmItem isAutoAlign = false
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10090
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/HwSystemManager( 3974): HoldService:uid:10090 pid:5686 died
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10090, pid: 5686
I/HwSystemManager( 3974): HoldService:oldVersionKey:10090,5686
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10090, pid: 5686
,I/PG Utils( 6658): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,E/HideAppsPagedView( 3746): removeHideApps  begin 
E/HideAppsPagedView( 3746): removeHideApps  end 
E/HideAppsPagedView( 3746):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3746):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
,E/HideAppsPagedView( 3746):  createAddIcon count = 0
I/HwLauncher( 3746):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/PG Utils( 6658): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 6419): EmailProvider->query->1449497279266;end;;consuming:3ms;
,I/HwEmailTag( 6658): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,W/MotionDetectionManager( 3746): startMotionAppsReco motionApps: 402 disabled
W/HwLauncher( 3746): Launcher.MotionManager startMotionAppsReco service flg 402 is unavailable
I/HwSystemManager( 6527): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 6527): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 6527): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,W/OpenGLRenderer( 3746): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 3746): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,W/ContextImpl( 6579): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10092
I/HwSystemManager( 3974): HoldService:uid:10092 pid:5719 died
I/HwSystemManager( 3974): BgPowerManagerService:onProcessDied uid = 10095
I/HwSystemManager( 3974): HoldService:oldVersionKey:10092,5719
I/HwSystemManager( 3974): HoldService:uid:10095 pid:5741 died
I/HwSystemManager( 3974): HoldService:oldVersionKey:10095,5741
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10092, pid: 5719
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10092, pid: 5719
E/HsmCoreServiceImpl( 2983): onTransact in code is: 102
I/MediaProcessHandler( 2983): processOp opType: 1, uid: 10095, pid: 5741
W/MediaProcessHandler( 2983): remove target not exist, maybe the UI process: uid: 10095, pid: 5741
,E/hwcomposer( 2292): setTopResource:1220: set top resource failed!! ret:-1 
E/hwcomposer( 2292): comp_mode= 0
E/hwcomposer( 2292): disp_ch_res = 0x0 
E/hwcomposer( 2292): res_info.ovly1_res = 0x0 
E/hwcomposer( 2292): res_info.ovly2_res = 0x205 
E/hwcomposer( 2292): res_info.ovly3_res = 0x46
E/hwcomposer( 2292): res_info.rot_res = 0x0
E/hwcomposer( 2292): res_info.scl2_res = 0x21
E/hwcomposer( 2292): res_info.compose_ch_res[0] = 0x408
E/hwcomposer( 2292): res_info.compose_ch_res[1] = 0x409
E/hwcomposer( 2292): res_info.compose_ch_res[2] = 0x40a
E/hwcomposer( 2292): res_info.compose_ch_res[3] = 0x80b
E/hwcomposer( 2292): res_info.compose_ch_res[4] = 0x52c
E/hwcomposer( 2292): res_info.compose_ch_res[5] = 0x4ad
E/hwcomposer( 2292): ade_reg_res = 0x0
E/hwcomposer( 2292): setGlobal:234: setTopResource fail!! 
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(37)
E/hwcomposer( 2292): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2292): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2292): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(57)
E/hwcomposer( 2292): phy_addr(0x2a2e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2292): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2292): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(2)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(5),  	 height(50),  	 width(720),  	 rotation(0), 	 sharefd(64)
E/hwcomposer( 2292): phy_addr(0x317e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2292): stride(2880),  	 dst_height(50),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,0,720,50),  	 dst_rect xywh(0,0,720,50)
E/hwcomposer( 2292): ovly_output_rect xywh(0,0,720,50),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): commit:654: commit failed!! ret:-1, frame_number:374, 
E/hwcomposer( 2292): is_finished  (0), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2292): dst_rotation (0), 	 dst_rect xywh (0,0,720,50), 	 src_rect xywh (0,0,720,50) 
E/hwcomposer( 2292): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2292): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2292): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2292): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2292): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2292): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2292): finishOneArea:142: finishOneArea commit error
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(37)
E/hwcomposer( 2292): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovl,y_surf_num(0)
E/hwcomposer( 2292): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,50,720,1134),  	 dst_rect xywh(0,50,720,1134)
E/hwcomposer( 2292): ovly_output_rect xywh(0,50,720,1134),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(57)
E/hwcomposer( 2292): phy_addr(0x2a2e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2292): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,50,720,1134),  	 dst_rect xywh(0,50,720,1134)
E/hwcomposer( 2292): ovly_output_rect xywh(0,50,720,1134),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): commit:654: commit failed!! ret:-1, frame_number:374, 
E/hwcomposer( 2292): is_finished  (0), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2292): dst_rotation (0), 	 dst_rect xywh (0,50,720,1134), 	 src_rect xywh (0,50,720,1134) 
E/hwcomposer( 2292): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2292): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2292): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2292): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2292): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2292): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2292): finishOneArea:142: finishOneArea commit error
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(0)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0100),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(3),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(37)
E/hwcomposer( 2292): phy_addr(0xe8e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2292): stride(5760),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,1184,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2292): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(1)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(57)
E/hwcomposer( 2292): phy_addr(0x2a2e000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2292): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,1184,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2292): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(2)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(5),  	 height(96),  	 width(720),  	 rotation(0), 	 sharefd(66)
E/hwcomposer( 2292): phy_addr(0x31e6000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2292): stride(2880),  	 dst_height(96),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,0,720,96),  	 dst_rect xywh(0,1184,720,96)
E/hwcomposer( 2292): ovly_output_rect xywh(0,1184,720,96),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): commit:654: commit failed!! ret:-1, frame_number:375, 
E/hwcomposer( 2292): is_finished  (1), 	 compose mode (0), 	 compose pattern num (0) 
E/hwcomposer( 2292): dst_rotation (0), 	 dst_rect xywh (0,1184,720,96), 	 src_rect xywh (0,1184,720,96) 
E/hw,composer( 2292): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2292): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2292): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2292): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2292): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2292): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2292): play:197: play commit error
E/hwcomposer( 2292): enableVsync:1073: vsync ioctl failed 
E/hwcomposer( 2292): EventControl:120: vsync ioctl failed
E/SurfaceFlinger( 2292): eventControl(0, 1) failed Operation not permitted
E/hwcomposer( 2292): setTopResource:1220: set top resource failed!! ret:-1 
E/hwcomposer( 2292): comp_mode= 0
E/hwcomposer( 2292): disp_ch_res = 0x3 
E/hwcomposer( 2292): res_info.ovly1_res = 0xc 
E/hwcomposer( 2292): res_info.ovly2_res = 0x0 
E/hwcomposer( 2292): res_info.ovly3_res = 0x0
E/hwcomposer( 2292): res_info.rot_res = 0x0
E/hwcomposer( 2292): res_info.scl2_res = 0x0
E/hwcomposer( 2292): res_info.compose_ch_res[0] = 0x0
E/hwcomposer( 2292): res_info.compose_ch_res[1] = 0x0
E/hwcomposer( 2292): res_info.compose_ch_res[2] = 0x0
E/hwcomposer( 2292): res_info.compose_ch_res[3] = 0x0
E/hwcomposer( 2292): res_info.compose_ch_res[4] = 0x0
E/hwcomposer( 2292): res_info.compose_ch_res[5] = 0x0
E/hwcomposer( 2292): ade_reg_res = 0x0
E/hwcomposer( 2292): setGlobal:234: setTopResource fail!! 
E/hwcomposer( 2292): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2292): compose_mode(0), 	 ch_index(6)
E/hwcomposer( 2292): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2292): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2292): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(21)
E/hwcomposer( 2292): phy_addr(0x402000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2292): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2292): src_rect xywh(0,0,720,1280),  	 dst_rect xywh(0,0,720,1280)
E/hwcomposer( 2292): ovly_output_rect xywh(0,0,720,1280),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2292): commit:654: commit failed!! ret:-1, frame_number:376, 
E/hwcomposer( 2292): is_finished  (1), 	 compose mode (0), 	 compose pattern num (3072) 
E/hwcomposer( 2292): dst_rotation (0), 	 dst_rect xywh (0,0,720,1280), 	 src_rect xywh (0,0,720,1280) 
E/hwcomposer( 2292): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2292): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2292): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2292): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2292): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2292): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2292): play:197: play commit error

```
