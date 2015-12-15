#### Test 50388019385b4d9_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/dex2oat ( 6050): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=default --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.googlequicksearchbox/files/extradex_jars/verified/backgroundtasks/backgroundtasks-0.jar --oat-fd=37 --oat-location=/data/data/com.google.android.googlequicksearchbox/files/extradex_jars/verified/backgroundtasks/backgroundtasks-0.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/PG Utils( 6011): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 3831): HoldService:uid:10050 pid:5357 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10050,5357
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10050, pid: 5357
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10050, pid: 5357
I/PG Utils( 3543): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5727): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/dex2oat ( 6050): dex2oat took 161.467ms (threads: 8)
W/InstanceID/Rpc( 5727): Found 10007
I/SearchBackgroundTaskFac( 5980): Checking for language pack updates
I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/VelvetNetworkClient( 5980): Network connection not availble
I/GservicesUpdateTask( 5980): Updating Gservices keys
I/VelvetNetworkClient( 5980): Network connection not availble
I/PG Utils( 5980): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/PG Utils( 5980): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 3543): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/WebViewFactory( 5980): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/CheckinService( 5727): Checkin interval check for package: unspecified last checkin: 1449832345873 min interval config: 0 actual interval: 356958653
I/PG Utils( 3543): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/LibraryLoader( 5980): Loading: webviewchromium
I/CheckinService( 5727): Disabling old GoogleServicesFramework version
I/LibraryLoader( 5980): Time to load native libraries: 11 ms (timestamps 2136-2147)
I/LibraryLoader( 5980): Expected native library version number "",actual native library version number ""
W/art     ( 5980): Attempt to remove local handle scope entry from IRT, ignoring
I/PG Utils( 3543): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5980): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/GCoreUlr( 5727): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/CheckinService( 5727): Checking schedule, now: 1450189304606 next: 1450422606597
I/CheckinService( 5727): active receiver: disabled
I/SystemUpdateService( 5727): cancelUpdate (empty URL)
I/SystemUpdateService( 5727): active receiver: disabled
I/art     ( 5634): Explicit concurrent mark sweep GC freed 8091(406KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 13MB/22MB, paused 918us total 38.078ms
W/art     ( 5980): Attempt to remove local handle scope entry from IRT, ignoring
W/RefreshDomainCookieTask( 5980): Search parameters fetch failed: com.google.android.apps.gsa.shared.api.io.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
W/RefreshDomainCookieTask( 5980): Search parameters fetch failed
E/Thermal-daemon( 2331): [ap] temp_new :32  temp_old :33
I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.security.snet.BOOT_COMPLETED
I/ActivityManager( 2992): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
W/BaseAppContext( 5727): Using Auth Proxy for data requests.
I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
E/BaseAppContext( 5727): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/art     ( 5727): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
I/art     ( 5727): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/j/c;
I/art     ( 5727): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/AuthZen ( 5727): Fetching signing key...
I/AuthZen ( 5727): Signing key fetched successfully!
W/BaseAppContext( 5727): Using Auth Proxy for data requests.
I/art     ( 5727): Explicit concurrent mark sweep GC freed 47684(3MB) AllocSpace objects, 28(560KB) LOS objects, 24% free, 18MB/24MB, paused 4.734ms total 137.061ms
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3543): Explicit concurrent mark sweep GC freed 18647(1267KB) AllocSpace objects, 10(200KB) LOS objects, 39% free, 20MB/33MB, paused 1.196ms total 104.109ms
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/art     ( 5634): Explicit concurrent mark sweep GC freed 2477(98KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 13MB/22MB, paused 522us total 29.148ms
I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/System  ( 3543): core_booster, getBoosterConfig = false
I/GCoreUlr( 3543): DispatchingService.onCreate()
I/System  ( 3543): core_booster, getBoosterConfig = false
I/ActivityManager( 2992): filter receiver for action = com.google.android.gcm.DISCONNECTED
W/GoogleHttpServiceClient( 3543): Timeout on service connection
W/GoogleHttpServiceClient( 3543): java.lang.Throwable
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.http.e.a(SourceFile:97)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.http.g.a(SourceFile:146)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:757)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:665)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.j.a.a(SourceFile:77)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.j.a.a(SourceFile:114)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.be.account.b.e.a(SourceFile:115)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.be.p.a(SourceFile:355)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.be.o.a(SourceFile:260)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.firstparty.dataservice.y.a(SourceFile:197)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:558)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:196)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.o.a(SourceFile:276)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.gms.auth.o.a(SourceFile:196)
W/GoogleHttpServiceClient( 3543): 	at com.google.android.b.b.onTransact(SourceFile:137)
W/GoogleHttpServiceClient( 3543): 	at android.os.Binder.execTransact(Binder.java:446)
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/GCoreUlr( 3543): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
E/Auth    ( 3543): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5980): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5980): java.io.IOException: NetworkError
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5980): 	at java.lang.Thread.run(Thread.java:831)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/PG Utils( 3543): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
E/Auth    ( 3543): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5980): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 5980): java.io.IOException: NetworkError
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 5980): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 5980): 	at java.lang.Thread.run(Thread.java:831)
W/Search.LoginHelper( 5980): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/GCoreFlp( 3543): No location to return for getLastLocation()
W/FusedLocationProvider( 3543): location=null
W/Auth    ( 3543): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/appproc ( 6125): CLASSPATH=/system/framework/am.jar
I/appproc ( 6125): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 6125): app_process:number,5,0
W/GCoreFlp( 3543): No location to return for getLastLocation()
W/FusedLocationProvider( 3543): location=null
I/AndroidRuntime( 6125): readDownloadBoosterConfig: 'false'
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/GCoreUlr( 3543): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 3543): Unbound from all location providers
I/GCoreUlr( 3543): Place inference reporting - stopped
I/GCoreUlr( 3543): DispatchingService.onDestroy()
I/GCoreUlr( 3543): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 3543): Unbound from all location providers
I/GCoreUlr( 3543): Place inference reporting - stopped
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 3543): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 3543): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/        ( 6125): power log dlsym ok
W/StubController( 6162): calendar access!
E/android_hardware_fm.cpp( 6125): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6125): ========64bit long size = 8
E/FM_HAL  ( 6125): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6125): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6125): 
I/fm_hisi ( 6125): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6125): 
I/fm_hisi ( 6125): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6125): 
E/android_hardware_fm.cpp( 6125): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 2992): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2992): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2992): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2992): Can not find class: Lcom/android/server/wm/StartingData;
I/HwLauncher( 3674): Launcher onPause()
I/HwLauncher( 3674): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3674): Launcher.MotionManager stopMotionAppsReco 403
I/art     ( 2992): Can not find class: Landroid/widget/ViewStub;
I/art     ( 2992): Can not find class: Landroid/webkit/ViewStub;
W/HwLauncher( 3674): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
I/art     ( 2992): Can not find class: Landroid/app/ViewStub;
W/HwLauncher( 3674): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
I/art     ( 2992): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/art     ( 3674): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3674): Can not find class: Lhuawei/android/widget/EditText;
I/art     ( 2325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 442us total 31.045ms
E/textview( 3674): initAddtionalStyle default
I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 420us total 28.625ms
E/        ( 2992): open /proc/5336/smaps fail errno 2
E/        ( 2992): open /proc/5357/smaps fail errno 2
I/PhoneStatusBar( 3233): shouldTranslucent:true
I/PhoneStatusBar( 3233): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwSystemManager( 3831): AppLockService:applock password not initial or function is closed
I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 1.175ms total 33.105ms
I/HwLauncher( 3674): Launcher onStop()
I/HwLauncher( 3674): Launcher dismissDialog
I/HwLauncher( 3674): Launcher dynamicIconsUnregister
I/HwLauncher( 3674): DynamicUpdater unregisterReceiver
W/PGApi_client( 3567): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@3487c8d5 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3567): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3567): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@25a1bc2e, action = com.huawei.pgmng.PGAction@3487c8d5 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3567): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@3487c8d5 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3567): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3567): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3567): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3567): return for smartPAOn and mLowAudioEffectEnable both = false
I/art     ( 2992): Explicit concurrent mark sweep GC freed 20683(1174KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 27MB/41MB, paused 1.800ms total 203.732ms
I/HwLauncher( 3674): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3674): DynamicUpdater unregisterReceiver
I/PG Utils( 6162): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
I/HwLauncher( 3674): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3674): DynamicUpdater unregisterReceiver
I/HwLauncher( 3674): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3674): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3674): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
W/StubController( 6186): calendar access!
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 3831): AppLockService:applock password not initial or function is closed
W/StubController( 6162): calendar access!
I/PG Utils( 6162): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
I/WebViewFactory( 6210): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
W/StubController( 6162): calendar access!
I/CalendarSimpleUiPRovider( 6162): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6162): onConfigurationChanged
I/PG Utils( 6162): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
W/StubController( 6162): calendar access!
I/HwCust  ( 6244): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl
I/CalendarSimpleUiPRovider( 6162): initParams20151215T152146Europe/Warsaw(2,348,3600,0,1450189306)
I/PG Utils( 6244): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/PG Utils( 6244): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
W/StubController( 6162): calendar access!
I/PG Utils( 6244): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/LibraryLoader( 6210): Loading: webviewchromium
I/HwCust  ( 6244): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/HwCust  ( 6244): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/PG Utils( 6244): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/HwCust  ( 6244): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
E/ContactsProtector( 6244): getHiCloudAccountData query fail
I/PG Utils( 6244): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/PG Utils( 3498): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
I/LibraryLoader( 6210): Time to load native libraries: 58 ms (timestamps 3887-3945)
I/LibraryLoader( 6210): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 6210): Expected native library version number "",actual native library version number ""
I/chromium( 6210): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/HwCust  ( 6244): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
I/BrowserStartupController( 6210): Initializing chromium process, renderers=0
W/art     ( 6210): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6210): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6210): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6210): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 6210): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
I/HwCust  ( 6244): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
I/HwLauncher( 3674): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
W/StubController( 6162): calendar access!
I/HwLauncher( 3674): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10056
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/HwSystemManager( 3831): HoldService:uid:10056 pid:5378 died
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10056, pid: 5378
I/HwSystemManager( 3831): HoldService:oldVersionKey:10056,5378
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10056, pid: 5378
I/HwLauncher( 3674): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3674): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3674): Model STK reName intent is received.
I/HwLauncher( 3674): Model mAllAppsList.updatePackage com.android.stk
I/HwLauncher( 3674): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
I/HwSystemManager( 3831): ContactsObserverHelper:Receive contacts change broadcast
I/ActivityManager( 2992): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
I/HwLauncher( 3674): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3674): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3674): Model STK reName intent is received.
I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3831): HoldService:uid:1000 pid:5400 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:1000,5400
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
W/MediaProcessHandler( 2992): processOp uid 1000 is not concerned!
I/HwLauncher( 3674): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/CalendarSimpleUiPRovider( 6162): loadEvent end update UI0
I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3674): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3674): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3674): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3674): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3674): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3674): Model mAllAppsList.updatePackage com.android.stk
I/HwLauncher( 3674): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3674): Launcher.Folder childCount: 5
I/HwLauncher( 3674): Launcher.Folder childCount: 5
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 6
I/HwLauncher( 3674): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3674): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
I/HwLauncher( 3674): Launcher.Folder childCount: 6
I/HwLauncher( 3674): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3674):  syncPages mCurrentPage = 0
I/HwLauncher( 3674): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
E/HideAppsPagedView( 3674):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3674):  createAddIcon count = 0
I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3674):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/HwLauncher( 3674): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3674): Launcher Deferring update until onResume
I/HwEmailTag( 6294): MailAppProvider->onCreate->begin, consuming 1450189306677ms->-prefixstartupperformance-
I/HwEmailTag( 6294): MailAppProvider->onCreate->end, consuming 1450189306704ms->-prefixstartupperformance-
W/chromium( 6210): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/HwCust  ( 6294): Constructor found for class com.android.email.service.HwCustImapServiceImpl
W/chromium( 6210): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/HwCust  ( 6294): Constructor found for class com.android.email.HwCustUtilityImpl
W/chromium( 6210): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/HwCust  ( 6294): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
I/HwCust  ( 6294): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
I/HwEmailTag( 6294): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6294): HwUtils->initStaticVarsAsync
I/HwCust  ( 6294): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
I/HwEmailTag( 6294): EmailContent->init->consuming:21ms->;-prefixstartupperformance-
I/HwEmailTag( 6294): EmailProvider->sURIMatcher is initialized
I/HwEmailTag( 6294): EmailProvider->onCreate->end, consuming 30ms->-prefixstartupperformance-
I/HwCust  ( 6294): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
I/HwEmailTag( 6294): EmailProvider->resetVisibleLimits->start:1450189306764 ->-prefixstartupperformance-
I/HwEmailTag( 6294): HwUtils->initStaticVarsAsync->run:consuming:34ms; bidiFormatter:android.support.v4.text.BidiFormatter@1873f856;accountsProjSize:42
I/HwEmailTag( 6294): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6294): HwUtils->initStaticVarsAsync
I/HwEmailTag( 6294): DBHelper->onOpen-> EmailProvider.db
I/HwEmailTag( 6294): EmailProvider->INTEGRITY_CHECK_URI != null
I/HwEmailTag( 6294): EmailProvider->onCreate->end, consuming 1ms->-prefixstartupperformance-
I/HwEmailTag( 6294): EmailProvider->resetVisibleLimits->start:1450189306781 ->-prefixstartupperformance-
I/HwLauncher( 3674): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10047
I/HwSystemManager( 3831): HoldService:uid:10047 pid:5437 died
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/HwSystemManager( 3831): HoldService:oldVersionKey:10047,5437
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10047, pid: 5437
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10047, pid: 5437
I/HwEmailTag( 6294): EmailApplication->onCreate->begin, consuming 7ms->-prefixstartupperformance-
I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwEmailTag( 6294): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
I/HwLauncher( 3674): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3674): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3674): Model shortcutInfo.title = SIM Toolkit
I/HwCust  ( 6294): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
I/HwLauncher( 3674): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3674): Launcher.Folder childCount: 5
I/HwLauncher( 3674): Launcher.Folder childCount: 5
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 6
I/HwLauncher( 3674): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwCust  ( 6294): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
I/HwEmailTag( 6294): EmailApplication->onCreate->end, consuming 12ms->-prefixstartupperformance-
I/HwLauncher( 3674): Launcher.Folder childCount: 6
I/HwLauncher( 3674): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3674):  syncPages mCurrentPage = 0
I/HwEmailTag( 6294): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 32ms.
E/HideAppsPagedView( 3674):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3674):  createAddIcon count = 0
I/HwLauncher( 3674):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/HwEmailTag( 6294): HwUtils->initStaticVarsAsync->run:consuming:24ms; bidiFormatter:android.support.v4.text.BidiFormatter@1873f856;accountsProjSize:42
I/HwLauncher( 3674): Launcher Deferring update until onResume
I/HwEmailTag( 6294): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/HwEmailTag( 6294): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6294): EmailProvider->initBuildCache->start->1450189306851->-prefixstartupperformance-
,I/HwEmailTag( 6294): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 6294): EmailProvider->initBuildCache->start->1450189306851; consuming:1->-prefixstartupperformance-
,I/HwEmailTag( 6294): EmailProvider->resetVisibleLimits->getDatabase, consuming:88ms;-prefixstartupperformance-
I/HwEmailTag( 6294): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 6294): EmailProvider->uiAccounts->start:1450189306853
,I/HwEmailTag( 6294): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6294): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 11ms.
,I/HwEmailTag( 6294): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6294): EmailProvider->resetVisibleLimits->getDatabase, consuming:107ms;-prefixstartupperformance-
I/HwEmailTag( 6294): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 6294): EmailProvider->uiAccounts->start:1450189306853;end,consuming:38
I/HwEmailTag( 6294): EmailProvider->query->1450189306781;end;;consuming:111ms;
,W/art     ( 6210): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6210): onDetachedFromWindow called when already detached. Ignoring
,I/art     ( 6210): Can not find class: Landroid/widget/ViewStub;
,I/art     ( 6210): Can not find class: Landroid/webkit/ViewStub;
,I/art     ( 6210): Can not find class: Landroid/app/ViewStub;
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 3831): HoldService:uid:10065 pid:5467 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10065,5467
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10065, pid: 5467
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10065, pid: 5467
,W/art     ( 6210): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6210): Attempt to remove local handle scope entry from IRT, ignoring
,W/StubController( 6162): calendar access!
,I/ActivityManager( 2992): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
I/PG Utils( 6162): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6343): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
,W/HWContacts( 6343): ProviderFeatureChcker - cootek package not installed
,E/TmoMonitor( 6343): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@1873f856
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GAV2    ( 5801): Thread[GAThread,5,main]: No campaign data found.
I/GAv4-SVC( 5727): Google Analytics 8.4.89 is starting up.
,I/HwCust  ( 6343): Constructor found for class com.android.mms.data.HwCustConversationImpl
,I/CalendarProvider2( 6186): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6186): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 2992): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/EmuiFeatureManager( 6343): loadEmailAnrSupportFlag:true
,I/Mms_threadcache( 6343): [RecipientIdCache] fill: begin
,E/MmsConfig( 6343): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
,I/OpenGLRenderer( 6210): Initialized EGL, version 1.4
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 1050
,I/HwSystemManager( 3831): HoldService:uid:1050 pid:5493 died
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/HwSystemManager( 3831): HoldService:oldVersionKey:1050,5493
W/MediaProcessHandler( 2992): processOp uid 1050 is not concerned!
,I/art     ( 2992): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
I/ActivityManager( 2992): Displayed com.example.hello/.MainActivity: +1s496ms
,I/SimFactoryManager( 6343): Inside init method of SimFactoryManger the combination is:-1
I/HwCust  ( 6343): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
,E/CSP_RADAR( 6343): Message execute too long time.{ when=-148ms what=1 target=com.huawei.mms.util.HwBackgroundLoader$3 }
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6343): isSIM1CardPresent:1
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:0
,I/HwCust  ( 6343): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 6343): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6343): isSIM2CardPresent:1
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6343): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/HwCust  ( 6343): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
,I/HwCust  ( 6343): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
,I/art     ( 6343): Can not find class: Lhuawei/android/view/TableLayout;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/TableLayout;
,I/art     ( 6343): Can not find class: Lhuawei/android/view/View;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/View;
,I/art     ( 6343): Can not find class: Landroid/widget/View;
I/art     ( 6343): Can not find class: Landroid/webkit/View;
,I/art     ( 6343): Can not find class: Landroid/app/View;
,I/art     ( 6343): Can not find class: Lhuawei/android/view/TableRow;
,I/art     ( 2992): Can not find class: Lcom/android/server/wm/DisplayContentList;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/TableRow;
,I/art     ( 6343): Can not find class: Lhuawei/android/view/LinearLayout;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/LinearLayout;
,I/chromium( 6210): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6210): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     ( 6343): Can not find class: Lhuawei/android/view/ImageButton;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/ImageButton;
,I/art     ( 6343): Can not find class: Lhuawei/android/view/TextView;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/TextView;
,I/art     ( 6343): Can not find class: Lhuawei/android/view/RelativeLayout;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/RelativeLayout;
,I/art     ( 6343): Can not find class: Lhuawei/android/view/ImageView;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/ImageView;
,I/art     ( 6343): Can not find class: Lhuawei/android/view/ViewStub;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/ViewStub;
,I/art     ( 6343): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6343): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6343): Can not find class: Landroid/app/ViewStub;
,I/chromium( 6210): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6210): 
,I/art     ( 6343): Can not find class: Lhuawei/android/view/FrameLayout;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/FrameLayout;
,I/art     ( 6343): Can not find class: Lhuawei/android/view/EditText;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/EditText;
,E/textview( 6343): initAddtionalStyle default
,I/art     ( 6343): Can not find class: Lhuawei/android/view/ProgressBar;
,I/art     ( 6343): Can not find class: Lhuawei/android/widget/ProgressBar;
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 6343): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,W/jxcore-log( 6210): Initializing JXcore engine
W/jxcore-log( 6210): JXcore engine is ready
,W/jxcore-log( 6210): Starting JXcore engine
,W/jxcore-log( 6210): Platform android
W/jxcore-log( 6210): 
W/jxcore-log( 6210): Process ARCH arm
W/jxcore-log( 6210): 
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10090
I/HwSystemManager( 3831): HoldService:uid:10090 pid:5535 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10090,5535
,E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10090, pid: 5535
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10090, pid: 5535
,I/jxcore-log( 6210): JXcore Cordova bridge is ready!
I/jxcore-log( 6210): 
,W/jxcore-log( 6210): JXcore engine is started
,E/jxcore-log( 6210): >> HUAWEI-ALE-L21
E/jxcore-log( 6210): 
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10001
I/HwSystemManager( 3831): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3831): HoldService:uid:10001 pid:4848 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10001,4848
I/HwSystemManager( 3831): NotificationManagerReceiver:onReceive, send action to background
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10001, pid: 4848
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10001, pid: 4848
,I/HwSystemManager( 3831): ProcPolicy:begin get procName.
,I/jxcore-log( 6210): Total memory 1949741056
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Free memory 32358400
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6210): 
I/jxcore-log( 6210): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6210): 
,I/HwSystemManager( 3831): ProcPolicy:this proc is:com.huawei.systemmanager:service
I/HwSystemManager( 3831): ProcPolicy:end get procName.
,I/jxcore-log( 6210): userPath [ 'www' ]
I/jxcore-log( 6210): 
,I/HwSystemManager( 3831): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@3749d0b4
,I/jxcore-log( 6210): Size 720 1184
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): Screen Brightness 242
I/jxcore-log( 6210): 
,E/jxcore-log( 6210): Dummy Error Log.
E/jxcore-log( 6210): 
,I/HwSystemManager( 3831): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3831): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3831): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings],
I/HwSystemManager( 3831): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
,I/HwSystemManager( 3831): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
,I/HwSystemManager( 3831): NmCenterDefValueXmlHelper:getConfigs: Starts
,I/HwSystemManager( 3831): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33,
,I/HwSystemManager( 3831): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
,I/HwSystemManager( 3831): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg,
I/HwSystemManager( 3831): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 3831): NotificationDBProvider:call: method = notification_list_query,
,I/HwSystemManager( 3831): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3831): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 3831): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3831): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3831): NotificationDBProvider:query starts, matchCode = 1
,I/PhoneStatusBar( 3233): notification pkg =com.android.settings
,I/PhoneStatusBar( 3233): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3233): notification pkg =android
I/PhoneStatusBar( 3233): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,I/HwSystemManager( 3831): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 3831): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3831): HsmIntentService:last work complete! lets stop service.
,W/asset   ( 6451): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwSystemManager( 3831): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@3749d0b4
,I/HwSystemManager( 6451): SystemManagerApplication:onCreate
,I/HwSystemManager( 3831): MainService:on startCommand,flags:0,startId:6
,I/System.out( 6451): [ls, -l, /system/app/HwSystemManager/HwSystemManager.apk]
I/System.out( 6451): null
I/System.out( 6451): null
I/System.out( 6451): Calling by::className:bkk  MethodName:yw
,I/HwSystemManager( 3831): LocalService:Received start id 6: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
,I/HwSystemManager( 3831): BgPowerManagerService:onStartCommand
,I/HwSystemManager( 3831): AppLockService:onStartCommand
,I/HwSystemManager( 6451): check push opration, match idx:-1
,I/HwSystemManager( 3831): AppCleanUpService:onStartCommand() in!
,I/HwSystemManager( 6451): HsmStat_info:feature enable:false
,I/HwSystemManager( 6451): ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello]
,I/HwSystemManager( 6451): OverseaCfgHelper:permissionStatus is 0
,I/HwSystemManager( 6451): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6451): ProcPolicy:begin get procName.
,I/HwSystemManager( 6451): ProcPolicy:this proc is:com.huawei.systemmanager
I/HwSystemManager( 6451): ProcPolicy:end get procName.
,I/HwSystemManager( 6451): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,I/YhdsEngine( 6451): [EngineIntentService] Received: com.huawei.dianxinos.optimizer.engine.action.APP_START
I/HwSystemManager( 6451): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 6451): SimCardManager:getOperatorNameFromService mNameServSlot0 = null
I/HwSystemManager( 6451): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
I/HwSystemManager( 6451): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 6451): SimCardManager:getOperatorNameFromService mNameServSlot1 = null
I/HwSystemManager( 6451): SimCardManager:/onReceive: action =android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 6451): SimCardManager:action:android.provider.Telephony.SPN_STRINGS_UPDATED
,I/HwSystemManager( 6451): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@313cadc4
,I/HwSystemManager( 6451): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,I/HwSystemManager( 6451): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,I/HwSystemManager( 6451): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,I/YhdsEngine( 6451): [AlarmEventMgr] event scheduled: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
,I/HwSystemManager( 6451): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
,I/HwSystemManager( 6451): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6451): OverseaCfgHelper:permissionStatus is 0
,I/HwSystemManager( 3831): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 3831): AppCleanUpService:onStartCommand() out!
E/HwSystemManager( 3831): AppCleanUpService:msg is 0
I/HwCust  ( 6451): Constructor found for class com.huawei.systemmanager.optimize.process.HwCustProtectAppControlImpl
,I/YhdsEngine( 6451): [EngineIntentService] Received: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
,I/HwSystemManager( 6451): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,I/HwSystemManager( 6451): HsmPackageManager:begin to scan apks.
I/HwSystemManager( 6451): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,W/HwSystemManager( 6451): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6451): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6451): HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:3, queue size:0
I/HwSystemManager( 6451): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6451): anf:packageCanAccessInternet com.example.hellohas INTERNET permission
,I/HwSystemManager( 6451): anf:packageCanAccessInternet component enable
,I/HwSystemManager( 6451): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6451): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6451): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6451): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6451): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule, DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6451): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6451): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], applock=[Rule AppLockNotMonitorListRule post: match[0], mismatch[2], Rule HomeCategoryRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6451): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello, replacing: false
I/YhdsEngine( 6451): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
I/HwSystemManager( 6451): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
I/HwSystemManager( 6451): XmlRuleBase:parseAndCacheList permission_black_list_match :[]
I/HwSystemManager( 6451): XmlRuleBase:parseAndCacheList black_match :[]
I/HwSystemManager( 6451): XmlRuleBase:parseAndCacheList permission_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 6451): AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6451): XmlRuleBase:parseAndCacheList white_match :[com.baidu.map.location, com.cootek.smartdialer_oem_module, com.sohu.inputmethod.sogou.huawei, com.huawei.hisuite, com.nuance.swype.emui, com.huawei.remoteassistant, com.iflytek.speechcloud, com.huawei.phoneservice, com.huawei.phonediagnose, com.nqmobile.antivirus20.hw, com.baidu.input_huawei]
I/HwSystemManager( 6451): XmlRuleBase:parseAndCacheList dropzone_black_list_match :[]
I/HwSystemManager( 6451): XmlRuleBase:parseAndCacheList dropzone_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 6451): HsmPackageManager:end to scan apks. size:150 + 0
,I/HwSystemManager( 6451): HsmPackageManager:init locale:en_US
I/HwSystemManager( 6451): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6451): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:2, queue size:0
I/HwSystemManager( 6451): ProtectAppControl:handleMessage:6
I/HwSystemManager( 6451): ProtectAppControl:begin install app inner:com.example.hello
I/HwSystemManager( 6451): AppManager:insert to db: name = com.example.hello uid = 10302 app type = false
W/HwSystemManager( 6451): AddViewAppManager:Current installed app not apply system_alert_window or applicationInfo null!
I/HwSystemManager( 6451): PermissionDBAdapter:DBAdapter created!
I/HwSystemManager( 6451): PermissionDbHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/permission.db
I/HwSystemManager( 6451): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6451): PermissionDBAdapter:appcationsList size:150
,W/HwSystemManager( 6451): ProtectAppControl:com.example.hello already exist!
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 198us total 23.643ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 212us total 24.607ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 192us total 25.477ms
,I/jxcore-log( 6210): getBuffer is called!!!!
I/jxcore-log( 6210): 
,I/HwSystemManager( 6451): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 6451): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6451): PermissionDBAdapter:appcationsList size:150
,I/HwEmailTag( 6294): EmailProvider->query->1450189308767;end;;consuming:2ms;
,I/HwSystemManager( 6451): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 6451): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6451): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6451): HsmIntentService:last work complete! lets stop service.
,I/HwEmailTag( 6294): EmailApplication->handleMessage->startService CleanRecipientAddressService
,I/art     ( 2992): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/HwEmailTag( 6294): Device->updateDeviceIdIfNeeded
,I/HwEmailTag( 6294): CleanRecipient->onCreate
,I/HwEmailTag( 6294): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 6294): Device->getDeviceId->
,I/HwEmailTag( 6294): Device->getDeviceIdInternal->isUpdate:false
,I/HwEmailTag( 6294): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 6294): CleanRecipient->onStartCommand->action is null
I/HwEmailTag( 6294): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
I/HwEmailTag( 6294): CleanRecipient->onHandleIntent->action is null
,I/HwEmailTag( 6294): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 6294): CleanRecipient->onDestroy
,I/HwSystemManager( 6451): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@313cadc4
,I/HwEmailTag( 6294): AccountReconciler->reconcileAccountsInternal->consuming:91ms
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10092
I/HwSystemManager( 3831): HoldService:uid:10092 pid:5567 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10092,5567
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10092, pid: 5567
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10092, pid: 5567
,I/HwCust  ( 6544): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 6544): EmailContent->init->consuming:19ms->;-prefixstartupperformance-
,I/HwEmailTag( 6544): Exchange->onCreate
,I/GAv4    ( 6507): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6507):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6507):   adb logcat -s GAv4
,W/GAv4    ( 6507): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6507): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6507): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6507): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.44
,I/art     ( 2992): Explicit concurrent mark sweep GC freed 13339(682KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.774ms total 170.975ms
,I/PG Utils( 6544): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6544): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 6294): EmailProvider->query->1450189309212;end;;consuming:1ms;
,I/HwEmailTag( 6544): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,W/ContextImpl( 6507): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10095
I/HwSystemManager( 3831): HoldService:uid:10095 pid:5589 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10095,5589
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10095, pid: 5589
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10095, pid: 5589
,I/ContactsAppilcation( 6343): intent:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,I/CommonUtilMethods( 6343): action:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6343): intent:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
,I/CommonUtilMethods( 6343): action:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
I/ContactsAppilcation( 6343): intent:android.provider.Telephony.SPN_STRINGS_UPDATED
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10058
I/HwSystemManager( 3831): HoldService:uid:10058 pid:5611 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10058,5611
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10058, pid: 5611
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10058, pid: 5611
,I/art     ( 6507): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6507): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6507): Installed default security provider GmsCore_OpenSSL
,I/art     ( 2992): Can not find class: Lcom/android/server/accounts/AccountManagerService$TestFeaturesSession;
,I/HwSystemManager( 6451): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 6451): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 12
I/HwSystemManager( 6451): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/PG Utils( 6583): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 6451): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/HwSystemManager( 6451): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 12
I/HwSystemManager( 6451): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/PG Utils( 6583): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6583): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/UpdateIcingCorporaServi( 5980): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/GmsModuleInitializer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/app/GmsApplicationContext;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue;
,I/art     ( 5727): Can not find class: Lcom/google/android/flib/pref/PreferenceFile;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/PlatformVersion;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils$1;
,I/art     ( 5727): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/Asserts;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReaderImpl;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReader;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/receiver/PlaySystemBroadcastReceiver;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/UserAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/GamesSyncAdapter;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/sync/BaseGmsSyncAdapter;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/config/G;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesLog;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/VersionUtils;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/GamesSharedPrefs;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$AsyncOperationQueue;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/Preconditions;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/AsyncOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$OperationTask;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService$PooledAsyncOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/WrappedGamesCallbacks;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/quests/AcceptQuestOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractDataHolderOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$Operation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/requests/AcceptRequestOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/AcceptTurnBasedMatchInvitationOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/AcknowledgeNotificationsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/AddNearbyPlayerOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractStatusReportingOperation;
I/UpdateIcingCorporaServi( 5980): UpdateCorporaTask done [took 116 ms] updated apps [took 116 ms] 
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CancelTurnBasedMatchOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/quests/ClaimMilestoneOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/ClearDataOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/ClearNotificationsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/events/ClearPendingEventsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/ApiClientTracker;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveContents;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/CommitSnapshotOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomEnteredCallback;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/ConnectionInfo;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/safeparcel/SafeParcelable;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/CreateRoomOperation;
,I/HwSystemManager( 6451): HsmStat_info:service connect
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CreateTurnBasedMatchOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DeclineInvitationOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/DeleteSnapshotOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DismissInvitationOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/DismissTurnBasedMatchOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/DismissPlayerSuggestionOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/requests/DismissRequestOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/multiplayer/ParticipantResult;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/FinishTurnBasedMatchOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/GetGamesAuthTokenOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/GetGamesServerAuthCodeOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/GetInboxActivityCountsOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/GetScoreOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$GamesThreadFactory;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/GetTurnBasedMatchOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/AccountsChangedOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/PackageModifiedOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/PeopleChangedOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/PopupManager$PopupLocationInfo;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/IncrementAchievementOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/events/EventIncrementEntry;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/events/IncrementEventsOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/InitializeGamesOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/InvalidateAppContentOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/IsGameMutedOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/JoinRoomOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/video/VideoConfiguration;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/video/LaunchGameForRecordingOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/client/IPlayGamesCallbacks;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/ClientContext;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomLeftCallback;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveDiagnostics;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/response/FastMapJsonResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/response/FastJsonResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/LeaveRoomOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LeaveTurnBasedMatchOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/video/ListVideosOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsInternalOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AppContentContext;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/LoadAppContentOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractMultiDataHolderOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadCircledPlayersOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameCollectionComparisonOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadConnectedPlayersOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/LoadContactSettingsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsByIdOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/LoadExperimentsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadFirstPartyPlayersOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameFirstPartyOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameInstancesOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameSearchSuggestionsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGamesCollectionOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadInvitablePlayersOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/LoadInvitationsOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadLeaderboardsOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadMoreScoresOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpStreamOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/acls/LoadNotifyAclOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadPlayGamesRecentlyPlayedOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayerOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadScoresOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/stats/LoadPlayerStatsOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersInternalOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadProfileSettingsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/quests/LoadQuestsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestSummariesOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestsOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/LoadSnapshotsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LoadTurnBasedMatchesOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpForGameCategoriesOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/NotificationOpenedOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/OpenLatencyLoggingSessionOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/RecordApplicationSessionOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/RecordPlayerSuggestionActionOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/RematchTurnBasedMatchOperation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$P2pStatusReportCallback;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/ReportP2pStatusOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/ResolveSnapshotConflictOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/UpdateAchievementOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/SearchForGamesOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/SearchForPlayersOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/requests/SendRequestOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/SetAchievementStepsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/SetGameMuteStatusOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/SetIdentitySharingConfirmedOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/quests/QuestStateChangedPopupOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/SignOutOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/GamesUtils;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/GamesOperationAdapter;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/AndroidUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/video/StopRecordingOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/SubmitScoreOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/UpdateContactSettingsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/acls/UpdateNotifyAclOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/games/UpdatePlayedOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/players/UpdateProfileSettingsOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/UpdateTurnBasedMatchOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/IGmsCallbacks;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/GetServiceRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/ValidatePlayServiceConnectionOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/ValidateServiceConnectionOperation;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/VerifySnapshotFolderOperation;
,E/Thermal-daemon( 2331): [ap] temp_new :33  temp_old :32
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$2;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/ExperimentUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/ExperimentUtils$Experiment;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/AccountUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/LatencyLoggingSessions;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/logging/LatencyLogger;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/DataBroker;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/Lockable;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/service/OperationException;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/auth/GoogleAuthException;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/Lockable$LockableLock;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/GamesServer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/AbstractServer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/auth/appcert/AppCertServiceClient;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/auth/AuthSessionAuthenticator;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/error/ErrorUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/auth/GoogleAuthUtil;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer$DefaultApiaryRetryPolicy;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$1;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$Batch;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/response/FieldMappingDictionary;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/ApiaryRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/VolleyInterruptedError;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/NoResponseRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/ImageRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/GamesRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GamesExperiments;
I/art     ( 5727): Can not find class: Lcom/google/android/play/experiments/PlayExperiments;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/Base64Utils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/config/GamesOptions;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/error/ErrorInstanceResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/error/GamesException$Builder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/error/GamesException;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$6;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$1;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$3;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$4;
,I/art     ( 5727): Can not find class: Lcom/google/android/gsf/Gservices;
,I/art     ( 5727): Can not find class: Lcom/google/android/gsf/Gservices$1;
,I/art     ( 5727): Can not find class: Lcom/google/android/gsf/Gservices$1$1;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Icing   ( 5727): Storage manager: low false usage 1.77MB avail 8.40GB capacity 10.40GB
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/GamesServerFactory;
,I/AccountTypeManager( 6343): Adding account type = com.android.contacts.model.account.ExchangeAccountType@20c5596f in the cache
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:0
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:1
,W/BaseAppContext( 5727): Using Auth Proxy for data requests.
,W/BaseAppContext( 5727): Using Auth Proxy for data requests.
I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/server/PlusServer;
,I/HwCust  ( 6343): Constructor found for class com.android.contacts.model.account.HwCustAccountModelCustomizationImpl
I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/config/G;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/SpamAndAbuseHeaders;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/server/ContainerParam;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/auth/AuthTokenTimeCache;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/server/SocialClient;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/AccountTypeManager( 6343): Adding account type = com.android.contacts.model.account.ExternalAccountType@32d88b05 in the cache
,W/BaseAppContext( 5727): Using Auth Proxy for data requests.
,W/BaseAppContext( 5727): Using Auth Proxy for data requests.
,I/art     ( 5634): Explicit concurrent mark sweep GC freed 2747(107KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 13MB/17MB, paused 445us total 30.380ms
,W/BaseAppContext( 5727): Using Auth Proxy for data requests.
W/BaseAppContext( 5727): Using Auth Proxy for data requests.
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryServer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/utils/Log;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryRequest;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/G;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$5;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/ResourceType( 6343): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6343): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
,W/ResourceType( 6343): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6343): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6343): Adding account type = com.android.contacts.model.account.ExternalAccountType@35781d8b in the cache
,I/AccountTypeManager( 6343): Adding account type = com.android.contacts.model.account.GoogleAccountType@1a71e68 in the cache
,W/BaseAppContext( 5727): Using Auth Proxy for data requests.
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/TransientCacheOwner;
E/ExternalAccountType( 6343): Unsupported attribute readOnly
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/InboxCounter;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$Builder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$DataType;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/utils/GamesDataUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/DefaultClock;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/Clock;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/BaseApi;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApiInternal;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/AchievementCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/Agents$QueryBuilder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementDefinitions;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementDefinitionsColumns;
,I/AccountTypeManager( 6343): AccountManager, account size is: 2
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/DataHolder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/DataHolder$Builder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Players;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayersColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$1;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementFlushData;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleRequest;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/ApiRateLimitUtil;
I/AccountTypeManager( 6343): Loaded meta-data for 5 account types, 3 accounts in 188ms(wall) 64ms(cpu)
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/error/ErrorResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementInstances;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementInstancesColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/provider/QuerySpec;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/achievement/AchievementBuffer;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/AbstractDataBuffer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/DataBuffer;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/Releasable;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/achievement/Achievement;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/Freezable;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/Agents;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$TypeQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementStepData;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$IncrementQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/popup/AchievementPopup;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/popup/BasePopup;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/PlayGamesUploadService;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/GcmTaskService;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinition;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/response/FastContentValuesJsonResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievement;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/GamePlayerCacheKey;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementPendingOps;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementPendingOpsColumns;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$PendingOpsQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/constants/AchievementState;
,I/art     ( 5727): Can not find class: Landroid/support/v4/util/ArrayMap;
,I/art     ( 5727): Can not find class: Landroid/support/v4/util/SimpleArrayMap;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementSetStepsAtLeast;,
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateRequest;
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementIncrement;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementUpdateResult;
I/PeopleDatabaseHelper( 5727): cleanUpNonGplusAccounts done.
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementIncrementResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsListResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationFetchList;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementGetMultipleResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementListResponse;
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementSetStepsAtLeastResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUnlockResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AchievementRevealResponse;
,I/art     ( 5727): Can not find class: Landroid/support/v4/util/ContainerHelpers;
,I/art     ( 5727): Can not find class: Landroid/support/v4/util/ArrayMap$1;
,I/art     ( 5727): Can not find class: Landroid/support/v4/util/MapCollections;
I/art     ( 5727): Can not find class: Landroid/support/v4/util/MapCollections$KeySet;
,I/art     ( 5727): Can not find class: Landroid/support/v4/util/MapCollections$ArrayIterator;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache$OwnerCache;
,I/art     ( 5727): Can not find class: Landroid/support/v4/util/LruCache;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/BaseGmsContentProvider;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/Objects;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$UriType;
,I/art     ( 5727): Can not find class: Lcom/android/common/content/ProjectionMap;
,I/art     ( 5727): Can not find class: Lcom/android/common/content/ProjectionMap$Builder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/provider/TableJoiner;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerLevels;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerLevelColumns;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerStats;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerStatsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ClientContexts;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ClientContextsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestPendingOps;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestPendingOpsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ApplicationSessions;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ApplicationSessionColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AppContents;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AppContentColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Images;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ImagesColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardPendingScores;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Requests;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Matches;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchesPendingOps;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesPendingOpsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesDataStore;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleter;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesDatabaseHelper;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/utils/UriUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$ImageCleaner;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$3;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/ImageStore;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/ImageStore$Entry;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$GamesProjectionMapBuilder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameInstances;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameInstancesColumns;
,E/Icing   ( 5727): Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventInstances;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventInstancesColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventPendingOps;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventPendingOpsColumns;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ExperienceEvents;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ExperienceEventColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Invitations;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$InvitationsColumns;
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Participants;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ParticipantsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardInstances;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardInstancesColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardScores;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardScoresColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Notifications;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$NotificationsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Milestones;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MilestoneColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestRecipients;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestRecipientsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Snapshots;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$SnapshotColumns;
,I/art     ( 5727): Can not find class: Lcom/android/common/SharedPreferencesCompat;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Games;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GamesColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventDefinitions;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventDefinitionColumns;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Leaderboards;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/constants/OfflineMatchAction;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Quests;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$QuestsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$1;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleterAssociatedQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$2;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/Joiner;
,I/MusicStore( 6630): Database version: 120
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AppContentsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/AppContentSectionAndCardCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/AppContentBaseCache;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/AppContentActionCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/AppContentAnnotationCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/AppContentConditionCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/AppContentTupleCache;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$CardImageInsertHelper;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ContentEntry;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Section;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Card;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/CardAnnotation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ImageAsset;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/CardCondition;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/CardAction;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/response/FastParser$ParseException;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/GamesCardScreenFirstPartyResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$ServerCookieQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/constants/DeviceType;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/EventAgent;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/EventResolver;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventsApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$WindowInfo;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodRange;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodUpdate;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$PendingOpsQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$EventDefinitionRefreshInfo;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinition;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinitionListResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$UnresolvedException;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEvent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEventListResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventRecordRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext$Builder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApiInternal;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/GameCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/GameSearchCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/BaseSearchCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCache;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplication;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Application;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/MarketApplication;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/MarketBadge;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ImageConfig;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/converter/ImageUrlBuilder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/MarketInstance;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameBadges;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameBadgesColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Instance;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/InstanceAndroidDetails;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/PackageUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Snapshot;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/PanoUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationCategory;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/GameBuffer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/Game;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationList;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchContext;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchList;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetUpdatesMultipleFirstPartyResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsFlushData;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/SessionBatch;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetMultipleFirstPartyResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$FirstPartyGameListProcessor;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationListFirstPartyResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$GameRefreshRecord;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/TransientDataHolder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$VersionQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplicationUpdates;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/constants/AppUpdateType;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/ArrayUtils;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/InvalidId;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCacheKey;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$StoreGamesProcessor;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameSearchSuggestions;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameSearchSuggestionsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestion;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/DataUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationSearchFirstPartyResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Session;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$InstanceQuery;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApiInternal;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/LeaderboardScoreCache;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Leaderboard;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScores;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardEntry;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Player;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/constants/LeaderboardCollection;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/constants/TimeSpan;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PageTokensQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheKey;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheOwner;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PendingScoreQuery;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/provider/SelectionArgs;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ScoreSubmission;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreSubmissionList;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreListResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListFirstPartyResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScoreListResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScore;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScoreRank;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader$Builder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GamesDroidGuard;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScore;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData$Result;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6630): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/NotificationAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/PlayCommonAgent;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/NonListener;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApiInternal;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleApi;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/PeopleApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/MetagameApiInternal;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ExperiencesApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/PlayerCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/PlayerSearchCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/ContactSettingsCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/ProfileSettingsCache;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/cache/XpEventStreamCache;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/PlayerBuffer;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/Player;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$CircledStateQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p$Builder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient$Builder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/People;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/Api;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions$HasOptions;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/ConnectionResult;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyPlayer;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Played;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListFirstPartyResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$PeopleNetworkData;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/PlayerLevel;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Experience;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PeopleFeed;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/response/FastSafeParcelableJsonResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person$Image;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleFeed;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/model/people/Person;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/model/people/Person$Image;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$TrimExperiencesQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ProfileSettings;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleOptions;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/internal/PeopleUtils;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/Graph;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/PendingResult;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/Result;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleResult;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/People$ReleasableResult;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/Status;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/model/PersonBuffer;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/model/DataBufferWithSyncInfo;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/people/model/Person;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/logging/GamesPlayLogger;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/data/GamesDataChangeUris;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity$ImageEntity;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/images/ImageBroker;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$LevelQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/GamesStatusCodes;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ContactSettings;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ContactChannelSetting;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/constants/NotificationChannel;
,W/ContextImpl( 6630): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceListResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/CategoryListResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Category;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/MetagameConfig;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLevel;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceSyncFirstPartyResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$SyncNetworkResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AccountMetadata;
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataApiInternal;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestonesApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Quest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestone;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestCriterion;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestContribution;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/quest/QuestBuffer;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/EntityBuffer;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/quest/Quest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$QuestsEntities;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/GameEventListenerRegistry;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/popup/QuestPopup;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$SyncNetworkResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$NotifyDataHolder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$MilestoneClaimedQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestListFirstPartyResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestListResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataSyncFirstPartyResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/QuestSyncFirstPartyResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/RevisionAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RevisionsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyRevisionCheckResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AclAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AclsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMember;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingRoster;
I/art     ( 5727): Can not find class: Lcom/google/protobuf/micro/MessageMicro;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingTargetId;
,I/art     ( 5727): Can not find class: Lcom/google/protobuf/micro/InvalidProtocolBufferMicroException;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Acl;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMemberConversions;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Acls;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AclsColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/AclUpdateRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestSummaryColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RequestsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/OutboundRequestInfo;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RequestRecipient;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestEntities;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/request/GameRequestBuffer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/request/GameRequest;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$RequestSummariesData;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/PlayerRef;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/DataBufferRef;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/GameRef;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateList;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdate;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$SyncNetworkResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RequestEntity;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Request;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyNotification;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/InboundRequestInfo;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$TrimRequestsQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$PendingOpsQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/SendRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/constants/RequestType;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RequestSyncResponseFirstParty;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes$Builder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResultList;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResult;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApi;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApiInternal;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/service/FilesApi;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/Drive;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveApi;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveApi$ResourceIdSetResult;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet$Builder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/MetadataBundle;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/MetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/CustomPropertyKey;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/data/BitmapTeleporter;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/Query;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveApi$MetadataBufferResult;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$ResultPair;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/MetadataBuffer;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/Api$ClientKey;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/Api$Client;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/GmsClient;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/GmsClientEventManager$GmsClientEventState;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/LogicalFilter;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/AbstractFilter;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/Filter;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl$6;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/internal/DriveBaseApiMethodImpl;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ApiMethodImpl;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/internal/BasePendingResult;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ResultHolder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/api/internal/GoogleApiClientImpl$Runner;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/FullTextSearchDetector;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/FilterVisitor;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/Metadata;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveId;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/mdm/DeviceManager;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi$DeviceNameResult;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$DriveIdQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveIdResult;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveFile;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveResource;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveResource$MetadataResult;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$TitleMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/StringMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/BaseMetadataField;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/SortableMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$ModifiedMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/DateMetadataField;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/OrderedMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableOrderedMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$MimeTypeMetadataField;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/internal/model/File;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/postprocessor/PostProcessorHelper;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveContentsResult;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation$SnapshotOpenData;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties$Builder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/Agents$TwoColumnMapper;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange$Builder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/service/PlaySnapshotEventService;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/chimera/DriveEventService;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions$Builder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/ImageUtils;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveFolder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/internal/DriveFolderImpl;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/internal/DriveResourceImpl;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFolderResult;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotListResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFileResult;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/Query$Builder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/SearchableField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableCollectionMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/InFilter;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/ComparisonFilter;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/Operator;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/HasFilter;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/SortOrder$Builder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$CreatedMetadataField;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/internal/FieldWithSortOrder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/drive/query/SortOrder;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/util/IOUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/StatsAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/StatsApi;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/StatsResponse;
,W/ContextImpl( 6630): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitiesApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchEntities;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyMultiplayerEntity;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/Room;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatch;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/multiplayer/InvitationBuffer;
,W/ContextImpl( 6630): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/multiplayer/Invitation;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/multiplayer/Participatable;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/multiplayer/Participant;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$SyncNetworkResponse;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$VersionInfo;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitySyncFirstParty;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApi;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/NetworkDiagnostics;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent$RoomCache;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomJoinRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/constants/Capability;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomClientAddress;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomCreateRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomAutoMatchingCriteria;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomP2PStatuses;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/RoomStatus;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent;,
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApi;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchResults;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/MatchParticipantResult;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent$PendingOpsQuery;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/server/response/FastParser;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchTurn;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchDataRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchCreateRequest;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedAutoMatchingCriteria;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/constants/TurnBasedMatchStatus;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/multiplayer/turnbased/TurnBasedMatchBuffer;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchRematch;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController$CaptureStateCallback;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay$CaptureOverlayListener;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/youtube/server/api/LiveBroadcastsApiInternal;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/youtube/server/api/LiveStreamsApiInternal;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/VideoHandler;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/VideoUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController$8;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent$RecordingSession;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/youtube/server/api/LiveStreamListResponse;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/youtube/server/api/LiveStream;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/youtube/server/api/CdnSettings;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/youtube/server/api/IngestionInfo;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/youtube/server/api/LiveStreamSnippet;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/video/VideoConfiguration$Builder;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/instrumentation/Profiler;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/instrumentation/ProfileScope;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController$10;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent$3;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/util/VideoCapabilities;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent$2;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/popup/VideoCapturedPopup$VideoCapturedPopupClickListener;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/popup/VideoCapturedPopup;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/util/VideoEncodingProfiles;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/instrumentation/Counter;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController$7;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/CameraUtils;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/CameraPreviewController;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay$5;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/CameraPreviewController$CameraPreviewCallbacks;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay$Position;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay$6;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/ui/video/DeviceRotationListener;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$VideoColumns;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent$1;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GamesUris;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent$MetadataQuery;
,I/art     ( 6630): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6630): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2296f852: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6630): Installed default security provider GmsCore_OpenSSL
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/Agents$1;
,I/art     ( 5727): Can not find class: Lcom/google/android/gms/games/broker/Agents$2;
I/art     ( 5727): Can not find class: Lcom/google/android/gms/common/internal/ClientContextCreator;
,I/ConfigStore( 6630): Config Database version: 1
,I/art     ( 2992): Can not find class: Lcom/android/server/power/Notifier$2;
,I/KeyguardFingerprint.Validation( 3144): start
,E/AuthenticationManager( 3144): AuthenticationManager open failed: the AuthenticationService is null
W/KeyguardFingerprint.Utils( 3144): AuthenticationManager open return null
I/KeyguardFingerprint.Validation( 3144): Fingerprint unlock is not enabled
I/KeyguardViewMediator( 3144): fingerprint validation not started
,E/WifiStateMachine( 2992):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine( 2992):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine( 2992):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=true state InitialState suppState:UninitializedState
,E/WifiStateMachine( 2992):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine( 2992):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine( 2992):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine( 2992):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine( 2992):  InitialState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
E/WifiStateMachine( 2992):  DefaultState !CMD_SET_SUSPEND_OPT_ENABLED 0 0
E/WifiStateMachine( 2992):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine( 2992):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
W/audio_a2dp_hw( 2636): adev_set_parameters: WARNING: set param called even when stream out is null
,W/HwScreenOnProximityLock( 2992): releaseLock: return because sensor listener is held = false
,I/TimeManager( 3233): receiver action = android.intent.action.SCREEN_ON
,I/TimeManager( 3233): hand message 2
I/TimeManager( 3233): notify time change. size = 2
,I/TimeLayout( 3233): time = 15:21
,I/TimeLayout( 3233): updateDate date = 12/15/2015
,I/TimeLayout( 3233): weekDay = Tuesday
,E/WifiStateMachine( 2992):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 2992):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine( 2992):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=true state InitialState suppState:UninitializedState
,E/WifiStateMachine( 2992): setScanAlarm false period 10000 initial delay 0
E/WifiStateMachine( 2992):  InitialState CMD_ENABLE_RSSI_POLL 0 0
,E/WifiStateMachine( 2992):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
,E/WifiStateMachine( 2992):  InitialState CMD_SET_SUSPEND_OPT_ENABLED 1 0
E/WifiStateMachine( 2992):  DefaultState CMD_SET_SUSPEND_OPT_ENABLED 1 0
,W/audio_a2dp_hw( 2636): adev_set_parameters: WARNING: set param called even when stream out is null
,I/HwLauncher( 3674): Launcher receiver screen off broadcast sendmessage true
,I/TimeManager( 3233): receiver action = android.intent.action.SCREEN_OFF
I/TimeManager( 3233): hand message 3
,I/HwSystemManager( 3831): BgPowerManagerService:MSG_SCREEN_OFF Received and mScreenOffTime :1450189311470 mScreenOffBatterylevel :2205
,I/HwSystemManager( 3831): AppLockService:BroadcastReceiver, intent is null or applock function is closed!
,I/MediaRouter( 6630): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=6, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/Icing   ( 5727): updateResources: need to parse f{com.google.android.gms}
,I/HwEmailTag( 6294): EmailProvider->query->1450189311497;end;;consuming:2ms;
,I/HwEmailTag( 6294): EmailProvider->query->1450189311501;end;;consuming:2ms;
,I/PG Utils( 2992): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6630): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GHttpClientFactory( 6630): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6630): Using platform SSLCertificateSocketFactory
,W/System.err( 2992): java.lang.SecurityException: WifiService: Neither user 10084 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2992): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2992): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2992): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2992): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2992): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2992): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2992): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiManager( 6630): WifiServiceMessenger == null
,I/PG Utils( 2992): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,W/StubController( 6162): calendar access!
,I/CalendarSimpleUiPRovider( 6162): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6162): onConfigurationChanged
I/CalendarSimpleUiPRovider( 6162): initParams20151215T152151Europe/Warsaw(2,348,3600,0,1450189311)
W/StubController( 6162): calendar access!
,I/PG Utils( 6162): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6162): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 6162): calendar access!
,I/HwEmailTag( 6294): EmailProvider->query->1450189311627;end;;consuming:47ms;
,E/SQLiteLog( 6186): (284) automatic index on view_events(_id)
,W/StubController( 6186): calendar access!
,I/PG Utils( 6630): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,E/MDM     ( 3543): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/PG Utils( 6630): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6630): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2992): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,W/GCoreFlp( 3543): No location to return for getLastLocation()
,W/FusedLocationProvider( 3543): location=null
,I/art     ( 2992): Explicit concurrent mark sweep GC freed 18384(986KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.267ms total 220.670ms
,I/HwEmailTag( 6294): EmailProvider->query->1450189311876;end;;consuming:2ms;
,I/HwEmailTag( 6294): HwUtils->triggerPeriodSync->
I/HwEmailTag( 6294): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 6294): EmailProvider->triggerPeroidSync->accountId:-1
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/StubController( 6162): calendar access!
,I/PG Utils( 6630): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5727): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/CalendarSimpleUiPRovider( 6162): loadEvent end update UI0
,I/MediaStoreImporter( 6630): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/PG Utils( 5727): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,W/IcingInternalCorpora( 5727): getNumBytesRead when not calculated.
,I/PG Utils( 6689): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10087
I/HwSystemManager( 3831): HoldService:uid:10087 pid:5667 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10087,5667
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10087, pid: 5667
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10087, pid: 5667
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Babel_SMS( 6689): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6689): MmsConfig.loadMmsSettings
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Babel_SMS( 6689): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
I/Babel_SMS( 6689): MmsConfig.loadFromDatabase
,I/Icing   ( 5727): Internal init done: storage state 0
,E/Babel_SMS( 6689): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6689): MmsConfig.loadFromResources
,E/Babel_SMS( 6689): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6689): MmsConfig.loadMmsSettings: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Icing   ( 5727): Post-init done
,I/CameraHalInterface( 2636): Found a matching camera info for ID 0
,I/CameraHalInterface( 2636): Found a matching camera info for ID 1
,W/Settings( 6689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/System.err( 2992): java.lang.SecurityException: WifiService: Neither user 10058 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2992): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2992): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2992): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2992): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2992): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2992): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2992): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiManager( 6689): WifiServiceMessenger == null
,I/Babel_Crash( 6689): startup - clean
,I/Babel   ( 6689): deleted: false for 0
,W/VideoCapabilities( 6689): Unsupported mime video/mpeg
,W/VideoCapabilities( 6689): Unsupported mime video/mpeg2
,W/VideoCapabilities( 6689): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile/level 0/0 for video/3gpp
W/VideoCapabilities( 6689): Unrecognized profile 0 for video/3gpp
,W/VideoCapabilities( 6689): Unsupported mime video/mp4
,I/VideoCapabilities( 6689): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6689): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6689): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6689): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6689): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6689): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6689): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6689): Unsupported profile 8 for video/mp4v-es
W/VideoCapabilities( 6689): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 6689): Unrecognized profile 0 for video/mp4v-es
,W/VideoCapabilities( 6689): Unsupported mime video/mpeg4
,W/VideoCapabilities( 6689): Unsupported mime video/x-flv
,W/VideoCapabilities( 6689): Unsupported mime video/vc1
,W/VideoCapabilities( 6689): Unsupported mime video/wvc1
,W/VideoCapabilities( 6689): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6689): Unsupported mime video/x-ms-wmv3
,W/VideoCapabilities( 6689): Unsupported mime video/x-pn-realvideo
,W/VideoCapabilities( 6689): Unsupported mime video/ffmpeg
,W/AudioCapabilities( 6689): Unsupported mime audio/ffmpeg
,I/VideoCapabilities( 6689): Unsupported profile 4 for video/mp4v-es
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/GCoreFlp( 3543): No location to return for getLastLocation()
W/FusedLocationProvider( 3543): location=null
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/vclib   ( 6689): onServiceConnected
,W/Babel   ( 6689): Attempted to change video mute state without an active call.
,I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5727): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2992): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/art     ( 6689): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6689): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6689): Installed default security provider GmsCore_OpenSSL
,I/HwEmailTag( 6294): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,W/StubController( 6162): calendar access!
,W/StubController( 6162): calendar access!
,I/CalendarSimpleUiPRovider( 6162): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6162): onConfigurationChanged
I/CalendarSimpleUiPRovider( 6162): initParams20151215T152152Europe/Warsaw(2,348,3600,0,1450189312)
,I/PG Utils( 6162): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 6162): calendar access!
,W/StubController( 6162): calendar access!
,I/CalendarSimpleUiPRovider( 6162): loadEvent end update UI0
,I/BluetoothAdapter( 6210): Start to disable Bluetooth!
,I/HwSystemManager( 3831): HoldService:checkBeforeShowDialog: uid:10302 pid:6210, permissionType:2097152
I/HwSystemManager( 3831): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2992): allowOpenWifi blocked:false
,I/jxcore-log( 6210): ****TEST TOOK:  5083  ms ****
I/jxcore-log( 6210): 
,I/jxcore-log( 6210): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6210): 
,I/Icing   ( 5727): Indexing 53A80AC07A6A4330682EAA68EA3C7AB28D8AFFB4 from com.google.android.gms
,I/Icing   ( 5727): Indexing done 53A80AC07A6A4330682EAA68EA3C7AB28D8AFFB4
,I/appproc ( 6747): CLASSPATH=/system/framework/pm.jar
I/appproc ( 6747): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 6747): app_process:number,5,0
,I/AndroidRuntime( 6747): readDownloadBoosterConfig: 'false'
,I/        ( 6747): power log dlsym ok
,E/android_hardware_fm.cpp( 6747): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6747): ========64bit long size = 8
E/FM_HAL  ( 6747): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 6747): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6747): 
I/fm_hisi ( 6747): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6747): 
I/fm_hisi ( 6747): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6747): 
,E/android_hardware_fm.cpp( 6747): register_android_hardware_fm_fmradio, ret is 0
,I/art     ( 2992): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/art     ( 2992): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10302
I/HwSystemManager( 3831): HoldService:uid:10302 pid:6210 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10302,6210
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10302, pid: 6210
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10302, pid: 6210
,I/ActivityManager( 2992): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2992): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/HwSystemManager( 3831): AppLockService:applock password not initial or function is closed
,I/HwLauncher( 3674): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3674): Model replacing = false package = com.example.hello
I/HwLauncher( 3674): Model  ACTION_PACKAGE_REMOVED replacing = false
I/HwLauncher( 3674): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
I/HwLauncher( 3674): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
I/HwLauncher( 3674): Model mAllAppsList.removePackage com.example.hello
I/HwLauncher( 3674): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
E/HideAppsPagedView( 3674): removeItems begin 
E/HideAppsPagedView( 3674): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3674): removeItems end 
I/HwSystemManager( 6451): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 6451): HsmPackageManager:replacing:false
I/HwSystemManager( 6451): HsmPackageManager:pkgName:com.example.hello
I/HwLauncher( 3674): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
I/HwSystemManager( 6451): HsmPackageManager:doAppRemoved, remove:com.example.hello
W/GeofencerStateMachine( 3543): Ignoring removeGeofence because network location is disabled.
W/ResourceType( 2992): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
I/HwLauncher( 3674): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3674): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3674): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3674): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3674): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,W/System.err( 3674): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 3674): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3674): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3674): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3674): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3674): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3674): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3674): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3674): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3674): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3674): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3674): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
W/System.err( 3674): java.lang.NullPointerException: null receiver
W/System.err( 3674): 	at java.lang.reflect.Field.get(Native Method)
W/System.err( 3674): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3674): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3674): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3674): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3674): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3674): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3674): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3674): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3674): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3674): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3674): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwLauncher( 3674): CellLayout rearrangeAfterRmItem isAutoAlign = false
I/HwLauncher( 3674): Launcher Deferring update until onResume
,I/HwSystemManager( 3831): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/InputReader( 2992): Reconfiguring input devices.  changes=0x00000010
,I/AccountTypeManager( 6343): Adding account type = com.android.contacts.model.account.ExchangeAccountType@17821f26 in the cache
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6343): Get SIM state from SIM factory manager: 1,For slotId:1
,I/AccountTypeManager( 6343): Adding account type = com.android.contacts.model.account.ExternalAccountType@25490767 in the cache
,W/asset   ( 2992): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,E/RegisteredServicesCache( 3609): invalidateCache set mNeedToastTableFull
,I/art     ( 5980): Explicit concurrent mark sweep GC freed 10122(899KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 1.393ms total 80.298ms
,W/System.err( 2992): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/ResourceType( 6343): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
,W/ResourceType( 6343): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6343): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6343): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
,I/AccountTypeManager( 6343): Adding account type = com.android.contacts.model.account.ExternalAccountType@a7215bd in the cache
W/System.err( 2992): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 2992): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 2992): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 2992): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2992): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2992): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/AccountTypeManager( 6343): Adding account type = com.android.contacts.model.account.GoogleAccountType@26107b2 in the cache
,E/ExternalAccountType( 6343): Unsupported attribute readOnly
,I/AccountTypeManager( 6343): AccountManager, account size is: 2
,I/AccountTypeManager( 6343): Loaded meta-data for 5 account types, 3 accounts in 86ms(wall) 33ms(cpu)
,I/art     ( 3831): Explicit concurrent mark sweep GC freed 93243(6MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 14MB/23MB, paused 2.284ms total 126.893ms
I/HwSystemManager( 3831): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/HwSystemManager( 3831): HsmPackageManager:replacing:false
I/HwSystemManager( 3831): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 3831): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwSystemManager( 3831): ww:deleteLockData:com.example.hello
,I/HwLauncher( 3674): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,I/art     ( 2992): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,I/art     ( 2992): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
I/art     ( 2992): Can not find class: Lhuawei/com/android/server/util/ReportTool;
,I/art     ( 2992): Can not find class: Lcom/huawei/report/ReporterInterface;
E/ReportTools( 2992): Can't find sReporterClazz
,I/art     ( 2992): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/art     ( 2992): Can not find class: Lhuawei/com/android/server/util/AppInfo;
,W/System.err( 2992): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 2992): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2992): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2992): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2992): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2992): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 2992): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 2992): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 2992): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 2992): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 2992): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 2992): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2992): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2992): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 2992): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 2992): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2992): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2992): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 2992): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 2992): This is not beta user build
I/HwLauncher( 3674): Launcher onStart()
I/HwLauncher( 3674): Launcher dynamicIconsRegister
I/HwLauncher( 3674): DynamicUpdater registerReceiver
,I/HwLauncher( 3674): DynamicUpdater call updateFolder
I/HwLauncher( 3674): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3674): DynamicUpdater registerReceiver
,I/HwLauncher( 3674): DynamicUpdater call updateFolder
I/HwLauncher( 3674): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3674): DynamicUpdater registerReceiver
,I/HwLauncher( 3674): DynamicUpdater call updateFolder
I/HwLauncher( 3674): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
I/HwLauncher( 3674): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3674): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
E/HideAppsPagedView( 3674): removeHideApps  begin 
E/HideAppsPagedView( 3674): removeHideApps  end 
E/HideAppsPagedView( 3674):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3674):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0,
E/HideAppsPagedView( 3674):  createAddIcon count = 0
,I/HwLauncher( 3674):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550,
I/HwLauncher( 3674): Launcher  onWindowVisibilityChanged visibility = 0
,I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,I/PhoneStatusBar( 3233): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/PhoneStatusBar( 3233): shouldTranslucent:true
I/PhoneStatusBar( 3233): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,E/Minikin ( 6770): addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,W/GalleryUtils( 6770): the font DroidSanChineseSlim is not exist!
,W/asset   ( 6794): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2992): Explicit concurrent mark sweep GC freed 29068(1853KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.970ms total 286.411ms
,I/HwCust  ( 6794): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
I/HwCust  ( 6794): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/HwLauncher( 3674): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,I/HwLauncher( 3674): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3674):  stringArray[] [unknown]
I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10010
I/HwSystemManager( 3831): HoldService:uid:10010 pid:6011 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10010,6011
,E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10010, pid: 6011
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10010, pid: 6011
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3831): HoldService:uid:1000 pid:6451 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:1000,6451
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
W/MediaProcessHandler( 2992): processOp uid 1000 is not concerned!
,I/HwSystemManager( 3831): avl:parsePowerWarningParameter result:{app_show_level=1, dangerous_current_level=30, count_frequency_fg=5, high_level_standard=10, msg_send_interval=240, dangerous_level_standard=25, min_interval_time=3, average_current_fg=350, count_frequency=60}
,I/HwSystemManager( 3831): BgPowerManagerService:MSG_SCREEN_ON Received and mScreenOmTime :1450189314385 mScreenOffTime :1450189311470mCurBatterylevel :2205mScreenOffBatterylevel :2205
,I/HwSystemManager( 3831): BgPowerManagerService:onProcessDied uid = 10044
,I/HwSystemManager( 3831): HoldService:uid:10044 pid:6507 died
I/HwSystemManager( 3831): HoldService:oldVersionKey:10044,6507
E/HsmCoreServiceImpl( 2992): onTransact in code is: 102
I/MediaProcessHandler( 2992): processOp opType: 1, uid: 10044, pid: 6507
W/MediaProcessHandler( 2992): remove target not exist, maybe the UI process: uid: 10044, pid: 6507

```
