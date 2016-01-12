#### Test 55613145ac448d4_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,D/Finsky  ( 4935): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
--------- beginning of system
V/AlarmManager(  857): RTC_WAKEUP set : Alarm{38e180a2 type 0 when 1452596467825 com.android.vending} when 1452596467825
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1729): Explicit concurrent mark sweep GC freed 32598(2MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 13MB/22MB, paused 1.385ms total 133.454ms
I/NotificationManager(  857): android: cancelAsUser(2) by android
I/ActivityManager(  857): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5322 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/AndroidRuntime( 5306): 
D/AndroidRuntime( 5306): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5306): CheckJNI is OFF
I/GservicesProvider( 5322): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient( 5322): GMS http client unavailable, use old client
I/GoogleHttpClient( 5322): GMS http client unavailable, use old client
D/libc-netbsd( 4935): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4935): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4935): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4935): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4935): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  857): android: cancelAsUser(2) by android
D/libc-netbsd( 4935): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4935): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AndroidRuntime( 5306): Calling main entry com.android.commands.am.Am
I/ActivityManager(  857): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5363 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  857): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
D/ActivityManager(  857): setTaskToReturnTo : TaskRecord{2ce1fce4 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  857): setTaskToReturnTo : TaskRecord{2ce1fce4 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  857): AppWindowTokenEx init.. 
D/ContextHelper(  857): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  857): Focus left window: Window{322aca0b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5306): Shutting down VM
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
I/NotificationManager(  857): android: cancelAsUser(2) by android
D/SplitWindow(  857): check instance of lgWin Window{36cf924e u0 Starting com.test.thalitest}
I/ActivityManager(  857): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5380 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
W/ResourcesManager( 5363): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5363): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/WindowStateAnimator(  857): Starting window displayed
I/SystemUI[Framework](  857): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  857): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  857): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  857): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d7c3e71,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/libc-netbsd( 4935): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4935): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
W/Finsky  ( 4935): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ActivityThread( 1874): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1874): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1874): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1874): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1874): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1874): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1874): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1874): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1874): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BarTransitions( 1369): draw background and invalidate : color = 1a000000
D/BarTransitions( 1369): draw background and invalidate : color = 13121212
I/HotwordDetector( 1932): Closing mic
I/MicrophoneInputStream( 1932): mic_close com.google.android.apps.gsa.speech.audio.u@36b2ef72
V/AudioRecord( 1932): stop()
D/AudioRecord( 1932): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
,V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3868000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/ActivityManager(  857): Activity reported stop, but no longer stopping: ActivityRecord{1268d3c8 u0 com.lge.launcher2/.Launcher t219}
,I/MultiDex( 5363): VM with version 2.1.0 has multidex support
I/MultiDex( 5363): install
,I/MultiDex( 5363): VM has multidex support, MultiDex support library is disabled.
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  281): disable_audio_route: exit
,E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  281): stop_input_stream: exit: status(0)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  281): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  281): setParameters(): io 17, keyvalue hotword_active=0, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3868000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1932): stop()
,V/AudioRecord( 1932): stop()
V/AudioRecord( 1932): stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioSystem(  857): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 1932): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3095): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb3868000 exiting
V/AudioSystem( 1745): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2636): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1932, calling pid 281
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioFlinger(  281): releasing 16 from 1932 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
I/HotwordRecognitionRnr( 1932): Stopping hotword detection.
D/ContextHelper( 5380): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/HotwordRecognitionRnr( 1932): Hotword detection finished
V/JNIHelp ( 5363): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5363): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5363): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1217734c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5363): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5363): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5363): com.google.android.gms: cancel(39789) by com.google.android.gms
I/WebViewFactory( 5380): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
D/LocationInitializer( 3921): Restart initialization of location
,E/MDM     ( 1729): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 5363): Reading stored module config
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
D/ChimeraCfgMgr( 5363): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/LibraryLoader( 5380): Time to load native libraries: 2 ms (timestamps 3659-3661)
I/LibraryLoader( 5380): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5380): Binding Chromium to main looper Looper (main, tid 1) {3ed0299a}
,I/LibraryLoader( 5380): Expected native library version number "",actual native library version number ""
I/chromium( 5380): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5380): Initializing chromium process, singleProcess=true
W/art     ( 5380): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5380): ApplicationContext is null in ApplicationStatus
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 93757918873; DSPS: 3170410; Offset : -2997249843
,D/CAR.SERVICE( 5363): Connecting to CarCallService...
,W/chromium( 5380): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
I/art     ( 5363): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5363): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/chromium( 5380): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5380): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5380): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5380): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5380): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5380): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5380): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5380): Remote Branch: 
I/Adreno-EGL( 5380): Local Patches: 
I/Adreno-EGL( 5380): Reconstruct Branch: 
D/NativeLibraryUtils( 5363): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 5363): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5363): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5363): Creating a new PhoneAdapter instance
W/ActivityManager(  857): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5363): setListener: com.google.android.gms.car.dn@2e15c28b
W/ActivityManager(  857): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5363): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5363): Starting CarCallService with initial phone null
I/NotificationManager( 5363): com.google.android.gms: cancel(10436) by com.google.android.gms
,V/AudioPolicyService(  281): registerClient() client 0xb40273c0, uid 10316
,D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cbca686:true
D/BluetoothAdapter( 5380): 746014054: getState() :  mService = null. Returning STATE_OFF
,D/CAR.SERVICE( 5363): Package validated; name: com.android.vending
,I/NotificationManager( 4935): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 4935): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/art     ( 5380): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5380): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5380): CordovaWebView is running on device made by: LGE
,W/art     ( 5380): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5380): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 5380): Activity.onPostResume() called 
,D/OpenGLRenderer( 5380): Render dirty regions requested: true
I/OpenGLRenderer( 5380): Initialized EGL, version 1.4
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{1b1dded1 type 2 when 94281 com.google.android.gms} when 94281
D/OpenGLRenderer( 5380): Enabling debug mode 0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/Atlas   ( 5380): Validating map...
,D/SplitWindow(  857): check instance of lgWin Window{d683437 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5380): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  857): Focus entered window: Window{d683437 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/libc-netbsd( 4935): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4935): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4935): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4935): [1] DailyHygiene.access$600: Logging device features
W/InputMethodManagerService(  857): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  857): Displayed com.test.thalitest/.MainActivity: +1s282ms
I/Timeline(  857): Timeline: Activity_windows_visible id: ActivityRecord{339e554d u0 com.test.thalitest/.MainActivity t220} time:94432
I/Timeline( 5380): Timeline: Activity_idle id: android.os.BinderProxy@cd1d416 time:94452
,D/Finsky  ( 4935): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{2a51dfe6 type 0 when 1452596470013 com.android.vending} when 1452596470013
D/Finsky  ( 4935): [599] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1729): client connected with version: 8296000
,W/BindingManager( 5380): Cannot call determinedVisibility() - never saw a connection for the pid: 5380
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/Finsky  ( 4935): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 4935): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/libc-netbsd( 4935): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4935): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4935): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4935): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager(  857): Killing 5156:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10069/pid_5156/cgroup.procs: No such file or directory
,D/JsMessageQueue( 5380): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5380): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622827008
,D/JX-Cordova( 5380): jxcore cordova android initializing
I/art     ( 5380): CheckpointMarkThreadRoots callback created = 0x9b5c94f0
,I/art     ( 5380): CheckpointMarkThreadRoots callback created = 0x9b5c94c0
,I/art     (  857): Explicit concurrent mark sweep GC freed 20839(925KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.692ms total 224.991ms
,W/jxcore-log( 5380): Initializing JXcore engine
,W/jxcore-log( 5380): JXcore engine is ready
W/jxcore-log( 5380): Starting JXcore engine
,W/.test.thalitest( 5380): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7686]" dev="sockfs" ino=7686 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5380): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 5380): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5613]" dev="sockfs" ino=5613 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5380): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5380): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5380): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25563]" dev="sockfs" ino=25563 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ActivityManager(  857): Process com.google.android.gm (pid 5045) has died
,W/jxcore-log( 5380): Platform android
W/jxcore-log( 5380): 
W/jxcore-log( 5380): Process ARCH arm
W/jxcore-log( 5380): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5380): JXcore Cordova bridge is ready!
I/jxcore-log( 5380): 
W/jxcore-log( 5380): JXcore engine is started
,I/chromium( 5380): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 5380): Toggling radios to true
I/jxcore-log( 5380): 
,D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  857): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  857): Message: 1
,D/BluetoothManagerService(  857): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(746014054)( 1982): onBind()
,D/BluetoothManagerService(  857): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/LocationManagerService(  857): getAllProviders()=[passive, gps, network]
D/BluetoothManagerService(  857): Message: 40
D/BluetoothManagerService(  857): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/Ulp_jni (  857): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  857): JNI:system_update. Event-4
D/WifiServiceImplEx(  857): setWifiEnabled: true pid=5380, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  857): setWifiEnabled: true pid=5380, uid=10316
,D/LocationManagerService(  857): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  857): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  857): JNI:system_update. Event-4
D/WifiServiceImplEx(  857): disconnect pid=5380, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  857): reconnect pid=5380, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5380): Radios toggled
I/jxcore-log( 5380): 
I/jxcore-log( 5380): My device name is: LGE-LG-D722
I/jxcore-log( 5380): 
I/LGFTMITEM(  857): [GET_FTM][id=6], offset=12288
I/bluedroid( 1982): config_hci_snoop_log
E/WifiHW  (  857): Wifi MAC Address = a0:39:f7:70:12:80
D/BluetoothManagerService(  857): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  857): Broadcasting onBluetoothServiceUp() to 9 receivers.
E/WifiHW  (  857): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  857): band=b
E/WifiHW  (  857): ": cur_etheraddr=a0:39:f7:70:12:80
,D/SoftapController(  276): Softap fwReload - Ok
V/LGMDMManagerInternal( 1982): Create singleton instance
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Setting iface cfg
D/CommandListener(  276): Trying to bring down wlan0
D/CommandListener(  276): Clearing all IP addresses on wlan0
E/WifiHW  (  857): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/wpa_supplicant( 5501): Successfully initialized wpa_supplicant
,D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothAdapterService(746014054)( 1982): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1982): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1982): Setting state to 11
I/BluetoothAdapterState( 1982): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(746014054)( 1982): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  857): Message: 60
D/BluetoothManagerService(  857): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  857): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1801): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): processStart()
,D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/wpa_supplicant( 5501): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5501): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1369): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/BtSettings.ProfileConfig( 1982): Unable to read settings
D/BtSettings.ProfileConfig( 1982): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1982): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1982): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1982): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1982): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1982): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1982): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1982): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1982): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.pan.PanService
I/ActivityManager(  857): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5505 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/WifiMonitor(  857): startMonitoring(wlan0) with mConnected = false
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
I/WifiServerServiceExt(  857): WIFI_STATE_CHANGED_ACTION [2]
,W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(746014054)( 1982): processStart() - Make Bond State Machine
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothBondStateMachine( 1982): make
,D/BluetoothAdapterService( 1982): setAdapterService() - set to: null
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/LGBluetoothServiceAdapter( 1982): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 1982): StableState(): Entering Off State
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1982): Unable to read settings
D/BtSettings.ProfileConfig( 1982): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1982): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1982): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1982): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1982): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1982): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1982): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1982): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1982): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1982): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,D/HeadsetService( 1982): Received start request. Starting profile...
D/BluetoothHeadset(  857): Proxy object connected
D/BluetoothHeadset( 1745): Proxy object connected
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:14.708 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/LGBluetoothHeadsetServiceJni( 1982): classInitNative: succeeds
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
,D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/LGBluetoothFeatureConfig( 1982): isPrivacyLogsEnabled : true
,I/BluetoothHeadsetServiceJni( 1982): classInitNative: succeeds
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
D/CAR.SERVICE( 5363): mConnectedToCar = false, abort
D/HeadsetStateMachine( 1982): make
D/BluetoothHeadset( 1745): Proxy object connected
D/BluetoothHeadset( 1745): Proxy object connected
,D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
E/ActivityThread( 5363): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2e7e413 that was originally bound here
E/ActivityThread( 5363): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2e7e413 that was originally bound here
E/ActivityThread( 5363): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5363): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5363): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5363): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5363): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5363): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5363): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5363): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5363): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5363): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5363): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5363): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5363): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5363): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5363): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5363): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5363): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5363): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5363): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5363): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5363): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5363): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5363): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/HeadsetStateMachine( 1982): max_hf_connections = 1
I/bluedroid( 1982): get_profile_interface handsfree
I/bt-btif ( 1982): btif_hf_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): max_hf_clients = 1
D/bt-btif ( 1982): btif_max_hf_clients = 1
D/bt-btif ( 1982): btif_enable_service: current services:0xa0680330
V/ToneGenerator( 1982): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  281): registerClient() client 0xb4027240, uid 1002
,V/AudioPolicyManager(  281): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  281): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  281): getOutput() returns output 2
V/AudioFlinger(  281): registerClient() client 0xb40330d0, pid 1982
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): thread 0xb56eb000 type 0 TID 1294 waking up
V/AudioFlinger(  281): thread 0xb5651000 type 0 TID 1293 waking up
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  857): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  857): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2636): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2636): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 2636): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2636): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  857): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  857): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): thread 0xb5735000 type 0 TID 1296 waking up
V/AudioSystem( 1982): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 1982): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1982): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1982): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1982): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/ToneGenerator( 1982): Create Track: 0xb4908a80
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 2
E/ActivityThread( 5363): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3516005a that was originally bound here
E/ActivityThread( 5363): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3516005a that was originally bound here
E/ActivityThread( 5363): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5363): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5363): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5363): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5363): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5363): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5363): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5363): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5363): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5363): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5363): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5363): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5363): 	at android.app.ActivityThread.handleBind,Service(ActivityThread.java:2847)
E/ActivityThread( 5363): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5363): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5363): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5363): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5363): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5363): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5363): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5363): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5363): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 1982): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1982): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 4
I/AudioFlinger(  281): isAudioPlaybackHookOn() false
D/AudioTrack( 1982): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  281): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  281): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  281): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  281): getOutput() returns output 2
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3095): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3095): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3095): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3095): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1932): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1932): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1932): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1932): ioConfigChanged() opening already existing output! 4
W/ActivityManager(  857): Unbind failed: could not find connection for android.os.BinderProxy@321a5a6e
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1932): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1932): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1982): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1982): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 2636): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2636): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  857): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  857): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3095): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3095): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1982): getLatency() output 2, latency 50
V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1982): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1982): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1982): Create normal PCM 0x1 Track
V/AudioFlinger(  281): createTrack() lSessionId: 22
V/AudioFlinger(  281): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1982): Flags here  0x4 
V/AudioTrack( 1982): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  281): acquiring 22 from 1982, for 1982
V/AudioFlinger(  281):  added new entry for 22
V/ToneGenerator( 1982): ToneGenerator INIT OK, time: 99290
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/HeadsetStateMachine( 1982): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1982): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1982): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1982): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5651000
V/AudioFlinger(  281): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1982
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/audio_hw_primary(  281): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  281): voice_set_parameters: enter: bt_samplerate=8000
D/A2dpService( 1982): Received start request. Starting profile...
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
I/BluetoothAvrcpServiceJni( 1982): classInitNative: succeeds
D/BluetoothA2dp(  857): Proxy object connected
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  281): platform_set_parameters: enter: bt_samplerate=8000
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.sap.SapService
V/Avrcp   ( 1982): make
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
D/Avrcp   ( 1982): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1982): get_profile_interface avrcp
I/bt-btif ( 1982): btif_rc_get_interface
I/bt-btif ( 1982): ## init ##
I/LGBluetoothAvrcpServiceJni( 1982): classInitNative: succeeds
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
I/LGBluetoothAvrcpAdapter( 1982): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,I/LGBluetoothAvrcpServiceJni( 1982): initNative: succeeds
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
I/BluetoothAvrcpBrcmAdapterJni( 1982): classInitBrcmNative
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1982): ToneGenerator destructor
V/ToneGenerator( 1982): stopTone
V/ToneGenerator( 1982): Delete Track: 0xb4908a80
V/AudioTrack( 1982): ~AudioTrack, releasing session id from 1982 on behalf of 1982
V/AudioFlinger(  281): releasing 22 from 1982 for 1982
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): remove track (4099) and delete from mixer
V/AudioPolicyService(  281): AudioCommandThread() adding release output 2
V/AudioPolicyService(  281): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  281): releaseOutput() 2
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioFlinger(  281): PlaybackThread::Track destructor
V/AudioFlinger(  281): removeClient_l() pid 1982, calling pid 281
I/BluetoothAvrcpBrcmAdapterJni( 1982): initBrcmNative
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(746014054)( 1982): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/LGMDMManager( 1982): Create singleton instance
,I/BluetoothAdapterState( 1982): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/ActivityManager(  857): Process com.lge.qremote (pid 5020) has died
,D/UEI.SmartControl( 4660): Service.onUnbind: IControl
V/AudioService(  857): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  857): No RCC entry present to update
D/UEI.SmartControl( 4660): Service.onDestroy
D/UEI.SmartControl( 4660): Shutdown IRRCPlayer... 
W/irrc_jni( 4660): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4660): ~IrrcClient ++ 
D/irrcClient( 4660): ~IrrcClient -- 
W/irrc_jni( 4660): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4660): Blaster closed
D/UEI.SmartControl( 4660): Blaster closed
D/UEI.SmartControl( 4660): Shut down QS...
D/UEI.SmartControl( 4660): Stopped file observer...
E/RemoteController( 1982): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1982): classInitNative
I/BluetoothA2dpServiceJni( 1982): classInitNative: succeeds
D/A2dpStateMachine( 1982): make
,I/UEI.SmartControl( 4660): QS lib stop result = true
D/UEI.SmartControl( 4660): QS shutdown complete
I/bluedroid( 1982): get_profile_interface a2dp
I/bt-btif ( 1982): btif_av_get_src_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0680330
I/LGBluetoothA2dpServiceJni( 1982): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1982): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1982): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1982): [BTUI] init
D/LGBluetoothPowerControlManager( 1982): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  857): Message: 30
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
,D/A2dpStateMachine( 1982): Enter Disconnected: -2
I/BluetoothHidServiceJni( 1982): classInitNative: succeeds
D/HidService( 1982): Received start request. Starting profile...
I/bluedroid( 1982): get_profile_interface hidhost
I/bt-btif ( 1982): btif_hh_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0680330
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
I/BluetoothHealthServiceJni( 1982): classInitNative: succeeds
D/HealthService( 1982): Received start request. Starting profile...
I/bluedroid( 1982): get_profile_interface health
I/bt-btif ( 1982): btif_hl_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): Process name (droid.bluetooth)
D/bt-btif ( 1982): btif_hl_soc_thread_init
D/bt-btif ( 1982): create_thread: entered
D/bt-btif ( 1982): create_thread: thread created successfully
D/bt-btif ( 1982): entered btif_hl_select_thread
D/bt-btif ( 1982): btif_hl_select_wakeup_init
D/bt-btif ( 1982): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1982): max_s=55 
D/bt-btif ( 1982): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1982): classInitNative: succeeds
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
I/BluetoothPanServiceJni( 1982): classInitNative(L105): succeeds
,D/PanService( 1982): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1982): initializeNative(L110): pan
I/bluedroid( 1982): get_profile_interface pan
D/bt-btif ( 1982): stack_initialized = 0, btpan_cb.enabled:0
,I/LGBluetoothPanAdapter( 1982): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
I/BtGatt.JNI( 1982): classInitNative(L901): classInitNative: Success!
,D/BtGatt.DebugUtils( 1982): handleDebugAction() action=null
D/BtGatt.GattService( 1982): Received start request. Starting profile...
D/BtGatt.GattService( 1982): start()
I/bluedroid( 1982): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1982): advertise manager created
I/LGBluetoothGattAdapter( 1982): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1982): setGattService:  set to: null
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
,I/LGBluetoothMapAdapter( 1982): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1982): BluetoothMapBinder()
D/BluetoothMapService( 1982): Received start request. Starting profile...
D/BluetoothMapService( 1982): start()
D/BluetoothMapEmailSettingsLoader( 1982): Found 0 applications
D/BluetoothMapEmailAppObserver( 1982): createReceiver()
D/BluetoothMapEmailAppObserver( 1982): initObservers()
,D/BluetoothMapEmailAppObserver( 1982): getEnabledAccountItems()
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/HeadsetStateMachine( 1982): Proxy object connected
D/LGBluetoothHfpAdapter( 1982): [BTUI] queryPhoneState
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 1982): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/HeadsetStateMachine( 1982): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
,I/BluetoothSAPServiceJni( 1982): classInitNative(L170): succeeds
D/SapService( 1982): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1982): initializeNative(L175): sap
I/bluedroid( 1982): get_profile_interface sap
I/bt-btif ( 1982): btif_sc_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0680330
I/LGBluetoothSapAdapter( 1982): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1982): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1982): [BTUI] initSapManager
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
,V/BluetoothFTPServiceJni( 1982): classInitNative
I/BluetoothFTPServiceJni( 1982): classInitNative(L271): succeeds
,D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/BluetoothFTPService( 1982): BluetoothFtpBinder()
D/**BluetoothFTPService( 1982): Received start request. Starting profile...
V/BluetoothFTPService( 1982): FTP-Server Service start
D/BluetoothFTPServiceJni( 1982): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1982): get_profile_interface ftp
I/bt-btif ( 1982): btif_fts_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0680330
D/BluetoothFTPServiceJni( 1982): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/LGBluetoothFeatureConfig( 1982): isPrivacyLogsEnabled : true
W/ResourcesManager( 5505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/BluetoothOPPServiceJni( 1982): classInitNative
W/ResourcesManager( 5505): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5505): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/BluetoothOPPServiceJni( 1982): classInitNative(L373): succeeds
V/OppService( 1982): Opp initBinder
W/ResourcesManager( 5505): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5505): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/**OppService( 1982): Received start request. Starting profile...
,D/OppService( 1982): Starting OppService 
D/LGBluetoothOppAdapter( 1982): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1982): com.android.bluetooth: cancelAll by com.android.bluetooth
,D/LgeBluetoothSimManager( 1745): [BTUI] SAP_ENABLE_EVT
V/BluetoothOppNotification( 1982): send message
V/OppService( 1982): Deleted complete outbound shares, number =  0
,V/OppService( 1982): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1982): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@3516005a on behalf of 
D/BluetoothOppPreference( 1982): Dumping Names:  
D/BluetoothOppPreference( 1982): {}
D/BluetoothOppPreference( 1982): Dumping Channels:  
,D/BluetoothOppPreference( 1982): {}
D/OppService( 1982): Start()
W/BluetoothOPPServiceJni( 1982): initOppNative
D/BluetoothOPPServiceJni( 1982): initOppNative(L383): OPP
I/bluedroid( 1982): get_profile_interface opp
I/bt-btif ( 1982): btif_op_get_interface
D/BluetoothOPPServiceJni( 1982): initOppNative(L411): mOppCallbacksObj 2098434
D/BluetoothOPPServiceJni( 1982): initOppNative(L413): calling OPP init
I/bt-btif ( 1982): btif_opp_init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0680330
D/BluetoothOPPServiceJni( 1982): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1982): initOppNative(L430): mOppCallbacksObj 2098434
V/OppService( 1982): setOppService(): set to: com.broadcom.bt.service.opp.OppService@2e15c28b
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/BluetoothA2dp( 1982): Proxy object connected
D/LGBluetoothPowerControlManager( 1982): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@30c5f68
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1982): pendingUpdate is :  true
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@3c67f81 on behalf of 
V/BluetoothOppNotification( 1982): update too frequent, put in queue
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1982): pendingUpdate is :  false
E/OppService( 1982): UpdateThread is Completed
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1982): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
I/IndexDatabaseHelper( 5505): Using schema version: 115
I/IndexDatabaseHelper( 5505): Index is fine
,D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1982): Handler(): got msg=1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1982): new notify threadi!
V/BluetoothOppNotification( 1982): send delay message
V/OppService( 1982): ContentObserver received notification
V/OppService( 1982): ContentObserver received notification
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(746014054)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(746014054)( 1982): onProfileServiceStateChange() - All profile services started.
,D/BluetoothAdapterState( 1982): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1982): enable
I/bt-btif ( 1982): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1982): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 1982): pendingUpdate is :  true
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
I/GKI_LINUX( 1982): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1982): btu_task pending for preload complete event
I/bt_hci_bdroid( 1982): init
I/bt_vendor( 1982): init
I/bt_vnd_conf( 1982): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@3523c826 on behalf of 
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@3a9bfc67 on behalf of 
I/bt_vnd_conf( 1982): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
V/BluetoothOppNotification( 1982): mUpdateCompleteNotification = true
V/OppService( 1982): pendingUpdate is :  false
E/OppService( 1982): UpdateThread is Completed
I/bt-btif ( 1982): libbt-hci init returns 0
,V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@19fc0a14 on behalf of 
V/BluetoothOppNotification( 1982): outbound: succ-0  fail-0
I/NotificationManager( 1982): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1982): outbound notification was removed.
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@3ada92bd on behalf of 
V/BluetoothOppNotification( 1982): inbound: succ-0  fail-0
I/NotificationManager( 1982): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1982): inbound notification was removed.
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@22f440b2 on behalf of 
I/bt_userial_vendor( 1982): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 1982): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1982): device fd = 68 open
D/bt_hwcfg( 1982): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1982): hw_config_cback state=1
,V/BluetoothPbapReceiver( 1982): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1982): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1982): ***********state = 11
D/bt_hwcfg( 1982): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1982): hw_config_cback state=4
D/bt_hwcfg( 1982): Chipset Name: BCM4334B0
D/bt_hwcfg( 1982): Chipset BCM4334B0
D/bt_hwcfg( 1982): Target name = [BCM4334B0]
I/bt_hwcfg( 1982): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1982): hw_config_cback state=2
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1982): hw_config_cback state=3
I/bt_hwcfg( 1982): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1982): hw_config_cback state=5
D/WiFiOffLoadUpdatePriority( 5505): remove : truetruefalse
D/WiFiOffLoadUpdatePriority( 5505): remove2
V/WiFiOffLoadSharedPrefsUtils( 5505): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5505): save remove
D/WiFiOffLoadBroadcast( 5505): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5505): S: false, R: true
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/ActivityManager(  857): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5554 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/BluetoothPermissionRequest( 5505): onReceive
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/Tethering(  857): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LGBluetoothFeatureConfig( 5505):  get() - isFeatureLoaded : false
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@390728f5:true
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
V/BluetoothSapReceiver( 1982): [BTUI] checkServiceStart
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 1982): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
E/wpa_supplicant( 5501): USIM:  scard_init function
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/wpa_supplicant( 5501): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 9
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/ActivityManager(  857): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5573 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/PCSuite ( 5554): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/UsbSettingsReceiver( 5505): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5505): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5505): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5505): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/UsbSettingsReceiver( 5505): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/wpa_supplicant( 5501): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/wpa_supplicant( 5501): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/UsbSettingsControl( 5505): [AUTORUN] getUsbConnected() : connected=true
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/UsbSettingsReceiver( 5505): [AUTORUN] onReceive() : availableList=[wlan0]
D/bt_hwcfg( 1982): hw_config_cback state=6
D/UsbSettingsReceiver( 5505): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5505): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5505): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WifiStateMachine(  857): MAC Addr from driver = a0:39:f7:70:12:80
D/UsbSettingsReceiver( 5505): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/UsbSettingsControl( 5505): [AUTORUN] setTetherStatus() : status=false
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  857): setPowerSaveActivated(false)
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/ActivityManager(  857): Killing 4854:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
W/ResourcesManager( 5573): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5573): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1982): hw_config_cback state=6
I/ActivityManager(  857): Killing 4660:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/bt_hwcfg( 1982): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1982): Settlement delay -- 100 ms
,I/bt_hwcfg( 1982): Setting fw settlement delay to 100 
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1982): hw_config_cback state=2
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1982): hw_config_cback state=7
I/bt_hwcfg( 1982): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1982): Setting local bd addr to F8:95:C7:87:85:54
W/libprocessgroup(  857): failed to open /acct/uid_10086/pid_4854/cgroup.procs: No such file or directory
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1982): hw_config_cback state=8
I/bt_hwcfg( 1982): vendor lib fwcfg completed
I/bt-btif ( 1982): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1982): btu_task received preload complete event
D/AuthorizationBluetoothService( 1729): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.07 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
W/libprocessgroup(  857): failed to open /acct/uid_10089/pid_4660/cgroup.procs: No such file or directory
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,I/WifiServerServiceExt(  857): WIFI_STATE_CHANGED_ACTION [3]
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/        ( 1982): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1982): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1982): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1982): BTE_InitTraceLevels -- TRC_PROTOCOL,0
D/WiFiOffLoadUpdatePriority( 5505): remove : truetruetrue
I/WifiServerServiceExt(  857): batteryPsActivateMsgHandler : state:0 event:3
E/WifiServerServiceExt(  857): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
E/WifiConfigStore(  857): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiStateMachine(  857): enableVerboseLogging : level 2
D/WifiStateMachine(  857): Setting OUI to DA-A1-19
D/WifiNative-HAL(  857): Setting external_sim to 1
I/WifiNative-HAL(  857): startHal
E/wifi    (  857): getStaticLongField sWifiHalHandle 0x9b5578ec
I/WifiHAL (  857): Initializing wifi
D/WfdsService( 1801): Supplicant Connection state is changed : true
D/WfdsService( 1801): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1801): Set the WFDS Monitor: true
I/WifiHAL (  857): Creating socket
,D/WfdsMonitor( 1801): WfdsMonitorThread create
D/WfdsMonitor( 1801): WFDS Monitor is created and started
D/WfdsService( 1801): WiFi: Supplicant connection re-established
I/WifiHAL (  857): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  857): Did set static halHandle = 0xb4983f40
D/wifi    (  857): halHandle = 0xb4983f40, mVM = 0xb487c280, mCls = 0x601bae
E/wifi    (  857): getStaticLongField sWifiHalHandle 0x9b55789c
D/wifi    (  857): array field set
I/WifiNative-HAL(  857): interface[0] = wlan0
I/WifiNative-HAL(  857): interface[1] = p2p0
E/CtrlSupplicant( 1801): Access OK "@android:wpa_wlan0"
D/wifi    (  857): setting scan oui 0x9a4869b8
D/WifiHAL (  857): Sending mac address OUI
E/WifiHAL (  857): failed to set scanning mac OUI; result = -95
E/CtrlSupplicant( 1801): Succeed to open control connection
D/WifiStateMachine(  857): Setting OUI to DA-A1-19
I/WifiNative-HAL(  857): startHal
D/wifi    (  857): setting scan oui 0x9a4869b8
D/WifiHAL (  857): Sending mac address OUI
E/CtrlSupplicant( 1801): Succeed to open monitor connection
E/WifiHAL (  857): failed to set scanning mac OUI; result = -95
D/WfdsMonitor( 1801): Supplicant connection established
D/WfdsService( 1801): Connected to the supplicant for wfds
I/WifiNative-HAL(  857): Waiting for HAL events mWifiHalHandle=-1265090752
D/wifi    (  857): waitForHalEvents called, vm = 0xb487c280, obj = 0x601bae, env = 0xaaf0d120
E/wifi    (  857): getStaticLongField sWifiHalHandle 0x97b8ab2c
W/Settings( 4559): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/WifiHS20(  857): hidePasspointNotification off =false
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.132 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/WifiScanningService(  857): SCAN_AVAILABLE : 3
D/RttService(  857): SCAN_AVAILABLE : 3
,D/RttService(  857): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  857): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  857): startHal
D/LGWifiP2pService(  857): P2pDisabledState{ when=-5ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  857): getting scan capabilities on interface[0] = 0x9a4869b8
D/WifiHAL (  857): Creating message to get scan capablities; iface = 24
D/wifi    (  857): failed to get capabilities : -95
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/WifiScanningService(  857): could not get scan capabilities
D/CommandListener(  276): Setting iface cfg
D/CommandListener(  276): Trying to bring up p2p0
I/WifiServerServiceExt(  857): set CMD_ADD_DEFAULT_PROFILE
D/WifiMonitor(  857): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  857): P2pEnablingState
D/LGWifiP2pService(  857): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2p socket connection successful
D/LGWifiP2pService(  857): P2pEnabledState
I/WifiServerServiceExt(  857): setWifiDualbandAPConnection band : 1
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
E/wpa_supplicant( 5501): nWIFIDualbandAPConnection: 1
,D/LGWifiP2pService(  857): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  857): before postfix = G3s-1
D/WifiServerServiceExt(  857): postfix byte check : 5
D/LGWifiP2pService(  857): after postfix = G3s-1
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/WifiServerServiceExt(  857): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5501): disconnect_rssi_lvl: -100
I/WifiServerServiceExt(  857): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5501): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
I/WifiServerServiceExt(  857): set CMD_UPDATE_DEFAULT_PROFILE
I/wpa_supplicant( 5501): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/wpa_supplicant( 5501): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiNative-HAL(  857): p2pGetDeviceAddress
,E/bt-btif ( 1982): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
D/WifiNative-HAL(  857): p2pGetDeviceAddress returning a2:39:f7:70:12:80
I/GKI_LINUX( 1982): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1982): warning : media task started media_task_refcnt 1 
D/BT_PROF_AUDIO( 1982): created moving average (N=100)
W/bt-smp  ( 1982): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
D/BT_PROF_AUDIO( 1982): reset rate average
W/bt-btif ( 1982): Plain text, enter 0, exit 0
W/bt-smp  ( 1982): Plain text(LSB ~ MSB) = f1 dd 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1982): Encrypted text(LSB ~ MSB) = 22 3c 86 74 aa c6 53 87 e5 3f 72 f9 ae 39 fa 49 
W/bt-btm  ( 1982): Stopping oneshot timer
E/bt-btif ( 1982): Calling BTA_HhEnable
E/bt-btif ( 1982): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1982): Address is:F8:95:C7:87:85:54
D/WfdsService( 1801): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/BluetoothAdapterProperties( 1982): Name is: G3s-1
D/BluetoothManagerService(  857): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  857): Stored Bluetooth name: G3s-1
D/LGWifiP2pService(  857): DeviceAddress: a2:39:f7:70:12:80
D/BluetoothAdapterProperties( 1982): Scan Mode:20
D/BluetoothAdapterProperties( 1982): Discoverable Timeout:120
E/bt-btif ( 1982): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1982): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1982): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1982): BTA_JvEnable
E/bt-btif ( 1982): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1982): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1982): init_hci_slots(L136): in
D/IOP_DB_BT( 1982): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1982): db_open: db_open : handle 2691213276l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1982): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1982): db_query: result 1
I/        ( 1982): iop_db_open: iop_db_open status 0
E/bt-btif ( 1982): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1982): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1982): bta_pan_co_init
D/bte_conf( 1982): Device ID record 1 : primary
D/bte_conf( 1982):   vendorId            = 00c4
D/bte_conf( 1982):   vendorIdSource      = 0001
D/bte_conf( 1982):   product             = 13a1
D/bte_conf( 1982):   version             = 1000
D/bte_conf( 1982):   clientExecutableURL = 
D/bte_conf( 1982):   serviceDescription  = 
D/bte_conf( 1982):   documentationURL    = 
D/bte_conf( 1982): bte_load_did_conf no section named DID2.
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 1982): btif_hf_upstreams_evt: wrong handle = 12346 
I/bt-btif ( 1982): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1982): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterState( 1982): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1982): ScanMode =  20
D/BluetoothAdapterProperties( 1982): State =  11
D/BluetoothAdapterProperties( 1982): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1982): Setting state to 12
I/BluetoothAdapterState( 1982): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(746014054)( 1982): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  857): Message: 60
D/BluetoothManagerService(  857): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  857): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/OppService( 1982): onOpcStateChange()
I/bt-btif ( 1982): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1982): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 1982): onOpsStateChange() :0
I/bt-btif ( 1982): HAL bt_fts_callbacks->operation_cmpl_cb
D/Bluetoo,thFTPServiceJni( 1982): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1982): onFtpServerEnabled: /storage
D/BluetoothPanServiceJni( 1982): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_properties_cb
D/OppService( 1982): Recieved MESSAGE_OPC_ENABLE
D/LGBluetoothFeatureConfig( 1982): isPrivacyLogsEnabled : true
I/BluetoothAdapterState( 1982): Entering On State
I/BluetoothAdapterState( 1982): Entering On State from state = 11
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/BluetoothA2dp( 1982): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothAdapterService(746014054)( 1982): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(746014054)( 1982): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1982): [BTUI] autoConnect() : not allowed
D/OppService( 1982): Recieved MESSAGE_OPS_ENABLE
D/BluetoothAdapterProperties( 1982): Scan Mode:21
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1982): Discoverable Timeout:120
D/BluetoothHeadset(  857): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
D/BluetoothA2dp(  857): onBluetoothStateChange: up=true
E/BluetoothManagerService(  857): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  857): Bluetooth State Change Intent: 11 -> 12
D/WfdsService( 1801): Update P2p Interface State: 3
D/LGBluetoothServiceAdapter( 1982): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1982): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1982): [BTUI]         local_name: G3s-1
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothAdapterService(746014054)( 1982): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(746014054)( 1982): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1982): [BTUI] autoConnect() : not allowed
D/LGBluetoothAPIService( 1801): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothManagerService(  857): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  857): Message: 40
D/BluetoothManagerService(  857): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/BluetoothMapService( 1982): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1982): STATE_ON
V/BluetoothMapService( 1982): Handler(): got msg=1
D/BluetoothMapMasInstance( 1982): Map Service startRfcommSocketListener
D/bt_h4   ( 1982): vendor lib postload completed
D/LGBluetoothAPIService( 1801): Message: 1
D/BluetoothMapMasInstance( 1982): MAS initSocket()
D/BluetoothMapMasInstance( 1982):   masId = 00
D/BluetoothMapMasInstance( 1982):   msgTypes = 0e
D/BluetoothMapMasInstance( 1982):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1982):   SDP string = 000eSMS/MMS
I/wpa_supplicant( 5501): wlan0: Associated with c0:ff:d4:d3:aa:48
D/LGBluetoothAPIService( 1801): MESSAGE_BOOT_COMPLETED
D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/LGBluetoothAPIService( 1801): [BTUI] LGBluetoothAPIService Binding Success
,D/LGWifiP2pService(  857): sending p2p persistent groups changed broadcast
I/wpa_supplicant( 5501): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5501): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c774566
D/LGWifiP2pService(  857): sending p2p connection changed broadcast
V/BluetoothPbapService( 1982): Pbap Service onCreate
V/BluetoothPbapService( 1982): Starting PBAP service
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1369): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/BluetoothAdapter( 1982): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothPbapAdapter( 1982): [BTUI] getInstance : create
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.3 DNS addrs= 0.0.0.0, 0.0.0.0, 
V/BluetoothOppNotification( 1982): new notify threadi!
V/BluetoothOppNotification( 1982): send delay message
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
V/BluetoothPbapService( 1982): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1982): state: 12
,D/WfdsService( 1801): WifiP2pState is changed : true
D/WfdsService( 1801): Receive the WFDS_ENABLE Method
D/WfdsService( 1801): Set the WFDS Monitor: true
D/WfdsService( 1801): Connected to the supplicant for wfds
D/WfdsJNI ( 1801): doCommand: WFDS_SET TRUE
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LGBluetoothAPIServer( 1982): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1982): [BTUI] onBind()
D/LGWifiP2pService(  857): InactiveState
D/LGWifiP2pService(  857): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/LGWifiP2pService(  857): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/LGWifiP2pService(  857): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
V/BluetoothPbapService( 1982): Handler(): got msg=1
D/LGBluetoothServiceAdapter( 1982): [BTUI] createSocketChannel FD=83 mFd=0
D/WfdsService( 1801): WIFI_P2P_CONNECTION_CHANGED_ACTION
V/BluetoothMapMasInstance( 1982): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1982): Accepting socket connection...
I/wpa_supplicant( 5501): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
V/BluetoothPbapService( 1982): Pbap Service startRfcommSocketListener
D/WfdsJNI ( 1801): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5501): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1801): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5501): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1801): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1801): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
E/WifiServerServiceExt(  857): No p2p device connected
D/WfdsService( 1801): selectPreferredScanChannel [6]
D/WfdsService( 1801): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
D/WiFiOffLoadUpdatePriority( 5505): remove1
V/WiFiOffLoadSharedPrefsUtils( 5505): save remove
,D/WfdsService( 1801): isConnected: false
D/LGBluetoothAPIService( 1801): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LocSvc_java(  857): onReceive
D/LGBluetoothAPIService( 1801): Message: 100
D/LGBluetoothAPIService( 1801): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.322 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  857): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LGWifiP2pService(  857): InactiveState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): DefaultState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothPbapService( 1982): Pbap Service initSocket
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.328 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WfdsService( 1801): GroupInfoAvailable: mGroupInfo is null
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.333 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/WfdsService( 1801): DefaultState - msg [9441285] is not handled
D/GONS    ( 1745): GONS isTestMode: false Country: 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,D/WiFiOffLoadBroadcast( 5505): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5505): S: false, R: false
I/WifiServiceExtension(  857): setVHTCapabilityType  : false
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.343 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 1982): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
D/LGBluetoothServiceAdapter( 1982): [BTUI] createSocketChannel FD=85 mFd=83
I/bt-btif ( 1982): BTA_JvRfcommStartServer
V/BluetoothPbapService( 1982): Succeed to create listening socket 
V/BluetoothPbapService( 1982): Accepting socket connection...
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@14229db9 on behalf of 
V/BluetoothOppNotification( 1982): mUpdateCompleteNotification = true
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@14e1b5fe on behalf of 
V/BluetoothOppNotification( 1982): outbound: succ-0  fail-0
I/NotificationManager( 1982): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
I/WifiServerServiceExt(  857): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  857): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
V/BluetoothOppNotification( 1982): outbound notification was removed.
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
I/WifiServiceExtension(  857): setSecurityType  : 2
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@2a02115f on behalf of 
V/BluetoothOppNotification( 1982): inbound: succ-0  fail-0
,I/NotificationManager( 1982): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1982): inbound notification was removed.
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@12a687ac on behalf of 
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STAT,E_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.395 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.397 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/WifiExtManager(  857): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@44506e1
,D/ConnectivityService(  857): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  857): Got NetworkAgent Messenger
D/ConnectivityService(  857): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  857): NetworkAgent connected
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  857): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  857): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Setting iface cfg
D/DhcpStateMachine(  857): StoppedState
E/WifiStateMachine(  857): Start Dhcp Watchdog 1
D/DhcpStateMachine(  857): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  857): WaitBeforeStartState
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateSCANNING
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateASSOCIATED
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadUpdatePriority( 5505): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5505): connected SSID: null
,D/WiFiOffLoadUpdatePriority( 5505): private wpa: "NG700" 300
D/WifiServiceImplEx(  857): addOrUpdateNetwork pid=5505, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  857):  uid = 1000 SSID "NG700" nid=0
I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:16.482 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  857): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateCOMPLETED
E/WifiStateMachine(  857): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService(  857): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@206bcf24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@206bcf24 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  857): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  857): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  857): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  857): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  857): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateCOMPLETED
E/WifiConfigStore(  857):  key="NG700"WPA_PSK netId=0 uid=0/1000
E/WifiConfigStore(  857): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5505):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5505): configuration updated: 0
I/WifiServerServiceExt(  857): set CMD_UPDATE_DEFAULT_PROFILE
,D/WiFiOffLoadUpdatePriority( 5505): configuration saved: true
D/PCSuite ( 5554): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/ContextImpl( 5505): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager(  857): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5623 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,V/BluetoothPbapReceiver( 1982): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1982): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1982): ***********state = 12
,D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
,D/LocalBluetoothProfileManager( 5505): Adding local A2DP profile
D/BluetoothManagerService(  857): Message: 30
,D/LocalBluetoothProfileManager( 5505): Adding local HEADSET profile
D/BluetoothManagerService(  857): Message: 30
D/BluetoothManagerService(  857): Message: 30
D/DhcpStateMachine(  857): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  857): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  857): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/BluetoothManagerService(  857): Message: 30
D/LocalBluetoothProfileManager( 5505): Adding local MAP profile
,I/dhcpcd  ( 5639): version 5.5.6 starting
E/dhcpcd  ( 5639): get_duid: Read-only file system
D/BluetoothMap( 5505): Create BluetoothMap proxy object
D/BluetoothManagerService(  857): Message: 30
D/BluetoothManagerService(  857): Message: 30
,V/BluetoothPbapService( 1982): Pbap Service onBind
D/LocalBluetoothProfileManager( 5505): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 5505): [BTUI] initUserBindClient
W/ContextImpl( 5505): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DockEventReceiver( 5505): finishStartingService: stopping service
,D/BluetoothA2dp( 5505): Proxy object connected
D/A2dpProfile( 5505): Bluetooth service connected
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothHeadset( 5505): Proxy object connected
,D/HeadsetProfile( 5505): Bluetooth service connected
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothInputDevice( 5505): Proxy object connected
D/HidProfile( 5505): Bluetooth service connected
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
,D/BluetoothPan( 5505): BluetoothPAN Proxy object connected
I/dhcpcd  ( 5639): wlan0: rebinding lease of 192.168.1.134
D/PanProfile( 5505): Bluetooth service connected
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothMap( 5505): Proxy object connected
D/MapProfile( 5505): Bluetooth service connected
D/BluetoothMap( 5505): getConnectedDevices()
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
V/BluetoothMapService( 1982): getConnectedDevices()
,D/BluetoothPbap( 5505): Proxy object connected
D/PbapServerProfile( 5505): Bluetooth service connected
D/LGBluetoothUserBindClient( 5505): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5505): onReceive
D/LGBluetoothFeatureConfig( 5505): isPrivacyLogsEnabled : true
,D/LGBluetoothUtils( 5505): [BTUI] FileNotFound: readProperty
V/BluetoothOppReceiver( 1982): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
V/BluetoothOppManager( 1982): restoreApplicationData! falsefalsenullnull
,V/BluetoothSapReceiver( 1982): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 1982): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/AuthorizationBluetoothService( 1729): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LGDMClient( 5623): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 5623): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
D/LGDMClient( 5623): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5623): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 5554): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/LGDMClient( 5623): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/PCSuite ( 5554): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5554): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5664 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  857): Killing 5246:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10013/pid_5246/cgroup.procs: No such file or directory
,W/ResourcesManager( 5664): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29dcafee:true
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
,V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  857): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/ActivityManager(  857): Process com.google.android.talk (pid 4559) has died
I/ActivityManager(  857): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5690 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,V/[BNRBootReceiver]( 5690): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5690): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/AudioFlinger(  281): thread 0xb56eb000 type 0 TID 1294 going to sleep
V/AudioFlinger(  281): thread 0xb5651000 type 0 TID 1293 going to sleep
,V/AudioFlinger(  281): thread 0xb5735000 type 0 TID 1296 going to sleep
V/[BNRBootReceiver]( 5690): Boot Receiver Return
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 5505): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
I/dhcpcd  ( 5639): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5639): wlan0: leased 192.168.1.134 for 86400 seconds
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  857): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5714 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5664): Create singleton instance
,I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 328us total 42.597ms
I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 26.624ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 31.156ms
,D/UEI.SmartControl( 5714): Quickset Services start...
I/UEI.SmartControl( 5714): Manufacture = LGE
,D/UEI.SmartControl( 5714): File observer start...
E/UEI.SmartControl( 5714): IR Port is disabled: false
D/UEI.SmartControl( 5714): Starting file observer...
D/UEI.SmartControl( 5714): Extracting JNI libs...
D/UEI.SmartControl( 5714): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5664): getMode name:com.lge.qremote
D/UEI.SmartControl( 5714): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5714): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5714): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5714): --- Selecting new region: 2
I/UEI.SmartControl( 5714): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5714): Platform has CIR...
D/UEI.SmartControl( 5714): NO CIR support, need to check package...
I/UEI.SmartControl( 5714): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5714): QS Service created
E/UEI.SmartControl( 5714): QS start get config
,D/UEI.SmartControl( 5714): Loading JNI Libs...
,D/UEI.SmartControl( 5714):  configuring local db...
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  857): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  857): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  857): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  857): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  857): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  857): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  857): bShouldSendDhcpAction Result: true
D/LGWifiP2pService(  857): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  857): DHCP Start/Renew wake lock is released.
D/LGWifiP2pService(  857): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  857): RunningState
D/ConnectivityService(  857): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine(  857): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  857): ignoring duplicate network state non-change
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:18.416 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  857): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:18.421 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  857): Adding iface wlan0 to network 100
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/WifiHS20(  857): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:18.433 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
E/WifiStateMachine(  857): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20(  857): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:18.452 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
,E/ConnectivityService(  857): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  857): Adding Route [fe80::/64 -> :: wlan0] to network 100
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  857): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  857): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  857): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  857): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  857): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
D/Nat464Xlat(  857): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  857): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  857):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  857):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  857):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): Connected
D/ConnectivityService(  857): currentScore = 0, newScore = 20
D/ConnectivityService(  857):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  857): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  857): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  857):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  857): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/TelephonyNetworkFactory-1( 1745): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] Start DNSResolver start to wait
E/ConnectivityService(  857): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  857): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  857): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  857): MasterInitialState.processMessage what=3
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = 1
,D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService(  857): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  857): [e] list.add(nai) empty : false size: 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] wait 500ms before dns check
D/ConnectivityService(  857): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  857): validation of new default Network = false
D/ConnectivityService(  857): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  857): enableDataServiceNotify 
D/DSQN    (  857): start dsqn bin
,V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
V/NetworkPolicy(  857): [LG_RESTRICTED] checkMobilePolicy_type()
,I/PCSuite ( 5554): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5554): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5505): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5505): MCCMNC not supported: null
I/PCSuite ( 5554): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5554): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  857): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  857): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
I/DSQN    ( 5763): DSQN samuel.seo ver 141203
E/DSQN    ( 5763): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5763): created command queue thread
I/DSQN    ( 5763): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5763): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/UEI.SmartControl( 5714):  ---- Has DB8: true
,D/UEI.SmartControl( 5714): QS start statue = true Error code = 0
D/UEI.SmartControl( 5714): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5714): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5714): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5714): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5714): IrrcClient ++ 
D/irrcClient( 5714): getIrrcService ++ 
D/irrcClient( 5714): getIrrcService -- 
D/irrcClient( 5714): IrrcClient -- 
W/irrc_jni( 5714): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5714): Services init done
I/UEI.SmartControl( 5714): Device manager: loading config....
D/UEI.SmartControl( 5714): QS Service init finished
D/UEI.SmartControl( 5714): QS Service version name: 0.1.73
D/UEI.SmartControl( 5714): QS Service version code: 1073
,D/UEI.SmartControl( 5714): Service requested: Control
D/UEI.SmartControl( 5714): Config is loaded...
D/UEI.SmartControl( 5714):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5714): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5714): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5714): Internal service binding...
D/UEI.SmartControl( 5714): -----IControl: 11
D/UEI.SmartControl( 5714): Caller: com.lge.qremote
D/UEI.SmartControl( 5714): ------------ IControl registerCallback...
I/UEI.SmartControl( 5714): Registering callback...
D/UEI.SmartControl( 5714): -----IControl: 19
D/UEI.SmartControl( 5714): Caller: com.lge.qremote
I/UEI.SmartControl( 5714): Registering Services Ready callback...
I/UEI.SmartControl( 5714): Notify client services are ready...
D/UEI.SmartControl( 5714): -----IControl: 8
,D/UEI.SmartControl( 5714): Caller: com.lge.qremote
I/AudioManager( 5664): getMode name:com.lge.qremote
I/ActivityManager(  857): Killing 5322:com.google.process.gapps/u0a6 (adj 15): empty #11
I/ActivityManager(  857): Killing 5211:com.android.providers.calendar/u0a14 (adj 15): empty #12
,W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_5322/cgroup.procs: No such file or directory
,W/libprocessgroup(  857): failed to open /acct/uid_10014/pid_5211/cgroup.procs: No such file or directory
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] DNSResolver start dns
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out(  857): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): Checking http://clients3.google.com/generate_204 on "NG700"
I/AudioManager( 5664): getMode name:com.lge.qremote
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5763): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 5763): restart monitoring
I/DSQN    ( 5763): dsqn report finish
D/LGDataListener(  276): argv[0]=dsqncommand
D/LGDataListener(  276): argv[1]=wlan0
D/LGDataListener(  276): argv[2]=1
D/LGDataListener(  276): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  857): DSQM DsqnNotification wlan0  1
D/DSQN    (  857): start to monitor internet connection
I/AudioManager( 5664): getMode name:com.lge.qremote
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jan 2016 11:01:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452596479215], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452596479197]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): Validated
D/ConnectivityService(  857): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  857):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  857):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  857): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  857): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  857): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  857): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
D/WIFI    (  857): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  857):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  857): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiDataContinuityService(  857): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/TelephonyNetworkFactory-1( 1745): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  857): set CMD_CAPTIVE_CHECK_COMPLETED
,D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-12 12:01:19.493 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/WifiInternetCheck(  857): Single check msg out of sync, ignoring.
,D/ConnectivityService(  857): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  857): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  857): onReceive
D/LocSvc_java(  857): got connectivity action
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  857): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  857): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  857): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  857): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  857): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  857): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  857): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5804 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out(  857): propertyValue:false
I/System.out(  857): propertyValue:false
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocSvc_java(  857): NTP server returned: 1452596481459 (Tue Jan 12 12:01:21 GMT+01:00 2016) reference: 106091 certainty: 13 system time offset: -194
,D/LocSvc_java(  857): Sending msg: 10 arg1:0 arg2:1
D/AlarmManagerService(  857): Setting time of day to sec=1452596481
W/AlarmManagerService(  857): Unable to set rtc to 1452596481: Invalid argument
,D/NetworkChangeNotifierAutoDetect( 1932): Network connectivity changed, type is: 2
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.TIME_SET
D/WeatherService( 2602): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:1:21
,D/WeatherService( 2602): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2602): 2 : This is isUpdating : false
D/WeatherService( 2602): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2602): 2 : buildUpdate, appWidgetId: 2
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
D/WeatherTheme( 2602): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2602): 2 : Fixed theme : optimus
D/WeatherReflect( 2602): 2 : Map key string is -2
D/lim     ( 2602): 2 : time = 12:01
I/WeatherReflect( 2602): Model Name : LG-D722
D/WeatherTheme( 2602): 2 : exactly same view!
D/WeatherTheme( 2602): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2602): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:1:21
,D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ActivityManager(  857): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5832 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager(  857): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,I/[LGHome]LGDateChangeReceiver( 1874): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=12 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 1874): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 12
,I/ActivityManager(  857): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5853 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/ChimeraCfgMgr( 3921): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3921): Module APK com.google.android.play.games already loaded
,I/[LGHome]LGCalendarIcon( 1874): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 12
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  857): Process com.google.android.gms:car (pid 5363) has died
,D/GpsLocationProvider(  857): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
,I/art     (  857): Explicit concurrent mark sweep GC freed 75039(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 4.725ms total 299.349ms
,W/ResourcesManager( 5853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5853): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5832): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5832): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5853): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 5832): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/GamesSyncServiceMain( 3921): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 3921): Failed to execute periodic sync, missing client context - aborting
,I/ActivityManager(  857): Process com.android.vending (pid 4935) has died
,I/ActivityManager(  857): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5878 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/GpsLocationProvider(  857): No APN found to select.
I/AppConfig( 5853): Total System Memory = 906309632
,I/GalleryUtils( 5853): Application Heap = 96 MB
I/AppConfig( 5853): App Tier : NOT_DEF
D/SystemHelper( 5853): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  857): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5897 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LgeGpsConstants(  857): Can't find 'ext_gps.conf'!!
I/LGEmail ( 5832): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
,D/LGEmail ( 5832): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  857): propertyValue:false
,I/NotificationManager(  857): android: cancelAsUser(-1597574061) by android
,I/GservicesProvider( 5878): Gservices pushing to system: true; secure/global: true
,I/NotificationManager(  857): android: cancelAsUser(-1816247584) by android
D/LgeGpsLocationProvider(  857): NTP server: europe.pool.ntp.org
,D/LgeGpsLocationProvider(  857): NTP server returned: 1452596482375 (Tue Jan 12 12:01:22 GMT+01:00 2016) reference: 106996 certainty: 36 system time offset: 28
I/GoogleHttpClient( 5878): GMS http client unavailable, use old client
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/GoogleHttpClient( 5878): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5878): GMS http client unavailable, use old client
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  857): propertyValue:false
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  857): propertyValue:false
,V/WifiInternetCheck(  857): isHttpConnectionAvailable - We got a valid response : 204
,I/MusicStore( 5804): Database version: 120
,W/ResourcesManager( 5897): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5897): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  857): Process com.lge.settings.easy (pid 5573) has died
,E/ActivityThread( 3921): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  857): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 35731, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  857): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 139272, reason: UserStart
I/NotificationManager(  857): android: cancelAsUser(716319171) by android
I/PhenotypeConfigurator( 1729): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,V/JNIHelp ( 5897): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Auth.Api.Credentials( 3921): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  857): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5945 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
W/System  ( 5897): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5897): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager(  857): android: cancelAsUser(-591465577) by android
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5804): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/ActivityManager(  857): Process com.lge.lgdmsclient (pid 5623) has died
,D/ALBootInit( 5945): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 5945): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5945): [setNextAlert] start
,D/Alarms  ( 5945): [setNextAlert] (1)
,D/Alarms  ( 5945):  minTime  = 0
D/Alarms  ( 5945):  -- OK multi -- 0
E/jeny.kim( 5945): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5945): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 5945): BUILD Operator: OPEN
W/art     ( 5897): Suspending all threads took: 13.132ms
,D/Alarms  ( 5945): broadcastToWidgetProvider : false
D/Alarms  ( 5945): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,V/SettingsProvider(  857): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/art     ( 5897): CheckpointMarkThreadRoots callback created = 0xb042db50
W/ContextImpl( 5804): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/DigitalAppWidgetProvider( 5945): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 5945): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@17b7caa8
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5804): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/DigitalAppWidgetProvider( 5945): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@17b7caa8
D/QuickCoverProvider( 5945): onReceiver
,I/NotificationManager(  857): android: cancelAsUser(-1816247584) by android
E/YouTube MDX( 5897): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/art     ( 5897): CheckpointMarkThreadRoots callback created = 0xb4958de0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  857): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=5982 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 1729): propertyValue:false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,W/ResourcesManager( 5804): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5804): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5982): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,W/ResourcesManager( 5897): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5897): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/CalendarApplication( 5982): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5982): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 5982): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@261b3aaf, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@17d37ebc, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@17126e45, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3ed0299a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@326ad2cb, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@17b7caa8, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3ef0a9c1, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2c774566, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@18d1d0a7, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@712e954, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@111d20fd, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2a2251f2, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@38c0d043, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@5f46c0, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@289fcff9, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@10ff9b3e, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2e162d9f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@9520eec, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2f0472b5, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@cd62d4a, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@a3a04bb, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2bc72dd8, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@20d68531, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@cd1d416, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2fa3197, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@316d4f84, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1ddd436d, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@350f1ba2, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@33265033, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2e31dff0, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@117a969, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1ce74fee, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@8ebbc8f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@56d0b1c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3c787325, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@25fc7cfa, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3df192ab, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@15cdbd08, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@34621ca1, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@38056ec6, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3534ae87, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3805a1b4,
D/GeneralP,referenceUtils( 5982): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5982): [init]
,I/Config  ( 5982): LGCalendar ver.4.40.17
I/Config  ( 5982): start check model
I/Config  ( 5982): start check native_ca
I/NotificationManager(  857): android: cancelAsUser(-591465577) by android
I/Config  ( 5982): Config Operator=OPEN, Country=EU
D/Config  ( 5982): [setDefaultValuesToPref]
D/Config  ( 5982): [parseProfiles]
D/ProfilesParser( 5982): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5982): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5982): [updateProfiletoCountryInfo]
D/GeneralPreference( 5982): [checkAndMigrateOldPreference]
,V/JNIHelp ( 5804): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/AgendaWidgetManager( 5982): [updateWidgets] 
,I/InitNotificationRingtoneService( 5982): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5982): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5982): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/NotificationManager(  857): android: cancelAsUser(-1597574061) by android
,I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5982): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5982): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,W/HolidayIntentService( 5982): onHandleIntent
D/HolidayDataLoader( 5982): readJsonAsset : holiday.json
,D/MonthWidgetProvider( 5982): [onReceive]
D/CalendarWidgetProvider( 5982): [onReceive]
D/CalendarWidgetProvider( 5982): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/ActivityThread( 5804): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/CalendarTypeController( 5982): [onUpdateAndInitCalendarTime]
W/System  ( 5804): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1486cd57: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5804): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  857): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  857): dumpNetworkRequest
D/ConnectivityService(  857):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  857):     Requests:
D/ConnectivityService(  857):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  857):     Lingered:
D/ConnectivityService(  857): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857): apparently satisfied.  currentScore=60
D/ConnectivityService(  857): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 3921): CM callback handler got msg 524290
D/AndroidMusic( 5804): GMSCore installation verified
D/UEI.SmartControl( 5714): Internal timer expired: 1
,I/ActivityManager(  857): Process com.lge.bnr (pid 5690) has died
,I/AlertUtils( 5982): set default noti to content://media/internal/audio/media/38
D/WeekWidgetProvider( 5982): [onReceive]
D/CalendarWidgetProvider( 5982): [onReceive]
D/CalendarWidgetProvider( 5982): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/InitNotificationRingtoneService( 5982): End InitializeAlertRingtoneService.onHandleIntent
D/CalendarTypeController( 5982): [onUpdateAndInitCalendarTime]
,I/NotificationManager( 5897): com.google.android.youtube: cancel(2) by com.google.android.youtube
E/HolidayIntentService( 5982): onHandleIntent:holiday data empty
D/WeatherAncestor( 2602): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:1:23
,D/UpdateThreadPoolManager( 2602): 2 : This is isUpdating : false
I/ConfigStore( 5804): Config Database version: 1
D/Weather_cast( 2602): 2 : set auto-update time : 1/12 15:1
D/WeatherAncestor( 2602): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:1:23
D/WeatherService( 2602): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
I/dex2oat ( 6018): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-977161587.jar --oat-fd=41 --oat-location=/data/data/com.google.android.youtube/cache/ads-977161587.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  857): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6033 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2602): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2602): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2602): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/InstanceID/Rpc( 5897): Found 10006
,I/NotificationManager(  857): android: cancelAsUser(-1816247584) by android
,I/ActivityManager(  857): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6053 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dex2oat ( 6018): dex2oat took 199.788ms (threads: 4)
,I/art     (  857): Explicit concurrent mark sweep GC freed 33467(1558KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/34MB, paused 2.590ms total 201.262ms
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5897): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/TimeService( 6033): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452596484180
D/        ( 6033): TimeServiceNative: User Time to be set is 1452596484180
D/QC-time-services( 6033): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6033): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6033): Lib:time_genoff_operation: pargs->ts_val = 1452596484180
D/QC-time-services( 6033): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  340): Daemon: Connection accepted:time_genoff
D/QC-time-services(  340): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452596484180
D/QC-time-services(  340): Daemon:genoff_opr: Base = 2, val = 1452596484180, operation = 0
D/QC-time-services(  340): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/25/70 15:3:1
D/QC-time-services(  340): Daemon:Value read from RTC seconds = 12495781000
D/QC-time-services(  340): Daemon:new time 1452596484180 
D/QC-time-services(  340): Daemon: delta 1440100703180 genoff 1440100703180 
D/QC-time-services(  340): Daemon:genoff_persistent_update: Writing genoff = 1440100703180 to memory
D/QC-time-services(  340): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  340): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  340): Updating the TOD offset
D/QC-time-services(  340): Daemon:genoff_persistent_update: Writing genoff = 1440100703180 to memory
D/QC-time-services(  340): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  340): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  340): Daemon:Update to modem bit set
D/QC-time-services(  340): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  340): Daemon: Base = 2, Value being sent to MODEM = 1124135903180
E/QC-time-services( 6033): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  340): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  340): Daemon: Time-services: Waiting to acceptconnection
I/CheckinService( 3921): Checkin interval check for package: unspecified last checkin: 1452528234042 min interval config: 0 actual interval: 68250182
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  276): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 5897): propertyValue:false
D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/MediaRouter( 5804): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5804): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5804): type=WIFI subType= reason=null isConnected=true
,W/PhenotypeConfigurator( 1729): Server returned 404
,W/DriveInitializer( 3921): Awaiting to be initialized
,I/art     ( 5878): Explicit concurrent mark sweep GC freed 8022(406KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.325ms total 58.058ms
W/DriveInitializer( 3921): Background init thread started
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3921): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,I/NotificationManager(  857): android: cancelAsUser(-1548111331) by android
I/Gmail   ( 6053): getAccountsCursor
I/NetworkMonitor( 5804): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  857): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6122 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  857): RTC_WAKEUP set : Alarm{359e43fb type 0 when 1452596484663 com.android.vending} when 1452596484663
,W/DriveInitializer( 3921): Background init thread ended
D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  857): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6134 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 317us total 23.059ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.608ms
,I/NotificationManager( 5897): com.google.android.youtube: cancel(10436) by com.google.android.youtube
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.832ms
,I/ActivityManager(  857): Process com.android.settings (pid 5505) has died
,W/ActivityManager(  857): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/eas_req ( 5832): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/GAV2    ( 6053): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/GHttpClientFactory( 5804): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/Gmail   ( 6053): Observing account changes for notifications
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/GoogleURLConnFactory( 5804): Using platform SSLCertificateSocketFactory
,I/NotificationManager(  857): android: cancelAsUser(353845882) by android
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   ( 6053): Sync started for account: account:61035162
,I/ActivityManager(  857): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6172 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/Gmail   ( 6053): Error finding the version of the Email provider.....
E/Gmail   ( 6053): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6053): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6053): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6053): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6053): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6053): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6053): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6053): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6053): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6053): getAccountsCursor
I/HubEmail( 5832): JNI_OnLoad()
I/HubEmail( 5832): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5832): registerNatives()
,I/HubEmail( 5832): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5832): registerNativeMethods()
I/HubEmail( 5832): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5832): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  857): Process com.lge.qremote (pid 5664) has died
,D/UEI.SmartControl( 5714): Service.onUnbind: IControl
D/UEI.SmartControl( 5714): Service.onDestroy
D/UEI.SmartControl( 5714): Shutdown IRRCPlayer... 
E/lowmemorykiller(  242): Error writing /proc/5945/oom_score_adj; errno=22
,E/lowmemorykiller(  242): Error writing /proc/5945/oom_score_adj; errno=22
I/PhoneApp( 1745): onTrimMemory: 10
I/PhoneApp( 1745): trim memory
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 5832): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/irrc_jni( 5714): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5714): ~IrrcClient ++ 
D/irrcClient( 5714): ~IrrcClient -- 
W/irrc_jni( 5714): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5714): Blaster closed
D/UEI.SmartControl( 5714): Blaster closed
D/UEI.SmartControl( 5714): Shut down QS...
D/UEI.SmartControl( 5714): Stopped file observer...
I/BackgroundMemoryTrimmer( 1932): Trimming objects from memory, since app is in the background.
I/UEI.SmartControl( 5714): QS lib stop result = true
,D/UEI.SmartControl( 5714): QS shutdown complete
E/lowmemorykiller(  242): Error writing /proc/5945/oom_score_adj; errno=22
I/ActivityManager(  857): Process com.lge.clock (pid 5945) has died
,D/LGDMClient( 6172): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6172): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/NotificationManager( 5804): com.google.android.music: cancel(1061) by com.google.android.music
,W/ContextImpl( 6172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6134): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6134): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6134): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6134):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6134):   adb logcat -s GAv4
D/Finsky  ( 6122): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6208 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6172): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6172): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/Gmail   ( 6053): notifyAccountChanged
W/GAv4    ( 6134): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/LGDMClient( 6172): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6172): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/GAv4    ( 6134): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
I/Gmail   ( 6053): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/GAv4    ( 6134): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6134): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/ContextImpl( 6172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6172): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6172): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6172): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6172): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6172): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/Gmail   ( 6053): notifyAccountChanged
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6134): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Gmail   ( 6053): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6053): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6053): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/AppUp4:AppBoxCP( 6208): onCreate
,W/AppUp4:DB( 6208):  [AppBoxDatabaseHelper] construct
D/Finsky  ( 6122): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/AppUp4:DB( 6208):  setFingerPrint start
I/AppUp4:DB( 6208):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6208):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6208):  SDK version = 0
I/AppUp4:DB( 6208):  beforefinger == newfinger no write in DB
W/Settings( 6122): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6122): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6122): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  857): Process com.uei.lg.quicksetsdk.lite (pid 5714) has died
,D/AppUp4:AppBoxApplication( 6208): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6208): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6208): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6208): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6208): [onReceive] request level :IDLE....
,V/DownloadManager( 3121): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3121): created cursor android.database.sqlite.SQLiteCursor@3df192ab on behalf of 6122
I/AppUp4:CustModeStarterReceiver( 6208): onReceive
,I/AppUp4:CustModeStarterReceiver( 6208): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6208): Context : android.app.ReceiverRestrictedContext@326ad2cb
D/AppUp4:CustFacade( 6208): isCustomizationCompleted : false
,I/WebViewFactory( 6134): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  857): Process com.lge.sync (pid 5554) has died
,D/AppUp4:CustFacade( 6208): isSimDevice : true
,I/art     (  857): Explicit concurrent mark sweep GC freed 23027(1063KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.573ms total 191.263ms
,I/LibraryLoader( 6134): Time to load native libraries: 2 ms (timestamps 965-967)
,I/LibraryLoader( 6134): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6134): Binding Chromium to main looper Looper (main, tid 1) {1804477c}
I/LibraryLoader( 6134): Expected native library version number "",actual native library version number ""
I/chromium( 6134): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6134): Initializing chromium process, singleProcess=true
W/art     ( 6134): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6134): ApplicationContext is null in ApplicationStatus
W/chromium( 6134): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/ActivityManager(  857): Process com.android.calendar (pid 5982) has died
I/BackgroundMemoryTrimmer( 1932): Trimming objects from memory, since app is in the background.
E/libEGL  ( 6134): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6134): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6134): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6134): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6134): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6134): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6134): Remote Branch: ,
I/Adreno-EGL( 6134): Local Patches: 
I/Adreno-EGL( 6134): Reconstruct Branch: 
,I/PhoneApp( 1745): onTrimMemory: 10
I/PhoneApp( 1745): trim memory
D/AppUp4:CustModeStarterReceiver( 6208): begin check event
I/AppUp4:CustModeStarterReceiver( 6208): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6208): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6208): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6208): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6208): handleAsyncCustNotification do not startCustService
D/Ads     ( 6122): Skipping gmscore version check
,D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  276): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/Finsky  ( 6122): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6122): [1] Libraries$2.run: Finished loading 1 libraries.
,V/AudioPolicyService(  281): registerClient() client 0xb4027080, uid 10079
,W/AudioManagerAndroid( 6134): Requires BLUETOOTH permission
D/Finsky  ( 6122): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 5897): propertyValue:false
,D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/LgeMiscReceiver( 3095): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3095): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3095): networkInfo.isConnected() = true
D/PhoneState( 3095): setPdpRejectCasuse : false
,D/libc-netbsd( 5897): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5897): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  857): Process com.android.gallery3d (pid 5853) has died
,I/BackgroundMemoryTrimmer( 1932): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1745): onTrimMemory: 10
I/PhoneApp( 1745): trim memory
I/NSApplication( 6134): Starting up...
,I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6291 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/Finsky  ( 6122): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Gmail   ( 6053): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14340, normalSync: true
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SyncAdapterService( 6134): Ignoring sync request for non-current account
,I/Gmail   ( 6053): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(-701419433) by android
W/ResourcesManager( 6053): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/PhoneMonitor( 6291): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6291): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6291): onReceive CONNECTIVITY_CHANGE networkType=1
,I/NotificationManager(  857): android: cancelAsUser(353845882) by android
,I/CheckinService( 3921): Checkin interval check for package: unspecified last checkin: 1452528234042 min interval config: 0 actual interval: 68252961
V/DownloadManager( 3121): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3121): DownloadService onCreate
I/NotificationManager( 3121): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3121): in removeSpuriousFiles
V/DownloadManager( 3121): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3121): created cursor android.database.sqlite.SQLiteCursor@38056ec6 on behalf of 3121
I/ActivityManager(  857): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6322 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/PhoneMonitor( 6291): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6291): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6291): [parse] Load xml
,V/TelephonyAutoProfiling( 6291): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6291): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/DownloadManager( 3121): in trimDatabase
V/DownloadManager( 3121): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3121): DownloadService onStartCommand
V/DownloadManager( 3121): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3121): created cursor android.database.sqlite.SQLiteCursor@16e2e1dd on behalf of 3121
,V/JNIHelp ( 6053): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/PhoneMonitor( 6291): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3121): created cursor android.database.sqlite.SQLiteCursor@2d59b152 on behalf of 3121
W/BaseAppContext( 3921): Using Auth Proxy for data requests.
I/CheckinService( 3921): Checking schedule, now: 1452596487150 next: 1452528263978
I/CheckinService( 3921): active receiver: enabled
W/BaseAppContext( 3921): Using Auth Proxy for data requests.
,W/BaseAppContext( 3921): Using Auth Proxy for data requests.
,I/CheckinService( 3921): Preparing to send checkin request
I/EventLogService( 3921): Accumulating logs since 1452594875771
,W/BaseAppContext( 3921): Using Auth Proxy for data requests.
,D/DrmBroadcastReceiver( 6322): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6322): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6322): Service onCreate
D/DrmService( 6322): Received new request = 2
I/DrmSntpClient( 6322): Start Sync process
D/DrmSntpClient( 6322): Server : 0
,D/WeatherAncestor( 2602): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:1:27
D/UpdateThreadPoolManager( 2602): 2 : This is isUpdating : false
,W/System  ( 6053): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
D/WeatherAncestor( 2602): connectivity changed - connection : true
I/ProviderInstaller( 6053): Installed default security provider GmsCore_OpenSSL
D/libc-netbsd( 6322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  276): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/Weather_cast( 2602): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2602): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:1:27
,D/WeatherService( 2602): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/art     ( 3921): Explicit concurrent mark sweep GC freed 12001(990KB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 14MB/24MB, paused 3.980ms total 116.579ms
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6322): propertyValue:false
I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6343 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2602): 2 : Utils getTopActivity com.lge.launcher2 / true
I/LGDrmClient( 6322): _DRM_ServiceGet() : Bind lgdrm service
,D/WeatherService( 2602): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2602): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/ILGDrmService(  287): eDRM_SetDRMTime +++
I/LGDRM   (  287): [DRM] SET TIME : YR=2016, MON=1, DAY=12
I/LGDRM   (  287): [DRM] SET TIME : HR=11, MIN=1, SEC=27
V/ILGDrmService(  287): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6322): Synched
D/DrmService( 6322): Completed !! request = 2
D/DrmService( 6322): Request count = 0
D/Finsky  ( 6122): [730] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6122): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  857): Process com.google.android.youtube (pid 5897) has died
V/DownloadManager( 3121): DownloadService onDestroy
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DrmService( 6322): Service onDestroy
I/VacuumService( 1729): Vacuum at: now=1452596487467 tag=VacuumService
W/BaseAppContext( 3921): Using Auth Proxy for data requests.
,W/BaseAppContext( 3921): Using Auth Proxy for data requests.
I/NotificationManager(  857): android: cancelAsUser(2) by android
,I/art     ( 5878): Explicit concurrent mark sweep GC freed 2804(110KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 2.308ms total 31.389ms
,W/BaseAppContext( 3921): Using Auth Proxy for data requests.
D/libc-netbsd( 6053): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6053): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6053): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6053): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10053
D/DnsProxyListener(  276): App 10053 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager( 6343): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 6053): propertyValue:false
D/libc-netbsd( 6053): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6053): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  857): android: cancelAsUser(-379682945) by android
,I/art     ( 6053): CheckpointMarkThreadRoots callback created = 0xaaf0b650
,I/art     ( 6053): CheckpointMarkThreadRoots callback created = 0xb0513c10
,I/GHttpClientFactory( 5804): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5804): Using platform SSLCertificateSocketFactory
I/MusicLifecycle( 5804): Sync started
,I/CheckinRequestBuilder( 3921): Checkin reason type: 8 attempt count: 1
,D/libc-netbsd( 6053): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6053): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/ActivityThread( 3921): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 6343): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6343): MmsConfig.loadMmsSettings
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel_SMS( 6343): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6343): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6343): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6343): MmsConfig.loadFromResources
E/Babel_SMS( 6343): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6343): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/ActivityManager(  857): Process com.lge.email (pid 5832) has died
,I/art     ( 6343): CheckpointMarkThreadRoots callback created = 0xb042d800
,I/NotificationManager(  857): android: cancelAsUser(2) by android
D/libc-netbsd( 5804): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5804): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5804): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5804): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10081
D/DnsProxyListener(  276): App 10081 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 6343): CheckpointMarkThreadRoots callback created = 0xb042d7e0
D/SensorManager( 6343): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6343): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6343): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6343): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6343): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6343): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6343): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6343): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6343): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6343): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6343): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6343): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6343): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6343): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6343): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6343): found sensor: Motion Accel, handle=46
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 5804): propertyValue:false
,D/libc-netbsd( 5804): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5804): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     (  857): Explicit concurrent mark sweep GC freed 19655(886KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.402ms total 183.330ms
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
,D/libc-netbsd( 5804): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5804): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Settings( 6343): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NotificationManager( 6053): com.google.android.gm: cancel(10436) by com.google.android.gm
,I/Babel_Crash( 6343): startup - clean
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel   ( 6343): deleted: false for 0
,I/ActivityManager(  857): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6389 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6343): Unsupported mime audio/x-lg-flac
I/art     ( 1729): Explicit concurrent mark sweep GC freed 54621(3MB) AllocSpace objects, 41(679KB) LOS objects, 39% free, 13MB/23MB, paused 3.861ms total 150.321ms
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioCapabilities( 6343): Unsupported mime audio/adpcm
I/jxcore-log( 5380): Test app app.js loaded
I/jxcore-log( 5380): 
W/AudioCapabilities( 6343): Unsupported mime audio/g726
W/AudioCapabilities( 6343): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6343): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6343): Unsupported mime video/mjpg
W/VideoCapabilities( 6343): Unsupported mime video/theora
,W/AudioCapabilities( 6343): Unsupported mime audio/evrc
,W/AudioCapabilities( 6343): Unsupported mime audio/qcelp
W/VideoCapabilities( 6343): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6343): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6343): Unsupported mime audio/qcelp
W/AudioCapabilities( 6343): Unsupported mime audio/evrc
W/VideoCapabilities( 6343): Unsupported mime video/mp4v-esdp
,I/chromium( 5380): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/VideoCapabilities( 6343): Unsupported profile 4 for video/mp4v-es
,E/lowmemorykiller(  242): Error writing /proc/6172/oom_score_adj; errno=22
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 113759459699; DSPS: 3825820; Offset : -2997237291
W/VideoCapabilities( 6343): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6343): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6343): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6343): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  857): Process com.lge.lgdmsclient (pid 6172) has died
,I/vclib   ( 6343): onServiceConnected
W/Babel   ( 6343): Attempted to change video mute state without an active call.
,I/NotificationManager( 6343): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6343): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6343): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6343): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6343): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/MusicSyncAdapter( 5804): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 5804): Periodic update
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 6343): propertyValue:false
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/Babel   ( 6343): connection state changed from UNKNOWN to CONNECTED
,W/MusicApiClient( 5804): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 5804): Sync ended
,I/NotificationManager(  857): android: cancelAsUser(-1123058983) by android
I/ActivityManager(  857): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6420 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6437 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6437): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6437): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6420): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MultiDex( 6437): VM with version 2.1.0 has multidex support
I/MultiDex( 6437): install
I/MultiDex( 6437): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6437): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 6053): Explicit concurrent mark sweep GC freed 79265(2MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/14MB, paused 574us total 77.814ms
,I/Gmail   ( 6053): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14578, normalSync: true
I/Gmail   ( 6053): lowestBackward conversation id 0
,W/ActivityThread( 6437): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6437): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1217734c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6437): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6437): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6437): com.google.android.gms: cancel(39789) by com.google.android.gms
I/NotificationManager( 6053): com.google.android.gm: cancel(10436) by com.google.android.gm
,I/NotificationManager( 6053): com.google.android.gm: cancel(10436) by com.google.android.gm
I/art     ( 6437): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6437): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/GAV2    ( 6053): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  857): Process com.android.vending (pid 6122) has died
,D/NativeLibraryUtils( 6437): Install completed successfully. count=14 extracted=0
I/Gmail   ( 6053): notifyAccountChanged
,I/Gmail   ( 6053): getAccountsCursor
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6053): notifyAccountChanged
,W/Gmail   ( 6053): Sync complete for account: account:61035162
I/NotificationManager(  857): android: cancelAsUser(1479798955) by android
D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): CdmEngine::OpenSession
I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
I/MusicWidget( 2510): mDelayedStopHandler : unbind
I/Gmail   ( 6053): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  281): L1 library not specified. Falling Back to L3
I/MusicBrowser( 2636): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2636): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2636): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2636): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2636): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2636): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2636): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2636): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  857):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2bc72dd8com.lge.music.MediaPlaybackService$6@20d68531
,D/MusicBrowser( 2636): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/GoogleURLConnFactory( 6437): Using platform SSLCertificateSocketFactory
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2636): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@18d1d0a7
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2636): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2636): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2636): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2636): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
E/Auth.Api.Credentials( 3921): [CredentialSyncAdapter] Unknown sync event.
I/MusicBrowser( 2636): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/WVCdm   (  281): PrepareKeyRequest: nonce=727684122
I/MusicBrowser( 2636): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2636): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2636): reset
,V/MediaPlayer[Native]( 2636): setListener
V/MediaPlayer[Native]( 2636): disconnect
V/MediaPlayer[Native]( 2636): destructor
,V/AudioFlinger(  281): releasing 19 from 2636 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2636): disconnect
D/MusicBrowser( 2636): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
D/libc-netbsd( 6437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6437): propertyValue:false
I/NotificationManager(  857): android: cancelAsUser(-591465577) by android
,I/SmartShareClient( 2636): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2636): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2636): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2636): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2636): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2636): [SmartShareManagerClient] unregisterListener: 215077910
W/SmartShareClient( 2636): [SmartShareManagerClient] unregisterListener invalid listener: 215077910
I/SmartShareClient( 2636): [SmartShareManagerClient] terminate service: 2636/MediaPlaybackService/387083845
E/HomeCloudIF( 2636): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2636): [SmartShareManagerClient] unbindService context:android.app.Application@2fa3197
V/CloudHub( 2636): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2636): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2636): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2636): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2636): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  857): Killing 6033:com.qualcomm.timeservice/1000 (adj 15): empty #11
I/CloudHub( 2636): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29983
,W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_6033/cgroup.procs: No such file or directory
,D/libc-netbsd( 6437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  857): Process com.google.android.talk (pid 6343) has died
,I/art     ( 6437): CheckpointMarkThreadRoots callback created = 0xb042daa0
,I/art     ( 6437): CheckpointMarkThreadRoots callback created = 0xb042da90
,I/iu.SyncManager( 3921): SYNC; picasa accounts
D/NetworkLogImpl( 3921): Loaded NetworkSpeedPredictor
I/iu.Environment( 3921): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3921): num queued entries: 0
,I/iu.UploadsManager( 3921): num updated entries: 0
I/iu.SyncManager( 3921): NEXT; no task
I/art     ( 6420): CheckpointMarkThreadRoots callback created = 0xb042d900
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 6420): CheckpointMarkThreadRoots callback created = 0xb042d8d0
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
,I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6485 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 6485): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/GCM     ( 1729): GCM config loaded
,I/Icing   ( 3921): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/Icing   ( 3921): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
,D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a737f21:true
,D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
,D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
I/ActivityManager(  857): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6509 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  857): Explicit concurrent mark sweep GC freed 24236(1040KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.302ms total 170.050ms
,I/NotificationManager(  857): android: cancelAsUser(-1874035846) by android
I/GoogleURLConnFactory( 3921): Using platform SSLCertificateSocketFactory
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/DigitalAppWidgetProvider( 6509): onReceive: android.intent.action.ALARM_CHANGED
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/WeatherAncestor( 2602): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:1:31
D/UpdateThreadPoolManager( 2602): 2 : This is isUpdating : false
D/Weather_cast( 2602): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2602): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:1:31
D/WeatherService( 2602): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2602): 2 : Utils getTopActivity com.lge.launcher2 / true
D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
D/WeatherService( 2602): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2602): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/System.out( 3921): propertyValue:false
W/art     ( 6420): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 3363): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/libc-netbsd( 6420): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6420): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  276): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  276): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/ActivityManager(  857): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=6548 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 282us total 23.651ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 369us total 20.668ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 20.555ms
,D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  857): Process com.lge.appbox.client (pid 6208) has died
,I/dex2oat ( 6566): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     ( 5878): Explicit concurrent mark sweep GC freed 3350(138KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 429us total 26.905ms
,D/Finsky  ( 6548): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dex2oat ( 6566): dex2oat took 127.765ms (threads: 4)
I/Adreno-EGL( 6437): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6437): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6437): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6437): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6437): Remote Branch: 
I/Adreno-EGL( 6437): Local Patches: 
I/Adreno-EGL( 6437): Reconstruct Branch: 
,I/Adreno-EGL( 6437): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6437): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6437): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6437): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6437): Remote Branch: 
I/Adreno-EGL( 6437): Local Patches: 
I/Adreno-EGL( 6437): Reconstruct Branch: 
,D/Finsky  ( 6548): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/NotificationManager( 6420): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,W/Settings( 6548): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6548): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6548): com.android.vending: cancel(-1050172287) by com.android.vending
,I/WVCdm   (  281): CdmEngine::CloseSession
I/WVCdm   (  281): L3 Terminate.
,V/DownloadManager( 3121): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3121): created cursor android.database.sqlite.SQLiteCursor@3c352520 on behalf of 6548
D/Ads     ( 6548): Skipping gmscore version check
,D/Finsky  ( 6548): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6548): [1] Libraries$2.run: Finished loading 1 libraries.
I/NotificationManager(  857): android: cancelAsUser(2145784878) by android
,D/Finsky  ( 6548): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6548): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/NotificationManager(  857): android: cancelAsUser(1500439826) by android
I/ActivityManager(  857): Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=6603 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/Adreno-EGL( 6437): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6437): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6437): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6437): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6437): Remote Branch: 
I/Adreno-EGL( 6437): Local Patches: 
I/Adreno-EGL( 6437): Reconstruct Branch: 
,I/MusicLeanback( 5804): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5804): Stop autocaching.
,W/ResourcesManager( 6603): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
,E/App     ( 6603): [App][onCreate()] 4.40.23
,D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1729): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 3921): Restart initialization of location
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
E/GmsUtils( 5804): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 5804): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5804): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MusicLeanback( 5804): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5804): Stop autocaching.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5804): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
I/WVCdm   (  281): CdmEngine::OpenSession
I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  281): L1 library not specified. Falling Back to L3
I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6636 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=821473133
D/AccountManager( 6603): setSyncFrequency
,D/DriveSyncService( 6603): onCreate
,D/DriveSyncService( 6603): onBind
I/ActivityManager(  857): Process com.google.android.apps.magazines (pid 6134) has died
,I/NotificationManager(  857): android: cancelAsUser(2126026182) by android
,D/DriveSyncAdapter( 6603): onPerformSync() START
D/DriveSyncAdapter( 6603): Not added account. Stop
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  857): Killing 6291:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/NotificationManager(  857): android: cancelAsUser(1312559638) by android
,W/ResourcesManager( 6636): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_6291/cgroup.procs: No such file or directory
,I/RemindersSync( 3921): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=557:priority=5:group=main]
,I/NotificationManager(  857): android: cancelAsUser(898701380) by android
,I/GCoreUlr( 1729): Uploading GCM registration ID for account#2#
,I/NotificationManager(  857): android: cancelAsUser(2145784878) by android
,E/lowmemorykiller(  242): Error writing /proc/2636/oom_score_adj; errno=22
V/AudioFlinger(  281): 2636 died, releasing its sessions
V/AudioFlinger(  281):  pid 1745 @ 0
V/AudioFlinger(  281):  pid 3095 @ 1
V/AudioFlinger(  281):  pid 3095 @ 2
,I/ActivityManager(  857): Process com.lge.music (pid 2636) has died
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
I/Babel_SMS( 6636): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6636): MmsConfig.loadMmsSettings
I/Babel_SMS( 6636): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6636): MmsConfig.loadFromDatabase
,I/art     ( 3121): Explicit concurrent mark sweep GC freed 5499(395KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 1.652ms total 75.765ms
,E/BaseAppContext( 1729): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/art     ( 6636): Suspending all threads took: 12.131ms
,E/Babel_SMS( 6636): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6636): MmsConfig.loadFromResources
E/Babel_SMS( 6636): canonicalizeMccMnc: invalid mccmnc nullnull
I/art     ( 6636): CheckpointMarkThreadRoots callback created = 0xaaf23e30
I/Babel_SMS( 6636): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6636): CheckpointMarkThreadRoots callback created = 0xaaf23e10
,D/SensorManager( 6636): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6636): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6636): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6636): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6636): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6636): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6636): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6636): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6636): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6636): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6636): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6636): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6636): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6636): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6636): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6636): found sensor: Motion Accel, handle=46
I/NotificationManager(  857): android: cancelAsUser(-1874035846) by android
,I/ActivityManager(  857): Process com.android.chrome (pid 6389) has died
,W/Settings( 6636): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6636): startup - clean
I/Babel   ( 6636): deleted: false for 0
,I/NotificationManager(  857): android: cancelAsUser(2) by android
I/NotificationManager(  857): android: cancelAsUser(-1548111331) by android
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
,W/AudioCapabilities( 6636): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6636): Unsupported mime audio/adpcm
W/AudioCapabilities( 6636): Unsupported mime audio/g726
W/AudioCapabilities( 6636): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6636): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6636): Unsupported mime video/mjpg
W/VideoCapabilities( 6636): Unsupported mime video/theora
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AudioCapabilities( 6636): Unsupported mime audio/evrc
W/AudioCapabilities( 6636): Unsupported mime audio/qcelp
W/VideoCapabilities( 6636): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6636): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6636): Unsupported mime audio/qcelp
W/AudioCapabilities( 6636): Unsupported mime audio/evrc
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/VideoCapabilities( 6636): Unsupported mime video/mp4v-esdp
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/VideoCapabilities( 6636): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6636): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6636): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6636): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  857): Process com.lge.clock (pid 6509) has died
W/VideoCapabilities( 6636): Unrecognized profile 2130706433 for video/avc
,I/art     (  857): Explicit concurrent mark sweep GC freed 34724(1532KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.105ms total 170.830ms
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
I/vclib   ( 6636): onServiceConnected
W/Babel   ( 6636): Attempted to change video mute state without an active call.
I/NotificationManager( 6636): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6696 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6485): Create singleton instance
,D/UEI.SmartControl( 6696): Quickset Services start...
,I/UEI.SmartControl( 6696): Manufacture = LGE
D/UEI.SmartControl( 6696): File observer start...
E/UEI.SmartControl( 6696): IR Port is disabled: false
D/UEI.SmartControl( 6696): Starting file observer...
D/UEI.SmartControl( 6696): Extracting JNI libs...
D/UEI.SmartControl( 6696): --- this system supports 32-bit or 64-bit only
I/GCoreUlr( 1729): GCM ID uploaded for account#2#
,I/AudioManager( 6485): getMode name:com.lge.qremote
I/GCoreUlr( 1729): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1729): DispatchingService.onCreate()
E/GmsUtils( 5804): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5804): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/NotificationManager(  857): android: cancelAsUser(1222422273) by android
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5804): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,I/GCoreUlr( 1729): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1729): Unbound from all location providers
,I/GCoreUlr( 1729): Place inference reporting - stopped
I/GCoreUlr( 1729): DispatchingService.onDestroy()
I/GCoreUlr( 1729): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1729): Unbound from all location providers
,I/GCoreUlr( 1729): Place inference reporting - stopped
D/UEI.SmartControl( 6696): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6696): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6696): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6696): --- Selecting new region: 2
,I/UEI.SmartControl( 6696): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6696): Platform has CIR...
D/UEI.SmartControl( 6696): NO CIR support, need to check package...
I/UEI.SmartControl( 6696): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6696): QS Service created
E/UEI.SmartControl( 6696): QS start get config
,D/UEI.SmartControl( 6696): Loading JNI Libs...
,D/UEI.SmartControl( 6696):  configuring local db...
I/WVCdm   (  281): CdmEngine::CloseSession
,I/WVCdm   (  281): L3 Terminate.
I/CheckinRequestBuilder( 3921): Classify the device as Phone.
,I/art     ( 3921): Explicit concurrent mark sweep GC freed 22615(1494KB) AllocSpace objects, 26(439KB) LOS objects, 39% free, 15MB/25MB, paused 1.534ms total 100.296ms
,D/UEI.SmartControl( 6696):  ---- Has DB8: true
,D/UEI.SmartControl( 6696): QS start statue = true Error code = 0
D/UEI.SmartControl( 6696): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6696): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6696): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6696): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6696): IrrcClient ++ 
D/irrcClient( 6696): getIrrcService ++ 
,D/irrcClient( 6696): getIrrcService -- 
D/irrcClient( 6696): IrrcClient -- 
W/irrc_jni( 6696): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6696): Services init done
I/UEI.SmartControl( 6696): Device manager: loading config....
D/UEI.SmartControl( 6696): QS Service init finished
D/UEI.SmartControl( 6696): QS Service version name: 0.1.73
D/UEI.SmartControl( 6696): QS Service version code: 1073
,D/UEI.SmartControl( 6696): Service requested: Control
,D/UEI.SmartControl( 6696): Config is loaded...
D/UEI.SmartControl( 6696):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6696): Notify AllClients services are ready: 0
D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 3921): propertyValue:false
D/UEI.SmartControl( 6696): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6696): Internal service binding...
,D/UEI.SmartControl( 6696): -----IControl: 11
,D/UEI.SmartControl( 6696): Caller: com.lge.qremote
D/UEI.SmartControl( 6696): ------------ IControl registerCallback...
I/UEI.SmartControl( 6696): Registering callback...
D/UEI.SmartControl( 6696): -----IControl: 19
D/UEI.SmartControl( 6696): Caller: com.lge.qremote
I/UEI.SmartControl( 6696): Registering Services Ready callback...
I/UEI.SmartControl( 6696): Notify client services are ready...
D/UEI.SmartControl( 6696): -----IControl: 8
D/UEI.SmartControl( 6696): Caller: com.lge.qremote
,I/AudioManager( 6485): getMode name:com.lge.qremote
I/AudioManager( 6485): getMode name:com.lge.qremote
,D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AudioManager( 6485): getMode name:com.lge.qremote
,D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3921): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3921): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 3921): Sending checkin request (10056 bytes)
,I/CheckinResponseProcessor( 3921): From server: 4 gservices updates and 0 deletes
,I/CertBlacklister(  857): Certificate blacklist changed, updating...
,I/GservicesProvider( 5878): main difference update completed
,I/CertBlacklister(  857): Certificate blacklist updated
I/CheckinRequestBuilder( 3921): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  857): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6746 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,E/ActivityThread( 3921): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  857): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6782 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/art     ( 5878): Explicit concurrent mark sweep GC freed 10086(497KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.303ms total 46.192ms
,I/ActivityManager(  857): Killing 6322:com.lge.drmservice/u0a51 (adj 15): empty #11
E/UpdateRequestReceiver( 6782): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinRequestBuilder( 3921): Classify the device as Phone.
,W/libprocessgroup(  857): failed to open /acct/uid_10051/pid_6322/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 6782): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6782): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6782): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  857): Killing 6548:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10036/pid_6548/cgroup.procs: No such file or directory
,I/CheckinTask( 3921): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 3921): Checking schedule, now: 1452596497073 next: 1453123746060
,I/CheckinService( 3921): active receiver: disabled
,D/CheckinService( 3921): Recording last checkin time for package unspecified as 1452596497105
,I/CheckinService( 3921): Checkin interval check for package: unspecified last checkin: 1452596497105 min interval config: 0 actual interval: 37
,I/CheckinService( 3921): Checking schedule, now: 1452596497155 next: 1453123746060
I/CheckinService( 3921): active receiver: disabled
,I/GservicesUpdateTask( 1932): Updating Gservices keys
I/SystemUpdateService( 3921): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 3921): onCreate
D/SystemUpdateService( 3921): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 3921): cancelUpdate (empty URL)
,I/SystemUpdateService( 3921): active receiver: disabled
,I/NotificationManager( 3921): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 3921): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  857): Handling package changes for user 0
,I/art     ( 5878): Explicit concurrent mark sweep GC freed 3311(133KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.107ms total 29.626ms
,I/art     ( 3921): Explicit concurrent mark sweep GC freed 22084(1313KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/25MB, paused 2.918ms total 98.823ms
,W/SQLiteConnectionPool( 3921): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/charger_monitor(  481): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,W/ResourcesManager(  857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SystemUpdateService( 3921): onDestroy
,E/DynamiteModule( 3921): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 3921): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 3921): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 3921): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 3921): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 3921): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 3921): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 3921): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 3921): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 3921): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 3921): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 3921): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 3921): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 3921): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 3921): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 3921): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 3921): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 3921): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 3921): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 3921): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 3921): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 3921): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 3921): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 3921): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 3921): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 3921): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 3921): 		... 17 more
E/DynamiteModule( 3921): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 3921): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 3921): Selected local version of com.google.android.gms.flags
D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
,I/NotificationService(  857): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  857): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  857): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
,D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
,I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/WifiController(  857): battery changed pluggedType: 2
,D/SystemEventReceiver( 3921): Received GSERVICES_CHANGED broadcast
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/BackupManagerService(  857): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  857): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@202bc6be
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/OcrUtils( 3921): Updating ocr activity enabled=false
,W/ResourceType(  857): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  857): Process com.google.android.apps.plus (pid 6420) has died
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1729): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  857): Explicit concurrent mark sweep GC freed 27918(1405KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.512ms total 168.848ms
,D/LocationProviderProxy(  857): applying state to connected service
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,W/ActivityManager(  857): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 3921): Updating downloaded model state (gservices changed)
I/art     ( 5878): Explicit concurrent mark sweep GC freed 2709(107KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 890us total 30.709ms
,I/NotificationManager(  857): android: cancelAsUser(-591465577) by android
I/art     ( 1729): Explicit concurrent mark sweep GC freed 47567(3MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 14MB/23MB, paused 1.363ms total 110.753ms
,D/GCM     ( 1729): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ActivityManager(  857): Killing 6603:com.lge.qmemoplus/1000 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_6603/cgroup.procs: No such file or directory
,I/art     ( 5878): Explicit concurrent mark sweep GC freed 2773(108KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.583ms total 33.767ms
,I/GCoreUlr( 1729): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1729): DispatchingService.onCreate()
,I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6859 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1729): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,E/ctxmgr  ( 1729): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
D/PhoneMonitor( 6859): Register our PhoneStateListener
,W/ctxmgr  ( 1729): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1729): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,V/SetupWizard( 6859): Connected to Gservices successfully
,D/PhoneMonitor( 6859): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6859): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6859): [parse] Load xml
V/TelephonyAutoProfiling( 6859): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6859): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6859): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     ( 1729): Explicit concurrent mark sweep GC freed 15625(864KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 14MB/24MB, paused 1.751ms total 91.803ms
,D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/GCoreUlr( 1729): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1729): Unbound from all location providers
I/GCoreUlr( 1729): Place inference reporting - stopped
I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6895 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/GCoreUlr( 1729): DispatchingService.onDestroy()
I/GCoreUlr( 1729): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1729): Unbound from all location providers
I/GCoreUlr( 1729): Place inference reporting - stopped
,I/NotificationManager( 6636): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6636): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6636): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6636): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6895): onCreate
,W/AppUp4:DB( 6895):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6895):  setFingerPrint start
,I/AppUp4:DB( 6895):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6895):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6895):  SDK version = 0
I/AppUp4:DB( 6895):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6895): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6895): onReceive
,I/AppUp4:CustModeStarterReceiver( 6895): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6895): Context : android.app.ReceiverRestrictedContext@17d37ebc
D/AppUp4:CustFacade( 6895): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6895): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6895): begin check event
I/AppUp4:CustModeStarterReceiver( 6895): Event For Nothing, skip.
I/ActivityManager(  857): Killing 6053:com.google.android.gm/u0a53 (adj 15): empty #11
W/System  ( 6636): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6636): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  857): failed to open /acct/uid_10053/pid_6053/cgroup.procs: No such file or directory
,I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6916 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 6636): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 6916): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6916): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6916): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 6916): Total System Memory = 906309632
,I/GalleryUtils( 6916): Application Heap = 96 MB
I/AppConfig( 6916): App Tier : NOT_DEF
,D/SystemHelper( 6916): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  857): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6941 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5804:com.google.android.music:main/u0a81 (adj 15): empty #11
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 1729): propertyValue:false
W/libprocessgroup(  857): failed to open /acct/uid_10081/pid_5804/cgroup.procs: No such file or directory
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ResourcesManager( 6941): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/SystemConfig( 6941): BUILD Country: EU
I/SystemConfig( 6941): BUILD Operator: OPEN
,D/UEI.SmartControl( 6696): Internal timer expired: 1
,I/ActivityManager(  857): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6964 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 6696:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6485): android.os.DeadObjectException
,W/System.err( 6485): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6485): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6485): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6485): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6485): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6485): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6485): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6485): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6485): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6485): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6485): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6485): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6485): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6485): android.os.DeadObjectException
W/System.err( 6485): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6485): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6485): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6485): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6485): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6485): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6485): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6485): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6485): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6485): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6485): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6485): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6485): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  857): failed to open /acct/uid_10089/pid_6696/cgroup.procs: No such file or directory
W/ActivityManager(  857): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/SystemConfig( 6941): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6941): existFile = false
I/SystemConfig( 6941): canReadFile = false
I/SystemConfig( 6941): systemFeature RCS result false
D/SystemConfig( 6941): refreshRcsSupport() :false
,I/LockScreenSettings( 6964): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6982 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 320us total 30.898ms
,I/NotificationManager(  857): android: cancelAsUser(2) by android
I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 341us total 22.813ms
,D/LockScreenSettings( 6964): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6964): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6964): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6964): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6964): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 25.230ms
I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7005 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 6485:com.lge.qremote/u0a106 (adj 15): empty #11
W/art     ( 6636): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup(  857): failed to open /acct/uid_10106/pid_6485/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6982): Quickset Services start...
I/UEI.SmartControl( 6982): Manufacture = LGE
,D/UEI.SmartControl( 6982): File observer start...
W/ResourcesManager( 7005): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/UEI.SmartControl( 6982): IR Port is disabled: false
D/UEI.SmartControl( 6982): Starting file observer...
D/UEI.SmartControl( 6982): Extracting JNI libs...
D/UEI.SmartControl( 6982): --- this system supports 32-bit or 64-bit only
D/libc-netbsd( 6636): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6636): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
D/UEI.SmartControl( 6982): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6982): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6982): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6982): --- Selecting new region: 2
I/UEI.SmartControl( 6982): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6982): Platform has CIR...
D/UEI.SmartControl( 6982): NO CIR support, need to check package...
I/UEI.SmartControl( 6982): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6982): QS Service created
,E/UEI.SmartControl( 6982): QS start get config
,D/UEI.SmartControl( 6982): Loading JNI Libs...
,D/UEI.SmartControl( 6982):  configuring local db...
,I/UpdateIcingCorporaServi( 1932): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  857): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7040 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 6746:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1932): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
,D/UEI.SmartControl( 6982):  ---- Has DB8: true
,D/UEI.SmartControl( 6982): QS start statue = true Error code = 0
D/UEI.SmartControl( 6982): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6982): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6982): IRRCDataComm has AudioManager!!!!.
,W/libprocessgroup(  857): failed to open /acct/uid_10009/pid_6746/cgroup.procs: No such file or directory
W/irrc_jni( 6982): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6982): IrrcClient ++ 
D/irrcClient( 6982): getIrrcService ++ 
D/irrcClient( 6982): getIrrcService -- 
D/irrcClient( 6982): IrrcClient -- 
W/irrc_jni( 6982): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6982): Services init done
I/UEI.SmartControl( 6982): Device manager: loading config....
D/UEI.SmartControl( 6982): QS Service init finished
D/UEI.SmartControl( 6982): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6982): QS Service version code: 1073
D/UEI.SmartControl( 6982): Service requested: Control
D/UEI.SmartControl( 6982): Config is loaded...
D/UEI.SmartControl( 6982):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6982): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6982): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6982): Service.onUnbind: IControl
,D/UEI.SmartControl( 6982): Service.onDestroy
D/UEI.SmartControl( 6982): Shutdown IRRCPlayer... 
W/irrc_jni( 6982): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6982): ~IrrcClient ++ 
D/irrcClient( 6982): ~IrrcClient -- 
W/irrc_jni( 6982): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6982): Blaster closed
D/UEI.SmartControl( 6982): Blaster closed
D/UEI.SmartControl( 6982): Shut down QS...
D/UEI.SmartControl( 6982): Stopped file observer...
I/UEI.SmartControl( 6982): QS lib stop result = true
,D/UEI.SmartControl( 6982): QS shutdown complete
D/UEI.SmartControl( 6982): QS Service created
E/UEI.SmartControl( 6982): QS start get config
,D/UEI.SmartControl( 6982):  configuring local db...
I/art     ( 6636): Note: end time exceeds epoch: 
,I/Babel   ( 6636): Account registration complete:1-Redacted-21
,I/art     (  857): Explicit concurrent mark sweep GC freed 20074(1043KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.336ms total 159.271ms
,I/Babel   ( 6636): ProcessRegisterDeviceResponse
I/Babel   ( 6636): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{1c7c851d type 2 when 126585 com.google.android.talk} when 126585
,D/Finsky  ( 7040): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 6982):  ---- Has DB8: true
,D/UEI.SmartControl( 6982): QS start statue = true Error code = 0
D/UEI.SmartControl( 6982): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6982): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6982): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6982): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6982): IrrcClient ++ 
D/irrcClient( 6982): getIrrcService ++ 
D/irrcClient( 6982): getIrrcService -- 
D/irrcClient( 6982): IrrcClient -- 
W/irrc_jni( 6982): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6982): Services init done
I/UEI.SmartControl( 6982): Device manager: loading config....
D/UEI.SmartControl( 6982): QS Service init finished
D/UEI.SmartControl( 6982): QS Service version name: 0.1.73
D/UEI.SmartControl( 6982): QS Service version code: 1073
D/UEI.SmartControl( 6982): Service requested: Control
,D/UEI.SmartControl( 6982): Config is loaded...
,D/UEI.SmartControl( 6982):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 6982): Request IControl service: devices are loaded...
,I/UEI.SmartControl( 6982): Notify AllClients services are ready: 0
E/ActivityThread( 6982): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2c774566 that was originally bound here
E/ActivityThread( 6982): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2c774566 that was originally bound here
E/ActivityThread( 6982): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6982): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6982): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6982): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6982): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6982): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6982): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6982): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6982): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6982): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6982): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6982): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6982): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6982): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6982): Internal service binding...
,D/Finsky  ( 7040): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7040): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7040): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7040): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3121): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3121): created cursor android.database.sqlite.SQLiteCursor@2ab0bed9 on behalf of 7040
D/Ads     ( 7040): Skipping gmscore version check
D/Finsky  ( 7040): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7040): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  857): Killing 6782:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10003/pid_6782/cgroup.procs: No such file or directory
,D/Finsky  ( 7040): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 3921): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 7040): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PackageBroadcastService( 3921): Null package name or gms related package.  Ignoreing.
I/Icing   ( 3921): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7114 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
D/WifiController(  857): battery changed pluggedType: 2
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  481): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,W/ResourcesManager( 7114): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  857): Message: 20
,D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8ab1a9a:true
,D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
D/BluetoothAdapterService(746014054)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9520eec
V/LGMDMManager( 7114): Create singleton instance
,I/AudioManager( 7114): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6982): -----IControl: 11
D/UEI.SmartControl( 6982): File observer start...
E/UEI.SmartControl( 6982): IR Port is disabled: false
D/UEI.SmartControl( 6982): Starting file observer...
D/UEI.SmartControl( 6982): Caller: com.lge.qremote
D/UEI.SmartControl( 6982): ------------ IControl registerCallback...
I/UEI.SmartControl( 6982): Registering callback...
D/UEI.SmartControl( 6982): -----IControl: 19
D/UEI.SmartControl( 6982): Caller: com.lge.qremote
I/UEI.SmartControl( 6982): Registering Services Ready callback...
I/UEI.SmartControl( 6982): Notify client services are ready...
,D/UEI.SmartControl( 6982): -----IControl: 8
D/UEI.SmartControl( 6982): Caller: com.lge.qremote
I/AudioManager( 7114): getMode name:com.lge.qremote
I/ActivityManager(  857): Killing 6437:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_6437/cgroup.procs: No such file or directory
,I/AudioManager( 7114): getMode name:com.lge.qremote
I/AudioManager( 7114): getMode name:com.lge.qremote
,E/Babel   ( 6636): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,E/Babel   ( 6636): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,I/art     ( 6636): Note: end time exceeds epoch: 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/Icing   ( 3921): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 3921): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 3921): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  857): Killing 6859:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_6859/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/UEI.SmartControl( 6982): file observer is disposed!
,W/PackageSettings(  857): Skipping PackageSetting{cf4e30f com.example.hello/10317} due to missing metadata
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 6982): Internal timer expired: 2
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  857): Killing 6895:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_6895/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 133760473650; DSPS: 4481214; Offset : -2997261693
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{141e1bb type 2 when 136506 android} when 136506
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
,I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
,I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=296790110, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,D/WeatherService( 2602): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:2:0
D/WeatherService( 2602): 2 : TimeTick Intent And Screen On
D/WeatherService( 2602): 2 : SDK version : 21
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2602): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2602): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2602): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2602): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2602): 2 : This is isUpdating : false
D/WeatherService( 2602): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2602): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2602): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2602): 2 : Fixed theme : optimus
D/WeatherReflect( 2602): 2 : Map key string is -2
,D/lim     ( 2602): 2 : time = 12:02
I/WeatherReflect( 2602): Model Name : LG-D722
D/WeatherTheme( 2602): 2 : Different view - status_min_formatted : 01 != 02
D/WeatherTheme( 2602): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2602): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2602): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2602): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/Weather4x2_optimus( 2602): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2602): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2602): forecast size is 0
D/Theme   ( 2602): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2602): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2602): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2602): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2602): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2602): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2602): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2602): url is : null
D/Theme   ( 2602): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2602): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2602): 2 : update view, appWidgetId: 2
,D/WeatherService( 2602): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:2:0
D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=296790110 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29029 ms ago)
,D/qdlights(  857): set_light_backlight: 253
,D/qdlights(  857): set_light_backlight: 250
D/qdlights(  857): set_light_backlight: 246
,D/qdlights(  857): set_light_backlight: 243
,D/qdlights(  857): set_light_backlight: 240
,D/qdlights(  857): set_light_backlight: 236
,D/qdlights(  857): set_light_backlight: 233
,D/qdlights(  857): set_light_backlight: 230
,D/qdlights(  857): set_light_backlight: 226
,D/qdlights(  857): set_light_backlight: 223
,D/qdlights(  857): set_light_backlight: 220
,D/qdlights(  857): set_light_backlight: 216
,D/qdlights(  857): set_light_backlight: 213
,D/qdlights(  857): set_light_backlight: 210
,D/qdlights(  857): set_light_backlight: 206
,D/qdlights(  857): set_light_backlight: 203
,D/qdlights(  857): set_light_backlight: 200
,D/qdlights(  857): set_light_backlight: 196
,D/qdlights(  857): set_light_backlight: 193
,D/qdlights(  857): set_light_backlight: 190
,D/qdlights(  857): set_light_backlight: 186
,D/qdlights(  857): set_light_backlight: 183
,D/qdlights(  857): set_light_backlight: 180
,D/qdlights(  857): set_light_backlight: 176
,D/qdlights(  857): set_light_backlight: 173
,D/qdlights(  857): set_light_backlight: 170
,D/qdlights(  857): set_light_backlight: 166
,D/qdlights(  857): set_light_backlight: 163
,D/qdlights(  857): set_light_backlight: 160
,D/qdlights(  857): set_light_backlight: 156
,D/qdlights(  857): set_light_backlight: 153
,D/qdlights(  857): set_light_backlight: 150
,D/qdlights(  857): set_light_backlight: 146
,D/qdlights(  857): set_light_backlight: 143
,D/qdlights(  857): set_light_backlight: 140
,D/qdlights(  857): set_light_backlight: 136
,D/qdlights(  857): set_light_backlight: 133
,D/qdlights(  857): set_light_backlight: 130
,D/qdlights(  857): set_light_backlight: 126
,D/qdlights(  857): set_light_backlight: 123
,D/qdlights(  857): set_light_backlight: 120
,D/qdlights(  857): set_light_backlight: 116
,D/qdlights(  857): set_light_backlight: 113
,D/qdlights(  857): set_light_backlight: 110
,D/qdlights(  857): set_light_backlight: 106
,D/qdlights(  857): set_light_backlight: 103
,D/qdlights(  857): set_light_backlight: 100
,D/qdlights(  857): set_light_backlight: 96
,D/qdlights(  857): set_light_backlight: 93
,D/qdlights(  857): set_light_backlight: 90
,D/qdlights(  857): set_light_backlight: 86
,D/qdlights(  857): set_light_backlight: 83
,D/qdlights(  857): set_light_backlight: 80
,D/qdlights(  857): set_light_backlight: 76
,D/qdlights(  857): set_light_backlight: 73
,D/qdlights(  857): set_light_backlight: 70
,D/qdlights(  857): set_light_backlight: 66
,D/qdlights(  857): set_light_backlight: 63
,D/qdlights(  857): set_light_backlight: 60
,D/qdlights(  857): set_light_backlight: 56
,D/qdlights(  857): set_light_backlight: 53
,D/qdlights(  857): set_light_backlight: 50
,D/qdlights(  857): set_light_backlight: 46
,D/qdlights(  857): set_light_backlight: 43
,D/qdlights(  857): set_light_backlight: 40
,D/qdlights(  857): set_light_backlight: 36
,D/qdlights(  857): set_light_backlight: 33
,D/qdlights(  857): set_light_backlight: 30
,D/qdlights(  857): set_light_backlight: 26
,D/qdlights(  857): set_light_backlight: 23
,D/qdlights(  857): set_light_backlight: 20
,D/qdlights(  857): set_light_backlight: 16
,D/qdlights(  857): set_light_backlight: 13
,D/qdlights(  857): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 153761242081; DSPS: 5136599; Offset : -2997258051
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36024 ms ago)
I/PowerManagerService(  857): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36040 ms ago)
,W/ContextImpl(  857): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  857): Sleeping (uid 1000)...
D/LPWGController(  857): [updateScreenState] screen on = false
D/LPWGController(  857): disable proximity sensor
,D/LPWGController(  857): enable proximity sensor
I/SensorManager(  857): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2d7646d8] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  857): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  857): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  857): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  857): activate: handle is 48, enable
V/sensors_hal_Ctx(  857): activate sensors is 1400000000000
D/sensors_hal_Thresh(  857): enable: handle=48
I/sensors_hal_SAM(  857): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  857): waitForResponse: timeout=1000
V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  857): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  857): enable: Received response: 0
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36085 ms ago)
,I/Adreno-EGL(  857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  857): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  857): Build Date: 03/02/15 Mon
I/Adreno-EGL(  857): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  857): Remote Branch: 
I/Adreno-EGL(  857): Local Patches: 
I/Adreno-EGL(  857): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (169 us)
,I/Sensors (  435): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  857): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  857): processInd: handle 48, count=1
V/sensors_hal_Thresh(  857): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  857): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  857): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  857): poll: count: 256
I/sensors_hal_Ctx(  857): poll: released wakelock sensor_ind
D/sensors_hal_Util(  857): waitForResponse: timeout=0
D/LPWGController(  857): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  857): current mode = 1  value = 1 1
I/LPWGController(  857): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  857): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  857): set_light_backlight: 0
,I/SensorManager(  857): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  857): activate: handle is 46, disable
V/sensors_hal_Ctx(  857): activate sensors is 1000000000000
D/sensors_hal_LP2(  857): enable: handle=46
D/sensors_hal_LP2(  857): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  857): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  857): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  857): Display changed displayId=0
V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  857): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1745): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  857): Excessive delay in setPowerMode(): 188ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  857): Got set_interactive hint
D/KeyguardViewMediator( 1369): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1328): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1369): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1328): notifyScreenOffLocked
D/SmartCoverViewMediator( 1328): handleNotifyScreenOFF
D/KeyguardViewMediator( 1369): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1369): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1369): unregisterProximitySensor
,D/WifiServerServiceExt(  857): sendKtScanInterval  mRtspPlay : false
,D/StatusBarWindowView( 1369): onScreenTurnedOff why = 3
I/WifiServerServiceExt(  857): set CMD_KT_SCAN_INTERVAL
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 857
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  281): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,D/GpsLocationProvider(  857): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1801): stopPatternFlashing()
D/Cliptray Service( 1801): lockStatus = 0
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1782): action : android.intent.action.SCREEN_ON
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1801): RESTART MSG
D/NfcServiceNXP( 1782): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1782): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1782): isRequireNfcCRouting() return true
D/LNfcService( 1782): isHCERoutingtoHost() return : true
D/NfcService( 1782): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): newParams.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): screenState= 3
D/NfcService( 1782): Discovery configuration equal, not updating.
D/Ulp_jni (  857): JNI:system_update. Event-0
D/SplitWindow(  857): check instance of lgWin Window{3f22de97 u0 SearchPanel}
,D/InputDispatcher(  857): Window went away: Window{c773019 u0 SearchPanel}
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2602): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:2:13
,D/WeatherService( 2602): 2 : ACTION screen on
I/Sensors (  435): sns_pwr.c(301):releasing wakelock
D/WeatherService( 2602): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2602): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2602): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:2:13
D/AppCleanupService( 3798): android.intent.action.SCREEN_ON
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): ACTION_SCREEN_ON
V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 857
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: enter: screen_state=off
,V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
,V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
D/WifiController(  857): CMD_SCREEN_OFF 
D/WifiController(  857): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  857): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1782): action : android.intent.action.SCREEN_OFF
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
D/NfcServiceNXP( 1782): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2602): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:2:13
D/WeatherService( 2602): 2 : ACTION screen off
D/WeatherService( 2602): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2602): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:2:13
D/AppCleanupService( 3798): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3798): AppUsageStatsSaveTask
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): ACTION_SCREEN_OFF
E/NxpNfcJni( 1782): getReconnectState = 0x0
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1782): getDefaultRoute
D/LNfcService( 1782): isRequireNfcCRouting() return true
D/LNfcService( 1782): isHCERoutingtoHost() return : true
D/NfcService( 1782): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): newParams.techmask= mTechMask: 0
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): screenState= 1
E/NxpNfcJni( 1782): getReconnectState = 0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1369): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{174f884 type 2 when 161974 com.android.systemui} when 161974
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1745): getCallState : 0
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1369): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1369): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{3c9e386d type 2 when 166515 android} when 166515
,E/ActivityThread( 3921): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  857): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 139272, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  857): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 230550, reason: UserStart
I/NotificationManager(  857): android: cancelAsUser(716319171) by android
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 173762069156; DSPS: 5791986; Offset : -2997252762
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{ac9b0ee type 2 when 187965 com.google.android.gms} when 187965
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{11dd098f type 2 when 187739 android} when 187739
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/PhenotypeConfigurator( 1729): Scheduling Phenotype for one-off execution 4269 seconds from now (1452596563695)
,D/GetConfigurationSnapshotOperation( 1729): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1729): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 1729): propertyValue:false
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 193762742742; DSPS: 6447368; Offset : -2997251787
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{12d9747f type 2 when 196538 android} when 196538
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  857): battery changed pluggedType: 2
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 213763509401; DSPS: 7102754; Offset : -2997277569
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 233764191841; DSPS: 7758136; Offset : -2997266542
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ClearcutLoggerApiImpl( 1729): disconnect managed GoogleApiClient
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 253764868135; DSPS: 8413518; Offset : -2997261739
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 273765624482; DSPS: 9068903; Offset : -2997268618
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 293766378016; DSPS: 9724287; Offset : -2997247193
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 313767198321; DSPS: 10379674; Offset : -2997250838
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 5380): --= Surplus to requirements =--
I/jxcore-log( 5380): 
I/jxcore-log( 5380): ****TEST TOOK:  ms ****
I/jxcore-log( 5380): 
I/jxcore-log( 5380): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5380): 
,D/AndroidRuntime( 7270): 
D/AndroidRuntime( 7270): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7270): CheckJNI is OFF
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/AndroidRuntime( 7270): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  857): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  857): Killing 5380:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  857): Skipping PackageSetting{cf4e30f com.example.hello/10317} due to missing metadata
,I/WindowState(  857): WIN DEATH: Window{d683437 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  857): Focus left window: Window{d683437 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  857): Window went away: Window{d683437 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  857):   Force finishing activity ActivityRecord{339e554d u0 com.test.thalitest/.MainActivity t220}
,V/ActivityManager(  857): Display changed displayId=0
,D/DSDPConnection( 1745): Display #0 changed.
W/ActivityManager(  857): Spurious death for ProcessRecord{214f7c4c 5380:com.test.thalitest/u0a316}, curProc for 5380: null
,I/ActivityManager(  857): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
W/System.err( 3363): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/System.err( 3363): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,W/System.err( 3363): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3363): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3363): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3363): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3363): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3363): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3363): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3363): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3363): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3363): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  857): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7295 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [Launcher.java:5203:onStart()]onStart
,I/art     ( 1932): Explicit concurrent mark sweep GC freed 9386(571KB) AllocSpace objects, 2(48KB) LOS objects, 40% free, 12MB/21MB, paused 5.181ms total 150.478ms
I/art     ( 3921): Explicit concurrent mark sweep GC freed 10090(536KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 1.216ms total 156.791ms
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]EVENT( 1874): [Launcher.java:776:onResume()]onResume
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]EVENT( 1874): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1874): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1874): [Launcher.java:929:onResume()]onResume end
I/Activity( 1874): Activity.onPostResume() called 
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1874): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1874): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1369): handleShortcutListChanged...
I/SystemUI[Framework](  857): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  857): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  857): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  857): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  857): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d7c3e71,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/SystemUI[Framework](  857): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  857): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  857): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  857): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@d7c3e71,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  857): Focus entered window: Window{322aca0b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
,W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1874): [setNavigationBarColor] color=0x 0
,D/KeyguardModel( 1369): handleShortcutListChanged...
W/ResourcesManager( 7295): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7295): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7295): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     (  857): Explicit concurrent mark sweep GC freed 62214(3MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 23.906ms total 308.894ms
I/art     (  857): WaitForGcToComplete blocked for 170.513ms for cause Explicit
,D/administrator(  857): Handling package changes for user 0
,I/LGEmail ( 7295): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7295): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  857): Explicit concurrent mark sweep GC freed 5505(330KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 8.320ms total 286.314ms
,D/AndroidRuntime( 7270): Shutting down VM
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
W/InputMethodManagerService(  857): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  857): Got RemoteException sending setActive(false) notification to pid 5380 uid 10316
I/NotificationService(  857): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  857): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
,D/TaskPersister(  857): removeObsoleteFile: deleting file=220_task.xml
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  857): Timeline: Activity_windows_visible id: ActivityRecord{1268d3c8 u0 com.lge.launcher2/.Launcher t219} time:324625
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/IInputConnectionWrapper( 1874): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1616): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/PackageChangeReceiver( 7295): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1874): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7328 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  857): Killing 6916:com.android.gallery3d/u0a23 (adj 15): empty #11
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,W/libprocessgroup(  857): failed to open /acct/uid_10023/pid_6916/cgroup.procs: No such file or directory
,W/ResourcesManager(  857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7328): onCreate
,W/AppUp4:DB( 7328):  [AppBoxDatabaseHelper] construct
W/FileUtils( 7328): Failed to chmod(/data/data/com.lge.appbox.client/databases/appbox.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/AppUp4:DB( 7328):  setFingerPrint start
I/AppUp4:DB( 7328):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7328):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7328):  SDK version = 0
I/AppUp4:DB( 7328):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7328): AppBoxApplication onCreate()
E/SQLiteLog( 7328): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/SQLiteDatabase( 7328): Error inserting package=com.test.thalitest
E/SQLiteDatabase( 7328): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 7328): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 7328): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
E/SQLiteDatabase( 7328): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 7328): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 7328): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
E/SQLiteDatabase( 7328): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
E/SQLiteDatabase( 7328): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 7328): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 7328): 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
E/SQLiteDatabase( 7328): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 7328): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 7328): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 7328): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 7328): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 7328): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/SQLiteDatabase( 7328): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/SQLiteDatabase( 7328): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/SQLiteDatabase( 7328): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7328): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7328): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 7328): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7328): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7328): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 7328): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  857): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7348 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a

```
