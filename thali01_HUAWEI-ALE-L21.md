#### Test 502422853393492_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/HwSystemManager( 5660): HsmStat_info:service connect
I/dex2oat ( 5879): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=default --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1343769968.jar --oat-fd=33 --oat-location=/data/data/com.google.android.youtube/cache/ads-1343769968.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/YouTube MDX( 5843): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/dex2oat ( 5879): dex2oat took 40.681ms (threads: 8)
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/e;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/l;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/i;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/g;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/m;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/f;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/k;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/j;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/d;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/c;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/b;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/h;
I/art     ( 5843): Can not find class: Lcom/google/android/ads/zxxz/a;
W/ContextImpl( 5843): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
I/MultiDex( 5899): VM with version 2.1.0 has multidex support
I/MultiDex( 5899): install
I/System  ( 5843): core_booster, getBoosterConfig = false
I/MultiDex( 5899): MultiDexExtractor.load(/data/app/com.google.android.gms-2/base.apk, false)
I/MultiDex( 5899): loading existing secondary dex files
I/MultiDex( 5899): load found 3 secondary dex files
I/MultiDex( 5899): install done
W/ContextImpl( 5843): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
W/ContextImpl( 5843): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/ContextImpl( 5843): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 5843): Found 10007
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
W/ContextImpl( 5843): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
I/art     ( 5899): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
W/System  ( 5899): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@843b1da: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5899): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.INITIALIZE
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/SUPL20_PCM( 3894): calling nc.connect for pcm
I/SUPL20_NC( 3894): Calling getLocalSocket for PCM
I/SUPL20_NC( 3894): deque initialized
I/SUPL20_NC( 3894): WriterThread initialize
I/SUPL20_NC( 3894): readerThread initialized
I/SUPL20_SCM( 3894): calling nc.connect for scm
I/SUPL20_PCM( 3894): process icmdID: 0X101
I/SUPL20_NC( 3894): Calling getLocalSocket for SCM
I/SUPL20_PCM( 3894): process hello msg
I/SUPL20_PCM( 3894): init msg success
I/SUPL20_NC( 3894): deque initialized
I/SUPL20_NC( 3894): WriterThread initialize
I/SUPL20_NC( 3894): readerThread initialized
I/SUPL20_PCM( 3894): sendHelloMessage
I/SUPL20_PCM( 3894): process: process less then zero 0
I/SUPL20_LocMan( 3894): register the Emergency Receiver 
I/SUPL20_SPIMESLP-SENDING( 3894): m_bPacket.length 12
I/SUPL20_SPIMESLP-SENDING( 3894): bBrokenPipe = false
I/SUPL20_PCM( 3894): process icmdID: 0X103
I/SUPL20_PCM( 3894):  process MSG_PCM_GET_LOCATION_ID
I/SUPL20_PCM( 3894): process: process less then zero 0
I/SUPL20_PCM( 3894): process icmdID: 0X11a
I/SUPL20_PCM( 3894):  process MSG_PCM_GET_HIST_KEY
I/SUPL20_SCM( 3894): buffer size:12writePosition: 12
I/SUPL20_SCM( 3894): process icmdID2: 0X201
I/SUPL20_SCM( 3894): process hello msg
I/SUPL20_SCM( 3894): init msg success
I/SUPL20_SPIMESLP-SENDING( 3894): m_bPacket.length 12
I/SUPL20_SPIMESLP-SENDING( 3894): bBrokenPipe = false
I/SUPL20_SCM( 3894): sendHelloMessage
I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 4196): HoldService:uid:1000 pid:5445 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:1000,5445
I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10059
I/HwSystemManager( 4196): HoldService:uid:10059 pid:5468 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10059,5468
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
W/MediaProcessHandler( 3040): processOp uid 1000 is not concerned!
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10059, pid: 5468
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10059, pid: 5468
I/SUPL20_LocMan( 3894): SIM state :1
I/SUPL20_LocMan( 3894): Registered MyPhoneStateListener
W/PhoneInterfaceManager( 3872): shouldBlockLocation running ...
I/PhoneInterfaceManager( 3872): shouldBlockLocation  ret:false
E/SUPL20_LocMan( 3894): tm.getCellLocation() returned null
I/SUPL20_LocMan( 3894):  sim is not enabled on the SET
I/SUPL20_LocMan( 3894): onServiceStateChanged ServiceState.STATE_POWER_OFF
E/PhoneInterfaceManager( 3872): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/SUPL20_LocMan( 3894): Phone type:GSM
I/SUPL20_LocMan( 3894): NULL Value received for network operator
I/SUPL20_LocMan( 3894):  cellInfo NetworkType:UNKNOWN,0
I/SUPL20_SPIMESLP-SENDING( 3894): m_bPacket.length 40
I/SUPL20_SPIMESLP-SENDING( 3894): bBrokenPipe = false
I/SUPL20_LocMan( 3894): onDataConnectionStateChanged networkType = 0
I/SUPL20_LocMan( 3894): onDataConnectionStateChanged state = -1
I/SUPL20_PCM( 3894): Fetching the historic secret key ...
I/SUPL20_PCM( 3894): process: process less then zero 0
I/SUPL20_SPIMESLP-SENDING( 3894): m_bPacket.length 24
I/SUPL20_SPIMESLP-SENDING( 3894): bBrokenPipe = false
W/PhoneInterfaceManager( 3872): shouldBlockLocation running ...
I/PhoneInterfaceManager( 3872): shouldBlockLocation  ret:false
E/SUPL20_LocMan( 3894): tm.getCellLocation() returned null
I/SUPL20_LocMan( 3894): onDataConnectionStateChanged Unknown: -1
W/PhoneInterfaceManager( 3872): shouldBlockLocation running ...
I/PhoneInterfaceManager( 3872): shouldBlockLocation  ret:false
E/SUPL20_LocMan( 3894): tm.getCellLocation() returned null
I/PG Utils( 5975): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/Babel_SMS( 5975): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5975): MmsConfig.loadMmsSettings
I/Babel_SMS( 5975): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
I/Babel_SMS( 5975): MmsConfig.loadFromDatabase
E/Babel_SMS( 5975): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5975): MmsConfig.loadFromResources
E/Babel_SMS( 5975): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5975): MmsConfig.loadMmsSettings: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
I/CameraHalInterface( 2585): Found a matching camera info for ID 0
I/CameraHalInterface( 2585): Found a matching camera info for ID 1
W/Settings( 5975): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/System.err( 3040): java.lang.SecurityException: WifiService: Neither user 10058 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 3040): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 3040): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 3040): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 3040): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 3040): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 3040): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 3040): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 5975): WifiServiceMessenger == null
I/Babel_Crash( 5975): startup - clean
I/Babel   ( 5975): deleted: false for 0
W/VideoCapabilities( 5975): Unsupported mime video/mpeg
W/VideoCapabilities( 5975): Unsupported mime video/mpeg2
W/VideoCapabilities( 5975): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile/level 0/0 for video/3gpp
W/VideoCapabilities( 5975): Unrecognized profile 0 for video/3gpp
W/VideoCapabilities( 5975): Unsupported mime video/mp4
I/VideoCapabilities( 5975): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5975): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5975): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5975): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5975): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5975): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5975): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5975): Unsupported profile 8 for video/mp4v-es
W/VideoCapabilities( 5975): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 5975): Unrecognized profile 0 for video/mp4v-es
W/VideoCapabilities( 5975): Unsupported mime video/mpeg4
W/VideoCapabilities( 5975): Unsupported mime video/x-flv
W/VideoCapabilities( 5975): Unsupported mime video/vc1
W/VideoCapabilities( 5975): Unsupported mime video/wvc1
W/VideoCapabilities( 5975): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 5975): Unsupported mime video/x-ms-wmv3
W/VideoCapabilities( 5975): Unsupported mime video/x-pn-realvideo
W/VideoCapabilities( 5975): Unsupported mime video/ffmpeg
W/AudioCapabilities( 5975): Unsupported mime audio/ffmpeg
I/VideoCapabilities( 5975): Unsupported profile 4 for video/mp4v-es
I/vclib   ( 5975): onServiceConnected
W/Babel   ( 5975): Attempted to change video mute state without an active call.
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/appproc ( 6016): CLASSPATH=/system/framework/am.jar
I/appproc ( 6016): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 6016): app_process:number,5,0
I/AndroidRuntime( 6016): readDownloadBoosterConfig: 'false'
I/art     ( 5899): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/InstanceID/Rpc( 5899): Found 10007
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/        ( 6016): power log dlsym ok
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
E/android_hardware_fm.cpp( 6016): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6016): ========64bit long size = 8
E/FM_HAL  ( 6016): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 6016): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6016): 
I/fm_hisi ( 6016): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6016): 
I/fm_hisi ( 6016): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6016): 
E/android_hardware_fm.cpp( 6016): register_android_hardware_fm_fmradio, ret is 0
I/CheckinService( 5899): Checkin interval check for package: unspecified last checkin: 1449217171307 min interval config: 0 actual interval: 196808099
I/CheckinService( 5899): Disabling old GoogleServicesFramework version
I/art     ( 3040): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 3040): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 3040): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 3040): Can not find class: Lcom/android/server/wm/StartingData;
I/HwLauncher( 3916): Launcher onPause()
I/HwLauncher( 3916): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3916): Launcher.MotionManager stopMotionAppsReco 403
I/art     ( 3040): Can not find class: Landroid/widget/ViewStub;
I/art     ( 3040): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 3040): Can not find class: Landroid/app/ViewStub;
W/HwLauncher( 3916): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
W/HwLauncher( 3916): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
I/GCoreUlr( 5899): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 3605): DispatchingService.onCreate()
I/art     ( 2324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 905us total 26.002ms
I/art     ( 3040): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/CheckinService( 5899): Checking schedule, now: 1449413979556 next: 1449807432251
I/CheckinService( 5899): active receiver: disabled
I/art     ( 3916): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3916): Can not find class: Lhuawei/android/widget/EditText;
E/textview( 3916): initAddtionalStyle default
I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 645us total 24.871ms
I/PhoneStatusBar( 3498): shouldTranslucent:true
I/PhoneStatusBar( 3498): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwSystemManager( 4196): AppLockService:applock password not initial or function is closed
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 22.485ms total 58.180ms
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/AlarmInitReceiver( 5496): handleMessage : AlarmInitReceiver, will exit app. Config.exit_count: 0
I/art     ( 5496): System.exit called, status: 0
I/AndroidRuntime( 5496): VM exiting with result code 0, cleanup skipped.
W/PGApi_client( 3800): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@2e08fd96 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3800): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3800): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@2ff4e64b, action = com.huawei.pgmng.PGAction@2e08fd96 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3800): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@2e08fd96 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3800): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3800): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
I/SystemUpdateService( 5899): cancelUpdate (empty URL)
I/SystemUpdateService( 5899): active receiver: disabled
W/AudioEffectLowPowerImpl jhh( 3800): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3800): return for smartPAOn and mLowAudioEffectEnable both = false
I/GCoreUlr( 3605): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/HwLauncher( 3916): Launcher onStop()
I/HwLauncher( 3916): Launcher dismissDialog
I/HwLauncher( 3916): Launcher dynamicIconsUnregister
I/HwLauncher( 3916): DynamicUpdater unregisterReceiver
I/HwLauncher( 3916): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3916): DynamicUpdater unregisterReceiver
I/HwLauncher( 3916): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3916): DynamicUpdater unregisterReceiver
I/HwLauncher( 3916): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3916): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3916): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3916): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3916): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3916): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10045
I/HwSystemManager( 4196): HoldService:uid:10045 pid:5496 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10045,5496
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10045, pid: 5496
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10045, pid: 5496
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.security.snet.BOOT_COMPLETED
I/HwSystemManager( 4196): AppLockService:applock password not initial or function is closed
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/WebViewFactory( 6054): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
W/BaseAppContext( 5899): Using Auth Proxy for data requests.
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/art     ( 5899): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
I/art     ( 5899): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/h/c;
I/art     ( 5899): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/LibraryLoader( 6054): Loading: webviewchromium
I/AuthZen ( 5899): Fetching signing key...
I/LibraryLoader( 6054): Time to load native libraries: 53 ms (timestamps 433-486)
I/LibraryLoader( 6054): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 6054): Expected native library version number "",actual native library version number ""
I/AuthZen ( 5899): Signing key fetched successfully!
I/chromium( 6054): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
W/BaseAppContext( 5899): Using Auth Proxy for data requests.
I/ActivityManager( 3040): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
I/BrowserStartupController( 6054): Initializing chromium process, renderers=0
W/art     ( 6054): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6054): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
I/art     ( 3605): Explicit concurrent mark sweep GC freed 29645(1958KB) AllocSpace objects, 16(320KB) LOS objects, 40% free, 17MB/29MB, paused 2.108ms total 145.500ms
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/chromium( 6054): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6054): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 6054): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
I/art     ( 3703): Explicit concurrent mark sweep GC freed 6195(351KB) AllocSpace objects, 3(60KB) LOS objects, 40% free, 17MB/29MB, paused 983us total 65.910ms
I/GCoreUlr( 3605): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/art     ( 5899): Explicit concurrent mark sweep GC freed 46913(3MB) AllocSpace objects, 30(600KB) LOS objects, 40% free, 17MB/29MB, paused 1.488ms total 132.030ms
I/art     ( 3040): Explicit concurrent mark sweep GC freed 20442(1079KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 27MB/41MB, paused 1.715ms total 179.004ms
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 3040): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/art     ( 3040): Can not find class: Lcom/android/server/accounts/AccountManagerService$GetAccountsByTypeAndFeatureSession;
I/art     ( 3040): Can not find class: Lcom/android/server/accounts/AccountManagerService$Session;
I/GCoreUlr( 3605): Unbound from all location providers
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/GCoreFlp( 3605): No location to return for getLastLocation()
I/PG Utils( 3605): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/FusedLocationProvider( 5899): location=null
I/EventLogService( 5899): Aggregate from 1449412087291 (log), 1449412087291 (data)
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/GCoreFlp( 3605): No location to return for getLastLocation()
W/FusedLocationProvider( 5899): location=null
I/GCoreUlr( 3605): DispatchingService.onDestroy()
I/GCoreUlr( 3605): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 3605): Unbound from all location providers
W/chromium( 6054): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6054): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6054): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/Kids    ( 5899): [AbstractKidsOperation] Invalid device state 3
W/Auth    ( 3703): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/Kids    ( 5899): [KidAccountFixer] No network connection
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/ActivityManager( 3040): filter receiver for action = com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/iu.UploadsManager( 5899): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
W/art     ( 6054): Attempt to remove local handle scope entry from IRT, ignoring
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
W/AwContents( 6054): onDetachedFromWindow called when already detached. Ignoring
I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/art     ( 6054): Can not find class: Landroid/widget/ViewStub;
,I/art     ( 6054): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 6054): Can not find class: Landroid/app/ViewStub;
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/SystemBroadcastReceiver( 6140): Boot has been completed
,I/SystemBroadcastReceiver( 6140): toggleAppIcon() : FLAG_SYSTEM = true
,I/PG Utils( 5899): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/iu.UploadsManager( 5899): End new media; added: 0, uploading: 0, time: 82 ms
,W/art     ( 6054): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6054): Attempt to remove local handle scope entry from IRT, ignoring
,I/SystemBroadcastReceiver( 6140): Killing my process: pid=6140
I/Process ( 6140): Sending signal. PID: 6140 SIG: 9
,I/OpenGLRenderer( 6054): Initialized EGL, version 1.4
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10077
I/HwSystemManager( 4196): HoldService:uid:10077 pid:6140 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10077,6140
,E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10077, pid: 6140
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10077, pid: 6140
,I/art     ( 3040): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
,I/ActivityManager( 3040): Displayed com.example.hello/.MainActivity: +1s337ms
,I/chromium( 6054): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 6054): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     ( 3040): Can not find class: Lcom/android/server/wm/DisplayContentList;
,E/Fabric  ( 6176): Unknown error while loading Crashlytics settings. Crashes will be cached until settings can be retrieved.
,E/WearSyncService( 6176): Failed to connect to GoogleApiClient within the timeout
I/chromium( 6054): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6054): 
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 383us total 24.556ms
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 227us total 24.819ms
,W/jxcore-log( 6054): Initializing JXcore engine
W/jxcore-log( 6054): JXcore engine is ready
,W/jxcore-log( 6054): Starting JXcore engine
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 192us total 23.635ms
,W/jxcore-log( 6054): Platform android
W/jxcore-log( 6054): 
W/jxcore-log( 6054): Process ARCH arm
W/jxcore-log( 6054): 
,I/ActivityManager( 3040): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/PG Utils( 6242): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/jxcore-log( 6054): JXcore Cordova bridge is ready!
I/jxcore-log( 6054): 
,W/jxcore-log( 6054): JXcore engine is started
,I/ActivityManager( 3040): filter receiver for action = com.google.android.gm.intent.ACTION_PROVIDER_CREATED
,I/Gmail   ( 6242): getAccountsCursor
,E/jxcore-log( 6054): >> HUAWEI-ALE-L21
E/jxcore-log( 6054): 
,I/jxcore-log( 6054): Total memory 1949741056
I/jxcore-log( 6054): 
,I/jxcore-log( 6054): Free memory 18427904
I/jxcore-log( 6054): 
,I/jxcore-log( 6054): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6054): 
I/jxcore-log( 6054): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6054): 
,I/art     ( 6242): Can not find class: Lcom/google/ads/AdRequest;
,I/jxcore-log( 6054): userPath [ 'www' ]
I/jxcore-log( 6054): 
,I/jxcore-log( 6054): Size 720 1184
I/jxcore-log( 6054): 
,I/jxcore-log( 6054): Screen Brightness 242
I/jxcore-log( 6054): 
,E/jxcore-log( 6054): Dummy Error Log.
E/jxcore-log( 6054): 
,W/GAV2    ( 6242): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 6242): Observing account changes for notifications
,E/Gmail   ( 6242): Error finding the version of the Email provider.....
E/Gmail   ( 6242): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6242): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:120)
E/Gmail   ( 6242): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6242): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6242): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6242): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6242): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6242): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6242): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6242): getAccountsCursor
,E/SQLiteLog( 6242): (283) recovered 122 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/PG Utils( 6286): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 6242): notifyAccountChanged
,I/PG Utils( 6242): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/Gmail   ( 6242): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6242): getAccountsCursor
,I/Gmail   ( 6242): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6242): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6242): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/PG Utils( 6242): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6242): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6242): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 6242): getAccountsCursor
,I/art     ( 3040): Explicit concurrent mark sweep GC freed 13135(729KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 27MB/41MB, paused 1.845ms total 193.985ms
,I/jxcore-log( 6054): getBuffer is called!!!!
I/jxcore-log( 6054): 
,W/System.err( 3040): java.lang.SecurityException: WifiService: Neither user 10025 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 3040): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 3040): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 3040): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 3040): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 3040): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 3040): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 3040): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 6286): WifiServiceMessenger == null
,W/Settings( 6286): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6286): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PG Utils( 6286): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6286): acquire_providerpkg:[com.android.providers.downloads] pid:[]  maybe timeout , send to PG
,I/art     ( 3040): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/HwSystemManager( 4196): HoldService:uid:10040 pid:5522 died
I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10040
I/HwSystemManager( 4196): HoldService:oldVersionKey:10040,5522
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10040, pid: 5522
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10040, pid: 5522
,I/PG Utils( 6337): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6337): acquire_providerpkg:[com.google.android.partnersetup] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6373): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6373): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/VelvetNetworkClient( 6337): Network connection not availble
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10001
I/HwSystemManager( 4196): HoldService:uid:10001 pid:4887 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10001,4887
I/HwSystemManager( 4196): HoldService:uid:10032 pid:5399 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10032,5399
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10001, pid: 4887
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10001, pid: 4887
I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10032
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
,I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10032, pid: 5399
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10032, pid: 5399
,W/StubController( 6404): calendar access!
,I/PG Utils( 6404): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 6426): calendar access!
,W/StubController( 6404): calendar access!
,I/PG Utils( 6404): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 6404): calendar access!
,I/CalendarSimpleUiPRovider( 6404): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
,I/CalendarSimpleUiPRovider( 6404): onConfigurationChanged
,I/CalendarSimpleUiPRovider( 6404): initParams20151206T155943Europe/Warsaw(0,339,3600,0,1449413983)
,W/StubController( 6404): calendar access!
,W/StubController( 6404): calendar access!
,E/        ( 3040): open /proc/4887/smaps fail errno 2
E/        ( 3040): open /proc/5399/smaps fail errno 2
E/        ( 3040): open /proc/5522/smaps fail errno 2
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 4196): HoldService:uid:1000 pid:5568 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:1000,5568
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
W/MediaProcessHandler( 3040): processOp uid 1000 is not concerned!
,I/ActivityManager( 3040): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,W/StubController( 6404): calendar access!
,I/CalendarSimpleUiPRovider( 6404): loadEvent end update UI0
,I/HwLauncher( 3916): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwLauncher( 3916): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
I/HwLauncher( 3916): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
,I/HwLauncher( 3916): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3916): Model STK reName intent is received.
I/HwLauncher( 3916): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3916): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3916): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3916): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3916): Model STK reName intent is received.
,I/HwLauncher( 3916): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3916): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3916): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3916): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3916): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3916): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3916): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3916): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3916): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3916): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3916): Launcher.Folder childCount: 5
I/HwLauncher( 3916): Launcher.Folder childCount: 5
I/HwLauncher( 3916): Launcher.Folder childCount: 7
I/HwLauncher( 3916): Launcher.Folder childCount: 7
I/HwLauncher( 3916): Launcher.Folder childCount: 6
I/HwLauncher( 3916): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3916): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3916): Launcher.Folder childCount: 6
I/HwLauncher( 3916): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3916): Launcher.Folder childCount: 7
I/HwLauncher( 3916): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3916):  syncPages mCurrentPage = 0
,I/HwLauncher( 3916): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3916): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,E/HideAppsPagedView( 3916):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3916):  createAddIcon count = 0
,I/HwLauncher( 3916): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3916):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3916): Launcher Deferring update until onResume
,I/HwLauncher( 3916): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3916): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3916): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3916): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3916): Model shortcutInfo.title = SIM Toolkit
,I/HwLauncher( 3916): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3916): Launcher.Folder childCount: 5
I/HwLauncher( 3916): Launcher.Folder childCount: 5
I/HwLauncher( 3916): Launcher.Folder childCount: 7
I/HwLauncher( 3916): Launcher.Folder childCount: 7
I/HwLauncher( 3916): Launcher.Folder childCount: 6
I/HwLauncher( 3916): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3916): Launcher.Folder childCount: 6
,I/HwLauncher( 3916): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3916): Launcher.Folder childCount: 7
I/HwLauncher( 3916): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3916):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3916):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3916):  createAddIcon count = 0
,I/HwLauncher( 3916):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550,
I/HwLauncher( 3916): Launcher Deferring update until onResume
,I/HwEmailTag( 6457): MailAppProvider->onCreate->begin, consuming 1449413983726ms->-prefixstartupperformance-
,I/HwEmailTag( 6457): MailAppProvider->onCreate->end, consuming 1449413983750ms->-prefixstartupperformance-
,I/HwCust  ( 6457): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 6457): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 6457): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwCust  ( 6457): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/HwEmailTag( 6457): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6457): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6457): HwUtils->initStaticVarsAsync
,I/HwEmailTag( 6457): HwUtils->initStaticVarsAsync
,I/HwCust  ( 6457): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 6457): EmailContent->init->consuming:30ms->;-prefixstartupperformance-
,I/HwEmailTag( 6457): EmailProvider->sURIMatcher is initialized
I/HwEmailTag( 6457): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 6457): EmailProvider->onCreate->end, consuming 44ms->-prefixstartupperformance-
,I/HwEmailTag( 6457): EmailProvider->onCreate->end, consuming 44ms->-prefixstartupperformance-
,I/HwCust  ( 6457): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 6457): EmailProvider->resetVisibleLimits->start:1449413983827 ->-prefixstartupperformance-
I/HwEmailTag( 6457): EmailProvider->resetVisibleLimits->start:1449413983826 ->-prefixstartupperformance-
,I/HwEmailTag( 6457): HwUtils->initStaticVarsAsync->run:consuming:54ms; bidiFormatter:android.support.v4.text.BidiFormatter@247d4fd3;accountsProjSize:42
,I/HwEmailTag( 6457): HwUtils->initStaticVarsAsync->run:consuming:64ms; bidiFormatter:android.support.v4.text.BidiFormatter@247d4fd3;accountsProjSize:42
,I/HwEmailTag( 6457): EmailApplication->onCreate->begin, consuming 75ms->-prefixstartupperformance-
,I/HwEmailTag( 6457): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/HwEmailTag( 6457): DBHelper->onOpen-> EmailProvider.db
,I/HwCust  ( 6457): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwCust  ( 6457): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
,I/HwEmailTag( 6457): EmailApplication->onCreate->end, consuming 81ms->-prefixstartupperformance-
,I/HwEmailTag( 6457): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 6457): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 39ms.
,I/HwEmailTag( 6457): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 6457): DBHelper->onOpen-> EmailProvider.db
,I/HwCust  ( 6483): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl
,I/HwEmailTag( 6457): EmailProvider->initBuildCache->start->1449413983917->-prefixstartupperformance-
,I/HwEmailTag( 6457): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 6457): EmailProvider->initBuildCache->start->1449413983917; consuming:1->-prefixstartupperformance-
,I/HwEmailTag( 6457): EmailProvider->uiAccounts->start:1449413983918
I/HwEmailTag( 6457): EmailProvider->resetVisibleLimits->getDatabase, consuming:91ms;-prefixstartupperformance-
I/HwEmailTag( 6457): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 6457): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6457): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 13ms.
,I/HwEmailTag( 6457): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6457): EmailProvider->resetVisibleLimits->getDatabase, consuming:129ms;-prefixstartupperformance-
I/HwEmailTag( 6457): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 6457): EmailProvider->uiAccounts->start:1449413983918;end,consuming:41
I/HwEmailTag( 6457): EmailProvider->query->1449413983822;end;;consuming:137ms;
,I/PG Utils( 6483): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10052
I/HwSystemManager( 4196): HoldService:uid:10052 pid:5592 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10052,5592
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10052, pid: 5592
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10052, pid: 5592
,I/PG Utils( 6483): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6483): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6483): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/HwCust  ( 6483): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
,I/PG Utils( 6483): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6483): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
,I/ActivityManager( 3040): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
E/ContactsProtector( 6483): getHiCloudAccountData query fail
I/PG Utils( 6483): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 3040): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/PG Utils( 3774): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6483): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
,I/HwCust  ( 6483): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 4196): HoldService:uid:10050 pid:5617 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10050,5617
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10050, pid: 5617
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10050, pid: 5617
,I/HwCust  ( 6515): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
,I/HwSystemManager( 4196): ContactsObserverHelper:Receive contacts change broadcast
,W/HWContacts( 6515): ProviderFeatureChcker - cootek package not installed
,E/TmoMonitor( 6515): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@247d4fd3
,I/HwCust  ( 6515): Constructor found for class com.android.mms.data.HwCustConversationImpl
,I/EmuiFeatureManager( 6515): loadEmailAnrSupportFlag:true
,I/Mms_threadcache( 6515): [RecipientIdCache] fill: begin
,I/CalendarProvider2( 6426): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6426): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 3040): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/SimFactoryManager( 6515): Inside init method of SimFactoryManger the combination is:-1
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6515): isSIM1CardPresent:1
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 6515): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 6515): isSIM2CardPresent:1
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:0
,E/MmsConfig( 6515): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 6515): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/HwCust  ( 6515): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
,I/HwCust  ( 6515): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
,I/art     ( 6515): Can not find class: Lhuawei/android/view/TableLayout;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/TableLayout;
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10056
I/HwSystemManager( 4196): HoldService:uid:10056 pid:5638 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10056,5638
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10056, pid: 5638
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10056, pid: 5638
,I/art     ( 6515): Can not find class: Lhuawei/android/view/View;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/View;
I/art     ( 6515): Can not find class: Landroid/widget/View;
I/art     ( 6515): Can not find class: Landroid/webkit/View;
I/art     ( 6515): Can not find class: Landroid/app/View;
,I/art     ( 6515): Can not find class: Lhuawei/android/view/TableRow;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/TableRow;
,I/art     ( 6515): Can not find class: Lhuawei/android/view/LinearLayout;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/LinearLayout;
,I/HwCust  ( 6515): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
,I/HwCust  ( 6515): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
,I/art     ( 6515): Can not find class: Lhuawei/android/view/ImageButton;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/ImageButton;
,I/art     ( 6515): Can not find class: Lhuawei/android/view/TextView;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/TextView;
,I/art     ( 6515): Can not find class: Lhuawei/android/view/RelativeLayout;
I/art     ( 6515): Can not find class: Lhuawei/android/widget/RelativeLayout;
,I/art     ( 6515): Can not find class: Lhuawei/android/view/ImageView;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/ImageView;
,I/art     ( 6515): Can not find class: Lhuawei/android/view/ViewStub;
I/art     ( 6515): Can not find class: Lhuawei/android/widget/ViewStub;
,I/art     ( 6515): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6515): Can not find class: Landroid/webkit/ViewStub;
,I/art     ( 6515): Can not find class: Landroid/app/ViewStub;
,I/art     ( 6515): Can not find class: Lhuawei/android/view/FrameLayout;
I/art     ( 6515): Can not find class: Lhuawei/android/widget/FrameLayout;
,I/art     ( 6515): Can not find class: Lhuawei/android/view/EditText;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/EditText;
,E/textview( 6515): initAddtionalStyle default
,I/art     ( 6515): Can not find class: Lhuawei/android/view/ProgressBar;
,I/art     ( 6515): Can not find class: Lhuawei/android/widget/ProgressBar;
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 6515): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 4196): HoldService:uid:1000 pid:5660 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:1000,5660
,E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
W/MediaProcessHandler( 3040): processOp uid 1000 is not concerned!
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 4196): HoldService:uid:10065 pid:5700 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10065,5700
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10065, pid: 5700
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10065, pid: 5700
I/HwSystemManager( 4196): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 4196): NotificationManagerReceiver:onReceive, send action to background
I/HwSystemManager( 4196): ProcPolicy:begin get procName.
,I/HwSystemManager( 4196): ProcPolicy:this proc is:com.huawei.systemmanager:service
I/HwSystemManager( 4196): ProcPolicy:end get procName.
,I/HwSystemManager( 4196): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@24f6a232
,I/HwSystemManager( 4196): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 4196): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 4196): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings]
I/HwSystemManager( 4196): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
I/HwSystemManager( 4196): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
I/HwSystemManager( 4196): NmCenterDefValueXmlHelper:getConfigs: Starts
,I/HwSystemManager( 4196): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33
,I/HwSystemManager( 4196): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
,I/HwSystemManager( 4196): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 4196): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 4196): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 4196): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 4196): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 4196): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 4196): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 4196): NotificationDBProvider:query starts, matchCode = 1
I/HwSystemManager( 4196): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 4196): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 4196): HsmIntentService:last work complete! lets stop service.
,I/PhoneStatusBar( 3498): notification pkg =com.android.settings
I/PhoneStatusBar( 3498): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3498): notification pkg =android
I/PhoneStatusBar( 3498): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,W/asset   ( 6579): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwSystemManager( 4196): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@24f6a232
,I/HwSystemManager( 6579): SystemManagerApplication:onCreate
,I/HwSystemManager( 4196): MainService:on startCommand,flags:0,startId:6
,I/System.out( 6579): [ls, -l, /system/app/HwSystemManager/HwSystemManager.apk]
I/System.out( 6579): null
I/System.out( 6579): null
I/System.out( 6579): Calling by::className:bkk  MethodName:yw
,I/HwSystemManager( 4196): LocalService:Received start id 6: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
,I/HwSystemManager( 4196): BgPowerManagerService:onStartCommand
,I/HwSystemManager( 4196): AppLockService:onStartCommand
,I/HwSystemManager( 6579): check push opration, match idx:-1
I/HwSystemManager( 4196): AppCleanUpService:onStartCommand() in!
,I/HwSystemManager( 6579): HsmStat_info:feature enable:false
,I/HwSystemManager( 6579): ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.test.thalitest]
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 1050
,I/HwSystemManager( 4196): HoldService:uid:1050 pid:5726 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:1050,5726
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
W/MediaProcessHandler( 3040): processOp uid 1050 is not concerned!
,I/HwSystemManager( 6579): OverseaCfgHelper:permissionStatus is 0
,I/HwSystemManager( 6579): AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6579): ProcPolicy:begin get procName.
,I/HwSystemManager( 6579): ProcPolicy:this proc is:com.huawei.systemmanager
I/HwSystemManager( 6579): ProcPolicy:end get procName.
,I/HwSystemManager( 6579): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,I/YhdsEngine( 6579): [EngineIntentService] Received: com.huawei.dianxinos.optimizer.engine.action.APP_START
I/HwSystemManager( 6579): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 6579): SimCardManager:getOperatorNameFromService mNameServSlot0 = null
I/HwSystemManager( 6579): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
I/HwSystemManager( 6579): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
,I/HwSystemManager( 6579): SimCardManager:getOperatorNameFromService mNameServSlot1 = null
I/HwSystemManager( 6579): SimCardManager:/onReceive: action =android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 6579): SimCardManager:action:android.provider.Telephony.SPN_STRINGS_UPDATED
,I/HwSystemManager( 6579): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@7df7710
,I/HwSystemManager( 6579): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,I/HwSystemManager( 6579): HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,I/HwSystemManager( 6579): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,I/HwSystemManager( 6579): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
,I/HwSystemManager( 6579): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6579): OverseaCfgHelper:permissionStatus is 0
,I/YhdsEngine( 6579): [AlarmEventMgr] event scheduled: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
I/HwSystemManager( 4196): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 4196): AppCleanUpService:onStartCommand() out!
E/HwSystemManager( 4196): AppCleanUpService:msg is 0
I/HwCust  ( 6579): Constructor found for class com.huawei.systemmanager.optimize.process.HwCustProtectAppControlImpl
,I/YhdsEngine( 6579): [EngineIntentService] Received: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
I/HwSystemManager( 6579): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,I/HwSystemManager( 6579): HsmPackageManager:begin to scan apks.
,I/HwSystemManager( 6579): NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6579): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,W/HwSystemManager( 6579): BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6579): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6579): HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:3, queue size:0
,I/HwSystemManager( 6579): anf:packageCanAccessInternet com.example.hellohas INTERNET permission
,I/HwSystemManager( 6579): anf:packageCanAccessInternet component enable
,I/HwSystemManager( 6579): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6579): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6579): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6579): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6579): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6579): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
,I/HwSystemManager( 6579): abu:parseRule result: {common=[Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], dropzone=[Rule DropzoneMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule DropzoneNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], applock=[Rule AppLockNotMonitorListRule post: match[0], mismatch[2], Rule HomeCategoryRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], notification=[Rule NotificationMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NotificationNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], netmanager=[Rule NetAccessMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule NetAccessNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], bootstart=[Rule BootstartMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule BootstartNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]], permission=[Rule PermissionMonitorListRule post: match[1], mismatch[2], Rule DefaultMonitorListRule post: match[1], mismatch[2], Rule PermissionNotMonitorListRule post: match[0], mismatch[2], Rule DefaultAllowListRule post: match[0], mismatch[2], Rule UnRemovableAppRule post: match[0], mismatch[2], Rule AlwaysMatchRule post: match[1], mismatch[2]]}
I/HwSystemManager( 6579): DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello, replacing: false
I/YhdsEngine( 6579): [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
I/HwSystemManager( 6579): DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
I/HwSystemManager( 6579): AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6579): XmlRuleBase:parseAndCacheList permission_black_list_match :[]
I/HwSystemManager( 6579): XmlRuleBase:parseAndCacheList black_match :[]
I/HwSystemManager( 6579): XmlRuleBase:parseAndCacheList dropzone_black_list_match :[]
I/HwSystemManager( 6579): XmlRuleBase:parseAndCacheList dropzone_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 6579): XmlRuleBase:parseAndCacheList permission_white_list_match :[com.huawei.intelligent]
I/HwSystemManager( 6579): XmlRuleBase:parseAndCacheList white_match :[com.baidu.map.location, com.cootek.smartdialer_oem_module, com.sohu.inputmethod.sogou.huawei, com.huawei.hisuite, com.nuance.swype.emui, com.huawei.remoteassistant, com.iflytek.speechcloud, com.huawei.phoneservice, com.huawei.phonediagnose, com.nqmobile.antivirus20.hw, com.baidu.input_huawei]
,I/HwSystemManager( 6579): HsmPackageManager:end to scan apks. size:150 + 0
,I/HwSystemManager( 6579): HsmPackageManager:init locale:en_US
,I/HwSystemManager( 6579): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 6579): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:2, queue size:0
I/HwSystemManager( 6579): ProtectAppControl:handleMessage:6
I/HwSystemManager( 6579): ProtectAppControl:begin install app inner:com.example.hello
,I/HwSystemManager( 6579): AppManager:insert to db: name = com.example.hello uid = 10302 app type = false
,I/HwSystemManager( 6579): PermissionDBAdapter:DBAdapter created!
,I/HwSystemManager( 6579): PermissionDbHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/permission.db
W/HwSystemManager( 6579): AddViewAppManager:Current installed app not apply system_alert_window or applicationInfo null!
,I/HwSystemManager( 6579): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6579): PermissionDBAdapter:appcationsList size:150
,I/StagefrightMediaScannerEx( 3677): StagefrightMediaScanner destructor
,I/art     ( 3040): Explicit concurrent mark sweep GC freed 14106(759KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.049ms total 194.849ms
,I/HwSystemManager( 4196): OptimizeProvider:delete com.example.hello
,I/HwSystemManager( 6579): PowerGenieDbHelper:delete protect app:com.example.hello
,I/HwSystemManager( 4196): ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.test.thalitest, com.example.hello]
,I/HwSystemManager( 6579): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 6579): CommonFunctionUtil:compareCode = 10485760
,I/HwEmailTag( 6457): EmailProvider->query->1449413985827;end;;consuming:1ms;
,I/HwEmailTag( 6457): EmailApplication->handleMessage->startService CleanRecipientAddressService
,E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_11_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_12_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_13_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_14_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_15_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_16_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_17_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_18_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_19_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_20_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_21_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_22_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_23_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_24_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_25_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_26_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_27_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_30_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_28_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_29_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_PERMISSION_TRUST_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_2_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_1_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_5_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_6_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_3_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_7_TEMP_VIEW(packageName)
E/SQLiteLog( 4196): (284) automatic index on VaguePermission_COL_4_TEMP_VIEW(packageName)
,I/HwEmailTag( 6457): Device->updateDeviceIdIfNeeded
,I/HwEmailTag( 6457): CleanRecipient->onCreate
I/HwEmailTag( 6457): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 6457): Device->getDeviceId->
I/HwEmailTag( 6457): Device->getDeviceIdInternal->isUpdate:false
,I/HwEmailTag( 6457): CleanRecipient->onStartCommand->action is null
I/HwEmailTag( 6457): Device->getDeviceIdInternal->get id from deviceName, return successfully.
I/HwEmailTag( 6457): CleanRecipient->onHandleIntent->action is null
I/HwEmailTag( 6457): Device->updateDeviceIdIfNeeded->deviceId is consistent id , return directly.
I/HwEmailTag( 6457): AccountReconciler->reconcileAccountsInternal->consuming:90ms
,I/HwEmailTag( 6457): EmailProvider->query->1449413985924;end;;consuming:2ms;
,I/HwEmailTag( 6457): CleanRecipient->onHandleIntent-> clean RecipientAddress done, nothing changed!!
,I/HwEmailTag( 6457): CleanRecipient->onDestroy
,I/HwSystemManager( 6579): HsmPackageManager:get all installed packages, flag:0, size:150
E/HwSystemManager( 6579): PermissionDBAdapter:appcationsList size:150
,I/HwEmailTag( 6457): AccountReconciler->reconcileAccountsInternal->consuming:6ms
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 287us total 33.755ms
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 240us total 23.596ms
,I/art     ( 2323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 259us total 24.965ms
,I/HwCust  ( 6646): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 6646): EmailContent->init->consuming:25ms->;-prefixstartupperformance-
I/HwEmailTag( 6646): Exchange->onCreate
,I/PG Utils( 6646): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6646): acquire_providerpkg:[com.android.email] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 6457): EmailProvider->query->1449413986062;end;;consuming:1ms;
,I/HwEmailTag( 6646): PingSyncSynchronizer->PSS->->PSS has no active accounts; stopping service.
,I/HwSystemManager( 6579): PermissionDBAdapter:DBAdapter refreshAllCachedData!
,I/HwSystemManager( 6579): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 6579): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 6579): HsmIntentService:last work complete! lets stop service.
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10090
I/HwSystemManager( 4196): HoldService:uid:10090 pid:5769 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10090,5769
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10090, pid: 5769
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10090, pid: 5769
,I/HwSystemManager( 6579): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@7df7710
,I/GAv4    ( 6619): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6619):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6619):   adb logcat -s GAv4
,W/GAv4    ( 6619): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10092
I/HwSystemManager( 4196): HoldService:uid:10092 pid:5799 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10092,5799
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10092, pid: 5799
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10092, pid: 5799
,I/ContactsAppilcation( 6515): intent:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
,W/GAv4    ( 6619): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/CommonUtilMethods( 6515): action:android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
,I/ContactsAppilcation( 6515): intent:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
,W/GAv4    ( 6619): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CommonUtilMethods( 6515): action:android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED networkName showSpn = false spn =  showPlmn = false plmn = null
,I/ContactsAppilcation( 6515): intent:android.provider.Telephony.SPN_STRINGS_UPDATED
,W/AnalyticsTrackerProxyImpl( 6619): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.44
,W/ContextImpl( 6619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/BluetoothAdapter( 6054): Start to disable Bluetooth!
,I/GAV2    ( 6242): Thread[GAThread,5,main]: No campaign data found.
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10095
I/HwSystemManager( 4196): HoldService:uid:10095 pid:5821 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10095,5821
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10095, pid: 5821
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10095, pid: 5821
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GAv4-SVC( 5899): Google Analytics 8.3.01 is starting up.
,I/HwSystemManager( 4196): HoldService:checkBeforeShowDialog: uid:10302 pid:6054, permissionType:2097152
I/HwSystemManager( 4196): OverseaCfgHelper:permissionStatus is 0
,I/HwSystemManager( 6579): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/ConnectPermission( 3040): allowOpenWifi blocked:false
I/HwSystemManager( 6579): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 6579): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/jxcore-log( 6054): ****TEST TOOK:  5269  ms ****
I/jxcore-log( 6054): 
,I/jxcore-log( 6054): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6054): 
,I/art     ( 6619): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6619): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6619): Installed default security provider GmsCore_OpenSSL
,I/art     ( 3040): Can not find class: Lcom/android/server/accounts/AccountManagerService$TestFeaturesSession;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/GmsModuleInitializer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/app/GmsApplicationContext;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue;
,I/art     ( 5899): Can not find class: Lcom/google/android/flib/pref/PreferenceFile;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/PlatformVersion;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/permission/PermissionUtils$1;
,I/art     ( 5899): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/Asserts;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReaderImpl;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$GservicesReader;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/receiver/PlaySystemBroadcastReceiver;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/UserAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/GamesSyncAdapter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/sync/BaseGmsSyncAdapter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/config/G;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesLog;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/VersionUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/GamesSharedPrefs;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$AsyncOperationQueue;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/Preconditions;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/AsyncOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/BaseAsyncOperationService$OperationTask;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/PooledAsyncOperationService$PooledAsyncOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/WrappedGamesCallbacks;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/quests/AcceptQuestOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractDataHolderOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$Operation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/requests/AcceptRequestOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/AcceptTurnBasedMatchInvitationOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/AcknowledgeNotificationsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/AddNearbyPlayerOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractStatusReportingOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CancelTurnBasedMatchOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/quests/ClaimMilestoneOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/ClearDataOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/ClearNotificationsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/events/ClearPendingEventsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/ApiClientTracker;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveContents;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/CommitSnapshotOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomEnteredCallback;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/ConnectionInfo;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/safeparcel/SafeParcelable;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/CreateRoomOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/CreateTurnBasedMatchOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DeclineInvitationOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/DeleteSnapshotOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/DismissInvitationOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/DismissTurnBasedMatchOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/DismissPlayerSuggestionOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/requests/DismissRequestOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/multiplayer/ParticipantResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/FinishTurnBasedMatchOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/GetGamesAuthTokenOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/GetInboxActivityCountsOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/GetScoreOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$GamesThreadFactory;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/GetTurnBasedMatchOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/AccountsChangedOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/PackageModifiedOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/PeopleChangedOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/PopupManager$PopupLocationInfo;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/IncrementAchievementOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/events/EventIncrementEntry;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/events/IncrementEventsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/InitializeGamesOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/InvalidateAppContentOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/IsGameMutedOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/JoinRoomOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/video/VideoConfiguration;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/video/LaunchGameForRecordingOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/client/IPlayGamesCallbacks;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/ClientContext;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$RoomLeftCallback;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveDiagnostics;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/response/FastMapJsonResponse;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/response/FastJsonResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/LeaveRoomOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LeaveTurnBasedMatchOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/video/ListVideosOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/LoadAchievementsInternalOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AppContentContext;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/appcontent/LoadAppContentOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/AbstractMultiDataHolderOperation;,
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadCircledPlayersOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameCollectionComparisonOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadConnectedPlayersOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/LoadContactSettingsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/events/LoadEventsByIdOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/LoadExperimentsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadFirstPartyPlayersOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameFirstPartyOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameInstancesOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGameSearchSuggestionsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadGamesCollectionOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadInvitablePlayersOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/invitations/LoadInvitationsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadLeaderboardsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadMoreScoresOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpStreamOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/acls/LoadNotifyAclOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/LoadPlayGamesRecentlyPlayedOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayerOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/LoadScoresOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/stats/LoadPlayerStatsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadPlayersInternalOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadProfileSettingsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/quests/LoadQuestsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestSummariesOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/requests/LoadRequestsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/LoadSnapshotsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/LoadTurnBasedMatchesOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/LoadXpForGameCategoriesOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/NotificationOpenedOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/RecordApplicationSessionOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/RecordPlayerSuggestionActionOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/RematchTurnBasedMatchOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$P2pStatusReportCallback;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/realtime/ReportP2pStatusOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/ResolveSnapshotConflictOperation;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/UpdateAchievementOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/SearchForGamesOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/SearchForPlayersOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/requests/SendRequestOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/achievements/SetAchievementStepsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/notifications/SetGameMuteStatusOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/SetIdentitySharingConfirmedOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/quests/QuestStateChangedPopupOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/SignOutOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/AndroidUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlayGamesAsyncService$OperationAdapter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/video/StopRecordingOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/leaderboards/SubmitScoreOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/UpdateContactSettingsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/acls/UpdateNotifyAclOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/games/UpdatePlayedOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/players/UpdateProfileSettingsOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/turnbased/UpdateTurnBasedMatchOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/IGmsCallbacks;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/GetServiceRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/ValidatePlayServiceConnectionOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/ValidateServiceConnectionOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/VerifySnapshotFolderOperation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$2;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/DataBroker;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/Lockable;
,I/HwSystemManager( 6579): PermissionDBAdapter:preInstalledAppsPermissionEmendation no need emendation!
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/service/OperationException;
I/HwSystemManager( 6579): PermissionDBAdapter:checkDBErrorBecauseofHOTA packageNameDBList size 13
I/HwSystemManager( 6579): PermissionDBAdapter:checkDBErrorBecauseofHOTA nameList is0
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/auth/GoogleAuthException;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/Lockable$LockableLock;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/GamesServer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/AbstractServer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/auth/appcert/AppCertServiceClient;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/auth/AuthSessionAuthenticator;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/error/ErrorUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/auth/GoogleAuthUtil;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/AbstractApiaryServer$DefaultApiaryRetryPolicy;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$1;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryRequest;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/BaseApiaryServer$Batch;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/response/FieldMappingDictionary;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/ApiaryRequest;
,I/PeopleContactsSync( 5899): CP2 sync disabled
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/VolleyInterruptedError;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/NoResponseRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/ImageRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/GamesRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GamesExperiments;
,I/art     ( 5899): Can not find class: Lcom/google/android/play/experiments/PlayExperiments;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/Base64Utils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/config/GamesOptions;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/error/ErrorInstanceResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/error/GamesException$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/error/GamesException;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$6;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$1;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$3;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$4;
,I/Icing   ( 5899): Storage manager: low false usage 1.44MB avail 7.15GB capacity 8.84GB
,I/HwSystemManager( 6579): HsmStat_info:service connect
,I/art     ( 5899): Can not find class: Lcom/google/android/gsf/Gservices;
,I/art     ( 5899): Can not find class: Lcom/google/android/gsf/Gservices$1;
,I/art     ( 5899): Can not find class: Lcom/google/android/gsf/Gservices$1$1;
,W/Icing   ( 5899): Received bad json for section weights override -- ignoring.
,W/Icing   ( 5899): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 5899): Received bad json for section weights override -- ignoring.
,W/Icing   ( 5899): Received bad json for corpus context scoring override -- ignoring.
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/GamesServerFactory;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/BaseAppContext( 5899): Using Auth Proxy for data requests.
W/BaseAppContext( 5899): Using Auth Proxy for data requests.
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/server/PlusServer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/config/G;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/SpamAndAbuseHeaders;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/server/ContainerParam;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/auth/AuthTokenTimeCache;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/server/SocialClient;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/BaseAppContext( 5899): Using Auth Proxy for data requests.
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/AccountTypeManager( 6515): Adding account type = com.android.contacts.model.account.ExchangeAccountType@3e853f48 in the cache
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:1
,I/HwCust  ( 6515): Constructor found for class com.android.contacts.model.account.HwCustAccountModelCustomizationImpl
,I/appproc ( 6702): CLASSPATH=/system/framework/pm.jar
I/appproc ( 6702): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 6702): app_process:number,5,0
,I/AccountTypeManager( 6515): Adding account type = com.android.contacts.model.account.ExternalAccountType@3c245b06 in the cache
,I/art     ( 3703): Explicit concurrent mark sweep GC freed 9722(576KB) AllocSpace objects, 2(40KB) LOS objects, 40% free, 17MB/29MB, paused 1.033ms total 83.880ms
,W/BaseAppContext( 5899): Using Auth Proxy for data requests.
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/AndroidRuntime( 6702): readDownloadBoosterConfig: 'false'
W/BaseAppContext( 5899): Using Auth Proxy for data requests.
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryServer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/utils/Log;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/server/apiary/DriveApiaryRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/G;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/config/GservicesValue$5;
,W/ResourceType( 6515): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
W/ResourceType( 6515): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
W/ResourceType( 6515): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
W/ResourceType( 6515): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6515): Adding account type = com.android.contacts.model.account.ExternalAccountType@35307f4 in the cache
,I/AccountTypeManager( 6515): Adding account type = com.android.contacts.model.account.GoogleAccountType@117eeb1d in the cache
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/ExternalAccountType( 6515): Unsupported attribute readOnly
,I/AccountTypeManager( 6515): AccountManager, account size is: 2
,I/AccountTypeManager( 6515): Loaded meta-data for 5 account types, 3 accounts in 109ms(wall) 57ms(cpu)
,W/BaseAppContext( 5899): Using Auth Proxy for data requests.
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/TransientCacheOwner;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/InboxCounter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/ColumnSpec$DataType;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/utils/GamesDataUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/DefaultClock;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/Clock;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/BaseApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementsApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/AchievementCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/Agents$QueryBuilder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementDefinitions;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementDefinitionsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/DataHolder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/DataHolder$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Players;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayersColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$1;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementFlushData;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateMultipleResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/ApiRateLimitUtil;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/error/ErrorResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementInstances;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementInstancesColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/provider/QuerySpec;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/achievement/AchievementBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/AbstractDataBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/DataBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/Releasable;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/achievement/Achievement;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/Freezable;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/Agents;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$TypeQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementStepData;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$IncrementQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/ui/popup/AchievementPopup;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/ui/popup/BasePopup;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlayGamesUploadService;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/GcmTaskService;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinition;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/response/FastContentValuesJsonResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievement;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/GamePlayerCacheKey;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AchievementPendingOps;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AchievementPendingOpsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$PendingOpsQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/constants/AchievementState;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/util/AccountUtils;
,I/art     ( 5899): Can not find class: Landroid/support/v4/util/ArrayMap;
,I/art     ( 5899): Can not find class: Landroid/support/v4/util/SimpleArrayMap;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementSetStepsAtLeast;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUpdateRequest;
I/PG Utils( 6711): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/GamesAchievementIncrement;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AchievementAgent$AchievementUpdateResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementIncrementResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementDefinitionsListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationFetchList;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementGetMultipleResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerAchievementListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementSetStepsAtLeastResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementUnlockResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AchievementRevealResponse;
,I/art     ( 5899): Can not find class: Landroid/support/v4/util/ContainerHelpers;
,I/art     ( 5899): Can not find class: Landroid/support/v4/util/ArrayMap$1;
,I/art     ( 5899): Can not find class: Landroid/support/v4/util/MapCollections;
I/art     ( 5899): Can not find class: Landroid/support/v4/util/MapCollections$KeySet;
,I/art     ( 5899): Can not find class: Landroid/support/v4/util/MapCollections$ArrayIterator;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/TransientDataHolderCache$OwnerCache;
,I/art     ( 5899): Can not find class: Landroid/support/v4/util/LruCache;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/BaseGmsContentProvider;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/Objects;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$UriType;
,I/art     ( 5899): Can not find class: Lcom/android/common/content/ProjectionMap;
,I/art     ( 5899): Can not find class: Lcom/android/common/content/ProjectionMap$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/provider/TableJoiner;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerLevels;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerLevelColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$PlayerStats;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$PlayerStatsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ClientContexts;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ClientContextsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestPendingOps;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestPendingOpsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ApplicationSessions;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ApplicationSessionColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AppContents;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AppContentColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Images;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ImagesColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardPendingScores;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Requests;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Matches;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchesPendingOps;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MatchesPendingOpsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesDataStore;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesDatabaseHelper;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/utils/UriUtils;,
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$ImageCleaner;
E/Icing   ( 5899): Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$3;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/ImageStore;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/ImageStore$Entry;,
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$GamesProjectionMapBuilder;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameInstances;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameInstancesColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventInstances;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventInstancesColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventPendingOps;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventPendingOpsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$ExperienceEvents;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ExperienceEventColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Invitations;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$InvitationsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Participants;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$ParticipantsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardInstances;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardInstancesColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$LeaderboardScores;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardScoresColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Notifications;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$NotificationsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Milestones;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$MilestoneColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestRecipients;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestRecipientsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Snapshots;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$SnapshotColumns;
,I/art     ( 5899): Can not find class: Lcom/android/common/SharedPreferencesCompat;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Games;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GamesColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$EventDefinitions;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$EventDefinitionColumns;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Leaderboards;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$LeaderboardsColumns;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/constants/OfflineMatchAction;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Quests;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$QuestsColumns;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$1;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$DataDeleterAssociatedQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/PlayGamesContentProvider$2;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AppContentsApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/AppContentSectionAndCardCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/AppContentBaseCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/AppContentActionCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/AppContentAnnotationCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/AppContentConditionCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/AppContentTupleCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$CardImageInsertHelper;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ContentEntry;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Section;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Card;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/CardAnnotation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ImageAsset;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/CardCondition;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/CardAction;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/response/FastParser$ParseException;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/GamesCardScreenFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AppContentAgent$ServerCookieQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/constants/DeviceType;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/EventAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/EventResolver;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventsApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventsApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$WindowInfo;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodRange;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventPeriodUpdate;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$PendingOpsQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$EventDefinitionRefreshInfo;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinition;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventDefinitionListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/EventAgent$UnresolvedException;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEvent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerEventListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventRecordRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/EventUpdateResponse;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GamesClientContext$Builder;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApi;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationsApiInternal;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/GameCache;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/GameSearchCache;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/BaseSearchCache;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCache;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplication;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Application;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/MarketApplication;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/MarketBadge;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ImageConfig;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/converter/ImageUrlBuilder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/MarketInstance;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameBadges;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameBadgesColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Instance;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/InstanceAndroidDetails;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/util/PackageUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Snapshot;,
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/util/PanoUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationCategory;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/GameBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/Game;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationList;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchContext;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationUpdatesFetchList;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetUpdatesMultipleFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsFlushData;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/SessionBatch;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationGetMultipleFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$FirstPartyGameListProcessor;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationListFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$GameRefreshRecord;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/TransientDataHolder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$VersionQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyApplicationUpdates;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/constants/AppUpdateType;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/ArrayUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/InvalidId;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/GameCompareCacheKey;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$StoreGamesProcessor;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GameSearchSuggestions;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$GameSearchSuggestionsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/finsky/SearchSuggestion;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/DataUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ApplicationSearchFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$ApplicationSessionsQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Session;
,I/        ( 6702): power log dlsym ok
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameAgent$InstanceQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardsApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ScoresApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/LeaderboardScoreCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Leaderboard;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScores;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardEntry;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Player;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/constants/LeaderboardCollection;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/constants/TimeSpan;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PageTokensQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheKey;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/ScoreCacheOwner;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/LeaderboardAgent$PendingScoreQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/provider/SelectionArgs;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ScoreSubmission;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreSubmissionList;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreListResponse;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScoreResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScoreListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLeaderboardScore;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/LeaderboardScoreRank;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/leaderboard/LeaderboardScoreBufferHeader$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GamesDroidGuard;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerScore;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/leaderboard/ScoreSubmissionData$Result;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/NotificationAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/PlayCommonAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/NonListener;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayersApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleApi;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/PeopleApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/MetagameApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ExperiencesApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/PlayerCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/PlayerSearchCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/ContactSettingsCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/ProfileSettingsCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/cache/XpEventStreamCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/PlayerBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/Player;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$CircledStateQuery;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/People;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/Api;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/People$PeopleOptions1p;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions$HasOptions;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/Api$ApiOptions;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/GoogleApiClient;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/ConnectionResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyPlayer;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Played;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListFirstPartyResponse;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$PeopleNetworkData;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/PlayerLevel;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Experience;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PeopleFeed;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/response/FastSafeParcelableJsonResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/Person$Image;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/service/v1/PeopleFeed;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/model/people/Person;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/model/people/Person$Image;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$TrimExperiencesQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ProfileSettings;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleOptions;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/internal/PeopleUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/Graph;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/PendingResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/Result;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/Graph$LoadPeopleResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/People$ReleasableResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/Status;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/model/PersonBuffer;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/model/DataBufferWithSyncInfo;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/people/model/Person;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/logging/GamesPlayLogger;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/data/GamesDataChangeUris;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/plus/service/v1whitelisted/models/PersonEntity$ImageEntity;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/images/ImageBroker;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$LevelQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/GamesStatusCodes;
I/PG Utils( 6711): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ContactSettings;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ContactChannelSetting;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/constants/NotificationChannel;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/CategoryListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Category;
,E/android_hardware_fm.cpp( 6702): register_android_hardware_fm_fmradio
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/MetagameConfig;
I/android_hardware_fm.cpp( 6702): ========64bit long size = 8
E/FM_HAL  ( 6702): [FM_HAL], libname is libhisifm_if
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/PlayerLevel;
I/fm_hisi ( 6702): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6702): 
I/fm_hisi ( 6702): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6702): 
I/fm_hisi ( 6702): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6702): 
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/ExperienceSyncFirstPartyResponse;
E/android_hardware_fm.cpp( 6702): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/PlayerAgent$SyncNetworkResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$AccountMetadata;
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestsApiInternal;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataApiInternal;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestonesApi;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Quest;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestMilestone;
I/PG Utils( 6711): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestCriterion;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestContribution;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/quest/QuestBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/EntityBuffer;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/quest/Quest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$QuestsEntities;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/Joiner;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/GameEventListenerRegistry;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/ui/popup/QuestPopup;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$SyncNetworkResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$NotifyDataHolder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/QuestAgent$MilestoneClaimedQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestListFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestMetadataSyncFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/QuestSyncFirstPartyResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/RevisionAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RevisionsApiInternal;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyRevisionCheckResponse;
,I/art     ( 3040): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/art     ( 3040): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AclAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AclsApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMember;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingRoster;
,I/art     ( 5899): Can not find class: Lcom/google/protobuf/micro/MessageMicro;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/people/proto/AclProto$SharingTargetId;
,I/art     ( 5899): Can not find class: Lcom/google/protobuf/micro/InvalidProtocolBufferMicroException;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Acl;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/people/data/AudienceMemberConversions;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$Acls;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$AclsColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/AclUpdateRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/GamesContract$RequestSummaryColumns;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RequestsApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/OutboundRequestInfo;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RequestRecipient;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$RequestEntities;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/request/GameRequestBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/request/GameRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$RequestSummariesData;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/PlayerRef;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/DataBufferRef;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/GameRef;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateList;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdate;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$SyncNetworkResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RequestEntity;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Request;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyNotification;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/InboundRequestInfo;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$TrimRequestsQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/RequestAgent$PendingOpsQuery;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/SendRequest;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/constants/RequestType;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RequestSyncResponseFirstParty;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/request/RequestUpdateOutcomes$Builder;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResultList;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RequestUpdateResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotsApiInternal;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/service/FilesApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/Drive;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveApi;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveApi$ResourceIdSetResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/MetadataBundle;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/MetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/CustomPropertyKey;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/data/BitmapTeleporter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/Query;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveApi$MetadataBufferResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$ResultPair;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/MetadataBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/Api$ClientKey;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/Api$Client;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/GmsClient;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/GmsClientEventManager$GmsClientEventState;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/LogicalFilter;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/AbstractFilter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/Filter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/internal/DriveClientImpl$6;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/internal/DriveBaseApiMethodImpl;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ApiMethodImpl;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/internal/BasePendingResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/internal/BaseImplementation$ResultHolder;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/api/internal/GoogleApiClientImpl$Runner;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/FullTextSearchDetector;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/FilterVisitor;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/Metadata;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveId;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/mdm/DeviceManager;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/mdm/DeviceManagerApi$DeviceNameResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/SnapshotAgent$DriveIdQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveIdResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveFile;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveResource;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveResource$MetadataResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$TitleMetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/StringMetadataField;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/BaseMetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableMetadataField;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/SortableMetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$ModifiedMetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/DateMetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/OrderedMetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableOrderedMetadataField;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/BasicFields$MimeTypeMetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/internal/model/File;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/postprocessor/PostProcessorHelper;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveApi$DriveContentsResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/operations/snapshots/OpenSnapshotOperation$SnapshotOpenData;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/Agents$TwoColumnMapper;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/snapshot/SnapshotMetadataChange$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/service/PlaySnapshotEventService;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/chimera/DriveEventService;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/ExecutionOptions;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/MetadataChangeSet;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/ImageUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveFolder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/internal/DriveFolderImpl;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/internal/DriveResourceImpl;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFolderResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/SnapshotListResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/DriveFolder$DriveFileResult;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/Query$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/SearchableField;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/SearchableCollectionMetadataField;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/InFilter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/ComparisonFilter;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/Operator;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/HasFilter;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/AppVisibleCustomProperties;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/SortOrder$Builder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/metadata/internal/fields/DateFields$CreatedMetadataField;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/internal/FieldWithSortOrder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/drive/query/SortOrder;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/util/IOUtils;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/StatsAgent;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/StatsApi;,
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/StatsResponse;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitiesApiInternal;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$MatchEntities;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/FirstPartyMultiplayerEntity;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/Room;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatch;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/multiplayer/InvitationBuffer;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/multiplayer/Invitation;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/multiplayer/Participatable;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/multiplayer/Participant;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$SyncNetworkResponse;,
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerAgent$VersionInfo;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/MultiplayerUtils;,
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/MultiplayerEntitySyncFirstParty;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApi;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomsApiInternal;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/NetworkDiagnostics;,
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/RealTimeAgent$RoomCache;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomJoinRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/constants/Capability;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomClientAddress;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomCreateRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomAutoMatchingCriteria;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomLeaveRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomP2PStatuses;,
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/RoomStatus;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApi;
,I/HwLauncher( 3916): Launcher  onWindowVisibilityChanged visibility = 4
,I/HwLauncher( 3916): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3916): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchesApiInternal;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchResults;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/MatchParticipantResult;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/TurnBasedAgent$PendingOpsQuery;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/server/response/FastParser;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchTurn;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchDataRequest;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchCreateRequest;,
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedAutoMatchingCriteria;
,I/ActivityManager( 3040): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/internal/constants/TurnBasedMatchStatus;
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/multiplayer/turnbased/TurnBasedMatchBuffer;
,I/ActivityManager( 3040): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/server/api/TurnBasedMatchRematch;
,W/ResourceType( 3040): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/VideoAgent;
,I/HwLauncher( 3916): Launcher onStart()
I/HwLauncher( 3916): Launcher dynamicIconsRegister
I/HwLauncher( 3916): DynamicUpdater registerReceiver
,I/HwSystemManager( 6579): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 6579): HsmPackageManager:replacing:false
I/HwSystemManager( 6579): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 6579): HsmPackageManager:doAppRemoved, remove:com.example.hello
I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10302
I/HwSystemManager( 4196): HoldService:uid:10302 pid:6054 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10302,6054
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10302, pid: 6054
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10302, pid: 6054
I/HwSystemManager( 4196): AppLockService:applock password not initial or function is closed
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/recorder/captors/ScreenCaptureController$CaptureStateCallback;
,W/GeofencerStateMachine( 3605): Ignoring removeGeofence because network location is disabled.
,I/AccountTypeManager( 6515): Adding account type = com.android.contacts.model.account.ExchangeAccountType@1cb3f763 in the cache
,I/HwLauncher( 3916): DynamicUpdater call updateFolder
I/HwSystemManager( 4196): AppManager:getNetAppInfoFromDB cursor lenth = 1
I/HwLauncher( 3916): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3916): DynamicUpdater registerReceiver
I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:0
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/ui/video/ScreenCaptureOverlay$CaptureOverlayListener;
I/InputReader( 3040): Reconfiguring input devices.  changes=0x00000010
,I/HwLauncher( 3916): DynamicUpdater call updateFolder
I/HwLauncher( 3916): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3916): DynamicUpdater registerReceiver
,I/SimFactoryManager( 6515): Get SIM state from SIM factory manager: 1,For slotId:1
,I/AccountTypeManager( 6515): Adding account type = com.android.contacts.model.account.ExternalAccountType@792af60 in the cache
,E/RegisteredServicesCache( 3850): invalidateCache set mNeedToastTableFull
,W/ResourceType( 6515): For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
,W/ResourceType( 6515): Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
,W/ResourceType( 6515): For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
,W/ResourceType( 6515): Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
I/AccountTypeManager( 6515): Adding account type = com.android.contacts.model.account.ExternalAccountType@2f241c19 in the cache
,I/AccountTypeManager( 6515): Adding account type = com.android.contacts.model.account.GoogleAccountType@2745c4de in the cache
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/provider/GamesContractInternal$GamesUris;
,W/PGApi_client( 3800): recv actoionId = 10010, action = com.huawei.pgmng.PGAction@f1bdd17 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3800): in handleAction method, action = 10010
W/PGMiddleWare jhh( 3800): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@2ff4e64b, action = com.huawei.pgmng.PGAction@f1bdd17 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3800): jhh handle default mActionId = 10010, action = com.huawei.pgmng.PGAction@f1bdd17 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3800): enter into the safetyguard Scene.
W/AudioEffectLowPowerImpl jhh( 3800): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
,W/AudioEffectLowPowerImpl jhh( 3800): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3800): return for smartPAOn and mLowAudioEffectEnable both = false
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/AccountAgent$MetadataQuery;
,E/ExternalAccountType( 6515): Unsupported attribute readOnly
,W/asset   ( 3040): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/AccountTypeManager( 6515): AccountManager, account size is: 2
,I/art     ( 4196): Explicit concurrent mark sweep GC freed 90654(5MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 14MB/23MB, paused 1.375ms total 106.799ms
I/HwSystemManager( 4196): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/HwSystemManager( 4196): HsmPackageManager:replacing:false
I/HwSystemManager( 4196): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 4196): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/AccountTypeManager( 6515): Loaded meta-data for 5 account types, 3 accounts in 83ms(wall) 21ms(cpu)
,I/HwLauncher( 3916): DynamicUpdater call updateFolder
I/HwLauncher( 3916): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3916): Launcher onResume()
I/UpdateIcingCorporaServi( 6337): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/HwLauncher( 3916): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
,I/HwLauncher( 3916): Launcher doResumeWork()
I/HwLauncher( 3916): Launcher.MotionManager startMotionAppsReco 402
,I/HwLauncher( 3916): Launcher  onResume mIsToUninstallApp = false
,W/System.err( 3040): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,I/HwSystemManager( 4196): ww:deleteLockData:com.example.hello
,W/System.err( 3040): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3040): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 3040): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 3040): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3040): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3040): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/HwLauncher( 3916): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3916): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/Agents$1;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/games/broker/Agents$2;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/ClientContextCreator;
,I/HwLauncher( 3916): Launcher  onWindowVisibilityChanged visibility = 0
I/art     ( 3040): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
I/HwLauncher( 3916): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3916): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,I/art     ( 3040): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
I/art     ( 3040): Can not find class: Lhuawei/com/android/server/util/ReportTool;
,I/art     ( 3040): Can not find class: Lcom/huawei/report/ReporterInterface;
I/art     ( 5899): Can not find class: Lcom/google/android/gms/common/internal/GmsLogger;
E/ReportTools( 3040): Can't find sReporterClazz
,I/art     ( 3040): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/art     ( 3040): Can not find class: Lhuawei/com/android/server/util/AppInfo;
,W/System.err( 3040): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,E/GameAgent( 5899): Caller attempted to insert game data for non-existent package.
E/GameAgent( 5899): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
E/GameAgent( 5899): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
E/GameAgent( 5899): 	at com.google.android.gms.games.broker.GameAgent.registerGame(GameAgent.java:1562)
E/GameAgent( 5899): 	at com.google.android.gms.games.broker.DataBroker.registerGame(DataBroker.java:3120)
E/GameAgent( 5899): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
E/GameAgent( 5899): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:978)
E/GameAgent( 5899): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/GameAgent( 5899): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/GameAgent( 5899): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/GameAgent( 5899): 	at java.lang.Thread.run(Thread.java:831)
W/System.err( 3040): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3040): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3040): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 3040): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 3040): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 3040): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 3040): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 3040): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 3040): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 3040): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 3040): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3040): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3040): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3040): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 3040): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 3040): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3040): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3040): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3040): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 3040): This is not beta user build
I/PhoneStatusBar( 3498): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/HwLauncher( 3916): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3916): Model replacing = false package = com.example.hello
I/HwLauncher( 3916): Model  ACTION_PACKAGE_REMOVED replacing = false
I/HwLauncher( 3916): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
I/HwLauncher( 3916): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
I/HwLauncher( 3916): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
,I/HwLauncher( 3916): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3916): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3916): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3916): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3916): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,W/asset   ( 6789): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/PhoneStatusBar( 3498): shouldTranslucent:true
,I/PhoneStatusBar( 3498): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/PG Utils( 3916): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6789): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,I/HwCust  ( 6789): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/PG Utils( 3916): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,I/HwLauncher( 3916): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,I/HwLauncher( 3916): Model mAllAppsList.removePackage com.example.hello
,I/HwLauncher( 3916): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3916):  stringArray[] [unknown]
,E/HideAppsPagedView( 3916): removeItems begin 
E/HideAppsPagedView( 3916): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3916): removeItems end 
,I/HwLauncher( 3916): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
,W/System.err( 3916): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3916): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3916): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3916): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3916): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3916): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3916): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3916): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3916): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3916): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
W/System.err( 3916): java.lang.NullPointerException: null receiver
W/System.err( 3916): 	at java.lang.reflect.Field.get(Native Method)
,W/System.err( 3916): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3916): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3916): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3916): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3916): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3916): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3916): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3916): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3916): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwLauncher( 3916): CellLayout rearrangeAfterRmItem isAutoAlign = false
,W/MotionDetectionManager( 3916): startMotionAppsReco motionApps: 402 disabled
,W/HwLauncher( 3916): Launcher.MotionManager startMotionAppsReco service flg 402 is unavailable
,I/art     ( 3040): Explicit concurrent mark sweep GC freed 24474(1638KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 27MB/41MB, paused 1.730ms total 381.169ms
,E/HideAppsPagedView( 3916): removeHideApps  begin 
E/HideAppsPagedView( 3916): removeHideApps  end 
E/HideAppsPagedView( 3916):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3916):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3916):  createAddIcon count = 0
,I/HwLauncher( 3916):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwSystemManager( 4196): BgPowerManagerService:onProcessDied uid = 10087
I/HwSystemManager( 4196): HoldService:uid:10087 pid:5843 died
I/HwSystemManager( 4196): HoldService:oldVersionKey:10087,5843
E/HsmCoreServiceImpl( 3040): onTransact in code is: 102
I/MediaProcessHandler( 3040): processOp opType: 1, uid: 10087, pid: 5843
W/MediaProcessHandler( 3040): remove target not exist, maybe the UI process: uid: 10087, pid: 5843
,I/MusicStore( 6765): Database version: 120
,I/HwEmailTag( 6457): HwUtils->triggerPeriodSync->
,I/HwEmailTag( 6457): EmailProvider->call->triggerPeroidSync,accountId:-1
I/HwEmailTag( 6457): EmailProvider->triggerPeroidSync->accountId:-1
,I/Icing   ( 5899): updateResources: need to parse f{com.google.android.gms}
,I/PG Utils( 6765): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/ContextImpl( 6765): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/ContextImpl( 6765): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ContextImpl( 6765): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/OpenGLRenderer( 3916): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 3916): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/art     ( 6765): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6765): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@217f4cdf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6765): Installed default security provider GmsCore_OpenSSL
,W/SharedPreferencesImpl( 5899): writeToFile: Got exception:
W/SharedPreferencesImpl( 5899): java.io.IOException: write failed: EROFS (Read-only file system)
W/SharedPreferencesImpl( 5899): 	at libcore.io.IoBridge.write(IoBridge.java:509)
W/SharedPreferencesImpl( 5899): 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
W/SharedPreferencesImpl( 5899): 	at com.android.internal.util.FastXmlSerializer.flushBytes(FastXmlSerializer.java:232)
W/SharedPreferencesImpl( 5899): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:253)
W/SharedPreferencesImpl( 5899): 	at com.android.internal.util.FastXmlSerializer.endDocument(FastXmlSerializer.java:198)
W/SharedPreferencesImpl( 5899): 	at com.android.internal.util.XmlUtils.writeMapXml(XmlUtils.java:188)
W/SharedPreferencesImpl( 5899): 	at android.app.SharedPreferencesImpl.writeToFile(SharedPreferencesImpl.java:597)
W/SharedPreferencesImpl( 5899): 	at android.app.SharedPreferencesImpl.access$800(SharedPreferencesImpl.java:51)
W/SharedPreferencesImpl( 5899): 	at android.app.SharedPreferencesImpl$2.run(SharedPreferencesImpl.java:512)
W/SharedPreferencesImpl( 5899): 	at android.app.SharedPreferencesImpl.enqueueDiskWrite(SharedPreferencesImpl.java:533)
W/SharedPreferencesImpl( 5899): 	at android.app.SharedPreferencesImpl.access$100(SharedPreferencesImpl.java:51)
W/SharedPreferencesImpl( 5899): 	at android.app.SharedPreferencesImpl$EditorImpl.commit(SharedPreferencesImpl.java:455)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.r.a(SourceFile:449)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.b.f.l(SourceFile:470)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.b.ab.a(SourceFile:153)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.b.ab.a(SourceFile:104)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.b.ab.b(SourceFile:88)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.u.a(SourceFile:1898)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.u.a(SourceFile:1798)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.ak.e(SourceFile:460)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.ak.a(SourceFile:454)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.g.c.run(SourceFile:281)
W/SharedPreferencesImpl( 5899): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/SharedPreferencesImpl( 5899): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/SharedPreferencesImpl( 5899): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
W/SharedPreferencesImpl( 5899): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
W/SharedPreferencesImpl( 5899): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/SharedPreferencesImpl( 5899): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/SharedPreferencesImpl( 5899): 	at com.google.android.gms.icing.g.g.run(SourceFile:50)
W/SharedPreferencesImpl( 5899): 	at java.lang.Thread.run(Thread.java:831)
W/SharedPreferencesImpl( 5899): Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
W/SharedPreferencesImpl( 5899): 	at libcore.io.Posix.writeBytes(Native Method)
W/SharedPreferencesImpl( 5899): 	at libcore.io.Posix.write(Posix.java:223)
W/SharedPreferencesImpl( 5899): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
W/SharedPreferencesImpl( 5899): 	at libcore.io.IoBridge.write(IoBridge.java:504)
W/SharedPreferencesImpl( 5899): 	... 29 more
,I/ConfigStore( 6765): Config Database version: 1
E/SharedPreferencesImpl( 5899): Couldn't clean up partially-written file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml
E/SharedPreferencesImpl( 5899): Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml
E/SQLiteDatabase( 6765): Failed to open database '/data/data/com.google.android.music/databases/config.db'.
E/SQLiteDatabase( 6765): android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/SQLiteDatabase( 6765): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/SQLiteDatabase( 6765): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6765): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6765): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/SQLiteDatabase( 6765): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 6765): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/SQLiteDatabase( 6765): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteDatabase( 6765): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteDatabase( 6765): 	at android.content.ContentResolver.query(ContentResolver.java:489)
E/SQLiteDatabase( 6765): 	at android.content.ContentResolver.query(ContentResolver.java:426)
E/SQLiteDatabase( 6765): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/SQLiteDatabase( 6765): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/SQLiteDatabase( 6765): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/SQLiteDatabase( 6765): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/SQLiteDatabase( 6765): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/SQLiteDatabase( 6765): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/SQLiteDatabase( 6765): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/SQLiteDatabase( 6765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase( 6765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/SQLiteDatabase( 6765): 	at android.app.ActivityThread.access$1900(ActivityThread.java:152)
E/SQLiteDatabase( 6765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1402)
E/SQLiteDatabase( 6765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6765): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6765): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
E/SQLiteDatabase( 6765): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6765): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
E/SQLiteDatabase( 6765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/SharedPreferencesImpl( 5899): Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml
E/AndroidRuntime( 6765): FATAL EXCEPTION: main
E/AndroidRuntime( 6765): Process: com.google.android.music:main, PID: 6765
E/AndroidRuntime( 6765): java.lang.RuntimeException: Unable to create application com.google.android.music.MusicApplication: android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/AndroidRuntime( 6765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4802)
E/AndroidRuntime( 6765): 	at android.app.ActivityThread.access$1900(ActivityThread.java:152)
E/AndroidRuntime( 6765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1402)
E/AndroidRuntime( 6765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6765): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6765): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
E/AndroidRuntime( 6765): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6765): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
E/AndroidRuntime( 6765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/AndroidRuntime( 6765): Caused by: android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
E/AndroidRuntime( 6765): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
E/AndroidRuntime( 6765): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6765): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6765): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/AndroidRuntime( 6765): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 6765): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/AndroidRuntime( 6765): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/AndroidRuntime( 6765): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/AndroidRuntime( 6765): 	at android.content.ContentResolver.query(ContentResolver.java:489)
E/AndroidRuntime( 6765): 	at android.content.ContentResolver.query(ContentResolver.java:426)
E/AndroidRuntime( 6765): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/AndroidRuntime( 6765): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/AndroidRuntime( 6765): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/AndroidRuntime( 6765): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/AndroidRuntime( 6765): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/AndroidRuntime( 6765): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/AndroidRuntime( 6765): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/AndroidRuntime( 6765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime( 6765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime( 6765): 	... 9 more
I/art     ( 3040): Can not find class: Lcom/android/server/am/ActivityManagerService$21;
I/art     ( 3040): Can not find class: Lcom/android/server/am/AppErrorResult;
E/SharedPreferencesImpl( 5899): Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml
W/System.err( 3040): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
W/System.err( 3040): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 3040): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 3040): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 3040): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 3040): 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1425)
W/System.err( 3040): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3040): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3040): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3040): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/ReportTools( 3040): This is not beta user build
I/Process ( 6765): Sending signal. PID: 6765 SIG: 9
,I/PG Utils( 3040): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
E/SharedPreferencesImpl( 5899): Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml
I/HwEmailTag( 6457): EmailProvider->query->1449413989201;end;;consuming:2ms;
I/HwEmailTag( 6457): EmailProvider->query->1449413989206;end;;consuming:2ms;
E/SharedPreferencesImpl( 5899): Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml
E/SharedPreferencesImpl( 5899): Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml
I/PG Utils( 5899): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,E/JavaBinder( 3040): !!! FAILED BINDER TRANSACTION !!!
,I/art     ( 3040): Can not find class: Lcom/android/server/power/Notifier$2;
,I/KeyguardFingerprint.Validation( 3358): start
,E/AuthenticationManager( 3358): AuthenticationManager open failed: the AuthenticationService is null
W/KeyguardFingerprint.Utils( 3358): AuthenticationManager open return null
I/KeyguardFingerprint.Validation( 3358): Fingerprint unlock is not enabled
I/KeyguardViewMediator( 3358): fingerprint validation not started
,E/hwcomposer( 2294): setTopResource:1220: set top resource failed!! ret:-1 
E/hwcomposer( 2294): comp_mode= 0
E/hwcomposer( 2294): disp_ch_res = 0x3 
E/hwcomposer( 2294): res_info.ovly1_res = 0xc 
E/hwcomposer( 2294): res_info.ovly2_res = 0x0 
E/hwcomposer( 2294): res_info.ovly3_res = 0x0
E/hwcomposer( 2294): res_info.rot_res = 0x0
E/hwcomposer( 2294): res_info.scl2_res = 0x0
E/hwcomposer( 2294): res_info.compose_ch_res[0] = 0x0
E/hwcomposer( 2294): res_info.compose_ch_res[1] = 0x0
E/hwcomposer( 2294): res_info.compose_ch_res[2] = 0x0
E/hwcomposer( 2294): res_info.compose_ch_res[3] = 0x0
E/hwcomposer( 2294): res_info.compose_ch_res[4] = 0x0
E/hwcomposer( 2294): res_info.compose_ch_res[5] = 0x0
E/hwcomposer( 2294): ade_reg_res = 0x0
E/hwcomposer( 2294): setGlobal:234: setTopResource fail!! 
E/hwcomposer( 2294): setRegionInfo:817: set region info failed!! ret:-1 
E/hwcomposer( 2294): compose_mode(0), 	 ch_index(6)
E/hwcomposer( 2294): ch_type(0),  	 surface_num(0)
E/hwcomposer( 2294): blending(0xff0105),  	 dim_blending(0x0)
E/hwcomposer( 2294): format(5),  	 height(1280),  	 width(720),  	 rotation(0), 	 sharefd(21)
E/hwcomposer( 2294): phy_addr(0x402000),  	 sec_ovly_ch_count(0),  	 sec_ovly_surf_num(0)
E/hwcomposer( 2294): stride(2880),  	 dst_height(1280),  	 dst_width(720)
E/hwcomposer( 2294): src_rect xywh(0,0,720,1280),  	 dst_rect xywh(0,0,720,1280)
E/hwcomposer( 2294): ovly_output_rect xywh(0,0,720,1280),  	 clip_right(0) 	 uv_addr(0)
E/hwcomposer( 2294): commit:654: commit failed!! ret:-1, frame_number:371, 
E/hwcomposer( 2294): is_finished  (1), 	 compose mode (0), 	 compose pattern num (3072) 
E/hwcomposer( 2294): dst_rotation (0), 	 dst_rect xywh (0,0,720,1280), 	 src_rect xywh (0,0,720,1280) 
E/hwcomposer( 2294): offline_dst_format (0), 	 offline_dst_rect xywh (0,0,0,0) 
E/hwcomposer( 2294): offline_phy_addr (0x0), 	 offline_stride (0), 	 offline_frame_phy_addr (0x0) 
E/hwcomposer( 2294): rot_height (0), 	 rot_width (0), 	 offline_frame_share_fd (0) 
E/hwcomposer( 2294): wifi_dst_format (0), 	 wifi_phy_addr (0x0), 	 wifi_stride (0)
E/hwcomposer( 2294): wifi_dst_rect xywh (0,0,0,0), 	 wifi_src_rect xywh (0,0,0,0)
E/hwcomposer( 2294): scl2_src_rect xywh (0,0,0,0), 	 scl2_dst_rect xywh (0,0,0,0)
E/hwcomposer( 2294): play:197: play commit error
E/hwcomposer( 2294): enableVsync:1073: vsync ioctl failed 
E/hwcomposer( 2294): EventControl:120: vsync ioctl failed
E/SurfaceFlinger( 2294): eventControl(0, 1) failed Operation not permitted

```
