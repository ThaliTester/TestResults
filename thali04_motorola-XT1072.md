#### Test 625090942f85e77_thali04_motorola-XT1072 Logs


```
--------- beginning of system
I/ActivityManager(  878): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5098 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
I/ActivityManager(  878): Killing 3451:com.android.defcontainer/u0a10 (adj 15): empty #7
W/ResourcesManager( 4926): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4926): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  878): failed to open /acct/uid_10010/pid_3451/cgroup.procs: No such file or directory
--------- beginning of main
V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 5067): Created com.android.providers.calendar.CalendarAlarmManager@36468648(com.android.providers.calendar.CalendarProvider2@3ca14ce1)
I/ActivityManager(  878): Killing 4840:com.android.vending/u0a32 (adj 15): empty #7
W/ResourcesManager( 5098): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
W/Flag    ( 4926): Duration spec must be at least 2 characters long
V/JNIHelp ( 4926): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_4840/cgroup.procs: No such file or directory
I/ActivityManager(  878): Killing 3073:com.google.android.calendar/u0a49 (adj 15): empty #7
I/ProviderInstaller( 4926): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  878): failed to open /acct/uid_10049/pid_3073/cgroup.procs: No such file or directory
I/ActivityManager(  878): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5127 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  878): send {1fe85511, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED}
I/ActivityManager(  878): Killing 4309:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_4309/cgroup.procs: No such file or directory
V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PeopleContactsSync( 1959): CP2 cleanup done, kept= duration=781 ms
E/SQLiteLog( 5127): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
I/PeopleContactsSync( 1959): ===CP2 sync finished, success=true, time=941,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
D/AndroidRuntime( 5123): 
D/AndroidRuntime( 5123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5123): CheckJNI is OFF
I/PeopleSync( 1959): ***Sync finished***, duration: 7730 [5005f081]
I/ActivityManager(  878): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5151 uid=10096 gids={50096, 9997} abi=armeabi-v7a
I/ActivityManager(  878): Killing 4686:com.google.android.apps.docs/u0a57 (adj 15): empty #7
W/libprocessgroup(  878): failed to open /acct/uid_10057/pid_4686/cgroup.procs: No such file or directory
I/AnalyticsLogBase( 5127): PlayLogger.onLoggerConnected
I/System.out( 5151): TimeService: Loaded Library 
D/TimeService( 5151): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457711973180
D/        ( 5151): TimeServiceNative: User Time to be set is 1457711973180
D/QC-time-services( 5151): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5151): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5151): Lib:time_genoff_operation: pargs->ts_val = 1457711973180
D/QC-time-services( 5151): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  324): Daemon: Connection accepted:time_genoff
D/QC-time-services(  324): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457711973180
D/QC-time-services(  324): Daemon:genoff_opr: Base = 2, val = 1457711973180, operation = 0
D/QC-time-services(  324): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/11/116 15:57:46
D/QC-time-services(  324): Daemon:Value read from RTC seconds = 1457711866000
D/QC-time-services(  324): Daemon:new time 1457711973180 
D/QC-time-services(  324): Daemon: delta 107180 genoff 107180 
D/QC-time-services(  324): Daemon:genoff_persistent_update: Writing genoff = 107180 to memory
D/QC-time-services(  324): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  324): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  324): Updating the TOD offset
D/QC-time-services(  324): Daemon:genoff_persistent_update: Writing genoff = 107180 to memory
D/QC-time-services(  324): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  324): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  324): Daemon:Update to modem bit set
D/QC-time-services(  324): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  324): Daemon: Base = 2, Value being sent to MODEM = 18446743757744858796
E/QC-time-services( 5151): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  878): Killing 4974:com.android.chrome/u0a52 (adj 15): empty #7
E/QC-time-services(  324): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  324): Daemon: Time-services: Waiting to acceptconnection
W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_4974/cgroup.procs: No such file or directory
D/AndroidRuntime( 5123): Calling main entry com.android.commands.am.Am
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (147 us)
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5123): Shutting down VM
I/ActivityManager(  878): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5185 uid=10571 gids={50571, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  878): Killing 5009:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  878): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5212 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_5009/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5067): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5067): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5229 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 5047:android.process.acore/u0a7 (adj 15): empty #7
,I/WebViewFactory( 5185): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_5047/cgroup.procs: No such file or directory
,W/ResourcesManager( 5229): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/LibraryLoader( 5185): Time to load native libraries: 6 ms (timestamps 950-956)
I/LibraryLoader( 5185): Expected native library version number "",actual native library version number ""
,I/GAv4    ( 5212): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5212):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5212):   adb logcat -s GAv4
,W/GAv4    ( 5212): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
V/WebViewChromiumFactoryProvider( 5185): Binding Chromium to main looper Looper (main, tid 1) {22a5f8c7}
I/LibraryLoader( 5185): Expected native library version number "",actual native library version number ""
I/chromium( 5185): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5185): Initializing chromium process, singleProcess=true
,W/art     ( 5185): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5185): ApplicationContext is null in ApplicationStatus
,W/GAv4    ( 5212): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5212): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/chromium( 5185): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5185): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5185): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5185): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5185): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5185): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5185): Local Branch: 
I/Adreno-EGL( 5185): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5185): Local Patches: NONE
I/Adreno-EGL( 5185): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  878): Killing 5098:com.motorola.context/u0a8 (adj 15): empty #7
,D/BluetoothManagerService(  878): Message: 20
,D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@993b1a6:true
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_5098/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2579): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5274 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SundryService( 2579): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
E/SQLiteLog( 2579): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2579): ServiceHandler.handleMessage: mWaitCount=1
,I/PushService( 2579): started with background data enabled, making sure notification mechanism is enabled
,D/Central_PollingManager( 1468): wake lock released
,I/ActivityManager(  878): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5297 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a,
,W/ResourcesManager( 5297): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ContactLocale( 5274): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/art     ( 5185): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  878): Explicit concurrent mark sweep GC freed 21427(1083KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/31MB, paused 1.860ms total 138.254ms
,W/AwContents( 5185): onDetachedFromWindow called when already detached. Ignoring
,E/global frequency( 2579): no tags to log
D/Checkin ( 2579): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/SystemWebViewEngine( 5185): CordovaWebView is running on device made by: motorola
,W/art     ( 5185): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5185): Attempt to remove local handle scope entry from IRT, ignoring
,D/BSUtils ( 2579): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/OpenGLRenderer( 5185): Render dirty regions requested: true
,D/Atlas   ( 5185): Validating map...
,W/chromium( 5185): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  878): Killing 5067:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/BSUtils ( 2579): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2579): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  878): failed to open /acct/uid_10005/pid_5067/cgroup.procs: No such file or directory
,D/BSUtils ( 2579): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/OpenGLRenderer( 5185): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5185): Enabling debug mode 0
,I/ActivityManager(  878): Killing 5151:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,I/art     ( 1468): Explicit concurrent mark sweep GC freed 4243(176KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 660us total 36.580ms
,I/Keyboard.Facilitator( 1401): onFinishInput()
,W/libprocessgroup(  878): failed to open /acct/uid_10096/pid_5151/cgroup.procs: No such file or directory
,I/LaunchCheckinHandler(  878): Displayed com.test.thalitest/.MainActivity,cp,ca,1456
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/ActivityManager(  878): Displayed com.test.thalitest/.MainActivity: +1s456ms
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BSUtils ( 2579): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/WifiService(  878): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@25ef2ed4}
E/Adreno-ES20( 5185): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5185): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/BSUtils ( 2579): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ActivityManager(  878): Killing 1959:com.google.android.gms/u0a16 (adj 15): empty #7
,D/BSUtils ( 2579): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
W/BindingManager( 5185): Cannot call determinedVisibility() - never saw a connection for the pid: 5185
,E/PhoneInterfaceManager( 1549): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/ConnectivityService(  878): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@12dc192)
D/WifiService(  878): Client connection lost with reason: 4
,D/ConnectivityService(  878): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  878): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_1959/cgroup.procs: No such file or directory
,I/SFPerfTracer(  278):      triggers: (rate: 15:463) (compose: 0:1) (post: 0:1) (render: 0:2) (8:921 frames) (9:1005)
,D/SFPerfTracer(  278):        layers: (4:13) (FocusedStackFrame (0xb7e99218): 0:15)* (DimLayer (0xb7f2d580): 0:7)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7f303c8): 0:48)- (StatusBar (0xb7f48018): 0:125) (NavigationBar (0xb7f49d30): 0:33) (com.android.systemui.ImageWallpaper (0xb7f4c048): 0:6)* (Starting com.motorola.ccc.ota (0xb7f37340): 0:30)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f54560): 0:55)- (Starting com.test.thalitest (0xb7f37340): 9:40) (com.test.thalitest/com.test.thalitest.MainActivity (0xb7f316e8): 6:12) 
,I/art     ( 2579): Explicit concurrent mark sweep GC freed 17807(1078KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 957us total 86.106ms
,D/BSUtils ( 2579): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2579): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/OtaApp  ( 2579): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2579): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2579): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  878): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/BSUtils ( 2579): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/OtaApp  ( 2579): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2579): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2579): publish the event [tag = MOT_OTA event name = LOG]
,I/global frequency( 2579): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2579): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/OtaApp  ( 2579): [info] > Exceed max defer attempts for optional update, suppresing later btn
E/global frequency( 2579): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2579): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2579): publish the event [tag = MOT_OTA event name = LOG]
,D/Checkin ( 2579): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2579): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/ActivityManager(  878): Start proc com.google.android.gms for broadcast com.google.android.gms/.wearable.service.AutoStarterReceiver: pid=5341 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/OtaApp  ( 2579): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2579): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2579): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2579): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2579): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2579): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2579): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2579): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2579): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2579): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2579): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  878): Activity reported stop, but no longer stopping: ActivityRecord{28205b4a u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
,I/Keyboard.Facilitator( 1401): onFinishInput()
,W/InputMethodManagerService(  878): Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3990fdb (uid=10571 pid=5185)
,W/IInputConnectionWrapper( 5185): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  878): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,226
,W/ResourcesManager( 5341): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5341): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (33:246 vsyncs) (35:1028)
,I/global frequency( 2579): BcsDSCheckin.events found events 112
D/Checkin ( 2579): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/JsMessageQueue( 5185): Set native->JS mode to OnlineEventsBridgeMode
,I/MultiDex( 5341): VM with version 2.1.0 has multidex support
I/MultiDex( 5341): install
I/MultiDex( 5341): VM has multidex support, MultiDex support library is disabled.
,D/jxcore_app_log( 5185): JniHelper::setJavaVM(0xb7be6310), pthread_self() = -1208255952
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5185): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5185):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5185):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5185):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5185):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5185): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f855ff2 added. We now have 1 listener(s)
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/art     (  878): Explicit concurrent mark sweep GC freed 12694(568KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 2.191ms total 203.363ms
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5185): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5185): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5185): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5185): setHandshakeRequired: true -> false
,I/art     ( 4926): WaitForGcToComplete blocked for 20.036ms for cause DisableMovingGc
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bf0b5f9 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5185): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  878): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5185): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5185): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 5185): Constructor: Bluetooth LE discovery mode is not supported
,I/BSUtils ( 2579): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/chromium( 5185): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/MMApiWebService( 2579): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1468): Explicit concurrent mark sweep GC freed 4105(178KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 792us total 60.068ms
,V/JNIHelp ( 5341): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/MMApiWSBase( 2579): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2579): publish the event [tag = MOT_CCE event name = LOG]
,I/SFPerfTracer(  278):      triggers: (rate: 15:463) (compose: 0:1) (post: 0:1) (render: 0:4) (12:973 frames) (13:1066)
D/SFPerfTracer(  278):        layers: (5:11) (FocusedStackFrame (0xb7e99218): 0:16)* (DimLayer (0xb7f2d580): 0:8) (StatusBar (0xb7f48018): 0:143) (NavigationBar (0xb7f49d30): 0:45) (com.android.systemui.ImageWallpaper (0xb7f4c048): 0:6)* (Starting com.test.thalitest (0xb7f37340): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7f316e8): 0:59) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f37340): 13:27) 
,W/ActivityThread( 5341): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5341): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c6ca4d9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5341): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 5341): Reading stored module config
,I/ActivityManager(  878): Killing 5212:com.google.android.deskclock/u0a55 (adj 15): empty #7
,D/NativeLibraryUtils( 5341): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  878): failed to open /acct/uid_10055/pid_5212/cgroup.procs: No such file or directory
,D/WearableService( 1715): callingUid 10016, callindPid: 1715
,D/LocationInitializer( 5341): Restart initialization of location
,E/MDM     ( 1715): [222] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  878): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=38.50 rxSuccessRate=33.58 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  878): WifiStateMachine CMD_START_SCAN with age=17357 interval=30000 maxinterval=300000
E/WifiStateMachine(  878): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  878): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  878): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
,V/AlarmManager(  878): done {4e7c823, *alarm*:com.android.server.WifiManager.action.START_SCAN} [44292ms]
I/wpa_supplicant( 1438): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  878): [1,457,711,976,433 ms] noteScanstart no scan source
,I/SundryService( 2579): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2579): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2579): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2579): ServiceHandler.handleMessage: mWaitCount=0
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,E/WifiStateMachine(  878): [1,457,711,976,464 ms] noteScanEnd no scan source
,E/WifiStateMachine(  878): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@26075268 sup_state=COMPLETED debouncing=false
,I/ActivityManager(  878): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5375 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 20.437ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.387ms
,D/GetNotificationsWS( 2579): unbindWebServices(): un-registering our AIDL callback...
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 23.353ms
,I/art     ( 5341): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5341): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/IcingInternalCorpora( 5341): getNumBytesRead when not calculated.
,W/GCoreFlp( 1715): No location to return for getLastLocation()
W/FusedLocationProvider( 1715): location=null
,I/Gmail   ( 5375): getAccountsCursor
,D/ActivityThread( 5375): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5406 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  878): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5375): Observing account changes for notifications
,W/GAV2    ( 5375): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Exchange( 5406): EasService.onCreate
,I/Exchange( 5406): RestartPingTask
,I/Exchange( 5406): RestartPingsTask did not start any pings.
I/Exchange( 5406): PSS stopIfIdle
I/Exchange( 5406): PSS has no active accounts; stopping service.
,I/Gmail   ( 5375): getAccountsCursor
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 5406): onDestroy
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminPushReceiver( 2579): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2579): Type: null
D/3CDM.DeviceAdminPushReceiver( 2579): Data: null
,I/CE-UpdateModelService( 5297): ACTION_REGISTRATION_COMPLETE
,D/3CDM.Service( 2579): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.Service( 2579): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
,D/3CDM.Service( 2579): DeviceAdmin - syncWithCCC
D/3CDM.Service( 2579): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2579): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2579): blur.service.cred.locationToken = null
D/3CDM.Service( 2579): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2579): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2579): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2579): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
I/ActivityManager(  878): Killing 5229:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/3CDM.Service( 2579): Sync to CCE settings done, instantiate Locate now.
,E/SQLiteLog( 5375): (283) recovered 38 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_5229/cgroup.procs: No such file or directory
,I/Gmail   ( 5375): notifyAccountChanged
D/BSUtils ( 2579): set .setup.DeviceAdminSetupReceiver enabled
,D/Checkin ( 3015): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/Gmail   ( 5375): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5375): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  878): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5447 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 5375): getAccountsCursor
,I/Gmail   ( 5375): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5375): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/MMApiWSBase( 2579): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2579): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 2579): AppWSProxy - sendAIDLWSResponse() sending reponse
,W/ResourcesManager( 5447): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/global frequency( 2579): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2579): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/CalendarProvider2( 5447): Created com.android.providers.calendar.CalendarAlarmManager@36468648(com.android.providers.calendar.CalendarProvider2@3ca14ce1)
,V/AlarmManager(  878): done {3d86f620, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [11661ms]
,I/Gmail   ( 5375): getAccountsCursor
,V/AlarmManager(  878): send {de17202, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,E/SQLiteLog( 5447): (284) automatic index on view_events(_id)
,D/CheckinProvider(  878): 112 events delete 0 left
,I/art     (  878): Explicit concurrent mark sweep GC freed 12390(627KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.744ms total 128.072ms
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/global frequency( 2579): BcsDSCheckin.events found events 0
,D/Checkin ( 2579): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  878): done {8502f61, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10994ms]
,I/BSUtils ( 2579): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2579): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2579): BcsTimer.onReceive checkin completed (1276752592:ERROR_OK)
,D/Checkin ( 2579): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5467 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 5467): Register our PhoneStateListener
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/SetupWizard( 5467): Connected to Gservices successfully
,I/ActivityManager(  878): Killing 4926:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10105/pid_4926/cgroup.procs: No such file or directory
,W/ContextImpl( 5127): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5127): Thread[GAThread,5,main]: No campaign data found.
,W/DataUsage( 2579): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2579): publish the event [tag = MOT_CCE event name = LOG]
,I/GAv4-SVC( 5341): Google Analytics 8.7.03 is starting up.
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5492 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5492): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/art     ( 5185): Suspending all threads took: 23.791ms
,W/jxcore-log( 5185): Initializing JXcore engine
W/jxcore-log( 5185): JXcore engine is ready
,W/Thread-599( 5362): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10571 path="socket:[9365]" dev="sockfs" ino=9365 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-599( 5362): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10571 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-599( 5362): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10571 path="socket:[7077]" dev="sockfs" ino=7077 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-599( 5362): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10571 path="socket:[24706]" dev="sockfs" ino=24706 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5185): Starting JXcore engine
,I/Babel_SMS( 5492): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5492): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5492): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 5492): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5492): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5492): MmsConfig.loadFromResources
,E/Babel_SMS( 5492): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5492): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/jxcore-log( 5185): Platform android
W/jxcore-log( 5185): 
W/jxcore-log( 5185): Process ARCH arm
W/jxcore-log( 5185): 
,W/Settings( 5492): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5492): startup - clean
,I/Babel   ( 5492): deleted: false for 0
,I/CalendarProvider2( 5447): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5447): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5522 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 5274:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_5274/cgroup.procs: No such file or directory
,D/TaskPersister(  878): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  878): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/VideoCapabilities( 5492): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5492): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5492): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5492): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5492): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5492): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5492): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5492): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  878): Killing 5406:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10060/pid_5406/cgroup.procs: No such file or directory
,I/vclib   ( 5492): onServiceConnected
W/Babel   ( 5492): Attempted to change video mute state without an active call.
,I/jxcore-log( 5185): JXcore Cordova bridge is ready!
I/jxcore-log( 5185): 
,W/jxcore-log( 5185): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5185): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 5185): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 5185): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5185): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5185): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 5185): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,I/ActivityManager(  878): Killing 5375:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10063/pid_5375/cgroup.procs: No such file or directory
W/PluginManager( 5185): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 76ms. Plugin should use CordovaInterface.getThreadPool().
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:39000 mC
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5551 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 5447:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/AndroidRuntime( 5543): 
D/AndroidRuntime( 5543): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5543): CheckJNI is OFF
,W/libprocessgroup(  878): failed to open /acct/uid_10005/pid_5447/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5576 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5576): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5576): Created com.android.providers.calendar.CalendarAlarmManager@36468648(com.android.providers.calendar.CalendarProvider2@3ca14ce1)
,D/AndroidRuntime( 5543): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  878): Force stopping com.test.thalitest appid=10571 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 5185:com.test.thalitest/u0a571 (adj 9): stop com.test.thalitest
,D/WifiService(  878): Client connection lost with reason: 4
,W/PackageSettings(  878): Skipping PackageSetting{39d2675f com.example.hello/10568} due to missing metadata
,W/ActivityManager(  878): Spurious death for ProcessRecord{26e13d47 5185:com.test.thalitest/u0a571}, curProc for 5185: null
,I/ActivityManager(  878): Force stopping com.test.thalitest appid=10571 user=0: pkg removed
,I/Keyboard.Facilitator( 1401): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1401): run()
,W/GeofencerStateMachine( 1715): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,I/Decoder ( 1401): createOrResetDecoder
,I/art     ( 3015): Explicit concurrent mark sweep GC freed 11864(1711KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 1.015ms total 50.394ms
,I/ConfigService( 1715): onCreate
,I/art     ( 1569): Explicit concurrent mark sweep GC freed 3883(253KB) AllocSpace objects, 2(72KB) LOS objects, 25% free, 13MB/17MB, paused 512us total 89.930ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1401): run()
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5610 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  878): removeObsoleteFile: deleting file=9_task.xml
,D/TaskPersister(  878): removeObsoleteFile: deleting file=9_task_thumbnail.png
,I/art     (  878): Explicit concurrent mark sweep GC freed 15229(1009KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 4.569ms total 194.792ms
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/AndroidRuntime( 5543): Shutting down VM
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1401): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1401): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1401): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1401): run()
I/StatsUtilsManager( 1401): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1401): shouldRecordStats() = Too Soon
,I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5630 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Launcher( 1569): Deferring update until onResume
,W/ResourcesManager( 5492): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5492): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5492): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5492): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5492): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  878): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=5653 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  878): send {aaec6d0, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
V/AlarmManager(  878): send {4e7c823, *alarm*:com.android.server.WifiManager.action.START_SCAN}
V/AlarmManager(  878): done {aaec6d0, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [44ms]
,I/ContactLocale( 5630): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5672 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 5297:com.motorola.context/u0a8 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.728ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.133ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.716ms
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_5297/cgroup.procs: No such file or directory
,W/asset   ( 5672): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5672): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5672): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5672): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5576): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5576): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  878): Killing 5467:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_5467/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 5551): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f55d660 new=com.google.android.velvet.VelvetApplication@1f55d660
,D/PkgBroadcastIntentOp( 5341): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PkgBroadcastIntentOp( 5341): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5702 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WearableController( 5341): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5653): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/FileUtils( 5341): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/TaskRunnerFutureTask( 5551): Unchecked exception running task: ExtraDexRegistry[Jar loading for icingsync]
E/TaskRunnerFutureTask( 5551): java.lang.IllegalArgumentException: optimizedDirectory not readable/writable: /data/data/com.google.android.googlequicksearchbox/files/extradex_jars/verified/icingsync
E/TaskRunnerFutureTask( 5551): 	at dalvik.system.DexPathList.<init>(DexPathList.java:101)
E/TaskRunnerFutureTask( 5551): 	at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/TaskRunnerFutureTask( 5551): 	at dalvik.system.DexClassLoader.<init>(DexClassLoader.java:57)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.libraries.velour.dynloader.b.<init>(DexFirstClassLoader.java:20)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.libraries.velour.dynloader.e.a(JarEntryPointLoader.java:82)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.libraries.velour.dynloader.e.a(JarEntryPointLoader.java:35)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.libraries.velour.dynloader.i.G(JarLoader.java:253)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.libraries.velour.dynloader.i.bjN(JarLoader.java:135)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:337)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/TaskRunnerFutureTask( 5551): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/TaskRunnerFutureTask( 5551): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/TaskRunnerFutureTask( 5551): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/TaskRunnerFutureTask( 5551): 	at java.lang.Thread.run(Thread.java:818)
E/TaskRunnerFutureTask( 5551): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,E/Icing   ( 5341): Failed to open Apps corpus file.
E/Icing   ( 5341): Failed to append to component name file.
E/SharedPreferencesImpl( 5341): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
W/ResourcesManager( 5702): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5739 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/SharedPreferencesImpl( 5551): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
,--------- beginning of crash
E/AndroidRuntime( 5551): FATAL EXCEPTION: User-Facing Blocking-0
E/AndroidRuntime( 5551): Process: com.google.android.googlequicksearchbox:search, PID: 5551
E/AndroidRuntime( 5551): java.lang.RuntimeException: Unchecked exception running task: ExtraDexRegistry[Jar loading for icingsync]
E/AndroidRuntime( 5551): 	at com.google.android.apps.gsa.shared.util.c.a.q.g(TaskRunnerFutureTask.java:135)
E/AndroidRuntime( 5551): 	at com.google.android.apps.gsa.shared.util.c.a.q.aDg(TaskRunnerFutureTask.java:116)
E/AndroidRuntime( 5551): 	at com.google.android.apps.gsa.shared.util.c.a.q.done(TaskRunnerFutureTask.java:104)
E/AndroidRuntime( 5551): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 5551): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 5551): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 5551): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5551): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5551): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 5551): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 5551): Caused by: java.lang.IllegalArgumentException: optimizedDirectory not readable/writable: /data/data/com.google.android.googlequicksearchbox/files/extradex_jars/verified/icingsync
E/AndroidRuntime( 5551): 	at dalvik.system.DexPathList.<init>(DexPathList.java:101)
E/AndroidRuntime( 5551): 	at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 5551): 	at dalvik.system.DexClassLoader.<init>(DexClassLoader.java:57)
E/AndroidRuntime( 5551): 	at com.google.android.libraries.velour.dynloader.b.<init>(DexFirstClassLoader.java:20)
E/AndroidRuntime( 5551): 	at com.google.android.libraries.velour.dynloader.e.a(JarEntryPointLoader.java:82)
E/AndroidRuntime( 5551): 	at com.google.android.libraries.velour.dynloader.e.a(JarEntryPointLoader.java:35)
E/AndroidRuntime( 5551): 	at com.google.android.libraries.velour.dynloader.i.G(JarLoader.java:253)
E/AndroidRuntime( 5551): 	at com.google.android.libraries.velour.dynloader.i.bjN(JarLoader.java:135)
E/AndroidRuntime( 5551): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:337)
E/AndroidRuntime( 5551): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 5551): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 5551): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 5551): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5551): 	... 4 more
I/Process ( 5551): Sending signal. PID: 5551 SIG: 9
,I/ActivityManager(  878): Process com.google.android.googlequicksearchbox:search (pid 5551) has died
,W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,E/MP-Decision( 2161): Error(-22) changing core 2 status to offline
E/MP-Decision( 2161): Error(-22) changing core 1 status to offline

```
