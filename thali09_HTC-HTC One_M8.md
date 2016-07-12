#### Test 757892685a40176_thali09_HTC-HTC One_M8 Logs


```
--------- beginning of main
07-12 17:45:03.123  5848  5867 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 205 ms] updated apps [took 205 ms] 
07-12 17:45:03.123   976  1089 D Process : killProcessQuiet, pid=4722
07-12 17:45:03.123   976  1089 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
--------- beginning of system
07-12 17:45:03.123   976  1089 I ActivityManager: Killing 4722:com.htc.mediamanager/u0a29 (adj 15): empty #17
07-12 17:45:03.143   976  1641 I ActivityManager: Recipient 4722
07-12 17:45:03.203  4125  5847 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-12 17:45:03.203  4125  5847 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-12 17:45:03.243   976  1641 D Process : killProcessQuiet, pid=4722
07-12 17:45:03.243   976  1641 W libprocessgroup: failed to open /acct/uid_10029/pid_4722/cgroup.procs: No such file or directory
07-12 17:45:03.243   976  1641 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:03.313  5869  5869 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
07-12 17:45:03.313  5869  5869 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 17:45:03.313  5869  5869 I GAv4    :   adb logcat -s GAv4
07-12 17:45:03.323  5869  5869 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-12 17:45:03.333  1439  1911 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-12 17:45:03.333  1439  1911 D PhoneApp: -- N1 =0
07-12 17:45:03.333  1439  1911 D PhoneApp: -- N2 =0
07-12 17:45:03.333  1439  1911 D PhoneApp: -- N3 =0
07-12 17:45:03.343  5869  5869 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-12 17:45:03.343  5869  5912 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-12 17:45:03.353  5869  5869 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
07-12 17:45:03.443   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
07-12 17:45:03.443   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 17:45:03.443  5869  5917 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
07-12 17:45:03.453  5869  5918 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 17:45:03.453  5869  5918 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-12 17:45:03.473   976  1635 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5919 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-12 17:45:03.473   976  1635 D Process : killProcessQuiet, pid=5019
07-12 17:45:03.473   976  1635 I ActivityManager: Killing 5019:com.google.android.talk/u0a120 (adj 15): empty #17
07-12 17:45:03.473   976  1635 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
07-12 17:45:03.493   976  1519 I ActivityManager: Recipient 5019
07-12 17:45:03.513   976  1519 D Process : killProcessQuiet, pid=5019
07-12 17:45:03.513   976  1519 W libprocessgroup: failed to open /acct/uid_10120/pid_5019/cgroup.procs: No such file or directory
07-12 17:45:03.513   976  1519 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:03.513   976  1067 D PMS     : acquireWL(1a1abd72): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 976 1000 WorkSource{1000}
07-12 17:45:03.513   976  1067 V AlarmManager: sending alarm PendingIntent{a12ab5: PendingIntentRecord{1ca0854a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=109078, Int=0
07-12 17:45:03.513   976  1067 V AlarmManager: sending alarm PendingIntent{3b4795c3: PendingIntentRecord{24ee5e40 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1468338303525, Int=0
07-12 17:45:03.523  5919  5919 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 17:45:03.533  1122  2206 D WeatherUtility: Weather sync is On
07-12 17:45:03.563  5869  5918 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
07-12 17:45:03.603  1122  2206 D WeatherUtility: Weather sync is On
07-12 17:45:03.603  5869  5918 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-12 17:45:03.603  5869  5918 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-12 17:45:03.603   976   992 D PMS     : acquireWL(2d33ebe): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1409 10054 null
07-12 17:45:03.613  1746  1746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 17:45:03.673   976  1521 D PMS     : acquireWL(1131b558): PARTIAL_WAKE_LOCK  AsyncService 0x1 5919 10176 null
07-12 17:45:03.683   976  1482 D PMS     : releaseWL(1131b558): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-12 17:45:03.683   976  1089 D PMS     : acquireWL(3a066796): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5919 10176 null
07-12 17:45:03.693   976  1636 D PMS     : releaseWL(3a066796): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
07-12 17:45:03.723   976   976 D PMS     : acquireWL(1c4dff17): PARTIAL_WAKE_LOCK  *backup* 0x1 976 1000 null
07-12 17:45:03.723   976   976 D PMS     : releaseWL(1a1abd72): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
07-12 17:45:03.723   976  1089 I ActivityManager: Killing 5476:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
07-12 17:45:03.723   976  1089 D Process : killProcessQuiet, pid=5476
07-12 17:45:03.723   976  1089 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-12 17:45:03.723   976  1091 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
07-12 17:45:03.733   976  1091 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
07-12 17:45:03.733   976  1091 D PMS     : releaseWL(1c4dff17): PARTIAL_WAKE_LOCK  *backup* 0x1 null
07-12 17:45:03.733   976  1637 I ActivityManager: Recipient 5476
07-12 17:45:03.813   976  1637 D Process : killProcessQuiet, pid=5476
07-12 17:45:03.813   976  1637 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:03.813   976  1637 W libprocessgroup: failed to open /acct/uid_10079/pid_5476/cgroup.procs: No such file or directory
,07-12 17:45:04.173  4125  4205 I Icing   : Indexing 133D3F44B423C1F90B90CE261AE1222BFA42C728 from com.google.android.googlequicksearchbox
07-12 17:45:04.203  4125  4205 D Icing   : Loaded CLD2 Version V2.0 - 20141016
07-12 17:45:04.213  5946  5956 E cutils-trace: Error opening trace file: No such file or directory (2)
07-12 17:45:04.243  4125  4205 I Icing   : Indexing done 133D3F44B423C1F90B90CE261AE1222BFA42C728
07-12 17:45:04.253   976  1303 D PMS     : releaseWL(11fe782f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
07-12 17:45:04.253   976  1482 D Process : killProcessQuiet, pid=5549
07-12 17:45:04.253   976  1482 I ActivityManager: Killing 5549:com.htc.bgp/u0a11 (adj 15): empty #17
07-12 17:45:04.253   976  1482 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-12 17:45:04.263   976  1636 I ActivityManager: Recipient 5549
07-12 17:45:04.273  5946  5946 D CustomizationManager: ====startRecUseTime====
07-12 17:45:04.273  5946  5946 D htc.customization.log.level:  is 
07-12 17:45:04.273  5946  5946 W CustomizationLogLevel: Level value is invalid, use default level 2
07-12 17:45:04.313   976  1636 D Process : killProcessQuiet, pid=5549
07-12 17:45:04.313   976  1636 W libprocessgroup: failed to open /acct/uid_10011/pid_5549/cgroup.procs: No such file or directory
07-12 17:45:04.313   976  1636 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:04.353  5946  5946 D CustomizationManager:  Read ACC file spent 0.046 (s)
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__001
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__102
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__203
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__405
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__304
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__032
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__016
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-12 17:45:04.353  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__A48
07-12 17:45:04.363  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__K18
07-12 17:45:04.363  5946  5946 D CIDMapFileReader: Parsing tag item name = HTC__002
07-12 17:45:04.363  5946  5946 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
07-12 17:45:04.363  5946  5946 I CustomizationCIDLoader: Parsing tag category name = system
07-12 17:45:04.363  5946  5946 I CustomizationCIDLoader: Parsing tag category name = application
07-12 17:45:04.363  5946  5946 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-12 17:45:04.363  5946  5946 I CustomizationCIDLoader: Parsing tag category name = Settings
07-12 17:45:04.363  5946  5946 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-12 17:45:04.363  5946  5946 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-12 17:45:04.363  5946  5946 I CustomizationCIDLoader: Parsing tag category name = ACC
07-12 17:45:04.363  5946  5946 D CustomizationManager:  Read CID file spent 0.088 (s)
07-12 17:45:04.363  5946  5946 D CustomizationManager:  All configurations done spent 0.088 (s)
07-12 17:45:04.383  5946  5946 E ActTriggerJNI: open library fail.
07-12 17:45:04.393  2267  2283 E MP-Decision: Update arg 2
07-12 17:45:04.393   976   991 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 17:45:04.393   976  1039 D PMS     : acquireHCC(35db8ced): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 976 1000 null
07-12 17:45:04.393   976  1039 D PMS     : acquireHCC(3fb96722): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 976 1000 null
07-12 17:45:04.393  2267  2283 E MP-Decision: Update arg 4
07-12 17:45:04.413  2267  2283 E MP-Decision: Update arg "0 190 240 240".
07-12 17:45:04.413  2267  2283 E MP-Decision: Update arg "0 75 400 400".
07-12 17:45:04.423   976   991 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5976 uid=10192 gids={50192, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-12 17:45:04.443   976   976 V ActivityManager: Display changed displayId=0
07-12 17:45:04.443  1200  1200 D DotMatrix: [EventService]  onDisplayChanged: 0
07-12 17:45:04.443  1200  1200 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
07-12 17:45:04.483  1483  1483 I TrimMemoryManager: [trimMemory] 20
07-12 17:45:04.513  5976  5976 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-12 17:45:04.533  5976  5976 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3634-3635)
07-12 17:45:04.533  5976  5976 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:04.543  5976  5976 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {295c7158}
07-12 17:45:04.543  5976  5976 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:04.543  5976  5976 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 17:45:04.563  5976  5976 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-12 17:45:04.563  5976  5976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:45:04.563  5976  5976 E SysUtils: ApplicationContext is null in ApplicationStatus
07-12 17:45:04.573  5976  5999 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-12 17:45:04.573  5976  5976 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-12 17:45:04.573  5976  5976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:04.573  5976  5976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 17:45:04.583  5976  5976 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
07-12 17:45:04.583  5976  5976 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-12 17:45:04.583  5976  5976 I Adreno-EGL: Build Date: 12/11/14 Thu
07-12 17:45:04.583  5976  5976 I Adreno-EGL: Local Branch: 
07-12 17:45:04.583  5976  5976 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
07-12 17:45:04.583  5976  5976 I Adreno-EGL: Local Patches: NONE
07-12 17:45:04.583  5976  5976 I Adreno-EGL: Reconstruct Branch: NOTHING
07-12 17:45:04.633   976   991 W System.err: java.lang.Throwable: stack dump
07-12 17:45:04.633   976   991 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-12 17:45:04.633   976   991 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
07-12 17:45:04.633   976   991 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-12 17:45:04.633   976   991 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-12 17:45:04.633   976  1017 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-12 17:45:04.633   976  1017 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e03e82b:true
07-12 17:45:04.633  5976  6010 D BluetoothAdapter: 546630423: getState() :  mService = null. Returning STATE_OFF
,07-12 17:45:04.703  5976  5976 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,07-12 17:45:04.773   976  1264 I art     : Explicit concurrent mark sweep GC freed 23120(1287KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 860us total 66.203ms
07-12 17:45:04.783  5976  5976 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-12 17:45:04.793  5976  5976 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
07-12 17:45:04.793  5976  5976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:45:04.793  5976  5976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:45:04.833   976  1067 D PMS     : acquireWL(873321b): PARTIAL_WAKE_LOCK  *alarm* 0x1 976 1000 WorkSource{10025}
07-12 17:45:04.833   976  1067 V AlarmManager: sending alarm PendingIntent{e32bfb8: PendingIntentRecord{26553295 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=113926, Int=0
07-12 17:45:04.833   976   991 D PMS     : acquireWL(255e191): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1746 10025 WorkSource{10025 com.google.android.gms}
07-12 17:45:04.833   976   976 D PMS     : releaseWL(873321b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10025}
07-12 17:45:04.833  1746  6021 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
07-12 17:45:04.833  1746  6021 D libc    : [NET] android_getaddrinfofornet-, err=8
07-12 17:45:04.833  1746  6021 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
07-12 17:45:04.843  1746  6021 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-12 17:45:04.843  1746  6021 D libc    : [NET] android_getaddrinfo_proxy+
07-12 17:45:04.843  1746  6021 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-12 17:45:04.843   464  6024 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
07-12 17:45:04.843   464  6024 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-12 17:45:04.843   464  6024 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-12 17:45:04.843   464  6024 D libc    : [NET] android_getaddrinfofornet-, err=7
07-12 17:45:04.843  1746  6021 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-12 17:45:04.843   976  1521 D PMS     : releaseWL(255e191): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10025 com.google.android.gms}
07-12 17:45:04.843  5976  5976 D Atlas   : Validating map...
07-12 17:45:04.873   976  1000 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6025 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
07-12 17:45:04.873   976  1525 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-12 17:45:04.873  5976  6008 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-12 17:45:04.883   976  1016 D StatusBarManagerService: setSystemUiVisibility(0xc0000600)
07-12 17:45:04.883   976  1016 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:45:04.883   976  1016 D StatusBarManagerService: hiding MENU key
07-12 17:45:04.893   976  1016 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-12 17:45:04.893   976  1016 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:45:04.893   976  1016 D StatusBarManagerService: hiding MENU key
07-12 17:45:04.903  6025  6025 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-12 17:45:04.943  5976  5976 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3e100c59, mServedView=org.apache.cordova.engine.SystemWebView{366e901e VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3230b0ff
07-12 17:45:04.953   976   992 I InputMethodManagerService: Disable input method client, pid=1483
07-12 17:45:04.953   976   992 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-12 17:45:04.953  5976  5976 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
07-12 17:45:04.963   976  1018 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +513ms (total +557ms)
07-12 17:45:04.983  5976  5976 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5976
07-12 17:45:05.053  5976  5976 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-12 17:45:05.073  6025  6052 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-12 17:45:05.083  6025  6052 I Babel_SMS: MmsConfig.loadMmsSettings
07-12 17:45:05.113   976  1303 I ActivityManager: Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6056 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
07-12 17:45:05.153  6056  6056 W HtcWrapAdjustableCursorFactory: HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
07-12 17:45:05.153  5976  6043 D jxcore_app_log: JniHelper::setJavaVM(0xb8789b98), pthread_self() = -1180703512
07-12 17:45:05.153   976  1519 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6025, uid=10120, userID:0
07-12 17:45:05.163  6056  6056 D MessageFrequencyProvider: onCreate
07-12 17:45:05.163  5976  6043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:45:05.163  5976  6043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:45:05.163  5976  6043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:45:05.163  5976  6043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:45:05.163  5976  6043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 17:45:05.163  5976  6043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d5fa82 added. We now have 1 listener(s)
07-12 17:45:05.163  6056  6072 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string
07-12 17:45:05.163   976  1634 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 17:45:05.163  5976  6043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 50:2E:6C:AC:21:50
07-12 17:45:05.163  5976  6043 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "50:2E:6C:AC:21:50"
07-12 17:45:05.163  6056  6056 V GetPrviateResource: GetPrviateResource
07-12 17:45:05.163  5976  6043 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:05.163  5976  6043 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:05.173  6056  6071 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile
07-12 17:45:05.173  6056  6056 V GetPrviateResource: GetPrviateResource
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 50:2E:6C:AC:21:50
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 17:45:05.173  5976  6043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbfbdc9 added. We now have 1 listener(s)
07-12 17:45:05.173  6025  6052 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
07-12 17:45:05.173  6025  6052 I Babel_SMS: MmsConfig.loadFromDatabase
07-12 17:45:05.173  5976  6043 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:05.173  5976  6043 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 17:45:05.173   976  1079 D WifiService: New client listening to asynchronous messages
07-12 17:45:05.173  5976  6043 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 17:45:05.173   976   976 E WifiTrafficPoller: ADD_CLIENT: 7
07-12 17:45:05.173  5976  6043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:05.173  5976  6043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 17:45:05.173  5976  6043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 17:45:05.173  5976  6043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 17:45:05.173  5976  6043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:05.173   976   992 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-12 17:45:05.173  5976  6043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 50:2E:6C:AC:21:50
07-12 17:45:05.183  5976  6043 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 17:45:05.183  5976  6043 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:05.183  5976  6043 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:05.183  5976  6043 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 17:45:05.183  5976  6043 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:05.183  5976  6043 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:05.183  5976  6043 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:05.183  5976  6043 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:05.183  5976  6043 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:05.183  5976  6043 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 17:45:05.183  5976  6043 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:05.183  6025  6052 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-12 17:45:05.183  6025  6052 I Babel_SMS: MmsConfig.loadFromResources
07-12 17:45:05.183  5976  6043 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 17:45:05.183  6025  6052 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-12 17:45:05.183  6025  6052 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
07-12 17:45:05.183  6056  6056 D MessageCustFlag: sense_version=6.0
07-12 17:45:05.193  6056  6056 D BTAccessoryUtil: createReceiver
07-12 17:45:05.193  6056  6056 D BTAccessoryUtil: registerReceiver return intent = null
07-12 17:45:05.193  6056  6056 D MessageCustFlag: sku_id=99
07-12 17:45:05.203  5976  5976 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-12 17:45:05.203  6056  6056 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
07-12 17:45:05.203  6056  6056 W SystemReader: Cannot find qct_8960_interface, use default value instead
07-12 17:45:05.203  6025  6025 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:05.213  6025  6025 I Babel_Crash: startup - clean
07-12 17:45:05.213  6025  6079 I Babel   : deleted: false for 0
07-12 17:45:05.243   976  1502 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6025, uid=10120, userID:0
07-12 17:45:05.243   976  1637 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6025, uid=10120, userID:0
07-12 17:45:05.243   976  1264 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6025, uid=10120, userID:0
07-12 17:45:05.243   976  1634 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6025, uid=10120, userID:0
07-12 17:45:05.243   976  1636 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6025, uid=10120, userID:0
07-12 17:45:05.243   976  1519 I ActivityManager: Killing 5575:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
07-12 17:45:05.243   976  1519 D Process : killProcessQuiet, pid=5575
07-12 17:45:05.243   976  1519 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
07-12 17:45:05.263   976  1089 I ActivityManager: Recipient 5575
07-12 17:45:05.263   976  1079 D WifiService: Client connection lost with reason: 4
07-12 17:45:05.343   976  1089 D Process : killProcessQuiet, pid=5575
07-12 17:45:05.343   976  1089 W libprocessgroup: failed to open /acct/uid_1000/pid_5575/cgroup.procs: No such file or directory
07-12 17:45:05.343   976  1089 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:05.363  6025  6025 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-12 17:45:05.373  6025  6025 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-12 17:45:05.373  6025  6025 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 17:45:05.373  6025  6025 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-12 17:45:05.383  6025  6025 W AudioCapabilities: Unsupported mime audio/qcelp
07-12 17:45:05.383  6025  6025 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-12 17:45:05.403  6025  6025 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
,07-12 17:45:05.433  6025  6025 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-12 17:45:05.433  6025  6025 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 17:45:05.433  6025  6025 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-12 17:45:05.443  6025  6025 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,07-12 17:45:05.443   976  1637 D Process : killProcessQuiet, pid=5602,
07-12 17:45:05.443   976  1637 I ActivityManager: Killing 5602:com.htc.mobiledata/u0a48 (adj 15): empty #17
07-12 17:45:05.443   976  1637 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,07-12 17:45:05.453   976  1264 I ActivityManager: Recipient 5602,
,07-12 17:45:05.513   976  1264 D Process : killProcessQuiet, pid=5602,
07-12 17:45:05.513   976  1264 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:05.513   976  1264 W libprocessgroup: failed to open /acct/uid_10048/pid_5602/cgroup.procs: No such file or directory
,07-12 17:45:05.513  6025  6025 I vclib   : onServiceConnected,
07-12 17:45:05.513  6025  6025 W Babel   : Attempted to change video mute state without an active call.
,07-12 17:45:05.913  5976  6078 W jxcore-log: Initializing JXcore engine,
07-12 17:45:05.913  5976  6078 W jxcore-log: JXcore engine is ready
,07-12 17:45:05.973  5976  6078 W jxcore-log: Starting JXcore engine,
,07-12 17:45:06.053  5976  6078 W jxcore-log: Platform android,
07-12 17:45:06.053  5976  6078 W jxcore-log: 
07-12 17:45:06.053  5976  6078 W jxcore-log: Process ARCH arm
07-12 17:45:06.053  5976  6078 W jxcore-log: 
,07-12 17:45:06.253  5976  6078 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:45:06.253  5976  6078 I jxcore-log: 
,07-12 17:45:06.253  5976  6078 W jxcore-log: JXcore engine is started
,07-12 17:45:06.263  5976  6043 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,07-12 17:45:06.263  5976  5976 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:45:06.273  5976  6078 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-12 17:45:06.273  5976  6078 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-12 17:45:06.273  5976  5976 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-12 17:45:06.273  5976  5976 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-12 17:45:06.283   976  1089 I ActivityManager: Killing 5628:com.htc.calendar/u0a10 (adj 15): empty #17
07-12 17:45:06.283   976  1089 D Process : killProcessQuiet, pid=5628
07-12 17:45:06.283   976  1089 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityStack.destroyActivityLocked:3417 
07-12 17:45:06.283   976  1303 I ActivityManager: Recipient 5628
,07-12 17:45:06.323   976  1303 D Process : killProcessQuiet, pid=5628,
07-12 17:45:06.323  5976  6043 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 43ms. Plugin should use CordovaInterface.getThreadPool().
07-12 17:45:06.323   976  1303 W libprocessgroup: failed to open /acct/uid_10010/pid_5628/cgroup.procs: No such file or directory
07-12 17:45:06.323  5976  5976 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-12 17:45:06.323  5976  5976 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-12 17:45:06.323   976  1303 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:06.323  5976  5976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:06.323  5976  5976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:06.323  5976  5976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:06.323  5976  5976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:06.323  5976  5976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35d5fa82 removed from the list
07-12 17:45:06.323  5976  5976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:06.323  5976  5976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbfbdc9 removed from the list
07-12 17:45:06.323  5976  5976 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:06.323  5976  5976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-12 17:45:06.323  5976  5976 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 17:45:06.393   976  1039 D PMS     : releaseHCC(35db8ced): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
07-12 17:45:06.393   976  1039 D PMS     : releaseHCC(3fb96722): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-12 17:45:06.403  2267  2283 E MP-Decision: Update arg 1,
,07-12 17:45:06.533  6082  6085 E cutils-trace: Error opening trace file: No such file or directory (2),
,07-12 17:45:06.573  6082  6082 D CustomizationManager: ====startRecUseTime====
,07-12 17:45:06.583  6082  6082 D htc.customization.log.level:  is 
07-12 17:45:06.583  6082  6082 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-12 17:45:06.663  6082  6082 D CustomizationManager:  Read ACC file spent 0.046 (s),
,07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__001
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__102
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__203
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__405,
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__304
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__032
07-12 17:45:06.663  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-12 17:45:06.673  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__016,
07-12 17:45:06.673  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-12 17:45:06.673  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__A48
07-12 17:45:06.673  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__K18
07-12 17:45:06.673  6082  6082 D CIDMapFileReader: Parsing tag item name = HTC__002
07-12 17:45:06.673  6082  6082 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
,07-12 17:45:06.673  6082  6082 I CustomizationCIDLoader: Parsing tag category name = system
,07-12 17:45:06.673  6082  6082 I CustomizationCIDLoader: Parsing tag category name = application
,07-12 17:45:06.673  6082  6082 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,07-12 17:45:06.673  6082  6082 I CustomizationCIDLoader: Parsing tag category name = Settings
07-12 17:45:06.673  6082  6082 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
,07-12 17:45:06.673  6082  6082 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-12 17:45:06.673  6082  6082 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-12 17:45:06.673  6082  6082 D CustomizationManager:  Read CID file spent 0.096 (s)
,07-12 17:45:06.673  6082  6082 D CustomizationManager:  All configurations done spent 0.096 (s)
,07-12 17:45:06.693  6082  6082 E ActTriggerJNI: open library fail.
,07-12 17:45:06.703   976  1637 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=6082, uid=2000 userid=0
,07-12 17:45:06.703   976  1000 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=-1: uninstall pkg
07-12 17:45:06.703   976  1000 D Process : killProcessQuiet, pid=5976
,07-12 17:45:06.703   976  1000 I ActivityManager: Killing 5976:com.test.thalitest/u0a192 (adj 9): stop com.test.thalitest
07-12 17:45:06.703   976  1000 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,07-12 17:45:06.733   976   991 I ActivityManager: Recipient 5976
07-12 17:45:06.733   976  1079 D WifiService: Client connection lost with reason: 4
,07-12 17:45:06.773   976  1054 W PackageSettings: Skipping PackageSetting{2fe758d4 com.example.hello/10380} due to missing metadata
,07-12 17:45:06.813   976   991 W ActivityManager: Spurious death for ProcessRecord{a1f7c71 5976:com.test.thalitest/u0a192}, curProc for 5976: null,
07-12 17:45:06.813   976  1054 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=0: pkg removed
,07-12 17:45:06.823  1200  1200 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-12 17:45:06.823  1200  1200 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-12 17:45:06.823  1200  1200 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,07-12 17:45:06.823  1483  1882 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-12 17:45:06.833   976  1075 D PMS     : acquireWL(17b89a56): PARTIAL_WAKE_LOCK  NetworkStats 0x1 976 1000 null
07-12 17:45:06.823  1483  1882 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-12 17:45:06.833   976  1076 V NetworkPolicy: ACTION_UID_REMOVED for uid=10192
,07-12 17:45:06.853  1483  1483 I Launcher: Deferring update until onResume,
07-12 17:45:06.853   976  1521 D PMS     : acquireWL(146f3a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1696 10025 WorkSource{10025 com.google.android.gms},
07-12 17:45:06.853  1483  1483 D Launcher: waitUntilResume // bindAppsRemoved
,07-12 17:45:06.863   976  1636 D PMS     : releaseWL(146f3a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
07-12 17:45:06.873  1439  1439 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-12 17:45:06.873  1483  1483 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
07-12 17:45:06.883  1409  6107 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
07-12 17:45:06.883  1409  6107 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-12 17:45:06.883  1545  6108 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-12 17:45:06.893  1573  1955 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-12 17:45:06.893  1573  1955 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-12 17:45:06.893   976  1075 D PMS     : releaseWL(17b89a56): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,07-12 17:45:06.893   976  1076 V NetworkPolicy: writePolicyLocked()
,07-12 17:45:06.923   976  1076 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
07-12 17:45:06.923   976  1076 D libc    : [NET] android_getaddrinfofornet-, err=8
07-12 17:45:06.923   976  1076 V NetworkPolicy: updateNetworkEnabledLocked()
07-12 17:45:06.923   976  1076 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
07-12 17:45:06.923   976  1076 V NetworkPolicy: updateNotificationsLocked()
07-12 17:45:06.923   976  1076 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-12 17:45:06.923   976  1076 D libc    : [NET] android_getaddrinfo_proxy+
07-12 17:45:06.923   976  1076 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-12 17:45:06.923   464  6122 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
07-12 17:45:06.923   464  6122 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-12 17:45:06.923   464  6122 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-12 17:45:06.923   464  6122 D libc    : [NET] android_getaddrinfofornet-, err=7
07-12 17:45:06.923   976  1076 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,07-12 17:45:06.923   976  1089 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6117 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,07-12 17:45:06.943  1573  1955 E ExternalAccountType: Unsupported attribute readOnly
07-12 17:45:06.943   976   976 W PackageManager: Unable to load service info ResolveInfo{6999b8c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-12 17:45:06.943   976   976 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-12 17:45:06.943   976   976 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
07-12 17:45:06.943   976   976 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
07-12 17:45:06.943   976   976 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-12 17:45:06.943   976   976 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-12 17:45:06.943   976   976 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-12 17:45:06.943   976   976 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-12 17:45:06.943   976   976 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:45:06.943   976   976 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:45:06.943   976   976 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:45:06.943   976   976 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-12 17:45:06.943   976   976 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-12 17:45:06.943   976   976 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:06.943   976   976 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
,07-12 17:45:06.943   976   976 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
07-12 17:45:06.943   976   976 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,07-12 17:45:06.953   976   999 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
,07-12 17:45:06.983   976   999 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-12 17:45:06.993   976  1016 D StatusBarManagerService: setSystemUiVisibility(0x8700),
07-12 17:45:06.993   976  1016 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:45:06.993   976  1016 D StatusBarManagerService: hiding MENU key
07-12 17:45:06.993   976  1016 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
07-12 17:45:06.993   976  1016 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:45:06.993   976  1016 D StatusBarManagerService: hiding MENU key
,07-12 17:45:06.993  6117  6117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 ,
,07-12 17:45:07.003   976  1519 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5976 uid 10192,
07-12 17:45:07.003   976  1519 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-12 17:45:07.023   976   976 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,07-12 17:45:07.033  1746  1746 E NetworkScheduler.SchedulerReceiver: Invalid parameter app,
07-12 17:45:07.033  1746  1746 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-12 17:45:07.033   976  1641 D PMS     : acquireWL(3af78b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1746 10025 WorkSource{10025 com.google.android.gms}
,07-12 17:45:07.033   976  1089 D PMS     : releaseWL(3af78b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,07-12 17:45:07.063  4125  6143 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-12 17:45:07.063  4125  4125 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-12 17:45:07.063  4125  4125 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-12 17:45:07.063  4125  4125 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games,
07-12 17:45:07.063  4125  4125 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-12 17:45:07.063  4125  6143 D AccountUtils: Clearing selected account for com.test.thalitest
,07-12 17:45:07.063   976  1054 I art     : Explicit concurrent mark sweep GC freed 28632(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 16MB/25MB, paused 1.652ms total 243.353ms
,07-12 17:45:07.073  5848  6145 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,07-12 17:45:07.083   976  1635 D PMS     : acquireWL(3f805d0a): PARTIAL_WAKE_LOCK  AsyncService 0x1 5919 10176 null,
,07-12 17:45:07.083   976  1641 D PMS     : releaseWL(3f805d0a): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-12 17:45:07.083   976  1637 D PMS     : acquireWL(bce4398): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5919 10176 null
,07-12 17:45:07.093   976  1635 D PMS     : releaseWL(bce4398): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,07-12 17:45:07.093  5723  5723 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
07-12 17:45:07.093  5723  5723 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,07-12 17:45:07.093  4125  6143 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,07-12 17:45:07.093  5723  5723 I DeviceManagement: WorkflowService: Starting workflow service
07-12 17:45:07.093  5723  6149 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@56c1351] args=[Bundle[mParcelledData.dataSize=112]]
07-12 17:45:07.093  5723  6149 I DeviceManagement: PackageUpdateWorkflow: ==================================================,
07-12 17:45:07.103  5723  6149 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
07-12 17:45:07.103  5723  6149 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,07-12 17:45:07.103  5723  6149 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,07-12 17:45:07.113   976  1502 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6153 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
07-12 17:45:07.113  5723  6152 I DeviceManagement: SessionStateController: Checking invariants...
,07-12 17:45:07.153  4125  4125 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-12 17:45:07.153   976  1482 D PMS     : acquireWL(12721cba): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4125 10025 null
,07-12 17:45:07.153   976  1637 D PMS     : releaseWL(12721cba): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,07-12 17:45:07.163  4125  6166 W BaseAppContext: Using Auth Proxy for data requests.,
,07-12 17:45:07.163  4125  6166 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 17:45:07.163  4125  6151 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,07-12 17:45:07.163  4125  6151 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-12 17:45:07.163  4125  6151 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-12 17:45:07.163  4125  6151 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,07-12 17:45:07.173  4125  6151 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,07-12 17:45:07.173  4125  6151 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,07-12 17:45:07.183  4125  6151 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,07-12 17:45:07.183  4125  6151 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,07-12 17:45:07.183  4125  6151 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,07-12 17:45:07.183  4125  6151 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-12 17:45:07.183  4125  6151 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,07-12 17:45:07.183  4125  6151 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
07-12 17:45:07.183  4125  6151 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,07-12 17:45:07.183  5723  6152 I DeviceManagement: ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
,07-12 17:45:07.203   976  1264 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=6174 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a
07-12 17:45:07.203   976  1426 I ActivityManager: Delay finish: com.android.documentsui/.PackageReceiver
07-12 17:45:07.203  5723  6152 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,07-12 17:45:07.203  5723  6149 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
07-12 17:45:07.203   976   992 I ActivityManager: Resuming delayed broadcast
07-12 17:45:07.203  5723  6149 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,07-12 17:45:07.203  5723  6149 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@56c1351]
,07-12 17:45:07.213  4125  4125 I ConfigFetchService: service connected
,07-12 17:45:07.233   976   992 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6192 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,07-12 17:45:07.233  5723  5723 I DeviceManagement: WorkflowService: Stopping workflow service
,07-12 17:45:07.233   976  1636 D PMS     : acquireWL(1ff5245e): PARTIAL_WAKE_LOCK  Icing 0x1 4125 10025 WorkSource{10025 com.google.android.gms}
,07-12 17:45:07.243  6056  6056 D Messaging: supportCMAS(SIE)/init? false/true
,07-12 17:45:07.243  6056  6056 D MmsConfig: networkCode: 
07-12 17:45:07.243  6056  6056 D MessageCustFlag: sku_id=99
07-12 17:45:07.243  6056  6056 D MmsConfig: SIE smsPri: null
07-12 17:45:07.243  6056  6056 D MmsConfig: networkCode: 
,07-12 17:45:07.253  4125  6201 I PeopleContactsSync: CP2 sync disabled
,07-12 17:45:07.253   976  1303 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4125, uid=10025, userID:0
,07-12 17:45:07.263  6056  6214 D Messaging: mNeedToUpdateDate2 start
,07-12 17:45:07.273  4125  4205 I Icing   : doRemovePackageData com.test.thalitest
,07-12 17:45:07.273  6056  6056 D MmsConfig: packageName: com.htc.vvm.att does not exist
,07-12 17:45:07.273  6056  6056 D ReportIndicatorCache: startAsyncQueryReports ---
,07-12 17:45:07.283  6056  6073 D MmsAsyncWorkHandler: 
07-12 17:45:07.283  6056  6073 D MmsAsyncWorkHandler: HM tk = 20001
07-12 17:45:07.283  6056  6073 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
,07-12 17:45:07.283  5848  6145 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] 
07-12 17:45:07.283  6056  6056 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@2294263b
,07-12 17:45:07.283   976  1426 D Process : killProcessQuiet, pid=5647,
07-12 17:45:07.283   976  1426 I ActivityManager: Killing 5647:com.android.settings:remote/1000 (adj 15): empty #17
07-12 17:45:07.283   976  1426 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-12 17:45:07.283  6056  6056 D DraftCache: [DraftCache/1] DraftCache.constructor
07-12 17:45:07.283  6056  6056 D DraftCache: [DraftCache/1] refresh
07-12 17:45:07.283  6056  6056 D MmsConfig: networkCode: 
,07-12 17:45:07.293   976  1641 I ActivityManager: Recipient 5647
,07-12 17:45:07.293  6056  6218 D Messaging: ViewCache CreatePreloadOnlyConversationList
,07-12 17:45:07.303  6174  6174 D ExternalStorage: After updating volumes, found 1 active roots
,07-12 17:45:07.323  1439  2318 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
,07-12 17:45:07.323  1439  2318 D MmsSmsV2Provider:  slotId = -1000
07-12 17:45:07.323  1439  2318 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,07-12 17:45:07.323  6056  6216 I Messaging: mccmnc> 
,07-12 17:45:07.323  6056  6218 D MessageCustFlag: sense_version=6.0
,07-12 17:45:07.333   976  1641 D Process : killProcessQuiet, pid=5647
07-12 17:45:07.333   976  1641 W libprocessgroup: failed to open /acct/uid_1000/pid_5647/cgroup.procs: No such file or directory
07-12 17:45:07.333   976  1641 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,07-12 17:45:07.333  1439  1962 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 96
07-12 17:45:07.333  1439  1962 D AccFlag : sku_id=99
,07-12 17:45:07.333  6056  6073 D DraftCache: [DraftCache/806] rebuildCache
,07-12 17:45:07.333  6056  6218 D Jerry   : start to preload cursor >>>>>>>
07-12 17:45:07.333  6192  6192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
07-12 17:45:07.333  1439  1464 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
07-12 17:45:07.333  1439  1464 D MmsSmsV2Provider:  slotId = -1000
07-12 17:45:07.333  1439  1464 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
07-12 17:45:07.333  1439  2318 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
07-12 17:45:07.343  1439  2318 D MmsSmsV2Provider:  slotId = -1000
07-12 17:45:07.343  1439  2318 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
07-12 17:45:07.343  6056  6214 D Messaging: mNeedToUpdateDate2: false
07-12 17:45:07.343  1439  1962 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 96
07-12 17:45:07.343  1439  1962 D Jerry   : URI_DRAFT
07-12 17:45:07.343  6056  6073 D DraftCache: hasDraft() = false mNeedNotifyChange = true
07-12 17:45:07.343  6056  6073 D DraftCache: [DraftCache/806] rebuildCache time: 1
07-12 17:45:07.343  6056  6073 D MmsAsyncWorkHandler: 
07-12 17:45:07.343  6056  6073 D MmsAsyncWorkHandler: HM tk = 20002
07-12 17:45:07.343  6192  6221 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
07-12 17:45:07.343  1439  2318 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
07-12 17:45:07.343  1439  2318 D MmsSmsV2Provider:  slotId = -1000
07-12 17:45:07.343  1439  2318 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
07-12 17:45:07.343  6056  6056 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1
07-12 17:45:07.343  6056  6056 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
07-12 17:45:07.343  6056  6056 D PhoneStorageUtil: createReceiver
07-12 17:45:07.353  6192  6221 D PowerUsageService: removed uid = 10192
07-12 17:45:07.353  6056  6215 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
07-12 17:45:07.353  1439  1962 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 96
07-12 17:45:07.353  1439  1962 D MmsSmsV2Provider:  slotId = -1000
07-12 17:45:07.353  1439  2318 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
07-12 17:45:07.353  1439  2318 D AccFlag : sku_id=99
07-12 17:45:07.353  6056  6218 D Messaging: ViewCache CreatePreload
07-12 17:45:07.353  6056  6218 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
07-12 17:45:07.363  6056  6218 D Cust_MMSMS: _has_set_default_values_2=true
07-12 17:45:07.363  6056  6218 D MsgPreferenceUtils: def_index: 0
07-12 17:45:07.373   976  1089 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=6225 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 17:45:07.383   976  1089 I ActivityManager: Killing 5690:com.google.android.partnersetup/u0a28 (adj 15): empty #17
07-12 17:45:07.383   976  1089 D Process : killProcessQuiet, pid=5690
,07-12 17:45:07.383   976  1089 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-12 17:45:07.383  1439  1464 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
07-12 17:45:07.383  1439  1464 D AccFlag : sku_id=99
07-12 17:45:07.383   474   474 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 140us total 9.327ms
07-12 17:45:07.383  6056  6218 D MsgPreferenceUtils: globalIndex = 1
,07-12 17:45:07.393   976  1634 I ActivityManager: Recipient 5690
07-12 17:45:07.393  6056  6218 D MsgPreferenceUtils: phone state: true
07-12 17:45:07.393  6056  6218 D MsgPreferenceUtils: sd state: false
07-12 17:45:07.393  6056  6218 D MsgPreferenceUtils: vIndex = 0
07-12 17:45:07.393   474   474 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 136us total 8.815ms
,07-12 17:45:07.403   474   474 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 132us total 8.643ms
,07-12 17:45:07.433   976  1634 D Process : killProcessQuiet, pid=5690
07-12 17:45:07.433   976  1634 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:07.433   976  1634 W libprocessgroup: failed to open /acct/uid_10028/pid_5690/cgroup.procs: No such file or directory
,07-12 17:45:07.433  1439  2318 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
07-12 17:45:07.433  1439  2318 V MmsProvider: Update uri=content://mms, match=0
,07-12 17:45:07.433  1439  2318 V MmsProvider: selection=st=129 AND m_type!=134
07-12 17:45:07.433  6056  6239 D Messaging: Reset downloading state: 0
07-12 17:45:07.433  6056  6239 V MmsSystemEventReceiver: TransactionService is going to be woken up.
,07-12 17:45:07.443  6225  6225 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 17:45:07.443  6056  6056 V TransactionService: 1-Creating TransactionService
,07-12 17:45:07.453  6056  6056 V TransactionService: onStartCommand: 1,
07-12 17:45:07.453  6056  6056 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
07-12 17:45:07.453  6056  6256 V TransactionService: 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
07-12 17:45:07.453  6056  6256 V TransactionService: Loading previous transactions.
,07-12 17:45:07.463  1439  1962 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 96,
07-12 17:45:07.463  1439  1962 D AccFlag : device_type: 1
,07-12 17:45:07.463  6056  6256 D TransactionService: Force set service start id to 1
07-12 17:45:07.463  6056  6256 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
,07-12 17:45:07.463  6056  6256 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
07-12 17:45:07.463  6056  6256 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
07-12 17:45:07.463  6056  6056 V TransactionService: Destroying TransactionService
,07-12 17:45:07.463  6056  6256 V TransactionService: 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,07-12 17:45:07.493   976  1426 I ActivityManager: Killing 5743:com.htc.backup/u0a118 (adj 15): empty #17,
07-12 17:45:07.493   976  1426 D Process : killProcessQuiet, pid=5743
07-12 17:45:07.493   976  1426 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,07-12 17:45:07.503   976  1303 I ActivityManager: Recipient 5743,
,07-12 17:45:07.523  6153  6173 D Documents: Update found 7 roots in 349ms,
,07-12 17:45:07.543   976  1303 D Process : killProcessQuiet, pid=5743
07-12 17:45:07.543   976  1303 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
07-12 17:45:07.543   976  1303 W libprocessgroup: failed to open /acct/uid_10118/pid_5743/cgroup.procs: No such file or directory
,07-12 17:45:07.543  6153  6219 D Documents: Update found 7 roots in 240ms
,07-12 17:45:07.543  4125  6150 W DriveInitializer: Awaiting to be initialized
,07-12 17:45:07.543  4125  6263 W DriveInitializer: Background init thread started
,07-12 17:45:07.603   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
07-12 17:45:07.603   363   408 W Vold    : Returning OperationFailed - no handler for errno 0,
07-12 17:45:07.603  4125  6263 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,07-12 17:45:07.613  4125  6263 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-12 17:45:07.613  4125  6263 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0xb9ac0d78
,07-12 17:45:07.613  4125  6263 W DriveInitializer: Background init thread ended
07-12 17:45:07.613  4125  6150 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-12 17:45:07.613  4125  6150 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0xb9ac0d78
07-12 17:45:07.613  4125  6263 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
07-12 17:45:07.613  4125  6263 E AndroidRuntime: Process: com.google.android.gms, PID: 4125
07-12 17:45:07.613  4125  6263 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:585)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.e(SourceFile:804)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at com.google.android.gms.drive.events.ao.a(SourceFile:135)
07-12 17:45:07.613  4125  6263 E AndroidRuntime: 	at com.google.android.gms.drive.r.run(SourceFile:72)
,07-12 17:45:07.613   976  1482 E ActivityManager: App crashed! Process: com.google.android.gms
07-12 17:45:07.613  4125  6263 D Process : killProcess, pid=4125
07-12 17:45:07.623  4125  6150 E DriveAsyncService: disk I/O error (code 3850)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:585)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-12 17:45:07.623  4125  6150 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: Can't write: system_app_crash
07-12 17:45:07.623   976  6265 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:45:07.623   976  6265 E DropBoxManagerService: 	... 5 more
07-12 17:45:07.623  4125  6263 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
07-12 17:45:07.643   976  1521 D Process : killProcessQuiet, pid=4125
07-12 17:45:07.643   976  1521 I ActivityManager: Recipient 4125
07-12 17:45:07.643   976  1521 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-12 17:45:07.643   976  1636 D PMS     : handleWLDeath(1ff5245e): PARTIAL_WAKE_LOCK  Icing 0x1
,07-12 17:45:07.663   976  1521 I ActivityManager: Process com.google.android.gms (pid 4125) has died
07-12 17:45:07.663   976  1521 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
07-12 17:45:07.663   976  1521 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
07-12 17:45:07.663   976  1521 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
07-12 17:45:07.663   976  1521 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
07-12 17:45:07.663  1746  1746 I ConfigService: onDestroy
,07-12 17:45:08.333  1483  1882 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
07-12 17:45:08.333  1483  1882 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3d474274 +,
07-12 17:45:08.333  1483  1882 I Prism.WidgetManager: onLoadItems() +,
07-12 17:45:08.453  1483  1882 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-12 17:45:08.613  1483  1882 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,07-12 17:45:08.683  1483  1882 E Prism.WidgetManager: The same lists. No need to update. skip it.
07-12 17:45:08.683  1483  1882 I Prism.WidgetManager: onLoadItems() -
07-12 17:45:08.683  1483  1882 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3d474274 -
,07-12 17:45:08.683  1483  1882 E SQLiteLog: (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=73] disk I/O error,
07-12 17:45:08.683  1483  1882 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xb98398f8
,07-12 17:45:08.693   976  1000 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.icing.service.IndexWorkerService: pid=6287 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,07-12 17:45:08.693  1483  1882 E AndroidRuntime: FATAL EXCEPTION: TaskWorker,
07-12 17:45:08.693  1483  1882 E AndroidRuntime: Process: com.htc.launcher, PID: 1483
07-12 17:45:08.693  1483  1882 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
,07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102),
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:45:08.693  1483  1882 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:45:08.693   976  1637 E ActivityManager: App crashed! Process: com.htc.launcher
07-12 17:45:08.693   976  1637 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,07-12 17:45:08.693   976  1525 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
,07-12 17:45:08.693   976  1525 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:45:08.693   976  1525 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:45:08.693   976  1525 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,07-12 17:45:08.693   976  1525 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-12 17:45:08.693   976  1525 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-12 17:45:08.693   976  1525 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-12 17:45:08.693   976  1525 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-12 17:45:08.693   976  1525 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
,07-12 17:45:08.693   976  1525 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-12 17:45:08.693   976  1525 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-12 17:45:08.693   976  1525 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:08.703   976  1525 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-12 17:45:08.703   976  1525 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:45:08.703   976  1525 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:45:08.703   976  1525 W System.err: 	at libcore.io.Posix.open(Native Method)
07-12 17:45:08.703   976  1525 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:45:08.703   976  1525 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:45:08.703   976  1525 W System.err: 	... 12 more
,07-12 17:45:08.703   976  1637 W ActivityManager:   Force finishing activity com.htc.launcher/.Launcher
,07-12 17:45:08.703   976  6301 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-12 17:45:08.703   976  6301 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1468338308720.dbox_tmp: open failed: EROFS (Read-only file system)
07-12 17:45:08.703   976  6301 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-12 17:45:08.703   976  6301 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 17:45:08.703   976  6301 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 17:45:08.703   976  6301 E ErrorReport: 	,at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
07-12 17:45:08.703   976  6301 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-12 17:45:08.703   976  6301 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 17:45:08.703   976  6301 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-12 17:45:08.703   976  6301 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 17:45:08.703   976  6301 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 17:45:08.703   976  6301 E ErrorReport: 	... 4 more
,07-12 17:45:08.713  1483  1882 D Process : killProcess, pid=1483
07-12 17:45:08.713  1483  1882 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,07-12 17:45:08.723  6287  6287 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-12 17:45:08.733  6287  6287 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-12 17:45:08.733   976  1636 D Process : killProcessQuiet, pid=1483
,07-12 17:45:08.733   976  1636 I ActivityManager: Recipient 1483
07-12 17:45:08.733   976  1636 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,07-12 17:45:08.733   976  1502 I WindowState: WIN DEATH: Window{137f9817 u0 com.htc.launcher/com.htc.launcher.Launcher}
,07-12 17:45:08.753   976  1636 I ActivityManager: Process com.htc.launcher (pid 1483) has died
,07-12 17:45:08.753   976  1636 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
,07-12 17:45:08.753  2267  2283 E MP-Decision: Update arg "0 380 380 380".
,07-12 17:45:08.753  2267  2283 E MP-Decision: Update arg "0 400 400 400".

```
