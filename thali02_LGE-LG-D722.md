#### Test 50650278dbf8a2a_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/Finsky  ( 4971): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
--------- beginning of system
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{4a946fb type 0 when 1450226345421 com.android.vending} when 1450226345421
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  841): Explicit concurrent mark sweep GC freed 15059(697KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.286ms total 163.541ms
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1728): Explicit concurrent mark sweep GC freed 26183(1552KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 13MB/22MB, paused 1.701ms total 81.606ms
,I/NotificationManager(  841): android: cancelAsUser(2) by android
D/libc-netbsd( 4971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  268): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  841): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4971): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  841): android: cancelAsUser(2) by android
D/libc-netbsd( 4971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  841): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5474 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  841): android: cancelAsUser(2) by android
D/libc-netbsd( 4971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 4971): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5474): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5474): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5474): VM with version 2.1.0 has multidex support
I/MultiDex( 5474): install
I/MultiDex( 5474): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5474): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 5474): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5474): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2df8ab3a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
D/AndroidRuntime( 5471): 
D/AndroidRuntime( 5471): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ProviderInstaller( 5474): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5474): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5474): com.google.android.gms: cancel(39789) by com.google.android.gms
D/AndroidRuntime( 5471): CheckJNI is OFF
D/WearableService( 1728): callingUid 10006, callindPid: 1728
D/ChimeraCfgMgr( 5474): Reading stored module config
E/MDM     ( 1728): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5276): Restart initialization of location
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 5474): Loading module com.google.android.gms.car from APK com.google.android.gms
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
D/CAR.SERVICE( 5474): Connecting to CarCallService...
D/NativeLibraryUtils( 5474): Install completed successfully. count=14 extracted=0
I/art     ( 5474): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5474): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 5474): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 5474): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5474): Creating a new PhoneAdapter instance
W/ActivityManager(  841): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5474): setListener: com.google.android.gms.car.dn@23f17351
W/ActivityManager(  841): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5474): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5474): Starting CarCallService with initial phone null
I/NotificationManager( 5474): com.google.android.gms: cancel(10436) by com.google.android.gms
D/AndroidRuntime( 5471): Calling main entry com.android.commands.am.Am
D/CAR.SERVICE( 5474): Package validated; name: com.android.vending
I/ActivityManager(  841): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  841): setTaskToReturnTo : TaskRecord{220b4354 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  841): setTaskToReturnTo : TaskRecord{220b4354 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  841): AppWindowTokenEx init.. 
D/ContextHelper(  841): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
D/InputDispatcher(  841): Focus left window: Window{2097e810 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5471): Shutting down VM
I/[LGHome]EVENT( 1872): [Launcher.java:986:onPause()]onPause
I/NotificationManager( 4971): com.android.vending: cancel(10436) by com.android.vending
D/SplitWindow(  841): check instance of lgWin Window{b25253e u0 Starting com.test.thalitest}
V/Finsky  ( 4971): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/ActivityManager(  841): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5533 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1872): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1936): Closing mic
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@3881d877
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  272): RecordHandle::stop()
V/AudioFlinger(  272): RecordThread::stop
V/AudioFlinger(  272): Record stopped OK
V/AudioPolicyManager(  272): stopInput() input 16
V/AudioPolicyService(  272): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  272): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioPolicyService(  272): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  272): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  272): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  272): ThreadBase::setParameters() routing=0
D/audio_hw_primary(  272): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/[LGHome]EVENT( 1872): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  841): Starting window displayed
V/audio_hw_primary(  272): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  272): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  272): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  272): disable_audio_route: reset and update mixer path: audio-record
I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/audio_hw_primary(  272): disable_audio_route: exit
E/audio_hw_primary(  272): disable_snd_device: enter 144
D/hardware_info(  272): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  272): disable_snd_device: snd_device(144: lg-vr-handset-mic)
W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2299adbe,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  272): stop_input_stream: exit: status(0)
V/audio_hw_primary(  272): in_standby: exit:  status(0)
V/AudioFlinger(  272): RecordThread: loop stopping
V/AudioFlinger(  272): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  272): RecordThread: loop starting
V/AudioFlinger(  272): processConfigEvents_l() remaining events 1
V/AudioFlinger(  272): processConfigEvents_l() DONE thread 0xb384e000
V/AudioFlinger(  272): RecordThread: loop stopping
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
V/AudioPolicyManager(  272): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  272): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  272): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  272): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioPolicyService(  272): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
D/BarTransitions( 1370): draw background and invalidate : color = 16000000
,V/AudioPolicyService(  272): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  272): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioPolicyService(  272): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  272): setParameters(): io 16, keyvalue hotword_active=0, calling pid 272
V/AudioFlinger(  272): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  272): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  272): RecordThread: loop starting
D/BarTransitions( 1370): draw background and invalidate : color = 18171717
V/AudioFlinger(  272): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  272): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  272): in_set_parameters: exit: status(0)
V/AudioFlinger(  272): processConfigEvents_l() DONE thread 0xb384e000
V/AudioFlinger(  272): RecordThread: loop stopping
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
V/AudioRecord( 1936): stop()
,V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioFlinger(  272): RecordHandle::stop()
V/AudioFlinger(  272): RecordThread::stop
,V/AudioFlinger(  272): releasing 15 from 1936 for -1
V/AudioFlinger(  272):  decremented refcount to 0
V/AudioPolicyManager(  272): releaseInput() 16
V/AudioFlinger(  272): purging stale effects
V/AudioPolicyManager(  272): closeInput(16)
V/AudioFlinger(  272): closeInput() 16
V/AudioSystem(  272): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  841): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1745): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  272): ThreadBase::exit
V/AudioFlinger(  272): RecordThread: loop starting
V/AudioFlinger(  272): RecordThread 0xb384e000 exiting
D/audio_hw_primary(  272): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  272): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  272): in_standby: exit:  status(0)
V/AudioSystem( 3116): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyService(  272): AudioCommandThread() adding update audio port list
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyService(  272): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioSystem( 2762): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyService(  272): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
V/AudioPolicyManager(  272): releaseInput() exit
V/AudioFlinger(  272): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  272): removeClient_l() pid 1936, calling pid 272
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
I/HotwordRecognitionRnr( 1936): Hotword detection finished
,D/ContextHelper( 5533): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 5533): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/NotificationManager(  841): android: cancelAsUser(2) by android
,D/libc-netbsd( 4971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4971): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4971): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 4971): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{1cd59b69 type 0 when 1450226347240 com.android.vending} when 1450226347240
D/Finsky  ( 4971): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,I/LibraryLoader( 5533): Time to load native libraries: 3 ms (timestamps 4224-4227)
,I/LibraryLoader( 5533): Expected native library version number "",actual native library version number ""
D/DeviceConnectionService( 1728): client connected with version: 8296000
D/Finsky  ( 4971): [594] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,V/WebViewChromiumFactoryProvider( 5533): Binding Chromium to main looper Looper (main, tid 1) {a4a5bb8}
I/LibraryLoader( 5533): Expected native library version number "",actual native library version number ""
,I/chromium( 5533): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/libc-netbsd( 4971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/BrowserStartupController( 5533): Initializing chromium process, singleProcess=true
D/libc-netbsd( 4971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  268): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
W/art     ( 5533): Attempt to remove local handle scope entry from IRT, ignoring
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  841): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/SysUtils( 5533): ApplicationContext is null in ApplicationStatus
W/chromium( 5533): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5533): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5533): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5533): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5533): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5533): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5533): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5533): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5533): Remote Branch: 
I/Adreno-EGL( 5533): Local Patches: 
I/Adreno-EGL( 5533): Reconstruct Branch: 
,V/AudioPolicyService(  272): registerClient() client 0xb57e9620, uid 10316
,D/BluetoothManagerService(  841): Message: 20
,D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24de1f20:true
D/BluetoothAdapter( 5533): 31863245: getState() :  mService = null. Returning STATE_OFF
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 94648857781; DSPS: 3192792; Offset : -2793335315
W/art     ( 5533): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5533): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5533): CordovaWebView is running on device made by: LGE
,W/art     ( 5533): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5533): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 5533): Activity.onPostResume() called 
,D/OpenGLRenderer( 5533): Render dirty regions requested: true
I/OpenGLRenderer( 5533): Initialized EGL, version 1.4
D/OpenGLRenderer( 5533): Enabling debug mode 0
,D/Atlas   ( 5533): Validating map...
,D/SplitWindow(  841): check instance of lgWin Window{7c79050 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5533): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  841): Focus entered window: Window{7c79050 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  841): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  841): Displayed com.test.thalitest/.MainActivity: +1s297ms
I/Timeline(  841): Timeline: Activity_windows_visible id: ActivityRecord{144772fd u0 com.test.thalitest/.MainActivity t220} time:94995
I/Timeline( 5533): Timeline: Activity_idle id: android.os.BinderProxy@1b908594 time:95002
W/BindingManager( 5533): Cannot call determinedVisibility() - never saw a connection for the pid: 5533
,D/JsMessageQueue( 5533): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5533): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622845952
,D/JX-Cordova( 5533): jxcore cordova android initializing
I/art     ( 5533): CheckpointMarkThreadRoots callback created = 0xb00ecd20
,I/art     ( 5533): CheckpointMarkThreadRoots callback created = 0xb00eccf0
,W/jxcore-log( 5533): Initializing JXcore engine
,W/jxcore-log( 5533): JXcore engine is ready
W/jxcore-log( 5533): Starting JXcore engine
,W/.test.thalitest( 5533): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7325]" dev="sockfs" ino=7325 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5533): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5533): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7483]" dev="sockfs" ino=7483 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5533): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5533): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5533): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25687]" dev="sockfs" ino=25687 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5533): Platform android
W/jxcore-log( 5533): 
,W/jxcore-log( 5533): Process ARCH arm
W/jxcore-log( 5533): 
I/ActivityManager(  841): Killing 5248:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10086/pid_5248/cgroup.procs: No such file or directory
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5533): JXcore Cordova bridge is ready!
I/jxcore-log( 5533): 
,W/jxcore-log( 5533): JXcore engine is started
I/chromium( 5533): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5533): Skipped 171 frames!  The application may be doing too much work on its main thread.
,D/CAR.SERVICE( 5474): mConnectedToCar = false, abort
,E/ActivityThread( 5474): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f0f9a19 that was originally bound here
E/ActivityThread( 5474): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f0f9a19 that was originally bound here
E/ActivityThread( 5474): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5474): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5474): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5474): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5474): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5474): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5474): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5474): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5474): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5474): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5474): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5474): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5474): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5474): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5474): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5474): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5474): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5474): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5474): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5474): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5474): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5474): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 5474): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@331e8078 that was originally bound here
E/ActivityThread( 5474): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@331e8078 that was originally bound here
E/ActivityThread( 5474): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5474): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5474): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5474): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5474): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5474): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5474): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5474): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5474): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5474): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5474): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5474): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5474): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5474): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 5474): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5474): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5474): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5474): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5474): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5474): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5474): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  841): Unbind failed: could not find connection for android.os.BinderProxy@299d1968
,I/jxcore-log( 5533): Toggling radios to true
I/jxcore-log( 5533): 
,D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  841): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService(  841): Message: 1
D/BluetoothManagerService(  841): MESSAGE_ENABLE: mBluetooth = null
,D/BluetoothAdapterService(522550116)( 1966): onBind()
,D/BluetoothManagerService(  841): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  841): Message: 40
D/BluetoothManagerService(  841): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/LocationManagerService(  841): getAllProviders()=[passive, gps, network]
,D/WifiServiceImplEx(  841): setWifiEnabled: true pid=5533, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  841): setWifiEnabled: true pid=5533, uid=10316
D/Ulp_jni (  841): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni (  841): JNI:system_update. Event-4
,D/LocationManagerService(  841): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  841): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  841): JNI:system_update. Event-4
D/WifiServiceImplEx(  841): disconnect pid=5533, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  841): reconnect pid=5533, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5533): Radios toggled
I/jxcore-log( 5533): 
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bluedroid( 1966): config_hci_snoop_log
D/BluetoothManagerService(  841): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  841): Broadcasting onBluetoothServiceUp() to 9 receivers.
I/LGFTMITEM(  841): [GET_FTM][id=6], offset=12288
E/WifiHW  (  841): Wifi MAC Address = a0:39:f7:70:12:80
E/WifiHW  (  841): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  841): band=b
E/WifiHW  (  841): ": cur_etheraddr=a0:39:f7:70:12:80
D/SoftapController(  268): Softap fwReload - Ok
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  268): Setting iface cfg
D/CommandListener(  268): Trying to bring down wlan0
D/CommandListener(  268): Clearing all IP addresses on wlan0
V/LGMDMManagerInternal( 1966): Create singleton instance
E/WifiHW  (  841): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/wpa_supplicant( 5628): Successfully initialized wpa_supplicant
,D/WifiMonitor(  841): startMonitoring(wlan0) with mConnected = false
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,I/wpa_supplicant( 5628): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5628): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:13.9 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/ActivityManager(  841): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5635 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/WifiServerServiceExt(  841): WIFI_STATE_CHANGED_ACTION [2]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothAdapterService(522550116)( 1966): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1966): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1966): Setting state to 11
I/BluetoothAdapterState( 1966): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(522550116)( 1966): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  841): Message: 60
,I/jxcore-log( 5533): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 5533): 
D/BluetoothAdapterService(522550116)( 1966): processStart()
I/jxcore-log( 5533): Perf Test app loaded loaded
I/jxcore-log( 5533): 
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BluetoothManagerService(  841): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  841): Bluetooth State Change Intent: 10 -> 11
I/jxcore-log( 5533): check test folder
I/jxcore-log( 5533): 
D/LGBluetoothAPIService( 1798): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/jxcore-log( 5533): found test : ./testFindPeers.js
I/jxcore-log( 5533): 
,D/BtSettings.ProfileConfig( 1966): Unable to read settings
D/BtSettings.ProfileConfig( 1966): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1966): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1966): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1966): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1966): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1966): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1966): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1966): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1966): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1966): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(522550116)( 1966): processStart() - Make Bond State Machine
I/jxcore-log( 5533): found test : ./testSendData.js
I/jxcore-log( 5533): 
,D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/BluetoothBondStateMachine( 1966): make
D/BluetoothAdapterService( 1966): setAdapterService() - set to: null
I/[SystemUI]BluetoothHandler( 1370): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
D/LGBluetoothServiceAdapter( 1966): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 1966): StableState(): Entering Off State
,D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1966): Unable to read settings
D/BtSettings.ProfileConfig( 1966): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1966): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1966): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1966): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1966): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1966): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1966): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1966): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1966): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1966): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1966): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1966): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 1966): Received start request. Starting profile...
D/BluetoothHeadset( 1745): Proxy object connected
D/BluetoothHeadset(  841): Proxy object connected
D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1966): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
I/LGBluetoothHeadsetServiceJni( 1966): classInitNative: succeeds
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
,D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1966): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1966): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/LGBluetoothFeatureConfig( 1966): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1966): classInitNative: succeeds
,D/BluetoothHeadset( 1745): Proxy object connected
D/HeadsetStateMachine( 1966): make
D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothHeadset( 1745): Proxy object connected
,D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1966): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1966): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1966): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1966): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1966): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1966): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1966): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1966): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(522550116)( 1966): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/LGMDMManager( 1966): Create singleton instance
,I/BluetoothAdapterState( 1966): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 1966): max_hf_connections = 1
I/bluedroid( 1966): get_profile_interface handsfree
I/bt-btif ( 1966): btif_hf_get_interface
I/bt-btif ( 1966): init
D/bt-btif ( 1966): max_hf_clients = 1
D/bt-btif ( 1966): btif_max_hf_clients = 1
D/bt-btif ( 1966): btif_enable_service: current services:0xa06b6330
V/ToneGenerator( 1966): ToneGenerator constructor: streamType=8, volume=1.000000
,V/AudioPolicyService(  272): registerClient() client 0xb57e9440, uid 1002
V/AudioPolicyManager(  272): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  272): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  272): getOutput() returns output 2
V/AudioFlinger(  272): registerClient() client 0xb40330b8, pid 1966
V/AudioFlinger(  272): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  272): thread 0xb5651000 type 0 TID 1292 waking up
V/AudioFlinger(  272): processConfigEvents_l() remaining events 1
V/AudioFlinger(  272): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  272): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  272): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  841): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  841): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  272): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 2762): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1966): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2762): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1966): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioFlinger(  272): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  272): sendConfigEvent_l() num events 1 event 0
,V/AudioFlinger(  272): thread 0xb56eb000 type 0 TID 1293 waking up
V/AudioFlinger(  272): thread 0xb5735000 type 0 TID 1295 waking up
V/ToneGenerator( 1966): Create Track: 0xb4909480
V/AudioTrack( 1966): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1966): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioFlinger(  272): processConfigEvents_l() remaining events 1
V/AudioFlinger(  272): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  272): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  272): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 2
V/AudioFlinger(  272): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioFlinger(  272): processConfigEvents_l() remaining events 1
V/AudioFlinger(  272): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  272): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  272): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  272): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem(  841): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  841): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  841): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  841): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1966): ioConfigChanged() event 0, ioHandle 4
I/AudioFlinger(  272): isAudioPlaybackHookOn() false
V/AudioSystem( 1966): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1966): ioConfigChanged() event 0, ioHandle 6
D/AudioTrack( 1966): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioSystem( 1966): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 2762): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2762): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  272): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioSystem( 2762): ioConfigChanged() event 0, ioHandle 6
V/AudioPolicyManager(  272): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioSystem( 2762): ioConfigChanged() opening already existing output! 6
V/AudioPolicyManagerEx(  272): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  272): getOutput() returns output 2
V/AudioSystem( 1966): getLatency() output 2, latency 50
V/AudioSystem( 1966): getFrameCount() output 2, frameCount 960
,V/AudioTrack( 1966): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1966): Create normal PCM 0x1 Track
V/AudioSystem( 1936): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1936): ioConfigChanged() opening already existing output! 2
,V/AudioSystem( 1370): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1370): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  272): createTrack() lSessionId: 21
V/AudioFlinger(  272): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  272): sendConfigEvent_l() num events 1 event 1
V/AudioSystem( 3116): ioConfigChanged() event 0, ioHandle 2
V/AudioTrack( 1966): Flags here  0x4 
,V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 1966): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioSystem( 3116): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1370): ioConfigChanged() event 0, ioHandle 4
V/AudioFlinger(  272): acquiring 21 from 1966, for 1966
V/AudioFlinger(  272):  added new entry for 21,
V/ToneGenerator( 1966): ToneGenerator INIT OK, time: 101184
V/AudioSystem( 1936): ioConfigChanged() event 0, ioHandle 4
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
V/AudioSystem( 1936): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1370): ioConfigChanged() opening already existing output! 4
,V/AudioSystem( 3116): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 4
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
V/AudioFlinger(  272): processConfigEvents_l() remaining events 1
V/AudioFlinger(  272): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1936): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1936): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1370): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1370): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3116): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3116): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3116): ioConfigChanged() opening already existing output! 6
D/A2dpService( 1966): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 1966): classInitNative: succeeds
D/HeadsetStateMachine( 1966): Enter Disconnected: -2, size: 0
V/Avrcp   ( 1966): make
D/Avrcp   ( 1966): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1966): get_profile_interface avrcp
D/BluetoothA2dp(  841): Proxy object connected
D/HeadsetPhoneState( 1966): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1966): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1966): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  272): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1966
I/bt-btif ( 1966): btif_rc_get_interface
I/bt-btif ( 1966): ## init ##
,D/audio_hw_primary(  272): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  272): voice_set_parameters: enter: bt_samplerate=8000
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: exit
V/voice   (  272): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  272): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  272): platform_set_parameters: enter: bt_samplerate=8000
I/LGBluetoothAvrcpServiceJni( 1966): classInitNative: succeeds
,I/LGBluetoothAvrcpAdapter( 1966): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
V/msm8974_platform(  272): platform_set_parameters: exit with code(0)
I/LGBluetoothAvrcpServiceJni( 1966): initNative: succeeds
V/lge_audio_loopback(  272): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  272): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1966): ToneGenerator destructor
V/ToneGenerator( 1966): stopTone
V/ToneGenerator( 1966): Delete Track: 0xb4909480
V/AudioFlinger(  272): remove track (4099) and delete from mixer
V/AudioTrack( 1966): ~AudioTrack, releasing session id from 1966 on behalf of 1966
V/AudioPolicyService(  272): AudioCommandThread() adding release output 2
V/AudioPolicyService(  272): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  272): releasing 21 from 1966 for 1966
V/AudioFlinger(  272):  decremented refcount to 0
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioFlinger(  272): purging stale effects
V/AudioPolicyService(  272): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  272): releaseOutput() 2
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
V/AudioFlinger(  272): PlaybackThread::Track destructor
V/AudioFlinger(  272): removeClient_l() pid 1966, calling pid 272
I/chromium( 5533): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  841): Process com.google.android.gm (pid 5077) has died
,I/BluetoothAvrcpBrcmAdapterJni( 1966): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 1966): initBrcmNative
,V/AudioService(  841): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
E/AudioService(  841): No RCC entry present to update
,E/RemoteController( 1966): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1966): classInitNative
I/BluetoothA2dpServiceJni( 1966): classInitNative: succeeds
D/A2dpStateMachine( 1966): make
I/bluedroid( 1966): get_profile_interface a2dp
I/bt-btif ( 1966): btif_av_get_src_interface
I/bt-btif ( 1966): init
D/bt-btif ( 1966): btif_enable_service: current services:0xa06b6330
I/LGBluetoothA2dpServiceJni( 1966): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1966): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1966): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1966): [BTUI] init
I/ActivityManager(  841): Process com.lge.qremote (pid 5033) has died
D/UEI.SmartControl( 5053): Service.onUnbind: IControl
,D/UEI.SmartControl( 5053): Service.onDestroy
D/LGBluetoothPowerControlManager( 1966): [BTUI] init : getProfileProxy
D/UEI.SmartControl( 5053): Shutdown IRRCPlayer... 
D/BluetoothManagerService(  841): Message: 30
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
I/BluetoothHidServiceJni( 1966): classInitNative: succeeds
W/ResourcesManager( 5635): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/A2dpStateMachine( 1966): Enter Disconnected: -2
W/ResourcesManager( 5635): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 5635): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5635): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5635): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/HidService( 1966): Received start request. Starting profile...
I/bluedroid( 1966): get_profile_interface hidhost
I/bt-btif ( 1966): btif_hh_get_interface
I/bt-btif ( 1966): init
D/bt-btif ( 1966): btif_enable_service: current services:0xa06b6330
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
I/BluetoothHealthServiceJni( 1966): classInitNative: succeeds
D/HealthService( 1966): Received start request. Starting profile...
W/irrc_jni( 5053): IRRCPlayer_nativeFinalize ++ 
I/bluedroid( 1966): get_profile_interface health
D/irrcClient( 5053): ~IrrcClient ++ 
I/bt-btif ( 1966): btif_hl_get_interface
D/irrcClient( 5053): ~IrrcClient -- 
I/bt-btif ( 1966): init
D/bt-btif ( 1966): Process name (droid.bluetooth)
D/bt-btif ( 1966): btif_hl_soc_thread_init
W/irrc_jni( 5053): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5053): Blaster closed
D/UEI.SmartControl( 5053): Blaster closed
D/UEI.SmartControl( 5053): Shut down QS...
D/UEI.SmartControl( 5053): Stopped file observer...
D/bt-btif ( 1966): create_thread: entered
D/bt-btif ( 1966): create_thread: thread created successfully
D/bt-btif ( 1966): entered btif_hl_select_thread
D/bt-btif ( 1966): btif_hl_select_wakeup_init
D/bt-btif ( 1966): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1966): max_s=55 
D/bt-btif ( 1966): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1966): classInitNative: succeeds
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
I/BluetoothPanServiceJni( 1966): classInitNative(L105): succeeds
,I/UEI.SmartControl( 5053): QS lib stop result = true
D/UEI.SmartControl( 5053): QS shutdown complete
D/PanService( 1966): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1966): initializeNative(L110): pan
I/bluedroid( 1966): get_profile_interface pan
D/bt-btif ( 1966): stack_initialized = 0, btpan_cb.enabled:0
I/LGBluetoothPanAdapter( 1966): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
,I/BtGatt.JNI( 1966): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 1966): handleDebugAction() action=null
D/BtGatt.GattService( 1966): Received start request. Starting profile...
D/BtGatt.GattService( 1966): start()
I/bluedroid( 1966): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1966): advertise manager created
I/LGBluetoothGattAdapter( 1966): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1966): setGattService:  set to: null
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
,D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
I/LGBluetoothMapAdapter( 1966): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1966): BluetoothMapBinder()
D/BluetoothMapService( 1966): Received start request. Starting profile...
D/BluetoothMapService( 1966): start()
D/BluetoothMapEmailSettingsLoader( 1966): Found 0 applications
D/BluetoothMapEmailAppObserver( 1966): createReceiver()
,D/BluetoothMapEmailAppObserver( 1966): initObservers()
D/BluetoothMapEmailAppObserver( 1966): getEnabledAccountItems()
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
,I/BluetoothSAPServiceJni( 1966): classInitNative(L170): succeeds
D/SapService( 1966): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1966): initializeNative(L175): sap
I/bluedroid( 1966): get_profile_interface sap
I/bt-btif ( 1966): btif_sc_get_interface
I/bt-btif ( 1966): init
D/bt-btif ( 1966): btif_enable_service: current services:0xa06b6330
I/LGBluetoothSapAdapter( 1966): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1966): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1966): [BTUI] initSapManager
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
D/LgeBluetoothSimManager( 1745): [BTUI] SAP_ENABLE_EVT
,V/BluetoothFTPServiceJni( 1966): classInitNative
I/BluetoothFTPServiceJni( 1966): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
D/BluetoothFTPService( 1966): BluetoothFtpBinder()
D/**BluetoothFTPService( 1966): Received start request. Starting profile...
V/BluetoothFTPService( 1966): FTP-Server Service start
D/BluetoothFTPServiceJni( 1966): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1966): get_profile_interface ftp
I/bt-btif ( 1966): btif_fts_get_interface
I/bt-btif ( 1966): init
D/bt-btif ( 1966): btif_enable_service: current services:0xa06b6330
D/BluetoothFTPServiceJni( 1966): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
D/LGBluetoothFeatureConfig( 1966): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1966): classInitNative
I/BluetoothOPPServiceJni( 1966): classInitNative(L373): succeeds
,V/OppService( 1966): Opp initBinder
D/**OppService( 1966): Received start request. Starting profile...
D/OppService( 1966): Starting OppService 
D/LGBluetoothOppAdapter( 1966): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1966): com.android.bluetooth: cancelAll by com.android.bluetooth
I/IndexDatabaseHelper( 5635): Using schema version: 115
V/BluetoothOppNotification( 1966): send message
I/IndexDatabaseHelper( 5635): Index is fine
,D/BluetoothOppPreference( 1966): Dumping Names:  
D/BluetoothOppPreference( 1966): {}
D/BluetoothOppPreference( 1966): Dumping Channels:  
D/BluetoothOppPreference( 1966): {}
D/OppService( 1966): Start()
W/BluetoothOPPServiceJni( 1966): initOppNative
D/BluetoothOPPServiceJni( 1966): initOppNative(L383): OPP
I/bluedroid( 1966): get_profile_interface opp
I/bt-btif ( 1966): btif_op_get_interface
D/BluetoothOPPServiceJni( 1966): initOppNative(L411): mOppCallbacksObj 1049850
D/BluetoothOPPServiceJni( 1966): initOppNative(L413): calling OPP init
I/bt-btif ( 1966): btif_opp_init
D/bt-btif ( 1966): btif_enable_service: current services:0xa06b6330
D/BluetoothOPPServiceJni( 1966): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1966): initOppNative(L430): mOppCallbacksObj 1049850
V/OppService( 1966): setOppService(): set to: com.broadcom.bt.service.opp.OppService@347256ea
D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
D/HeadsetStateMachine( 1966): Proxy object connected
D/LGBluetoothHfpAdapter( 1966): [BTUI] queryPhoneState
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1966): Proxy object connected
D/LGBluetoothPowerControlManager( 1966): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@e267ddb
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
,D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 1966): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1966): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1966): pendingUpdate is :  true
D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,V/OppService( 1966): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1966): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1966): Handler(): got msg=1
V/OppService( 1966): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1966): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@2096f7b6 on behalf of 
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@2c851cb7 on behalf of 
V/BluetoothOppNotification( 1966): update too frequent, put in queue
V/OppService( 1966): pendingUpdate is :  false
E/OppService( 1966): UpdateThread is Completed
D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1966): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1966): new notify threadi!
V/BluetoothOppNotification( 1966): send delay message
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - Message: 1
D/BluetoothAdapterService(522550116)( 1966): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1966): isTurningOnRadio()=false
D/BluetoothAdapterState( 1966): isTurningOffRadio()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1966): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1966): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(522550116)( 1966): onProfileServiceStateChange() - All profile services started.
,V/OppService( 1966): ContentObserver received notification
V/OppService( 1966): ContentObserver received notification
V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 1966): pendingUpdate is :  true
V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterState( 1966): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1966): enable
I/bt-btif ( 1966): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1966): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@2ff72c24 on behalf of 
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@388f38d on behalf of 
I/bt_hci_bdroid( 1966): init
I/bt_vendor( 1966): init
I/bt_vnd_conf( 1966): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/GKI_LINUX( 1966): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1966): btu_task pending for preload complete event
I/bt_vnd_conf( 1966): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1966): libbt-hci init returns 0
,V/BluetoothOppNotification( 1966): mUpdateCompleteNotification = true
I/ActivityManager(  841): Process com.android.calendar (pid 5385) has died
,I/bt_userial_vendor( 1966): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1966): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1966): device fd = 72 open
,D/bt_hwcfg( 1966): hw_config_cback opcode:0x0c03
,D/bt_hwcfg( 1966): hw_config_cback state=1
D/bt_hwcfg( 1966): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1966): hw_config_cback state=4
D/bt_hwcfg( 1966): Chipset Name: BCM4334B0
,D/bt_hwcfg( 1966): Chipset BCM4334B0
D/bt_hwcfg( 1966): Target name = [BCM4334B0]
I/bt_hwcfg( 1966): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1966): hw_config_cback state=2
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1966): hw_config_cback state=3
I/bt_hwcfg( 1966): bt vendor lib: set UART baud 4000000
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1966): hw_config_cback state=5
,I/art     (  841): Explicit concurrent mark sweep GC freed 18703(869KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.983ms total 177.286ms
,V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/OppService( 1966): pendingUpdate is :  false
E/OppService( 1966): UpdateThread is Completed
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@2792d942 on behalf of 
V/BluetoothOppNotification( 1966): outbound: succ-0  fail-0
I/NotificationManager( 1966): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
,V/BluetoothOppNotification( 1966): outbound notification was removed.
V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@22c4cd53 on behalf of 
V/BluetoothOppNotification( 1966): inbound: succ-0  fail-0
I/NotificationManager( 1966): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1966): inbound notification was removed.
V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@258ce690 on behalf of 
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
E/wpa_supplicant( 5628): USIM:  scard_init function
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/wpa_supplicant( 5628): rfkill: Cannot open RFKILL control device
I/Netd    (  268): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
I/Netd    (  268): M: Get netlink event, ifname: p2p0 action: 9
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
V/BluetoothPbapReceiver( 1966): PbapReceiver onReceive 
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/Netd    (  268): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
V/BluetoothPbapReceiver( 1966): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1966): ***********state = 11
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/Tethering(  841): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/DSQN    (  841): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/wpa_supplicant( 5628): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/wpa_supplicant( 5628): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5635): remove : truetruefalse
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WifiStateMachine(  841): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5635): remove2
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
V/WiFiOffLoadSharedPrefsUtils( 5635): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5635): save remove
D/WiFiOffLoadBroadcast( 5635): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WiFiOffLoadBroadcast( 5635): S: false, R: true
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  841): setPowerSaveActivated(false)
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/ActivityManager(  841): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5693 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/WifiServerServiceExt(  841): WIFI_STATE_CHANGED_ACTION [3]
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/WifiServerServiceExt(  841): batteryPsActivateMsgHandler : state:0 event:3
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
E/WifiServerServiceExt(  841): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
E/WifiConfigStore(  841): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WifiStateMachine(  841): enableVerboseLogging : level 2
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.219 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WifiStateMachine(  841): Setting OUI to DA-A1-19
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WifiNative-HAL(  841): Setting external_sim to 1
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/WifiNative-HAL(  841): startHal
E/wifi    (  841): getStaticLongField sWifiHalHandle 0x9b2f48ec
I/WifiHAL (  841): Initializing wifi
I/WifiHAL (  841): Creating socket
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/BluetoothPermissionRequest( 5635): onReceive
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WfdsService( 1798): Supplicant Connection state is changed : true
D/WfdsService( 1798): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/LGBluetoothFeatureConfig( 5635):  get() - isFeatureLoaded : false
D/WfdsService( 1798): Set the WFDS Monitor: true
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
W/Settings( 5128): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WfdsMonitor( 1798): WfdsMonitorThread create
D/WfdsMonitor( 1798): WFDS Monitor is created and started
D/WfdsService( 1798): WiFi: Supplicant connection re-established
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
,I/WifiHAL (  841): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  841): Did set static halHandle = 0x9dacbf00
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/wifi    (  841): halHandle = 0x9dacbf00, mVM = 0xb487c280, mCls = 0x501dce
E/wifi    (  841): getStaticLongField sWifiHalHandle 0x9b2f489c
D/wifi    (  841): array field set
I/WifiNative-HAL(  841): interface[0] = wlan0
I/WifiNative-HAL(  841): interface[1] = p2p0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
E/CtrlSupplicant( 1798): Access OK "@android:wpa_wlan0"
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
E/CtrlSupplicant( 1798): Succeed to open control connection
E/CtrlSupplicant( 1798): Succeed to open monitor connection
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WfdsMonitor( 1798): Supplicant connection established
D/WfdsService( 1798): Connected to the supplicant for wfds
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/wifi    (  841): setting scan oui 0x9a19a028
D/WifiHAL (  841): Sending mac address OUI
E/WifiHAL (  841): failed to set scanning mac OUI; result = -95
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1966): hw_config_cback state=6
D/WifiStateMachine(  841): Setting OUI to DA-A1-19
I/WifiNative-HAL(  841): startHal
D/wifi    (  841): setting scan oui 0x9a19a028
D/WifiHAL (  841): Sending mac address OUI
E/WifiHAL (  841): failed to set scanning mac OUI; result = -95
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
I/WifiNative-HAL(  841): Waiting for HAL events mWifiHalHandle=-1649623296
D/wifi    (  841): waitForHalEvents called, vm = 0xb487c280, obj = 0x501dce, env = 0x9a095580
E/wifi    (  841): getStaticLongField sWifiHalHandle 0x97a29b2c
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/WifiHS20(  841): hidePasspointNotification off =false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1966): hw_config_cback state=6
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1966): hw_config_cback state=6
D/charger_monitor(  472): init target 500000
D/LGWifiP2pService(  841): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  841): SCAN_AVAILABLE : 3
D/RttService(  841): SCAN_AVAILABLE : 3
D/WifiScanningService(  841): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  841): startHal
D/RttService(  841): DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  841): getting scan capabilities on interface[0] = 0x9a19a028
D/WifiHAL (  841): Creating message to get scan capablities; iface = 24
D/wifi    (  841): failed to get capabilities : -95
E/WifiScanningService(  841): could not get scan capabilities
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  268): Setting iface cfg
D/CommandListener(  268): Trying to bring up p2p0
,D/WifiMonitor(  841): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  841): P2pEnablingState
D/LGWifiP2pService(  841): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2p socket connection successful
D/LGWifiP2pService(  841): P2pEnabledState
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.309 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/BluetoothManagerService(  841): Message: 20
D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f956a27:true
D/LGWifiP2pService(  841): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  841): before postfix = G3s-1
I/WifiServerServiceExt(  841): set CMD_ADD_DEFAULT_PROFILE
I/WifiServerServiceExt(  841): setWifiDualbandAPConnection band : 1
D/WifiServerServiceExt(  841): postfix byte check : 5
D/LGWifiP2pService(  841): after postfix = G3s-1
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiNative-HAL(  841): p2pGetDeviceAddress
D/WifiNative-HAL(  841): p2pGetDeviceAddress returning a2:39:f7:70:12:80
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
E/wpa_supplicant( 5628): nWIFIDualbandAPConnection: 1
I/WifiServerServiceExt(  841): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5628): disconnect_rssi_lvl: -100
I/WifiServerServiceExt(  841): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5628): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
D/LGWifiP2pService(  841): DeviceAddress: a2:39:f7:70:12:80
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/WfdsService( 1798): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/WifiServerServiceExt(  841): set CMD_UPDATE_DEFAULT_PROFILE
V/BluetoothSapReceiver( 1966): [BTUI] checkServiceStart
,D/WfdsService( 1798): Update P2p Interface State: 3
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/LGBluetoothStateChangeReceiver( 1966): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/charger_monitor(  472): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LGWifiP2pService(  841): sending p2p persistent groups changed broadcast
,I/bt_hwcfg( 1966): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1966): Settlement delay -- 100 ms
I/bt_hwcfg( 1966): Setting fw settlement delay to 100 
I/wpa_supplicant( 5628): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/wpa_supplicant( 5628): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/ActivityManager(  841): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5717 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/LGWifiP2pService(  841): sending p2p connection changed broadcast
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService(  841): InactiveState
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): DefaultState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  841): No p2p device connected
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,D/WfdsService( 1798): WifiP2pState is changed : true
D/WfdsService( 1798): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1798): Receive the WFDS_ENABLE Method
D/WfdsService( 1798): Set the WFDS Monitor: true
D/WfdsService( 1798): Connected to the supplicant for wfds
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WfdsJNI ( 1798): doCommand: WFDS_SET TRUE
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
D/WfdsService( 1798): isConnected: false
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1798): GroupInfoAvailable: mGroupInfo is null
I/wpa_supplicant( 5628): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1798): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5628): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
,D/WfdsJNI ( 1798): doCommand: WFDS_CLEAR_PD_INFO,
I/wpa_supplicant( 5628): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1798): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1798): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1798): selectPreferredScanChannel [6]
D/WfdsService( 1798): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
W/WfdsService( 1798): DefaultState - msg [9441285] is not handled
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.439 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5628): wlan0: Associated with c0:ff:d4:d3:aa:48
D/LocSvc_java(  841): onReceive
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.456 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.459 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateSCANNING
D/GONS    ( 1745): GONS isTestMode: false Country: 
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.488 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 5628): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5628): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.494 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1966): hw_config_cback state=2
I/WifiServiceExtension(  841): setVHTCapabilityType  : false
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1966): hw_config_cback state=7
I/bt_hwcfg( 1966): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1966): Setting local bd addr to F8:95:C7:87:85:54
D/PCSuite ( 5693): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/WifiServerServiceExt(  841): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  841): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  841): setSecurityType  : 2
D/UsbSettingsReceiver( 5635): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5635): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5635): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5635): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5635): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/bt_hwcfg( 1966): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1966): hw_config_cback state=8
I/bt_hwcfg( 1966): vendor lib fwcfg completed
I/bt-btif ( 1966): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1966): btu_task received preload complete event
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.547 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.555 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/        ( 1966): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_AVCT,2
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/        ( 1966): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1966): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1966): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1966): BTE_InitTraceLevels -- TRC_PROTOCOL,0
W/ResourcesManager( 5717): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/ConnectivityService(  841): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/UsbSettingsControl( 5635): [AUTORUN] getUsbConnected() : connected=true
D/WifiExtManager(  841): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@289524ca
,D/UsbSettingsReceiver( 5635): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5635): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5635): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5635): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5635): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/WifiExtManager(  841): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@36f2663b
D/UsbSettingsControl( 5635): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService(  841): Got NetworkAgent Messenger
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  841): NetworkAgent connected
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WiFiOffLoadUpdatePriority( 5635): remove : truetruetrue
,E/WifiConfigStore(  841): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 5717): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  268): Setting iface cfg
D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/DhcpStateMachine(  841): StoppedState
E/WifiStateMachine(  841): Start Dhcp Watchdog 1
D/DhcpStateMachine(  841): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  841): WaitBeforeStartState
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateGROUP_HANDSHAKE
V/BluetoothOppNotification( 1966): new notify threadi!
V/BluetoothOppNotification( 1966): send delay message
,V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@e9e3b89 on behalf of 
V/BluetoothOppNotification( 1966): mUpdateCompleteNotification = true
I/QCNEJ   ( 1833): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:15.646 DNS addrs= 0.0.0.0, 0.0.0.0, 
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@479478e on behalf of 
V/BluetoothOppNotification( 1966): outbound: succ-0  fail-0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/NotificationManager( 1966): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1966): outbound notification was removed.
V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@144ebaf on behalf of 
,V/BluetoothOppNotification( 1966): inbound: succ-0  fail-0
I/NotificationManager( 1966): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1966): inbound notification was removed.
V/BluetoothOppProvider( 1966): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/BluetoothOppProvider( 1966): created cursor android.database.sqlite.SQLiteCursor@281dbbc on behalf of 
E/bt-btif ( 1966): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 1966): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1966): warning : media task started media_task_refcnt 1 
D/BT_PROF_AUDIO( 1966): created moving average (N=100)
D/BT_PROF_AUDIO( 1966): reset rate average
W/bt-btif ( 1966): overflow 0, enter 0, exit 0
E/bt-btif ( 1966): Calling BTA_HhEnable
E/bt-btif ( 1966): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1966): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-smp  ( 1966): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1966): Plain text(LSB ~ MSB) = 64 74 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1966): Encrypted text(LSB ~ MSB) = eb 26 a9 54 d3 bc d0 d4 22 4e a8 61 55 aa 75 ea 
W/bt-btm  ( 1966): Stopping oneshot timer
D/BluetoothAdapterProperties( 1966): Address is:F8:95:C7:87:85:54
D/BluetoothManagerService(  841): Bluetooth Adapter name changed to G3s-1
D/BluetoothAdapterProperties( 1966): Name is: G3s-1
D/BluetoothManagerService(  841): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1966): Scan Mode:20
D/BluetoothAdapterProperties( 1966): Discoverable Timeout:120
E/bt-btif ( 1966): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1966): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1966): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1966): BTA_JvEnable
E/bt-btif ( 1966): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1966): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1966): init_hci_slots(L136): in
D/IOP_DB_BT( 1966): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1966): db_open: db_open : handle 2691434460l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1966): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 1966): db_query: result 1
I/        ( 1966): iop_db_open: iop_db_open status 0
E/bt-btif ( 1966): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1966): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1966): bta_pan_co_init
D/bte_conf( 1966): Device ID record 1 : primary
D/bte_conf( 1966):   vendorId            = 00c4
D/bte_conf( 1966):   vendorIdSource      = 0001
D/bte_conf( 1966):   product             = 13a1
D/bte_conf( 1966):   version             = 1000
D/bte_conf( 1966):   clientExecutableURL = 
D/bte_conf( 1966):   serviceDescription  = 
D/bte_conf( 1966):   documentationURL    = 
D/bte_conf( 1966): bte_load_did_conf no section named DID2.
I/bt-btif ( 1966): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 1966): btif_hf_upstreams_evt: wrong handle = 12336 
I/bt-btif ( 1966): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1966): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterState( 1966): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1966): ScanMode =  20
D/BluetoothAdapterProperties( 1966): State =  11
D/BluetoothAdapterProperties( 1966): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1966): Setting state to 12
I/BluetoothAdapterState( 1966): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(522550116)( 1966): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  841): Message: 60
D/BluetoothManagerService(  841): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 1966): Entering On State
D/BluetoothManagerService(  841): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 1966): Entering On State from state = 11
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothAdapterService(522550116)( 1966): isQuetModeEnabled() - Enabled = false
D/BluetoothA2dp( 1966): onBluetoothStateChange: up=true
D/BluetoothAdapterService(522550116)( 1966): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1966): [BTUI] autoConnect() : not allowed
D/BluetoothA2dp(  841): onBluetoothStateChange: up=true
D/BluetoothHeadset(  841): onBluetoothStateChange: up=true
D/OppService( 1966): onOpcStateChange()
I/bt-btif ( 1966): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1966): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 1966): Recieved MESSAGE_OPC_ENABLE
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
D/OppService( 1966): onOpsStateChange() :0
I/bt-btif ( 1966): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
D/BluetoothFTPServiceJni( 1966): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1966): onFtpServerEnabled: /storage
D/LGBluetoothFeatureConfig( 1966): isPrivacyLogsEnabled : true
D/BluetoothPanServiceJni( 1966): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 1966): HAL bt_hal_cbacks->adapter_properties_cb
E/BluetoothManagerService(  841): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  841): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothServiceAdapter( 1966): [BTUI] OnState
D/OppService( 1966): Recieved MESSAGE_OPS_ENABLE
,D/LGBluetoothServiceAdapter( 1966): [BTUI]         global_name: G3s-1
D/BluetoothAdapterProperties( 1966): Scan Mode:21
D/LGBluetoothServiceAdapter( 1966): [BTUI]         local_name: G3s-1
I/bt-btif ( 1966): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1966): Discoverable Timeout:120
D/LGBluetoothAPIService( 1798): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothAdapterService(522550116)( 1966): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(522550116)( 1966): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1966): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService(  841): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothManagerService(  841): Message: 40
D/LGBluetoothAPIService( 1798): Message: 1
D/BluetoothManagerService(  841): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
I/BluetoothMapService( 1966): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1966): STATE_ON
D/LGBluetoothAPIService( 1798): MESSAGE_BOOT_COMPLETED
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1370): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/bt_h4   ( 1966): vendor lib postload completed
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22d73e46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22d73e46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  841): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  841): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  841): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  841): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  841): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine(  841): DHCP Start wake lock is acquired.
I/LGBluetoothAPIService( 1798): [BTUI] LGBluetoothAPIService Binding Success
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  841): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  841): setSupplicantStateCOMPLETED
,D/BluetoothAdapterService( 1966): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f257b64
V/BluetoothPbapService( 1966): Pbap Service onCreate
V/BluetoothPbapService( 1966): Starting PBAP service
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/LGBluetoothPbapAdapter( 1966): [BTUI] getInstance : create
V/BluetoothMapService( 1966): Handler(): got msg=1
D/BluetoothMapMasInstance( 1966): Map Service startRfcommSocketListener
V/BluetoothPbapService( 1966): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1966): state: 12
D/LGBluetoothAPIServer( 1966): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1966): [BTUI] onBind()
D/BluetoothMapMasInstance( 1966): MAS initSocket()
D/BluetoothMapMasInstance( 1966):   masId = 00
D/BluetoothMapMasInstance( 1966):   msgTypes = 0e
D/BluetoothMapMasInstance( 1966):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1966):   SDP string = 000eSMS/MMS
V/BluetoothPbapService( 1966): Handler(): got msg=1
D/LGBluetoothAPIService( 1798): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothPbapService( 1966): Pbap Service startRfcommSocketListener
D/LGBluetoothAPIService( 1798): Message: 100
D/LGBluetoothAPIService( 1798): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 1966): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1966): BTA_JvCreateRecordByUser
V/BluetoothPbapService( 1966): Pbap Service initSocket
D/WiFiOffLoadUpdatePriority( 5635): remove1
V/WiFiOffLoadSharedPrefsUtils( 5635): save remove
I/bt-btif ( 1966): BTA_JvRfcommStartServer
D/BluetoothManagerService(  841): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothServiceAdapter( 1966): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothMapMasInstance( 1966): Succeed to create listening socket 
,D/BluetoothMapMasInstance( 1966): Accepting socket connection...
W/BluetoothAdapter( 1966): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1966): BTA_JvCreateRecordByUser
D/LGBluetoothServiceAdapter( 1966): [BTUI] createSocketChannel FD=85 mFd=83
I/bt-btif ( 1966): BTA_JvRfcommStartServer
V/BluetoothPbapService( 1966): Succeed to create listening socket 
V/BluetoothPbapService( 1966): Accepting socket connection...
D/WiFiOffLoadBroadcast( 5635): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5635): S: false, R: false
D/WiFiOffLoadUpdatePriority( 5635): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5635): connected SSID: null
,D/WiFiOffLoadUpdatePriority( 5635): private wpa: "NG700" 300
D/WifiServiceImplEx(  841): addOrUpdateNetwork pid=5635, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  841):  uid = 1000 SSID "NG700" nid=0
E/WifiConfigStore(  841):  key="NG700"WPA_PSK netId=0 uid=0/1000
E/WifiConfigStore(  841): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5635):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5635): configuration updated: 0
I/WifiServerServiceExt(  841): set CMD_UPDATE_DEFAULT_PROFILE
,D/WiFiOffLoadUpdatePriority( 5635): configuration saved: true
,D/PCSuite ( 5693): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 5635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/ActivityManager(  841): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5752 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/BluetoothPbapReceiver( 1966): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1966): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1966): ***********state = 12
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
,D/LocalBluetoothProfileManager( 5635): Adding local A2DP profile
D/BluetoothManagerService(  841): Message: 30
D/LocalBluetoothProfileManager( 5635): Adding local HEADSET profile
D/BluetoothManagerService(  841): Message: 30
D/BluetoothManagerService(  841): Message: 30
,D/BluetoothManagerService(  841): Message: 30
D/LocalBluetoothProfileManager( 5635): Adding local MAP profile
D/BluetoothMap( 5635): Create BluetoothMap proxy object
D/BluetoothManagerService(  841): Message: 30
D/BluetoothManagerService(  841): Message: 30
,D/DhcpStateMachine(  841): DHCPV4 request on wlan0
D/LocalBluetoothProfileManager( 5635): LocalBluetoothProfileManager construction complete
V/LgDhcpStateMachineHelper(  841): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  841): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
V/BluetoothPbapService( 1966): Pbap Service onBind
D/LGBluetoothUserBindClient( 5635): [BTUI] initUserBindClient
W/ContextImpl( 5635): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
I/dhcpcd  ( 5769): version 5.5.6 starting
,E/dhcpcd  ( 5769): get_duid: Read-only file system
D/DockEventReceiver( 5635): finishStartingService: stopping service
D/BluetoothA2dp( 5635): Proxy object connected
D/A2dpProfile( 5635): Bluetooth service connected
,D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothHeadset( 5635): Proxy object connected
D/HeadsetProfile( 5635): Bluetooth service connected
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothInputDevice( 5635): Proxy object connected
D/HidProfile( 5635): Bluetooth service connected
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothPan( 5635): BluetoothPAN Proxy object connected
D/PanProfile( 5635): Bluetooth service connected
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
,D/BluetoothMap( 5635): Proxy object connected
D/MapProfile( 5635): Bluetooth service connected
D/BluetoothMap( 5635): getConnectedDevices()
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
V/BluetoothMapService( 1966): getConnectedDevices()
D/BluetoothPbap( 5635): Proxy object connected
D/PbapServerProfile( 5635): Bluetooth service connected
D/LGBluetoothUserBindClient( 5635): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5635): onReceive
D/LGBluetoothFeatureConfig( 5635): isPrivacyLogsEnabled : true
,D/LGBluetoothUtils( 5635): [BTUI] FileNotFound: readProperty
V/BluetoothOppReceiver( 1966): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
V/BluetoothOppManager( 1966): restoreApplicationData! falsefalsenullnull
,I/Netd    (  268): M: Get netlink event, ifname: p2p0 action: 6
D/LGDMClient( 5752): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5752): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/BluetoothSapReceiver( 1966): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 1966): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
W/ContextImpl( 5752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/dhcpcd  ( 5769): wlan0: rebinding lease of 192.168.1.134
,D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
D/LGDMClient( 5752): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5752): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 5752): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/PCSuite ( 5693): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5693): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5693): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  841): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5787 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  841): Killing 5053:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.574ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.729ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.481ms
,W/libprocessgroup(  841): failed to open /acct/uid_10089/pid_5053/cgroup.procs: No such file or directory
,W/ResourcesManager( 5787): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  841): Message: 20
D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@db201f5:true
,D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
I/ActivityManager(  841): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5810 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  841): Process com.google.android.talk (pid 5128) has died
,V/[BNRBootReceiver]( 5810): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5810): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,V/[BNRBootReceiver]( 5810): Boot Receiver Return,
,V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5635): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
I/rmt_storage(  266): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  266): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  266): wakelock acquired: 1, error no: 42
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  266): 
I/rmt_storage(  266): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5829 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5787): Create singleton instance
,D/UEI.SmartControl( 5829): Quickset Services start...
,I/AudioManager( 5787): getMode name:com.lge.qremote
I/UEI.SmartControl( 5829): Manufacture = LGE
D/UEI.SmartControl( 5829): File observer start...
E/UEI.SmartControl( 5829): IR Port is disabled: false
D/UEI.SmartControl( 5829): Starting file observer...
D/UEI.SmartControl( 5829): Extracting JNI libs...
D/UEI.SmartControl( 5829): --- this system supports 32-bit or 64-bit only
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5829): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5829): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5829): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5829): --- Selecting new region: 2
,I/UEI.SmartControl( 5829): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5829): Platform has CIR...
D/UEI.SmartControl( 5829): NO CIR support, need to check package...
I/UEI.SmartControl( 5829): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5829): QS Service created
E/UEI.SmartControl( 5829): QS start get config
,D/UEI.SmartControl( 5829): Loading JNI Libs...
D/UEI.SmartControl( 5829):  configuring local db...
,I/NotificationManager( 1936): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/AudioFlinger(  272): thread 0xb5651000 type 0 TID 1292 going to sleep
,V/AudioFlinger(  272): thread 0xb56eb000 type 0 TID 1293 going to sleep
V/AudioFlinger(  272): thread 0xb5735000 type 0 TID 1295 going to sleep
I/dhcpcd  ( 5769): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/dhcpcd  ( 5769): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  268): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5829):  ---- Has DB8: true
,D/UEI.SmartControl( 5829): QS start statue = true Error code = 0
D/UEI.SmartControl( 5829): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5829): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5829): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5829): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5829): IrrcClient ++ 
,D/irrcClient( 5829): getIrrcService ++ 
D/irrcClient( 5829): getIrrcService -- 
D/irrcClient( 5829): IrrcClient -- 
W/irrc_jni( 5829): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5829): Services init done
,I/UEI.SmartControl( 5829): Device manager: loading config....
D/UEI.SmartControl( 5829): QS Service init finished
D/UEI.SmartControl( 5829): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5829): QS Service version code: 1073
D/UEI.SmartControl( 5829): Service requested: Control
D/UEI.SmartControl( 5829): Config is loaded...
D/UEI.SmartControl( 5829):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5829): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5829): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5829): Internal service binding...
,D/UEI.SmartControl( 5829): -----IControl: 11
D/UEI.SmartControl( 5829): Caller: com.lge.qremote
D/UEI.SmartControl( 5829): ------------ IControl registerCallback...
I/UEI.SmartControl( 5829): Registering callback...
D/UEI.SmartControl( 5829): -----IControl: 19
D/UEI.SmartControl( 5829): Caller: com.lge.qremote
I/UEI.SmartControl( 5829): Registering Services Ready callback...
,I/UEI.SmartControl( 5829): Notify client services are ready...
D/UEI.SmartControl( 5829): -----IControl: 8
D/UEI.SmartControl( 5829): Caller: com.lge.qremote
I/AudioManager( 5787): getMode name:com.lge.qremote
I/ActivityManager(  841): Killing 5474:com.google.android.gms:car/u0a6 (adj 15): empty #11
,I/ActivityManager(  841): Killing 5358:com.android.providers.calendar/u0a14 (adj 15): empty #12
,W/libprocessgroup(  841): failed to open /acct/uid_10006/pid_5474/cgroup.procs: No such file or directory
,W/libprocessgroup(  841): failed to open /acct/uid_10014/pid_5358/cgroup.procs: No such file or directory
I/AudioManager( 5787): getMode name:com.lge.qremote
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  841): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  841): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  841): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  841): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  841): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  841): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  841): bShouldSendDhcpAction Result: true
I/AudioManager( 5787): getMode name:com.lge.qremote
D/DhcpStateMachine(  841): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  841): RunningState
D/LGWifiP2pService(  841): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  841): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  841): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine(  841): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  841): ignoring duplicate network state non-change
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  841): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
D/ConnectivityService(  841): Adding iface wlan0 to network 100
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  841): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  841): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:17.604 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  841): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:17.611 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:17.614 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:17.616 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
E/ConnectivityService(  841): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  841): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  841): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  841): Setting Dns servers for network 100 to [/192.168.1.1]
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  841): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  841): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  841): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  841): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  841):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  841): currentScore = 0, newScore = 20
D/ConnectivityService(  841):    accepting network in place of null
D/ConnectivityService(  841): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  841): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1745): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
,E/ConnectivityService(  841): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  841): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  841): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  841): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  841): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
W/QCNEJ   ( 1833): |CORE| No family connected
I/QCNEJ   ( 1833): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/Tethering(  841): MasterInitialState.processMessage what=3
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=,com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  841): validation of new default Network = false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  841): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  841): enableDataServiceNotify 
D/DSQN    (  841): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] Start DNSResolver start to wait
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,I/QCNEJ   ( 1833): |CORE| sendDefaultNwMsg: default = 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] wait 500ms before dns check
D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
,D/ConnectivityService(  841): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/DSQN    ( 5887): DSQN samuel.seo ver 141203
E/DSQN    ( 5887): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5887): created command queue thread
I/DSQN    ( 5887): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5887): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
I/PCSuite ( 5693): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out(  841): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PCSuite ( 5693): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5635): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5635): MCCMNC not supported: null
I/PCSuite ( 5693): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5693): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/NetworkPolicy(  841): [LG_RESTRICTED] checkMobilePolicy_type()
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] DNSResolver start dns
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out(  841): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5887): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5887): restart monitoring
,D/LGDataListener(  268): argv[0]=dsqncommand
D/LGDataListener(  268): argv[1]=wlan0
D/LGDataListener(  268): argv[2]=1
D/LGDataListener(  268): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5887): dsqn report finish
D/DSQN    (  841): DSQM DsqnNotification wlan0  1
D/DSQN    (  841): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 00:39:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450226358272], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450226358255]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  841): Validated
D/ConnectivityService(  841): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  841): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  841):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  841):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  841): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  841): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  841): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  841): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
I/WifiServerServiceExt(  841): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityService(  841): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1745): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  841): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  841):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1833): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-16 01:39:18.661 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/jxcore-log( 5533): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5533): 
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/WifiInternetCheck(  841): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  841): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  841): onReceive
D/LocSvc_java(  841): got connectivity action
D/AlarmManagerService(  841): Setting time of day to sec=1450226360
,W/AlarmManagerService(  841): Unable to set rtc to 1450226360: Invalid argument
D/LocSvc_java(  841): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
,D/LocSvc_java(  841): Sending msg: 4 arg1:1 arg2:1
,D/LocSvc_java(  841): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  841): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  841): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5916 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocSvc_java(  841): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  841): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  841): Sending msg: 5 arg1:0 arg2:1
,D/LocSvc_java(  841): NTP server returned: 1450226357911 (Wed Dec 16 01:39:17 GMT+01:00 2015) reference: 104692 certainty: 13 system time offset: -2993
D/LocSvc_java(  841): Sending msg: 10 arg1:0 arg2:1
I/[SystemUI]Clock( 1370): onReceive = android.intent.action.TIME_SET
,I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/WeatherService( 2751): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 1:39:20
D/WeatherService( 2751): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2751): 2 : This is isUpdating : false
D/WeatherService( 2751): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2751): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2751): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2751): 2 : Fixed theme : optimus
D/WeatherReflect( 2751): 2 : Map key string is -2
I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5936 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/NetworkChangeNotifierAutoDetect( 1936): Network connectivity changed, type is: 2
,W/ActivityManager(  841): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
D/lim     ( 2751): 2 : time = 01:39
,I/WeatherReflect( 2751): Model Name : LG-D722
,I/[LGHome]LGDateChangeReceiver( 1872): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=16 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,D/WeatherTheme( 2751): 2 : exactly same view!
D/WeatherTheme( 2751): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2751): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 1:39:21
I/[LGHome]LGCalendarIcon( 1872): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 16
,I/[LGHome]LGCalendarIcon( 1872): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 16
I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  841): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5956 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/ResourcesManager( 5936): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5936): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5936): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 5956): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5956): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5956): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/GoogleURLConnFactory( 1728): Using platform SSLCertificateSocketFactory
D/GpsLocationProvider(  841): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  841): Process com.android.vending (pid 4971) has died
,I/ActivityManager(  841): Process com.google.process.gapps (pid 1985) has died
,E/GpsLocationProvider(  841): No APN found to select.
I/AppConfig( 5956): Total System Memory = 906309632
,I/GalleryUtils( 5956): Application Heap = 96 MB
I/AppConfig( 5956): App Tier : NOT_DEF
,D/SystemHelper( 5956): region [EU], country [EU], operator [OPEN], sub-operator []
D/LgeGpsConstants(  841): Can't find 'ext_gps.conf'!!
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  841): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5980 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out(  841): propertyValue:false
I/LGEmail ( 5936): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/NotificationManager(  841): android: cancelAsUser(-1597574061) by android
,D/LGEmail ( 5936): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/LgeGpsLocationProvider(  841): NTP server: europe.pool.ntp.org
,D/LgeGpsLocationProvider(  841): NTP server returned: 1450226361562 (Wed Dec 16 01:39:21 GMT+01:00 2015) reference: 108339 certainty: 23 system time offset: 21
I/GservicesProvider( 5980): Gservices pushing to system: true; secure/global: true
,I/MusicStore( 5916): Database version: 120
I/NotificationManager(  841): android: cancelAsUser(-1816247584) by android
,I/GoogleHttpClient( 5980): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5980): GMS http client unavailable, use old client
,I/ActivityManager(  841): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6018 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{2cc1c6d type 0 when 1450226361762 com.android.vending} when 1450226361762
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/art     (  841): Explicit concurrent mark sweep GC freed 74561(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.454ms total 195.183ms
,D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  841): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6039 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out(  841): propertyValue:false
I/GoogleHttpClient( 5980): GMS http client unavailable, use old client
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  841): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  841): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  268): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out(  841): propertyValue:false
,V/WifiInternetCheck(  841): isHttpConnectionAvailable - We got a valid response : 204
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5916): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/ALBootInit( 6039): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6039): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6039): [setNextAlert] start
,D/Alarms  ( 6039): [setNextAlert] (1)
,D/Alarms  ( 6039):  minTime  = 0
D/Alarms  ( 6039):  -- OK multi -- 0
E/jeny.kim( 6039): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6039): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/ActivityManager(  841): Process com.lge.lgdmsclient (pid 5752) has died
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityThread( 5276): Failed to find provider info for com.android.contacts.metadata
I/CommonUtil( 6039): BUILD Operator: OPEN
,D/Alarms  ( 6039): broadcastToWidgetProvider : false
D/SyncManager(  841): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 38396, reason: UserStart, SyncResult: databaseError: true stats []
D/Alarms  ( 6039): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/SyncManager(  841): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 141223, reason: UserStart
I/NotificationManager(  841): android: cancelAsUser(716319171) by android
V/SettingsProvider(  841): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6039): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6039): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1f864f6
V/DigitalAppWidgetProvider( 6039): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1f864f6
,D/QuickCoverProvider( 6039): onReceiver
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5916): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5916): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  841): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6079 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Auth.Api.Credentials( 5276): [CredentialSyncAdapter] Unknown sync event.
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
I/NotificationManager(  841): android: cancelAsUser(-591465577) by android
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
,W/ResourcesManager( 5916): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5916): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 6018): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/ResourcesManager( 6079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5829): Internal timer expired: 1
,V/JNIHelp ( 5916): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  841): Process com.lge.bnr (pid 5810) has died
,D/CalendarApplication( 6079): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6079): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6079): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@143b7515, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1e3b702a, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@25f7be1b, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@a4a5bb8, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@31eb4d91, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1f864f6, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@11ca20f7, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1f257b64, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1e631cd, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3bdda82, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@32f5d593, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1c70e9d0, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2a311dc9, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@731cce, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@191e37ef, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@18c2d2fc, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1224cd85, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2a2837da, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@c0640b, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1be822e8, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3e9bd01, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@11e1f7a6, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@270f35e7, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1b908594, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@29b4283d, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@225e832, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3f8f4983, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@16ba6700, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@22c00b39, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3646557e, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2772fadf, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3bdef32c, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2c0d21f5, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3a6e4b8a, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@32b665fb, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@5de1618, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@18dae871, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@6d9656, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2efb66d7, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3baa7bc4, lg_preferences_alerts_vibratetype=com.android.calendar.adap,tation.PreferenceKey$KeyData@16e49aad, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3544c1e2, l
,D/GeneralPreferenceUtils( 6079): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6079): [init]
,I/Config  ( 6079): LGCalendar ver.4.40.17
I/Config  ( 6079): start check model
I/Config  ( 6079): start check native_ca
I/Config  ( 6079): Config Operator=OPEN, Country=EU
D/Config  ( 6079): [setDefaultValuesToPref]
D/Config  ( 6079): [parseProfiles]
D/ProfilesParser( 6079): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6079): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6079): [updateProfiletoCountryInfo]
D/GeneralPreference( 6079): [checkAndMigrateOldPreference]
E/ConnectivityChangeReceiver( 5276): Ignoring connectivity change
,E/AgendaWidgetManager( 6079): [updateWidgets] 
I/InitNotificationRingtoneService( 6079): Start InitializeAlertRingtoneService.onHandleIntent
,I/NotificationManager(  841): android: cancelAsUser(-1816247584) by android
I/AlertUtils( 6079): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/ConnectivityService(  841): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/AlertUtils( 6079): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,D/ConnectivityService(  841): dumpNetworkRequest
D/ConnectivityService(  841):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  841):     Requests:
D/ConnectivityService(  841):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  841):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  841):     Lingered:
D/ConnectivityService(  841): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  841): apparently satisfied.  currentScore=60
D/ConnectivityService(  841): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5276): CM callback handler got msg 524290
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,W/ActivityThread( 5916): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
W/System  ( 5916): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@56ad9fd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/ProviderInstaller( 5916): Installed default security provider GmsCore_OpenSSL
D/Finsky  ( 6018): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/AndroidMusic( 5916): GMSCore installation verified
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6079): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6079): set default noti to content://media/internal/audio/media/38
,W/Settings( 6018): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/InitNotificationRingtoneService( 6079): End InitializeAlertRingtoneService.onHandleIntent
W/Settings( 6018): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6018): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ConfigStore( 5916): Config Database version: 1
D/Ads     ( 6018): Skipping gmscore version check
,D/Finsky  ( 6018): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6018): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@6d9656 on behalf of 6018
I/NotificationManager(  841): android: cancelAsUser(-591465577) by android
,D/Finsky  ( 6018): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6018): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6134 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/HolidayIntentService( 6079): onHandleIntent
,D/HolidayDataLoader( 6079): readJsonAsset : holiday.json
D/MonthWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6079): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6079): [onUpdateAndInitCalendarTime]
,D/WeatherAncestor( 2751): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 1:39:23
D/UpdateThreadPoolManager( 2751): 2 : This is isUpdating : false
D/Weather_cast( 2751): 2 : set auto-update time : 12/16 4:39
,D/WeatherAncestor( 2751): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 1:39:23
D/WeatherService( 2751): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,I/art     ( 5980): Explicit concurrent mark sweep GC freed 8156(411KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.124ms total 70.941ms
,E/HolidayIntentService( 6079): onHandleIntent:holiday data empty
I/ActivityManager(  841): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6152 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 23.247ms
,W/ResourcesManager( 6134): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 27.540ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 22.987ms
,I/ActivityManager(  841): Process com.lge.settings.easy (pid 5717) has died
,W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2751): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2751): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2751): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/NotificationManager(  841): android: cancelAsUser(-1548111331) by android
I/MediaRouter( 5916): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/TimeService( 6152): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226363330
D/        ( 6152): TimeServiceNative: User Time to be set is 1450226363331
D/QC-time-services( 6152): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6152): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6152): Lib:time_genoff_operation: pargs->ts_val = 1450226363331
D/QC-time-services( 6152): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  317): Daemon: Connection accepted:time_genoff
D/QC-time-services(  317): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450226363331
D/QC-time-services(  317): Daemon:genoff_opr: Base = 2, val = 1450226363331, operation = 0
D/QC-time-services(  317): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/28/70 4:41:8
V/MusicLeanback( 5916): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/QC-time-services(  317): Daemon:Value read from RTC seconds = 10125668000
D/QC-time-services(  317): Daemon:new time 1450226363331 
D/QC-time-services(  317): Daemon: delta 1440100695331 genoff 1440100695331 
D/QC-time-services(  317): Daemon:genoff_persistent_update: Writing genoff = 1440100695331 to memory
D/QC-time-services(  317): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  317): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  317): Updating the TOD offset
D/QC-time-services(  317): Daemon:genoff_persistent_update: Writing genoff = 1440100695331 to memory
,D/QC-time-services(  317): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  317): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  317): Daemon:Update to modem bit set
D/QC-time-services(  317): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 6152): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  317): Daemon: Base = 2, Value being sent to MODEM = 1124135895331
I/NetworkMonitor( 5916): type=WIFI subType= reason=null isConnected=true
E/QC-time-services(  317): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  317): Daemon: Time-services: Waiting to acceptconnection
W/DriveInitializer( 5276): Awaiting to be initialized
W/DriveInitializer( 5276): Background init thread started
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5276): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,I/NotificationManager(  841): android: cancelAsUser(-1597574061) by android
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/DriveInitializer( 5276): Background init thread ended
,D/Finsky  ( 6018): [715] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6018): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/art     (  841): Explicit concurrent mark sweep GC freed 27423(1269KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.856ms total 187.769ms
,W/PhenotypeConfigurator( 1728): Server returned 404
,I/ActivityManager(  841): Process com.android.settings (pid 5635) has died
,I/ActivityManager(  841): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6195 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5276): Checkin interval check for package: unspecified last checkin: 1450203570120 min interval config: 0 actual interval: 22793572
,I/NetworkMonitor( 5916): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 5916): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/NotificationManager(  841): android: cancelAsUser(353845882) by android
I/GoogleURLConnFactory( 5916): Using platform SSLCertificateSocketFactory
D/eas_req ( 5936): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  841): Process com.lge.sync (pid 5693) has died
,I/NotificationManager( 5916): com.google.android.music: cancel(1061) by com.google.android.music
,I/ActivityManager(  841): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6223 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 5936): JNI_OnLoad()
I/HubEmail( 5936): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5936): registerNatives()
I/HubEmail( 5936): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5936): registerNativeMethods()
I/HubEmail( 5936): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 5936): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 5936): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6223): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6223): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6223): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6223): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6223): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6223): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6223): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
W/ResourcesManager( 6195): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6195): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LGDMClient( 6223): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6249 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6223): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6223): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6223): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6223): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6223): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6223): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  841): Killing 5829:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,V/JNIHelp ( 6195): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System.err( 5787): android.os.DeadObjectException
W/System.err( 5787): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5787): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5787): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5787): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5787): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5787): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5787): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5787): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5787): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5787): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5787): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5787): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 5787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5787): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5787): android.os.DeadObjectException
W/System.err( 5787): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5787): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5787): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5787): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5787): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5787): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5787): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5787): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5787): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5787): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5787): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5787): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5787): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/System  ( 6195): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6195): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  841): failed to open /acct/uid_10089/pid_5829/cgroup.procs: No such file or directory
W/ActivityManager(  841): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6271 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Process com.android.vending (pid 6018) has died
,I/AppUp4:AppBoxCP( 6249): onCreate
,W/AppUp4:DB( 6249):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6249):  setFingerPrint start
I/AppUp4:DB( 6249):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6249):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6249):  SDK version = 0
I/AppUp4:DB( 6249):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6249): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6249): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6249): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6249): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6249): [onReceive] request level :IDLE....
D/UEI.SmartControl( 6271): Quickset Services start...
,I/AppUp4:CustModeStarterReceiver( 6249): onReceive
I/AppUp4:CustModeStarterReceiver( 6249): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
I/UEI.SmartControl( 6271): Manufacture = LGE
D/UEI.SmartControl( 6271): File observer start...
,E/UEI.SmartControl( 6271): IR Port is disabled: false
D/UEI.SmartControl( 6271): Starting file observer...
D/UEI.SmartControl( 6271): Extracting JNI libs...
D/AppUp4:CustFacade( 6249): Context : android.app.ReceiverRestrictedContext@31eb4d91
D/AppUp4:CustFacade( 6249): isCustomizationCompleted : false
D/UEI.SmartControl( 6271): --- this system supports 32-bit or 64-bit only
D/AppUp4:CustFacade( 6249): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6249): begin check event
I/AppUp4:CustModeStarterReceiver( 6249): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6249): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6249): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6249): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 6249): handleAsyncCustNotification do not startCustService
D/UEI.SmartControl( 6271): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6271): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6271): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/LgeMiscReceiver( 3116): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3116): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3116): networkInfo.isConnected() = true
D/PhoneState( 3116): setPdpRejectCasuse : false
I/UEI.SmartControl( 6271): --- Selecting new region: 2
I/UEI.SmartControl( 6271): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6271): Platform has CIR...
,D/UEI.SmartControl( 6271): NO CIR support, need to check package...
,I/UEI.SmartControl( 6271): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6271): QS Service created
I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6297 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/NotificationManager(  841): android: cancelAsUser(-1874035846) by android
E/UEI.SmartControl( 6271): QS start get config
,I/art     ( 6195): CheckpointMarkThreadRoots callback created = 0xb002d960
,W/ResourcesManager( 6195): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6195): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 6195): CheckpointMarkThreadRoots callback created = 0xb002d950
D/UEI.SmartControl( 6271): Loading JNI Libs...
,D/UEI.SmartControl( 6271):  configuring local db...
W/art     ( 6134): Attempt to remove local handle scope entry from IRT, ignoring
I/NotificationManager(  841): android: cancelAsUser(353845882) by android
,W/art     ( 6195): Suspending all threads took: 41.291ms
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,D/libc-netbsd( 6134): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6134): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  268): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  268): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/YouTube MDX( 6195): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/NotificationManager(  841): android: cancelAsUser(-1548111331) by android
D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/PhoneMonitor( 6297): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6297): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6297): onReceive CONNECTIVITY_CHANGE networkType=1
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6195): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
V/DownloadManager( 3139): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3139): DownloadService onCreate
,I/CheckinService( 5276): Checkin interval check for package: unspecified last checkin: 1450203570120 min interval config: 0 actual interval: 22794826
I/DownloadManager( 3139): in removeSpuriousFiles
I/NotificationManager( 3139): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/PhoneMonitor( 6297): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/DownloadManager( 3139): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@3544c1e2 on behalf of 3139
V/TelephonyAutoProfiling( 6297): [loadFeatureFromXml] *** start feature loading from xml
I/DownloadManager( 3139): in trimDatabase
V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@38259973 on behalf of 3139
D/TelephonyAutoProfiling( 6297): [parse] Load xml
,I/ActivityManager(  841): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6348 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3139): DownloadService onStartCommand
V/TelephonyAutoProfiling( 6297): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6297): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3139): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@3a5d34a9 on behalf of 3139
,D/PhoneMonitor( 6297): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5276): Disabling old GoogleServicesFramework version
,I/dex2oat ( 6333): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads871434824.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads871434824.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,V/DownloadManager( 3139): DownloadService onDestroy
D/DrmBroadcastReceiver( 6348): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6348): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6348): Service onCreate
D/WeatherAncestor( 2751): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:39:25
D/DrmService( 6348): Received new request = 2
D/UpdateThreadPoolManager( 2751): 2 : This is isUpdating : false
,D/WeatherAncestor( 2751): connectivity changed - connection : true
D/Weather_cast( 2751): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2751): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:39:25
D/WeatherService( 2751): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/UEI.SmartControl( 6271):  ---- Has DB8: true
,I/DrmSntpClient( 6348): Start Sync process
D/DrmSntpClient( 6348): Server : 0
D/UEI.SmartControl( 6271): QS start statue = true Error code = 0
D/UEI.SmartControl( 6271): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6271): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/libc-netbsd( 6348): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6348): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6348): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6348): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  268): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
,D/UEI.SmartControl( 6271): IRRCDataComm has AudioManager!!!!.
,I/ActivityManager(  841): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6379 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2751): 2 : Utils getTopActivity com.lge.launcher2 / true
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 6348): propertyValue:false
W/irrc_jni( 6271): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6271): IrrcClient ++ 
D/irrcClient( 6271): getIrrcService ++ 
D/irrcClient( 6271): getIrrcService -- 
D/irrcClient( 6271): IrrcClient -- 
W/irrc_jni( 6271): IRRCPlayer_nativeInit -- 
D/WeatherService( 2751): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2751): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/UEI.SmartControl( 6271): Services init done
,D/UEI.SmartControl( 6271): QS Service init finished
D/UEI.SmartControl( 6271): QS Service version name: 0.1.73
D/UEI.SmartControl( 6271): QS Service version code: 1073
I/CheckinService( 5276): Checking schedule, now: 1450226365286 next: 1450203600092
I/CheckinService( 5276): active receiver: enabled
I/UEI.SmartControl( 6271): Device manager: loading config....
D/UEI.SmartControl( 6271): Service requested: Control
,I/NotificationManager( 6195): com.google.android.youtube: cancel(2) by com.google.android.youtube
I/LGDrmClient( 6348): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  283): eDRM_SetDRMTime +++
,I/LGDRM   (  283): [DRM] SET TIME : YR=2015, MON=12, DAY=16
I/LGDRM   (  283): [DRM] SET TIME : HR=0, MIN=39, SEC=25
I/dex2oat ( 6333): dex2oat took 220.466ms (threads: 4)
,V/ILGDrmService(  283): eDRM_SetDRMTime ---
I/DrmSntpClient( 6348): Synched
D/DrmService( 6348): Completed !! request = 2
D/DrmService( 6348): Request count = 0
V/DrmService( 6348): Service onDestroy
I/ActivityManager(  841): Killing 5787:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6271): Config is loaded...
,I/CheckinService( 5276): Preparing to send checkin request
I/EventLogService( 5276): Accumulating logs since 1450226015246
D/UEI.SmartControl( 6271):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6271): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6271): Request IControl service: devices are loaded...
,W/libprocessgroup(  841): failed to open /acct/uid_10106/pid_5787/cgroup.procs: No such file or directory
I/ActivityManager(  841): Killing 6039:com.lge.clock/u0a10 (adj 15): empty #11
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6195): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6195): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6195): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/libprocessgroup(  841): failed to open /acct/uid_10010/pid_6039/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6271): Internal service binding...
,W/ResourcesManager( 6379): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/InstanceID/Rpc( 6195): Found 10006
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6195): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/art     ( 5276): Explicit concurrent mark sweep GC freed 12084(1035KB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 12MB/20MB, paused 2.166ms total 133.597ms
,I/ActivityManager(  841): Killing 6079:com.android.calendar/u0a13 (adj 15): empty #11
,I/NotificationManager( 6195): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  268): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  841): failed to open /acct/uid_10013/pid_6079/cgroup.procs: No such file or directory
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 6195): propertyValue:false
D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinRequestBuilder( 5276): Checkin reason type: 8 attempt count: 1
,I/art     (  841): Explicit concurrent mark sweep GC freed 21610(1015KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.782ms total 171.627ms
,E/ActivityThread( 5276): Failed to find provider info for com.google.android.wearable.settings
I/NotificationManager(  841): android: cancelAsUser(2145784878) by android
,I/NotificationManager( 6134): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,I/Babel_SMS( 6379): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6379): MmsConfig.loadMmsSettings
,I/NotificationManager(  841): android: cancelAsUser(2145784878) by android
,W/art     ( 6379): Suspending all threads took: 9.389ms
,I/Babel_SMS( 6379): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6379): MmsConfig.loadFromDatabase
I/art     ( 6379): CheckpointMarkThreadRoots callback created = 0xb002d570
,E/Babel_SMS( 6379): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6379): MmsConfig.loadFromResources
E/Babel_SMS( 6379): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6379): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6379): CheckpointMarkThreadRoots callback created = 0xb002d550
,D/SensorManager( 6379): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6379): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6379): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6379): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6379): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6379): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6379): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6379): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6379): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6379): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6379): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6379): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6379): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6379): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6379): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6379): found sensor: Motion Accel, handle=46
,W/Settings( 6379): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6379): startup - clean
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
I/Babel   ( 6379): deleted: false for 0
D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  268): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 6195): propertyValue:false
D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  841): Process com.google.android.music:main (pid 5916) has died
,D/libc-netbsd( 6195): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6195): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  841): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6455 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AudioCapabilities( 6379): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6379): Unsupported mime audio/adpcm
W/AudioCapabilities( 6379): Unsupported mime audio/g726
W/AudioCapabilities( 6379): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6379): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6379): Unsupported mime video/mjpg
W/VideoCapabilities( 6379): Unsupported mime video/theora
,W/AudioCapabilities( 6379): Unsupported mime audio/evrc
,W/AudioCapabilities( 6379): Unsupported mime audio/qcelp
W/VideoCapabilities( 6379): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6379): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6379): Unsupported mime audio/qcelp
W/AudioCapabilities( 6379): Unsupported mime audio/evrc
W/VideoCapabilities( 6379): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6379): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6379): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6379): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6379): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6379): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6379): onServiceConnected
,W/Babel   ( 6379): Attempted to change video mute state without an active call.
I/NotificationManager( 6379): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6379): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6379): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6379): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6379): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  268): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 6379): propertyValue:false
I/ActivityManager(  841): Killing 6152:com.qualcomm.timeservice/1000 (adj 15): empty #11
,I/Babel   ( 6379): connection state changed from UNKNOWN to CONNECTED
,W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6152/cgroup.procs: No such file or directory
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  841): Killing 5956:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10023/pid_5956/cgroup.procs: No such file or directory
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1728): Vacuum at: now=1450226366964 tag=VacuumService
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6455): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6455): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/art     ( 5980): Explicit concurrent mark sweep GC freed 2862(119KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 859us total 37.759ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6455): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/InstanceID/Rpc( 5276): Found 10006
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6455): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6455): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6455):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6455):   adb logcat -s GAv4
I/ActivityManager(  841): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6486 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/GAv4    ( 6455): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6455): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 6486): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6486): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 6455): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/MultiDex( 6486): VM with version 2.1.0 has multidex support
I/MultiDex( 6486): install
I/MultiDex( 6486): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6486): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6486): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6486): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2df8ab3a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6486): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6486): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6486): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6486): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6486): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  841): Process com.lge.email (pid 5936) has died
,I/WebViewFactory( 6455): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/NativeLibraryUtils( 6486): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  841): Process com.uei.lg.quicksetsdk.lite (pid 6271) has died
,D/WVCdm   (  272): Instantiating CDM.
,I/WVCdm   (  272): CdmEngine::OpenSession
I/WVCdm   (  272): Level3 Library Dec 11 2014 16:13:16
I/GoogleURLConnFactory( 6486): Using platform SSLCertificateSocketFactory
,I/LibraryLoader( 6455): Time to load native libraries: 4 ms (timestamps 4593-4597)
W/WVCdm   (  272): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  272): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  272): L1 library not specified. Falling Back to L3
I/LibraryLoader( 6455): Expected native library version number "",actual native library version number ""
D/libc-netbsd( 6486): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6486): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6486): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6486): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 6486): propertyValue:false
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 114654409648; DSPS: 3848334; Offset : -2793344524
V/WebViewChromiumFactoryProvider( 6455): Binding Chromium to main looper Looper (main, tid 1) {347256ea}
,I/LibraryLoader( 6455): Expected native library version number "",actual native library version number ""
I/chromium( 6455): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/art     ( 6486): Background sticky concurrent mark sweep GC freed 21668(1279KB) AllocSpace objects, 2(32KB) LOS objects, 11% free, 10MB/11MB, paused 6.760ms total 81.546ms
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  272): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  272): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
I/BrowserStartupController( 6455): Initializing chromium process, singleProcess=true
W/art     ( 6455): Attempt to remove local handle scope entry from IRT, ignoring
D/WVCdm   (  272): PrepareKeyRequest: nonce=3548932116
E/SysUtils( 6455): ApplicationContext is null in ApplicationStatus
,W/chromium( 6455): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6455): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6455): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6455): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6455): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6455): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6455): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6455): Remote Branch: 
I/Adreno-EGL( 6455): Local Patches: 
I/Adreno-EGL( 6455): Reconstruct Branch: 
V/AudioPolicyService(  272): registerClient() client 0xb57f7140, uid 10079
,W/AudioManagerAndroid( 6455): Requires BLUETOOTH permission
D/libc-netbsd( 6486): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6486): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6486): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6486): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NSApplication( 6455): Starting up...
,I/ActivityManager(  841): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6555 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6486): CheckpointMarkThreadRoots callback created = 0xb002dd00
,I/art     ( 6486): CheckpointMarkThreadRoots callback created = 0xb002dcf0
,I/art     ( 6134): CheckpointMarkThreadRoots callback created = 0xb002d450
,I/art     ( 6134): CheckpointMarkThreadRoots callback created = 0xb002d440
,I/MusicWidget( 2713): mDelayedStopHandler : unbind
,I/iu.SyncManager( 5276): SYNC; picasa accounts
I/MusicBrowser( 2762): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2762): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2762): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2762): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2762): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2762): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2762): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2762): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  841):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@11e1f7a6com.lge.music.MediaPlaybackService$6@270f35e7
,D/MusicBrowser( 2762): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2762): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1e631cd
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2762): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
D/NetworkLogImpl( 5276): Loaded NetworkSpeedPredictor
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2762): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2762): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/iu.Environment( 5276): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2762): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/iu.UploadsManager( 5276): num queued entries: 0
,I/iu.UploadsManager( 5276): num updated entries: 0
I/iu.SyncManager( 5276): NEXT; no task
I/MusicBrowser( 2762): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2762): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2762): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2762): reset
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
V/MediaPlayer[Native]( 2762): setListener
V/MediaPlayer[Native]( 2762): disconnect
V/MediaPlayer[Native]( 2762): destructor
V/AudioFlinger(  272): releasing 18 from 2762 for -1
V/AudioFlinger(  272):  decremented refcount to 0
V/AudioFlinger(  272): purging stale effects
V/MediaPlayer[Native]( 2762): disconnect
D/MusicBrowser( 2762): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/ActivityManager(  841): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6582 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/SmartShareClient( 2762): [SmartShareManagerClient] smartshare client supported version code: 305010
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.434ms
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.535ms
,I/SmartShareClient( 2762): [SmartShareManagerClient] smartshare client enabled
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.449ms
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MusicBrowser( 2762): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2762): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2762): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2762): [SmartShareManagerClient] unregisterListener: 462456212
W/SmartShareClient( 2762): [SmartShareManagerClient] unregisterListener invalid listener: 462456212
I/SmartShareClient( 2762): [SmartShareManagerClient] terminate service: 2762/MediaPlaybackService/636993051
E/HomeCloudIF( 2762): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2762): [SmartShareManagerClient] unbindService context:android.app.Application@29b4283d
,V/CloudHub( 2762): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2762): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2762): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2762): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2762): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/ActivityManager(  841): Killing 6223:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/ResourcesManager( 6582): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/CloudHub( 2762): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29981
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/GCM     ( 1728): GCM config loaded
,W/libprocessgroup(  841): failed to open /acct/uid_1000/pid_6223/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  841): Message: 20
D/BluetoothManagerService(  841): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39d4236d:true
,D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
D/BluetoothAdapterService(522550116)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2a2837da
I/ActivityManager(  841): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6606 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/dex2oat ( 6603): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6603): dex2oat took 102.733ms (threads: 4)
,I/Adreno-EGL( 6486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6486): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6486): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6486): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6486): Remote Branch: 
I/Adreno-EGL( 6486): Local Patches: 
I/Adreno-EGL( 6486): Reconstruct Branch: 
,I/DigitalAppWidgetProvider( 6606): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  841): Killing 6249:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_6249/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2751): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:39:29
I/ActivityManager(  841): Process com.google.android.youtube (pid 6195) has died
D/UpdateThreadPoolManager( 2751): 2 : This is isUpdating : false
,D/Weather_cast( 2751): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2751): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:39:29
D/WeatherService( 2751): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2751): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2751): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2751): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/ContextImpl( 3397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/WearableService( 1728): callingUid 10006, callindPid: 1728
,D/LocationInitializer( 5276): Restart initialization of location
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1728): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/WVCdm   (  272): CdmEngine::OpenSession
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 66632(4MB) AllocSpace objects, 57(935KB) LOS objects, 39% free, 13MB/23MB, paused 1.512ms total 127.350ms
,W/GCoreFlp( 1728): No location to return for getLastLocation()
,W/FusedLocationProvider( 1728): location=null
I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6644 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6582): Create singleton instance
,D/UEI.SmartControl( 6644): Quickset Services start...
I/UEI.SmartControl( 6644): Manufacture = LGE
D/UEI.SmartControl( 6644): File observer start...
,E/UEI.SmartControl( 6644): IR Port is disabled: false
D/UEI.SmartControl( 6644): Starting file observer...
D/UEI.SmartControl( 6644): Extracting JNI libs...
D/UEI.SmartControl( 6644): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6582): getMode name:com.lge.qremote
D/UEI.SmartControl( 6644): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6644): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6644): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6644): --- Selecting new region: 2
,I/UEI.SmartControl( 6644): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6644): Platform has CIR...
D/UEI.SmartControl( 6644): NO CIR support, need to check package...
I/UEI.SmartControl( 6644): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6644): QS Service created
E/UEI.SmartControl( 6644): QS start get config
,D/UEI.SmartControl( 6644): Loading JNI Libs...
,I/WVCdm   (  272): CdmEngine::CloseSession
D/UEI.SmartControl( 6644):  configuring local db...
I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  272): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  272): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
D/WVCdm   (  272): PrepareKeyRequest: nonce=1649584627
D/UEI.SmartControl( 6644):  ---- Has DB8: true
,D/UEI.SmartControl( 6644): QS start statue = true Error code = 0
D/UEI.SmartControl( 6644): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6644): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6644): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6644): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6644): IrrcClient ++ 
D/irrcClient( 6644): getIrrcService ++ 
D/irrcClient( 6644): getIrrcService -- 
D/irrcClient( 6644): IrrcClient -- 
W/irrc_jni( 6644): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6644): Services init done
,D/UEI.SmartControl( 6644): QS Service init finished
I/UEI.SmartControl( 6644): Device manager: loading config....
D/UEI.SmartControl( 6644): QS Service version name: 0.1.73
D/UEI.SmartControl( 6644): QS Service version code: 1073
D/UEI.SmartControl( 6644): Service requested: Control
D/UEI.SmartControl( 6644): Config is loaded...
D/UEI.SmartControl( 6644): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6644): Internal service binding...
,D/UEI.SmartControl( 6644):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6644): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6644): -----IControl: 11
D/UEI.SmartControl( 6644): Caller: com.lge.qremote
D/UEI.SmartControl( 6644): ------------ IControl registerCallback...
I/UEI.SmartControl( 6644): Registering callback...
D/UEI.SmartControl( 6644): -----IControl: 19
D/UEI.SmartControl( 6644): Caller: com.lge.qremote
I/UEI.SmartControl( 6644): Registering Services Ready callback...
,I/UEI.SmartControl( 6644): Notify client services are ready...
D/UEI.SmartControl( 6644): -----IControl: 8
D/UEI.SmartControl( 6644): Caller: com.lge.qremote
I/AudioManager( 6582): getMode name:com.lge.qremote
,I/ActivityManager(  841): Killing 6297:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_6297/cgroup.procs: No such file or directory
,I/AudioManager( 6582): getMode name:com.lge.qremote
,I/art     (  841): Explicit concurrent mark sweep GC freed 26488(1213KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.226ms total 136.879ms
,I/AudioManager( 6582): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/WVCdm   (  272): CdmEngine::CloseSession
,I/WVCdm   (  272): L3 Terminate.
I/Adreno-EGL( 6486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6486): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6486): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6486): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6486): Remote Branch: 
I/Adreno-EGL( 6486): Local Patches: 
I/Adreno-EGL( 6486): Reconstruct Branch: 
,I/Adreno-EGL( 6486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6486): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6486): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6486): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6486): Remote Branch: 
I/Adreno-EGL( 6486): Local Patches: 
I/Adreno-EGL( 6486): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5276): Classify the device as Phone.
,D/libc-netbsd( 5276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 5276): propertyValue:false
D/libc-netbsd( 5276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5276): Sending checkin request (9842 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinResponseProcessor( 5276): From server: 3 gservices updates and 0 deletes
,I/CertBlacklister(  841): Certificate blacklist changed, updating...
,I/GservicesProvider( 5980): main difference update completed
,I/CertBlacklister(  841): Certificate blacklist updated
,I/ActivityManager(  841): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6690 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/CheckinRequestBuilder( 5276): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5276): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  841): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6725 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 6348:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10051/pid_6348/cgroup.procs: No such file or directory
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/UpdateRequestReceiver( 6725): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6725): Received malformed URL while handling Gservices.CHANGED_ACTION
I/CheckinRequestBuilder( 5276): Classify the device as Phone.
,E/UpdateRequestReceiver( 6725): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6725): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  841): Killing 6455:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10079/pid_6455/cgroup.procs: No such file or directory
,I/GservicesUpdateTask( 1936): Updating Gservices keys
I/art     ( 5980): Explicit concurrent mark sweep GC freed 10019(496KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.004ms total 31.115ms
,I/CheckinService( 5276): Checkin interval check for package: unspecified last checkin: 1450203570120 min interval config: 0 actual interval: 22803779
I/CheckinTask( 5276): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5276): Checking schedule, now: 1450226373920 next: 1450753622909
,I/CheckinService( 5276): active receiver: disabled
,I/SystemUpdateService( 5276): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/CheckinService( 5276): Checking schedule, now: 1450226373967 next: 1450753622909
,I/CheckinService( 5276): active receiver: disabled
D/SystemUpdateService( 5276): onCreate
D/SystemUpdateService( 5276): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5276): cancelUpdate (empty URL)
,I/SystemUpdateService( 5276): active receiver: disabled
,I/NotificationManager( 5276): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 5276): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/art     ( 5276): Explicit concurrent mark sweep GC freed 19747(1442KB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 12MB/21MB, paused 1.656ms total 69.960ms
,I/art     ( 5980): Explicit concurrent mark sweep GC freed 3025(114KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.164ms total 27.191ms
,D/CheckinService( 5276): Recording last checkin time for package unspecified as 1450226374295
,D/SystemUpdateService( 5276): onDestroy
,E/DynamiteModule( 5276): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5276): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5276): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5276): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5276): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5276): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5276): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5276): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5276): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5276): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5276): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5276): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5276): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5276): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5276): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5276): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5276): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5276): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5276): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5276): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5276): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5276): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5276): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5276): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5276): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5276): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5276): 		... 17 more
E/DynamiteModule( 5276): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 5276): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5276): Selected local version of com.google.android.gms.flags
D/SystemEventReceiver( 5276): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5276): Updating ocr activity enabled=false
,W/ActivityManager(  841): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 5276): Updating downloaded model state (gservices changed)
,I/art     ( 5980): Explicit concurrent mark sweep GC freed 2652(104KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 769us total 27.143ms
,I/art     ( 5276): Explicit concurrent mark sweep GC freed 12106(793KB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 12MB/21MB, paused 7.619ms total 99.998ms
,W/SQLiteConnectionPool( 5276): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/GCM     ( 1728): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  841): Killing 6134:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/NotificationManager(  841): android: cancelAsUser(-591465577) by android
I/ActivityManager(  841): Killing 6555:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  841): failed to open /acct/uid_10086/pid_6134/cgroup.procs: No such file or directory
,W/libprocessgroup(  841): failed to open /acct/uid_10048/pid_6555/cgroup.procs: No such file or directory
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 13829(677KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/23MB, paused 1.773ms total 85.159ms
,I/GCoreUlr( 1728): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1728): DispatchingService.onCreate()
D/UEI.SmartControl( 6644): Internal timer expired: 1
,I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1833): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  841): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1872): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/art     ( 5980): Explicit concurrent mark sweep GC freed 2678(107KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.515ms total 66.918ms
,I/ActivityManager(  841): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6807 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/GCoreUlr( 1728): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
D/administrator(  841): Handling package changes for user 0
,E/ctxmgr  ( 1728): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/PhoneMonitor( 6807): Register our PhoneStateListener
,I/art     (  841): Explicit concurrent mark sweep GC freed 26904(1366KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.881ms total 174.426ms
,W/ctxmgr  ( 1728): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1728): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
V/SetupWizard( 6807): Connected to Gservices successfully
,I/NotificationService(  841): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
I/GCoreUlr( 1728): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/BackupManagerService(  841): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  841): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/BackupManagerService(  841): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
D/LCardEmulationManager( 1780): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1780): getDefaultRoute
,D/PhoneMonitor( 6807): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/ActivityManager(  841): Killing 2762:com.lge.music/u0a28 (adj 15): empty #11
V/TelephonyAutoProfiling( 6807): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6807): [parse] Load xml
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AudioFlinger(  272): 2762 died, releasing its sessions
V/AudioFlinger(  272):  pid 1745 @ 0
V/AudioFlinger(  272):  pid 3116 @ 1
V/AudioFlinger(  272):  pid 3116 @ 2
V/TelephonyAutoProfiling( 6807): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6807): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6807): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  841): failed to open /acct/uid_10028/pid_2762/cgroup.procs: No such file or directory
,V/BackupManagerService(  841): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  841): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@387e9c1b
I/GCoreUlr( 1728): DispatchingService.onDestroy()
I/GCoreUlr( 1728): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
,D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ResourceType(  841): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6834 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LGHome]EVENT( 1872): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1728): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  841): applying state to connected service
,I/NotificationManager( 6379): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6379): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6379): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 6834): onCreate
,V/JNIHelp ( 6379): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/AppUp4:DB( 6834):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6834):  setFingerPrint start
I/AppUp4:DB( 6834):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6834):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6834):  SDK version = 0
I/AppUp4:DB( 6834):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6834): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6834): onReceive
I/AppUp4:CustModeStarterReceiver( 6834): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6834): Context : android.app.ReceiverRestrictedContext@1e3b702a
,D/AppUp4:CustFacade( 6834): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6834): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6834): begin check event
I/AppUp4:CustModeStarterReceiver( 6834): Event For Nothing, skip.
W/System  ( 6379): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6379): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  841): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6856 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6856): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6856): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 6856): Total System Memory = 906309632
,I/GalleryUtils( 6856): Application Heap = 96 MB
I/AppConfig( 6856): App Tier : NOT_DEF
D/SystemHelper( 6856): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  841): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6878 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 6606:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10010/pid_6606/cgroup.procs: No such file or directory
,W/ResourcesManager( 6878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6878): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6878): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6878): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6878): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6878): BUILD Country: EU
I/SystemConfig( 6878): BUILD Operator: OPEN
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/SystemConfig( 6878): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6878): existFile = false
I/SystemConfig( 6878): canReadFile = false
I/SystemConfig( 6878): systemFeature RCS result false
D/SystemConfig( 6878): refreshRcsSupport() :false
,I/ActivityManager(  841): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6900 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  841): Killing 6690:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  841): failed to open /acct/uid_10009/pid_6690/cgroup.procs: No such file or directory
,I/LockScreenSettings( 6900): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6900): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6900): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6900): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6900): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6900): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  841): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6917 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  841): Killing 6725:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10003/pid_6725/cgroup.procs: No such file or directory
,W/ResourcesManager( 6917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  841): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6942 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 275us total 21.707ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.623ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.992ms
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
,I/ActivityManager(  841): Killing 6807:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10038/pid_6807/cgroup.procs: No such file or directory
,D/Finsky  ( 6942): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6942): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6942): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6942): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6942): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@3ab659cf on behalf of 6942
D/Ads     ( 6942): Skipping gmscore version check
D/Finsky  ( 6942): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6942): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6942): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5276): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5276): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6942): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5276): updateResources: need to parse f{com.google.android.gms}
I/Icing   ( 5276): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5276): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5276): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  841): Killing 6486:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10006/pid_6486/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/charger_monitor(  472): init target 500000
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  472): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/WifiController(  841): battery changed pluggedType: 2
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  841): Killing 6644:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6582): android.os.DeadObjectException
,W/System.err( 6582): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6582): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6582): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6582): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6582): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6582): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6582): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6582): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6582): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6582): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6582): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6582): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6582): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6582): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6582): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6582): android.os.DeadObjectException
W/System.err( 6582): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6582): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6582): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6582): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6582): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6582): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6582): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6582): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6582): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6582): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6582): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6582): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6582): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6582): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6582): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  841): failed to open /acct/uid_10089/pid_6644/cgroup.procs: No such file or directory
W/ActivityManager(  841): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  841): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7018 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7018): Quickset Services start...
,I/UEI.SmartControl( 7018): Manufacture = LGE
D/UEI.SmartControl( 7018): File observer start...
E/UEI.SmartControl( 7018): IR Port is disabled: false
D/UEI.SmartControl( 7018): Starting file observer...
D/UEI.SmartControl( 7018): Extracting JNI libs...
D/UEI.SmartControl( 7018): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7018): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7018): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7018): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7018): --- Selecting new region: 2
,I/UEI.SmartControl( 7018): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7018): Platform has CIR...
D/UEI.SmartControl( 7018): NO CIR support, need to check package...
I/UEI.SmartControl( 7018): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7018): QS Service created
E/UEI.SmartControl( 7018): QS start get config
,D/UEI.SmartControl( 7018): Loading JNI Libs...
,D/UEI.SmartControl( 7018):  configuring local db...
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/UEI.SmartControl( 7018):  ---- Has DB8: true
,D/UEI.SmartControl( 7018): QS start statue = true Error code = 0
D/UEI.SmartControl( 7018): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7018): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7018): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7018): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7018): IrrcClient ++ 
D/irrcClient( 7018): getIrrcService ++ 
D/irrcClient( 7018): getIrrcService -- 
D/irrcClient( 7018): IrrcClient -- 
W/irrc_jni( 7018): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7018): Services init done
,I/UEI.SmartControl( 7018): Device manager: loading config....
,D/UEI.SmartControl( 7018): QS Service init finished
D/UEI.SmartControl( 7018): QS Service version name: 0.1.73
D/UEI.SmartControl( 7018): QS Service version code: 1073
D/UEI.SmartControl( 7018): Service requested: Control
D/UEI.SmartControl( 7018): Config is loaded...
D/UEI.SmartControl( 7018): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7018): -----IControl: 11
I/ActivityManager(  841): Killing 6582:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7018): Caller: com.lge.qremote
D/UEI.SmartControl( 7018): ------------ IControl registerCallback...
I/UEI.SmartControl( 7018): Registering callback...
D/UEI.SmartControl( 7018):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7018): Notify AllClients services are ready: 0
,W/libprocessgroup(  841): failed to open /acct/uid_10106/pid_6582/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7018): Internal service binding...
W/PackageSettings(  841): Skipping PackageSetting{342ecc75 com.example.hello/10317} due to missing metadata
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinService( 5276): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/UEI.SmartControl( 7018): Internal timer expired: 1
,D/UEI.SmartControl( 7018): Service.onUnbind: IControl
D/UEI.SmartControl( 7018): Service.onDestroy
W/System.err( 7018): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1f257b64
W/System.err( 7018): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7018): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7018): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7018): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7018): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7018): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7018): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7018): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7018): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7018): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7018): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7018): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7018): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
,W/System.err( 7018): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7018): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1f257b64
D/UEI.SmartControl( 7018): Shutdown IRRCPlayer... 
W/irrc_jni( 7018): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7018): ~IrrcClient ++ 
D/irrcClient( 7018): ~IrrcClient -- 
W/irrc_jni( 7018): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7018): Blaster closed
D/UEI.SmartControl( 7018): Blaster closed
D/UEI.SmartControl( 7018): Shut down QS...
,D/UEI.SmartControl( 7018): Stopped file observer...
I/UEI.SmartControl( 7018): QS lib stop result = true
D/UEI.SmartControl( 7018): QS shutdown complete
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 134655259745; DSPS: 4503722; Offset : -2793347356
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{36392b60 type 2 when 137953 android} when 137953
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=926040437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,D/WeatherService( 2751): 2 : TimeTick Intent has been received, Time(hour:min:sec) 1:40:0
D/WeatherService( 2751): 2 : TimeTick Intent And Screen On
D/WeatherService( 2751): 2 : SDK version : 21
W/ActivityManager(  841): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2751): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2751): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2751): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2751): 2 : requestRefreshAppWidget, isUpdateStart : false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UpdateThreadPoolManager( 2751): 2 : This is isUpdating : false
D/WeatherService( 2751): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2751): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2751): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2751): 2 : Fixed theme : optimus
D/WeatherReflect( 2751): 2 : Map key string is -2
,D/lim     ( 2751): 2 : time = 01:40
,I/WeatherReflect( 2751): Model Name : LG-D722
D/WeatherTheme( 2751): 2 : Different view - status_min_formatted : 39 != 40
D/WeatherTheme( 2751): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2751): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2751): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2751): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2751): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2751): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2751): forecast size is 0
D/Theme   ( 2751): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2751): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2751): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2751): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2751): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2751): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2751): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2751): url is : null
D/Theme   ( 2751): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2751): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2751): 2 : update view, appWidgetId: 2
D/WeatherService( 2751): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 1:40:0
D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=926040437 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
,I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1872): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1872): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  841): ALS enabled for SRE
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28638 ms ago)
,D/qdlights(  841): set_light_backlight: 252
,D/qdlights(  841): set_light_backlight: 249
D/qdlights(  841): set_light_backlight: 246
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
D/qdlights(  841): set_light_backlight: 242
,D/qdlights(  841): set_light_backlight: 239
,D/qdlights(  841): set_light_backlight: 236
,D/qdlights(  841): set_light_backlight: 232
,D/qdlights(  841): set_light_backlight: 229
,D/qdlights(  841): set_light_backlight: 226
,D/qdlights(  841): set_light_backlight: 222
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  841): set_light_backlight: 219
D/qdlights(  841): set_light_backlight: 216
,D/qdlights(  841): set_light_backlight: 212
,D/qdlights(  841): set_light_backlight: 209
,D/qdlights(  841): set_light_backlight: 206
,D/qdlights(  841): set_light_backlight: 202
,D/qdlights(  841): set_light_backlight: 199
,D/qdlights(  841): set_light_backlight: 196
,D/qdlights(  841): set_light_backlight: 192
,D/qdlights(  841): set_light_backlight: 189
,D/qdlights(  841): set_light_backlight: 186
,D/qdlights(  841): set_light_backlight: 182
,D/qdlights(  841): set_light_backlight: 179
,D/qdlights(  841): set_light_backlight: 176
,D/qdlights(  841): set_light_backlight: 172
,D/qdlights(  841): set_light_backlight: 169
,D/qdlights(  841): set_light_backlight: 166
,D/qdlights(  841): set_light_backlight: 162
,D/qdlights(  841): set_light_backlight: 159
,D/qdlights(  841): set_light_backlight: 156
,D/qdlights(  841): set_light_backlight: 152
,D/qdlights(  841): set_light_backlight: 149
,D/qdlights(  841): set_light_backlight: 146
,D/qdlights(  841): set_light_backlight: 142
,D/qdlights(  841): set_light_backlight: 139
,D/qdlights(  841): set_light_backlight: 136
,D/qdlights(  841): set_light_backlight: 132
,D/qdlights(  841): set_light_backlight: 129
,D/qdlights(  841): set_light_backlight: 126
,D/qdlights(  841): set_light_backlight: 122
,D/qdlights(  841): set_light_backlight: 119
,D/qdlights(  841): set_light_backlight: 116
,D/qdlights(  841): set_light_backlight: 112
,D/qdlights(  841): set_light_backlight: 109
,D/qdlights(  841): set_light_backlight: 106
,D/qdlights(  841): set_light_backlight: 102
,D/qdlights(  841): set_light_backlight: 99
,D/qdlights(  841): set_light_backlight: 96
,D/qdlights(  841): set_light_backlight: 92
,D/qdlights(  841): set_light_backlight: 89
,D/qdlights(  841): set_light_backlight: 86
,D/qdlights(  841): set_light_backlight: 82
,D/qdlights(  841): set_light_backlight: 79
,D/qdlights(  841): set_light_backlight: 76
,D/qdlights(  841): set_light_backlight: 72
,D/qdlights(  841): set_light_backlight: 69
,D/qdlights(  841): set_light_backlight: 66
,D/qdlights(  841): set_light_backlight: 62
,D/qdlights(  841): set_light_backlight: 59
,D/qdlights(  841): set_light_backlight: 56
,D/qdlights(  841): set_light_backlight: 52
,D/qdlights(  841): set_light_backlight: 49
,D/qdlights(  841): set_light_backlight: 46
,D/qdlights(  841): set_light_backlight: 42
,D/qdlights(  841): set_light_backlight: 39
,D/qdlights(  841): set_light_backlight: 36
,D/qdlights(  841): set_light_backlight: 32
,D/qdlights(  841): set_light_backlight: 29
,D/qdlights(  841): set_light_backlight: 26
,D/qdlights(  841): set_light_backlight: 22
,D/qdlights(  841): set_light_backlight: 19
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  841): set_light_backlight: 16
,D/qdlights(  841): set_light_backlight: 12
,D/qdlights(  841): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 154656007758; DSPS: 5159107; Offset : -2793362465
,I/PowerManagerService(  841): ALS enabled for SRE
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35632 ms ago)
,I/PowerManagerService(  841): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  841): ALS enabled for SRE
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35644 ms ago)
,W/ContextImpl(  841): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  841): Sleeping (uid 1000)...
,D/LPWGController(  841): [updateScreenState] screen on = false
D/LPWGController(  841): disable proximity sensor
D/LPWGController(  841): enable proximity sensor
I/SensorManager(  841): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2dcee819] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  841): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  841): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  841): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  841): activate: handle is 48, enable
V/sensors_hal_Ctx(  841): activate sensors is 1400000000000
D/sensors_hal_Thresh(  841): enable: handle=48
I/sensors_hal_SAM(  841): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  841): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  841): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  841): enable: Received response: 0
D/PowerManagerServiceEx(  841): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35686 ms ago)
I/Adreno-EGL(  841): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  841): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  841): Build Date: 03/02/15 Mon
I/Adreno-EGL(  841): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  841): Remote Branch: 
I/Adreno-EGL(  841): Local Patches: 
I/Adreno-EGL(  841): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (133 us)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Sensors (  421): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  841): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  841): processInd: handle 48, count=1
V/sensors_hal_Thresh(  841): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  841): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  841): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  841): poll: count: 256
I/sensors_hal_Ctx(  841): poll: released wakelock sensor_ind
D/sensors_hal_Util(  841): waitForResponse: timeout=0
D/LPWGController(  841): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  841): current mode = 1  value = 1 1
I/LPWGController(  841): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  841): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  841): set_light_backlight: 0
,I/SensorManager(  841): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  841): activate: handle is 46, disable
V/sensors_hal_Ctx(  841): activate sensors is 1000000000000
D/sensors_hal_LP2(  841): enable: handle=46
D/sensors_hal_LP2(  841): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  841): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  841): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/sensors_hal_SAM(  841): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  841): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  841): Display changed displayId=0
,D/DSDPConnection( 1745): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
,D/SurfaceControl(  841): Excessive delay in setPowerMode(): 219ms
,I/QCOM PowerHAL(  841): Got set_interactive hint
D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1370): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1370): handleNotifyScreenOff
D/WifiServerServiceExt(  841): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  841): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=on, calling pid 841
,D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: enter: screen_state=on
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: exit
V/voice   (  272): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  272): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  272): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  272): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  272): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  272): adev_set_parameters: exit with code(0)
D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
,D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/GpsLocationProvider(  841): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1833): |CORE| sendScreenState: state:true
I/LEDService( 1798): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1798): stopPatternFlashing()
D/LNfcService( 1780): action : android.intent.action.SCREEN_ON
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): updateLightsLocked : turn off led
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1798): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDHandler( 1798): RESTART MSG
D/Cliptray Service( 1798): lockStatus = 0
D/NfcServiceNXP( 1780): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1780): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1780): isRequireNfcCRouting() return true
D/LNfcService( 1780): isHCERoutingtoHost() return : true
D/NfcService( 1780): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1780): mEnableLPD: true
D/NfcService( 1780): mEnableReader: false
D/NfcService( 1780): mEnableHostRouting: true
D/NfcService( 1780): newParams.techmask= mTechMask: default
D/NfcService( 1780): mEnableLPD: true
D/NfcService( 1780): mEnableReader: false
D/NfcService( 1780): mEnableHostRouting: true
D/NfcService( 1780): screenState= 3
D/NfcService( 1780): Discovery configuration equal, not updating.
,D/SplitWindow(  841): check instance of lgWin Window{10f59d8c u0 SearchPanel}
,D/Ulp_jni (  841): JNI:system_update. Event-0
,D/InputDispatcher(  841): Window went away: Window{3c8e149d u0 SearchPanel}
I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2751): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:40:10
,D/WeatherService( 2751): 2 : ACTION screen on
D/WeatherService( 2751): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2751): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2751): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:40:10
D/AppCleanupService( 3850): android.intent.action.SCREEN_ON
,W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): ACTION_SCREEN_ON
V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=off, calling pid 841
,D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: enter: screen_state=off
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: exit
V/voice   (  272): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  272): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  272): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  272): adev_set_parameters: exit with code(0)
D/WifiController(  841): CMD_SCREEN_OFF 
D/WifiController(  841): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  841): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
I/Sensors (  421): sns_pwr.c(301):releasing wakelock
,I/QCNEJ   ( 1833): |CORE| sendScreenState: state:false
,I/LEDService( 1798): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1798): stopPatternFlashing()
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1798): clear
I/LEDService( 1798): getCurrentHighestLGLedRecord : size = 1
D/LNfcService( 1780): action : android.intent.action.SCREEN_OFF
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1798): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1798): updateLightsLocked : turn on led
E/LEDService( 1798): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1798): Can't handle this request of patternId:0
D/LEDHandler( 1798): RESTART MSG
D/NfcServiceNXP( 1780): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1872): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2751): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:40:10
D/WeatherService( 2751): 2 : ACTION screen off
D/WeatherService( 2751): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2751): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:40:10
D/AppCleanupService( 3850): android.intent.action.SCREEN_OFF
D/AppCleanupService( 3850): AppUsageStatsSaveTask
,W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  841): ACTION_SCREEN_OFF
E/NxpNfcJni( 1780): getReconnectState = 0x0
,D/LCardEmulationManager( 1780): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1780): getDefaultRoute
D/LNfcService( 1780): isRequireNfcCRouting() return true
D/LNfcService( 1780): isHCERoutingtoHost() return : true
D/NfcService( 1780): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1780): mEnableLPD: true
D/NfcService( 1780): mEnableReader: false
D/NfcService( 1780): mEnableHostRouting: true
D/NfcService( 1780): newParams.techmask= mTechMask: 0
D/NfcService( 1780): mEnableLPD: true
D/NfcService( 1780): mEnableReader: false
D/NfcService( 1780): mEnableHostRouting: true
D/NfcService( 1780): screenState= 1
E/NxpNfcJni( 1780): getReconnectState = 0x0
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{34dcecd5 type 2 when 161597 com.android.systemui} when 161597
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1745): getCallState : 0
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{13f7ecea type 2 when 167962 android} when 167962
,E/ActivityThread( 5276): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  841): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 141223, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  841): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 232238, reason: UserStart
I/NotificationManager(  841): android: cancelAsUser(716319171) by android
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 174656765459; DSPS: 5814492; Offset : -2793367547
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  472): init target 500000
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{1789dab7 type 2 when 187499 com.google.android.gms} when 187499
,I/PhenotypeConfigurator( 1728): Scheduling Phenotype for one-off execution 3951 seconds from now (1450226441097)
,D/GetConfigurationSnapshotOperation( 1728): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     (  841): Explicit concurrent mark sweep GC freed 57193(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 2.472ms total 167.914ms
,I/PhenotypeFlagCommitter( 1728): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1728): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 24123(1451KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 14MB/23MB, paused 1.556ms total 90.202ms
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{4e181bc type 2 when 188670 android} when 188670
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 194657559253; DSPS: 6469878; Offset : -2793367861
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{217e4c54 type 2 when 197986 android} when 197986
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): init target 500000
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 214658321225; DSPS: 7125263; Offset : -2793368464
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1728): disconnect managed GoogleApiClient
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 234659080384; DSPS: 7780647; Offset : -2793341622
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  472): init target 500000
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 254659845688; DSPS: 8436033; Offset : -2793369828
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 274660940161; DSPS: 9091428; Offset : -2793343027
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 294661707028; DSPS: 9746814; Offset : -2793369903
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 314662377853; DSPS: 10402195; Offset : -2793340000
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 334663123627; DSPS: 11057580; Offset : -2793357660
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  841): remove 7a79102
,D/LocationManagerService(  841): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  841): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  841): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  841): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  841): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=926040437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=926040437 [*alarm*], flags=0x0
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 354663885912; DSPS: 11712965; Offset : -2793357611
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 374664581268; DSPS: 12368348; Offset : -2793364577
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 394665448292; DSPS: 13023736; Offset : -2793351811
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 414666030992; DSPS: 13679115; Offset : -2793349074
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  841): android: cancelAsUser(2) by android
,D/libc-netbsd( 6942): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6942): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6942): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6942): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  268): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 6942): propertyValue:false
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=926040437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{11be3bb type 2 when 433800 android} when 433800
D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=926040437 [*alarm*], flags=0x0
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 434666710047; DSPS: 14334497; Offset : -2793341745
,I/jxcore-log( 5533): Connected to the server!
I/jxcore-log( 5533): 
,I/chromium( 5533): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 454667477695; DSPS: 14989883; Offset : -2793367710
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 474668139406; DSPS: 15645264; Offset : -2793346400
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 494668918254; DSPS: 16300650; Offset : -2793361087
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 514669665641; DSPS: 16956034; Offset : -2793346018
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 534670414123; DSPS: 17611419; Offset : -2793360318
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 554671244793; DSPS: 18266806; Offset : -2793354170
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 574671915619; DSPS: 18922188; Offset : -2793354209
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 594672570560; DSPS: 19577569; Offset : -2793340477
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 614673250552; DSPS: 20232952; Offset : -2793362311
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 634673960544; DSPS: 20888335; Offset : -2793354327
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=926040437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,D/Finsky  ( 6942): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{21a0fc31 type 0 when 1450226893143 com.android.vending} when 1450226893143
,I/ActivityManager(  841): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7248 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,D/libc-netbsd( 6942): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6942): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6942): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6942): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  268): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  268): res_queryN name = xxxxx succeed
,I/System.out( 6942): propertyValue:false
D/libc-netbsd( 6942): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6942): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DigitalAppWidgetProvider( 7248): onReceive: com.android.deskclock.ON_QUARTER_HOUR
V/DigitalAppWidgetProvider( 7248): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1e3b702a
D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=926040437 [*alarm*], flags=0x0
D/libc-netbsd( 6942): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6942): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,I/qtaguid ( 6942): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6942): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6942): untagSocket(44) failed with errno -22
D/Finsky  ( 6942): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  841): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7290 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  841): android: cancelAsUser(2) by android
,W/ResourcesManager( 7290): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7290): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7290): VM with version 2.1.0 has multidex support
I/MultiDex( 7290): install
,I/MultiDex( 7290): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7290): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6942): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6942): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6942): untagSocket(44) failed with errno -22
W/ActivityThread( 7290): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7290): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2df8ab3a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7290): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7290): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7290): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1728): callingUid 10006, callindPid: 1728
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5276): Restart initialization of location
,E/MDM     ( 1728): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 7290): Reading stored module config
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 7290): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1728): No location to return for getLastLocation()
,W/FusedLocationProvider( 1728): location=null
D/NativeLibraryUtils( 7290): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 7290): Connecting to CarCallService...
I/art     ( 6942): CheckpointMarkThreadRoots callback created = 0xb002d930
,I/art     ( 7290): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7290): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6942): CheckpointMarkThreadRoots callback created = 0xb01e6e70
,D/CAR.SERVICE( 7290): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 7290): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7290): Creating a new PhoneAdapter instance
W/ActivityManager(  841): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7290): setListener: com.google.android.gms.car.dn@23f17351
W/ActivityManager(  841): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 7290): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 7290): Starting CarCallService with initial phone null
I/NotificationManager( 7290): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 7290): Package validated; name: com.android.vending
,I/ActivityManager(  841): Process com.google.android.talk (pid 6379) has died
,I/NotificationManager( 6942): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6942): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,I/qtaguid ( 6942): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6942): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6942): untagSocket(44) failed with errno -22
,D/Finsky  ( 6942): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.magazines to true
,D/Finsky  ( 6942): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.magazines from  to d_AAAAAAADF8w=
W/ResourcesManager( 6942): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6942): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6942): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6942): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 6942): [1] DailyHygiene.access$600: Logging device features
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 654674588348; DSPS: 21543715; Offset : -2793336511
V/AlarmManager(  841): RTC_WAKEUP set : Alarm{1846c1f1 type 0 when 1450226907882 com.android.vending} when 1450226907882
,D/DeviceConnectionService( 1728): client connected with version: 8296000
,D/Finsky  ( 6942): [856] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  841): android: cancelAsUser(2) by android
,I/ActivityManager(  841): Killing 6834:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  841): failed to open /acct/uid_10011/pid_6834/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 7290): mConnectedToCar = false, abort
,E/ActivityThread( 7290): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f0f9a19 that was originally bound here
E/ActivityThread( 7290): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f0f9a19 that was originally bound here
E/ActivityThread( 7290): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7290): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7290): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7290): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7290): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7290): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7290): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7290): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7290): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7290): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 7290): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 7290): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 7290): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 7290): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 7290): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 7290): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 7290): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7290): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7290): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7290): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7290): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7290): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7290): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 7290): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@331e8078 that was originally bound here
E/ActivityThread( 7290): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@331e8078 that was originally bound here
E/ActivityThread( 7290): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7290): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7290): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7290): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7290): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7290): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7290): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7290): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 7290): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 7290): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 7290): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 7290): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 7290): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 7290): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 7290): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 7290): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7290): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7290): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7290): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7290): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7290): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7290): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  841): Unbind failed: could not find connection for android.os.BinderProxy@3ad54fb0
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{14a9a5ae type 0 when 1450226922243 com.android.vending} when 1450226922243
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/Finsky  ( 6942): [845] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6942): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 674675270685; DSPS: 22199098; Offset : -2793356156
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 694676126927; DSPS: 22854486; Offset : -2793354146
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 714676788743; DSPS: 23509868; Offset : -2793363716
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 734677457694; DSPS: 24165250; Offset : -2793366517
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 754678224561; DSPS: 24820635; Offset : -2793362276
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 774678997678; DSPS: 25476020; Offset : -2793351813
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 794679669232; DSPS: 26131402; Offset : -2793351593
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 814680565892; DSPS: 26786792; Offset : -2793370930
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 834681409791; DSPS: 27442179; Offset : -2793351343
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 854682082961; DSPS: 28097561; Offset : -2793349144
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 874682752952; DSPS: 28752943; Offset : -2793350409
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 894683411695; DSPS: 29408325; Offset : -2793363000
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 914684191479; DSPS: 30063710; Offset : -2793346417
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 934684849909; DSPS: 30719092; Offset : -2793359452
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 954685695214; DSPS: 31374480; Offset : -2793368847
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 974686273696; DSPS: 32029859; Offset : -2793369939
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 994686929990; DSPS: 32685240; Offset : -2793354253
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=926040437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{f4abf4f type 2 when 1002503 com.android.bluetooth} when 1002503
D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=926040437 [*alarm*], flags=0x0
,W/bt-smp  ( 1966): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1966): Plain text(LSB ~ MSB) = 34 d5 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1966): Encrypted text(LSB ~ MSB) = 29 87 41 8a 64 1e 86 c3 41 fe 9f 31 0c 68 36 6a 
W/bt-btm  ( 1966): Stopping oneshot timer
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1014687602742; DSPS: 33340622; Offset : -2793353174
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{f37b6dc type 2 when 1015808 com.google.android.gms} when 1015808
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1034688354297; DSPS: 33996007; Offset : -2793364845
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1054689069967; DSPS: 34651390; Offset : -2793350688
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1074689730271; DSPS: 35306772; Offset : -2793361928
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1094690740421; DSPS: 35962165; Offset : -2793358780
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1114691407340; DSPS: 36617547; Offset : -2793363117
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1134692149468; DSPS: 37272931; Offset : -2793353333
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1154692813523; DSPS: 37928313; Offset : -2793360664
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1174693487161; DSPS: 38583695; Offset : -2793358361
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1194694346372; DSPS: 39239083; Offset : -2793353720
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1214695124020; DSPS: 39894469; Offset : -2793369347
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  841): User[0] Flushing usage stats to disk
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1234695861201; DSPS: 40549853; Offset : -2793364744
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1254696622911; DSPS: 41205238; Offset : -2793366157
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1274697338737; DSPS: 41860621; Offset : -2793351896
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1294698013105; DSPS: 42516003; Offset : -2793349228
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1314698672836; DSPS: 43171385; Offset : -2793360700
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1334699431162; DSPS: 43826770; Offset : -2793365887
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1354700583707; DSPS: 44482167; Offset : -2793342545
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1374701255262; DSPS: 45137549; Offset : -2793341959
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1394701931401; DSPS: 45792932; Offset : -2793368402
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1414702682746; DSPS: 46448316; Offset : -2793350469
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1434703416853; DSPS: 47103700; Offset : -2793347038
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1454704096117; DSPS: 47759083; Offset : -2793369861
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1474704836265; DSPS: 48414467; Offset : -2793361926
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1494705560997; DSPS: 49069851; Offset : -2793369408
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1514706243073; DSPS: 49725233; Offset : -2793359110
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1534706908950; DSPS: 50380615; Offset : -2793364282
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1554707649308; DSPS: 51035999; Offset : -2793356187
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1574708324248; DSPS: 51691381; Offset : -2793353520
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1594709086584; DSPS: 52346766; Offset : -2793353499
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1614709814181; DSPS: 53002150; Offset : -2793358583
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1634710980683; DSPS: 53657548; Offset : -2793352088
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1654711746249; DSPS: 54312933; Offset : -2793348863
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1674712400408; DSPS: 54968315; Offset : -2793366274
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1694713256650; DSPS: 55623703; Offset : -2793364810
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1714713910341; DSPS: 56279084; Offset : -2793351805
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1734714657260; DSPS: 56934469; Offset : -2793368164
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1754715338762; DSPS: 57589851; Offset : -2793357424
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1774716096307; DSPS: 58245236; Offset : -2793362949
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1794716794581; DSPS: 58900619; Offset : -2793366319
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1814717470042; DSPS: 59556001; Offset : -2793362558
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1834718305242; DSPS: 60211388; Offset : -2793351279
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1854719047891; DSPS: 60866772; Offset : -2793340948
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=926040437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,V/AlarmManager(  841): RTC_WAKEUP set : Alarm{4ee6eba type 0 when 1450227815314 com.google.android.gms} when 1450227815314
I/ProcessStatsService(  841): Prepared write state in 14ms
,I/ProcessStatsService(  841): Prepared write state in 20ms
,I/ProcessStatsService(  841): Prepared write state in 9ms
,I/DigitalAppWidgetProvider( 7248): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7248): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1e3b702a
,D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=926040437 [*alarm*], flags=0x0
D/LocationManagerService(  841): getAllProviders()=[passive, gps, network]
,I/EventLogService( 5276): Aggregate from 1450226365675 (log), 1450226015246 (data)
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@141b7f5c on behalf of 5276
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  268): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  268): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  268): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  268): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  268): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,I/art     ( 3139): Explicit concurrent mark sweep GC freed 5804(415KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 918us total 66.036ms
,V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@dab7265 on behalf of 5276
V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@2df8ab3a on behalf of 5276
I/art     (  841): Explicit concurrent mark sweep GC freed 48619(2MB) AllocSpace objects, 6(221KB) LOS objects, 33% free, 23MB/35MB, paused 3.378ms total 251.268ms
I/NotificationManager(  841): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ProcessStatsService(  841): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-14-31.bin
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,W/Settings(  841): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  841): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  841): battery changed pluggedType: 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1874719931320; DSPS: 61522161; Offset : -2793343206
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  841): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  841): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  841): tsOffsetIs: Apps: 1894720835948; DSPS: 62177551; Offset : -2793353532
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  841): acquireWakeLockInternal: lock=926040437, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=841
,V/AlarmManager(  841): ELAPSED_WAKEUP set : Alarm{c3b5336 type 2 when 1902535 com.android.bluetooth} when 1902535
W/bt-smp  ( 1966): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1966): Plain text(LSB ~ MSB) = c6 e0 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1966): Encrypted text(LSB ~ MSB) = 3d 6d 5b 21 a9 61 6c 1f 4a 43 fc 39 8a 56 5e 8a 
,TIME-OUT KILL (timeout was 1800000ms),W/bt-btm  ( 1966): Stopping oneshot timer
D/PowerManagerServiceEx(  841): releaseWakeLockInternal: lock=926040437 [*alarm*], flags=0x0
D/AndroidRuntime( 7536): 
D/AndroidRuntime( 7536): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7536): CheckJNI is OFF
D/AndroidRuntime( 7536): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  841): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  841): Killing 5533:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  841): WIN DEATH: Window{7c79050 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  841): Focus left window: Window{7c79050 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  841): Window went away: Window{7c79050 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  841): Skipping PackageSetting{342ecc75 com.example.hello/10317} due to missing metadata
I/ActivityManager(  841):   Force finishing activity ActivityRecord{144772fd u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  841): Display changed displayId=0
D/DSDPConnection( 1745): Display #0 changed.
W/ActivityManager(  841): Spurious death for ProcessRecord{1a611237 5533:com.test.thalitest/u0a316}, curProc for 5533: null
I/ActivityManager(  841): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  841):   Force finishing activity ActivityRecord{144772fd u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  841): Duplicate finish request for ActivityRecord{144772fd u0 com.test.thalitest/.MainActivity t220 f}
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1833): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1872): [Launcher.java:5203:onStart()]onStart
W/System.err( 3397): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/InputReader(  841): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3397): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3397): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3397): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3397): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3397): 	at android.os.Handler.dispatchMessage(Handler.java:95)
I/ActivityManager(  841): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7563 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1872): [Launcher.java:776:onResume()]onResume
I/art     ( 1936): Explicit concurrent mark sweep GC freed 9979(616KB) AllocSpace objects, 2(48KB) LOS objects, 39% free, 12MB/20MB, paused 5.845ms total 134.812ms
W/System.err( 3397): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3397): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3397): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3397): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3397): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3397): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1872): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1872): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1872): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1872): [Launcher.java:929:onResume()]onResume end
I/Activity( 1872): Activity.onPostResume() called 
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1872): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1872): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1872): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/art     (  841): Explicit concurrent mark sweep GC freed 11928(897KB) AllocSpace objects, 4(99KB) LOS objects, 33% free, 23MB/35MB, paused 4.382ms total 231.335ms
I/art     (  841): WaitForGcToComplete blocked for 128.673ms for cause Explicit
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1370): handleShortcutListChanged...
I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/InputDispatcher(  841): Focus entered window: Window{2097e810 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2299adbe,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  841): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  841): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  841): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  841): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2299adbe,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  841): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 1872): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
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
I/[LGHome]EVENT( 1872): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1370): handleShortcutListChanged...
I/[LGHome]EVENT( 1872): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1872): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 7563): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7563): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/administrator(  841): Handling package changes for user 0
I/art     (  841): Explicit concurrent mark sweep GC freed 2713(130KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.896ms total 197.684ms
I/NotificationService(  841): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  841): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  841): Receieved: android.intent.action.PACKAGE_REMOVED
D/AndroidRuntime( 7536): Shutting down VM
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
I/LGEmail ( 7563): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/TaskPersister(  841): removeObsoleteFile: deleting file=220_task.xml
D/LGEmail ( 7563): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/LCardEmulationManager( 1780): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1780): getDefaultRoute
W/InputMethodManagerService(  841): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  841): Got RemoteException sending setActive(false) notification to pid 5533 uid 10316
I/[LGHome]Launcher.Model( 1872): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  841): Timeline: Activity_windows_visible id: ActivityRecord{1af7cc97 u0 com.lge.launcher2/.Launcher t219} time:1905823
W/IInputConnectionWrapper( 1872): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1872): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1569): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1872): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1872): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/PackageChangeReceiver( 7563): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 1872): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1872): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1872): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  841): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7597 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  841): Killing 6856:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  841): failed to open /acct/uid_10023/pid_6856/cgroup.procs: No such file or directory
W/ResourcesManager(  841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
I/AppUp4:AppBoxCP( 7597): onCreate
W/AppUp4:DB( 7597):  [AppBoxDatabaseHelper] construct
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
E/SQLiteDatabase( 7597): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 7597): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 7597): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 7597): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7597): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7597): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 7597): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 7597): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 7597): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 7597): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 7597): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 7597): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 7597): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7597): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7597): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7597): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 7597): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7597): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7597): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 7597): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 7597): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 7597): FATAL EXCEPTION: main
E/AndroidRuntime( 7597): Process: com.lge.appbox.client, PID: 7597
E/AndroidRuntime( 7597): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7597): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 7597): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 7597): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 7597): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 7597): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7597): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7597): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7597): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 7597): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7597): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7597): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 7597): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 7597): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 7597): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 7597): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7597): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7597): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 7597): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 7597): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 7597): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 7597): 	... 11 more
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1872): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
E/DropBoxManagerService(  841): Can't write: system_app_crash
E/DropBoxManagerService(  841): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  841): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  841): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  841): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  841): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  841): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  841): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  841): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  841): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  841): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  841): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  841): 	... 5 more
I/ActivityManager(  841): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7616 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/Process ( 7597): Sending signal. PID: 7597 SIG: 9
W/ResourceType(  841): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)

```
