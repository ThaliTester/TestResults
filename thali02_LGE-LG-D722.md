#### Test 5065027865f659b_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,D/AlertService( 5143): Beginning updateAlertNotification
D/AlertService( 5143): No fired or scheduled alerts
I/NotificationManager( 5143): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5143): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5143): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5143): No events found starting within 1 week.
--------- beginning of system
I/ActivityManager(  960): Killing 4997:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10018/pid_4997/cgroup.procs: No such file or directory
D/AndroidRuntime( 5199): 
D/AndroidRuntime( 5199): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5199): CheckJNI is OFF
D/AndroidRuntime( 5199): Calling main entry com.android.commands.am.Am
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  960): setTaskToReturnTo : TaskRecord{395d3e71 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  960): setTaskToReturnTo : TaskRecord{395d3e71 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  960): AppWindowTokenEx init.. 
D/ContextHelper(  960): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  960): Focus left window: Window{db58901 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5199): Shutting down VM
D/SplitWindow(  960): check instance of lgWin Window{a253f73 u0 Starting com.test.thalitest}
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5219 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1931): Closing mic
I/MicrophoneInputStream( 1931): mic_close com.google.android.apps.gsa.speech.audio.u@29f1f84b
V/AudioRecord( 1931): stop()
D/AudioRecord( 1931): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  285): Record stopped OK
V/AudioPolicyManager(  285): stopInput() input 17
V/AudioPolicyService(  285): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  285): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release audio patch
I/WindowStateAnimator(  960): Starting window displayed
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  285): ThreadBase::setParameters() routing=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3844000
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35a8b148,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = 2f000000
,V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyService(  285): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  285): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  285): setParameters(): io 17, keyvalue hotword_active=0, calling pid 285
V/AudioFlinger(  285): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  285): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  285): in_set_parameters: exit: status(0)
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3844000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
D/BarTransitions( 1370): draw background and invalidate : color = 36343434
,V/AudioRecord( 1931): stop()
V/AudioRecord( 1931): stop()
,V/AudioRecord( 1931): stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 17
V/AudioPolicyManager(  285): closeInput(17)
V/AudioFlinger(  285): releasing 16 from 1931 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): closeInput() 17
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  960): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): ThreadBase::exit
V/AudioFlinger(  285): RecordThread: loop starting
,V/AudioSystem( 1931): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2817): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1737): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1931): Stopping hotword detection.
V/AudioFlinger(  285): RecordThread 0xb3844000 exiting
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioSystem( 3085): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  285): removeClient_l() pid 1931, calling pid 285
I/HotwordRecognitionRnr( 1931): Hotword detection finished
,D/ContextHelper( 5219): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5219): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5219): Time to load native libraries: 2 ms (timestamps 2785-2787)
,I/LibraryLoader( 5219): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5219): Binding Chromium to main looper Looper (main, tid 1) {151eacbc}
,I/LibraryLoader( 5219): Expected native library version number "",actual native library version number ""
I/chromium( 5219): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5219): Initializing chromium process, singleProcess=true
W/art     ( 5219): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5219): ApplicationContext is null in ApplicationStatus
W/chromium( 5219): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5219): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5219): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5219): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5219): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5219): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5219): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5219): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5219): Remote Branch: 
I/Adreno-EGL( 5219): Local Patches: 
I/Adreno-EGL( 5219): Reconstruct Branch: 
V/AudioPolicyService(  285): registerClient() client 0xb57e81c0, uid 10316
,D/BluetoothManagerService(  960): Message: 20
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3539bf1d:true
,D/BluetoothAdapter( 5219): 751476673: getState() :  mService = null. Returning STATE_OFF
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,W/art     ( 5219): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5219): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5219): CordovaWebView is running on device made by: LGE
,W/art     ( 5219): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5219): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5219): Activity.onPostResume() called 
,D/OpenGLRenderer( 5219): Render dirty regions requested: true
,I/OpenGLRenderer( 5219): Initialized EGL, version 1.4
D/OpenGLRenderer( 5219): Enabling debug mode 0
D/Atlas   ( 5219): Validating map...
,D/SplitWindow(  960): check instance of lgWin Window{17eda98d u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5219): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  960): Focus entered window: Window{17eda98d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  960): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +1s214ms
I/Timeline(  960): Timeline: Activity_windows_visible id: ActivityRecord{12203456 u0 com.test.thalitest/.MainActivity t220} time:93551
I/Timeline( 5219): Timeline: Activity_idle id: android.os.BinderProxy@10b6bbd8 time:93572
,W/BindingManager( 5219): Cannot call determinedVisibility() - never saw a connection for the pid: 5219
,D/JsMessageQueue( 5219): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{2a0d8c9a type 0 when 1449598335833 com.android.vending} when 1449598335833
,D/Finsky  ( 4836): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/jxcore_app_log( 5219): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618635264
D/JX-Cordova( 5219): jxcore cordova android initializing
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,I/art     ( 5219): CheckpointMarkThreadRoots callback created = 0x9a504a80
,I/art     ( 5219): CheckpointMarkThreadRoots callback created = 0x9a504a50
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4836): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 94850680124; DSPS: 3206118; Offset : -2997529542
,I/ActivityManager(  960): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5310 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4836): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5310): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5310): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5310): VM with version 2.1.0 has multidex support
I/MultiDex( 5310): install
I/MultiDex( 5310): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5310): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 5310): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5310): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19500e9e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5310): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5310): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5310): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
,E/MDM     ( 1729): [92] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 2013): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2013): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 2286): Restart initialization of location
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 2013): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 2286): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/GCoreFlp( 1729): No location to return for getLastLocation()
,W/FusedLocationProvider( 2013): location=null
,I/art     (  960): Explicit concurrent mark sweep GC freed 16994(761KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 4.111ms total 252.837ms
,D/NativeLibraryUtils( 5310): Install completed successfully. count=13 extracted=0
,I/art     ( 5310): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5310): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/NotificationManager( 5310): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 4836): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 4836): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4836): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4836): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 4836): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{14787e81 type 0 when 1449598337380 com.android.vending} when 1449598337380
,D/Finsky  ( 4836): [1] DailyHygiene.reschedule: Scheduling new run in 257 minutes (failures=4)
D/DeviceConnectionService( 1729): client connected with version: 8296000
,D/Finsky  ( 4836): [564] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/jxcore-log( 5219): Initializing JXcore engine
,W/jxcore-log( 5219): JXcore engine is ready
W/jxcore-log( 5219): Starting JXcore engine
,W/.test.thalitest( 5219): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8423]" dev="sockfs" ino=8423 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5219): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5219): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6465]" dev="sockfs" ino=6465 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5219): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5219): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5219): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[22092]" dev="sockfs" ino=22092 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/ProcessCpuTracker(  960): Skipping unknown process pid 5297
W/ProcessCpuTracker(  960): Skipping unknown process pid 5298
W/ProcessCpuTracker(  960): Skipping unknown process pid 5300
W/ProcessCpuTracker(  960): Skipping unknown process pid 5309
W/ProcessCpuTracker(  960): Skipping unknown process pid 5352
,W/jxcore-log( 5219): Platform android
W/jxcore-log( 5219): 
,W/jxcore-log( 5219): Process ARCH arm
W/jxcore-log( 5219): 
I/ActivityManager(  960): Process com.google.android.talk (pid 4910) has died
,I/jxcore-log( 5219): JXcore Cordova bridge is ready!
I/jxcore-log( 5219): 
,W/jxcore-log( 5219): JXcore engine is started
,I/chromium( 5219): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/jxcore  ( 5219): Error!: missing ) after argument list
E/jxcore  ( 5219): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5219): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/InputDispatcher(  960): Focus left window: Window{17eda98d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (162 us)
,W/PluginManager( 5219): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 33ms. Plugin should use CordovaInterface.getThreadPool().
I/[LGHome]EVENT( 1874): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1874): [Launcher.java:776:onResume()]onResume
,I/[LGHome]LGActivityUtil( 1874): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1874): [Launcher.java:929:onResume()]onResume end
I/Activity( 1874): Activity.onPostResume() called 
I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/WeatherAncestor( 2797): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:12:19
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35a8b148,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/InputDispatcher(  960): Focus entered window: Window{db58901 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/UpdateThreadPoolManager( 2797): 2 : This is isUpdating : false
W/[LGHome]LGWallpaperInfo( 1874): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WeatherService( 2797): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WallpaperManager( 1874): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/WeatherService( 2797): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 2797): 2 : shouldTimeTickRegistered().........
D/WeatherAncestor( 2797): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 19:12:19
D/WeatherService( 2797): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2797): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2797): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2797): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2797): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 2797): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2797): 2 : This is isUpdating : false
D/WeatherService( 2797): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2797): 2 : buildUpdate, appWidgetId: 2
,D/WeatherTheme( 2797): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2797): 2 : Fixed theme : optimus
D/WeatherReflect( 2797): 2 : Map key string is -2
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1874): [setNavigationBarColor] color=0x 0
D/lim     ( 2797): 2 : time = 19:12
I/WeatherReflect( 2797): Model Name : LG-D722
D/WeatherTheme( 2797): 2 : exactly same view!
D/WeatherTheme( 2797): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/InputMethodManagerService(  960): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/IInputConnectionWrapper( 5219): showStatusIcon on inactive InputConnection
,W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2797): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2797): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2797): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Timeline( 1874): Timeline: Activity_idle id: android.os.BinderProxy@22e2920a time:98040
I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@35a8b148,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = f8000000
D/BarTransitions( 1370): draw background and invalidate : color = f7ededed
I/HotwordRecognitionRnr( 1931): Starting hotword detection.
,I/MicrophoneInputStream( 1931): mic_starting com.google.android.apps.gsa.speech.audio.u@300b64f7
V/AudioRecord( 1931): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1931): set(): mSessionId 22
V/AudioPolicyManager(  285): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  285): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  285): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  285): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e420)
V/audio_hw_primary(  285): adev_open_input_stream: exit
V/AudioFlinger(  285): openInput_l() openInputStream returned input 0xb546e420, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  285): openInput_l() created record thread: ID 23 thread 0xb3844000
V/AudioSystem(  285): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioSystem(  960): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioSystem( 1931): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3085): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
I/AudioFlinger(  285): AudioFlinger's thread 0xb3844000 ready to run
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioSystem( 1370): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2817): ioConfigChanged() event 3, ioHandle 23
,V/AudioSystem( 1737): ioConfigChanged() event 3, ioHandle 23
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioFlinger(  285): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  285): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  285): acquiring 22 from 1931, for -1
V/AudioFlinger(  285):  added new entry for 22
V/AudioRecord( 1931): start, sync event 0 trigger session 0
V/AudioRecord( 1931): mAudioRecord->start()
V/AudioFlinger(  285): RecordHandle::start()
V/AudioFlinger(  285): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  285): startInput() module primary->input primary(23)
V/AudioPolicyManager(  285): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  285): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  285): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  285): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  285): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  285): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  285): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  285): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  285): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  285): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  285): in_set_parameters: exit: status(0)
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3844000
V/AudioFlinger::PatchPanel(  285): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  285): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  285): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  285): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  285): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  285): setParameters(): io 23, keyvalue hotword_active=1, calling pid 285
V/AudioFlinger(  285): ThreadBase::setParameters() hotword_active=1
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  285): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  285): in_set_parameters: exit: status(0)
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3844000
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): AudioPolicyManager::startInput() input source = 1999
,I/MicrophoneInputStream( 1931): mic_started com.google.android.apps.gsa.speech.audio.u@300b64f7
V/msm8974_platform(  285): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  285): start_input_stream: enter: stream(0xb546e420)usecase(7: audio-record)
V/voice   (  285): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  285): start_input_stream: usecase(7)
E/audio_hw_primary(  285): select_devices: enter and usecase(7)
V/msm8974_platform(  285): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  285): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  285): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  285): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  285): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  285): enable_snd_device: enter  144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  285): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
,D/ACDB-LOADER(  285): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  285): ACDB -> send_adm_topology
D/ACDB-LOADER(  285): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  285): ACDB -> send_asm_topology
D/ACDB-LOADER(  285): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  285): ACDB -> send_audtable
D/ACDB-LOADER(  285): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  285): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  285): ACDB -> send_audvoltable
D/ACDB-LOADER(  285): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  285): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  285): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  285): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  285): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  285): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  285): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  285): enable_audio_route: exit
D/audio_hw_primary(  285): select_devices: done
V/audio_hw_primary(  285): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  285): start_input_stream: exit
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/HotwordWorker( 1931): onReady
,I/Timeline(  960): Timeline: Activity_windows_visible id: ActivityRecord{ae7bce5 u0 com.lge.launcher2/.Launcher t219} time:98313
,D/InputDispatcher(  960): Window went away: Window{17eda98d u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/OpenGLRenderer( 1874): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1874): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1874): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1874): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1874): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1874): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/ActivityManager(  960): Killing 5016:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10069/pid_5016/cgroup.procs: No such file or directory
,I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{23c62b44 type 0 when 1449598352101 com.android.vending} when 1449598352101
,W/ContextImpl( 3342): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 4836): [555] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4836): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 114852824855; DSPS: 3861548; Offset : -2997521095
,I/MusicWidget( 2753): mDelayedStopHandler : unbind
,I/MusicBrowser( 2817): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2817): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2817): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2817): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2817): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2817): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2817): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  960):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@318b8b4acom.lge.music.MediaPlaybackService$6@22170abb
,D/MusicBrowser( 2817): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2cca9fc1
,I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2817): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2817): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2817): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2817): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2817): reset
V/MediaPlayer[Native]( 2817): setListener
,V/MediaPlayer[Native]( 2817): disconnect
V/MediaPlayer[Native]( 2817): destructor
V/AudioFlinger(  285): releasing 19 from 2817 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/MediaPlayer[Native]( 2817): disconnect
D/MusicBrowser( 2817): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2817): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2817): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2817): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2817): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2817): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2817): [SmartShareManagerClient] unregisterListener: 280411096
W/SmartShareClient( 2817): [SmartShareManagerClient] unregisterListener invalid listener: 280411096
I/SmartShareClient( 2817): [SmartShareManagerClient] terminate service: 2817/MediaPlaybackService/368992431
E/HomeCloudIF( 2817): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2817): [SmartShareManagerClient] unbindService context:android.app.Application@2c19fb31
V/CloudHub( 2817): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2817): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2817): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2817): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2817): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  960): Killing 4787:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/CloudHub( 2817): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29986
,W/libprocessgroup(  960): failed to open /acct/uid_10086/pid_4787/cgroup.procs: No such file or directory
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2817): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19977
,D/charger_monitor(  484): init target 500000
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 134854168130; DSPS: 4516952; Offset : -2997520358
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=608453509, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,D/WeatherService( 2797): 2 : TimeTick Intent has been received, Time(hour:min:sec) 19:13:0
D/WeatherService( 2797): 2 : TimeTick Intent And Screen On
D/WeatherService( 2797): 2 : SDK version : 21
W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2797): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2797): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2797): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2797): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2797): 2 : This is isUpdating : false
D/WeatherService( 2797): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2797): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2797): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2797): 2 : Fixed theme : optimus
D/WeatherReflect( 2797): 2 : Map key string is -2
D/lim     ( 2797): 2 : time = 19:13
I/WeatherReflect( 2797): Model Name : LG-D722
D/WeatherTheme( 2797): 2 : Different view - status_min_formatted : 12 != 13
D/WeatherTheme( 2797): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2797): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2797): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2797): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2797): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2797): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2797): forecast size is 0
D/Theme   ( 2797): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2797): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2797): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2797): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2797): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2797): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2797): setTouchIntent, appWidgetId: 2
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/Theme_WeatherAncestor_optimus( 2797): url is : null
D/Theme   ( 2797): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2797): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2797): 2 : update view, appWidgetId: 2
D/WeatherService( 2797): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 19:13:0
,D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=608453509 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2817): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2817): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/PowerManagerService(  960): ALS enabled for SRE
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28600 ms ago)
,D/qdlights(  960): set_light_backlight: 253
,D/qdlights(  960): set_light_backlight: 250
D/qdlights(  960): set_light_backlight: 247
,D/qdlights(  960): set_light_backlight: 243
,D/qdlights(  960): set_light_backlight: 240
,D/qdlights(  960): set_light_backlight: 237
,D/qdlights(  960): set_light_backlight: 233
,D/qdlights(  960): set_light_backlight: 230
,D/qdlights(  960): set_light_backlight: 227
,D/qdlights(  960): set_light_backlight: 223
,D/qdlights(  960): set_light_backlight: 220
,D/qdlights(  960): set_light_backlight: 217
,D/qdlights(  960): set_light_backlight: 213
,D/qdlights(  960): set_light_backlight: 210
,D/qdlights(  960): set_light_backlight: 207
,D/qdlights(  960): set_light_backlight: 203
,D/qdlights(  960): set_light_backlight: 200
,D/qdlights(  960): set_light_backlight: 197
,D/qdlights(  960): set_light_backlight: 193
,D/qdlights(  960): set_light_backlight: 190
,D/qdlights(  960): set_light_backlight: 187
,D/qdlights(  960): set_light_backlight: 183
,D/qdlights(  960): set_light_backlight: 180
,D/qdlights(  960): set_light_backlight: 177
,D/qdlights(  960): set_light_backlight: 173
,D/qdlights(  960): set_light_backlight: 170
,D/qdlights(  960): set_light_backlight: 167
,D/qdlights(  960): set_light_backlight: 163
,D/qdlights(  960): set_light_backlight: 160
,D/qdlights(  960): set_light_backlight: 157
,D/qdlights(  960): set_light_backlight: 153
,D/qdlights(  960): set_light_backlight: 150
,D/qdlights(  960): set_light_backlight: 146
,D/qdlights(  960): set_light_backlight: 143
,D/qdlights(  960): set_light_backlight: 140
,D/qdlights(  960): set_light_backlight: 136
,D/qdlights(  960): set_light_backlight: 133
,D/qdlights(  960): set_light_backlight: 130
,D/qdlights(  960): set_light_backlight: 126
,D/qdlights(  960): set_light_backlight: 123
,D/qdlights(  960): set_light_backlight: 120
,D/qdlights(  960): set_light_backlight: 116
,D/qdlights(  960): set_light_backlight: 113
,D/qdlights(  960): set_light_backlight: 110
,D/qdlights(  960): set_light_backlight: 106
,D/qdlights(  960): set_light_backlight: 103
,D/qdlights(  960): set_light_backlight: 100
,D/qdlights(  960): set_light_backlight: 96
,D/qdlights(  960): set_light_backlight: 93
,D/qdlights(  960): set_light_backlight: 90
,D/qdlights(  960): set_light_backlight: 86
,D/qdlights(  960): set_light_backlight: 83
,D/qdlights(  960): set_light_backlight: 80
,D/qdlights(  960): set_light_backlight: 76
,D/qdlights(  960): set_light_backlight: 73
,D/qdlights(  960): set_light_backlight: 70
,D/qdlights(  960): set_light_backlight: 66
,D/qdlights(  960): set_light_backlight: 63
,D/qdlights(  960): set_light_backlight: 60
,D/qdlights(  960): set_light_backlight: 56
,D/qdlights(  960): set_light_backlight: 53
,D/qdlights(  960): set_light_backlight: 50
,D/qdlights(  960): set_light_backlight: 46
,D/qdlights(  960): set_light_backlight: 43
,D/qdlights(  960): set_light_backlight: 40
,D/qdlights(  960): set_light_backlight: 36
,D/qdlights(  960): set_light_backlight: 33
,D/qdlights(  960): set_light_backlight: 29
,D/qdlights(  960): set_light_backlight: 26
,D/qdlights(  960): set_light_backlight: 23
,D/qdlights(  960): set_light_backlight: 19
,D/qdlights(  960): set_light_backlight: 16
,D/qdlights(  960): set_light_backlight: 13
,D/qdlights(  960): set_light_backlight: 10
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{1727542d type 2 when 129237 com.google.android.gms} when 129237
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{1f32bd62 type 2 when 132661 com.google.android.gms} when 132661
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd( 2013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd( 2013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager(  960): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5470 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5470): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5470): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5470): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5470): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5470): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5470): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5470): MmsConfig.loadFromResources
E/Babel_SMS( 5470): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5470): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 5470): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5470): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5470): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5470): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5470): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5470): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5470): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5470): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5470): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5470): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5470): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5470): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5470): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5470): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5470): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5470): found sensor: Motion Accel, handle=46
,W/Settings( 5470): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5470): startup - clean
,I/Babel   ( 5470): deleted: false for 0
,I/art     ( 5470): CheckpointMarkThreadRoots callback created = 0xb002d960
,W/AudioCapabilities( 5470): Unsupported mime audio/x-lg-flac
I/art     ( 5470): CheckpointMarkThreadRoots callback created = 0xb002d940
,W/AudioCapabilities( 5470): Unsupported mime audio/adpcm
W/AudioCapabilities( 5470): Unsupported mime audio/g726
W/AudioCapabilities( 5470): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5470): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5470): Unsupported mime video/mjpg
W/VideoCapabilities( 5470): Unsupported mime video/theora
,W/AudioCapabilities( 5470): Unsupported mime audio/evrc
,W/AudioCapabilities( 5470): Unsupported mime audio/qcelp
W/VideoCapabilities( 5470): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5470): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5470): Unsupported mime audio/qcelp
W/AudioCapabilities( 5470): Unsupported mime audio/evrc
W/VideoCapabilities( 5470): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5470): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5470): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5470): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5470): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5470): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  960): Killing 5047:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  960): failed to open /acct/uid_10053/pid_5047/cgroup.procs: No such file or directory
,I/vclib   ( 5470): onServiceConnected
W/Babel   ( 5470): Attempted to change video mute state without an active call.
I/NotificationManager( 5470): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 154855265673; DSPS: 5172348; Offset : -2997521683
,I/PowerManagerService(  960): ALS enabled for SRE
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35585 ms ago)
I/PowerManagerService(  960): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  960): ALS enabled for SRE
,D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35593 ms ago)
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  960): Sleeping (uid 1000)...
D/LPWGController(  960): [updateScreenState] screen on = false
,D/LPWGController(  960): disable proximity sensor
D/LPWGController(  960): enable proximity sensor
I/SensorManager(  960): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2ee56ce0] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  960): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  960): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  960): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  960): activate: handle is 48, enable
,V/sensors_hal_Ctx(  960): activate sensors is 1400000000000
D/sensors_hal_Thresh(  960): enable: handle=48
I/sensors_hal_SAM(  960): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  960): waitForResponse: timeout=1000
V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  960): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  960): enable: Received response: 0
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35620 ms ago)
I/Adreno-EGL(  960): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  960): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  960): Build Date: 03/02/15 Mon
I/Adreno-EGL(  960): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  960): Remote Branch: 
I/Adreno-EGL(  960): Local Patches: 
I/Adreno-EGL(  960): Reconstruct Branch: 
,I/Sensors (  439): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  960): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  960): processInd: handle 48, count=1
V/sensors_hal_Thresh(  960): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  960): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  960): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  960): poll: count: 256
I/sensors_hal_Ctx(  960): poll: released wakelock sensor_ind
D/sensors_hal_Util(  960): waitForResponse: timeout=0
D/LPWGController(  960): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  960): current mode = 1  value = 1 1
I/LPWGController(  960): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  960): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  960): set_light_backlight: 0
,I/SensorManager(  960): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  960): activate: handle is 46, disable
V/sensors_hal_Ctx(  960): activate sensors is 1000000000000
D/sensors_hal_LP2(  960): enable: handle=46
,D/sensors_hal_LP2(  960): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  960): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  960): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  960): Display changed displayId=0
,V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  960): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1737): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  960): Excessive delay in setPowerMode(): 249ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  960): Got set_interactive hint
,I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
,D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
I/HotwordDetector( 1931): Closing mic
I/MicrophoneInputStream( 1931): mic_close com.google.android.apps.gsa.speech.audio.u@300b64f7
V/AudioRecord( 1931): stop()
D/AudioRecord( 1931): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
,V/AudioFlinger(  285): Record stopped OK
V/AudioPolicyManager(  285): stopInput() input 23
V/AudioPolicyService(  285): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  285): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch handle 24
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  285): ThreadBase::setParameters() routing=0
,V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3844000
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
,V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
,V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
,V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 20 af handle 24
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() adding set parameter string hotword_active=0, io 23 ,delay 0
V/AudioPolicyService(  285): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing set parameters string hotword_active=0, io 23
V/AudioFlinger(  285): setParameters(): io 23, keyvalue hotword_active=0, calling pid 285
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioFlinger(  285): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  285): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  285): in_set_parameters: exit: status(0)
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3844000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioRecord( 1931): stop()
,V/AudioRecord( 1931): stop()
V/AudioRecord( 1931): stop()
D/KeyguardViewMediator( 1370): notifyScreenOffLocked
V/AudioFlinger(  285): releasing 22 from 1931 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 23
V/AudioPolicyManager(  285): closeInput(23)
V/AudioFlinger(  285): closeInput() 23
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 1931): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  285): ThreadBase::exit
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): RecordThread 0xb3844000 exiting
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  285): removeClient_l() pid 1931, calling pid 285
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioSystem( 2817): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 1737): ioConfigChanged() event 4, ioHandle 23
,V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioSystem( 3085): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem(  960): ioConfigChanged() event 4, ioHandle 23
I/HotwordRecognitionRnr( 1931): Stopping hotword detection.
I/HotwordRecognitionRnr( 1931): Hotword detection finished
D/WifiServerServiceExt(  960): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 960
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: enter: screen_state=on
,V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  285): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1370): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
D/GpsLocationProvider(  960): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
,I/LEDService( 1796): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1796): stopPatternFlashing()
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1796): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,I/LEDService( 1796): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1796): lockStatus = 0
I/LEDService( 1796): updateLightsLocked : turn off led
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1783): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1796): RESTART MSG
D/NfcServiceNXP( 1783): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1783): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 3
D/NfcService( 1783): Discovery configuration equal, not updating.
,D/SplitWindow(  960): check instance of lgWin Window{348ea23f u0 SearchPanel}
,D/InputDispatcher(  960): Window went away: Window{17f2811c u0 SearchPanel}
,I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,D/Ulp_jni (  960): JNI:system_update. Event-0
,V/PhoneApp( 1737): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2797): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:13:18
,D/WeatherService( 2797): 2 : ACTION screen on
D/WeatherService( 2797): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2797): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2797): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:13:18
D/AppCleanupService( 3754): android.intent.action.SCREEN_ON
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 960
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/WifiController(  960): CMD_SCREEN_OFF 
D/WifiController(  960): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  960): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1796): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1796): stopPatternFlashing()
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
I/LEDService( 1796): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1796): set_light_notifications: 0,0,0,0,3
I/LEDService( 1796): updateLightsLocked : turn on led
E/LEDService( 1796): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1796): Can't handle this request of patternId:0
D/LEDHandler( 1796): RESTART MSG
D/VolumeVibrator( 1796): clear
I/Cliptray Service( 1796): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1783): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1783): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
W/ActivityManager(  960): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,V/PhoneApp( 1737): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2797): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:13:18
D/WeatherService( 2797): 2 : ACTION screen off
D/WeatherService( 2797): 2 : TimeTick Receiver Unregister
D/WeatherService( 2797): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:13:18
D/AppCleanupService( 3754): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3754): AppUsageStatsSaveTask
E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: 0
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 1
E/NxpNfcJni( 1783): getReconnectState = 0x0
,I/Sensors (  439): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{11e4770c type 2 when 161607 com.android.systemui} when 161607
,D/PhoneUtils( 1737): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1737): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1737): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1737): getCallState : 0
,D/PhoneUtils( 1737): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1737): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1737): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 174857244521; DSPS: 5827772; Offset : -2997496064
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1729): disconnect managed GoogleApiClient
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{19d48855 type 2 when 186933 com.google.android.gms} when 186933
,I/NotificationManager( 1931): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  484): init target 500000
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 194859837116; DSPS: 6483218; Offset : -2997527798
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=608453509, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{1bfb36 type 2 when 188595 com.google.android.gms} when 188595
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=608453509 [*alarm*], flags=0x0
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 214862381693; DSPS: 7138661; Offset : -2997516389
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{14389a37 type 2 when 186664 android} when 186664
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 234864931632; DSPS: 7794104; Offset : -2997499461
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): init target 500000
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 254867338344; DSPS: 8449543; Offset : -2997503611
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 274868963701; DSPS: 9104957; Offset : -2997525969
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 294871962756; DSPS: 9760415; Offset : -2997517897
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 314874507540; DSPS: 10415858; Offset : -2997506071
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 334877054514; DSPS: 11071302; Offset : -2997522471
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  960): remove 3dea0328
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  960): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  960): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  960): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=608453509, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{18a09ba4 type 2 when 275839 com.google.android.gms} when 275839
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=608453509 [*alarm*], flags=0x0
,D/libc-netbsd( 2013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
,D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 354879592731; DSPS: 11726745; Offset : -2997517083
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 374882143089; DSPS: 12382188; Offset : -2997499918
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 394884690426; DSPS: 13037632; Offset : -2997516057
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 414887241823; DSPS: 13693075; Offset : -2997497619
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 434889791400; DSPS: 14348519; Offset : -2997511232
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 454891425038; DSPS: 15003933; Offset : -2997525752
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 474893966332; DSPS: 15659376; Offset : -2997517417
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 494896514505; DSPS: 16314819; Offset : -2997502203
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 514899058974; DSPS: 16970263; Offset : -2997521210
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 534901914383; DSPS: 17625716; Offset : -2997503963
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 554904457553; DSPS: 18281160; Offset : -2997524373
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 574907007544; DSPS: 18936603; Offset : -2997507236
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 594909556807; DSPS: 19592047; Offset : -2997521477
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 614912013465; DSPS: 20247487; Offset : -2997506095
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 634914556480; DSPS: 20902930; Offset : -2997496377
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=608453509, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{1661994b type 2 when 604105 com.google.android.gms} when 604105
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=608453509 [*alarm*], flags=0x0
,D/libc-netbsd( 2013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 654917100796; DSPS: 21558374; Offset : -2997515251
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 674919512714; DSPS: 22213813; Offset : -2997513727
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 694921412186; DSPS: 22869235; Offset : -2997506527
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 714923958533; DSPS: 23524679; Offset : -2997523839
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 734926508056; DSPS: 24180122; Offset : -2997507301
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 754929054975; DSPS: 24835566; Offset : -2997523859
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 774931409498; DSPS: 25491003; Offset : -2997519007
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 794933953605; DSPS: 26146446; Offset : -2997508146
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 814936356517; DSPS: 26801885; Offset : -2997516044
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 834938902341; DSPS: 27457328; Offset : -2997503205
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 854941908687; DSPS: 28112787; Offset : -2997518073
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 874944449096; DSPS: 28768230; Offset : -2997510648
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 894946999090; DSPS: 29423674; Offset : -2997524184
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 914949544653; DSPS: 30079117; Offset : -2997511241
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 934952093085; DSPS: 30734560; Offset : -2997496132
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 954954647296; DSPS: 31390004; Offset : -2997505790
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 974957195934; DSPS: 32045448; Offset : -2997520081
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 994959585039; DSPS: 32700886; Offset : -2997511451
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1014962137221; DSPS: 33356330; Offset : -2997522668
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1034963786118; DSPS: 34011744; Offset : -2997521720
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1054966336006; DSPS: 34667187; Offset : -2997504842
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1074967980269; DSPS: 35322601; Offset : -2997508477
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1094970527242; DSPS: 35978044; Offset : -2997494540
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1114973074788; DSPS: 36633488; Offset : -2997510524
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1134975621495; DSPS: 37288931; Offset : -2997496645
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1154978166855; DSPS: 37944375; Offset : -2997514839
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=608453509, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{1cbabc04 type 2 when 1155496 com.google.android.gms} when 1155496
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=608453509 [*alarm*], flags=0x0
,D/libc-netbsd( 2013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1174980717107; DSPS: 38599818; Offset : -2997497468
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1194983264963; DSPS: 39255262; Offset : -2997513116
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1214985815529; DSPS: 39910705; Offset : -2997495509
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  960): User[0] Flushing usage stats to disk
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1234987480209; DSPS: 40566120; Offset : -2997509296
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1254990364630; DSPS: 41221575; Offset : -2997523758
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1274992204620; DSPS: 41876995; Offset : -2997515057
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1294994757009; DSPS: 42532438; Offset : -2997495913
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1314996778617; DSPS: 43187865; Offset : -2997518722
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1334999196161; DSPS: 43843304; Offset : -2997511912
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1355001958450; DSPS: 44498754; Offset : -2997496335
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1375004501094; DSPS: 45154198; Offset : -2997517271
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1395006144265; DSPS: 45809612; Offset : -2997521997
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1415008692538; DSPS: 46465055; Offset : -2997506630
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1435010807793; DSPS: 47120485; Offset : -2997527424
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1455013354660; DSPS: 47775928; Offset : -2997513724
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1475015756576; DSPS: 48431367; Offset : -2997522698
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1495018302662; DSPS: 49086810; Offset : -2997509597
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1515020833694; DSPS: 49742253; Offset : -2997511602
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1535023385772; DSPS: 50397697; Offset : -2997522870
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1555025788056; DSPS: 51053135; Offset : -2997502780
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1575027500757; DSPS: 51708551; Offset : -2997499064
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1595030518825; DSPS: 52364011; Offset : -2997530747
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1615033067304; DSPS: 53019454; Offset : -2997515383
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1635035620424; DSPS: 53674897; Offset : -2997495196
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1655038035935; DSPS: 54330337; Offset : -2997521196
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1675040582440; DSPS: 54985780; Offset : -2997507599
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1796): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1796): Battery Level Remaining: 100%
D/LEDHandler( 1796): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  960): battery changed pluggedType: 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1695042988263; DSPS: 55641219; Offset : -2997512508
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1715045535182; DSPS: 56296662; Offset : -2997498678
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1735048081843; DSPS: 56952106; Offset : -2997515571
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1755050576522; DSPS: 57607548; Offset : -2997523047
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1775053120838; DSPS: 58262991; Offset : -2997511924
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1795055658482; DSPS: 58918434; Offset : -2997507240
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1815058203531; DSPS: 59573877; Offset : -2997495202
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1835060748105; DSPS: 60229321; Offset : -2997514182
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1855063571586; DSPS: 60884773; Offset : -2997498214
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1796): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1875066114443; DSPS: 61540217; Offset : -2997518833
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  960): Prepared write state in 19ms
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4836): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4836): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
,D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ProcessStatsService(  960): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-12-53.bin
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1895068664436; DSPS: 62195660; Offset : -2997501748
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5792): 
D/AndroidRuntime( 5792): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5792): CheckJNI is OFF
D/AndroidRuntime( 5792): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  960): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  960): Killing 5219:com.test.thalitest/u0a316 (adj 13): stop com.test.thalitest
W/PackageSettings(  960): Skipping PackageSetting{79b13ed com.example.hello/10030} due to missing metadata
I/ActivityManager(  960): Killing 5143:com.android.calendar/u0a13 (adj 15): empty for 1817s
I/ActivityManager(  960): Killing 4879:com.lge.qremote/u0a106 (adj 15): empty for 1823s
I/ActivityManager(  960): Killing 4591:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty for 1823s
W/ActivityManager(  960): Spurious death for ProcessRecord{29ac8c64 5219:com.test.thalitest/u0a316}, curProc for 5219: null
W/libprocessgroup(  960): failed to open /acct/uid_10013/pid_5143/cgroup.procs: No such file or directory
I/ActivityManager(  960): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/art     ( 1874): Explicit concurrent mark sweep GC freed 8399(483KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.025ms total 50.378ms
W/libprocessgroup(  960): failed to open /acct/uid_10106/pid_4879/cgroup.procs: No such file or directory
I/art     ( 1931): Explicit concurrent mark sweep GC freed 2221(145KB) AllocSpace objects, 2(689KB) LOS objects, 40% free, 12MB/20MB, paused 1.175ms total 64.192ms
E/lowmemorykiller(  243): Error opening /proc/4591/oom_score_adj; errno=2
W/ActivityManager(  960): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  960): android.os.DeadObjectException
W/ActivityManager(  960): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  960): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  960): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  960): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  960): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  960): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  960): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  960): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  960): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  960): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/ActivityManager(  960): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  960): android.os.DeadObjectException
W/ActivityManager(  960): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  960): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  960): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  960): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  960): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  960): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  960): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  960): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  960): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  960): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  960): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  960): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/libprocessgroup(  960): failed to open /acct/uid_10089/pid_4591/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3342): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3342): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3342): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3342): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3342): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3342): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5818 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  960): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5824 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 23.137ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.168ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 22.230ms
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     (  960): Explicit concurrent mark sweep GC freed 63174(3MB) AllocSpace objects, 18(390KB) LOS objects, 33% free, 23MB/35MB, paused 9.389ms total 239.309ms
I/art     (  960): WaitForGcToComplete blocked for 89.716ms for cause Explicit
D/administrator(  960): Handling package changes for user 0
I/art     (  960): Explicit concurrent mark sweep GC freed 8018(457KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.746ms total 233.869ms
I/art     (  960): WaitForGcToComplete blocked for 263.838ms for cause Explicit
I/NotificationService(  960): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  960): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  960): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  960): removeObsoleteFile: deleting file=220_task.xml
D/TaskPersister(  960): removeObsoleteFile: deleting file=220_task_thumbnail.png
D/AndroidRuntime( 5792): Shutting down VM
W/ResourcesManager(  960): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     (  960): Explicit concurrent mark sweep GC freed 4167(212KB) AllocSpace objects, 1(576KB) LOS objects, 33% free, 23MB/34MB, paused 2.392ms total 192.103ms
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 5818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5818): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5818): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LockScreenSettings( 5824): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): handleShortcutListChanged...
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
I/ActivityManager(  960): Killing 5116:com.android.providers.calendar/u0a14 (adj 15): empty for 1814s
W/ResourceType(  960): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/KeyguardModel( 1370): handleShortcutListChanged...
W/libprocessgroup(  960): failed to open /acct/uid_10014/pid_5116/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/LGEmail ( 5818): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 5818): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]

```
