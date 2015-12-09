#### Test 5065027873d6a28_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/AlertService( 5167): Beginning updateAlertNotification
D/AlertService( 5167): No fired or scheduled alerts
I/NotificationManager( 5167): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5167): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5167): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5167): No events found starting within 1 week.
,--------- beginning of system
I/ActivityManager(  859): Killing 5018:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  859): failed to open /acct/uid_10018/pid_5018/cgroup.procs: No such file or directory
V/AlarmManager(  859): RTC_WAKEUP set : Alarm{18e0e22d type 0 when 1449626573784 com.android.vending} when 1449626573784
D/Finsky  ( 4864): [580] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4864): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 5217): 
D/AndroidRuntime( 5217): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5217): CheckJNI is OFF
D/AndroidRuntime( 5217): Calling main entry com.android.commands.am.Am
I/ActivityManager(  859): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  859): setTaskToReturnTo : TaskRecord{38783362 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  859): setTaskToReturnTo : TaskRecord{38783362 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  859): AppWindowTokenEx init.. 
D/ContextHelper(  859): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  859): Focus left window: Window{ab4d5c6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5217): Shutting down VM
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  859): check instance of lgWin Window{36b764dc u0 Starting com.test.thalitest}
I/ActivityManager(  859): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5244 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  859): Starting window displayed
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
I/HotwordDetector( 1936): Closing mic
D/BarTransitions( 1372): draw background and invalidate : color = 8000000
W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@252ccc5f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BarTransitions( 1372): draw background and invalidate : color = c0c0c0c
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@8e414de
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  287): RecordHandle::stop()
V/AudioFlinger(  287): RecordThread::stop
V/AudioFlinger(  287): Record stopped OK
,V/AudioPolicyManager(  287): stopInput() input 17
V/AudioPolicyService(  287): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  287): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  287): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  287): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  287): ThreadBase::setParameters() routing=0
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb405e000
D/audio_hw_primary(  287): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  287): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  287): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  287): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  287): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  287): disable_audio_route: exit
E/audio_hw_primary(  287): disable_snd_device: enter 144
D/hardware_info(  287): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  287): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  287): stop_input_stream: exit: status(0)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioFlinger(  287): RecordThread: loop stopping
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyManager(  287): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  287): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  287): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  287): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyService(  287): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  287): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  287): setParameters(): io 17, keyvalue hotword_active=0, calling pid 287
V/AudioFlinger(  287): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  287): RecordThread: loop starting
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  287): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  287): in_set_parameters: exit: status(0)
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb405e000
V/AudioFlinger(  287): RecordThread: loop stopping
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioFlinger(  287): releasing 16 from 1936 for -1
V/AudioFlinger(  287):  decremented refcount to 0
V/AudioFlinger(  287): purging stale effects
V/AudioFlinger(  287): RecordHandle::stop()
V/AudioFlinger(  287): RecordThread::stop
V/AudioPolicyManager(  287): releaseInput() 17
V/AudioPolicyManager(  287): closeInput(17)
V/AudioFlinger(  287): closeInput() 17
V/AudioSystem(  287): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  859): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  287): ThreadBase::exit
V/AudioFlinger(  287): RecordThread: loop starting
V/AudioSystem( 2631): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3132): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  287): RecordThread 0xb405e000 exiting
D/audio_hw_primary(  287): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  287): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioPolicyService(  287): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  287): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  287): releaseInput() exit
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioFlinger(  287): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  287): AudioCommandThread() processing update audio port list
V/AudioFlinger(  287): removeClient_l() pid 1936, calling pid 287
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1936): Hotword detection finished
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
D/ContextHelper( 5244): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5244): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5244): Time to load native libraries: 2 ms (timestamps 2291-2293)
I/LibraryLoader( 5244): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5244): Binding Chromium to main looper Looper (main, tid 1) {1194a586}
I/LibraryLoader( 5244): Expected native library version number "",actual native library version number ""
I/chromium( 5244): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5244): Initializing chromium process, singleProcess=true
W/art     ( 5244): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5244): ApplicationContext is null in ApplicationStatus
W/chromium( 5244): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5244): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5244): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5244): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5244): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5244): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5244): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5244): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5244): Remote Branch: 
I/Adreno-EGL( 5244): Local Patches: 
I/Adreno-EGL( 5244): Reconstruct Branch: 
V/AudioPolicyService(  287): registerClient() client 0xb551c8c0, uid 10316
D/BluetoothManagerService(  859): Message: 20
D/BluetoothManagerService(  859): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1abcd45e:true
,D/BluetoothAdapter( 5244): 788336793: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5244): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5244): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5244): CordovaWebView is running on device made by: LGE
,W/art     ( 5244): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5244): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5244): Activity.onPostResume() called 
,D/OpenGLRenderer( 5244): Render dirty regions requested: true
I/OpenGLRenderer( 5244): Initialized EGL, version 1.4
D/OpenGLRenderer( 5244): Enabling debug mode 0
,D/Atlas   ( 5244): Validating map...
,D/SplitWindow(  859): check instance of lgWin Window{2f75110e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5244): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  859): Focus entered window: Window{2f75110e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  859): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  859): Displayed com.test.thalitest/.MainActivity: +1s160ms
I/Timeline(  859): Timeline: Activity_windows_visible id: ActivityRecord{aa1ecf3 u0 com.test.thalitest/.MainActivity t220} time:93007
I/Timeline( 5244): Timeline: Activity_idle id: android.os.BinderProxy@165725c2 time:93031
,W/BindingManager( 5244): Cannot call determinedVisibility() - never saw a connection for the pid: 5244
,D/JsMessageQueue( 5244): Set native->JS mode to OnlineEventsBridgeMode
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/jxcore_app_log( 5244): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622832128
D/JX-Cordova( 5244): jxcore cordova android initializing
,I/art     ( 5244): CheckpointMarkThreadRoots callback created = 0x9f5532d0
,I/art     ( 5244): CheckpointMarkThreadRoots callback created = 0x9f5532a0
,I/art     (  859): Explicit concurrent mark sweep GC freed 14396(680KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.737ms total 182.189ms
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{2df85d27 type 0 when 1449626577845 com.android.vending} when 1449626577845
D/Finsky  ( 4864): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  859): tsOffsetIs: Apps: 95151494292; DSPS: 3209534; Offset : -2800862693
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4864): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  859): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5363 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 5363): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5363): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Finsky  ( 4864): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/MultiDex( 5363): VM with version 2.1.0 has multidex support
I/MultiDex( 5363): install
I/MultiDex( 5363): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5363): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 5363): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5363): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@264ab58: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5363): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5363): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5363): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1962): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 3854): Restart initialization of location
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1962): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 3854): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1962): location=null
,W/jxcore-log( 5244): Initializing JXcore engine
W/jxcore-log( 5244): JXcore engine is ready
W/jxcore-log( 5244): Starting JXcore engine
,I/ActivityManager(  859): Process com.lge.lockscreensettings (pid 5037) has died
,W/.test.thalitest( 5244): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[4744]" dev="sockfs" ino=4744 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5244): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5244): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6787]" dev="sockfs" ino=6787 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5244): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5244): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5244): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24386]" dev="sockfs" ino=24386 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,D/NativeLibraryUtils( 5363): Install completed successfully. count=13 extracted=0
,I/art     ( 5363): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 5363): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
W/jxcore-log( 5244): Platform android
W/jxcore-log( 5244): 
W/jxcore-log( 5244): Process ARCH arm
W/jxcore-log( 5244): 
I/NotificationManager( 5363): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 4864): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 4864): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/ActivityManager(  859): Process com.google.android.apps.plus (pid 4806) has died
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4864): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4864): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 4864): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  859): RTC_WAKEUP set : Alarm{138b5c94 type 0 when 1449626579390 com.android.vending} when 1449626579390
,D/Finsky  ( 4864): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 4864): [589] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx(  859): acquireWakeLockInternal: lock=933771399, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=859
,D/WeatherService( 2603): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:3:0
D/WeatherService( 2603): 2 : TimeTick Intent And Screen On
D/WeatherService( 2603): 2 : SDK version : 21
,W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2603): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2603): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2603): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2603): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2603): 2 : This is isUpdating : false
D/WeatherService( 2603): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2603): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2603): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2603): 2 : Fixed theme : optimus
D/WeatherReflect( 2603): 2 : Map key string is -2
,D/lim     ( 2603): 2 : time = 03:03
I/WeatherReflect( 2603): Model Name : LG-D722
D/WeatherTheme( 2603): 2 : Different view - status_min_formatted : 02 != 03
D/WeatherTheme( 2603): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2603): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2603): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2603): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/Weather4x2_optimus( 2603): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2603): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2603): forecast size is 0
D/Theme   ( 2603): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2603): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2603): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2603): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2603): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2603): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2603): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2603): url is : null
D/Theme   ( 2603): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2603): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2603): 2 : update view, appWidgetId: 2
D/WeatherService( 2603): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:3:0
D/PowerManagerServiceEx(  859): releaseWakeLockInternal: lock=933771399 [*alarm*], flags=0x0
,I/jxcore-log( 5244): JXcore Cordova bridge is ready!
I/jxcore-log( 5244): 
,W/jxcore-log( 5244): JXcore engine is started
I/chromium( 5244): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5244): Skipped 211 frames!  The application may be doing too much work on its main thread.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/jxcore  ( 5244): Error!: missing ) after argument list
E/jxcore  ( 5244): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
I/chromium( 5244): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
D/InputDispatcher(  859): Focus left window: Window{2f75110e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (155 us)
,W/PluginManager( 5244): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
,I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
D/WeatherAncestor( 2603): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:3:0
D/UpdateThreadPoolManager( 2603): 2 : This is isUpdating : false
D/WeatherService( 2603): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2603): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 2603): 2 : shouldTimeTickRegistered().........
D/WeatherAncestor( 2603): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:3:0
D/WeatherService( 2603): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2603): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2603): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2603): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2603): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 2603): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2603): 2 : This is isUpdating : false
D/WeatherService( 2603): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2603): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2603): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2603): 2 : Fixed theme : optimus
W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@252ccc5f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WeatherReflect( 2603): 2 : Map key string is -2
D/lim     ( 2603): 2 : time = 03:03
I/WeatherReflect( 2603): Model Name : LG-D722
D/InputDispatcher(  859): Focus entered window: Window{ab4d5c6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/WeatherTheme( 2603): 2 : exactly same view!
D/WeatherTheme( 2603): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
,W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2603): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2603): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2603): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  859): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/IInputConnectionWrapper( 5244): showStatusIcon on inactive InputConnection
I/ActivityManager(  859): Process com.google.android.gm (pid 5068) has died
,I/HotwordRecognitionRnr( 1936): Starting hotword detection.
,I/MicrophoneInputStream( 1936): mic_starting com.google.android.apps.gsa.speech.audio.u@2cffab11
V/AudioRecord( 1936): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1936): set(): mSessionId 22
V/AudioPolicyManager(  287): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  287): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  287): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  287): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
V/audio_hw_primary(  287): adev_open_input_stream: exit
V/AudioFlinger(  287): openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
,V/AudioFlinger(  287): openInput_l() created record thread: ID 23 thread 0xb405e000
V/AudioSystem(  287): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1372): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1750): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1936): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3132): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  287): AudioCommandThread() adding update audio port list
V/AudioSystem( 2631): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  287): inserting command: 9 at index 0, num commands 0
V/AudioSystem(  859): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
I/Timeline( 1876): Timeline: Activity_idle id: android.os.BinderProxy@1f61a3cd time:97758
I/AudioFlinger(  287): AudioFlinger's thread 0xb405e000 ready to run
D/audio_hw_primary(  287): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioFlinger(  287): openRecord() lSessionId: 22 input 23
D/audio_hw_primary(  287): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioFlinger(  287): RecordThread: loop stopping
V/AudioFlinger(  287): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  287): acquiring 22 from 1936, for -1
V/AudioFlinger(  287):  added new entry for 22
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@252ccc5f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BarTransitions( 1372): draw background and invalidate : color = f9000000
V/AudioRecord( 1936): start, sync event 0 trigger session 0
V/AudioRecord( 1936): mAudioRecord->start()
,V/AudioFlinger(  287): RecordHandle::start()
V/AudioFlinger(  287): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  287): startInput() module primary->input primary(23)
V/AudioPolicyManager(  287): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  287): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  287): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  287): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  287): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  287): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  287): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  287): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  287): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  287): RecordThread: loop starting
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  287): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  287): in_set_parameters: exit: status(0)
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb405e000
V/AudioFlinger::PatchPanel(  287): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  287): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyManager(  287): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  287): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  287): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  287): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyService(  287): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  287): inserting command: 3 at index 0, num commands 0
D/BarTransitions( 1372): draw background and invalidate : color = f0e7e7e7
,V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  287): setParameters(): io 23, keyvalue hotword_active=1, calling pid 287
V/AudioFlinger(  287): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  287): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  287): in_set_parameters: exit: status(0)
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb405e000
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyManager(  287): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1936): mic_started com.google.android.apps.gsa.speech.audio.u@2cffab11
,V/msm8974_platform(  287): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  287): start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
V/voice   (  287): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  287): start_input_stream: usecase(7)
E/audio_hw_primary(  287): select_devices: enter and usecase(7)
V/msm8974_platform(  287): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  287): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  287): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  287): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  287): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  287): enable_snd_device: enter  144
D/hardware_info(  287): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  287): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  287): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  287): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  287): ACDB -> send_adm_topology
D/ACDB-LOADER(  287): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  287): ACDB -> send_asm_topology
D/ACDB-LOADER(  287): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  287): ACDB -> send_audtable
D/ACDB-LOADER(  287): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  287): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  287): ACDB -> send_audvoltable
D/ACDB-LOADER(  287): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  287): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  287): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  287): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  287): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  287): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  287): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  287): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  287): enable_audio_route: exit
D/audio_hw_primary(  287): select_devices: done
V/audio_hw_primary(  287): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  287): start_input_stream: exit
,I/HotwordWorker( 1936): onReady
,I/Timeline(  859): Timeline: Activity_windows_visible id: ActivityRecord{1e91ee8 u0 com.lge.launcher2/.Launcher t219} time:98021
,D/InputDispatcher(  859): Window went away: Window{2f75110e u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/OpenGLRenderer( 1876): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,W/OpenGLRenderer( 1876): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1876): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1876): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1876): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1876): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{37df2fa9 type 0 when 1449626594161 com.android.vending} when 1449626594161
,W/ContextImpl( 3383): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 4864): [580] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4864): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 115153241991; DSPS: 3864951; Offset : -2800854573
,I/MusicWidget( 2523): mDelayedStopHandler : unbind
,I/MusicBrowser( 2631): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2631): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2631): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2631): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2631): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2631): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2631): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2631): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  859):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1ae284a4com.lge.music.MediaPlaybackService$6@31b4a20d
,D/MusicBrowser( 2631): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2631): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@27e9b7e3
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2631): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2631): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2631): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2631): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2631): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2631): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2631): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2631): reset
,V/MediaPlayer[Native]( 2631): setListener
,V/MediaPlayer[Native]( 2631): disconnect
V/MediaPlayer[Native]( 2631): destructor
V/AudioFlinger(  287): releasing 19 from 2631 for -1
V/AudioFlinger(  287):  decremented refcount to 0
V/AudioFlinger(  287): purging stale effects
V/MediaPlayer[Native]( 2631): disconnect
D/MusicBrowser( 2631): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2631): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2631): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2631): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2631): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2631): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2631): [SmartShareManagerClient] unregisterListener: 374810050
W/SmartShareClient( 2631): [SmartShareManagerClient] unregisterListener invalid listener: 374810050
I/SmartShareClient( 2631): [SmartShareManagerClient] terminate service: 2631/MediaPlaybackService/300217953
E/HomeCloudIF( 2631): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2631): [SmartShareManagerClient] unbindService context:android.app.Application@6a85fd3
V/CloudHub( 2631): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2631): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2631): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2631): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2631): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2631): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2631): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19980
,D/charger_monitor(  478): init target 500000
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{1042f92e type 2 when 125803 com.google.android.gms} when 125803
V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{3c044ccf type 2 when 130104 com.google.android.gms} when 130104
,D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 135155662556; DSPS: 4520391; Offset : -2800875129
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2631): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2631): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/PowerManagerService(  859): ALS enabled for SRE
,D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29761 ms ago)
D/qdlights(  859): set_light_backlight: 253
,D/qdlights(  859): set_light_backlight: 249
D/qdlights(  859): set_light_backlight: 246
,D/qdlights(  859): set_light_backlight: 243
,D/qdlights(  859): set_light_backlight: 239
,D/qdlights(  859): set_light_backlight: 236
,D/qdlights(  859): set_light_backlight: 233
,D/qdlights(  859): set_light_backlight: 229
,D/qdlights(  859): set_light_backlight: 226
,D/qdlights(  859): set_light_backlight: 223
,D/qdlights(  859): set_light_backlight: 219
,D/qdlights(  859): set_light_backlight: 216
,D/qdlights(  859): set_light_backlight: 213
,D/qdlights(  859): set_light_backlight: 209
,D/qdlights(  859): set_light_backlight: 206
,D/qdlights(  859): set_light_backlight: 203
,D/qdlights(  859): set_light_backlight: 199
,D/qdlights(  859): set_light_backlight: 196
,D/qdlights(  859): set_light_backlight: 193
,D/qdlights(  859): set_light_backlight: 189
,D/qdlights(  859): set_light_backlight: 186
,D/qdlights(  859): set_light_backlight: 183
,D/qdlights(  859): set_light_backlight: 179
,D/qdlights(  859): set_light_backlight: 176
,D/qdlights(  859): set_light_backlight: 173
,D/qdlights(  859): set_light_backlight: 169
,D/qdlights(  859): set_light_backlight: 166
,D/qdlights(  859): set_light_backlight: 163
,D/qdlights(  859): set_light_backlight: 159
,D/qdlights(  859): set_light_backlight: 156
,D/qdlights(  859): set_light_backlight: 153
,D/qdlights(  859): set_light_backlight: 149
,D/qdlights(  859): set_light_backlight: 146
,D/qdlights(  859): set_light_backlight: 143
,D/qdlights(  859): set_light_backlight: 139
,D/qdlights(  859): set_light_backlight: 136
,D/qdlights(  859): set_light_backlight: 133
,D/qdlights(  859): set_light_backlight: 129
,D/qdlights(  859): set_light_backlight: 126
,D/qdlights(  859): set_light_backlight: 123
,D/qdlights(  859): set_light_backlight: 119
,D/qdlights(  859): set_light_backlight: 116
,D/qdlights(  859): set_light_backlight: 113
,D/qdlights(  859): set_light_backlight: 109
,D/qdlights(  859): set_light_backlight: 106
,D/qdlights(  859): set_light_backlight: 103
,D/qdlights(  859): set_light_backlight: 99
,D/qdlights(  859): set_light_backlight: 96
,D/qdlights(  859): set_light_backlight: 93
,D/qdlights(  859): set_light_backlight: 89
,D/qdlights(  859): set_light_backlight: 86
,D/qdlights(  859): set_light_backlight: 83
,D/qdlights(  859): set_light_backlight: 79
,D/qdlights(  859): set_light_backlight: 76
,D/qdlights(  859): set_light_backlight: 73
,D/qdlights(  859): set_light_backlight: 69
,D/qdlights(  859): set_light_backlight: 66
,D/qdlights(  859): set_light_backlight: 63
,D/qdlights(  859): set_light_backlight: 59
,D/qdlights(  859): set_light_backlight: 56
,D/qdlights(  859): set_light_backlight: 53
,D/qdlights(  859): set_light_backlight: 49
,D/qdlights(  859): set_light_backlight: 46
,D/qdlights(  859): set_light_backlight: 43
,D/qdlights(  859): set_light_backlight: 39
,D/qdlights(  859): set_light_backlight: 36
,D/qdlights(  859): set_light_backlight: 33
,D/qdlights(  859): set_light_backlight: 29
,D/qdlights(  859): set_light_backlight: 26
,D/qdlights(  859): set_light_backlight: 23
,D/qdlights(  859): set_light_backlight: 19
,D/qdlights(  859): set_light_backlight: 16
,D/qdlights(  859): set_light_backlight: 13
,D/qdlights(  859): set_light_backlight: 10
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 155156581142; DSPS: 5175781; Offset : -2800872070
,I/PowerManagerService(  859): ALS enabled for SRE
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36749 ms ago)
I/PowerManagerService(  859): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  859): ALS enabled for SRE
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36762 ms ago)
,W/ContextImpl(  859): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  859): Sleeping (uid 1000)...
D/LPWGController(  859): [updateScreenState] screen on = false
D/LPWGController(  859): disable proximity sensor
,D/LPWGController(  859): enable proximity sensor
I/SensorManager(  859): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1455f65c] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  859): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  859): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  859): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  859): activate: handle is 48, enable
V/sensors_hal_Ctx(  859): activate sensors is 1400000000000
D/sensors_hal_Thresh(  859): enable: handle=48
I/sensors_hal_SAM(  859): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
,D/sensors_hal_Util(  859): waitForResponse: timeout=1000
V/sensors_hal_SAM(  859): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  859): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  859): enable: Received response: 0
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36809 ms ago)
I/Adreno-EGL(  859): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  859): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  859): Build Date: 03/02/15 Mon
I/Adreno-EGL(  859): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  859): Remote Branch: 
I/Adreno-EGL(  859): Local Patches: 
I/Adreno-EGL(  859): Reconstruct Branch: 
,I/Sensors (  425): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  859): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  859): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  859): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  859): processInd: handle 48, count=1
V/sensors_hal_Thresh(  859): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  859): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  859): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  859): poll: count: 256
I/sensors_hal_Ctx(  859): poll: released wakelock sensor_ind
D/sensors_hal_Util(  859): waitForResponse: timeout=0
D/LPWGController(  859): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  859): current mode = 1  value = 1 1
I/LPWGController(  859): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  859): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/PowerManagerServiceEx(  859): acquireWakeLockInternal: lock=933771399, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=859
,D/WeatherService( 2603): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:4:0
D/WeatherService( 2603): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:4:0
D/PowerManagerServiceEx(  859): releaseWakeLockInternal: lock=933771399 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/qdlights(  859): set_light_backlight: 0
,I/SensorManager(  859): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  859): activate: handle is 46, disable
V/sensors_hal_Ctx(  859): activate sensors is 1000000000000
D/sensors_hal_LP2(  859): enable: handle=46
D/sensors_hal_LP2(  859): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  859): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  859): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  859): Display changed displayId=0
V/sensors_hal_SAM(  859): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  859): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  859): Excessive delay in setPowerMode(): 240ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  859): Got set_interactive hint
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
,D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
,D/KeyguardViewMediator( 1372): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
,I/HotwordDetector( 1936): Closing mic
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@2cffab11
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  287): RecordHandle::stop()
V/AudioFlinger(  287): RecordThread::stop
D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1372): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
,D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
V/AudioFlinger(  287): Record stopped OK
,V/AudioPolicyManager(  287): stopInput() input 23
V/AudioPolicyService(  287): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  287): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  287): releaseAudioPatch handle 24
V/AudioFlinger::PatchPanel(  287): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  287): ThreadBase::setParameters() routing=0
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb405e000
,D/audio_hw_primary(  287): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/WifiServerServiceExt(  859): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  287): setParameters(): io 0, keyvalue screen_state=on, calling pid 859
,V/audio_hw_primary(  287): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  287): disable_audio_route: enter: usecase(7)
,V/msm8974_platform_lge(  287): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  287): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  287): disable_audio_route: exit
E/audio_hw_primary(  287): disable_snd_device: enter 144
D/hardware_info(  287): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  287): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  287): stop_input_stream: exit: status(0)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioFlinger(  287): RecordThread: loop stopping
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyManager(  287): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  287): removeAudioPatch() handle 20 af handle 24
V/AudioPolicyService(  287): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  287): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio patch list
D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=on
V/voice   (  287): voice_set_parameters: enter: screen_state=on
V/compress_voip(  287): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  287): voice_extn_compress_voip_set_parameters: exit
V/voice   (  287): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  287): LGE_platform_set_parameters: enter: screen_state=on
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  287): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  287): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  287): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  287): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  287): adev_set_parameters: exit with code(0)
V/AudioPolicyService(  287): AudioCommandThread() adding set parameter string hotword_active=0, io 23 ,delay 0
V/AudioPolicyService(  287): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing set parameters string hotword_active=0, io 23
V/AudioFlinger(  287): setParameters(): io 23, keyvalue hotword_active=0, calling pid 287
V/AudioFlinger(  287): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  287): RecordThread: loop starting
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  287): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  287): in_set_parameters: exit: status(0)
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb405e000
V/AudioFlinger(  287): RecordThread: loop stopping
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
V/AudioFlinger(  287): RecordHandle::stop()
V/AudioFlinger(  287): releasing 22 from 1936 for -1
V/AudioFlinger(  287):  decremented refcount to 0
V/AudioFlinger(  287): RecordThread::stop
V/AudioFlinger(  287): purging stale effects
V/AudioPolicyManager(  287): releaseInput() 23
V/AudioPolicyManager(  287): closeInput(23)
V/AudioFlinger(  287): closeInput() 23
V/AudioSystem(  287): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem(  859): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  287): ThreadBase::exit
V/AudioSystem( 2631): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  287): RecordThread: loop starting
V/AudioFlinger(  287): RecordThread 0xb405e000 exiting
D/audio_hw_primary(  287): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  287): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioPolicyService(  287): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  287): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio port list
I/HotwordRecognitionRnr( 1936): Hotword detection finished
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioSystem( 3132): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 23
V/AudioPolicyManager(  287): releaseInput() exit
V/AudioFlinger(  287): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  287): removeClient_l() pid 1936, calling pid 287
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 23
D/GpsLocationProvider(  859): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1802): stopPatternFlashing()
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1802): lockStatus = 0
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
,D/LEDHandler( 1802): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 3
D/NfcService( 1785): Discovery configuration equal, not updating.
D/Ulp_jni (  859): JNI:system_update. Event-0
,D/SplitWindow(  859): check instance of lgWin Window{33a2e6eb u0 SearchPanel}
,D/InputDispatcher(  859): Window went away: Window{13aa679b u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2603): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:4:0
D/WeatherService( 2603): 2 : ACTION screen on
D/WeatherService( 2603): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2603): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2603): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:4:0
D/AppCleanupService( 3789): android.intent.action.SCREEN_ON
,V/AudioFlinger(  287): setParameters(): io 0, keyvalue screen_state=off, calling pid 859
D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: enter: screen_state=off
V/compress_voip(  287): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  287): voice_extn_compress_voip_set_parameters: exit
V/voice   (  287): voice_set_parameters: exit with code(0)
,V/msm8974_platform_lge(  287): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  287): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  287): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  287): adev_set_parameters: exit with code(0)
D/WifiController(  859): CMD_SCREEN_OFF 
D/WifiController(  859): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  859): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn on led
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
D/VolumeVibrator( 1802): clear
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
W/ActivityManager(  859): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2603): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:4:0
D/WeatherService( 2603): 2 : ACTION screen off
D/WeatherService( 2603): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2603): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:4:0
D/AppCleanupService( 3789): android.intent.action.SCREEN_OFF
D/AppCleanupService( 3789): AppUsageStatsSaveTask
E/NxpNfcJni( 1785): getReconnectState = 0x0
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/Sensors (  425): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{237a1c48 type 2 when 162720 com.android.systemui} when 162720
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 175159130927; DSPS: 5831224; Offset : -2800855530
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  283): App 1000 tries DNS query. Accept family:0 protocol:0
V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{374c2ae1 type 2 when 186970 android} when 186970
V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{b850006 type 2 when 188195 com.google.android.gms} when 188195
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/NotificationManager( 1936): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 13561(787KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/19MB, paused 2.288ms total 117.154ms
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 195162002898; DSPS: 6486678; Offset : -2800852185
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 215164557838; DSPS: 7142122; Offset : -2800860853
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  859): acquireWakeLockInternal: lock=933771399, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=859
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{3a234863 type 2 when 189933 com.google.android.gms} when 189933
V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{20a62c60 type 2 when 202920 com.google.android.gms} when 202920
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx(  859): releaseWakeLockInternal: lock=933771399 [*alarm*], flags=0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 235167137779; DSPS: 7797567; Offset : -2800874750
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 255169713657; DSPS: 8453011; Offset : -2800862322
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 275171420728; DSPS: 9108427; Offset : -2800864444
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  859): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 295173975777; DSPS: 9763871; Offset : -2800872844
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 315176521238; DSPS: 10419314; Offset : -2800860473
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 335179073207; DSPS: 11074758; Offset : -2800871903
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  859): remove 27a8db78
,D/LocationManagerService(  859): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  859): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  859): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  859): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 355181758984; DSPS: 11730206; Offset : -2800871464
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 375184315329; DSPS: 12385650; Offset : -2800878856
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  283): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{2bb92fb7 type 2 when 377377 com.google.android.gms} when 377377
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 395186807457; DSPS: 13041091; Offset : -2800858443
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 415189194168; DSPS: 13696529; Offset : -2800852026
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 435191927441; DSPS: 14351979; Offset : -2800865464
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 455194479673; DSPS: 15007423; Offset : -2800876709
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 475197021749; DSPS: 15662866; Offset : -2800867593
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 495199569033; DSPS: 16318309; Offset : -2800852982
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 515201497883; DSPS: 16973733; Offset : -2800877256
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 535204050321; DSPS: 17629176; Offset : -2800858064
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 555206450782; DSPS: 18284615; Offset : -2800868309
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 575209000149; DSPS: 18940058; Offset : -2800851928
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 595211899778; DSPS: 19595513; Offset : -2800851546
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 615214450239; DSPS: 20250957; Offset : -2800864561
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 635216997574; DSPS: 20906400; Offset : -2800850289
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 655219403556; DSPS: 21561839; Offset : -2800855040
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  859): acquireWakeLockInternal: lock=933771399, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=859
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{28ed4324 type 2 when 668501 com.google.android.gms} when 668501
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerManagerServiceEx(  859): releaseWakeLockInternal: lock=933771399 [*alarm*], flags=0x0
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 675221947976; DSPS: 22217283; Offset : -2800874148
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 695224498123; DSPS: 22872726; Offset : -2800857012
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 715227044210; DSPS: 23528170; Offset : -2800874402
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 735228698734; DSPS: 24183584; Offset : -2800867802
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 755231245705; DSPS: 24839027; Offset : -2800853815
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 775232871167; DSPS: 25494441; Offset : -2800876250
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/WifiController(  859): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 795235269909; DSPS: 26149879; Offset : -2800857827
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 815237299014; DSPS: 26805306; Offset : -2800873583
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 835239848592; DSPS: 27460749; Offset : -2800856547
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 855242265772; DSPS: 28116189; Offset : -2800881241
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 875244815452; DSPS: 28771632; Offset : -2800864494
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 895247360600; DSPS: 29427075; Offset : -2800852254
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 915249905227; DSPS: 30082519; Offset : -2800870713
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 935252452409; DSPS: 30737962; Offset : -2800856776
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 955255009691; DSPS: 31393406; Offset : -2800863101
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 975257426249; DSPS: 32048845; Offset : -2800857432
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 995259973843; DSPS: 32704289; Offset : -2800873081
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1015262528839; DSPS: 33359732; Offset : -2800851226
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1035265079453; DSPS: 34015176; Offset : -2800864087
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1055267485694; DSPS: 34670615; Offset : -2800868528
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1075269340740; DSPS: 35326036; Offset : -2800875236
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1095271759377; DSPS: 35981475; Offset : -2800867566
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1115274312964; DSPS: 36636919; Offset : -2800877402
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1135276861812; DSPS: 37292362; Offset : -2800861487
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1155278377428; DSPS: 37947772; Offset : -2800871569
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1175280360594; DSPS: 38603197; Offset : -2800871993
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1195282910589; DSPS: 39258640; Offset : -2800855218
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1215285317978; DSPS: 39914079; Offset : -2800858560
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  859): User[0] Flushing usage stats to disk
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1235287869744; DSPS: 40569523; Offset : -2800870454
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  859): acquireWakeLockInternal: lock=933771399, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=859
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{3e0053f9 type 2 when 1250711 com.google.android.gms} when 1250711
D/PowerManagerServiceEx(  859): releaseWakeLockInternal: lock=933771399 [*alarm*], flags=0x0
,D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  283): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1255290739264; DSPS: 41224977; Offset : -2800869456
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1275293291393; DSPS: 41880421; Offset : -2800880934
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1295295844929; DSPS: 42535864; Offset : -2800860382
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1315297354450; DSPS: 43191274; Offset : -2800876350
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1335299640744; DSPS: 43846709; Offset : -2800879213
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1355302189701; DSPS: 44502152; Offset : -2800863241
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1375304733646; DSPS: 45157595; Offset : -2800852254
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1395307277077; DSPS: 45813039; Offset : -2800872327
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1415309830662; DSPS: 46468482; Offset : -2800851441
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1435312374405; DSPS: 47123926; Offset : -2800871381
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1455314927732; DSPS: 47779370; Offset : -2800881531
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1475317325691; DSPS: 48434808; Offset : -2800863761
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1495319876153; DSPS: 49090252; Offset : -2800876724
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1515322545566; DSPS: 49745699; Offset : -2800862627
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1535325093482; DSPS: 50401143; Offset : -2800878161
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1555327641284; DSPS: 51056586; Offset : -2800863318
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1575330661957; DSPS: 51712045; Offset : -2800863652
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/art     (  859): Explicit concurrent mark sweep GC freed 56461(3MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/35MB, paused 3.942ms total 228.465ms
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1595333080229; DSPS: 52367484; Offset : -2800856423
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1615334729076; DSPS: 53022898; Offset : -2800855421
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1635337272297; DSPS: 53678342; Offset : -2800875834
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1655339816925; DSPS: 54333785; Offset : -2800864034
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1675342363220; DSPS: 54989228; Offset : -2800850881
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1695344500034; DSPS: 55644659; Offset : -2800880450
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1715347047163; DSPS: 56300102; Offset : -2800866541
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1735349591947; DSPS: 56955545; Offset : -2800854820
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1755352138501; DSPS: 57610989; Offset : -2800871639
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1775354683811; DSPS: 58266432; Offset : -2800859262
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1795357228433; DSPS: 58921876; Offset : -2800878115
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1815359755563; DSPS: 59577318; Offset : -2800853271
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1835362296335; DSPS: 60232762; Offset : -2800876183
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1855364840180; DSPS: 60888205; Offset : -2800865323
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1875366861686; DSPS: 61543631; Offset : -2800858030
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  859): Prepared write state in 12ms
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4864): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4864): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  283): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  283): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  283): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ProcessStatsService(  859): Pruning old procstats: /data/system/procstats/state-2015-12-08-07-13-23.bin
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 1895369260529; DSPS: 62199070; Offset : -2800869945
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5851): 
D/AndroidRuntime( 5851): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5851): CheckJNI is OFF
D/AndroidRuntime( 5851): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  859): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  859): Killing 5244:com.test.thalitest/u0a316 (adj 13): stop com.test.thalitest
W/PackageSettings(  859): Skipping PackageSetting{9100caf com.example.hello/10030} due to missing metadata
I/ActivityManager(  859): Killing 5167:com.android.calendar/u0a13 (adj 15): empty for 1818s
I/ActivityManager(  859): Killing 4906:com.lge.qremote/u0a106 (adj 15): empty for 1822s
I/ActivityManager(  859): Killing 4605:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty for 1822s
W/ActivityManager(  859): Spurious death for ProcessRecord{32a342d9 5244:com.test.thalitest/u0a316}, curProc for 5244: null
W/libprocessgroup(  859): failed to open /acct/uid_10013/pid_5167/cgroup.procs: No such file or directory
I/ActivityManager(  859): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/art     ( 1876): Explicit concurrent mark sweep GC freed 8895(504KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 1.842ms total 45.535ms
W/libprocessgroup(  859): failed to open /acct/uid_10106/pid_4906/cgroup.procs: No such file or directory
E/lowmemorykiller(  242): Error opening /proc/4605/oom_score_adj; errno=2
I/art     ( 1936): Explicit concurrent mark sweep GC freed 2450(158KB) AllocSpace objects, 2(689KB) LOS objects, 40% free, 12MB/20MB, paused 1.759ms total 78.776ms
W/ActivityManager(  859): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  859): android.os.DeadObjectException
W/ActivityManager(  859): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  859): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  859): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  859): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  859): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  859): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  859): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  859): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  859): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  859): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/ActivityManager(  859): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  859): android.os.DeadObjectException
W/ActivityManager(  859): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  859): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  859): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  859): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  859): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  859): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  859): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  859): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  859): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  859): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  859): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  859): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/libprocessgroup(  859): failed to open /acct/uid_10089/pid_4605/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3383): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3383): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3383): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3383): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3383): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3383): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3383): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3383): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3383): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3383): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3383): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3383): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  859): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  859): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5876 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  859): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5892 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     (  859): Explicit concurrent mark sweep GC freed 16909(1259KB) AllocSpace objects, 6(200KB) LOS objects, 33% free, 23MB/35MB, paused 17.351ms total 233.229ms
I/art     (  859): WaitForGcToComplete blocked for 70.030ms for cause Explicit
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/LockScreenSettings( 5892): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
W/ResourcesManager( 5876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5876): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/ResourcesManager( 5876): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/administrator(  859): Handling package changes for user 0
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/ActivityManager(  859): Killing 5139:com.android.providers.calendar/u0a14 (adj 15): empty for 1815s
D/KeyguardModel( 1372): handleShortcutListChanged...
W/libprocessgroup(  859): failed to open /acct/uid_10014/pid_5139/cgroup.procs: No such file or directory
I/art     (  859): Explicit concurrent mark sweep GC freed 5496(289KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.142ms total 228.643ms
I/NotificationService(  859): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  859): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  859): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  859): removeObsoleteFile: deleting file=220_task.xml
D/TaskPersister(  859): removeObsoleteFile: deleting file=220_task_thumbnail.png
I/LGEmail ( 5876): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 5876): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 5851): Shutting down VM
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
W/ResourcesManager(  859): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  859): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/PackageChangeReceiver( 5876): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  859): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5924 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  859): Killing 5363:com.google.android.gms:car/u0a6 (adj 15): empty for 1808s
W/libprocessgroup(  859): failed to open /acct/uid_10006/pid_5363/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 5924): onCreate
W/AppUp4:DB( 5924):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5924):  setFingerPrint start
I/AppUp4:DB( 5924):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5924):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5924):  SDK version = 0
I/AppUp4:DB( 5924):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5924): AppBoxApplication onCreate()
E/SQLiteLog( 5924): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
E/SQLiteDatabase( 5924): Error inserting package=com.test.thalitest
E/SQLiteDatabase( 5924): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5924): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5924): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
E/SQLiteDatabase( 5924): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 5924): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5924): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
E/SQLiteDatabase( 5924): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
E/SQLiteDatabase( 5924): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 5924): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 5924): 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
E/SQLiteDatabase( 5924): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 5924): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 5924): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 5924): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 5924): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 5924): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/SQLiteDatabase( 5924): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/SQLiteDatabase( 5924): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/SQLiteDatabase( 5924): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5924): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5924): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 5924): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5924): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5924): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 5924): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  859): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=5943 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a

```
