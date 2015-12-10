#### Test 506502784dae475_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
V/AlarmManager(  857): RTC_WAKEUP set : Alarm{7b4fed2 type 0 when 1449750983098 com.android.vending} when 1449750983098
--------- beginning of main
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Finsky  ( 4906): [580] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4906): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AlertService( 5321): Beginning updateAlertNotification
D/AlertService( 5321): No fired or scheduled alerts
I/NotificationManager( 5321): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(10) by com.android.calendar
,I/NotificationManager( 5321): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5321): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5321): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5321): No events found starting within 1 week.
I/ActivityManager(  857): Killing 5160:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10069/pid_5160/cgroup.procs: No such file or directory
D/AndroidRuntime( 5376): 
D/AndroidRuntime( 5376): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5376): CheckJNI is OFF
D/AndroidRuntime( 5376): Calling main entry com.android.commands.am.Am
I/ActivityManager(  857): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  857): setTaskToReturnTo : TaskRecord{1620aba3 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  857): setTaskToReturnTo : TaskRecord{1620aba3 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  857): AppWindowTokenEx init.. 
D/ContextHelper(  857): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  857): Focus left window: Window{3c529e3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5376): Shutting down VM
D/SplitWindow(  857): check instance of lgWin Window{3b4e7315 u0 Starting com.test.thalitest}
I/ActivityManager(  857): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5390 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1933): Closing mic
I/MicrophoneInputStream( 1933): mic_close com.google.android.apps.gsa.speech.audio.u@9ae6769
V/AudioRecord( 1933): stop()
D/AudioRecord( 1933): AudioRecord->stop()
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioFlinger(  276): Record stopped OK
V/AudioPolicyManager(  276): stopInput() input 17
V/AudioPolicyService(  276): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  276): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  276): ThreadBase::setParameters() routing=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb4317000
D/audio_hw_primary(  276): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/WindowStateAnimator(  857): Starting window displayed
I/SystemUI[Framework](  857): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  857): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  857): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  857): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1c6ff60e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1371): draw background and invalidate : color = b000000
D/BarTransitions( 1371): draw background and invalidate : color = 15141414
V/audio_hw_primary(  276): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  276): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  276): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  276): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  276): disable_audio_route: exit
E/audio_hw_primary(  276): disable_snd_device: enter 144
D/hardware_info(  276): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  276): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  276): stop_input_stream: exit: status(0)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  276): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  276): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  276): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  276): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  276): setParameters(): io 17, keyvalue hotword_active=0, calling pid 276
V/AudioFlinger(  276): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  276): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  276): in_set_parameters: exit: status(0)
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb4317000
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
,V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioPolicyManager(  276): releaseInput() 17
V/AudioPolicyManager(  276): closeInput(17)
V/AudioFlinger(  276): closeInput() 17
V/AudioSystem(  276): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  857): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): ThreadBase::exit
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioSystem( 2074): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): RecordThread 0xb4317000 exiting
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  276): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  276): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioPolicyService(  276): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  276): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  276): releaseInput() exit
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioFlinger(  276): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  276): AudioCommandThread() processing update audio port list
V/AudioFlinger(  276): removeClient_l() pid 1933, calling pid 276
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3079): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1933): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): releasing 16 from 1933 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
I/HotwordRecognitionRnr( 1933): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1933): Hotword detection finished
D/ContextHelper( 5390): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5390): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5390): Time to load native libraries: 6 ms (timestamps 1239-1245)
,I/LibraryLoader( 5390): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5390): Binding Chromium to main looper Looper (main, tid 1) {e9f1a58}
I/LibraryLoader( 5390): Expected native library version number "",actual native library version number ""
I/chromium( 5390): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5390): Initializing chromium process, singleProcess=true
W/art     ( 5390): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5390): ApplicationContext is null in ApplicationStatus
W/chromium( 5390): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5390): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5390): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5390): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5390): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5390): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5390): Remote Branch: 
I/Adreno-EGL( 5390): Local Patches: 
I/Adreno-EGL( 5390): Reconstruct Branch: 
,V/AudioPolicyService(  276): registerClient() client 0xb57e9720, uid 10316
,D/BluetoothManagerService(  857): Message: 20
,D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77d05ef:true
D/BluetoothAdapter( 5390): 575970797: getState() :  mService = null. Returning STATE_OFF
V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{1214663d type 2 when 91555 com.google.android.gms} when 91555
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,W/art     ( 5390): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5390): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5390): CordovaWebView is running on device made by: LGE
,W/art     ( 5390): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5390): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 5390): Activity.onPostResume() called 
,D/OpenGLRenderer( 5390): Render dirty regions requested: true
I/OpenGLRenderer( 5390): Initialized EGL, version 1.4
D/OpenGLRenderer( 5390): Enabling debug mode 0
,D/Atlas   ( 5390): Validating map...
,D/SplitWindow(  857): check instance of lgWin Window{fda292c u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5390): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  857): Focus entered window: Window{fda292c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/Finsky  ( 4906): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{36f3718a type 0 when 1449750985379 com.android.vending} when 1449750985379
I/ActivityManager(  857): Displayed com.test.thalitest/.MainActivity: +1s93ms
I/Timeline(  857): Timeline: Activity_windows_visible id: ActivityRecord{346eea0 u0 com.test.thalitest/.MainActivity t220} time:91887
W/InputMethodManagerService(  857): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/Timeline( 5390): Timeline: Activity_idle id: android.os.BinderProxy@14e5f634 time:91900
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,W/BindingManager( 5390): Cannot call determinedVisibility() - never saw a connection for the pid: 5390
,D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4906): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  857): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5477 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4906): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5477): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5477): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5477): VM with version 2.1.0 has multidex support
I/MultiDex( 5477): install
I/MultiDex( 5477): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5477): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/JsMessageQueue( 5390): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityThread( 5477): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5477): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29e958da: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5477): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5477): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5477): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 5477): Reading stored module config
,D/LocationInitializer( 5205): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,D/ChimeraCfgMgr( 5477): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 28606(1695KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 13MB/22MB, paused 2.120ms total 134.491ms
,W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
D/jxcore_app_log( 5390): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622832128
D/JX-Cordova( 5390): jxcore cordova android initializing
D/CAR.SERVICE( 5477): Connecting to CarCallService...
D/NativeLibraryUtils( 5477): Install completed successfully. count=14 extracted=0
,I/art     ( 5477): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5477): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 5477): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5477): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5477): Creating a new PhoneAdapter instance
W/ActivityManager(  857): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5477): setListener: com.google.android.gms.car.dn@ee27d71
W/ActivityManager(  857): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5477): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5477): Starting CarCallService with initial phone null
I/NotificationManager( 5477): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 5390): CheckpointMarkThreadRoots callback created = 0x9b2584a0
,I/art     ( 5390): CheckpointMarkThreadRoots callback created = 0x9b258470
D/CAR.SERVICE( 5477): Package validated; name: com.android.vending
,I/NotificationManager( 4906): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 4906): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4906): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4906): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 4906): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{3875097 type 0 when 1449750986870 com.android.vending} when 1449750986870
,D/Finsky  ( 4906): [1] DailyHygiene.reschedule: Scheduling new run in 869 minutes (failures=5)
,I/art     ( 5390): Background sticky concurrent mark sweep GC freed 29388(3MB) AllocSpace objects, 10(1398KB) LOS objects, 22% free, 15MB/19MB, paused 5.665ms total 61.270ms
,D/DeviceConnectionService( 1730): client connected with version: 8296000
D/Finsky  ( 4906): [589] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/jxcore-log( 5390): Initializing JXcore engine
,W/jxcore-log( 5390): JXcore engine is ready
W/jxcore-log( 5390): Starting JXcore engine
,W/.test.thalitest( 5390): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5494]" dev="sockfs" ino=5494 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5390): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5390): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8077]" dev="sockfs" ino=8077 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5390): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5390): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5390): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25951]" dev="sockfs" ino=25951 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5390): Platform android
W/jxcore-log( 5390): 
W/jxcore-log( 5390): Process ARCH arm
W/jxcore-log( 5390): 
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 94881221375; DSPS: 3206915; Offset : -2996829342
,I/jxcore-log( 5390): JXcore Cordova bridge is ready!
I/jxcore-log( 5390): 
W/jxcore-log( 5390): JXcore engine is started
,I/Choreographer( 5390): Skipped 172 frames!  The application may be doing too much work on its main thread.
I/chromium( 5390): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 5390): Toggling radios to true
I/jxcore-log( 5390): 
,D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  857): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  857): Message: 1
D/BluetoothManagerService(  857): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(722961412)( 1999): onBind()
,D/LocationManagerService(  857): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  857): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  857): JNI:system_update. Event-4
D/BluetoothManagerService(  857): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  857): Message: 40
D/BluetoothManagerService(  857): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/WifiServiceImplEx(  857): setWifiEnabled: true pid=5390, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  857): setWifiEnabled: true pid=5390, uid=10316
,D/LocationManagerService(  857): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  857): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  857): JNI:system_update. Event-4
D/WifiServiceImplEx(  857): disconnect pid=5390, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  857): reconnect pid=5390, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5390): Radios toggled
I/jxcore-log( 5390): 
I/bluedroid( 1999): config_hci_snoop_log
D/BluetoothManagerService(  857): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  857): Broadcasting onBluetoothServiceUp() to 9 receivers.
I/LGFTMITEM(  857): [GET_FTM][id=6], offset=12288
E/WifiHW  (  857): Wifi MAC Address = a0:39:f7:70:12:80
,V/LGMDMManagerInternal( 1999): Create singleton instance
E/WifiHW  (  857): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  857): band=b
E/WifiHW  (  857): ": cur_etheraddr=a0:39:f7:70:12:80
,D/SoftapController(  272): Softap fwReload - Ok
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  272): Setting iface cfg
D/CommandListener(  272): Trying to bring down wlan0
,D/CommandListener(  272): Clearing all IP addresses on wlan0
E/WifiHW  (  857): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothAdapterService(722961412)( 1999): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1999): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1999): Setting state to 11
I/BluetoothAdapterState( 1999): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(722961412)( 1999): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  857): Message: 60
D/BluetoothManagerService(  857): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  857): Bluetooth State Change Intent: 10 -> 11
D/BluetoothAdapterService(722961412)( 1999): processStart()
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/ActivityManager(  857): Process com.google.android.gm (pid 5005) has died
,I/wpa_supplicant( 5535): Successfully initialized wpa_supplicant
D/LGBluetoothAPIService( 1804): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
,D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1371): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/BtSettings.ProfileConfig( 1999): Unable to read settings
D/BtSettings.ProfileConfig( 1999): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1999): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1999): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1999): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1999): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1999): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1999): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1999): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1999): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1999): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  857): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5536 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/WifiMonitor(  857): startMonitoring(wlan0) with mConnected = false
I/WifiServerServiceExt(  857): WIFI_STATE_CHANGED_ACTION [2]
,I/wpa_supplicant( 5535): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5535): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
W/BluetoothAdapterService( 1999): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(722961412)( 1999): processStart() - Make Bond State Machine
,D/BluetoothBondStateMachine( 1999): make
I/BluetoothBondStateMachine( 1999): StableState(): Entering Off State
D/BluetoothAdapterService( 1999): setAdapterService() - set to: null
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
,D/LGBluetoothServiceAdapter( 1999): [BTUI] check adapter is available - true : set adapter available.
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:29.751 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 1999): Unable to read settings
D/BtSettings.ProfileConfig( 1999): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1999): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1999): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1999): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1999): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1999): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1999): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1999): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1999): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1999): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1999): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1999): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1999): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1999): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/BluetoothHeadset( 1750): Proxy object connected
D/HeadsetService( 1999): Received start request. Starting profile...
D/BluetoothHeadset(  857): Proxy object connected
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1999): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
I/LGBluetoothHeadsetServiceJni( 1999): classInitNative: succeeds
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 1999): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/LGBluetoothFeatureConfig( 1999): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1999): classInitNative: succeeds
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1999): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 1999): make
D/BluetoothHeadset( 1750): Proxy object connected
,D/BluetoothHeadset( 1750): Proxy object connected
I/art     (  857): Explicit concurrent mark sweep GC freed 18916(868KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 7.553ms total 197.922ms
,D/HeadsetStateMachine( 1999): max_hf_connections = 1
I/bluedroid( 1999): get_profile_interface handsfree
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1999): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
I/bt-btif ( 1999): btif_hf_get_interface
I/bt-btif ( 1999): init
,D/bt-btif ( 1999): max_hf_clients = 1
D/bt-btif ( 1999): btif_max_hf_clients = 1
D/bt-btif ( 1999): btif_enable_service: current services:0xa0628330
V/ToneGenerator( 1999): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  276): registerClient() client 0xb551cd20, uid 1002
V/AudioPolicyManager(  276): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  276): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  276): getOutput() returns output 2
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1999): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
V/AudioFlinger(  276): registerClient() client 0xb3844be0, pid 1999
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  276): thread 0xb5651000 type 0 TID 1292 waking up
V/AudioFlinger(  276): thread 0xb56eb000 type 0 TID 1293 waking up
V/AudioFlinger(  276): thread 0xb5735000 type 0 TID 1296 waking up
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  276): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  276): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  857): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  857): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1750): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1750): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 2074): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2074): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1999): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1999): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem(  276): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  276): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  857): ioConfigChanged() event 0, ioHandle 6
,V/AudioSystem( 1750): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1750): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 1999): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1999): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 2074): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2074): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  276): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  276): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 2074): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2074): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1371): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1371): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1371): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1371): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1371): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1371): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1999): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1933): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1933): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1933): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1933): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  857): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1750): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1750): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1933): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1933): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1999): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/ToneGenerator( 1999): Create Track: 0xb4909480
V/AudioTrack( 1999): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioSystem(  857): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  857): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3079): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3079): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3079): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3079): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3079): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3079): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 1999): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
I/AudioFlinger(  276): isAudioPlaybackHookOn() false
D/AudioTrack( 1999): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  276): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  276): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  276): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  276): getOutput() returns output 2
V/AudioSystem( 1999): getLatency() output 2, latency 50
V/AudioSystem( 1999): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1999): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1999): Create normal PCM 0x1 Track
V/AudioFlinger(  276): createTrack() lSessionId: 22
V/AudioFlinger(  276): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1999): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1999): Flags here  0x4 
V/AudioTrack( 1999): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  276): acquiring 22 from 1999, for 1999
V/AudioFlinger(  276):  added new entry for 22
V/ToneGenerator( 1999): ToneGenerator INIT OK, time: 96565
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb5651000
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
D/HeadsetStateMachine( 1999): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1999): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1999): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1999): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  276): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1999
D/BluetoothA2dp(  857): Proxy object connected
D/BluetoothAdapterService( 1999): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1999): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1999): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1999): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(722961412)( 1999): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
D/A2dpService( 1999): Received start request. Starting profile...
D/audio_hw_primary(  276): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  276): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  276): platform_set_parameters: enter: bt_samplerate=8000
I/BluetoothAvrcpServiceJni( 1999): classInitNative: succeeds
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
V/Avrcp   ( 1999): make
D/Avrcp   ( 1999): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1999): get_profile_interface avrcp
V/LGMDMManager( 1999): Create singleton instance
I/bt-btif ( 1999): btif_rc_get_interface
I/bt-btif ( 1999): ## init ##
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
I/LGBluetoothAvrcpServiceJni( 1999): classInitNative: succeeds
I/LGBluetoothAvrcpAdapter( 1999): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1999): initNative: succeeds
I/BluetoothAvrcpBrcmAdapterJni( 1999): classInitBrcmNative
,I/BluetoothAvrcpBrcmAdapterJni( 1999): initBrcmNative
I/BluetoothAdapterState( 1999): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/ToneGenerator( 1999): ToneGenerator destructor
V/ToneGenerator( 1999): stopTone
V/ToneGenerator( 1999): Delete Track: 0xb4909480
V/AudioTrack( 1999): ~AudioTrack, releasing session id from 1999 on behalf of 1999
V/AudioFlinger(  276): remove track (4099) and delete from mixer
V/AudioPolicyService(  276): AudioCommandThread() adding release output 2
V/AudioFlinger(  276): releasing 22 from 1999 for 1999
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/AudioPolicyService(  276): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  276): releaseOutput() 2
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
,V/AudioFlinger(  276): PlaybackThread::Track destructor
V/AudioFlinger(  276): removeClient_l() pid 1999, calling pid 276
W/ResourcesManager( 5536): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5536): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5536): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5536): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5536): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/AudioService(  857): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
E/AudioService(  857): No RCC entry present to update
,E/RemoteController( 1999): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1999): classInitNative
I/BluetoothA2dpServiceJni( 1999): classInitNative: succeeds
D/A2dpStateMachine( 1999): make
I/bluedroid( 1999): get_profile_interface a2dp
I/bt-btif ( 1999): btif_av_get_src_interface
I/bt-btif ( 1999): init
D/bt-btif ( 1999): btif_enable_service: current services:0xa0628330
I/LGBluetoothA2dpServiceJni( 1999): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1999): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1999): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1999): [BTUI] init
D/LGBluetoothPowerControlManager( 1999): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  857): Message: 30
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
D/A2dpStateMachine( 1999): Enter Disconnected: -2
I/BluetoothHidServiceJni( 1999): classInitNative: succeeds
,D/HidService( 1999): Received start request. Starting profile...
I/bluedroid( 1999): get_profile_interface hidhost
I/bt-btif ( 1999): btif_hh_get_interface
I/bt-btif ( 1999): init
D/bt-btif ( 1999): btif_enable_service: current services:0xa0628330
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
I/BluetoothHealthServiceJni( 1999): classInitNative: succeeds
D/HealthService( 1999): Received start request. Starting profile...
I/bluedroid( 1999): get_profile_interface health
I/bt-btif ( 1999): btif_hl_get_interface
I/bt-btif ( 1999): init
D/bt-btif ( 1999): Process name (droid.bluetooth)
D/bt-btif ( 1999): btif_hl_soc_thread_init
D/bt-btif ( 1999): create_thread: entered
D/bt-btif ( 1999): create_thread: thread created successfully
D/bt-btif ( 1999): entered btif_hl_select_thread
D/bt-btif ( 1999): btif_hl_select_wakeup_init
D/bt-btif ( 1999): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1999): max_s=55 
D/bt-btif ( 1999): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1999): classInitNative: succeeds
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
I/IndexDatabaseHelper( 5536): Using schema version: 115
I/BluetoothPanServiceJni( 1999): classInitNative(L105): succeeds
I/IndexDatabaseHelper( 5536): Index is fine
,D/PanService( 1999): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1999): initializeNative(L110): pan
I/bluedroid( 1999): get_profile_interface pan
D/bt-btif ( 1999): stack_initialized = 0, btpan_cb.enabled:0
I/LGBluetoothPanAdapter( 1999): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
I/BtGatt.JNI( 1999): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 1999): handleDebugAction() action=null
,D/BtGatt.GattService( 1999): Received start request. Starting profile...
D/BtGatt.GattService( 1999): start()
I/bluedroid( 1999): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1999): advertise manager created
I/LGBluetoothGattAdapter( 1999): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1999): setGattService:  set to: null
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
I/LGBluetoothMapAdapter( 1999): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1999): BluetoothMapBinder()
,D/BluetoothMapService( 1999): Received start request. Starting profile...
D/BluetoothMapService( 1999): start()
D/BluetoothMapEmailSettingsLoader( 1999): Found 0 applications
D/BluetoothMapEmailAppObserver( 1999): createReceiver()
D/BluetoothMapEmailAppObserver( 1999): initObservers()
D/BluetoothMapEmailAppObserver( 1999): getEnabledAccountItems()
,D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
D/HeadsetStateMachine( 1999): Proxy object connected
D/LGBluetoothHfpAdapter( 1999): [BTUI] queryPhoneState
I/BluetoothSAPServiceJni( 1999): classInitNative(L170): succeeds
D/SapService( 1999): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1999): initializeNative(L175): sap
I/bluedroid( 1999): get_profile_interface sap
I/bt-btif ( 1999): btif_sc_get_interface
I/bt-btif ( 1999): init
D/bt-btif ( 1999): btif_enable_service: current services:0xa0628330
I/LGBluetoothSapAdapter( 1999): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1999): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1999): [BTUI] initSapManager
,D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
D/LgeBluetoothSimManager( 1750): [BTUI] SAP_ENABLE_EVT
V/BluetoothFTPServiceJni( 1999): classInitNative
I/BluetoothFTPServiceJni( 1999): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
D/BluetoothFTPService( 1999): BluetoothFtpBinder()
,D/**BluetoothFTPService( 1999): Received start request. Starting profile...
V/BluetoothFTPService( 1999): FTP-Server Service start
D/BluetoothFTPServiceJni( 1999): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1999): get_profile_interface ftp
I/bt-btif ( 1999): btif_fts_get_interface
I/bt-btif ( 1999): init
D/bt-btif ( 1999): btif_enable_service: current services:0xa0628330
D/BluetoothFTPServiceJni( 1999): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
D/LGBluetoothFeatureConfig( 1999): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1999): classInitNative
D/HeadsetPhoneState( 1999): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/BluetoothOPPServiceJni( 1999): classInitNative(L373): succeeds
D/HeadsetStateMachine( 1999): Disconnected process message: 11, size: 0
V/OppService( 1999): Opp initBinder
D/**OppService( 1999): Received start request. Starting profile...
D/OppService( 1999): Starting OppService 
D/LGBluetoothOppAdapter( 1999): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,I/NotificationManager( 1999): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 1999): send message
D/BluetoothOppPreference( 1999): Dumping Names:  
D/BluetoothOppPreference( 1999): {}
D/BluetoothOppPreference( 1999): Dumping Channels:  
D/BluetoothOppPreference( 1999): {}
,D/OppService( 1999): Start()
W/BluetoothOPPServiceJni( 1999): initOppNative
D/BluetoothOPPServiceJni( 1999): initOppNative(L383): OPP
I/bluedroid( 1999): get_profile_interface opp
I/bt-btif ( 1999): btif_op_get_interface
D/BluetoothOPPServiceJni( 1999): initOppNative(L411): mOppCallbacksObj 5244154
D/BluetoothOPPServiceJni( 1999): initOppNative(L413): calling OPP init
V/OppService( 1999): Deleted complete outbound shares, number =  0
I/bt-btif ( 1999): btif_opp_init
D/bt-btif ( 1999): btif_enable_service: current services:0xa0628330
V/OppService( 1999): Deleted complete inbound failed shares, number = 0
D/BluetoothOPPServiceJni( 1999): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1999): initOppNative(L430): mOppCallbacksObj 5244154
V/OppService( 1999): setOppService(): set to: com.broadcom.bt.service.opp.OppService@39a2df18
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
,D/BluetoothA2dp( 1999): Proxy object connected
D/LGBluetoothPowerControlManager( 1999): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@ee27d71
V/BluetoothOppProvider( 1999): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1999): pendingUpdate is :  true
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@f0e0756 on behalf of 
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@31b983d7 on behalf of 
D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1999): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppNotification( 1999): update too frequent, put in queue
D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1999): Handler(): got msg=1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
V/OppService( 1999): pendingUpdate is :  false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
E/OppService( 1999): UpdateThread is Completed
D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(7229614,12)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1999): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1999): new notify threadi!
V/BluetoothOppNotification( 1999): send delay message
V/OppService( 1999): ContentObserver received notification
V/OppService( 1999): ContentObserver received notification
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - Message: 1
D/BluetoothAdapterService(722961412)( 1999): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1999): isTurningOnRadio()=false
,D/BluetoothAdapterState( 1999): isTurningOffRadio()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1999): isQuietModeServiceTurningOff()=false
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1999): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(722961412)( 1999): onProfileServiceStateChange() - All profile services started.
D/BluetoothAdapterState( 1999): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1999): enable
I/bt-btif ( 1999): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1999): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/OppService( 1999): pendingUpdate is :  true
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@172d4c4 on behalf of 
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@2e507fad on behalf of 
I/GKI_LINUX( 1999): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1999): btu_task pending for preload complete event
V/BluetoothOppNotification( 1999): mUpdateCompleteNotification = true
I/bt_hci_bdroid( 1999): init
I/bt_vendor( 1999): init
V/OppService( 1999): pendingUpdate is :  false
I/bt_vnd_conf( 1999): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
E/OppService( 1999): UpdateThread is Completed
I/bt_vnd_conf( 1999): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1999): libbt-hci init returns 0
,V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@2bfb42e2 on behalf of 
V/BluetoothOppNotification( 1999): outbound: succ-0  fail-0
I/NotificationManager( 1999): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1999): outbound notification was removed.
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothPbapReceiver( 1999): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1999): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@25288673 on behalf of 
V/BluetoothPbapReceiver( 1999): ***********state = 11
V/BluetoothOppNotification( 1999): inbound: succ-0  fail-0
I/NotificationManager( 1999): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
,V/BluetoothOppNotification( 1999): inbound notification was removed.
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@1b2a7930 on behalf of 
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/bt_userial_vendor( 1999): userial vendor open: opening /dev/ttyHS99
D/WiFiOffLoadUpdatePriority( 5536): remove : truetruefalse
D/bt_userial_vendor( 1999): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1999): device fd = 70 open
D/WiFiOffLoadUpdatePriority( 5536): remove2
V/WiFiOffLoadSharedPrefsUtils( 5536): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5536): save remove
D/WiFiOffLoadBroadcast( 5536): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5536): S: false, R: true
D/bt_hwcfg( 1999): hw_config_cback opcode:0x0c03
,D/bt_hwcfg( 1999): hw_config_cback state=1
D/bt_hwcfg( 1999): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1999): hw_config_cback state=4
,D/bt_hwcfg( 1999): Chipset Name: BCM4334B0
D/bt_hwcfg( 1999): Chipset BCM4334B0
D/bt_hwcfg( 1999): Target name = [BCM4334B0]
I/bt_hwcfg( 1999): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1999): hw_config_cback state=2
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1999): hw_config_cback state=3
I/bt_hwcfg( 1999): bt vendor lib: set UART baud 4000000
I/ActivityManager(  857): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5579 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1999): hw_config_cback state=5
,D/BluetoothPermissionRequest( 5536): onReceive
,D/LGBluetoothFeatureConfig( 5536):  get() - isFeatureLoaded : false
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/BluetoothManagerService(  857): Message: 20
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e59c1d6:true
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/Tethering(  857): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
V/BluetoothSapReceiver( 1999): [BTUI] checkServiceStart
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 1999): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
E/wpa_supplicant( 5535): USIM:  scard_init function
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/wpa_supplicant( 5535): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/Netd    (  272): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/Netd    (  272): M: Get netlink event, ifname: p2p0 action: 9
I/Netd    (  272): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/ActivityManager(  857): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5599 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/PCSuite ( 5579): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/ActivityManager(  857): Process com.lge.qremote (pid 4976) has died
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/UEI.SmartControl( 4671): Service.onUnbind: IControl
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/UEI.SmartControl( 4671): Service.onDestroy
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/UEI.SmartControl( 4671): Shutdown IRRCPlayer... 
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
W/irrc_jni( 4671): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4671): ~IrrcClient ++ 
D/irrcClient( 4671): ~IrrcClient -- 
W/irrc_jni( 4671): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4671): Blaster closed
D/UEI.SmartControl( 4671): Blaster closed
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/UEI.SmartControl( 4671): Shut down QS...
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/UEI.SmartControl( 4671): Stopped file observer...
I/UEI.SmartControl( 4671): QS lib stop result = true
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/UsbSettingsReceiver( 5536): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5536): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5536): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5536): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/wpa_supplicant( 5535): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,D/UEI.SmartControl( 4671): QS shutdown complete
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/UsbSettingsReceiver( 5536): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/wpa_supplicant( 5535): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WifiStateMachine(  857): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  857): setPowerSaveActivated(false)
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/WifiServerServiceExt(  857): WIFI_STATE_CHANGED_ACTION [3]
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:30.866 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/WifiServerServiceExt(  857): batteryPsActivateMsgHandler : state:0 event:3
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
E/WifiServerServiceExt(  857): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/UsbSettingsControl( 5536): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 5536): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5536): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5536): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5536): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5536): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/UsbSettingsControl( 5536): [AUTORUN] setTetherStatus() : status=false
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5536): remove : truetruetrue
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
W/ResourcesManager( 5599): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
E/WifiConfigStore(  857): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/WifiStateMachine(  857): enableVerboseLogging : level 2
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WifiStateMachine(  857): Setting OUI to DA-A1-19
D/WifiNative-HAL(  857): Setting external_sim to 1
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
W/Settings( 5052): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WfdsService( 1804): Supplicant Connection state is changed : true
D/WfdsService( 1804): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WfdsService( 1804): Set the WFDS Monitor: true
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/WifiNative-HAL(  857): startHal
E/wifi    (  857): getStaticLongField sWifiHalHandle 0x9b4488ec
D/WfdsMonitor( 1804): WfdsMonitorThread create
I/WifiHAL (  857): Initializing wifi
I/WifiHAL (  857): Creating socket
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WfdsMonitor( 1804): WFDS Monitor is created and started
D/WfdsService( 1804): WiFi: Supplicant connection re-established
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/WifiHAL (  857): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  857): Did set static halHandle = 0xb0679200
D/wifi    (  857): halHandle = 0xb0679200, mVM = 0xb487c280, mCls = 0x901b32
E/wifi    (  857): getStaticLongField sWifiHalHandle 0x9b44889c
D/wifi    (  857): array field set
I/WifiNative-HAL(  857): interface[0] = wlan0
I/WifiNative-HAL(  857): interface[1] = p2p0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
E/CtrlSupplicant( 1804): Access OK "@android:wpa_wlan0"
D/wifi    (  857): setting scan oui 0x9a0db778
D/WifiHAL (  857): Sending mac address OUI
E/WifiHAL (  857): failed to set scanning mac OUI; result = -95
E/CtrlSupplicant( 1804): Succeed to open control connection
D/WifiStateMachine(  857): Setting OUI to DA-A1-19
I/WifiNative-HAL(  857): startHal
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/wifi    (  857): setting scan oui 0x9a0db778
D/WifiHAL (  857): Sending mac address OUI
E/WifiHAL (  857): failed to set scanning mac OUI; result = -95
E/CtrlSupplicant( 1804): Succeed to open monitor connection
I/WifiNative-HAL(  857): Waiting for HAL events mWifiHalHandle=-1335389696
D/wifi    (  857): waitForHalEvents called, vm = 0xb487c280, obj = 0x901b32, env = 0xb0645f20
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
E/wifi    (  857): getStaticLongField sWifiHalHandle 0x9914cb2c
D/WfdsMonitor( 1804): Supplicant connection established
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WfdsService( 1804): Connected to the supplicant for wfds
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WifiHS20(  857): hidePasspointNotification off =false
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:30.948 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5599): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/LGWifiP2pService(  857): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/CommandListener(  272): Setting iface cfg
D/CommandListener(  272): Trying to bring up p2p0
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
I/WifiServerServiceExt(  857): set CMD_ADD_DEFAULT_PROFILE
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WifiMonitor(  857): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  857): P2pEnablingState
D/LGWifiP2pService(  857): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/LGWifiP2pService(  857): P2p socket connection successful
D/bt_hwcfg( 1999): hw_config_cback state=6
D/LGWifiP2pService(  857): P2pEnabledState
I/WifiServerServiceExt(  857): setWifiDualbandAPConnection band : 1
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WifiScanningService(  857): SCAN_AVAILABLE : 3
D/RttService(  857): SCAN_AVAILABLE : 3
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/AuthorizationBluetoothService( 1730): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/WifiScanningService(  857): DefaultState got{ when=-5ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 5535): nWIFIDualbandAPConnection: 1
I/WifiNative-HAL(  857): startHal
D/RttService(  857): DefaultState got{ when=-4ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/WifiServerServiceExt(  857): set CMD_DISCONNECT_RSSI_LVL : -100
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
E/wpa_supplicant( 5535): disconnect_rssi_lvl: -100
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/LGWifiP2pService(  857): [LGE_P2P] initializeP2pSettings() check postfix
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/LGWifiP2pService(  857): before postfix = G3s-1
D/WifiServerServiceExt(  857): postfix byte check : 5
D/LGWifiP2pService(  857): after postfix = G3s-1
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
I/WifiServerServiceExt(  857): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5535): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
I/WifiServerServiceExt(  857): set CMD_UPDATE_DEFAULT_PROFILE
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/wifi    (  857): getting scan capabilities on interface[0] = 0x9a0db778
D/WifiHAL (  857): Creating message to get scan capablities; iface = 24
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1999): hw_config_cback state=6
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1999): hw_config_cback state=6
I/wpa_supplicant( 5535): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/wifi    (  857): failed to get capabilities : -95
E/WifiScanningService(  857): could not get scan capabilities
,I/wpa_supplicant( 5535): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-HAL(  857): p2pGetDeviceAddress
,D/WifiNative-HAL(  857): p2pGetDeviceAddress returning a2:39:f7:70:12:80
D/LGWifiP2pService(  857): DeviceAddress: a2:39:f7:70:12:80
D/WfdsService( 1804): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,D/WfdsService( 1804): Update P2p Interface State: 3
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:31.047 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/LGWifiP2pService(  857): sending p2p persistent groups changed broadcast
,D/LGWifiP2pService(  857): sending p2p connection changed broadcast
D/LGWifiP2pService(  857): InactiveState
D/LGWifiP2pService(  857): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5535): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/LGWifiP2pService(  857): InactiveState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): DefaultState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1804): WifiP2pState is changed : true
D/WfdsService( 1804): Receive the WFDS_ENABLE Method
D/WfdsService( 1804): Set the WFDS Monitor: true
D/WfdsService( 1804): Connected to the supplicant for wfds
D/WfdsJNI ( 1804): doCommand: WFDS_SET TRUE
D/WfdsService( 1804): WIFI_P2P_CONNECTION_CHANGED_ACTION
E/WifiServerServiceExt(  857): No p2p device connected
D/LGWifiP2pService(  857): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1804): isConnected: false
D/LGWifiP2pService(  857): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1804): GroupInfoAvailable: mGroupInfo is null
,I/bt_hwcfg( 1999): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1999): Settlement delay -- 100 ms
I/bt_hwcfg( 1999): Setting fw settlement delay to 100 
I/wpa_supplicant( 5535): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1804): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5535): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1804): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5535): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WiFiOffLoadUpdatePriority( 5536): remove1
V/WiFiOffLoadSharedPrefsUtils( 5536): save remove
D/WfdsJNI ( 1804): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1804): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1804): selectPreferredScanChannel [6]
D/WfdsService( 1804): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
W/WfdsService( 1804): DefaultState - msg [9441285] is not handled
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:31.107 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LocSvc_java(  857): onReceive
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 5535): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5535): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:31.116 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateSCANNING
D/WiFiOffLoadBroadcast( 5536): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5536): S: false, R: false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:31.128 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/GONS    ( 1750): GONS isTestMode: false Country: 
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:31.13 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension(  857): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,I/WifiServerServiceExt(  857): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  857): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  857): setSecurityType  : 2
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:31.182 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:31.19 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1999): hw_config_cback state=2
D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1999): hw_config_cback state=7
I/bt_hwcfg( 1999): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1999): Setting local bd addr to F8:95:C7:87:85:54
D/WifiExtManager(  857): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@1ebc82e3
D/ConnectivityService(  857): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  857): Got NetworkAgent Messenger
D/ConnectivityService(  857): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  857): NetworkAgent connected
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  857): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  857): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/bt_hwcfg( 1999): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1999): hw_config_cback state=8
I/bt_hwcfg( 1999): vendor lib fwcfg completed
I/bt-btif ( 1999): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1999): btu_task received preload complete event
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  272): Setting iface cfg
I/        ( 1999): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1999): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1999): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1999): BTE_InitTraceLevels -- TRC_PROTOCOL,0
,D/DhcpStateMachine(  857): StoppedState
E/WifiStateMachine(  857): Start Dhcp Watchdog 1
D/DhcpStateMachine(  857): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  857): WaitBeforeStartState
D/WiFiOffLoadUpdatePriority( 5536): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5536): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5536): private wpa: "NG700" 300
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateASSOCIATED
D/WifiServiceImplEx(  857): addOrUpdateNetwork pid=5536, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  857):  uid = 1000 SSID "NG700" nid=0
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateGROUP_HANDSHAKE
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:31.26 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  857): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/LGWifiP2pService(  857): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2d83230e target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  857): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2d83230e target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  857): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  857): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  857): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  857): DHCP Start wake lock is acquired.
I/ActivityManager(  857): Killing 5180:com.google.android.apps.plus/u0a86 (adj 15): empty #11
V/LgDhcpStateMachineHelper(  857): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  857): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
E/bt-btif ( 1999): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 1999): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1999): warning : media task started media_task_refcnt 1 
E/bt-btif ( 1999): Calling BTA_HhEnable
D/BT_PROF_AUDIO( 1999): created moving average (N=100)
D/BT_PROF_AUDIO( 1999): reset rate average
W/bt-btif ( 1999): overflow 0, enter 0, exit 0
E/bt-btif ( 1999): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1999): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1999): Address is:F8:95:C7:87:85:54
W/bt-smp  ( 1999): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1999): Plain text(LSB ~ MSB) = 45 99 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1999): Encrypted text(LSB ~ MSB) = 08 d3 0c 1c ec f5 e9 e2 a7 76 7f 65 58 b1 59 1a 
W/bt-btm  ( 1999): Stopping oneshot timer
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateCOMPLETED
,V/BluetoothOppNotification( 1999): new notify threadi!
V/BluetoothOppNotification( 1999): send delay message
W/libprocessgroup(  857): failed to open /acct/uid_10086/pid_5180/cgroup.procs: No such file or directory
D/BluetoothAdapterProperties( 1999): Name is: G3s-1
D/BluetoothManagerService(  857): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  857): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1999): Scan Mode:20
D/BluetoothAdapterProperties( 1999): Discoverable Timeout:120
D/WifiServerServiceExt(  857): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  857): setSupplicantStateCOMPLETED
E/WifiConfigStore(  857):  key="NG700"WPA_PSK netId=0 uid=0/1000
E/bt-btif ( 1999): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1999): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1999): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1999): BTA_JvEnable
E/bt-btif ( 1999): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1999): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1999): init_hci_slots(L136): in
D/IOP_DB_BT( 1999): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1999): db_open: db_open : handle 2690852828l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1999): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1999): db_query: result 1
I/        ( 1999): iop_db_open: iop_db_open status 0
E/bt-btif ( 1999): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1999): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1999): bta_pan_co_init
D/bte_conf( 1999): Device ID record 1 : primary
D/bte_conf( 1999):   vendorId            = 00c4
D/bte_conf( 1999):   vendorIdSource      = 0001
D/bte_conf( 1999):   product             = 13a1
D/bte_conf( 1999):   version             = 1000
D/bte_conf( 1999):   clientExecutableURL = 
D/bte_conf( 1999):   serviceDescription  = 
D/bte_conf( 1999):   documentationURL    = 
D/bte_conf( 1999): bte_load_did_conf no section named DID2.
I/bt-btif ( 1999): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1999): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1999): ScanMode =  20
D/BluetoothAdapterProperties( 1999): State =  11
,D/BluetoothAdapterProperties( 1999): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1999): Setting state to 12
I/BluetoothAdapterState( 1999): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(722961412)( 1999): updateAdapterState() - Broadcasting state to 1 receivers.
E/bt-btif ( 1999): btif_hf_upstreams_evt: wrong handle = 8240 
I/bt-btif ( 1999): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1999): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 1999): onOpcStateChange()
D/BluetoothManagerService(  857): Message: 60
D/BluetoothManagerService(  857): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/OppService( 1999): Recieved MESSAGE_OPC_ENABLE
D/BluetoothManagerService(  857): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/bt-btif ( 1999): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1999): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 1999): onOpsStateChange() :0
I/bt-btif ( 1999): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1999): operation_cmpl_callback(L192):  oper:3 status:0
D/BluetoothHeadset( 1750): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 1999): Entering On State
I/BluetoothAdapterState( 1999): Entering On State from state = 11
D/LGBluetoothFeatureConfig( 1999): isPrivacyLogsEnabled : true
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothAdapterService(722961412)( 1999): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(722961412)( 1999): autoConnect() - Initiate auto connection on BT on...
I/BluetoothFTPService( 1999): onFtpServerEnabled: /storage
D/BluetoothAdapterService( 1999): [BTUI] autoConnect() : not allowed
D/OppService( 1999): Recieved MESSAGE_OPS_ENABLE
D/BluetoothHeadset( 1750): onBluetoothStateChange: up=true
D/BluetoothPanServiceJni( 1999): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothHeadset(  857): onBluetoothStateChange: up=true
I/bt-btif ( 1999): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothA2dp(  857): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 1999): Scan Mode:21
I/bt-btif ( 1999): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1999): Discoverable Timeout:120
D/BluetoothA2dp( 1999): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 1999): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1999): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1999): [BTUI]         local_name: G3s-1
D/BluetoothHeadset( 1750): onBluetoothStateChange: up=true
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothAdapterService(722961412)( 1999): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(722961412)( 1999): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1999): [BTUI] autoConnect() : not allowed
E/BluetoothManagerService(  857): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  857): Bluetooth State Change Intent: 11 -> 12
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/BluetoothManagerService(  857): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  857): Message: 40
D/BluetoothManagerService(  857): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1804): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@2d2269a9 on behalf ,of 
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
I/BluetoothMapService( 1999): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1999): STATE_ON
D/LGBluetoothAPIService( 1804): Message: 1
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1371): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/LGBluetoothAPIService( 1804): MESSAGE_BOOT_COMPLETED
D/bt_h4   ( 1999): vendor lib postload completed
I/LGBluetoothAPIService( 1804): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService( 1999): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b178404
,V/BluetoothOppNotification( 1999): mUpdateCompleteNotification = true
V/BluetoothPbapService( 1999): Pbap Service onCreate
V/BluetoothPbapService( 1999): Starting PBAP service
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/LGBluetoothPbapAdapter( 1999): [BTUI] getInstance : create
V/BluetoothPbapService( 1999): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1999): state: 12
V/BluetoothMapService( 1999): Handler(): got msg=1
D/BluetoothMapMasInstance( 1999): Map Service startRfcommSocketListener
D/LGBluetoothAPIServer( 1999): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1999): [BTUI] onBind()
V/BluetoothPbapService( 1999): Handler(): got msg=1
D/LGBluetoothAPIService( 1804): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothPbapService( 1999): Pbap Service startRfcommSocketListener
D/LGBluetoothAPIService( 1804): Message: 100
D/LGBluetoothAPIService( 1804): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothMapMasInstance( 1999): MAS initSocket()
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@2d75f85c on behalf of 
V/BluetoothOppNotification( 1999): outbound: succ-0  fail-0
,D/BluetoothMapMasInstance( 1999):   masId = 00
D/BluetoothMapMasInstance( 1999):   msgTypes = 0e
D/BluetoothMapMasInstance( 1999):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1999):   SDP string = 000eSMS/MMS
I/NotificationManager( 1999): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1999): outbound notification was removed.
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothPbapService( 1999): Pbap Service initSocket
D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiConfigStore(  857): Setting BSSID for "NG700"WPA_PSK to any
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@ef765 on behalf of 
V/BluetoothOppNotification( 1999): inbound: succ-0  fail-0
W/BluetoothAdapter( 1999): getBluetoothService() called with no BluetoothManagerCallback
I/NotificationManager( 1999): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
,V/BluetoothOppNotification( 1999): inbound notification was removed.
W/BluetoothAdapter( 1999): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 1999): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
I/bt-btif ( 1999): BTA_JvCreateRecordByUser
I/bt-btif ( 1999): BTA_JvCreateRecordByUser
I/bt-btif ( 1999): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1999): [BTUI] createSocketChannel FD=83 mFd=0
I/bt-btif ( 1999): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1999): [BTUI] createSocketChannel FD=85 mFd=83
V/BluetoothPbapService( 1999): Succeed to create listening socket 
V/BluetoothMapMasInstance( 1999): Succeed to create listening socket 
V/BluetoothPbapService( 1999): Accepting socket connection...
D/BluetoothMapMasInstance( 1999): Accepting socket connection...
V/BluetoothOppProvider( 1999): created cursor android.database.sqlite.SQLiteCursor@12de4c3a on behalf of 
D/WiFiOffLoadUpdatePriority( 5536):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5536): configuration updated: 0
I/WifiServerServiceExt(  857): set CMD_UPDATE_DEFAULT_PROFILE
,D/WiFiOffLoadUpdatePriority( 5536): configuration saved: true
,D/PCSuite ( 5579): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 5536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/DhcpStateMachine(  857): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  857): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  857): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  857): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5637 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/dhcpcd  ( 5642): version 5.5.6 starting
,E/dhcpcd  ( 5642): get_duid: Read-only file system
V/BluetoothPbapReceiver( 1999): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1999): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1999): ***********state = 12
,I/dhcpcd  ( 5642): wlan0: rebinding lease of 192.168.1.134
,D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/LocalBluetoothProfileManager( 5536): Adding local A2DP profile
D/BluetoothManagerService(  857): Message: 30
D/LocalBluetoothProfileManager( 5536): Adding local HEADSET profile
D/BluetoothManagerService(  857): Message: 30
,D/BluetoothManagerService(  857): Message: 30
D/BluetoothManagerService(  857): Message: 30
,D/LocalBluetoothProfileManager( 5536): Adding local MAP profile
D/BluetoothMap( 5536): Create BluetoothMap proxy object
D/BluetoothManagerService(  857): Message: 30
D/BluetoothManagerService(  857): Message: 30
,D/LocalBluetoothProfileManager( 5536): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 1999): Pbap Service onBind
D/LGBluetoothUserBindClient( 5536): [BTUI] initUserBindClient
W/ContextImpl( 5536): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/CAR.SERVICE( 5477): mConnectedToCar = false, abort
D/DockEventReceiver( 5536): finishStartingService: stopping service
D/BluetoothA2dp( 5536): Proxy object connected
D/A2dpProfile( 5536): Bluetooth service connected
,D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothHeadset( 5536): Proxy object connected
D/HeadsetProfile( 5536): Bluetooth service connected
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothInputDevice( 5536): Proxy object connected
D/HidProfile( 5536): Bluetooth service connected
I/dhcpcd  ( 5642): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothPan( 5536): BluetoothPAN Proxy object connected
E/ActivityThread( 5477): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@239e0039 that was originally bound here
E/ActivityThread( 5477): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@239e0039 that was originally bound here
E/ActivityThread( 5477): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5477): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5477): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5477): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5477): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5477): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5477): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5477): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5477): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5477): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5477): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5477): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5477): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5477): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5477): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5477): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5477): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5477): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5477): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5477): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5477): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5477): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5477): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/PanProfile( 5536): Bluetooth service connected
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
,D/BluetoothMap( 5536): Proxy object connected
D/MapProfile( 5536): Bluetooth service connected
D/BluetoothMap( 5536): getConnectedDevices()
E/ActivityThread( 5477): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@39a2df18 that was originally bound here
E/ActivityThread( 5477): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@39a2df18 that was originally bound here
E/ActivityThread( 5477): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5477): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5477): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5477): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5477): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5477): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5477): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5477): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5477): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5477): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5477): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5477): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5477): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5477): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5477): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5477): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5477): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5477): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5477): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5477): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5477): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5477): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  857): Unbind failed: could not find connection for android.os.BinderProxy@3c84f57a
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
V/BluetoothMapService( 1999): getConnectedDevices()
D/BluetoothPbap( 5536): Proxy object connected
D/PbapServerProfile( 5536): Bluetooth service connected
D/LGBluetoothUserBindClient( 5536): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5536): onReceive
,D/LGBluetoothFeatureConfig( 5536): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5536): [BTUI] FileNotFound: readProperty
I/ActivityManager(  857): Killing 4671:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/dhcpcd  ( 5642): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  857): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/Netd    (  272): M: Get netlink event, ifname: p2p0 action: 6
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/BluetoothOppReceiver( 1999): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,W/libprocessgroup(  857): failed to open /acct/uid_10089/pid_4671/cgroup.procs: No such file or directory
D/LGDMClient( 5637): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5637): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/BluetoothOppManager( 1999): restoreApplicationData! falsefalsenullnull
W/ContextImpl( 5637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,V/BluetoothSapReceiver( 1999): [BTUI] checkServiceStart
W/ContextImpl( 5637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGBluetoothStateChangeReceiver( 1999): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1730): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LGDMClient( 5637): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5637): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 5637): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
I/PCSuite ( 5579): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5579): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5579): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  857): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  857): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  857): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  857): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  857): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  857): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  857): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  857): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  857): RunningState
D/LGWifiP2pService(  857): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  857): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  857): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  857): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService(  857): ignoring duplicate network state non-change
I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5693 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  857): Killing 5321:com.android.calendar/u0a13 (adj 15): empty #11
,D/ConnectivityService(  857): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  857): Adding iface wlan0 to network 100
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/libprocessgroup(  857): failed to open /acct/uid_10013/pid_5321/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  857): [PASSPOINT] passpointNotification: hs20AP list is checked
,E/WifiStateMachine(  857): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  857): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService(  857): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  857): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
,D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  857): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:32.144 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:32.145 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:32.147 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:32.148 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  857): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  857): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  857): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  857): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  857): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,D/ConnectivityService(  857): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): Connected
D/ConnectivityService(  857):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  857):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityService(  857):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  857):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  857): currentScore = 0, newScore = 20
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  857):    accepting network in place of null
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  857): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/WIFI    (  857): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  857):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  857): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  857): Sending connected broadcast for type 1 Network,AgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  857): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/Tethering(  857): MasterInitialState.processMessage what=3
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
W/QCNEJ   ( 1840): |CORE| No family connected
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/ConnectivityService(  857): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  857): [e] list.add(nai) empty : false size: 1
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/ConnectivityService(  857): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
,D/ConnectivityService(  857): validation of new default Network = false
D/ConnectivityService(  857): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  857): enableDataServiceNotify 
D/DSQN    (  857): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] Start DNSResolver start to wait
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/DSQN    (  857): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] wait 500ms before dns check
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
,V/NetworkPolicy(  857): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  857): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/DSQN    ( 5714): DSQN samuel.seo ver 141203
E/DSQN    ( 5714): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5714): created command queue thread
I/DSQN    ( 5714): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5714): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityService(  857): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
W/ResourcesManager( 5693): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c68b9d2:true
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  857): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
D/ConnectivityService(  857): identical MTU - not setting
D/Nat464Xlat(  857): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  857): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  857): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  857): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  857): enableDataServiceNotify 
D/DSQN    (  857): start dsqn bin
I/ActivityManager(  857): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5720 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/DSQN    (  857): dsqn is running restart
,I/DSQN    ( 5726): DSQN samuel.seo ver 141203
E/DSQN    ( 5726): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 5726): created command queue thread
I/DSQN    ( 5726): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5726): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524295
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:32.461 DNS addrs= 192.168.1.1, 0.0.0.0, 
,V/[BNRBootReceiver]( 5720): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5720): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5720): Boot Receiver Return
,V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 5536): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
,I/ActivityManager(  857): Killing 5295:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10014/pid_5295/cgroup.procs: No such file or directory
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] DNSResolver start dns
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out(  857): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): Checking http://clients3.google.com/generate_204 on "NG700"
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
,I/DSQN    ( 5726): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5726): restart monitoring
D/LGDataListener(  272): argv[0]=dsqncommand
D/LGDataListener(  272): argv[1]=wlan0
D/LGDataListener(  272): argv[2]=1
D/LGDataListener(  272): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5726): dsqn report finish
D/DSQN    (  857): DSQM DsqnNotification wlan0  1
D/DSQN    (  857): start to monitor internet connection
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:36:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449750992802], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449750992784]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  857): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
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
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  857): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  857): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  857):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiDataContinuityService(  857): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  857): set CMD_CAPTIVE_CHECK_COMPLETED
,V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
I/PCSuite ( 5579): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5579): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5536): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5536): MCCMNC not supported: null
I/PCSuite ( 5579): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5579): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5748 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5693): Create singleton instance
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.282ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 20.161ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.759ms
,I/AudioManager( 5693): getMode name:com.lge.qremote
,V/AudioFlinger(  276): thread 0xb5735000 type 0 TID 1296 going to sleep
V/AudioFlinger(  276): thread 0xb56eb000 type 0 TID 1293 going to sleep
V/AudioFlinger(  276): thread 0xb5651000 type 0 TID 1292 going to sleep
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 5748): Quickset Services start...
I/UEI.SmartControl( 5748): Manufacture = LGE
,D/UEI.SmartControl( 5748): File observer start...
E/UEI.SmartControl( 5748): IR Port is disabled: false
D/UEI.SmartControl( 5748): Starting file observer...
D/UEI.SmartControl( 5748): Extracting JNI libs...
D/UEI.SmartControl( 5748): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 5748): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5748): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5748): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5748): --- Selecting new region: 2
I/UEI.SmartControl( 5748): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5748): Platform has CIR...
D/UEI.SmartControl( 5748): NO CIR support, need to check package...
I/UEI.SmartControl( 5748): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5748): QS Service created
E/UEI.SmartControl( 5748): QS start get config
,D/UEI.SmartControl( 5748): Loading JNI Libs...
,D/UEI.SmartControl( 5748):  configuring local db...
I/ActivityManager(  857): Process com.google.android.talk (pid 5052) has died
,D/UEI.SmartControl( 5748):  ---- Has DB8: true
D/UEI.SmartControl( 5748): QS start statue = true Error code = 0
D/UEI.SmartControl( 5748): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5748): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5748): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5748): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5748): IrrcClient ++ 
D/irrcClient( 5748): getIrrcService ++ 
,D/irrcClient( 5748): getIrrcService -- 
D/irrcClient( 5748): IrrcClient -- 
W/irrc_jni( 5748): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5748): Services init done
D/UEI.SmartControl( 5748): QS Service init finished
D/UEI.SmartControl( 5748): QS Service version name: 0.1.73
I/UEI.SmartControl( 5748): Device manager: loading config....
D/UEI.SmartControl( 5748): QS Service version code: 1073
D/UEI.SmartControl( 5748): Service requested: Control
,D/UEI.SmartControl( 5748): Config is loaded...
D/UEI.SmartControl( 5748): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5748): Internal service binding...
D/UEI.SmartControl( 5748): -----IControl: 11
D/UEI.SmartControl( 5748): Caller: com.lge.qremote
D/UEI.SmartControl( 5748): ------------ IControl registerCallback...
I/UEI.SmartControl( 5748): Registering callback...
D/UEI.SmartControl( 5748): -----IControl: 19
D/UEI.SmartControl( 5748): Caller: com.lge.qremote
D/UEI.SmartControl( 5748):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5748): Registering Services Ready callback...
,I/UEI.SmartControl( 5748): Notify client services are ready...
I/UEI.SmartControl( 5748): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5748): -----IControl: 8
D/UEI.SmartControl( 5748): Caller: com.lge.qremote
I/AudioManager( 5693): getMode name:com.lge.qremote
,I/ActivityManager(  857): Killing 4860:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_4860/cgroup.procs: No such file or directory
,I/AudioManager( 5693): getMode name:com.lge.qremote
I/AudioManager( 5693): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:34.266 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NotificationManager( 1933): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/WifiInternetCheck(  857): Single check msg out of sync, ignoring.
,D/ConnectivityService(  857): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  857): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  857): onReceive
D/LocSvc_java(  857): got connectivity action
D/LocSvc_java(  857): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  857): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  857): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  857): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  857): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  857): Sending msg: 5 arg1:0 arg2:1
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  857): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5803 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out(  857): propertyValue:false
I/System.out(  857): propertyValue:false
I/System.out(  857): propertyValue:false
D/LocSvc_java(  857): NTP server returned: 1449750995242 (Thu Dec 10 13:36:35 GMT+01:00 2015) reference: 101794 certainty: 10 system time offset: -81
,D/LocSvc_java(  857): Sending msg: 10 arg1:0 arg2:1
D/AlarmManagerService(  857): Setting time of day to sec=1449750995
W/AlarmManagerService(  857): Unable to set rtc to 1449750995: Invalid argument
I/ActivityManager(  857): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5821 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[SystemUI]Clock( 1371): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/WeatherService( 2683): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:36:35
,D/WeatherService( 2683): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/ActivityManager(  857): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5840 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/GpsLocationProvider(  857): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  857): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/WeatherService( 2683): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2683): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2683): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2683): 2 : Fixed theme : optimus
,W/ResourcesManager( 5821): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5821): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5821): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[LGHome]LGDateChangeReceiver( 1876): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=10 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
,I/ActivityManager(  857): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5863 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/WeatherReflect( 2683): 2 : Map key string is -2
D/lim     ( 2683): 2 : time = 13:36
,I/WeatherReflect( 2683): Model Name : LG-D722
,D/WeatherTheme( 2683): 2 : exactly same view!
D/WeatherTheme( 2683): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2683): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:36:35
I/ActivityManager(  857): Process com.android.vending (pid 4906) has died
I/[LGHome]LGCalendarIcon( 1876): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
,W/ResourcesManager( 5840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5840): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5840): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]LGCalendarIcon( 1876): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
I/GservicesProvider( 5863): Gservices pushing to system: true; secure/global: true
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/GoogleHttpClient( 5863): GMS http client unavailable, use old client
,I/ActivityManager(  857): Process com.google.android.gms:car (pid 5477) has died
,I/art     (  857): Explicit concurrent mark sweep GC freed 68495(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.526ms total 207.013ms
,E/GpsLocationProvider(  857): No APN found to select.
I/AppConfig( 5821): Total System Memory = 906309632
I/GalleryUtils( 5821): Application Heap = 96 MB
I/LGEmail ( 5840): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/AppConfig( 5821): App Tier : NOT_DEF
,D/SystemHelper( 5821): region [EU], country [EU], operator [OPEN], sub-operator []
D/LGEmail ( 5840): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/GoogleHttpClient( 5863): GMS http client unavailable, use old client
,D/LgeGpsConstants(  857): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
,I/NotificationManager(  857): android: cancelAsUser(-1597574061) by android
,I/MusicStore( 5803): Database version: 120
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out(  857): propertyValue:false
I/NotificationManager(  857): android: cancelAsUser(-1816247584) by android
,D/LgeGpsLocationProvider(  857): NTP server: europe.pool.ntp.org
,D/LgeGpsLocationProvider(  857): NTP server returned: 1449750996005 (Thu Dec 10 13:36:36 GMT+01:00 2015) reference: 102555 certainty: 20 system time offset: 4
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityThread( 5205): Failed to find provider info for com.android.contacts.metadata
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/SyncManager(  857): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37530, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  857): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 132859, reason: UserStart
,I/NotificationManager(  857): android: cancelAsUser(716319171) by android
E/Auth.Api.Credentials( 5205): [CredentialSyncAdapter] Unknown sync event.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5803): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/NotificationManager(  857): android: cancelAsUser(-591465577) by android
I/ActivityManager(  857): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5909 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out(  857): propertyValue:false
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  857): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  857): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out(  857): propertyValue:false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5803): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5803): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/WifiInternetCheck(  857): isHttpConnectionAvailable - We got a valid response : 204
D/ALBootInit( 5909): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 5909): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 5909): [setNextAlert] start
D/Alarms  ( 5909): [setNextAlert] (1)
,I/NotificationManager(  857): android: cancelAsUser(-1816247584) by android
D/Alarms  ( 5909):  minTime  = 0
D/Alarms  ( 5909):  -- OK multi -- 0
E/jeny.kim( 5909): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5909): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 5909): BUILD Operator: OPEN
,D/Alarms  ( 5909): broadcastToWidgetProvider : false
D/Alarms  ( 5909): Enter formatDayAndTime(final Context context, long timeInMiliSec)
I/NotificationManager(  857): android: cancelAsUser(-1597574061) by android
W/ResourcesManager( 5803): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5803): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/SettingsProvider(  857): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 5909): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 5909): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@24a6d496
V/DigitalAppWidgetProvider( 5909): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@24a6d496
D/QuickCoverProvider( 5909): onReceiver
V/JNIHelp ( 5803): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  857): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=5938 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 5803): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5803): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15bdae1d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5803): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5803): GMSCore installation verified
I/ActivityManager(  857): Process com.lge.lgdmsclient (pid 5637) has died
E/ConnectivityChangeReceiver( 5205): Ignoring connectivity change
,I/ConfigStore( 5803): Config Database version: 1
,W/ResourcesManager( 5938): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 5938): CalendarApplication.onCreate()
I/rmt_storage(  266): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  266): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  266): wakelock acquired: 1, error no: 42
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/ConnectivityService(  857): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  857): dumpNetworkRequest
D/ConnectivityService(  857):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  857):     Requests:
D/ConnectivityService(  857):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  857):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  857):     Lingered:
D/ConnectivityService(  857): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  857): apparently satisfied.  currentScore=60
D/ConnectivityService(  857): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5205): CM callback handler got msg 524290
,I/NotificationManager(  857): android: cancelAsUser(-591465577) by android
D/PreferenceKeysParser( 5938): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5938): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@244fd35, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@88425ca, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2803d33b, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@e9f1a58, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2bd537b1, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@24a6d496, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@31d26817, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2b178404, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@22549ded, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3873a422, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@198b6eb3, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2d8adc70, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@21ea2be9, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@294be06e, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@36c4430f, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@a994f9c, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@28309da5, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3f59957a, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1b0c012b, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3eb9c988, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@37b26f21, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@295b8f46, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@17c78507, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@14e5f634, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1725dc5d, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@313159d2, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@5cd6aa3, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2c0641a0, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@868e159, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2d27411e, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2ac20dff, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@271dd7cc, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@333d3a15, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3a02512a, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@18338b1b, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3436a4b8, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3fc46291, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@9cc55f6, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2075bdf7, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@160d5464, lg_preferences_alerts_vibratetype=com.a,ndroid.calendar.adaptation.PreferenceKey$KeyData@1cbb96cd, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@135fd
D/GeneralPreferenceUtils( 5938): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 5938): [init]
I/Config  ( 5938): LGCalendar ver.4.40.17
I/Config  ( 5938): start check model
I/Config  ( 5938): start check native_ca
I/Config  ( 5938): Config Operator=OPEN, Country=EU
D/Config  ( 5938): [setDefaultValuesToPref]
D/Config  ( 5938): [parseProfiles]
D/ProfilesParser( 5938): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5938): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5938): [updateProfiletoCountryInfo]
,D/GeneralPreference( 5938): [checkAndMigrateOldPreference]
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  266): 
I/rmt_storage(  266): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ActivityManager(  857): Process com.lge.bnr (pid 5720) has died
,I/ActivityManager(  857): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5960 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/AgendaWidgetManager( 5938): [updateWidgets] 
,I/InitNotificationRingtoneService( 5938): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5938): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5938): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
W/ResourcesManager( 5960): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,W/HolidayIntentService( 5938): onHandleIntent
D/MonthWidgetProvider( 5938): [onReceive]
,D/CalendarWidgetProvider( 5938): [onReceive]
D/CalendarWidgetProvider( 5938): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5938): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 5938): readJsonAsset : holiday.json
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/WeekWidgetProvider( 5938): [onReceive]
D/CalendarWidgetProvider( 5938): [onReceive]
D/CalendarWidgetProvider( 5938): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5938): [onUpdateAndInitCalendarTime]
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
D/WeatherAncestor( 2683): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:36:37
,D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
,D/Weather_cast( 2683): 2 : set auto-update time : 12/10 16:36
I/AlertUtils( 5938): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5938): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5938): set default noti to content://media/internal/audio/media/38
,D/WeatherAncestor( 2683): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:36:37
D/WeatherService( 2683): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
I/InitNotificationRingtoneService( 5938): End InitializeAlertRingtoneService.onHandleIntent
,E/HolidayIntentService( 5938): onHandleIntent:holiday data empty
,I/ActivityManager(  857): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5993 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/MediaRouter( 5803): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 5803): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/TimeService( 5993): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449750997457
D/        ( 5993): TimeServiceNative: User Time to be set is 1449750997457
D/QC-time-services( 5993): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5993): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5993): Lib:time_genoff_operation: pargs->ts_val = 1449750997457
D/QC-time-services( 5993): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  330): Daemon: Connection accepted:time_genoff
D/QC-time-services(  330): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449750997457
D/QC-time-services(  330): Daemon:genoff_opr: Base = 2, val = 1449750997457, operation = 0
D/QC-time-services(  330): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/22/70 16:38:24
D/QC-time-services(  330): Daemon:Value read from RTC seconds = 9650304000
D/QC-time-services(  330): Daemon:new time 1449750997457 
D/QC-time-services(  330): Daemon: delta 1440100693457 genoff 1440100693457 
D/QC-time-services(  330): Daemon:genoff_persistent_update: Writing genoff = 1440100693457 to memory
D/QC-time-services(  330): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  330): Daemon:time_persistent_memory_opr:Genoff write operation 
I/NetworkMonitor( 5803): type=WIFI subType= reason=null isConnected=true
,D/QC-time-services(  330): Updating the TOD offset
D/QC-time-services(  330): Daemon:genoff_persistent_update: Writing genoff = 1440100693457 to memory
D/QC-time-services(  330): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  330): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  330): Daemon:Update to modem bit set
E/QC-time-services( 5993): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  330): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  330): Daemon: Base = 2, Value being sent to MODEM = 1124135893457
E/QC-time-services(  330): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  330): Daemon: Time-services: Waiting to acceptconnection
,I/NetworkMonitor( 5803): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 5803): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5803): Using platform SSLCertificateSocketFactory
D/eas_req ( 5840): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/ActivityManager(  857): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6019 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  857): Explicit concurrent mark sweep GC freed 24019(1136KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.626ms total 184.152ms
,I/NotificationManager(  857): android: cancelAsUser(-1548111331) by android
I/CheckinService( 5205): Checkin interval check for package: unspecified last checkin: 1449748637924 min interval config: 0 actual interval: 2359819
,I/HubEmail( 5840): JNI_OnLoad()
I/HubEmail( 5840): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5840): registerNatives()
I/HubEmail( 5840): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5840): registerNativeMethods()
I/HubEmail( 5840): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 5840): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  857): Killing 5599:com.lge.settings.easy/1000 (adj 15): empty #11
,W/Settings( 5840): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5599/cgroup.procs: No such file or directory
,D/LGDMClient( 6019): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6019): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6019): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6019): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6019): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6019): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6051 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/NotificationManager( 5803): com.google.android.music: cancel(1061) by com.google.android.music
,I/art     ( 5863): Explicit concurrent mark sweep GC freed 7745(390KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 495us total 102.004ms
,I/ActivityManager(  857): Process com.android.settings (pid 5536) has died
,W/ContextImpl( 6019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,W/DriveInitializer( 5205): Awaiting to be initialized
W/DriveInitializer( 5205): Background init thread started
E/LGDMClient( 6019): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6019): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6019): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6019): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6019): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
W/ContextImpl( 5205): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  857): Killing 5579:com.lge.sync/1000 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 6051): onCreate
W/AppUp4:DB( 6051):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6051):  setFingerPrint start
I/AppUp4:DB( 6051):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5579/cgroup.procs: No such file or directory
,I/AppUp4:DB( 6051):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6051):  SDK version = 0
I/AppUp4:DB( 6051):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6051): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6051): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6051): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6051): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6051): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6051): onReceive
,I/AppUp4:CustModeStarterReceiver( 6051): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6051): Context : android.app.ReceiverRestrictedContext@2bd537b1
D/AppUp4:CustFacade( 6051): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6051): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6051): begin check event
I/AppUp4:CustModeStarterReceiver( 6051): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6051): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6051): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6051): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6051): handleAsyncCustNotification do not startCustService
I/ActivityManager(  857): Killing 5748:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5693): android.os.DeadObjectException
,W/System.err( 5693): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5693): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5693): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5693): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5693): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5693): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5693): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5693): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5693): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5693): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5693): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5693): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5693): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5693): android.os.DeadObjectException
W/System.err( 5693): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5693): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5693): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5693): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5693): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5693): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5693): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5693): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5693): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5693): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5693): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5693): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5693): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/LgeMiscReceiver( 3079): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3079): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3079): networkInfo.isConnected() = true
D/PhoneState( 3079): setPdpRejectCasuse : false
W/DriveInitializer( 5205): Background init thread ended
,E/libprocessgroup(  857): failed to kill 1 processes for processgroup 5748
,W/ActivityManager(  857): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6094 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 27.464ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.490ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 24.137ms
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6113 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6113): Quickset Services start...
,I/UEI.SmartControl( 6113): Manufacture = LGE
D/UEI.SmartControl( 6113): File observer start...
E/UEI.SmartControl( 6113): IR Port is disabled: false
D/UEI.SmartControl( 6113): Starting file observer...
D/UEI.SmartControl( 6113): Extracting JNI libs...
D/UEI.SmartControl( 6113): --- this system supports 32-bit or 64-bit only
W/art     ( 5960): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  857): Killing 5693:com.lge.qremote/u0a106 (adj 15): empty #11
,I/NotificationManager(  857): android: cancelAsUser(353845882) by android
D/UEI.SmartControl( 6113): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6113): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6113): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/PhoneMonitor( 6094): Register our PhoneStateListener
,I/UEI.SmartControl( 6113): --- Selecting new region: 2
I/UEI.SmartControl( 6113): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6113): Platform has CIR...
D/UEI.SmartControl( 6113): NO CIR support, need to check package...
I/UEI.SmartControl( 6113): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6113): QS Service created
W/libprocessgroup(  857): failed to open /acct/uid_10106/pid_5693/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6094): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6094): onReceive CONNECTIVITY_CHANGE networkType=1
,E/UEI.SmartControl( 6113): QS start get config
D/libc-netbsd( 5960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,E/BandwidthController(  272): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  272): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/PhoneMonitor( 6094): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/DownloadManager( 3103): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3103): DownloadService onCreate
V/TelephonyAutoProfiling( 6094): [loadFeatureFromXml] *** start feature loading from xml
,I/DownloadManager( 3103): in removeSpuriousFiles
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/NotificationManager( 3103): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyAutoProfiling( 6094): [parse] Load xml
V/TelephonyAutoProfiling( 6094): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6094): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3103): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  857): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6160 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
D/UEI.SmartControl( 6113): Loading JNI Libs...
,D/UEI.SmartControl( 6113):  configuring local db...
V/DownloadManager( 3103): created cursor android.database.sqlite.SQLiteCursor@1cbb96cd on behalf of 3103
,I/DownloadManager( 3103): in trimDatabase
V/DownloadManager( 3103): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3103): created cursor android.database.sqlite.SQLiteCursor@3d3e4293 on behalf of 3103
V/DownloadManager( 3103): DownloadService onStartCommand
V/DownloadManager( 3103): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3103): created cursor android.database.sqlite.SQLiteCursor@1c7d52d0 on behalf of 3103
,D/PhoneMonitor( 6094): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  857): Killing 5821:com.android.gallery3d/u0a23 (adj 15): empty #11
I/NotificationManager(  857): android: cancelAsUser(353845882) by android
,D/DrmBroadcastReceiver( 6160): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6160): 1  network is available. Sync DRM Time with NTP
,W/libprocessgroup(  857): failed to open /acct/uid_10023/pid_5821/cgroup.procs: No such file or directory
,V/DrmService( 6160): Service onCreate
D/DrmService( 6160): Received new request = 2
D/WeatherAncestor( 2683): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:39
V/DownloadManager( 3103): DownloadService onDestroy
,I/CheckinService( 5205): Checkin interval check for package: unspecified last checkin: 1449748637924 min interval config: 0 actual interval: 2361438
D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/WeatherAncestor( 2683): connectivity changed - connection : true
,D/Weather_cast( 2683): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2683): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:39
D/WeatherService( 2683): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 6160): Start Sync process
,D/DrmSntpClient( 6160): Server : 0
D/libc-netbsd( 6160): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6160): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6160): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6160): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  272): App 10051 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out( 6160): propertyValue:false
I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6179 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/UEI.SmartControl( 6113):  ---- Has DB8: true
D/UEI.SmartControl( 6113): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6113): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6113): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6113): IRRCDataComm has AudioManager!!!!.
,I/LGDrmClient( 6160): _DRM_ServiceGet() : Bind lgdrm service
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/ILGDrmService(  287): eDRM_SetDRMTime +++
I/LGDRM   (  287): [DRM] SET TIME : YR=2015, MON=12, DAY=10
I/LGDRM   (  287): [DRM] SET TIME : HR=12, MIN=36, SEC=39
V/ILGDrmService(  287): eDRM_SetDRMTime ---
I/DrmSntpClient( 6160): Synched
D/DrmService( 6160): Completed !! request = 2
D/DrmService( 6160): Request count = 0
V/DrmService( 6160): Service onDestroy
,I/CheckinService( 5205): Disabling old GoogleServicesFramework version
W/irrc_jni( 6113): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6113): IrrcClient ++ 
D/irrcClient( 6113): getIrrcService ++ 
D/irrcClient( 6113): getIrrcService -- 
D/irrcClient( 6113): IrrcClient -- 
W/irrc_jni( 6113): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6113): Services init done
I/UEI.SmartControl( 6113): Device manager: loading config....
,D/UEI.SmartControl( 6113): QS Service init finished
D/UEI.SmartControl( 6113): QS Service version name: 0.1.73
D/UEI.SmartControl( 6113): QS Service version code: 1073
D/UEI.SmartControl( 6113): Service requested: Control
D/UEI.SmartControl( 6113): Config is loaded...
,W/ResourcesManager( 6179): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinService( 5205): Checking schedule, now: 1449750999554 next: 1449748667874
I/CheckinService( 5205): active receiver: enabled
D/UEI.SmartControl( 6113):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6113): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6113): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6113): Service.onUnbind: IControl
D/UEI.SmartControl( 6113): Service.onDestroy
D/UEI.SmartControl( 6113): Shutdown IRRCPlayer... 
W/irrc_jni( 6113): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6113): ~IrrcClient ++ 
D/irrcClient( 6113): ~IrrcClient -- 
W/irrc_jni( 6113): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6113): Blaster closed
D/UEI.SmartControl( 6113): Blaster closed
D/UEI.SmartControl( 6113): Shut down QS...
D/UEI.SmartControl( 6113): Stopped file observer...
I/UEI.SmartControl( 6113): QS lib stop result = true
D/UEI.SmartControl( 6113): QS shutdown complete
D/UEI.SmartControl( 6113): QS Service created
I/CheckinService( 5205): Preparing to send checkin request
,I/EventLogService( 5205): Accumulating logs since 1449750392640
E/UEI.SmartControl( 6113): QS start get config
,D/UEI.SmartControl( 6113):  configuring local db...
,I/CheckinRequestBuilder( 5205): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5205): Failed to find provider info for com.google.android.wearable.settings
I/Babel_SMS( 6179): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6179): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6179): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6179): MmsConfig.loadFromDatabase
,D/UEI.SmartControl( 6113):  ---- Has DB8: true
E/Babel_SMS( 6179): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6179): MmsConfig.loadFromResources
E/Babel_SMS( 6179): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6179): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/UEI.SmartControl( 6113): QS start statue = true Error code = 0
D/UEI.SmartControl( 6113): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6113): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6113): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6113): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6113): IrrcClient ++ 
D/irrcClient( 6113): getIrrcService ++ 
,D/irrcClient( 6113): getIrrcService -- 
D/irrcClient( 6113): IrrcClient -- 
W/irrc_jni( 6113): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6113): Services init done
D/UEI.SmartControl( 6113): QS Service init finished
D/UEI.SmartControl( 6113): QS Service version name: 0.1.73
D/UEI.SmartControl( 6113): QS Service version code: 1073
D/UEI.SmartControl( 6113): Service requested: Control
I/UEI.SmartControl( 6113): Device manager: loading config....
E/ActivityThread( 6113): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2b178404 that was originally bound here
E/ActivityThread( 6113): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@2b178404 that was originally bound here
E/ActivityThread( 6113): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6113): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6113): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6113): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6113): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6113): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6113): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6113): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6113): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6113): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6113): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6113): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6113): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6113): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6113): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6113): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6113): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6113): Internal service binding...
,D/UEI.SmartControl( 6113): Config is loaded...
D/UEI.SmartControl( 6113):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6113): Notify AllClients services are ready: 0
,D/SensorManager( 6179): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6179): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6179): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6179): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6179): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6179): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6179): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6179): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6179): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6179): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6179): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6179): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6179): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6179): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6179): found sensor: LGE Relative Motion Detector Sensor, handle=34
,D/SensorManager( 6179): found sensor: Motion Accel, handle=46
,I/art     ( 6179): CheckpointMarkThreadRoots callback created = 0xaaf4e7d0
,W/Settings( 6179): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6179): startup - clean
,I/art     ( 6179): CheckpointMarkThreadRoots callback created = 0xaaf4e7b0
,I/Babel   ( 6179): deleted: false for 0
,I/ActivityManager(  857): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6218 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:40.27 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/AudioCapabilities( 6179): Unsupported mime audio/x-lg-flac
,I/ActivityManager(  857): Killing 5909:com.lge.clock/u0a10 (adj 15): empty #11
W/AudioCapabilities( 6179): Unsupported mime audio/adpcm
W/AudioCapabilities( 6179): Unsupported mime audio/g726
,W/AudioCapabilities( 6179): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6179): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6179): Unsupported mime video/mjpg
W/VideoCapabilities( 6179): Unsupported mime video/theora
,W/AudioCapabilities( 6179): Unsupported mime audio/evrc
,W/AudioCapabilities( 6179): Unsupported mime audio/qcelp
W/VideoCapabilities( 6179): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6179): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6179): Unsupported mime audio/qcelp
W/AudioCapabilities( 6179): Unsupported mime audio/evrc
W/VideoCapabilities( 6179): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6179): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6179): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6179): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6179): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6179): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  857): failed to open /acct/uid_10010/pid_5909/cgroup.procs: No such file or directory
I/ActivityManager(  857): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6236 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/vclib   ( 6179): onServiceConnected
W/Babel   ( 6179): Attempted to change video mute state without an active call.
,I/NotificationManager( 5960): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
I/NotificationManager( 6179): com.google.android.talk: cancel(10436) by com.google.android.talk
I/NotificationManager(  857): android: cancelAsUser(2145784878) by android
,I/ActivityManager(  857): Killing 5938:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10013/pid_5938/cgroup.procs: No such file or directory
D/libc-netbsd( 6179): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6179): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6179): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6179): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 6179): propertyValue:false
W/ResourcesManager( 6236): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6236): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 6179): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  857): Killing 5993:com.qualcomm.timeservice/1000 (adj 15): empty #11
,I/MultiDex( 6236): VM with version 2.1.0 has multidex support
I/MultiDex( 6236): install
I/MultiDex( 6236): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5993/cgroup.procs: No such file or directory
,V/JNIHelp ( 6236): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6236): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6236): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29e958da: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6236): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6236): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6236): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6236): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6236): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6218): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6218):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6218):   adb logcat -s GAv4
,I/art     ( 5205): Explicit concurrent mark sweep GC freed 10869(841KB) AllocSpace objects, 18(288KB) LOS objects, 24% free, 12MB/16MB, paused 1.061ms total 116.049ms
,W/GAv4    ( 6218): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6218): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6218): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/NativeLibraryUtils( 6236): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): CdmEngine::OpenSession
I/WVCdm   (  276): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  276): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  276): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  276): L1 library not specified. Falling Back to L3
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=1170463103
I/ActivityManager(  857): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6292 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  857): RTC_WAKEUP set : Alarm{2a14f66c type 0 when 1449751001640 com.android.vending} when 1449751001640
,I/art     ( 6236): CheckpointMarkThreadRoots callback created = 0xb04cbe40
,I/art     ( 6236): CheckpointMarkThreadRoots callback created = 0xb04cbe20
,I/art     (  857): Explicit concurrent mark sweep GC freed 19770(943KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.130ms total 162.774ms
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WebViewFactory( 6218): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/Finsky  ( 6292): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/LibraryLoader( 6218): Time to load native libraries: 28 ms (timestamps 8909-8937)
I/LibraryLoader( 6218): Expected native library version number "",actual native library version number ""
,I/dex2oat ( 6318): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,V/WebViewChromiumFactoryProvider( 6218): Binding Chromium to main looper Looper (main, tid 1) {3139ac8a}
I/LibraryLoader( 6218): Expected native library version number "",actual native library version number ""
,I/chromium( 6218): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6218): Initializing chromium process, singleProcess=true
,W/art     ( 6218): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6218): ApplicationContext is null in ApplicationStatus
D/Finsky  ( 6292): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/chromium( 6218): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/Settings( 6292): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6292): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6292): com.android.vending: cancel(-1050172287) by com.android.vending
I/dex2oat ( 6318): dex2oat took 137.379ms (threads: 4)
,I/Adreno-EGL( 6236): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6236): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6236): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6236): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6236): Remote Branch: 
I/Adreno-EGL( 6236): Local Patches: 
I/Adreno-EGL( 6236): Reconstruct Branch: 
,E/libEGL  ( 6218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/Ads     ( 6292): Skipping gmscore version check
,I/Adreno-EGL( 6218): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6218): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6218): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6218): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6218): Remote Branch: 
I/Adreno-EGL( 6218): Local Patches: 
I/Adreno-EGL( 6218): Reconstruct Branch: 
,D/Finsky  ( 6292): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6292): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3103): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3103): created cursor android.database.sqlite.SQLiteCursor@2eb42dce on behalf of 6292
D/Finsky  ( 6292): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6292): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/AudioPolicyService(  276): registerClient() client 0xb551c720, uid 10079
,W/AudioManagerAndroid( 6218): Requires BLUETOOTH permission
I/NSApplication( 6218): Starting up...
,I/ActivityManager(  857): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6359 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5803:com.google.android.music:main/u0a81 (adj 15): empty #11
I/Adreno-EGL( 6236): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6236): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6236): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6236): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6236): Remote Branch: 
I/Adreno-EGL( 6236): Local Patches: 
I/Adreno-EGL( 6236): Reconstruct Branch: 
,I/Adreno-EGL( 6236): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6236): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6236): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6236): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6236): Remote Branch: 
I/Adreno-EGL( 6236): Local Patches: 
I/Adreno-EGL( 6236): Reconstruct Branch: 
,I/WVCdm   (  276): CdmEngine::OpenSession
,W/libprocessgroup(  857): failed to open /acct/uid_10081/pid_5803/cgroup.procs: No such file or directory
,D/Finsky  ( 6292): [765] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6292): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  857): Killing 5840:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10021/pid_5840/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:36:43.25 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 5390): Test app app.js loaded
I/jxcore-log( 5390): 
,I/ActivityManager(  857): Killing 6019:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/Choreographer( 5390): Skipped 854 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5390): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/art     ( 5960): CheckpointMarkThreadRoots callback created = 0xb042d430
,I/art     ( 5960): CheckpointMarkThreadRoots callback created = 0xb042d3e0
,W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_6019/cgroup.procs: No such file or directory
,I/iu.SyncManager( 5205): SYNC; picasa accounts
,D/NetworkLogImpl( 5205): Loaded NetworkSpeedPredictor
I/iu.Environment( 5205): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5205): num queued entries: 0
E/lowmemorykiller(  242): Error opening /proc/6113/oom_score_adj; errno=2
I/iu.UploadsManager( 5205): num updated entries: 0
I/iu.SyncManager( 5205): NEXT; no task
,E/lowmemorykiller(  242): Error opening /proc/6113/oom_score_adj; errno=2
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  857): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6389 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  857): Process com.uei.lg.quicksetsdk.lite (pid 6113) has died
I/DigitalAppWidgetProvider( 6389): onReceive: android.intent.action.ALARM_CHANGED
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WeatherAncestor( 2683): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:36:43
D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
I/WVCdm   (  276): CdmEngine::CloseSession
D/Weather_cast( 2683): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2683): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:36:43
,D/WeatherService( 2683): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/GCM     ( 1730): GCM config loaded
,I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6411 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=2776937609
,W/ResourcesManager( 6411): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11b50c1e:true
,D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LocationInitializer( 5205): Restart initialization of location
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1730): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  857): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6433 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,I/ActivityManager(  857): Process com.google.android.talk (pid 6179) has died
,I/MusicStore( 6433): Database version: 120
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6433): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6433): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6433): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6433): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6433): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6433): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6433): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6433): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15bdae1d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6433): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6433): GMSCore installation verified
I/ConfigStore( 6433): Config Database version: 1
,I/MediaRouter( 6433): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 6433): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6433): type=WIFI subType= reason=null isConnected=true
,I/art     ( 6433): CheckpointMarkThreadRoots callback created = 0xb042d380
,I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6474 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/art     ( 6433): CheckpointMarkThreadRoots callback created = 0xb042d350
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.449ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.315ms
,I/MusicLeanback( 6433): Stop autocaching.
,I/MusicLeanback( 6433): Stop autocaching.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.338ms
I/GHttpClientFactory( 6433): Using our fixed implementation of GMSCore's GoogleHttpClient
I/MusicLeanback( 6433): Stop autocaching.
,I/GoogleURLConnFactory( 6433): Using platform SSLCertificateSocketFactory
I/MusicLeanback( 6433): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6433): Stop autocaching.
,W/ResourcesManager( 6474): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/NotificationManager( 6433): com.google.android.music: cancel(1061) by com.google.android.music
,E/GmsUtils( 6433): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6433): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Babel_SMS( 6474): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6474): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6474): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6474): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6474): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6474): MmsConfig.loadFromResources
E/Babel_SMS( 6474): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6474): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6474): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6474): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6474): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6474): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6474): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6474): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6474): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6474): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6474): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6474): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6474): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6474): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6474): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6474): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6474): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6474): found sensor: Motion Accel, handle=46
,I/art     ( 6474): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/ActivityManager(  857): Process com.lge.appbox.client (pid 6051) has died
,I/art     ( 6474): CheckpointMarkThreadRoots callback created = 0xb042d7e0
W/Settings( 6474): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6474): startup - clean
I/Babel   ( 6474): deleted: false for 0
,I/ActivityManager(  857): Process com.google.android.setupwizard (pid 6094) has died
,W/AudioCapabilities( 6474): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6474): Unsupported mime audio/adpcm
W/AudioCapabilities( 6474): Unsupported mime audio/g726
W/AudioCapabilities( 6474): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6474): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6474): Unsupported mime video/mjpg
W/VideoCapabilities( 6474): Unsupported mime video/theora
,W/AudioCapabilities( 6474): Unsupported mime audio/evrc
,W/AudioCapabilities( 6474): Unsupported mime audio/qcelp
W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6474): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6474): Unsupported mime audio/qcelp
W/AudioCapabilities( 6474): Unsupported mime audio/evrc
W/VideoCapabilities( 6474): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6474): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6517 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6411): Create singleton instance
,W/VideoCapabilities( 6474): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6474): onServiceConnected
W/Babel   ( 6474): Attempted to change video mute state without an active call.
I/NotificationManager( 6474): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/UEI.SmartControl( 6517): Quickset Services start...
,I/UEI.SmartControl( 6517): Manufacture = LGE
D/UEI.SmartControl( 6517): File observer start...
E/UEI.SmartControl( 6517): IR Port is disabled: false
D/UEI.SmartControl( 6517): Starting file observer...
D/UEI.SmartControl( 6517): Extracting JNI libs...
D/UEI.SmartControl( 6517): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6411): getMode name:com.lge.qremote
,I/WVCdm   (  276): CdmEngine::CloseSession
I/WVCdm   (  276): L3 Terminate.
,D/UEI.SmartControl( 6517): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6517): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6517): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/ContextImpl( 3353): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/UEI.SmartControl( 6517): --- Selecting new region: 2
I/UEI.SmartControl( 6517): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6517): Platform has CIR...
D/UEI.SmartControl( 6517): NO CIR support, need to check package...
I/UEI.SmartControl( 6517): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6517): QS Service created
E/UEI.SmartControl( 6517): QS start get config
,D/UEI.SmartControl( 6517): Loading JNI Libs...
D/UEI.SmartControl( 6517):  configuring local db...
,I/CheckinRequestBuilder( 5205): Classify the device as Phone.
,D/UEI.SmartControl( 6517):  ---- Has DB8: true
,D/UEI.SmartControl( 6517): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6517): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6517): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6517): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6517): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6517): IrrcClient ++ 
D/irrcClient( 6517): getIrrcService ++ 
D/irrcClient( 6517): getIrrcService -- 
D/irrcClient( 6517): IrrcClient -- 
W/irrc_jni( 6517): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6517): Services init done
,I/UEI.SmartControl( 6517): Device manager: loading config....
D/UEI.SmartControl( 6517): Config is loaded...
D/UEI.SmartControl( 6517):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6517): Notify AllClients services are ready: 0
,I/ActivityManager(  857): Process com.google.android.apps.magazines (pid 6218) has died
,D/UEI.SmartControl( 6517): QS Service init finished
D/UEI.SmartControl( 6517): QS Service version name: 0.1.73
D/UEI.SmartControl( 6517): QS Service version code: 1073
,D/UEI.SmartControl( 6517): Service requested: Control
D/UEI.SmartControl( 6517): Internal service binding...
D/UEI.SmartControl( 6517): -----IControl: 11
,D/UEI.SmartControl( 6517): Caller: com.lge.qremote
D/UEI.SmartControl( 6517): ------------ IControl registerCallback...
I/UEI.SmartControl( 6517): Registering callback...
D/UEI.SmartControl( 6517): -----IControl: 19
D/UEI.SmartControl( 6517): Caller: com.lge.qremote
I/UEI.SmartControl( 6517): Registering Services Ready callback...
I/UEI.SmartControl( 6517): Notify client services are ready...
,D/UEI.SmartControl( 6517): -----IControl: 8
D/UEI.SmartControl( 6517): Caller: com.lge.qremote
I/AudioManager( 6411): getMode name:com.lge.qremote
,I/AudioManager( 6411): getMode name:com.lge.qremote
,D/libc-netbsd( 5205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out( 5205): propertyValue:false
I/art     (  857): Explicit concurrent mark sweep GC freed 22041(995KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.245ms total 175.015ms
,I/AudioManager( 6411): getMode name:com.lge.qremote
D/libc-netbsd( 5205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5205): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5205): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5205): Sending checkin request (9982 bytes)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/CheckinRequestBuilder( 5205): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5205): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5205): Classify the device as Phone.
,I/CheckinTask( 5205): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5205): Checking schedule, now: 1449751007532 next: 1450278256526
I/CheckinService( 5205): active receiver: disabled
,D/CheckinService( 5205): Recording last checkin time for package unspecified as 1449751007562
,I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6563 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6563): Register our PhoneStateListener
,V/SetupWizard( 6563): Connected to Gservices successfully
,I/ActivityManager(  857): Killing 6160:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/PhoneMonitor( 6563): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6563): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6563): [parse] Load xml
V/TelephonyAutoProfiling( 6563): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6563): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6563): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  857): failed to open /acct/uid_10051/pid_6160/cgroup.procs: No such file or directory
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 114882237097; DSPS: 3862308; Offset : -2996828356
,I/MusicWidget( 2628): mDelayedStopHandler : unbind
,I/MusicBrowser( 2074): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2074): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2074): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2074): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2074): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2074): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2074): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2074): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  857):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@295b8f46com.lge.music.MediaPlaybackService$6@17c78507
,D/MusicBrowser( 2074): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@22549ded
,I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2074): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2074): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2074): reset
V/MediaPlayer[Native]( 2074): setListener
,V/MediaPlayer[Native]( 2074): disconnect
V/MediaPlayer[Native]( 2074): destructor
V/AudioFlinger(  276): releasing 19 from 2074 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/MediaPlayer[Native]( 2074): disconnect
D/MusicBrowser( 2074): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2074): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2074): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2074): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2074): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2074): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2074): [SmartShareManagerClient] unregisterListener: 350615092
W/SmartShareClient( 2074): [SmartShareManagerClient] unregisterListener invalid listener: 350615092
I/SmartShareClient( 2074): [SmartShareManagerClient] terminate service: 2074/MediaPlaybackService/671339323
E/HomeCloudIF( 2074): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2074): [SmartShareManagerClient] unbindService context:android.app.Application@1725dc5d
V/CloudHub( 2074): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2074): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2074): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2074): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2074): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  857): Killing 6292:com.android.vending/u0a36 (adj 15): empty #11
I/CloudHub( 2074): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29986
,W/libprocessgroup(  857): failed to open /acct/uid_10036/pid_6292/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  857): Killing 5960:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  857): Killing 6359:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  857): failed to open /acct/uid_10086/pid_5960/cgroup.procs: No such file or directory
,W/libprocessgroup(  857): failed to open /acct/uid_10048/pid_6359/cgroup.procs: No such file or directory
I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6612 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/administrator(  857): Handling package changes for user 0
,W/ResourcesManager( 6474): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6474): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 6474): com.google.android.talk: cancel(8) by com.google.android.talk
,V/JNIHelp ( 6474): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6612): onCreate
W/AppUp4:DB( 6612):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6612):  setFingerPrint start
,I/AppUp4:DB( 6612):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6612):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6612):  SDK version = 0
I/AppUp4:DB( 6612):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6612): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6612): onReceive
I/AppUp4:CustModeStarterReceiver( 6612): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6612): Context : android.app.ReceiverRestrictedContext@88425ca
D/AppUp4:CustFacade( 6612): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6612): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6612): begin check event
I/AppUp4:CustModeStarterReceiver( 6612): Event For Nothing, skip.
,W/System  ( 6474): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6474): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6635 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,W/ResourcesManager( 6635): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6635): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6635): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/NotificationService(  857): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  857): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  857): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/BackupManagerService(  857): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  857): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@91e6286
,W/ResourcesManager(  857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AppConfig( 6635): Total System Memory = 906309632
,I/GalleryUtils( 6635): Application Heap = 96 MB
I/AppConfig( 6635): App Tier : NOT_DEF
D/SystemHelper( 6635): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourceType(  857): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  857): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6658 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  857): Killing 6389:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10010/pid_6389/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/ResourcesManager( 6658): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6658): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6658): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,D/LocationProviderProxy(  857): applying state to connected service
,W/ResourcesManager( 6658): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6658): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6658): BUILD Country: EU
I/SystemConfig( 6658): BUILD Operator: OPEN
,I/ActivityManager(  857): Process com.google.android.music:main (pid 6433) has died
,I/ActivityManager(  857): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6681 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6658): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6658): existFile = false
,I/SystemConfig( 6658): canReadFile = false
I/SystemConfig( 6658): systemFeature RCS result false
D/SystemConfig( 6658): refreshRcsSupport() :false
,I/LockScreenSettings( 6681): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6681): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6681): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6681): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6681): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6681): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6698 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 6517:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6411): android.os.DeadObjectException
,W/System.err( 6411): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6411): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6411): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6411): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6411): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6411): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6411): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6411): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6411): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6411): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6411): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6411): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6411): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6411): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6411): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6411): android.os.DeadObjectException
W/System.err( 6411): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6411): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6411): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6411): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6411): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6411): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6411): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6411): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6411): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6411): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6411): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6411): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6411): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6411): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6411): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  857): failed to open /acct/uid_10089/pid_6517/cgroup.procs: No such file or directory
W/ActivityManager(  857): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,W/ResourcesManager( 6698): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6716 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6716): Quickset Services start...
,I/UEI.SmartControl( 6716): Manufacture = LGE
,D/UEI.SmartControl( 6716): File observer start...
E/UEI.SmartControl( 6716): IR Port is disabled: false
D/UEI.SmartControl( 6716): Starting file observer...
D/UEI.SmartControl( 6716): Extracting JNI libs...
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 6716): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6716): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6716): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6716): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6716): --- Selecting new region: 2
I/UEI.SmartControl( 6716): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6716): Platform has CIR...
D/UEI.SmartControl( 6716): NO CIR support, need to check package...
I/UEI.SmartControl( 6716): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6716): QS Service created
E/UEI.SmartControl( 6716): QS start get config
,D/UEI.SmartControl( 6716): Loading JNI Libs...
,D/UEI.SmartControl( 6716):  configuring local db...
,I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  857): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6748 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6716):  ---- Has DB8: true
D/UEI.SmartControl( 6716): QS start statue = true Error code = 0
D/UEI.SmartControl( 6716): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6716): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6716): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6716): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6716): IrrcClient ++ 
D/irrcClient( 6716): getIrrcService ++ 
D/irrcClient( 6716): getIrrcService -- 
D/irrcClient( 6716): IrrcClient -- 
W/irrc_jni( 6716): IRRCPlayer_nativeInit -- 
,I/ActivityManager(  857): Killing 6411:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6716): Services init done
I/UEI.SmartControl( 6716): Device manager: loading config....
,D/UEI.SmartControl( 6716): Config is loaded...
,I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
D/UEI.SmartControl( 6716): QS Service init finished
,W/libprocessgroup(  857): failed to open /acct/uid_10106/pid_6411/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6716): QS Service version name: 0.1.73
D/UEI.SmartControl( 6716): QS Service version code: 1073
D/UEI.SmartControl( 6716): Service requested: Control
I/ActivityManager(  857): Killing 6563:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/UEI.SmartControl( 6716):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6716): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6716): Internal service binding...
W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_6563/cgroup.procs: No such file or directory
,D/Finsky  ( 6748): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6748): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6748): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6748): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6748): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3103): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3103): created cursor android.database.sqlite.SQLiteCursor@40074ef on behalf of 6748
D/Finsky  ( 6748): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6748): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6748): Skipping gmscore version check
,I/ActivityManager(  857): Killing 6236:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,D/Finsky  ( 6748): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_6236/cgroup.procs: No such file or directory
D/Finsky  ( 6748): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  857): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6795 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PackageBroadcastService( 5205): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5205): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5205): updateResources: need to parse f{com.google.android.gms}
,I/MusicStore( 6795): Database version: 120
,I/art     (  857): Explicit concurrent mark sweep GC freed 28193(1396KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.110ms total 170.936ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6795): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6795): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6795): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6795): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6795): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6795): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6795): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6795): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15bdae1d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6795): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6795): GMSCore installation verified
I/ConfigStore( 6795): Config Database version: 1
,I/MediaRouter( 6795): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 6795): type=WIFI subType= reason=null isConnected=true
,I/MusicLeanback( 6795): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6795): Stop autocaching.
,I/art     ( 6795): CheckpointMarkThreadRoots callback created = 0xb042d380
D/WearableService( 1730): callingUid 10006, callindPid: 1730
I/NetworkMonitor( 6795): type=WIFI subType= reason=null isConnected=true
,I/art     ( 6795): CheckpointMarkThreadRoots callback created = 0xb042d350
,I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6839 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 321us total 28.503ms
,I/MusicLeanback( 6795): Stop autocaching.
I/MusicLeanback( 6795): Stop autocaching.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 22.484ms
I/GHttpClientFactory( 6795): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6795): Using platform SSLCertificateSocketFactory
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.629ms
W/ResourcesManager( 6839): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/art     ( 5863): Explicit concurrent mark sweep GC freed 3258(127KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 404us total 41.794ms
,I/MusicLeanback( 6795): Stop autocaching.
,I/NotificationManager( 6795): com.google.android.music: cancel(1061) by com.google.android.music
D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10594448:true
,D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
D/BluetoothAdapterService(722961412)( 1999): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f59957a
I/Icing   ( 5205): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,E/GmsUtils( 6795): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6795): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/Icing   ( 5205): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/LGMDMManager( 6839): Create singleton instance
,I/AudioManager( 6839): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6716): -----IControl: 11
D/UEI.SmartControl( 6716): Caller: com.lge.qremote
D/UEI.SmartControl( 6716): ------------ IControl registerCallback...
I/UEI.SmartControl( 6716): Registering callback...
,D/UEI.SmartControl( 6716): -----IControl: 19
D/UEI.SmartControl( 6716): Caller: com.lge.qremote
I/UEI.SmartControl( 6716): Registering Services Ready callback...
I/UEI.SmartControl( 6716): Notify client services are ready...
D/UEI.SmartControl( 6716): -----IControl: 8
D/UEI.SmartControl( 6716): Caller: com.lge.qremote
I/AudioManager( 6839): getMode name:com.lge.qremote
,I/ActivityManager(  857): Killing 6612:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/ActivityManager(  857): Killing 2074:com.lge.music/u0a28 (adj 15): empty #12
,V/AudioFlinger(  276): 2074 died, releasing its sessions
,V/AudioFlinger(  276):  pid 1750 @ 0
V/AudioFlinger(  276):  pid 3079 @ 1
,V/AudioFlinger(  276):  pid 3079 @ 2
W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_6612/cgroup.procs: No such file or directory
,W/libprocessgroup(  857): failed to open /acct/uid_10028/pid_2074/cgroup.procs: No such file or directory
I/AudioManager( 6839): getMode name:com.lge.qremote
I/AudioManager( 6839): getMode name:com.lge.qremote
,I/ActivityManager(  857): Killing 6474:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10061/pid_6474/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6716): Internal timer expired: 1
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/MusicLeanback( 6795): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6795): Stop autocaching.
,E/GmsUtils( 6795): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6795): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/CheckinService( 5205): Done disabling old GoogleServicesFramework version
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
,I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=725776311, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
,D/WeatherService( 2683): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:37:0
,D/WeatherService( 2683): 2 : TimeTick Intent And Screen On
D/WeatherService( 2683): 2 : SDK version : 21
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2683): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/WeatherService( 2683): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2683): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2683): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2683): 2 : Fixed theme : optimus
D/WeatherReflect( 2683): 2 : Map key string is -2
,D/lim     ( 2683): 2 : time = 13:37
I/WeatherReflect( 2683): Model Name : LG-D722
D/WeatherTheme( 2683): 2 : Different view - status_min_formatted : 36 != 37
D/WeatherTheme( 2683): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2683): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2683): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/Weather4x2_optimus( 2683): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2683): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2683): forecast size is 0
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2683): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2683): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2683): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2683): url is : null
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/WeatherAncestor( 2683): 2 : update view, appWidgetId: 2
D/WeatherService( 2683): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:37:0
,D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=725776311 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 303, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 303
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{3a50eb24 type 2 when 129458 com.google.android.gms} when 129458
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1730): Vacuum at: now=1449751023115 tag=VacuumService
W/InstanceID/Rpc( 5205): Found 10006
,D/PerfProfileCollectorService( 5205): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 5205): removeStateFiles() called
D/PerfProfileCollectorService( 5205): User is not opt-in to Usage & Diagnostics.
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 46363(3MB) AllocSpace objects, 37(592KB) LOS objects, 40% free, 13MB/22MB, paused 2.262ms total 144.028ms
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 12046 seconds from now (1449751023737)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:37:04.34 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{3022e9d8 type 2 when 131916 android} when 131916
,D/QcrilMsgTunnelSocket( 2289): readRilMessage: Buffer = [B@376c336c HexData = [010000000404000011000000514f454d484f4f4bef0308000100000003]
D/QcrilMsgTunnelSocket( 2289): Rcvd UNSOL response with 28 bytes data for SUB0
D/QcrilMsgTunnelSocket( 2289): Response ID 525295 is not served in this process.
D/QcrilMsgTunnelSocket( 2289): To broadcast an Intent via the notifier to external apps
D/QcrilMsgTunnelIfaceManager( 2289): handleMessage what = 0
D/QcrilMsgTunnelIfaceManager( 2289): Broadcasting intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
,D/QC_RIL_OEM_HOOK( 1750): Received Broadcast Intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
D/QC_RIL_OEM_HOOK( 1750): Oem ID in QCRILHOOK UNSOL RESP is QOEMHOOK
,V/TelephonyAutoProfiling( 1750): [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
,D/PhoneInterfaceManager( 1750): [PhoneIntfMgr] handleMessage : 2
,D/PhoneInterfaceManager( 1750): [PhoneIntfMgr] handleMessage : 3
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 13:37:07.363 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 134882911516; DSPS: 4517690; Offset : -2996823814
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28238 ms ago)
,D/qdlights(  857): set_light_backlight: 252
,D/qdlights(  857): set_light_backlight: 249
D/qdlights(  857): set_light_backlight: 246
,D/qdlights(  857): set_light_backlight: 242
,D/qdlights(  857): set_light_backlight: 239
,D/qdlights(  857): set_light_backlight: 236
,D/qdlights(  857): set_light_backlight: 232
,D/qdlights(  857): set_light_backlight: 229
,D/qdlights(  857): set_light_backlight: 226
,D/qdlights(  857): set_light_backlight: 222
,D/qdlights(  857): set_light_backlight: 219
,D/qdlights(  857): set_light_backlight: 216
,D/qdlights(  857): set_light_backlight: 212
,D/qdlights(  857): set_light_backlight: 209
,D/qdlights(  857): set_light_backlight: 206
,D/qdlights(  857): set_light_backlight: 202
,D/qdlights(  857): set_light_backlight: 199
,D/qdlights(  857): set_light_backlight: 196
,D/qdlights(  857): set_light_backlight: 192
,D/qdlights(  857): set_light_backlight: 189
,D/qdlights(  857): set_light_backlight: 186
,D/qdlights(  857): set_light_backlight: 182
,D/qdlights(  857): set_light_backlight: 179
,D/qdlights(  857): set_light_backlight: 176
,D/qdlights(  857): set_light_backlight: 172
,D/qdlights(  857): set_light_backlight: 169
,D/qdlights(  857): set_light_backlight: 166
,D/qdlights(  857): set_light_backlight: 162
,D/qdlights(  857): set_light_backlight: 159
,D/qdlights(  857): set_light_backlight: 156
,D/qdlights(  857): set_light_backlight: 152
,D/qdlights(  857): set_light_backlight: 149
,D/qdlights(  857): set_light_backlight: 146
,D/qdlights(  857): set_light_backlight: 142
,D/qdlights(  857): set_light_backlight: 139
,D/qdlights(  857): set_light_backlight: 136
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
D/qdlights(  857): set_light_backlight: 132
,D/qdlights(  857): set_light_backlight: 129
,D/qdlights(  857): set_light_backlight: 126
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  857): set_light_backlight: 122
D/qdlights(  857): set_light_backlight: 119
,D/qdlights(  857): set_light_backlight: 116
,D/qdlights(  857): set_light_backlight: 112
,D/qdlights(  857): set_light_backlight: 109
,D/qdlights(  857): set_light_backlight: 106
,D/qdlights(  857): set_light_backlight: 102
,D/qdlights(  857): set_light_backlight: 99
,D/qdlights(  857): set_light_backlight: 96
,D/qdlights(  857): set_light_backlight: 92
,D/qdlights(  857): set_light_backlight: 89
,D/qdlights(  857): set_light_backlight: 86
,D/qdlights(  857): set_light_backlight: 82
,D/qdlights(  857): set_light_backlight: 79
,D/qdlights(  857): set_light_backlight: 76
,D/qdlights(  857): set_light_backlight: 72
,D/qdlights(  857): set_light_backlight: 69
,D/qdlights(  857): set_light_backlight: 66
,D/qdlights(  857): set_light_backlight: 62
,D/qdlights(  857): set_light_backlight: 59
,D/qdlights(  857): set_light_backlight: 56
,D/qdlights(  857): set_light_backlight: 52
,D/qdlights(  857): set_light_backlight: 49
,D/qdlights(  857): set_light_backlight: 46
,D/qdlights(  857): set_light_backlight: 42
,D/qdlights(  857): set_light_backlight: 39
,D/qdlights(  857): set_light_backlight: 36
,D/qdlights(  857): set_light_backlight: 32
,D/qdlights(  857): set_light_backlight: 29
,D/qdlights(  857): set_light_backlight: 26
,D/qdlights(  857): set_light_backlight: 22
,D/qdlights(  857): set_light_backlight: 19
,D/qdlights(  857): set_light_backlight: 16
,D/qdlights(  857): set_light_backlight: 12
,D/qdlights(  857): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 154883666976; DSPS: 5173075; Offset : -2996830928
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35232 ms ago)
I/PowerManagerService(  857): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35245 ms ago)
,W/ContextImpl(  857): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  857): Sleeping (uid 1000)...
D/LPWGController(  857): [updateScreenState] screen on = false
D/LPWGController(  857): disable proximity sensor
,D/LPWGController(  857): enable proximity sensor
I/SensorManager(  857): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3d89f016] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  857): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  857): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  857): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  857): activate: handle is 48, enable
,V/sensors_hal_Ctx(  857): activate sensors is 1400000000000
D/sensors_hal_Thresh(  857): enable: handle=48
I/sensors_hal_SAM(  857): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  857): waitForResponse: timeout=1000
V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  857): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  857): enable: Received response: 0
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35293 ms ago)
I/Adreno-EGL(  857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  857): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  857): Build Date: 03/02/15 Mon
I/Adreno-EGL(  857): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  857): Remote Branch: 
I/Adreno-EGL(  857): Local Patches: 
I/Adreno-EGL(  857): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (142 us)
,I/Sensors (  414): sns_pwr.c(273):acquiring wakelock
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
,D/qdlights(  857): set_light_backlight: 0
,I/SensorManager(  857): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  857): activate: handle is 46, disable
V/sensors_hal_Ctx(  857): activate sensors is 1000000000000
D/sensors_hal_LP2(  857): enable: handle=46
D/sensors_hal_LP2(  857): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  857): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
I/DisplayManagerService(  857): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  857): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  857): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  857): Excessive delay in setPowerMode(): 183ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  857): Got set_interactive hint
,D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1371): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1371): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
,D/WifiServerServiceExt(  857): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 857
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
,V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  276): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WifiServerServiceExt(  857): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
,I/Sensors (  414): sns_pwr.c(301):releasing wakelock
,D/GpsLocationProvider(  857): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1804): RESTART MSG
D/SplitWindow(  857): check instance of lgWin Window{30990f6d u0 SearchPanel}
,I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1804): lockStatus = 0
D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1787): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1787): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 3
D/NfcService( 1787): Discovery configuration equal, not updating.
D/InputDispatcher(  857): Window went away: Window{bef24d1 u0 SearchPanel}
,I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,D/Ulp_jni (  857): JNI:system_update. Event-0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/WeatherService( 2683): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:37:30
,D/WeatherService( 2683): 2 : ACTION screen on
,D/WeatherService( 2683): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2683): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2683): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:37:30
D/AppCleanupService( 3802): android.intent.action.SCREEN_ON
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): ACTION_SCREEN_ON
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 857
,D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
D/WifiController(  857): CMD_SCREEN_OFF 
D/WifiController(  857): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  857): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1804): clear
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
,E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1787): getDefaultRoute
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: 0
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 1
E/NxpNfcJni( 1787): getReconnectState = 0x0
,I/art     (  857): Explicit concurrent mark sweep GC freed 41869(1994KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.094ms total 167.881ms
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2683): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:37:30
D/WeatherService( 2683): 2 : ACTION screen off
,D/WeatherService( 2683): 2 : TimeTick Receiver Unregister
D/WeatherService( 2683): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:37:30
,D/AppCleanupService( 3802): android.intent.action.SCREEN_OFF
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): ACTION_SCREEN_OFF
D/AppCleanupService( 3802): AppUsageStatsSaveTask
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{2f2cf7a2 type 2 when 161140 com.android.systemui} when 161140
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1750): getCallState : 0
D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{32e4fc33 type 2 when 161929 android} when 161929
,E/ActivityThread( 5205): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  857): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 132859, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  857): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 222406, reason: UserStart
I/NotificationManager(  857): android: cancelAsUser(716319171) by android
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 174884410094; DSPS: 5828460; Offset : -2996850776
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=725776311, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{23c071c type 2 when 187561 com.google.android.gms} when 187561
D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=725776311 [*alarm*], flags=0x0
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{1961bf25 type 2 when 188039 android} when 188039
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{1279d8fa type 2 when 191950 android} when 191950
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 194885185295; DSPS: 6483845; Offset : -2996838644
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 214885947996; DSPS: 7139230; Offset : -2996838805
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 234886783665; DSPS: 7794617; Offset : -2996827241
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 254887627824; DSPS: 8450005; Offset : -2996837679
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 274888387921; DSPS: 9105390; Offset : -2996840599
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 294889078225; DSPS: 9760772; Offset : -2996821396
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
D/WifiController(  857): battery changed pluggedType: 2
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 314889754676; DSPS: 10416155; Offset : -2996847239
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1999): Disconnected process message: 10, size: 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC

```
