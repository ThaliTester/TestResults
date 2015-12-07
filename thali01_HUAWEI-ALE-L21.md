#### Test 50242285e707819_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/ActivityManager( 2944): filter receiver for action = com.android.providers.calendar.intent.CalendarProvider2
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
W/MediaProcessHandler( 2944): processOp uid 1000 is not concerned!
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3868): HoldService:uid:1000 pid:5084 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:1000,5084
I/PGSocket( 3566): socket:android.net.LocalSocket@25ece12 impl:android.net.LocalSocketImpl@191369e3 fd:FileDescriptor[37] bw:java.io.BufferedWriter@20196fe0
I/HwSystemManager( 3868): HoldService:uid:10030 pid:5105 died
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10030
I/HwCust  ( 3630): Constructor found for class com.android.stk.HwCustStkAppServiceImpl
I/HwSystemManager( 3868): HoldService:oldVersionKey:10030,5105
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10030, pid: 5105
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10030, pid: 5105
E/STK App ( 3630): StkAppService refreshCatService fail
E/STK App ( 3630): StkAppService refreshCatService fail
I/HwCust  ( 5515): Constructor found for class org.simalliance.openmobileapi.service.HwCustSmartcardServiceImpl
I/SUPL20_Config( 3652):  supl version 2
I/SUPL20_Config( 3652): UDP socket enabled = false
I/SUPL20_Config( 3652): pcm socketpath is /data/gnss/pcm_socthe orginal parsed value is/data/gnss/pcm_soc
I/SUPL20_Config( 3652): scm socketpath is /data/gnss/scm_socthe orginal parsed value is/data/gnss/scm_soc
I/SUPL20_Config( 3652): UDP socket enabled = false
I/HwCust  ( 5515): Constructor found for class org.simalliance.openmobileapi.service.terminals.HwCustUiccTerminalImpl
I/UiccTerminal( 5515): get the TelephonyAPDU instance is success ,the real class is com.android.telephonyapdu.ITelephonyAPDU$Stub$Proxy
I/UiccTerminal( 5515): get the TelephonyAPDU instance is success ,the real class is com.android.telephonyapdu.ITelephonyAPDU$Stub$Proxy
I/SUPL20_Config( 3652): KeyStore Valid =true
I/SUPL20_Config( 3652): KeyStore Path = /system/etc/security
I/SUPL20_Config( 3652): ConnectionTimeOut :15
I/SUPL20_Config( 3652): ConnectionRetries:5
I/SUPL20_Config( 3652): PCMPort:9001
I/SUPL20_Config( 3652): PCMFQDN:127.0.0.1
I/SUPL20_Config( 3652): SCMPort:9002
I/SUPL20_Config( 3652): SCMFQDN:127.0.0.1
I/SUPL20_Config( 3652): PCMUnixSocPath:/data/gnss/pcm_soc
I/SUPL20_Config( 3652): SCMUnixSocPath:/data/gnss/scm_soc
E/SUPL20_Config( 3652): /system/etc/gnss/config/SuplConfig.spl not found 
E/SUPL20_Config( 3652): java.io.FileNotFoundException: /system/etc/gnss/config/SuplConfig.spl: open failed: ENOENT (No such file or directory)
E/SUPL20_Config( 3652): 	at libcore.io.IoBridge.open(IoBridge.java:463)
E/SUPL20_Config( 3652): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
E/SUPL20_Config( 3652): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
E/SUPL20_Config( 3652): 	at java.io.FileReader.<init>(FileReader.java:66)
E/SUPL20_Config( 3652): 	at com.android.supl.config.ConfigManager.loadKeyStorePath(ConfigManager.java:217)
E/SUPL20_Config( 3652): 	at com.android.supl.config.ConfigManager.<init>(ConfigManager.java:207)
E/SUPL20_Config( 3652): 	at com.android.supl.config.ConfigManager.getInstance(ConfigManager.java:196)
E/SUPL20_Config( 3652): 	at com.android.supl.loc.SUPLPlatformService.onCreate(SUPLPlatformService.java:114)
E/SUPL20_Config( 3652): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2858)
E/SUPL20_Config( 3652): 	at android.app.ActivityThread.access$2200(ActivityThread.java:152)
E/SUPL20_Config( 3652): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SUPL20_Config( 3652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SUPL20_Config( 3652): 	at android.os.Looper.loop(Looper.java:135)
E/SUPL20_Config( 3652): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
E/SUPL20_Config( 3652): 	at java.lang.reflect.Method.invoke(Native Method)
E/SUPL20_Config( 3652): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SUPL20_Config( 3652): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
E/SUPL20_Config( 3652): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/SUPL20_Config( 3652): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
E/SUPL20_Config( 3652): 	at libcore.io.Posix.open(Native Method)
E/SUPL20_Config( 3652): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/SUPL20_Config( 3652): 	at libcore.io.IoBridge.open(IoBridge.java:449)
E/SUPL20_Config( 3652): 	... 17 more
I/SUPL20_Config( 3652): key store path and pd taken from the config xml file
I/SUPL20_Config( 3652): stPd = 123456
I/SUPL20_Config( 3652): Path = /system/etc/security
I/SmartcardService( 5515): Initializing Access Control
I/SmartcardService( 5515): NOT initializing Access Control for SIM SE not present.
I/SmartcardService( 5515): OnPostExecute()
E/SUPL20_NC( 3652): iConnType = 0
I/SUPL20_SCMService( 3652): Support for MultiBearer
E/SUPL20_NC( 3652): iConnType = 0
I/SUPL20_SCMService( 3652): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3652): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3652): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3652): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3652): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3652): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3652): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3652): network type:0 ,UNKNOWN
I/art     ( 2944): Explicit concurrent mark sweep GC freed 14120(730KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.537ms total 160.469ms
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10032
I/HwSystemManager( 3868): HoldService:uid:10032 pid:5138 died
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10032, pid: 5138
I/HwSystemManager( 3868): HoldService:oldVersionKey:10032,5138
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10032, pid: 5138
,I/HwSystemManager( 3868): HoldService:uid:10004 pid:3697 died
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10004
I/HwSystemManager( 3868): HoldService:oldVersionKey:10004,3697
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10004, pid: 3697
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10004, pid: 3697
I/appproc ( 5612): CLASSPATH=/system/framework/am.jar
I/appproc ( 5612): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 5612): app_process:number,5,0
I/AndroidRuntime( 5612): readDownloadBoosterConfig: 'false'
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10059
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10059, pid: 5185
I/HwSystemManager( 3868): HoldService:uid:10059 pid:5185 died
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10059, pid: 5185
I/HwSystemManager( 3868): HoldService:oldVersionKey:10059,5185
I/        ( 5612): power log dlsym ok
E/android_hardware_fm.cpp( 5612): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 5612): ========64bit long size = 8
E/FM_HAL  ( 5612): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 5612): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 5612): 
I/fm_hisi ( 5612): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 5612): 
I/fm_hisi ( 5612): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 5612): 
E/android_hardware_fm.cpp( 5612): register_android_hardware_fm_fmradio, ret is 0
I/PG Utils( 5615): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 2944): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2944): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2944): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2944): Can not find class: Lcom/android/server/wm/StartingData;
I/HwLauncher( 3674): Launcher onPause()
I/HwLauncher( 3674): Launcher.MotionManager stopMotionAppsReco 402
I/HwLauncher( 3674): Launcher.MotionManager stopMotionAppsReco 403
I/art     ( 5615): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
W/System  ( 5615): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5615): Installed default security provider GmsCore_OpenSSL
W/HwLauncher( 3674): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
I/art     ( 2944): Can not find class: Landroid/widget/ViewStub;
I/art     ( 2944): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 2944): Can not find class: Landroid/app/ViewStub;
W/HwLauncher( 3674): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
I/art     ( 2944): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/art     ( 3674): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3674): Can not find class: Lhuawei/android/widget/EditText;
E/textview( 3674): initAddtionalStyle default
W/System.err( 2944): java.lang.SecurityException: WifiService: Neither user 10087 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2944): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2944): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2944): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2944): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2944): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2944): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2944): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 5615): WifiServiceMessenger == null
I/PhoneStatusBar( 3208): shouldTranslucent:true
I/PhoneStatusBar( 3208): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwSystemManager( 3868): AppLockService:applock password not initial or function is closed
W/PGApi_client( 3566): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@122b1299 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3566): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3566): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@3fbf8862, action = com.huawei.pgmng.PGAction@122b1299 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3566): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@122b1299 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3566): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3566): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3566): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3566): return for smartPAOn and mLowAudioEffectEnable both = false
I/HwLauncher( 3674): Launcher onStop()
I/HwLauncher( 3674): Launcher dismissDialog
I/HwLauncher( 3674): Launcher dynamicIconsUnregister
I/HwLauncher( 3674): DynamicUpdater unregisterReceiver
I/HwLauncher( 3674): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3674): DynamicUpdater unregisterReceiver
I/HwLauncher( 3674): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3674): DynamicUpdater unregisterReceiver
I/HwLauncher( 3674): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3674): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3674): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/HwSystemManager( 5426): HsmStat_info:service connect
I/WebViewFactory( 5661): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/LibraryLoader( 5661): Loading: webviewchromium
I/LibraryLoader( 5661): Time to load native libraries: 4 ms (timestamps 8662-8666)
I/LibraryLoader( 5661): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 5661): Expected native library version number "",actual native library version number ""
I/chromium( 5661): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5661): Initializing chromium process, renderers=0
W/art     ( 5661): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5661): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
I/HwSystemManager( 3868): AppLockService:applock password not initial or function is closed
W/chromium( 5661): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5661): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 5661): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
W/asset   ( 3674): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
I/dex2oat ( 5706): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=default --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-300379680.jar --oat-fd=33 --oat-location=/data/data/com.google.android.youtube/cache/ads-300379680.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/YouTube MDX( 5615): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/dex2oat ( 5706): dex2oat took 49.131ms (threads: 8)
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/e;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/l;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/i;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/g;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/m;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/f;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/k;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/j;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/d;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/c;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/b;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/h;
I/art     ( 5615): Can not find class: Lcom/google/android/ads/zxxz/a;
W/chromium( 5661): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5661): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5661): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/ContextImpl( 5615): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
I/MultiDex( 5728): VM with version 2.1.0 has multidex support
I/MultiDex( 5728): install
I/MultiDex( 5728): MultiDexExtractor.load(/data/app/com.google.android.gms-2/base.apk, false)
I/MultiDex( 5728): loading existing secondary dex files
I/MultiDex( 5728): load found 3 secondary dex files
I/MultiDex( 5728): install done
I/System  ( 5615): core_booster, getBoosterConfig = false
I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
W/art     ( 5661): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5661): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 5661): Can not find class: Landroid/widget/ViewStub;
I/art     ( 5661): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 5661): Can not find class: Landroid/app/ViewStub;
W/ContextImpl( 5615): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
W/art     ( 5661): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5661): Attempt to remove local handle scope entry from IRT, ignoring
W/ContextImpl( 5615): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
I/art     ( 5728): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
W/System  ( 5728): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f378ced: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5728): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.INITIALIZE
W/ContextImpl( 5615): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 5615): Found 10007
I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
W/ContextImpl( 5615): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/OpenGLRenderer( 5661): Initialized EGL, version 1.4
I/SUPL20_PCM( 3652): calling nc.connect for pcm
I/SUPL20_NC( 3652): Calling getLocalSocket for PCM
I/SUPL20_NC( 3652): deque initialized
I/SUPL20_NC( 3652): WriterThread initialize
I/SUPL20_NC( 3652): readerThread initialized
I/SUPL20_PCM( 3652): process icmdID: 0X101
I/SUPL20_PCM( 3652): process hello msg
I/SUPL20_PCM( 3652): init msg success
I/SUPL20_PCM( 3652): sendHelloMessage
I/SUPL20_PCM( 3652): process: process less then zero 0
I/SUPL20_LocMan( 3652): register the Emergency Receiver 
I/SUPL20_SPIMESLP-SENDING( 3652): m_bPacket.length 12
I/SUPL20_SPIMESLP-SENDING( 3652): bBrokenPipe = false
I/SUPL20_PCM( 3652): process icmdID: 0X103
I/SUPL20_PCM( 3652):  process MSG_PCM_GET_LOCATION_ID
I/SUPL20_PCM( 3652): process: process less then zero 0
I/SUPL20_SCM( 3652): calling nc.connect for scm
I/SUPL20_NC( 3652): Calling getLocalSocket for SCM
I/SUPL20_PCM( 3652): process icmdID: 0X11a
I/SUPL20_NC( 3652): deque initialized
I/SUPL20_NC( 3652): WriterThread initialize
I/SUPL20_PCM( 3652):  process MSG_PCM_GET_HIST_KEY
I/SUPL20_NC( 3652): readerThread initialized
I/SUPL20_SCM( 3652): buffer size:12writePosition: 12
I/SUPL20_SCM( 3652): process icmdID2: 0X201
I/SUPL20_SCM( 3652): process hello msg
I/SUPL20_SCM( 3652): init msg success
I/SUPL20_SCM( 3652): sendHelloMessage
I/SUPL20_LocMan( 3652): SIM state :1
I/SUPL20_SPIMESLP-SENDING( 3652): m_bPacket.length 12
I/SUPL20_LocMan( 3652): Registered MyPhoneStateListener
I/SUPL20_SPIMESLP-SENDING( 3652): bBrokenPipe = false
I/ActivityManager( 2944): Displayed com.example.hello/.MainActivity: +996ms
I/art     ( 2944): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
W/PhoneInterfaceManager( 3630): shouldBlockLocation running ...
I/PhoneInterfaceManager( 3630): shouldBlockLocation  ret:false
E/SUPL20_LocMan( 3652): tm.getCellLocation() returned null
I/SUPL20_LocMan( 3652):  sim is not enabled on the SET
,I/SUPL20_LocMan( 3652): onServiceStateChanged ServiceState.STATE_POWER_OFF
,E/PhoneInterfaceManager( 3630): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/SUPL20_LocMan( 3652): Phone type:GSM
,I/SUPL20_LocMan( 3652): NULL Value received for network operator
,I/SUPL20_LocMan( 3652):  cellInfo NetworkType:UNKNOWN,0
,I/SUPL20_LocMan( 3652): onDataConnectionStateChanged networkType = 0
,I/SUPL20_LocMan( 3652): onDataConnectionStateChanged state = -1
,I/SUPL20_SPIMESLP-SENDING( 3652): m_bPacket.length 40
I/SUPL20_SPIMESLP-SENDING( 3652): bBrokenPipe = false
,W/PhoneInterfaceManager( 3630): shouldBlockLocation running ...
,I/PhoneInterfaceManager( 3630): shouldBlockLocation  ret:false
,E/SUPL20_LocMan( 3652): tm.getCellLocation() returned null
,I/SUPL20_LocMan( 3652): onDataConnectionStateChanged Unknown: -1
,I/art     ( 2944): Can not find class: Lcom/android/server/wm/DisplayContentList;
,I/SUPL20_PCM( 3652): Fetching the historic secret key ...
I/SUPL20_PCM( 3652): process: process less then zero 0
I/SUPL20_SPIMESLP-SENDING( 3652): m_bPacket.length 24
I/SUPL20_SPIMESLP-SENDING( 3652): bBrokenPipe = false
,I/chromium( 5661): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5661): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/PhoneInterfaceManager( 3630): shouldBlockLocation running ...
,I/PhoneInterfaceManager( 3630): shouldBlockLocation  ret:false
,E/SUPL20_LocMan( 3652): tm.getCellLocation() returned null
,I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10047
I/HwSystemManager( 3868): HoldService:uid:10047 pid:5213 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10047,5213
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 1000
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/HwSystemManager( 3868): HoldService:uid:1000 pid:5163 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:1000,5163
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10047, pid: 5213
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10047, pid: 5213
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
W/MediaProcessHandler( 2944): processOp uid 1000 is not concerned!
,I/chromium( 5661): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5661): 
,I/PG Utils( 5829): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Babel_SMS( 5829): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5829): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5829): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
I/Babel_SMS( 5829): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5829): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5829): MmsConfig.loadFromResources
,E/Babel_SMS( 5829): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5829): MmsConfig.loadMmsSettings: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
,W/jxcore-log( 5661): Initializing JXcore engine
W/jxcore-log( 5661): JXcore engine is ready
,W/jxcore-log( 5661): Starting JXcore engine
,I/CameraHalInterface( 2378): Found a matching camera info for ID 0
,I/CameraHalInterface( 2378): Found a matching camera info for ID 1
,W/Settings( 5829): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/System.err( 2944): java.lang.SecurityException: WifiService: Neither user 10058 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2944): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2944): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2944): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2944): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2944): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2944): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2944): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiManager( 5829): WifiServiceMessenger == null
,I/Babel_Crash( 5829): startup - clean
,I/Babel   ( 5829): deleted: false for 0
,I/AlarmInitReceiver( 5238): handleMessage : AlarmInitReceiver, will exit app. Config.exit_count: 0
I/art     ( 5238): System.exit called, status: 0
I/AndroidRuntime( 5238): VM exiting with result code 0, cleanup skipped.
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10045, pid: 5238
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10045, pid: 5238
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10045
I/HwSystemManager( 3868): HoldService:uid:10045 pid:5238 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10045,5238
W/jxcore-log( 5661): Platform android
W/jxcore-log( 5661): 
W/jxcore-log( 5661): Process ARCH arm
W/jxcore-log( 5661): 
W/VideoCapabilities( 5829): Unsupported mime video/mpeg
W/VideoCapabilities( 5829): Unsupported mime video/mpeg2
W/VideoCapabilities( 5829): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile/level 0/0 for video/3gpp
W/VideoCapabilities( 5829): Unrecognized profile 0 for video/3gpp
W/VideoCapabilities( 5829): Unsupported mime video/mp4
I/VideoCapabilities( 5829): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5829): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5829): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5829): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5829): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5829): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5829): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 5829): Unsupported profile 8 for video/mp4v-es
W/VideoCapabilities( 5829): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 5829): Unrecognized profile 0 for video/mp4v-es
W/VideoCapabilities( 5829): Unsupported mime video/mpeg4
W/VideoCapabilities( 5829): Unsupported mime video/x-flv
W/VideoCapabilities( 5829): Unsupported mime video/vc1
W/VideoCapabilities( 5829): Unsupported mime video/wvc1
W/VideoCapabilities( 5829): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 5829): Unsupported mime video/x-ms-wmv3
W/VideoCapabilities( 5829): Unsupported mime video/x-pn-realvideo
W/VideoCapabilities( 5829): Unsupported mime video/ffmpeg
W/AudioCapabilities( 5829): Unsupported mime audio/ffmpeg
I/jxcore-log( 5661): JXcore Cordova bridge is ready!
I/jxcore-log( 5661): 
W/jxcore-log( 5661): JXcore engine is started
I/VideoCapabilities( 5829): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager( 2944): filter receiver for action = com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION
,E/jxcore-log( 5661): >> HUAWEI-ALE-L21
E/jxcore-log( 5661): 
,I/jxcore-log( 5661): Total memory 1949741056
I/jxcore-log( 5661): 
,I/jxcore-log( 5661): Free memory 18128896
I/jxcore-log( 5661): 
I/jxcore-log( 5661): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5661): 
I/jxcore-log( 5661): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5661): 
,I/vclib   ( 5829): onServiceConnected
,W/Babel   ( 5829): Attempted to change video mute state without an active call.
,I/jxcore-log( 5661): userPath [ 'www' ]
I/jxcore-log( 5661): 
I/jxcore-log( 5661): Size 720 1184
I/jxcore-log( 5661): 
,I/jxcore-log( 5661): Screen Brightness 242
I/jxcore-log( 5661): 
E/jxcore-log( 5661): Dummy Error Log.
E/jxcore-log( 5661): 
,I/PG Utils( 5728): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/iu.UploadsManager( 5728): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/PG Utils( 5728): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5728): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/iu.UploadsManager( 5728): End new media; added: 0, uploading: 0, time: 39 ms
I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2944): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/PG Utils( 5873): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2944): filter receiver for action = com.google.android.gm.intent.ACTION_PROVIDER_CREATED
,I/Gmail   ( 5873): getAccountsCursor
,I/art     ( 2944): Can not find class: Lcom/android/server/accounts/AccountManagerService$GetAccountsByTypeAndFeatureSession;
I/art     ( 2944): Can not find class: Lcom/android/server/accounts/AccountManagerService$Session;
,I/art     ( 5873): Can not find class: Lcom/google/ads/AdRequest;
,W/GAV2    ( 5873): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 5873): Observing account changes for notifications
,I/jxcore-log( 5661): getBuffer is called!!!!
I/jxcore-log( 5661): 
,I/art     ( 2944): Explicit concurrent mark sweep GC freed 15920(830KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.762ms total 176.188ms
,E/Gmail   ( 5873): Error finding the version of the Email provider.....
E/Gmail   ( 5873): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5873): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:120)
E/Gmail   ( 5873): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5873): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5873): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5873): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5873): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5873): getAccountsCursor
,E/SQLiteLog( 5873): (283) recovered 28 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/SystemBroadcastReceiver( 5920): Boot has been completed
,I/SystemBroadcastReceiver( 5920): toggleAppIcon() : FLAG_SYSTEM = true
,I/SystemBroadcastReceiver( 5920): Killing my process: pid=5920
I/Process ( 5920): Sending signal. PID: 5920 SIG: 9
,I/Gmail   ( 5873): notifyAccountChanged
,I/PG Utils( 5873): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 5873): getAccountsCursor
,I/Gmail   ( 5873): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/PG Utils( 5873): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 5873): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5873): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5873): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     ( 2944): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10077, pid: 5920
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10077, pid: 5920
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10077
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10040
I/HwSystemManager( 3868): HoldService:uid:10077 pid:5920 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10077,5920
I/HwSystemManager( 3868): HoldService:uid:10040 pid:5273 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10040,5273
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10040, pid: 5273
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10040, pid: 5273
I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 196us total 22.978ms
I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 231us total 26.086ms
I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 204us total 22.630ms
,I/PG Utils( 5873): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5873): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5873): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5873): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 5873): getAccountsCursor
,E/Fabric  ( 5950): Unknown error while loading Crashlytics settings. Crashes will be cached until settings can be retrieved.
,E/WearSyncService( 5950): Failed to connect to GoogleApiClient within the timeout
,I/PG Utils( 6007): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/System.err( 2944): java.lang.SecurityException: WifiService: Neither user 10025 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2944): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2944): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2944): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2944): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2944): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2944): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2944): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 6007): WifiServiceMessenger == null
,W/Settings( 6007): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6007): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PG Utils( 6007): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6007): acquire_providerpkg:[com.android.providers.downloads] pid:[]  maybe timeout , send to PG
,I/art     ( 5728): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/InstanceID/Rpc( 5728): Found 10007
,I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3868): HoldService:uid:1000 pid:5310 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:1000,5310
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
W/MediaProcessHandler( 2944): processOp uid 1000 is not concerned!
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/CheckinService( 5728): Checkin interval check for package: unspecified last checkin: 1449217171307 min interval config: 0 actual interval: 281785779
,I/CheckinService( 5728): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 5728): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 3533): DispatchingService.onCreate()
,I/CheckinService( 5728): Checking schedule, now: 1449498957164 next: 1449807432251
I/CheckinService( 5728): active receiver: disabled
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/SystemUpdateService( 5728): cancelUpdate (empty URL)
I/SystemUpdateService( 5728): active receiver: disabled
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.security.snet.BOOT_COMPLETED
,I/GCoreUlr( 3533): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 5728): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,I/art     ( 5728): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5728): Can not find class: Lcom/google/android/gms/common/h/c;
I/art     ( 5728): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2944): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3533): Explicit concurrent mark sweep GC freed 27107(1687KB) AllocSpace objects, 9(180KB) LOS objects, 40% free, 17MB/29MB, paused 5.459ms total 120.033ms
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 3761): Explicit concurrent mark sweep GC freed 8132(499KB) AllocSpace objects, 3(60KB) LOS objects, 40% free, 17MB/29MB, paused 6.607ms total 168.154ms
,I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2944): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/GCoreUlr( 3533): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 3533): Unbound from all location providers
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3533): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GCoreUlr( 3533): DispatchingService.onDestroy()
I/GCoreUlr( 3533): Stopping handler for UlrDispSvcFast
,I/art     ( 5728): Explicit concurrent mark sweep GC freed 47253(3MB) AllocSpace objects, 34(680KB) LOS objects, 40% free, 17MB/29MB, paused 3.540ms total 111.294ms
,W/BaseAppContext( 5728): Using Auth Proxy for data requests.
,I/AuthZen ( 5728): Fetching signing key...
,W/GCoreFlp( 3533): No location to return for getLastLocation()
,W/FusedLocationProvider( 5728): location=null
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/AuthZen ( 5728): Signing key fetched successfully!
,W/Kids    ( 5728): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 5728): [KidAccountFixer] No network connection
,W/GCoreFlp( 3533): No location to return for getLastLocation()
,W/FusedLocationProvider( 5728): location=null
,W/BaseAppContext( 5728): Using Auth Proxy for data requests.
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 2944): Explicit concurrent mark sweep GC freed 18095(994KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 27MB/41MB, paused 1.887ms total 203.126ms
,I/GCoreUlr( 3533): Unbound from all location providers
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/Auth    ( 3761): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6105): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6105): acquire_providerpkg:[com.google.android.partnersetup] pid:[]  maybe timeout , send to PG
,I/VelvetNetworkClient( 6105): Network connection not availble
,I/PG Utils( 6135): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6135): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/SearchBackgroundTaskFac( 6105): Checking for language pack updates
,I/VelvetNetworkClient( 6105): Network connection not availble
,I/GservicesUpdateTask( 6105): Updating Gservices keys
,I/PG Utils( 6105): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/VelvetNetworkClient( 6105): Network connection not availble
,I/HwCust  ( 6166): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl
,I/PG Utils( 6166): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,W/StubController( 6189): calendar access!
,I/PG Utils( 6166): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6166): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6166): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/HwCust  ( 6166): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
,I/PG Utils( 6166): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwCust  ( 6166): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
,E/ContactsProtector( 6166): getHiCloudAccountData query fail
I/PG Utils( 6166): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3507): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
,I/WebViewFactory( 6105): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/HwCust  ( 6166): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
,I/LibraryLoader( 6105): Loading: webviewchromium
,I/LibraryLoader( 6105): Time to load native libraries: 4 ms (timestamps 4252-4256)
,I/LibraryLoader( 6105): Expected native library version number "",actual native library version number ""
,I/HwSystemManager( 3868): HoldService:uid:10001 pid:4694 died
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10001
I/HwSystemManager( 3868): HoldService:oldVersionKey:10001,4694
I/PG Utils( 6189): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10001, pid: 4694
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10001, pid: 4694
,I/HwCust  ( 6166): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
,W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
,W/StubController( 6227): calendar access!
,E/        ( 2944): open /proc/4694/smaps fail errno 2
E/        ( 2944): open /proc/5238/smaps fail errno 2
E/        ( 2944): open /proc/5273/smaps fail errno 2
E/        ( 2944): open /proc/5310/smaps fail errno 2
,I/PG Utils( 6105): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3868): ContactsObserverHelper:Receive contacts change broadcast
,W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
,W/RefreshDomainCookieTask( 6105): Search parameters fetch failed: com.google.android.apps.gsa.shared.api.io.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
W/RefreshDomainCookieTask( 6105): Search parameters fetch failed
,W/Search.LoginHelper( 6105): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 6105): java.io.IOException: NetworkError
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 6105): 	at java.lang.Thread.run(Thread.java:831)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/StubController( 6189): calendar access!
,I/PG Utils( 6189): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/Search.LoginHelper( 6105): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 6105): java.io.IOException: NetworkError
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 6105): 	at java.lang.Thread.run(Thread.java:831)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/StubController( 6189): calendar access!
,I/CalendarSimpleUiPRovider( 6189): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 6189): onConfigurationChanged
,I/PG Utils( 6189): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/StubController( 6189): calendar access!
,I/CalendarSimpleUiPRovider( 6189): initParams20151207T153558Europe/Warsaw(1,340,3600,0,1449498958)
,W/Search.LoginHelper( 6105): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 6105): java.io.IOException: NetworkError
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 6105): 	at java.lang.Thread.run(Thread.java:831)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/StubController( 6189): calendar access!
,I/HwSystemManager( 3868): HoldService:uid:10052 pid:5332 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10052,5332
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10052, pid: 5332
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10052
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10052, pid: 5332
,W/StubController( 6189): calendar access!
,W/Search.LoginHelper( 6105): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 6105): java.io.IOException: NetworkError
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 6105): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 6105): 	at java.lang.Thread.run(Thread.java:831)
W/Search.LoginHelper( 6105): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,I/ActivityManager( 2944): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10104, pid: 4881
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10104
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10104, pid: 4881
I/HwSystemManager( 3868): HoldService:uid:10104 pid:4881 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10104,4881
,I/CalendarSimpleUiPRovider( 6189): loadEvent end update UI0
,I/HwLauncher( 3674): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwLauncher( 3674): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwLauncher( 3674): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3674): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3674): Model STK reName intent is received.
I/HwLauncher( 3674): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3674): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3674): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3674): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3674): Model STK reName intent is received.
,I/HwLauncher( 3674): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3674): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3674): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3674): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3674): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3674): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3674): Model mAllAppsList.updatePackage com.android.stk
I/HwLauncher( 3674): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3674): Launcher.Folder childCount: 5
I/HwLauncher( 3674): Launcher.Folder childCount: 5
,I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 6
I/HwLauncher( 3674): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3674): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3674): Launcher.Folder childCount: 6
I/HwLauncher( 3674): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3674): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3674): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3674):  syncPages mCurrentPage = 0
I/HwLauncher( 3674): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3674): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3674): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3674): Model shortcutInfo.title = SIM Toolkit
,E/HideAppsPagedView( 3674):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3674):  createAddIcon count = 0
,I/HwLauncher( 3674):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3674): Launcher Deferring update until onResume
I/HwLauncher( 3674): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3674): Launcher.Folder childCount: 5
I/HwLauncher( 3674): Launcher.Folder childCount: 5
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 6
I/HwLauncher( 3674): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwEmailTag( 6283): MailAppProvider->onCreate->begin, consuming 1449498959367ms->-prefixstartupperformance-
,I/HwLauncher( 3674): Launcher.Folder childCount: 6
I/HwLauncher( 3674): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3674): Launcher.Folder childCount: 7
I/HwLauncher( 3674): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3674):  syncPages mCurrentPage = 0
,E/HideAppsPagedView( 3674):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3674):  createAddIcon count = 0
,I/HwLauncher( 3674):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3674): Launcher Deferring update until onResume
,I/HwEmailTag( 6283): MailAppProvider->onCreate->end, consuming 1449498959396ms->-prefixstartupperformance-
,I/HwCust  ( 6283): Constructor found for class com.android.email.service.HwCustImapServiceImpl
,I/HwCust  ( 6283): Constructor found for class com.android.email.HwCustUtilityImpl
,I/HwCust  ( 6283): Constructor found for class com.android.email.provider.HwCustEmailProviderImpl
,I/HwCust  ( 6283): Constructor found for class com.android.email.activity.setup.HwCustEmailInviteResponseImpl
,I/HwEmailTag( 6283): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6283): EmailProvider->onCreate->start. -prefixstartupperformance-
I/HwEmailTag( 6283): HwUtils->initStaticVarsAsync
I/HwEmailTag( 6283): HwUtils->initStaticVarsAsync
,I/HwCust  ( 6283): Constructor found for class com.android.emailcommon.provider.HwCustPolicyImpl
,I/HwEmailTag( 6283): EmailContent->init->consuming:17ms->;-prefixstartupperformance-
,I/HwEmailTag( 6283): EmailProvider->sURIMatcher is initialized
I/HwEmailTag( 6283): EmailProvider->INTEGRITY_CHECK_URI != null
,I/HwEmailTag( 6283): EmailProvider->onCreate->end, consuming 34ms->-prefixstartupperformance-
I/HwEmailTag( 6283): EmailProvider->onCreate->end, consuming 34ms->-prefixstartupperformance-
,I/HwEmailTag( 6283): EmailProvider->resetVisibleLimits->start:1449498959457 ->-prefixstartupperformance-
,I/HwEmailTag( 6283): EmailProvider->resetVisibleLimits->start:1449498959458 ->-prefixstartupperformance-
I/HwCust  ( 6283): Constructor found for class com.huawei.email.provider.HwCustRecipientDBHelperImpl
,I/HwEmailTag( 6283): HwUtils->initStaticVarsAsync->run:consuming:47ms; bidiFormatter:android.support.v4.text.BidiFormatter@1719b098;accountsProjSize:42
,I/HwEmailTag( 6283): EmailApplication->onCreate->begin, consuming 51ms->-prefixstartupperformance-
,I/HwEmailTag( 6283): HwUtils->initStaticVarsAsync->run:consuming:49ms; bidiFormatter:android.support.v4.text.BidiFormatter@1719b098;accountsProjSize:42
I/HwEmailTag( 6283): EmailApplication->triggerPeriodSyncForAllAccountsDelayed->delay start.
,I/HwEmailTag( 6283): DBHelper->onOpen-> EmailProvider.db
,I/HwCust  ( 6283): Constructor found for class com.huawei.email.utils.HwCustSignatureHelperImpl
,I/HwCust  ( 6283): Constructor found for class com.huawei.email.utils.HwCustSignatureUtilsImpl
,I/HwEmailTag( 6283): EmailApplication->onCreate->end, consuming 57ms->-prefixstartupperformance-
,I/HwEmailTag( 6283): BaseWidgetProvider->WidgetProvider->onReceive->action is com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/HwEmailTag( 6283): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 28ms.
,I/HwEmailTag( 6283): DBHelper->onOpen-> EmailProvider.db
,W/StubController( 6189): calendar access!
,I/HwEmailTag( 6283): EmailProvider->initBuildCache->start->1449498959523->-prefixstartupperformance-
,I/HwEmailTag( 6283): EmailProvider->buildCache->end, consuming:1ms;
I/HwEmailTag( 6283): EmailProvider->initBuildCache->start->1449498959523; consuming:1->-prefixstartupperformance-
,I/HwEmailTag( 6283): EmailProvider->uiAccounts->start:1449498959525
,I/HwEmailTag( 6283): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6283): EmailProvider->getDatabase->-prefixstartupperformance-database, consuming = 12ms.
,I/HwEmailTag( 6283): DBHelper->onOpen-> EmailProvider.db
,I/HwEmailTag( 6283): EmailProvider->resetVisibleLimits->getDatabase, consuming:104ms;-prefixstartupperformance-
I/HwEmailTag( 6283): EmailProvider->resetVisibleLimits->getDatabase, consuming:103ms;-prefixstartupperformance-
I/HwEmailTag( 6283): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
I/HwEmailTag( 6283): EmailProvider->startupperformance->resetVisibleLimits->no account, return directly.
,I/HwEmailTag( 6283): EmailProvider->uiAccounts->start:1449498959525;end,consuming:40
I/HwEmailTag( 6283): EmailProvider->query->1449498959456;end;;consuming:109ms;
,I/PG Utils( 6189): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10050, pid: 5378
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10050, pid: 5378
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10050
I/HwSystemManager( 3868): HoldService:uid:10050 pid:5378 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10050,5378
,I/ActivityManager( 2944): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/ActivityManager( 2944): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/CalendarProvider2( 6227): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6227): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 2944): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/HwCust  ( 6317): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
,W/HWContacts( 6317): ProviderFeatureChcker - cootek package not installed
,I/BluetoothAdapter( 5661): Start to disable Bluetooth!
,E/TmoMonitor( 6317): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@34e0c20a
,E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10056
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10056, pid: 5404
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10056, pid: 5404
I/HwSystemManager( 3868): HoldService:uid:10056 pid:5404 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10056,5404
,I/HwSystemManager( 3868): HoldService:checkBeforeShowDialog: uid:10302 pid:5661, permissionType:2097152
I/HwSystemManager( 3868): OverseaCfgHelper:permissionStatus is 0
,I/ConnectPermission( 2944): allowOpenWifi blocked:false
,I/jxcore-log( 5661): ****TEST TOOK:  5097  ms ****
I/jxcore-log( 5661): 
,I/jxcore-log( 5661): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5661): 
,I/HwCust  ( 6317): Constructor found for class com.android.mms.data.HwCustConversationImpl
,I/EmuiFeatureManager( 6317): loadEmailAnrSupportFlag:true
,I/Mms_threadcache( 6317): [RecipientIdCache] fill: begin
,I/SimFactoryManager( 6317): Inside init method of SimFactoryManger the combination is:-1
,I/SimFactoryManager( 6317): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6317): isSIM1CardPresent:1
,I/SimFactoryManager( 6317): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6317): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 6317): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/SimFactoryManager( 6317): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6317): isSIM2CardPresent:1
,I/SimFactoryManager( 6317): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6317): Get SIM state from SIM factory manager: 1,For slotId:1
I/SimFactoryManager( 6317): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/HwCust  ( 6317): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
,E/MmsConfig( 6317): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
,I/HwCust  ( 6317): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
,I/art     ( 6317): Can not find class: Lhuawei/android/view/TableLayout;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/TableLayout;
,I/art     ( 6317): Can not find class: Lhuawei/android/view/View;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/View;
I/art     ( 6317): Can not find class: Landroid/widget/View;
I/art     ( 6317): Can not find class: Landroid/webkit/View;
,I/art     ( 6317): Can not find class: Landroid/app/View;
,I/HwLauncher( 3674): Model  onReceive intent=Intent { act=android.intent.action.TIME_TICK flg=0x50000014 (has extras) }
,I/TimeManager( 3208): receiver action = android.intent.action.TIME_TICK
,I/TimeManager( 3208): send message delay millis = 60990 ms
I/TimeManager( 3208): hand message 1
I/TimeManager( 3208): notify time change. size = 2
,I/TimeLayout( 3208): time = 15:36
,I/art     ( 6317): Can not find class: Lhuawei/android/view/TableRow;
I/art     ( 6317): Can not find class: Lhuawei/android/widget/TableRow;
,I/art     ( 6317): Can not find class: Lhuawei/android/view/LinearLayout;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/LinearLayout;
I/TimeLayout( 3208): updateDate date = 12/7/2015
,I/TimeLayout( 3208): weekDay = Monday
,I/HwCust  ( 6317): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
,I/art     ( 6317): Can not find class: Lhuawei/android/view/ImageButton;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/ImageButton;
,I/art     ( 6317): Can not find class: Lhuawei/android/view/TextView;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/TextView;
,I/HwCust  ( 6317): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
,I/art     ( 6317): Can not find class: Lhuawei/android/view/RelativeLayout;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/RelativeLayout;
,I/art     ( 6317): Can not find class: Lhuawei/android/view/ImageView;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/ImageView;
,I/art     ( 6317): Can not find class: Lhuawei/android/view/ViewStub;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/ViewStub;
,I/art     ( 6317): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6317): Can not find class: Landroid/webkit/ViewStub;
,I/art     ( 6317): Can not find class: Landroid/app/ViewStub;
,I/appproc ( 6347): CLASSPATH=/system/framework/pm.jar
I/appproc ( 6347): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 6347): app_process:number,5,0
,I/AndroidRuntime( 6347): readDownloadBoosterConfig: 'false'
,I/GAV2    ( 5873): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 6317): Can not find class: Lhuawei/android/view/FrameLayout;
,I/PG Utils( 5728): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/art     ( 6317): Can not find class: Lhuawei/android/widget/FrameLayout;
,I/art     ( 6317): Can not find class: Lhuawei/android/view/EditText;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/EditText;
I/GAv4-SVC( 5728): Google Analytics 8.3.01 is starting up.
,E/textview( 6317): initAddtionalStyle default
,I/art     ( 6317): Can not find class: Lhuawei/android/view/ProgressBar;
,I/art     ( 6317): Can not find class: Lhuawei/android/widget/ProgressBar;
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 6317): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,I/        ( 6347): power log dlsym ok
,E/android_hardware_fm.cpp( 6347): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6347): ========64bit long size = 8
E/FM_HAL  ( 6347): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 6347): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6347): 
I/fm_hisi ( 6347): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6347): 
I/fm_hisi ( 6347): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6347): 
,E/android_hardware_fm.cpp( 6347): register_android_hardware_fm_fmradio, ret is 0
,I/art     ( 2944): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/art     ( 2944): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,I/art     ( 2944): Explicit concurrent mark sweep GC freed 17689(1089KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 27MB/41MB, paused 2.268ms total 188.229ms
I/art     ( 2944): WaitForGcToComplete blocked for 175.290ms for cause HeapTrim
,I/HwLauncher( 3674): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,I/ActivityManager( 2944): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,W/GeofencerStateMachine( 3533): Ignoring removeGeofence because network location is disabled.
,W/ResourceType( 2944): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,I/ActivityManager( 2944): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/InputReader( 2944): Reconfiguring input devices.  changes=0x00000010
,I/HwLauncher( 3674): Launcher onStart()
I/HwLauncher( 3674): Launcher dynamicIconsRegister
I/HwLauncher( 3674): DynamicUpdater registerReceiver
,E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10302, pid: 5661
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10302, pid: 5661
,I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10302
,I/HwSystemManager( 3868): HoldService:uid:10302 pid:5661 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10302,5661
,E/RegisteredServicesCache( 3609): invalidateCache set mNeedToastTableFull
,W/asset   ( 2944): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 3868): Explicit concurrent mark sweep GC freed 87665(5MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 14MB/23MB, paused 968us total 71.168ms
I/HwSystemManager( 3868): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 3868): HsmPackageManager:replacing:false
I/HwSystemManager( 3868): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 3868): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwSystemManager( 3868): ww:deleteLockData:com.example.hello
,W/PGApi_client( 3566): recv actoionId = 10010, action = com.huawei.pgmng.PGAction@1757b95e actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3566): in handleAction method, action = 10010
W/PGMiddleWare jhh( 3566): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@3fbf8862, action = com.huawei.pgmng.PGAction@1757b95e actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3566): jhh handle default mActionId = 10010, action = com.huawei.pgmng.PGAction@1757b95e actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3566): enter into the safetyguard Scene.
W/AudioEffectLowPowerImpl jhh( 3566): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
,W/AudioEffectLowPowerImpl jhh( 3566): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3566): return for smartPAOn and mLowAudioEffectEnable both = false
,I/HwLauncher( 3674): DynamicUpdater call updateFolder
I/HwLauncher( 3674): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3674): DynamicUpdater registerReceiver
,I/HwLauncher( 3674): DynamicUpdater call updateFolder
I/HwLauncher( 3674): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3674): DynamicUpdater registerReceiver
,I/HwLauncher( 3674): DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
,I/HwLauncher( 3674): DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,I/HwLauncher( 3674): DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
I/HwLauncher( 3674): DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,I/HwLauncher( 3674): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3674): ClockDynamicUpdater clock update folder at ClockDynamicUpdater
I/HwLauncher( 3674): DynamicUpdater updateBitmap end and send update message
,W/System.err( 2944): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,I/HwSystemManager( 3868): AppManager:getNetAppInfoFromDB cursor lenth = 1
,I/HwSystemManager( 3868): AppLockService:applock password not initial or function is closed
,W/System.err( 2944): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 2944): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 2944): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 2944): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2944): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2944): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/HwLauncher( 3674): DynamicUpdater call updateFolder
I/HwLauncher( 3674): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
I/HwLauncher( 3674): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3674): Launcher onResume()
I/HwLauncher( 3674): Launcher doResumeWork()
,I/HwLauncher( 3674): Launcher.MotionManager startMotionAppsReco 402
,I/HwLauncher( 3674): Launcher  onResume mIsToUninstallApp = false
,I/art     ( 2944): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,I/art     ( 2944): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,I/art     ( 2944): Can not find class: Lhuawei/com/android/server/util/ReportTool;
,I/art     ( 2944): Can not find class: Lcom/huawei/report/ReporterInterface;
,E/ReportTools( 2944): Can't find sReporterClazz
,I/art     ( 2944): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/art     ( 2944): Can not find class: Lhuawei/com/android/server/util/AppInfo;
,W/System.err( 2944): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 2944): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2944): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2944): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2944): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2944): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 2944): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 2944): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 2944): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 2944): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 2944): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 2944): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2944): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2944): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2944): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 2944): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 2944): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2944): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 2944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 2944): This is not beta user build
,I/art     ( 2944): Explicit concurrent mark sweep GC freed 11595(732KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 27MB/41MB, paused 2.536ms total 261.913ms
,I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3868): HoldService:uid:1000 pid:5426 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:1000,5426
,E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
W/MediaProcessHandler( 2944): processOp uid 1000 is not concerned!
,I/HwLauncher( 3674): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,W/asset   ( 6413): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 206us total 29.973ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 190us total 22.405ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 192us total 22.134ms
,I/HwLauncher( 3674): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3674): Model replacing = false package = com.example.hello
I/HwLauncher( 3674): Model  ACTION_PACKAGE_REMOVED replacing = false
I/HwLauncher( 3674): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
,I/HwLauncher( 3674): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
I/HwLauncher( 3674): Launcher  onWindowVisibilityChanged visibility = 0
I/HwLauncher( 3674): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3674): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,I/HwLauncher( 3674): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3674): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3674): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3674): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3674): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,I/PhoneStatusBar( 3208): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/HwLauncher( 3674): DynamicUpdater call updateFolder
,I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 3868): HoldService:uid:10065 pid:5465 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:10065,5465
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
I/MediaProcessHandler( 2944): processOp opType: 1, uid: 10065, pid: 5465
W/MediaProcessHandler( 2944): remove target not exist, maybe the UI process: uid: 10065, pid: 5465
I/HwSystemManager( 3868): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3868): NotificationManagerReceiver:onReceive, send action to background
I/HwSystemManager( 3868): ProcPolicy:begin get procName.
,I/HwSystemManager( 3868): ProcPolicy:this proc is:com.huawei.systemmanager:service
I/HwSystemManager( 3868): ProcPolicy:end get procName.
,I/HwSystemManager( 3868): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@17b1e246
,I/HwCust  ( 6413): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/HwSystemManager( 3868): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3868): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3868): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings]
,I/HwSystemManager( 3868): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
,I/HwSystemManager( 3868): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
I/HwSystemManager( 3868): NmCenterDefValueXmlHelper:getConfigs: Starts
,I/HwSystemManager( 3868): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33
I/HwCust  ( 6413): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
I/HwSystemManager( 3868): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
,I/PhoneStatusBar( 3208): shouldTranslucent:true
I/PhoneStatusBar( 3208): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/PG Utils( 3674): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,I/HwLauncher( 3674): Model mAllAppsList.removePackage com.example.hello
,W/HwSystemManager( 3868): NotificationDBAdapter:initNewApp: Fail to get uid , skip applying default cfg. pkgname = com.example.hello
,I/HwSystemManager( 3868): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3868): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 3868): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3868): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3868): HsmIntentService:last work complete! lets stop service.
I/HwSystemManager( 3868): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3868): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3868): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 3868): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3868): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3868): NotificationDBProvider:query starts, matchCode = 1
,I/PhoneStatusBar( 3208): notification pkg =com.android.settings
I/PhoneStatusBar( 3208): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3208): notification pkg =android
I/PhoneStatusBar( 3208): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,I/HwLauncher( 3674): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,I/HwLauncher( 3674): WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
I/HwLauncher( 3674):  stringArray[] [unknown]
,I/art     ( 2325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 435us total 39.365ms
,W/asset   ( 6459): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 384us total 22.111ms
,I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 395us total 19.700ms
,I/HwEmailTag( 6283): EmailProvider->query->1449498961459;end;;consuming:2ms;
,I/HwEmailTag( 6283): EmailApplication->handleMessage->startService CleanRecipientAddressService
I/HwSystemManager( 6459): SystemManagerApplication:onCreate
E/HideAppsPagedView( 3674): removeItems begin 
E/HideAppsPagedView( 3674): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3674): removeItems end 
,I/HwSystemManager( 3868): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@17b1e246
I/HwSystemManager( 3868): BgPowerManagerService:onProcessDied uid = 1050
I/HwSystemManager( 3868): HoldService:uid:1050 pid:5491 died
I/HwSystemManager( 3868): HoldService:oldVersionKey:1050,5491
E/HsmCoreServiceImpl( 2944): onTransact in code is: 102
W/MediaProcessHandler( 2944): processOp uid 1050 is not concerned!
,I/HwEmailTag( 6283): Device->updateDeviceIdIfNeeded
,I/System.out( 6459): [ls, -l, /system/app/HwSystemManager/HwSystemManager.apk]
I/System.out( 6459): null
I/System.out( 6459): null
I/System.out( 6459): Calling by::className:bkk  MethodName:yw
I/HwEmailTag( 6283): CleanRecipient->onCreate
,I/HwLauncher( 3674): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
I/HwSystemManager( 3868): MainService:on startCommand,flags:0,startId:6
,W/System.err( 3674): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,E/SQLiteLog( 3674): (3850) statement aborts at 10: [DELETE FROM favorites4x5 WHERE _id=86] disk I/O error - SQLITE_IOERR_LOCK
I/PG Utils( 3674): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,I/HwEmailTag( 6283): CleanRecipient->onStartCommand->action is null
I/HwEmailTag( 6283): CleanRecipient->onHandleIntent->action is null
,W/System.err( 3674): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
E/HwLauncher( 3674): Launcher.LauncherProvider delete database fail Exception
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
,W/System.err( 3674): 	at java.lang.reflect.Field.get(Native Method)
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
I/HwEmailTag( 6283): Device->updateDeviceIdIfNeeded->doInBackground
I/HwEmailTag( 6283): Device->getDeviceId->
,I/HwSystemManager( 3868): LocalService:Received start id 6: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
,E/HideAppsPagedView( 3674): removeHideApps  begin 
E/HideAppsPagedView( 3674): removeHideApps  end 
E/HideAppsPagedView( 3674):  syncPages mCurrentPage = 0
,I/HwSystemManager( 3868): BgPowerManagerService:onStartCommand
,I/HwSystemManager( 3868): AppLockService:onStartCommand
,I/HwSystemManager( 3868): AppCleanUpService:onStartCommand() in!
,I/HwSystemManager( 6459): HsmStat_info:feature enable:false
,I/HwSystemManager( 6459): OverseaCfgHelper:permissionStatus is 0

```
