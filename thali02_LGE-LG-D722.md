#### Test 573480784751f5c_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/AlertService( 5397): Beginning updateAlertNotification
D/AlertService( 5397): No fired or scheduled alerts
I/NotificationManager( 5397): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5397): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5397): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5397): No events found starting within 1 week.
,D/AndroidRuntime( 5466): 
D/AndroidRuntime( 5466): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5466): CheckJNI is OFF
D/AndroidRuntime( 5466): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  874): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  874): setTaskToReturnTo : TaskRecord{1f01b99 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  874): setTaskToReturnTo : TaskRecord{1f01b99 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  874): AppWindowTokenEx init.. 
D/ContextHelper(  874): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  874): Focus left window: Window{3bc8c38c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5466): Shutting down VM
D/SplitWindow(  874): check instance of lgWin Window{1086f35b u0 Starting com.test.thalitest}
I/ActivityManager(  874): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5486 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1938): Closing mic
I/WindowStateAnimator(  874): Starting window displayed
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/MicrophoneInputStream( 1938): mic_close com.google.android.apps.gsa.speech.audio.u@1cc37b8c
V/AudioRecord( 1938): stop()
D/AudioRecord( 1938): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
I/SystemUI[Framework](  874): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  874): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  874): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  874): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  874): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@14a87290,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  874): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  285): Record stopped OK
V/AudioPolicyManager(  285): stopInput() input 17
V/AudioPolicyService(  285): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  285): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  285): ThreadBase::setParameters() routing=0
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = 15000000
,D/BarTransitions( 1373): draw background and invalidate : color = 19181818
V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
,V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3a02000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
,V/AudioPolicyService(  285): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
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
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3a02000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
V/AudioRecord( 1938): stop()
,V/AudioRecord( 1938): stop()
V/AudioRecord( 1938): stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 17
V/AudioPolicyManager(  285): closeInput(17)
V/AudioFlinger(  285): closeInput() 17
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  874): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): ThreadBase::exit
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3122): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1747): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioSystem( 1938): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): RecordThread 0xb3a02000 exiting
V/AudioFlinger(  285): releasing 16 from 1938 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
,V/AudioFlinger(  285): removeClient_l() pid 1938, calling pid 285
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioSystem( 2710): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1938): Hotword detection finished
I/HotwordRecognitionRnr( 1938): Stopping hotword detection.
,D/ContextHelper( 5486): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5486): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5486): Time to load native libraries: 2 ms (timestamps 3915-3917)
,I/LibraryLoader( 5486): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5486): Binding Chromium to main looper Looper (main, tid 1) {1a8d7047}
,I/LibraryLoader( 5486): Expected native library version number "",actual native library version number ""
D/Finsky  ( 5015): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  874): RTC_WAKEUP set : Alarm{270e72d3 type 0 when 1453985542483 com.android.vending} when 1453985542483
I/chromium( 5486): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5486): Initializing chromium process, singleProcess=true
W/art     ( 5486): Attempt to remove local handle scope entry from IRT, ignoring
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SysUtils( 5486): ApplicationContext is null in ApplicationStatus
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 5486): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5486): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/ActivityManager(  874): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5524 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
E/libEGL  ( 5486): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5486): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5486): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5486): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5486): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5486): Remote Branch: 
I/Adreno-EGL( 5486): Local Patches: 
I/Adreno-EGL( 5486): Reconstruct Branch: 
,I/GservicesProvider( 5524): Gservices pushing to system: true; secure/global: true
,V/AudioPolicyService(  285): registerClient() client 0xb39a14c0, uid 10316
,D/BluetoothManagerService(  874): Message: 20
D/BluetoothManagerService(  874): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28cf5a79:true
D/BluetoothAdapter( 5486): 673630691: getState() :  mService = null. Returning STATE_OFF
I/GoogleHttpClient( 5524): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5524): GMS http client unavailable, use old client
,I/NotificationManager(  874): android: cancelAsUser(2) by android
,W/art     ( 5486): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5486): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5486): CordovaWebView is running on device made by: LGE
,W/art     ( 5486): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5486): Attempt to remove local handle scope entry from IRT, ignoring
D/libc-netbsd( 5015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  874): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 5015): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Activity( 5486): Activity.onPostResume() called 
,I/NotificationManager(  874): android: cancelAsUser(2) by android
D/libc-netbsd( 5015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/OpenGLRenderer( 5486): Render dirty regions requested: true
I/OpenGLRenderer( 5486): Initialized EGL, version 1.4
D/OpenGLRenderer( 5486): Enabling debug mode 0
D/Atlas   ( 5486): Validating map...
,D/SplitWindow(  874): check instance of lgWin Window{2e01d2a3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5486): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  874): Focus entered window: Window{2e01d2a3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  874): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5575 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/InputMethodManagerService(  874): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  874): Displayed com.test.thalitest/.MainActivity: +1s314ms
I/Timeline(  874): Timeline: Activity_windows_visible id: ActivityRecord{2cfa8e5e u0 com.test.thalitest/.MainActivity t222} time:94724
,I/Timeline( 5486): Timeline: Activity_idle id: android.os.BinderProxy@14df1d3 time:94724
I/NotificationManager(  874): android: cancelAsUser(2) by android
,D/libc-netbsd( 5015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5015): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5575): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5575): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/BindingManager( 5486): Cannot call determinedVisibility() - never saw a connection for the pid: 5486
,I/MultiDex( 5575): VM with version 2.1.0 has multidex support
,I/MultiDex( 5575): install
I/MultiDex( 5575): VM has multidex support, MultiDex support library is disabled.
D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 94906212883; DSPS: 3208399; Offset : -3018568394
V/JNIHelp ( 5575): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5575): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5575): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a6596b1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5575): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5575): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5575): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1735): callingUid 10006, callindPid: 1735
,E/MDM     ( 1735): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4094): Restart initialization of location
D/ChimeraCfgMgr( 5575): Reading stored module config
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
D/JsMessageQueue( 5486): Set native->JS mode to OnlineEventsBridgeMode
W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
D/ChimeraCfgMgr( 5575): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 5575): Connecting to CarCallService...
,D/NativeLibraryUtils( 5575): Install completed successfully. count=14 extracted=0
,I/art     ( 5575): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5575): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 5575): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5575): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5575): Creating a new PhoneAdapter instance
W/ActivityManager(  874): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5575): setListener: com.google.android.gms.car.dn@2f5de134
W/ActivityManager(  874): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5575): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5575): Starting CarCallService with initial phone null
I/NotificationManager( 5575): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 5575): Package validated; name: com.android.vending
,I/NotificationManager( 5015): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5015): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/jxcore_app_log( 5486): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622858240
,I/chromium( 5486): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5486): CheckpointMarkThreadRoots callback created = 0xb04efd40
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5486): CheckpointMarkThreadRoots callback created = 0xb04efd10
I/NotificationManager(  874): android: cancelAsUser(2) by android
,D/libc-netbsd( 5015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5015): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5015): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  874): RTC_WAKEUP set : Alarm{379f11a9 type 0 when 1453985544503 com.android.vending} when 1453985544503
,D/Finsky  ( 5015): [1] DailyHygiene.reschedule: Scheduling new run in 288 minutes (failures=4)
,D/DeviceConnectionService( 1735): client connected with version: 8296000
D/Finsky  ( 5015): [599] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  874): android: cancelAsUser(2) by android
D/Finsky  ( 5015): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5015): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5015): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5015): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  874): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager(  874): Killing 5325:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/ActivityManager(  874): Killing 5306:com.android.contacts/u0a18 (adj 15): empty #12
,W/libprocessgroup(  874): failed to open /acct/uid_10069/pid_5325/cgroup.procs: No such file or directory
,W/libprocessgroup(  874): failed to open /acct/uid_10018/pid_5306/cgroup.procs: No such file or directory
I/art     (  874): Explicit concurrent mark sweep GC freed 15907(751KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 1.711ms total 175.457ms
,W/jxcore-log( 5486): Initializing JXcore engine
,W/jxcore-log( 5486): JXcore engine is ready
W/Thread-652( 5624): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6790]" dev="sockfs" ino=6790 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-652( 5624): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-652( 5624): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6048]" dev="sockfs" ino=6048 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-652( 5624): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-652( 5624): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-652( 5624): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[22424]" dev="sockfs" ino=22424 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5486): Starting JXcore engine
,W/jxcore-log( 5486): Platform android
W/jxcore-log( 5486): 
,W/jxcore-log( 5486): Process ARCH arm
W/jxcore-log( 5486): 
I/ActivityManager(  874): Process com.google.android.gm (pid 5204) has died
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5486): JXcore Cordova bridge is ready!
I/jxcore-log( 5486): 
W/jxcore-log( 5486): JXcore engine is started
,I/jxcore-log( 5486): Toggling radios to true
I/jxcore-log( 5486): 
,D/BluetoothManagerService(  874): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  874): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  874): Message: 1
D/BluetoothManagerService(  874): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(673630691)( 1987): onBind()
,D/BluetoothManagerService(  874): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  874): Message: 40
,D/LocationManagerService(  874): getAllProviders()=[passive, gps, network]
D/BluetoothManagerService(  874): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/Ulp_jni (  874): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/WifiServiceImplEx(  874): setWifiEnabled: true pid=5486, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/Ulp_jni (  874): JNI:system_update. Event-4
D/WifiService(  874): setWifiEnabled: true pid=5486, uid=10316
,D/LocationManagerService(  874): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  874): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  874): JNI:system_update. Event-4
D/WifiServiceImplEx(  874): disconnect pid=5486, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  874): reconnect pid=5486, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5486): Radios toggled
I/jxcore-log( 5486): 
I/jxcore-log( 5486): My device name is: LGE-LG-D722
I/jxcore-log( 5486): 
I/LGFTMITEM(  874): [GET_FTM][id=6], offset=12288
E/WifiHW  (  874): Wifi MAC Address = a0:39:f7:70:12:80
E/WifiHW  (  874): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  874): band=b
E/WifiHW  (  874): ": cur_etheraddr=a0:39:f7:70:12:80
,I/bluedroid( 1987): config_hci_snoop_log
D/BluetoothManagerService(  874): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  874): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/SoftapController(  280): Softap fwReload - Ok
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/LGMDMManagerInternal( 1987): Create singleton instance
D/CommandListener(  280): Setting iface cfg
D/CommandListener(  280): Trying to bring down wlan0
D/CommandListener(  280): Clearing all IP addresses on wlan0
E/WifiHW  (  874): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,I/wpa_supplicant( 5647): Successfully initialized wpa_supplicant
,D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothAdapterService(673630691)( 1987): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1987): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1987): Setting state to 11
I/BluetoothAdapterState( 1987): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(673630691)( 1987): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  874): Message: 60
,D/BluetoothAdapterService(673630691)( 1987): processStart()
D/BluetoothManagerService(  874): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  874): Bluetooth State Change Intent: 10 -> 11
D/WifiMonitor(  874): startMonitoring(wlan0) with mConnected = false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/LGBluetoothAPIService( 1803): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BtSettings.ProfileConfig( 1987): Unable to read settings
D/BtSettings.ProfileConfig( 1987): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1987): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1987): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1987): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1987): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1987): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1987): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1987): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1987): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1987): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1987): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/wpa_supplicant( 5647): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 5647): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
I/ActivityManager(  874): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5648 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/WifiServerServiceExt(  874): WIFI_STATE_CHANGED_ACTION [2]
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService,
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,W/BluetoothAdapterService( 1987): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(673630691)( 1987): processStart() - Make Bond State Machine
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:27.844 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/BluetoothBondStateMachine( 1987): make
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/BluetoothAdapterService( 1987): setAdapterService() - set to: null
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
D/LGBluetoothServiceAdapter( 1987): [BTUI] check adapter is available - true : set adapter available.
,I/BluetoothBondStateMachine( 1987): StableState(): Entering Off State
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1987): Unable to read settings
D/BtSettings.ProfileConfig( 1987): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1987): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1987): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1987): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1987): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1987): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1987): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1987): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1987): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1987): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1987): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1987): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
I/ActivityManager(  874): Process com.lge.qremote (pid 5165) has died
,D/UEI.SmartControl( 5185): Service.onUnbind: IControl
,D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
D/UEI.SmartControl( 5185): Service.onDestroy
D/BluetoothHeadset( 1747): Proxy object connected
D/BluetoothHeadset(  874): Proxy object connected
D/HeadsetService( 1987): Received start request. Starting profile...
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/UEI.SmartControl( 5185): Shutdown IRRCPlayer... 
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
I/LGBluetoothHeadsetServiceJni( 1987): classInitNative: succeeds
,D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/LGBluetoothFeatureConfig( 1987): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1987): classInitNative: succeeds
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.pan.PanService
D/HeadsetStateMachine( 1987): make
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/BluetoothHeadset( 1747): Proxy object connected
W/irrc_jni( 5185): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5185): ~IrrcClient ++ 
D/irrcClient( 5185): ~IrrcClient -- 
W/irrc_jni( 5185): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5185): Blaster closed
D/UEI.SmartControl( 5185): Blaster closed
D/UEI.SmartControl( 5185): Shut down QS...
,D/UEI.SmartControl( 5185): Stopped file observer...
D/BluetoothHeadset( 1747): Proxy object connected
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
I/UEI.SmartControl( 5185): QS lib stop result = true
,D/UEI.SmartControl( 5185): QS shutdown complete
D/HeadsetStateMachine( 1987): max_hf_connections = 1
I/bluedroid( 1987): get_profile_interface handsfree
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1987): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
I/bt-btif ( 1987): btif_hf_get_interface
I/bt-btif ( 1987): init
D/bt-btif ( 1987): max_hf_clients = 1
D/bt-btif ( 1987): btif_max_hf_clients = 1
D/bt-btif ( 1987): btif_enable_service: current services:0xa05a5330
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1987): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
,V/ToneGenerator( 1987): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  285): registerClient() client 0xb39a1500, uid 1002
V/AudioPolicyManager(  285): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  285): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  285): getOutput() returns output 2
V/AudioFlinger(  285): registerClient() client 0xb3ac3c70, pid 1987
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  285): thread 0xb5651000 type 0 TID 1291 waking up
V/AudioFlinger(  285): thread 0xb56eb000 type 0 TID 1292 waking up
V/AudioFlinger(  285): thread 0xb5735000 type 0 TID 1294 waking up
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem( 1987): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem(  285): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  285): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1747): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1747): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1987): ioConfigChanged() event 0, ioHandle 6
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 1987): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 1938): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1938): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2710): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2710): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3122): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3122): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  874): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  874): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  285): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  285): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  874): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  874): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1747): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1747): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 2710): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2710): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1938): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1938): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3122): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3122): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 4
V/ToneGenerator( 1987): Create Track: 0xb4909480
V/AudioSystem(  285): ioConfigChanged() event 0, ioHandle 2
V/AudioTrack( 1987): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioSystem(  285): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  874): ioConfigChanged() even,t 0, ioHandle 2
V/AudioSystem(  874): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1938): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1938): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2710): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2710): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1747): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1747): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 1987): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioSystem( 1987): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1987): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 3122): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3122): ioConfigChanged() opening already existing output! 2
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1987): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(673630691)( 1987): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/AudioSystem( 1987): ioConfigChanged() event 0, ioHandle 2
I/AudioFlinger(  285): isAudioPlaybackHookOn() false
V/AudioSystem( 1987): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
D/AudioTrack( 1987): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  285): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  285): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  285): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  285): getOutput() returns output 2
V/AudioSystem( 1987): getLatency() output 2, latency 50
V/AudioSystem( 1987): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1987): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1987): Create normal PCM 0x1 Track
V/LGMDMManager( 1987): Create singleton instance
V/AudioFlinger(  285): createTrack() lSessionId: 22
V/AudioFlinger(  285): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1987): Flags here  0x4 
V/AudioTrack( 1987): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  285): acquiring 22 from 1987, for 1987
V/AudioFlinger(  285):  added new entry for 22
V/ToneGenerator( 1987): ToneGenerator INIT OK, time: 99511
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb5651000
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
D/HeadsetStateMachine( 1987): Enter Disconnected: -2, size: 0
D/BluetoothA2dp(  874): Proxy object connected
D/HeadsetPhoneState( 1987): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1987): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1987): [BTUI] change sampling rate to 8000 when device is disconnected
D/A2dpService( 1987): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 1987): classInitNative: succeeds
V/Avrcp   ( 1987): make
D/Avrcp   ( 1987): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1987): get_profile_interface avrcp
V/AudioFlinger(  285): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1987
I/bt-btif ( 1987): btif_rc_get_interface
I/bt-btif ( 1987): ## init ##
I/LGBluetoothAvrcpServiceJni( 1987): classInitNative: succeeds
I/BluetoothAdapterState( 1987): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
I/LGBluetoothAvrcpAdapter( 1987): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1987): initNative: succeeds
D/audio_hw_primary(  285): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  285): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  285): platform_set_parameters: enter: bt_samplerate=8000
,I/BluetoothAvrcpBrcmAdapterJni( 1987): classInitBrcmNative
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1987): ToneGenerator destructor
V/ToneGenerator( 1987): stopTone
V/ToneGenerator( 1987): Delete Track: 0xb4909480
V/AudioTrack( 1987): ~AudioTrack, releasing session id from 1987 on behalf of 1987
V/AudioFlinger(  285): remove track (4099) and delete from mixer
V/AudioFlinger(  285): releasing 22 from 1987 for 1987
V/AudioPolicyService(  285): AudioCommandThread() adding release output 2
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioPolicyService(  285): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  285): releaseOutput() 2
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioFlinger(  285): PlaybackThread::Track destructor
V/AudioFlinger(  285): removeClient_l() pid 1987, calling pid 285
I/BluetoothAvrcpBrcmAdapterJni( 1987): initBrcmNative
V/AudioService(  874): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  874): No RCC entry present to update
E/RemoteController( 1987): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1987): classInitNative
I/BluetoothA2dpServiceJni( 1987): classInitNative: succeeds
D/A2dpStateMachine( 1987): make
I/bluedroid( 1987): get_profile_interface a2dp
I/bt-btif ( 1987): btif_av_get_src_interface
I/bt-btif ( 1987): init
D/bt-btif ( 1987): btif_enable_service: current services:0xa05a5330
I/LGBluetoothA2dpServiceJni( 1987): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1987): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1987): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1987): [BTUI] init
D/LGBluetoothPowerControlManager( 1987): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  874): Message: 30
,D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
D/A2dpStateMachine( 1987): Enter Disconnected: -2
I/BluetoothHidServiceJni( 1987): classInitNative: succeeds
D/HidService( 1987): Received start request. Starting profile...
I/bluedroid( 1987): get_profile_interface hidhost
I/bt-btif ( 1987): btif_hh_get_interface
I/bt-btif ( 1987): init
D/bt-btif ( 1987): btif_enable_service: current services:0xa05a5330
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
I/BluetoothHealthServiceJni( 1987): classInitNative: succeeds
D/HealthService( 1987): Received start request. Starting profile...
,I/bluedroid( 1987): get_profile_interface health
I/bt-btif ( 1987): btif_hl_get_interface
I/bt-btif ( 1987): init
D/bt-btif ( 1987): Process name (droid.bluetooth)
D/bt-btif ( 1987): btif_hl_soc_thread_init
D/bt-btif ( 1987): create_thread: entered
D/bt-btif ( 1987): create_thread: thread created successfully
D/bt-btif ( 1987): entered btif_hl_select_thread
D/bt-btif ( 1987): btif_hl_select_wakeup_init
I/LGBluetoothHealthServiceJni( 1987): classInitNative: succeeds
D/bt-btif ( 1987): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1987): max_s=55 
D/bt-btif ( 1987): set curr_set = org_set 
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
I/BluetoothPanServiceJni( 1987): classInitNative(L105): succeeds
D/PanService( 1987): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1987): initializeNative(L110): pan
,I/bluedroid( 1987): get_profile_interface pan
D/bt-btif ( 1987): stack_initialized = 0, btpan_cb.enabled:0
I/LGBluetoothPanAdapter( 1987): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
,I/BtGatt.JNI( 1987): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 1987): handleDebugAction() action=null
D/BtGatt.GattService( 1987): Received start request. Starting profile...
D/BtGatt.GattService( 1987): start()
I/bluedroid( 1987): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1987): advertise manager created
I/LGBluetoothGattAdapter( 1987): [BTUI] getInstance : create [LGBluetoothGattAdapter]
,D/LGBluetoothGattAdapter( 1987): setGattService:  set to: null
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
I/LGBluetoothMapAdapter( 1987): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1987): BluetoothMapBinder()
D/BluetoothMapService( 1987): Received start request. Starting profile...
D/BluetoothMapService( 1987): start()
D/BluetoothMapEmailSettingsLoader( 1987): Found 0 applications
,D/BluetoothMapEmailAppObserver( 1987): createReceiver()
D/BluetoothMapEmailAppObserver( 1987): initObservers()
D/BluetoothMapEmailAppObserver( 1987): getEnabledAccountItems()
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
I/BluetoothSAPServiceJni( 1987): classInitNative(L170): succeeds
D/SapService( 1987): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1987): initializeNative(L175): sap
I/bluedroid( 1987): get_profile_interface sap
I/bt-btif ( 1987): btif_sc_get_interface
I/bt-btif ( 1987): init
D/bt-btif ( 1987): btif_enable_service: current services:0xa05a5330
I/LGBluetoothSapAdapter( 1987): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1987): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1987): [BTUI] initSapManager
,D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
D/HeadsetStateMachine( 1987): Proxy object connected
D/LGBluetoothHfpAdapter( 1987): [BTUI] queryPhoneState
,V/BluetoothFTPServiceJni( 1987): classInitNative
I/BluetoothFTPServiceJni( 1987): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
D/BluetoothFTPService( 1987): BluetoothFtpBinder()
D/**BluetoothFTPService( 1987): Received start request. Starting profile...
V/BluetoothFTPService( 1987): FTP-Server Service start
D/BluetoothFTPServiceJni( 1987): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1987): get_profile_interface ftp
I/bt-btif ( 1987): btif_fts_get_interface
I/bt-btif ( 1987): init
D/bt-btif ( 1987): btif_enable_service: current services:0xa05a5330
D/BluetoothFTPServiceJni( 1987): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
D/LGBluetoothFeatureConfig( 1987): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1987): classInitNative
I/BluetoothOPPServiceJni( 1987): classInitNative(L373): succeeds
V/OppService( 1987): Opp initBinder
D/**OppService( 1987): Received start request. Starting profile...
D/OppService( 1987): Starting OppService 
D/LGBluetoothOppAdapter( 1987): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1987): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 1987): send message
,W/ResourcesManager( 5648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5648): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5648): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5648): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5648): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothOppPreference( 1987): Dumping Names:  
D/BluetoothOppPreference( 1987): {}
,D/BluetoothOppPreference( 1987): Dumping Channels:  
D/BluetoothOppPreference( 1987): {}
D/OppService( 1987): Start()
W/BluetoothOPPServiceJni( 1987): initOppNative
D/BluetoothOPPServiceJni( 1987): initOppNative(L383): OPP
I/bluedroid( 1987): get_profile_interface opp
I/bt-btif ( 1987): btif_op_get_interface
D/BluetoothOPPServiceJni( 1987): initOppNative(L411): mOppCallbacksObj 2098430
D/BluetoothOPPServiceJni( 1987): initOppNative(L413): calling OPP init
I/bt-btif ( 1987): btif_opp_init
D/bt-btif ( 1987): btif_enable_service: current services:0xa05a5330
D/BluetoothOPPServiceJni( 1987): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1987): initOppNative(L430): mOppCallbacksObj 2098430
V/OppService( 1987): setOppService(): set to: com.broadcom.bt.service.opp.OppService@36988e21
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1987): Proxy object connected
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
D/LGBluetoothPowerControlManager( 1987): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@8c8c246
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetPhoneState( 1987): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1987): Disconnected process message: 11, size: 0
V/OppService( 1987): pendingUpdate is :  true
D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/LgeBluetoothSimManager( 1747): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1987): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1987): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
V/OppService( 1987): Deleted complete inbound failed shares, number = 0
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1987): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
,V/BluetoothMapService( 1987): Handler(): got msg=1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@25bebcd2 on behalf of 
D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@27ceeb5d on behalf of 
D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppNotification( 1987): update too frequent, put in queue
V/OppService( 1987): pendingUpdate is :  false
E/OppService( 1987): UpdateThread is Completed
D/BluetoothAdapterService( 1987): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1987): new notify threadi!
V/BluetoothOppNotification( 1987): send delay message
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(673630691)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(673630691)( 1987): onProfileServiceStateChange() - All profile services started.
D/BluetoothAdapterState( 1987):, CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1987): enable
,I/bt-btif ( 1987): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1987): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/OppService( 1987): ContentObserver received notification
V/OppService( 1987): ContentObserver received notification
I/bt_hci_bdroid( 1987): init
I/bt_vendor( 1987): init
I/bt_vnd_conf( 1987): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1987): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1987): libbt-hci init returns 0
V/OppService( 1987): pendingUpdate is :  true
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
I/GKI_LINUX( 1987): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1987): btu_task pending for preload complete event
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@c2a91a3 on behalf of 
,V/OppService( 1987): pendingUpdate is :  false
E/OppService( 1987): UpdateThread is Completed
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@2d91dca0 on behalf of 
V/BluetoothOppNotification( 1987): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@1c13e059 on behalf of 
V/BluetoothOppNotification( 1987): outbound: succ-0  fail-0
I/NotificationManager( 1987): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1987): outbound notification was removed.
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@20a7d41e on behalf of 
V/BluetoothOppNotification( 1987): inbound: succ-0  fail-0
,I/NotificationManager( 1987): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1987): inbound notification was removed.
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@374aa4ff on behalf of 
I/bt_userial_vendor( 1987): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 1987): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1987): device fd = 70 open
D/bt_hwcfg( 1987): hw_config_cback opcode:0x0c03
,D/bt_hwcfg( 1987): hw_config_cback state=1
I/IndexDatabaseHelper( 5648): Using schema version: 115
I/IndexDatabaseHelper( 5648): Index is fine
D/bt_hwcfg( 1987): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1987): hw_config_cback state=4
D/bt_hwcfg( 1987): Chipset Name: BCM4334B0
D/bt_hwcfg( 1987): Chipset BCM4334B0
D/bt_hwcfg( 1987): Target name = [BCM4334B0]
,I/bt_hwcfg( 1987): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1987): hw_config_cback state=2
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1987): hw_config_cback state=3
I/bt_hwcfg( 1987): bt vendor lib: set UART baud 4000000
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1987): hw_config_cback state=5
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
V/BluetoothPbapReceiver( 1987): PbapReceiver onReceive 
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
V/BluetoothPbapReceiver( 1987): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1987): ***********state = 11
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/Tethering(  874): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/DSQN    (  874): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/WiFiOffLoadUpdatePriority( 5648): remove : truetruefalse
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/WiFiOffLoadUpdatePriority( 5648): remove2
D/bt_hwcfg( 1987): hw_config_cback state=6
V/WiFiOffLoadSharedPrefsUtils( 5648): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5648): save remove
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/WiFiOffLoadBroadcast( 5648): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5648): S: false, R: true
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
E/wpa_supplicant( 5647): USIM:  scard_init function
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/wpa_supplicant( 5647): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 9
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/ActivityManager(  874): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5699 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/BluetoothPermissionRequest( 5648): onReceive
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/LGBluetoothFeatureConfig( 5648):  get() - isFeatureLoaded : false
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/wpa_supplicant( 5647): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/BluetoothManagerService(  874): Message: 20
D/BluetoothManagerService(  874): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39c8bb08:true
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/wpa_supplicant( 5647): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/WifiStateMachine(  874): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  874): setPowerSaveActivated(false)
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:28.883 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/WifiServerServiceExt(  874): WIFI_STATE_CHANGED_ACTION [3]
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
V/BluetoothSapReceiver( 1987): [BTUI] checkServiceStart
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
E/WifiServerServiceExt(  874): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
I/WifiServerServiceExt(  874): batteryPsActivateMsgHandler : state:0 event:3
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 1987): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
E/WifiConfigStore(  874): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state,=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1987): hw_config_cback state=6
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1987): hw_config_cback state=6
,I/ActivityManager(  874): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5718 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/WifiStateMachine(  874): enableVerboseLogging : level 2
D/WifiStateMachine(  874): Setting OUI to DA-A1-19
D/WifiNative-HAL(  874): Setting external_sim to 1
I/WifiNative-HAL(  874): startHal
E/wifi    (  874): getStaticLongField sWifiHalHandle 0x9abbf8ec
I/WifiHAL (  874): Initializing wifi
I/WifiHAL (  874): Creating socket
I/WifiHAL (  874): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  874): Did set static halHandle = 0xb0687900
D/wifi    (  874): halHandle = 0xb0687900, mVM = 0xb487c280, mCls = 0x8011b6
E/wifi    (  874): getStaticLongField sWifiHalHandle 0x9abbf89c
D/wifi    (  874): array field set
I/WifiNative-HAL(  874): interface[0] = wlan0
I/WifiNative-HAL(  874): interface[1] = p2p0
D/wifi    (  874): setting scan oui 0x9cb55490
D/WifiHAL (  874): Sending mac address OUI
E/WifiHAL (  874): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  874): Setting OUI to DA-A1-19
I/WifiNative-HAL(  874): startHal
D/wifi    (  874): setting scan oui 0x9cb55490
D/WifiHAL (  874): Sending mac address OUI
E/WifiHAL (  874): failed to set scanning mac OUI; result = -95
I/WifiNative-HAL(  874): Waiting for HAL events mWifiHalHandle=-1335330560
D/wifi    (  874): waitForHalEvents called, vm = 0xb487c280, obj = 0x8011b6, env = 0xaaed3ef0
E/wifi    (  874): getStaticLongField sWifiHalHandle 0x985e7b2c
,D/WifiHS20(  874): hidePasspointNotification off =false
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  874): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  874): SCAN_AVAILABLE : 3
D/RttService(  874): SCAN_AVAILABLE : 3
,D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiScanningService(  874): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  874): startHal
D/CommandListener(  280): Setting iface cfg
D/CommandListener(  280): Trying to bring up p2p0
D/RttService(  874): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  874): getting scan capabilities on interface[0] = 0x9cb55490
D/WifiHAL (  874): Creating message to get scan capablities; iface = 24
D/wifi    (  874): failed to get capabilities : -95
E/WifiScanningService(  874): could not get scan capabilities
D/WifiMonitor(  874): startMonitoring(p2p0) with mConnected = true
D/WfdsService( 1803): Supplicant Connection state is changed : true
D/LGWifiP2pService(  874): P2pEnablingState
D/LGWifiP2pService(  874): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): P2p socket connection successful
D/WfdsService( 1803): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/LGWifiP2pService(  874): P2pEnabledState
D/WfdsService( 1803): Set the WFDS Monitor: true
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt(  874): set CMD_ADD_DEFAULT_PROFILE
D/WfdsMonitor( 1803): WfdsMonitorThread create
D/WfdsMonitor( 1803): WFDS Monitor is created and started
D/WfdsService( 1803): WiFi: Supplicant connection re-established
I/WifiServerServiceExt(  874): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 5647): nWIFIDualbandAPConnection: 1
,D/LGWifiP2pService(  874): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  874): before postfix = G3s-1
D/WifiServerServiceExt(  874): postfix byte check : 5
D/LGWifiP2pService(  874): after postfix = G3s-1
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/WifiServerServiceExt(  874): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5647): disconnect_rssi_lvl: -100
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:28.981 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiNative-HAL(  874): p2pGetDeviceAddress
I/WifiServerServiceExt(  874): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5647): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/WifiServerServiceExt(  874): set CMD_UPDATE_DEFAULT_PROFILE
E/CtrlSupplicant( 1803): Access OK "@android:wpa_wlan0"
D/WifiNative-HAL(  874): p2pGetDeviceAddress returning 
E/LGWifiP2pService(  874): p2pGetDeviceAddress NULL retry=1
D/WifiNative-HAL(  874): p2pGetDeviceAddress
D/WifiNative-HAL(  874): p2pGetDeviceAddress returning a2:39:f7:70:12:80
E/CtrlSupplicant( 1803): Succeed to open control connection
E/CtrlSupplicant( 1803): Succeed to open monitor connection
D/LGWifiP2pService(  874): DeviceAddress: a2:39:f7:70:12:80
D/WfdsService( 1803): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,D/WfdsService( 1803): Update P2p Interface State: 3
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/wpa_supplicant( 5647): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WfdsMonitor( 1803): Supplicant connection established
,D/WfdsService( 1803): Connected to the supplicant for wfds
I/wpa_supplicant( 5647): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/bt_hwcfg( 1987): bt vendor lib: set UART baud 115200
W/Settings( 5126): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1987): Settlement delay -- 100 ms
I/bt_hwcfg( 1987): Setting fw settlement delay to 100 
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,D/LGWifiP2pService(  874): sending p2p persistent groups changed broadcast
,I/wpa_supplicant( 5647): wlan0: Associated with c0:ff:d4:d3:aa:48
D/PCSuite ( 5699): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGWifiP2pService(  874): sending p2p connection changed broadcast
D/LGWifiP2pService(  874): InactiveState
D/LGWifiP2pService(  874): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): InactiveState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): P2pEnabledState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): DefaultState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1803): WifiP2pState is changed : true
D/WfdsService( 1803): Receive the WFDS_ENABLE Method
D/WfdsService( 1803): Set the WFDS Monitor: true
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1803): Connected to the supplicant for wfds
D/WfdsJNI ( 1803): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 5647): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
E/WifiServerServiceExt(  874): No p2p device connected
D/WfdsService( 1803): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsJNI ( 1803): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5647): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1803): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5647): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1803): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1803): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1803): selectPreferredScanChannel [6]
D/WfdsService( 1803): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
I/ActivityManager(  874): Killing 4955:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/wpa_supplicant( 5647): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/ResourcesManager( 5718): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/wpa_supplicant( 5647): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,D/LGWifiP2pService(  874): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1803): isConnected: false
D/WfdsService( 1803): GroupInfoAvailable: mGroupInfo is null
W/WfdsService( 1803): DefaultState - msg [9441285] is not handled
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1987): hw_config_cback state=2
,D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1987): hw_config_cback state=7
I/bt_hwcfg( 1987): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1987): Setting local bd addr to F8:95:C7:87:85:54
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5718): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 1987): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1987): hw_config_cback state=8
I/bt_hwcfg( 1987): vendor lib fwcfg completed
I/bt-btif ( 1987): HC preload_cb 0 [0:SUCCESS 1:FAIL]
,I/bt-btu  ( 1987): btu_task received preload complete event
W/libprocessgroup(  874): failed to open /acct/uid_10086/pid_4955/cgroup.procs: No such file or directory
I/        ( 1987): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:29.164 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/        ( 1987): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1987): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1987): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1987): BTE_InitTraceLevels -- TRC_PROTOCOL,0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/ActivityManager(  874): Killing 5185:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
E/bt-btif ( 1987): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 1987): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1987): warning : media task started media_task_refcnt 1 
D/BT_PROF_AUDIO( 1987): created moving average (N=100)
D/BT_PROF_AUDIO( 1987): reset rate average
W/bt-btif ( 1987): overflow 0, enter 0, exit 0
W/bt-smp  ( 1987): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1987): Plain text(LSB ~ MSB) = 46 14 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1987): Encrypted text(LSB ~ MSB) = d5 fc be 1e d0 ee 17 15 18 76 3b 54 f6 ea 44 bd 
W/bt-btm  ( 1987): Stopping oneshot timer
E/bt-btif ( 1987): Calling BTA_HhEnable
E/bt-btif ( 1987): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1987): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1987): Address is:F8:95:C7:87:85:54
V/BluetoothOppNotification( 1987): new notify threadi!
V/BluetoothOppNotification( 1987): send delay message
,V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@254822cc on behalf of 
V/BluetoothOppNotification( 1987): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@10192915 on behalf of 
V/BluetoothOppNotification( 1987): outbound: succ-0  fail-0
I/NotificationManager( 1987): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1987): outbound notification was removed.
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@2079142a on behalf of 
V/BluetoothOppNotification( 1987): inbound: succ-0  fail-0
I/NotificationManager( 1987): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1987): inbound notification was removed.
V/BluetoothOppProvider( 1987): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1987): created cursor android.database.sqlite.SQLiteCursor@3a2e921b on behalf of 
D/AuthorizationBluetoothService( 1735): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterProperties( 1987): Name is: G3s-1
W/libprocessgroup(  874): failed to open /acct/uid_10089/pid_5185/cgroup.procs: No such file or directory
D/LocSvc_java(  874): onReceive
D/BluetoothManagerService(  874): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  874): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1987): Scan Mode:20
D/BluetoothAdapterProperties( 1987): Discoverable Timeout:120
D/UsbSettingsReceiver( 5648): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5648): [AUTORUN] sys.usb.config = ptp_only,adb
E/bt-btif ( 1987): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1987): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
D/UsbSettingsReceiver( 5648): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5648): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/bt-btif ( 1987): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1987): BTA_JvEnable
E/bt-btif ( 1987): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1987): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1987): init_hci_slots(L136): in
D/IOP_DB_BT( 1987): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1987): db_open: db_open : handle 2690316252l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1987): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/IOP_DB_BT( 1987): db_query: result 1
I/        ( 1987): iop_db_open: iop_db_open status 0
E/bt-btif ( 1987): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1987): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1987): bta_pan_co_init
D/bte_conf( 1987): Device ID record 1 : primary
D/bte_conf( 1987):   vendorId            = 00c4
D/bte_conf( 1987):   vendorIdSource      = 0001
D/bte_conf( 1987):   product             = 13a1
D/bte_conf( 1987):   version             = 1000
D/bte_conf( 1987):   clientExecutableURL = 
D/bte_conf( 1987):   serviceDescription  = 
D/bte_conf( 1987):   documentationURL    = 
D/bte_conf( 1987): bte_load_did_conf no section named DID2.
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:29.422 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/bt-btif ( 1987): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1987): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1987): ScanMode =  20
D/BluetoothAdapterProperties( 1987): State =  11
D/BluetoothAdapterProperties( 1987): mDiscoverableTimeout = 120
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterProperties( 1987): Setting state to 12
I/BluetoothAdapterState( 1987): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(673630691)( 1987): updateAdapterState() - Broadcasting state to 1 receivers.
E/bt-btif ( 1987): btif_hf_upstreams_evt: wrong handle = 8240 
I/bt-btif ( 1987): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1987): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 1987): onOpcStateChange()
D/BluetoothManagerService(  874): Message: 60
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothManagerService(  874): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/OppService( 1987): Recieved MESSAGE_OPC_ENABLE
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/BluetoothManagerService(  874): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/LGBluetoothFeatureConfig( 1987): isPrivacyLogsEnabled : true
D/BluetoothHeadset( 1747): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 1987): Entering On State
I/BluetoothAdapterState( 1987): Entering On State from state = 11
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothAdapterService(673630691)( 1987): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(673630691)( 1987): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1987): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1747): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1987): onBluetoothStateChange: up=true
I/bt-btif ( 1987): HAL bt_op_callbacks->ops_state_cb
D/BluetoothHeadset(  874): onBluetoothStateChange: up=true
D/BluetoothOPPServiceJni( 1987): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 1987): onOpsStateChange() :0
I/bt-btif ( 1987): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1987): operation_cmpl_callback(L192):  oper:3 status:0
D/OppService( 1987): Recieved MESSAGE_OPS_ENABLE
I/BluetoothFTPService( 1987): onFtpServerEnabled: /storage
D/BluetoothHeadset( 1747): onBluetoothStateChange: up=true
D/BluetoothPanServiceJni( 1987): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 1987): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothA2dp(  874): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 1987): Scan Mode:21
I/bt-btif ( 1987): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1987): Discoverable Timeout:120
D/LGBluetoothServiceAdapter( 1987): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1987): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1987): [BTUI]         local_name: G3s-1
D/UsbSettingsReceiver( 5648): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifN,ameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:29.432 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/GONS    ( 1747): GONS isTestMode: false Country: 
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothAdapterService(673630691)( 1987): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(673630691)( 1987): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1987): [BTUI] autoConnect() : not allowed
E/BluetoothManagerService(  874): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  874): Bluetooth State Change Intent: 11 -> 12
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/bt_h4   ( 1987): vendor lib postload completed
D/BluetoothManagerService(  874): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  874): Message: 40
D/BluetoothManagerService(  874): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1803): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:29.453 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivit,y=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/CAR.SERVICE( 5575): mConnectedToCar = false, abort
D/LGBluetoothAPIService( 1803): Message: 1
D/LGBluetoothAPIService( 1803): MESSAGE_BOOT_COMPLETED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:29.456 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/WifiServiceExtension(  874): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/BluetoothMapService( 1987): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1987): STATE_ON
I/LGBluetoothAPIService( 1803): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2826c9e3
E/ActivityThread( 5575): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@17cada9c that was originally bound here
E/ActivityThread( 5575): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@17cada9c that was originally bound here
E/ActivityThread( 5575): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5575): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5575): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5575): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5575): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5575): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5575): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5575): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5575): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5575): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5575): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5575): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5575): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5575): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5575): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5575): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5575): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5575): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5575): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/WifiServerServiceExt(  874): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  874): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
V/BluetoothPbapService( 1987): Pbap Service onCreate
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
V/BluetoothPbapService( 1987): Starting PBAP service
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/LGBluetoothPbapAdapter( 1987): [BTUI] getInstance : create
V/BluetoothPbapService( 1987): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1987): state: 12
V/BluetoothMapService( 1987): Handler(): got msg=1
D/BluetoothMapMasInstance( 1987): Map Service startRfcommSocketListener
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
I/WifiServiceExtension(  874): setSecurityType  : 2
D/BluetoothMapMasInstance( 1987): MAS initSocket()
D/BluetoothMapMasInstance( 1987):   masId = 00
D/BluetoothMapMasInstance( 1987):   msgTypes = 0e
D/BluetoothMapMasInstance( 1987):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1987):   SDP string = 000eSMS/MMS
D/LGBluetoothAPIServer( 1987): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1987): [BTUI] onBind()
V/BluetoothPbapService( 1987): Handler(): got msg=1
D/LGBluetoothAPIService( 1803): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,D/LGBluetoothAPIService( 1803): Message: 100
D/LGBluetoothAPIService( 1803): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 1987): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 1987): Pbap Service initSocket
D/BluetoothManagerService(  874): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  874): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/UsbSettingsControl( 5648): [AUTORUN] getUsbConnected() : connected=true
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsReceiver( 5648): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5648): [AUTORUN] onReceive() : activeList=[]
W/BluetoothAdapter( 1987): getBluetoothService() called with no BluetoothManagerCallback
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 5648): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5648): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5648): [AUTORUN] onReceive() : TetherState Changed=wlan0
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:29.51 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/UsbSettingsControl( 5648): [AUTORUN] setTetherStatus() : status=false
D/LGBluetoothServiceAdapter( 1987): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothMapMasInstance( 1987): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1987): Accepting socket connection...
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:29.511 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/BluetoothAdapter( 1987): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
D/LGBluetoothServiceAdapter( 1987): [BTUI] createSocketChannel FD=85 mFd=83
I/bt-btif ( 1987): BTA_JvRfcommStartServer
V/BluetoothPbapService( 1987): Succeed to create listening socket 
V/BluetoothPbapService( 1987): Accepting socket connection...
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/ActivityThread( 5575): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@30d03c07 that was originally bound here
E/ActivityThread( 5575): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@30d03c07 that was originally bound here
E/ActivityThread( 5575): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5575): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5575): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5575): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5575): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5575): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5575): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5575): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5575): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5575): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5575): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5575): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5575): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5575): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5575): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5575): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5575): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5575): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5575): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5575): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5575): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  874): Unbind failed: could not find connection for android.os.BinderProxy@2ed37e9e
W/ContextImpl( 5648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 1987): PbapReceiver onReceive 
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
V/BluetoothPbapReceiver( 1987): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1987): ***********state = 12
D/WiFiOffLoadUpdatePriority( 5648): remove : truetruetrue
D/ConnectivityService(  874): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  874): Got NetworkAgent Messenger
D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  874): NetworkAgent connected
D/WifiExtManager(  874): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@32525a13
D/WifiExtManager(  874): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@2345450
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  874): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine(  874): Start Dhcp Watchdog 1
D/DhcpStateMachine(  874): StoppedState
D/DhcpStateMachine(  874): StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  874): WaitBeforeStartState
D/WifiServerServiceExt(  874): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  874): setSupplicantStateSCANNING
,D/WifiServerServiceExt(  874): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  874): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  874): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  874): setSupplicantStateASSOCIATED
D/WifiServerServiceExt(  874): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  874): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  874): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  874): setSupplicantStateGROUP_HANDSHAKE
I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:29.604 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt(  874): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  874): setSupplicantStateCOMPLETED
,D/LGWifiP2pService(  874): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b6d7180 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b6d7180 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  874): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  874): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  874): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  874): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  874): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  874): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt(  874): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  874): setSupplicantStateCOMPLETED
D/WiFiOffLoadUpdatePriority( 5648): remove1
,V/WiFiOffLoadSharedPrefsUtils( 5648): save remove
D/WiFiOffLoadBroadcast( 5648): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5648): S: false, R: false
D/WiFiOffLoadUpdatePriority( 5648): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5648): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5648): private wpa: "NG700" 300
,D/WifiServiceImplEx(  874): addOrUpdateNetwork pid=5648, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  874):  uid = 1000 SSID "NG700" nid=0
E/WifiConfigStore(  874):  key="NG700"WPA_PSK netId=0 uid=0/1000
E/WifiConfigStore(  874): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5648):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5648): configuration updated: 0
I/WifiServerServiceExt(  874): set CMD_UPDATE_DEFAULT_PROFILE
,D/WiFiOffLoadUpdatePriority( 5648): configuration saved: true
,D/PCSuite ( 5699): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  874): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5759 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 26.621ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.432ms
,D/DhcpStateMachine(  874): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  874): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  874): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.583ms
,I/dhcpcd  ( 5765): version 5.5.6 starting
E/dhcpcd  ( 5765): get_duid: Read-only file system
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
,D/LocalBluetoothProfileManager( 5648): Adding local A2DP profile
D/BluetoothManagerService(  874): Message: 30
I/Netd    (  280): M: Get netlink event, ifname: p2p0 action: 6
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocalBluetoothProfileManager( 5648): Adding local HEADSET profile
,D/BluetoothManagerService(  874): Message: 30
D/BluetoothManagerService(  874): Message: 30
,D/BluetoothManagerService(  874): Message: 30
D/LocalBluetoothProfileManager( 5648): Adding local MAP profile
,D/BluetoothMap( 5648): Create BluetoothMap proxy object
D/BluetoothManagerService(  874): Message: 30
I/dhcpcd  ( 5765): wlan0: rebinding lease of 192.168.1.134
D/BluetoothManagerService(  874): Message: 30
,V/BluetoothPbapService( 1987): Pbap Service onBind
D/LocalBluetoothProfileManager( 5648): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 5648): [BTUI] initUserBindClient
,W/ContextImpl( 5648): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 5648): finishStartingService: stopping service
D/BluetoothA2dp( 5648): Proxy object connected
D/A2dpProfile( 5648): Bluetooth service connected
,D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothHeadset( 5648): Proxy object connected
D/HeadsetProfile( 5648): Bluetooth service connected
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothInputDevice( 5648): Proxy object connected
D/HidProfile( 5648): Bluetooth service connected
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothPan( 5648): BluetoothPAN Proxy object connected
,D/PanProfile( 5648): Bluetooth service connected
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothMap( 5648): Proxy object connected
D/MapProfile( 5648): Bluetooth service connected
D/BluetoothMap( 5648): getConnectedDevices()
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
V/BluetoothMapService( 1987): getConnectedDevices()
D/BluetoothPbap( 5648): Proxy object connected
D/PbapServerProfile( 5648): Bluetooth service connected
D/LGBluetoothUserBindClient( 5648): [BTUI] onServiceConnected
,D/BluetoothPermissionRequest( 5648): onReceive
D/LGBluetoothFeatureConfig( 5648): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5648): [BTUI] FileNotFound: readProperty
V/BluetoothOppReceiver( 1987): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,V/BluetoothOppManager( 1987): restoreApplicationData! falsefalsenullnull
V/BluetoothSapReceiver( 1987): [BTUI] checkServiceStart
,D/LGBluetoothStateChangeReceiver( 1987): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/AuthorizationBluetoothService( 1735): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{382fafe0 type 2 when 101584 com.google.android.gms} when 101584
,D/LGDMClient( 5759): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 5759): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
D/LGDMClient( 5759): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
I/PCSuite ( 5699): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGDMClient( 5759): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/PCSuite ( 5699): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5699): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 5759): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  874): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5800 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  874): Killing 5397:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  874): failed to open /acct/uid_10013/pid_5397/cgroup.procs: No such file or directory
,W/ResourcesManager( 5800): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  874): Message: 20
D/BluetoothManagerService(  874): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9d79af8:true
,D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
I/ActivityManager(  874): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5823 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,V/[BNRBootReceiver]( 5823): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5823): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed,
V/[BNRBootReceiver]( 5823): Boot Receiver Return
,W/MainApplication( 5823): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
I/ActivityManager(  874): Killing 5126:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  874): failed to open /acct/uid_10061/pid_5126/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 5648): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  874): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AudioFlinger(  285): thread 0xb56eb000 type 0 TID 1292 going to sleep
,V/AudioFlinger(  285): thread 0xb5651000 type 0 TID 1291 going to sleep
V/AudioFlinger(  285): thread 0xb5735000 type 0 TID 1294 going to sleep
I/ActivityManager(  874): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5844 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5800): Create singleton instance
,I/AudioManager( 5800): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5844): Quickset Services start...
I/UEI.SmartControl( 5844): Manufacture = LGE
D/UEI.SmartControl( 5844): File observer start...
E/UEI.SmartControl( 5844): IR Port is disabled: false
D/UEI.SmartControl( 5844): Starting file observer...
D/UEI.SmartControl( 5844): Extracting JNI libs...
D/UEI.SmartControl( 5844): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  874): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5862 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 5765): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,D/UEI.SmartControl( 5844): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5844): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5844): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/dhcpcd  ( 5765): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/UEI.SmartControl( 5844): --- Selecting new region: 2
I/UEI.SmartControl( 5844): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5844): Platform has CIR...
D/UEI.SmartControl( 5844): NO CIR support, need to check package...
I/UEI.SmartControl( 5844): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5844): QS Service created
W/ResourcesManager( 5862): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/UEI.SmartControl( 5844): QS start get config
,D/UEI.SmartControl( 5844): Loading JNI Libs...
D/UEI.SmartControl( 5844):  configuring local db...
,D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  874): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  874): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  874): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  874): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  874): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  874): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  874): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  874): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  874): RunningState
D/LGWifiP2pService(  874): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  874): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  874): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  874): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService(  874): ignoring duplicate network state non-change
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  874): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  874): Adding iface wlan0 to network 100
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:31.761 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  874): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  874): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  874): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  874): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  874): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  874): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  874): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 5844):  ---- Has DB8: true
D/UEI.SmartControl( 5844): QS start statue = true Error code = 0
D/UEI.SmartControl( 5844): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 5844): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5844): IRRCDataComm has AudioManager!!!!.
I/ActivityManager(  874): Process com.android.vending (pid 5015) has died
E/WifiStateMachine(  874): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Nat464Xlat(  874): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  874): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  874): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  874): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  874):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): Connected
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  874):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  874): currentScore = 0, newScore = 20
D/ConnectivityService(  874):    accepting network in place of null
D/ConnectivityService(  874): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/WIFI    (  874): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  874):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20(  874): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:31.872 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  874): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:31.875 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/CSLegacyTypeTracker(  874): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/WifiHS20(  874): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  874): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:31.888 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/irrc_jni( 5844): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5844): IrrcClient ++ 
D/irrcClient( 5844): getIrrcService ++ 
D/irrcClient( 5844): getIrrcService -- 
D/irrcClient( 5844): IrrcClient -- 
W/irrc_jni( 5844): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5844): Services init done
,I/UEI.SmartControl( 5844): Device manager: loading config....
D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  874): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  874): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  874): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/Tethering(  874): MasterInitialState.processMessage what=3
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/TelephonyNetworkFactory-1( 1747): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/ConnectivityService(  874): validation of new default Network = false
D/UEI.SmartControl( 5844): QS Service init finished
D/ConnectivityService(  874): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  874): enableDataServiceNotify 
D/DSQN    (  874): start dsqn bin
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
,I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = 1
D/UEI.SmartControl( 5844): Config is loaded...
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): [LWD] Start DNSResolver start to wait
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): [LWD] wait 500ms before dns check
D/UEI.SmartControl( 5844): QS Service version name: 0.1.73
D/UEI.SmartControl( 5844): QS Service version code: 1073
D/UEI.SmartControl( 5844): Service requested: Control
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  874): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/UEI.SmartControl( 5844):  ----- QS SDK is ready!!!
D/ConnectivityService(  874): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/UEI.SmartControl( 5844): Notify AllClients services are ready: 0
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
,I/DSQN    ( 5915): DSQN samuel.seo ver 141203
E/DSQN    ( 5915): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5915): created command queue thread
I/DSQN    ( 5915): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5915): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/art     ( 5862): CheckpointMarkThreadRoots callback created = 0xaaf218e0
I/ActivityManager(  874): Process com.google.android.gms:car (pid 5575) has died
D/UEI.SmartControl( 5844): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5844): Internal service binding...
D/UEI.SmartControl( 5844): -----IControl: 11
,D/UEI.SmartControl( 5844): Caller: com.lge.qremote
I/art     ( 5862): CheckpointMarkThreadRoots callback created = 0xaaf218b0
D/UEI.SmartControl( 5844): ------------ IControl registerCallback...
I/UEI.SmartControl( 5844): Registering callback...
D/UEI.SmartControl( 5844): -----IControl: 19
D/UEI.SmartControl( 5844): Caller: com.lge.qremote
I/UEI.SmartControl( 5844): Registering Services Ready callback...
I/UEI.SmartControl( 5844): Notify client services are ready...
,D/UEI.SmartControl( 5844): -----IControl: 8
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
D/UEI.SmartControl( 5844): Caller: com.lge.qremote
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/Babel_SMS( 5862): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5862): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5862): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5862): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5862): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5862): MmsConfig.loadFromResources
E/Babel_SMS( 5862): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5862): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5862): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5862): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5862): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5862): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5862): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5862): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5862): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5862): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5862): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5862): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5862): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5862): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5862): found sensor: LGE Tilt Detector Sensor, handle=55
,D/SensorManager( 5862): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5862): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5862): found sensor: Motion Accel, handle=46
W/Settings( 5862): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5862): startup - clean
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/Babel   ( 5862): deleted: false for 0
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  874): propertyValue:false
I/ActivityManager(  874): Process com.google.android.gms (pid 4094) has died
,V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
V/NetworkPolicy(  874): [LG_RESTRICTED] checkMobilePolicy_type()
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): [LWD] DNSResolver start dns
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/AudioCapabilities( 5862): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5862): Unsupported mime audio/adpcm
,V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/NotificationManager( 1938): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
W/AudioCapabilities( 5862): Unsupported mime audio/g726
D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
W/AudioCapabilities( 5862): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5862): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5862): Unsupported mime video/mjpg
V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
I/PCSuite ( 5699): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5699): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 5648): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5648): MCCMNC not supported: null
I/PCSuite ( 5699): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5699): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/AudioManager( 5800): getMode name:com.lge.qremote
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  874): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): Checking http://clients3.google.com/generate_204 on "NG700"
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  276): 
I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/VideoCapabilities( 5862): Unsupported mime video/theora
,D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5915): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5915): restart monitoring
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5915): dsqn report finish
D/DSQN    (  874): DSQM DsqnNotification wlan0  1
D/DSQN    (  874): start to monitor internet connection
I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 13:52:32.631 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/AudioCapabilities( 5862): Unsupported mime audio/evrc
,W/AudioCapabilities( 5862): Unsupported mime audio/qcelp
W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5862): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5862): Unsupported mime audio/qcelp
W/AudioCapabilities( 5862): Unsupported mime audio/evrc
,W/VideoCapabilities( 5862): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 5862): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5862): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5862): onServiceConnected
W/Babel   ( 5862): Attempted to change video mute state without an active call.
I/art     ( 1735): Explicit concurrent mark sweep GC freed 29375(1766KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 13MB/22MB, paused 1.873ms total 120.992ms
,I/NotificationManager( 5862): com.google.android.talk: cancel(10436) by com.google.android.talk
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jan 2016 12:52:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453985552806], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453985552633]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): [LWD] wifi && isInternetCheckAvailable is false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  874): Validated
D/ConnectivityService(  874): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  874): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  874):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  874):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  874): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/WifiDataContinuityService(  874): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  874): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  874): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1747): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  874): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  874):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/art     (  874): Explicit concurrent mark sweep GC freed 65771(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 7.807ms total 240.907ms
I/AudioManager( 5800): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/AudioManager( 5800): getMode name:com.lge.qremote
V/WifiInternetCheck(  874): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  874): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  874): onReceive
D/LocSvc_java(  874): got connectivity action
D/LocSvc_java(  874): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  874): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  874): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  874): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  874): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  874): Sending msg: 5 arg1:0 arg2:1
D/LocSvc_java(  874): NTP server returned: 1453985552272 (Thu Jan 28 13:52:32 GMT+01:00 2016) reference: 103883 certainty: 30 system time offset: -2687
,I/ActivityManager(  874): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5944 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider(  874): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  874): Sending msg: 10 arg1:0 arg2:1
,D/AlarmManagerService(  874): Setting time of day to sec=1453985554
W/AlarmManagerService(  874): Unable to set rtc to 1453985554: Invalid argument
,D/NetworkChangeNotifierAutoDetect( 1938): Network connectivity changed, type is: 2
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.TIME_SET
D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:52:34
,I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2688): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2688): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2688): 2 : Fixed theme : optimus
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,D/WeatherReflect( 2688): 2 : Map key string is -2
,I/ActivityManager(  874): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5973 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/CalendarProvider2( 5362): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5362): Scheduling check of next Alarm
D/lim     ( 2688): 2 : time = 13:52
,W/ActivityManager(  874): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
I/WeatherReflect( 2688): Model Name : LG-D722
D/WeatherTheme( 2688): 2 : exactly same view!
D/WeatherTheme( 2688): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:52:34
,I/[LGHome]LGDateChangeReceiver( 1879): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=28 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 1879): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 28
,I/[LGHome]LGCalendarIcon( 1879): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 28
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  874): Start proc com.google.android.gms for service com.google.android.gms/.chromesync.sync.SyncService: pid=5990 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  874): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6005 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5973): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5973): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5973): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  874): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 6005): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6005): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6005): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
E/GpsLocationProvider(  874): No APN found to select.
,W/ResourcesManager( 5990): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5990): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeGpsConstants(  874): Can't find 'ext_gps.conf'!!
,D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/LGEmail ( 5973): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/System.out(  874): propertyValue:false
,I/AppConfig( 6005): Total System Memory = 906309632
,I/GalleryUtils( 6005): Application Heap = 96 MB
D/LGEmail ( 5973): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/MusicStore( 5944): Database version: 120
,I/AppConfig( 6005): App Tier : NOT_DEF
,D/SystemHelper( 6005): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  874): Killing 5362:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/LgeGpsLocationProvider(  874): NTP server: europe.pool.ntp.org
D/LgeGpsLocationProvider(  874): NTP server returned: 1453985555551 (Thu Jan 28 13:52:35 GMT+01:00 2016) reference: 107202 certainty: 84 system time offset: 0
I/NotificationManager(  874): android: cancelAsUser(-1597574061) by android
,I/MultiDex( 5990): VM with version 2.1.0 has multidex support
I/MultiDex( 5990): install
I/MultiDex( 5990): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  874): failed to open /acct/uid_10014/pid_5362/cgroup.procs: No such file or directory
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5944): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/jxcore-log( 5486): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5486): 
,I/ActivityManager(  874): Process com.lge.lgdmsclient (pid 5759) has died
,V/JNIHelp ( 5990): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5944): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5944): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ActivityThread( 5990): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5990): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@374aa4ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5990): Installed default security provider GmsCore_OpenSSL
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  874): propertyValue:false
I/ActivityManager(  874): Process com.lge.settings.easy (pid 5718) has died
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  874): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  874): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/NotificationManager( 5990): com.google.android.gms: cancel(10436) by com.google.android.gms
I/System.out(  874): propertyValue:false
I/NotificationManager( 5990): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WifiInternetCheck(  874): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  874): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6049 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/ResourcesManager( 5944): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5944): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/NativeLibraryUtils( 5990): Install completed successfully. count=14 extracted=0
,V/JNIHelp ( 5944): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationManager(  874): android: cancelAsUser(-1816247584) by android
D/ALBootInit( 6049): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6049): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6049): [setNextAlert] start
,D/Alarms  ( 6049): [setNextAlert] (1)
,D/Alarms  ( 6049):  minTime  = 0
D/Alarms  ( 6049):  -- OK multi -- 0
E/jeny.kim( 6049): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6049): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/ActivityThread( 5944): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5944): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21a5add0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5944): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5944): GMSCore installation verified
I/ActivityManager(  874): Process com.lge.bnr (pid 5823) has died
,E/ActivityThread( 5990): Failed to find provider info for com.android.contacts.metadata
I/ConfigStore( 5944): Config Database version: 1
,I/CommonUtil( 6049): BUILD Operator: OPEN
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 38231, reason: UserStart, SyncResult: databaseError: true stats []
D/Alarms  ( 6049): broadcastToWidgetProvider : false
D/SyncManager(  874): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 140427, reason: UserStart
I/NotificationManager(  874): android: cancelAsUser(716319171) by android
D/Alarms  ( 6049): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  874): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6049): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6049): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2857d99d
V/DigitalAppWidgetProvider( 6049): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2857d99d
,D/QuickCoverProvider( 6049): onReceiver
,I/ActivityManager(  874): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6079 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Auth.Api.Credentials( 5990): [CredentialSyncAdapter] Unknown sync event.
,D/CalendarApplication( 6079): CalendarApplication.onCreate()
,I/NotificationManager(  874): android: cancelAsUser(-591465577) by android
D/PreferenceKeysParser( 6079): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6079): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@310a4fc8, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2631861, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@31a51f86, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1a8d7047, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@458a074, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2857d99d, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1e23ae12, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2826c9e3, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@32994fe0, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@28dd7299, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1a8a995e, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@472213f, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@20738a0c, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@16899f55, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@17e2ed6a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@19f1925b, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@33d53af8, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1d91dbd1, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1cba7636, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2f2cf937, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@19f0ea4, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1e07640d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@38afbfc2, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@14df1d3, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2a107110, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2dd33409, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@24be160e, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2c7bd82f, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@ff38e3c, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3e7207c5, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1c49851a, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3df7c84b, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@16895228, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@22705b41, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3aead8e6, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@bf89e27, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@123568d4, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2ea66a7d, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2afb9d72, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2f46f5c3, lg_preferences_alerts_vibratetype=com.a,ndroid.calendar.adaptation.PreferenceKey$KeyData@17ea3e40, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@33343
,D/GeneralPreferenceUtils( 6079): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6079): [init]
,I/Config  ( 6079): LGCalendar ver.4.40.17
I/Config  ( 6079): start check model
I/Config  ( 6079): start check native_ca
I/Config  ( 6079): Config Operator=OPEN, Country=EU
D/Config  ( 6079): [setDefaultValuesToPref]
D/Config  ( 6079): [parseProfiles]
I/MediaRouter( 5944): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/ProfilesParser( 6079): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6079): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6079): [updateProfiletoCountryInfo]
D/GeneralPreference( 6079): [checkAndMigrateOldPreference]
V/MusicLeanback( 5944): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/AgendaWidgetManager( 6079): [updateWidgets] 
,I/NetworkMonitor( 5944): type=WIFI subType= reason=null isConnected=true
I/InitNotificationRingtoneService( 6079): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6079): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/art     ( 5990): CheckpointMarkThreadRoots callback created = 0xaaf26910
,I/AlertUtils( 6079): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/NetworkMonitor( 5944): type=WIFI subType= reason=null isConnected=true
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,D/UEI.SmartControl( 5844): Internal timer expired: 1
,D/eas_req ( 5973): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/art     ( 5990): CheckpointMarkThreadRoots callback created = 0xaaf268f0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/GHttpClientFactory( 5944): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/MonthWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,W/HolidayIntentService( 6079): onHandleIntent
D/HolidayDataLoader( 6079): readJsonAsset : holiday.json
,I/ActivityManager(  874): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6106 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/GoogleURLConnFactory( 5944): Using platform SSLCertificateSocketFactory
I/art     (  311): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 22.378ms
I/art     (  311): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.138ms
,I/art     (  874): Explicit concurrent mark sweep GC freed 32644(1620KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 8.436ms total 206.146ms
D/CalendarTypeController( 6079): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
D/WeekWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [onReceive]
D/CalendarWidgetProvider( 6079): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6079): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.040ms
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
D/WeatherAncestor( 2688): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:52:37
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
,D/Weather_cast( 2688): 2 : set auto-update time : 1/28 16:52
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:52:37
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/jxcore-log( 5486): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5486): 
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/HubEmail( 5973): JNI_OnLoad()
I/HubEmail( 5973): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5973): registerNatives()
I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/HubEmail( 5973): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5973): registerNativeMethods()
I/HubEmail( 5973): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5973): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/AlertUtils( 6079): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6079): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
E/HolidayIntentService( 6079): onHandleIntent:holiday data empty
,I/ActivityManager(  874): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6126 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  874): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
I/AlertUtils( 6079): set default noti to content://media/internal/audio/media/38
W/Settings( 5973): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/InitNotificationRingtoneService( 6079): End InitializeAlertRingtoneService.onHandleIntent
,D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/NotificationManager(  874): android: cancelAsUser(-1816247584) by android
,I/jxcore-log( 5486): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5486): 
,I/jxcore-log( 5486): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5486): 
,I/NotificationManager(  874): android: cancelAsUser(-591465577) by android
,D/ConnectivityService(  874): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  874): dumpNetworkRequest
D/ConnectivityService(  874):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  874):     Requests:
D/ConnectivityService(  874):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  874):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  874):     Lingered:
D/ConnectivityService(  874): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  874): apparently satisfied.  currentScore=60
D/ConnectivityService(  874): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5990): CM callback handler got msg 524290
D/TimeService( 6126): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453985557388
D/        ( 6126): TimeServiceNative: User Time to be set is 1453985557389
D/QC-time-services( 6126): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6126): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6126): Lib:time_genoff_operation: pargs->ts_val = 1453985557389
D/QC-time-services( 6126): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  343): Daemon: Connection accepted:time_genoff
D/QC-time-services(  343): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453985557389
D/QC-time-services(  343): Daemon:genoff_opr: Base = 2, val = 1453985557389, operation = 0
D/QC-time-services(  343): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/10/70 16:54:9
D/QC-time-services(  343): Daemon:Value read from RTC seconds = 13884849000
D/QC-time-services(  343): Daemon:new time 1453985557389 
D/QC-time-services(  343): Daemon: delta 1440100708389 genoff 1440100708389 
D/QC-time-services(  343): Daemon:genoff_persistent_update: Writing genoff = 1440100708389 to memory
D/QC-time-services(  343): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  343): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  343): Updating the TOD offset
D/QC-time-services(  343): Daemon:genoff_persistent_update: Writing genoff = 1440100708389 to memory
D/QC-time-services(  343): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  343): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  343): Daemon:Update to modem bit set
D/QC-time-services(  343): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  343): Daemon: Base = 2, Value being sent to MODEM = 1124135908389
E/QC-time-services( 6126): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  343): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  343): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager(  874): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6149 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/LGDMClient( 6106): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6106): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6106): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/jxcore-log( 5486): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5486): 
,W/ContextImpl( 6106): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6106): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6106): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/jxcore-log( 5486): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5486): 
,I/ActivityManager(  874): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6171 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/jxcore-log( 5486): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5486): 
I/NotificationManager(  874): android: cancelAsUser(-1597574061) by android
I/NotificationManager( 5944): com.google.android.music: cancel(1061) by com.google.android.music
I/jxcore-log( 5486): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5486): 
,D/LGDMClient( 6106): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  874): Killing 5862:com.google.android.talk/u0a61 (adj 15): empty #11
I/LGDMClient( 6106): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ResourcesManager( 6149): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  874): failed to open /acct/uid_10061/pid_5862/cgroup.procs: No such file or directory
,W/ContextImpl( 6106): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/CheckinService( 5990): Checkin interval check for package: unspecified last checkin: 1453981606038 min interval config: 0 actual interval: 3951657
E/LGDMClient( 6106): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6106): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6106): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6106): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LGDMClient( 6106): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  874): Killing 5648:com.android.settings/1000 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6171): onCreate
,W/AppUp4:DB( 6171):  [AppBoxDatabaseHelper] construct
W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_5648/cgroup.procs: No such file or directory
I/AppUp4:DB( 6171):  setFingerPrint start
I/AppUp4:DB( 6171):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6171):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6171):  SDK version = 0
I/AppUp4:DB( 6171):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6171): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6171): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6171): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6171): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6171): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6171): onReceive
I/AppUp4:CustModeStarterReceiver( 6171): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6171): Context : android.app.ReceiverRestrictedContext@458a074
D/AppUp4:CustFacade( 6171): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6171): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6171): begin check event
I/AppUp4:CustModeStarterReceiver( 6171): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6171): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6171): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6171): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6171): handleAsyncCustNotification do not startCustService
I/ActivityManager(  874): Process com.lge.qremote (pid 5800) has died
,D/UEI.SmartControl( 5844): Service.onUnbind: IControl
D/UEI.SmartControl( 5844): Service.onDestroy
D/UEI.SmartControl( 5844): Shutdown IRRCPlayer... 
W/irrc_jni( 5844): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5844): ~IrrcClient ++ 
D/irrcClient( 5844): ~IrrcClient -- 
W/irrc_jni( 5844): IRRCPlayer_nativeFinalize -- 
,D/UEI.SmartControl( 5844): Blaster closed
D/UEI.SmartControl( 5844): Blaster closed
D/UEI.SmartControl( 5844): Shut down QS...
D/UEI.SmartControl( 5844): Stopped file observer...
I/UEI.SmartControl( 5844): QS lib stop result = true
D/UEI.SmartControl( 5844): QS shutdown complete
I/LgeMiscReceiver( 3122): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3122): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3122): networkInfo.isConnected() = true
D/PhoneState( 3122): setPdpRejectCasuse : false
,I/ActivityManager(  874): Killing 5699:com.lge.sync/1000 (adj 15): empty #11
I/ActivityManager(  874): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6209 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_5699/cgroup.procs: No such file or directory
,I/art     ( 5524): Explicit concurrent mark sweep GC freed 1991(89KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 610us total 65.677ms
,W/DriveInitializer( 5990): Awaiting to be initialized
,W/DriveInitializer( 5990): Background init thread started
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5990): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,D/PhoneMonitor( 6209): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6209): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6209): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  874): Killing 5844:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/DriveInitializer( 5990): Background init thread ended
,V/DownloadManager( 3147): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneMonitor( 6209): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6209): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6209): [parse] Load xml
,V/TelephonyAutoProfiling( 6209): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6209): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6209): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5990): Checkin interval check for package: unspecified last checkin: 1453981606038 min interval config: 0 actual interval: 3952926
,W/libprocessgroup(  874): failed to open /acct/uid_10089/pid_5844/cgroup.procs: No such file or directory
I/NotificationManager(  874): android: cancelAsUser(2145784878) by android
V/DownloadManager( 3147): DownloadService onCreate
,I/DownloadManager( 3147): in removeSpuriousFiles
I/NotificationManager( 6149): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
I/NotificationManager( 3147): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3147): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3147): created cursor android.database.sqlite.SQLiteCursor@2afb9d72 on behalf of 3147
I/DownloadManager( 3147): in trimDatabase
V/DownloadManager( 3147): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3147): created cursor android.database.sqlite.SQLiteCursor@17ea3e40 on behalf of 3147
I/ActivityManager(  874): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6258 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3147): DownloadService onStartCommand
I/NotificationManager(  874): android: cancelAsUser(-1548111331) by android
V/DownloadManager( 3147): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3147): created cursor android.database.sqlite.SQLiteCursor@30e21ebe on behalf of 3147
,I/CheckinService( 5990): Disabling old GoogleServicesFramework version
I/ActivityManager(  874): Killing 6049:com.lge.clock/u0a10 (adj 15): empty #11
,W/libprocessgroup(  874): failed to open /acct/uid_10010/pid_6049/cgroup.procs: No such file or directory
,I/NotificationManager(  874): android: cancelAsUser(353845882) by android
I/NotificationManager( 5990): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  874): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6281 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  874): RTC_WAKEUP set : Alarm{d32dbd9 type 0 when 1453985559192 com.android.vending} when 1453985559192
V/DownloadManager( 3147): DownloadService onDestroy
D/DrmBroadcastReceiver( 6258): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6258): 1  network is available. Sync DRM Time with NTP
,D/WeatherAncestor( 2688): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:52:39
,D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherAncestor( 2688): connectivity changed - connection : true
,D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:52:39
V/DrmService( 6258): Service onCreate
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/DrmService( 6258): Received new request = 2
I/DrmSntpClient( 6258): Start Sync process
D/DrmSntpClient( 6258): Server : 0
,D/libc-netbsd( 6258): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6258): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6258): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6258): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  280): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  874): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6301 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  874): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
I/CheckinService( 5990): Checking schedule, now: 1453985559400 next: 1453981635951
I/CheckinService( 5990): active receiver: enabled
,D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinService( 5990): Preparing to send checkin request
I/EventLogService( 5990): Accumulating logs since 1453985514467
I/NotificationManager(  874): android: cancelAsUser(353845882) by android
,I/art     ( 5990): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5990): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/ResourcesManager( 6301): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/Finsky  ( 6281): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/CheckinRequestBuilder( 5990): Checkin reason type: 8 attempt count: 1
,V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{174a1c02 type 2 when 111591 com.android.providers.calendar} when 111591
,E/ActivityThread( 5990): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 6301): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6301): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6301): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6301): MmsConfig.loadFromDatabase
D/Finsky  ( 6281): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6281): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6281): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6281): com.android.vending: cancel(-1050172287) by com.android.vending
,E/Babel_SMS( 6301): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6301): MmsConfig.loadFromResources
E/Babel_SMS( 6301): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6301): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/art     (  874): Explicit concurrent mark sweep GC freed 27522(1291KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.510ms total 160.431ms
,D/Ads     ( 6281): Skipping gmscore version check
D/SensorManager( 6301): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6301): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6301): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6301): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6301): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6301): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6301): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6301): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6301): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6301): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6301): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6301): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6301): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6301): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6301): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6301): found sensor: Motion Accel, handle=46
,D/Finsky  ( 6281): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6281): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3147): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,I/art     ( 5990): WaitForGcToComplete blocked for 7.938ms for cause DisableMovingGc
V/DownloadManager( 3147): created cursor android.database.sqlite.SQLiteCursor@1754fe6c on behalf of 6281
D/Finsky  ( 6281): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Settings( 6301): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6301): startup - clean
,I/art     ( 6301): CheckpointMarkThreadRoots callback created = 0xb042d890
I/Babel   ( 6301): deleted: false for 0
D/Finsky  ( 6281): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     ( 6301): CheckpointMarkThreadRoots callback created = 0xb042d870
,W/AudioCapabilities( 6301): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6301): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6301): Unsupported mime audio/g726
W/AudioCapabilities( 6301): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6301): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6301): Unsupported mime video/mjpg
I/ActivityManager(  874): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6355 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/VideoCapabilities( 6301): Unsupported mime video/theora
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6258): propertyValue:false
,W/AudioCapabilities( 6301): Unsupported mime audio/evrc
W/AudioCapabilities( 6301): Unsupported mime audio/qcelp
W/VideoCapabilities( 6301): Unrecognized profile 2130706433 for video/avc
I/LGDrmClient( 6258): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  290): eDRM_SetDRMTime +++
W/AudioCapabilities( 6301): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6301): Unsupported mime audio/qcelp
W/AudioCapabilities( 6301): Unsupported mime audio/evrc
I/LGDRM   (  290): [DRM] SET TIME : YR=2016, MON=1, DAY=28
I/LGDRM   (  290): [DRM] SET TIME : HR=12, MIN=52, SEC=39
V/ILGDrmService(  290): eDRM_SetDRMTime ---
I/DrmSntpClient( 6258): Synched
D/DrmService( 6258): Completed !! request = 2
D/DrmService( 6258): Request count = 0
V/DrmService( 6258): Service onDestroy
I/ActivityManager(  874): Killing 5944:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/VideoCapabilities( 6301): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6301): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6301): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6301): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6301): Unrecognized profile 2130706433 for video/avc
W/art     ( 6301): Suspending all threads took: 10.090ms
,W/libprocessgroup(  874): failed to open /acct/uid_10081/pid_5944/cgroup.procs: No such file or directory
W/VideoCapabilities( 6301): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6301): onServiceConnected
,W/Babel   ( 6301): Attempted to change video mute state without an active call.
D/libc-netbsd( 6301): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6301): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6301): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6301): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
I/NotificationManager( 6301): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6301): propertyValue:false
,I/ActivityManager(  874): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6378 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/Babel   ( 6301): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  874): Killing 5973:com.lge.email/u0a21 (adj 15): empty #11
,D/Finsky  ( 6281): [765] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6281): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/libprocessgroup(  874): failed to open /acct/uid_10021/pid_5973/cgroup.procs: No such file or directory
,I/ActivityManager(  874): Killing 6079:com.android.calendar/u0a13 (adj 15): empty #11
W/ResourcesManager( 6378): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6378): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6355): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6355): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6355): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6355): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6355):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6355):   adb logcat -s GAv4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6355): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/MultiDex( 6378): VM with version 2.1.0 has multidex support
I/MultiDex( 6378): install
I/MultiDex( 6378): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  874): failed to open /acct/uid_10013/pid_6079/cgroup.procs: No such file or directory
W/GAv4    ( 6355): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
V/JNIHelp ( 6378): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/GAv4    ( 6355): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6355): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/ActivityThread( 6378): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6378): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a6596b1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6378): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6378): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6378): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6378): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6378): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6378): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  285): Instantiating CDM.
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  285): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  285): L1 library not specified. Falling Back to L3
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=3980352808
I/WebViewFactory( 6355): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6355): Time to load native libraries: 3 ms (timestamps 3253-3256)
I/LibraryLoader( 6355): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6355): Binding Chromium to main looper Looper (main, tid 1) {36988e21}
I/LibraryLoader( 6355): Expected native library version number "",actual native library version number ""
I/chromium( 6355): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6355): Initializing chromium process, singleProcess=true
W/art     ( 6355): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6355): ApplicationContext is null in ApplicationStatus
,W/chromium( 6355): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6355): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6355): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6355): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6355): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6355): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6355): Remote Branch: 
I/Adreno-EGL( 6355): Local Patches: 
I/Adreno-EGL( 6355): Reconstruct Branch: 
,I/art     ( 6378): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,V/AudioPolicyService(  285): registerClient() client 0xb39a1540, uid 10079
W/AudioManagerAndroid( 6355): Requires BLUETOOTH permission
,I/WVCdm   (  285): CdmEngine::OpenSession
I/art     ( 6378): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,I/ActivityManager(  874): Process com.android.gallery3d (pid 6005) has died
,I/NSApplication( 6355): Starting up...
,I/ActivityManager(  874): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6440 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
I/ActivityManager(  874): Killing 6126:com.qualcomm.timeservice/1000 (adj 15): empty #11
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_6126/cgroup.procs: No such file or directory
,I/iu.SyncManager( 5990): SYNC; picasa accounts
,D/NetworkLogImpl( 5990): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5990): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 5990): num queued entries: 0
I/iu.UploadsManager( 5990): num updated entries: 0
I/iu.SyncManager( 5990): NEXT; no task
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,D/WearableService( 1735): callingUid 10006, callindPid: 1735
D/LocationInitializer( 5990): Restart initialization of location
,E/MDM     ( 1735): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  874): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6480 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  311): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 24.628ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.001ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 20.896ms
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCM     ( 1735): GCM config loaded
I/ActivityManager(  874): Process com.lge.appbox.client (pid 6171) has died
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,W/ResourcesManager( 6480): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/IcingInternalCorpora( 5990): getNumBytesRead when not calculated.
,D/BluetoothManagerService(  874): Message: 20
D/BluetoothManagerService(  874): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ef34ec5:true
,D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
D/BluetoothAdapterService(673630691)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d91dbd1
I/ActivityManager(  874): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6509 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  874): tsOffsetIs: Apps: 114907005532; DSPS: 3863784; Offset : -3018542773
,I/DigitalAppWidgetProvider( 6509): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2688): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:52:43
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
,D/Weather_cast( 2688): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:52:43
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  874): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6527 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  874): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6527): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/WVCdm   (  285): CdmEngine::CloseSession
,D/CalendarProvider2( 6527): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@26bea1ba
I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=4229312689
I/ActivityManager(  874): Process com.android.vending (pid 6281) has died
D/CalendarProvider2( 6527): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6527): Created com.android.providers.calendar.CalendarAlarmManager@1a8d7047(com.android.providers.calendar.CalendarProvider2@26bea1ba)
,D/CalendarProviderBroadcastReceiver( 6527): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6527): [IntentService] WakeLock acquire, start IntentSerivce
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/CalendarProvider2( 6527): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6527): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 6527): [getOrCreateCalendarAlarmManager]
E/MDM     ( 1735): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5990): Restart initialization of location
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ContextImpl( 3402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,D/CalendarProvider2( 6527): [IntentService] Release Lock
,D/CalendarProvider2( 6527): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  874): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6561 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6480): Create singleton instance
,I/AudioManager( 6480): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6561): Quickset Services start...
,I/UEI.SmartControl( 6561): Manufacture = LGE
D/UEI.SmartControl( 6561): File observer start...
E/UEI.SmartControl( 6561): IR Port is disabled: false
,D/UEI.SmartControl( 6561): Starting file observer...
,D/UEI.SmartControl( 6561): Extracting JNI libs...
D/UEI.SmartControl( 6561): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6561): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6561): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6561): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6561): --- Selecting new region: 2
,I/UEI.SmartControl( 6561): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6561): Platform has CIR...
D/UEI.SmartControl( 6561): NO CIR support, need to check package...
I/UEI.SmartControl( 6561): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6561): QS Service created
I/MusicWidget( 2613): mDelayedStopHandler : unbind
,I/ActivityManager(  874): Process com.google.android.apps.magazines (pid 6355) has died
,E/UEI.SmartControl( 6561): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicBrowser( 2710): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2710): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2710): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2710): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2710): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2710): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  874):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@38afbfc2com.lge.music.MediaPlaybackService$6@14df1d3
D/MusicBrowser( 2710): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
D/UEI.SmartControl( 6561): Loading JNI Libs...
D/UEI.SmartControl( 6561):  configuring local db...
,I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@32994fe0
I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2710): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2710): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2710): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2710): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2710): reset
V/MediaPlayer[Native]( 2710): setListener
V/MediaPlayer[Native]( 2710): disconnect
V/MediaPlayer[Native]( 2710): destructor
V/AudioFlinger(  285): releasing 19 from 2710 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
,V/MediaPlayer[Native]( 2710): disconnect
D/MusicBrowser( 2710): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2710): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2710): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2710): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2710): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2710): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2710): [SmartShareManagerClient] unregisterListener: 705720592
W/SmartShareClient( 2710): [SmartShareManagerClient] unregisterListener invalid listener: 705720592
I/SmartShareClient( 2710): [SmartShareManagerClient] terminate service: 2710/MediaPlaybackService/832905094
E/HomeCloudIF( 2710): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2710): [SmartShareManagerClient] unbindService context:android.app.Application@2dd33409
V/CloudHub( 2710): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2710): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2710): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2710): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2710): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/CloudHub( 2710): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29975
,D/UEI.SmartControl( 6561):  ---- Has DB8: true
,D/UEI.SmartControl( 6561): QS start statue = true Error code = 0
D/UEI.SmartControl( 6561): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6561): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6561): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6561): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6561): IrrcClient ++ 
D/irrcClient( 6561): getIrrcService ++ 
D/irrcClient( 6561): getIrrcService -- 
D/irrcClient( 6561): IrrcClient -- 
W/irrc_jni( 6561): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6561): Services init done
D/UEI.SmartControl( 6561): QS Service init finished
D/UEI.SmartControl( 6561): QS Service version name: 0.1.73
D/UEI.SmartControl( 6561): QS Service version code: 1073
D/UEI.SmartControl( 6561): Service requested: Control
I/UEI.SmartControl( 6561): Device manager: loading config....
D/UEI.SmartControl( 6561): Config is loaded...
,D/UEI.SmartControl( 6561):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6561): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6561): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6561): Internal service binding...
D/UEI.SmartControl( 6561): -----IControl: 11
D/UEI.SmartControl( 6561): Caller: com.lge.qremote
D/UEI.SmartControl( 6561): ------------ IControl registerCallback...
I/UEI.SmartControl( 6561): Registering callback...
D/UEI.SmartControl( 6561): -----IControl: 19
,D/UEI.SmartControl( 6561): Caller: com.lge.qremote
I/UEI.SmartControl( 6561): Registering Services Ready callback...
I/UEI.SmartControl( 6561): Notify client services are ready...
D/UEI.SmartControl( 6561): -----IControl: 8
D/UEI.SmartControl( 6561): Caller: com.lge.qremote
I/AudioManager( 6480): getMode name:com.lge.qremote
,I/ActivityManager(  874): Killing 6209:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/ActivityManager(  874): Killing 6106:com.lge.lgdmsclient/1000 (adj 15): empty #12
,I/art     (  874): Explicit concurrent mark sweep GC freed 20708(923KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.561ms total 158.895ms
,W/libprocessgroup(  874): failed to open /acct/uid_10038/pid_6209/cgroup.procs: No such file or directory
,W/libprocessgroup(  874): failed to open /acct/uid_1000/pid_6106/cgroup.procs: No such file or directory
I/AudioManager( 6480): getMode name:com.lge.qremote
I/AudioManager( 6480): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): L3 Terminate.
,I/dex2oat ( 6597): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6597): dex2oat took 124.153ms (threads: 4)
,I/Adreno-EGL( 6378): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6378): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6378): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6378): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6378): Remote Branch: 
I/Adreno-EGL( 6378): Local Patches: 
I/Adreno-EGL( 6378): Reconstruct Branch: 
,I/Adreno-EGL( 6378): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6378): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6378): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6378): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6378): Remote Branch: 
I/Adreno-EGL( 6378): Local Patches: 
I/Adreno-EGL( 6378): Reconstruct Branch: 
,I/Adreno-EGL( 6378): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6378): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6378): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6378): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6378): Remote Branch: 
I/Adreno-EGL( 6378): Local Patches: 
I/Adreno-EGL( 6378): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/CheckinRequestBuilder( 5990): Classify the device as Phone.
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
I/art     ( 5524): Explicit concurrent mark sweep GC freed 2874(114KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 815us total 27.753ms
,D/libc-netbsd( 5990): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5990): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5990): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5990): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5990): propertyValue:false
,D/libc-netbsd( 5990): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5990): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5990): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5990): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5990): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5990): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5990): Sending checkin request (9840 bytes)
,I/jxcore-log( 5486): Test app app.js loaded
I/jxcore-log( 5486): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5486): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 5486): BLE advertisement is supported
I/jxcore-log( 5486): 
I/chromium( 5486): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 5990): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5990): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5990): Classify the device as Phone.
,I/CheckinTask( 5990): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5990): Checking schedule, now: 1453985568017 next: 1454512817011
I/CheckinService( 5990): active receiver: disabled
,D/CheckinService( 5990): Recording last checkin time for package unspecified as 1453985568051
,I/ActivityManager(  874): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6622 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6622): Register our PhoneStateListener
,V/SetupWizard( 6622): Connected to Gservices successfully
,I/ActivityManager(  874): Killing 6258:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/PhoneMonitor( 6622): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6622): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6622): [parse] Load xml
W/libprocessgroup(  874): failed to open /acct/uid_10051/pid_6258/cgroup.procs: No such file or directory
,V/TelephonyAutoProfiling( 6622): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6622): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6622): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  874): Killing 6149:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  874): Killing 6440:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  874): failed to open /acct/uid_10086/pid_6149/cgroup.procs: No such file or directory
,W/libprocessgroup(  874): failed to open /acct/uid_10048/pid_6440/cgroup.procs: No such file or directory
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  874): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/ActivityManager(  874): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6664 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  874): Handling package changes for user 0
I/NotificationManager( 6301): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6301): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6301): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6301): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6664): onCreate
W/AppUp4:DB( 6664):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6664):  setFingerPrint start
,I/AppUp4:DB( 6664):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6664):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6664):  SDK version = 0
I/AppUp4:DB( 6664):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6664): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6664): onReceive
I/AppUp4:CustModeStarterReceiver( 6664): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6664): Context : android.app.ReceiverRestrictedContext@2631861
D/AppUp4:CustFacade( 6664): isCustomizationCompleted : false
W/System  ( 6301): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6301): Installed default security provider GmsCore_OpenSSL
D/AppUp4:CustFacade( 6664): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6664): begin check event
I/AppUp4:CustModeStarterReceiver( 6664): Event For Nothing, skip.
I/ActivityManager(  874): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6686 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 6561): Internal timer expired: 1
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,W/ResourcesManager(  874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6686): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6686): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6686): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationService(  874): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  874): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  874): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  874): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  874): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  874): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@27176053
W/ResourceType(  874): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  874): Process com.android.providers.calendar (pid 6527) has died
,I/AppConfig( 6686): Total System Memory = 906309632
,I/GalleryUtils( 6686): Application Heap = 96 MB
,I/AppConfig( 6686): App Tier : NOT_DEF
,D/SystemHelper( 6686): region [EU], country [EU], operator [OPEN], sub-operator []
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  874): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6712 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  874): Process com.lge.clock (pid 6509) has died
,D/LocationProviderProxy(  874): applying state to connected service
,W/ResourcesManager( 6712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/AudioFlinger(  285): 2710 died, releasing its sessions
V/AudioFlinger(  285):  pid 1747 @ 0
V/AudioFlinger(  285):  pid 3122 @ 1
V/AudioFlinger(  285):  pid 3122 @ 2
,I/SystemConfig( 6712): BUILD Country: EU
,I/SystemConfig( 6712): BUILD Operator: OPEN
,I/ActivityManager(  874): Process com.lge.music (pid 2710) has died
,I/ActivityManager(  874): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6731 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6712): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6712): existFile = false
I/SystemConfig( 6712): canReadFile = false
I/SystemConfig( 6712): systemFeature RCS result false
D/SystemConfig( 6712): refreshRcsSupport() :false
,I/LockScreenSettings( 6731): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6731): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6731): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6731): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6731): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6731): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  874): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6751 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UpdateIcingCorporaServi( 1938): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  874): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6776 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6622:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1938): UpdateCorporaTask done [took 102 ms] updated apps [took 102 ms] 
,W/libprocessgroup(  874): failed to open /acct/uid_10038/pid_6622/cgroup.procs: No such file or directory
,D/Finsky  ( 6776): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6776): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6776): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6776): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6776): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3147): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3147): created cursor android.database.sqlite.SQLiteCursor@83d6c35 on behalf of 6776
D/Ads     ( 6776): Skipping gmscore version check
D/Finsky  ( 6776): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6776): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  874): Killing 6561:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6480): android.os.DeadObjectException
,W/System.err( 6480): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6480): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6480): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6480): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6480): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6480): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6480): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6480): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6480): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6480): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6480): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6480): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6480): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6480): android.os.DeadObjectException
W/System.err( 6480): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6480): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6480): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6480): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6480): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6480): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6480): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6480): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6480): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6480): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6480): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6480): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6480): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  874): failed to open /acct/uid_10089/pid_6561/cgroup.procs: No such file or directory
W/ActivityManager(  874): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/Finsky  ( 6776): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5990): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  874): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6833 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 5990): Null package name or gms related package.  Ignoreing.
,I/art     (  311): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 324us total 39.155ms
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/art     (  311): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 23.604ms
D/Finsky  ( 6776): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 25.999ms
D/UEI.SmartControl( 6833): Quickset Services start...
,I/UEI.SmartControl( 6833): Manufacture = LGE
D/UEI.SmartControl( 6833): File observer start...
,I/Icing   ( 5990): Storage manager: low false usage 1.71MB avail 2.36GB capacity 4.06GB
,E/UEI.SmartControl( 6833): IR Port is disabled: false
D/UEI.SmartControl( 6833): Starting file observer...
D/UEI.SmartControl( 6833): Extracting JNI libs...
D/UEI.SmartControl( 6833): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6833): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6833): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6833): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/art     (  874): Explicit concurrent mark sweep GC freed 27004(1376KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.840ms total 153.528ms
I/UEI.SmartControl( 6833): --- Selecting new region: 2
,I/UEI.SmartControl( 6833): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6833): Platform has CIR...
D/UEI.SmartControl( 6833): NO CIR support, need to check package...
I/UEI.SmartControl( 6833): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6833): QS Service created
E/UEI.SmartControl( 6833): QS start get config
,D/UEI.SmartControl( 6833): Loading JNI Libs...
,D/UEI.SmartControl( 6833):  configuring local db...
I/Icing   ( 5990): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 6833):  ---- Has DB8: true
,D/UEI.SmartControl( 6833): QS start statue = true Error code = 0
D/UEI.SmartControl( 6833): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6833): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6833): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6833): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6833): IrrcClient ++ 
,D/irrcClient( 6833): getIrrcService ++ 
D/irrcClient( 6833): getIrrcService -- 
D/irrcClient( 6833): IrrcClient -- 
W/irrc_jni( 6833): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6833): Services init done
I/UEI.SmartControl( 6833): Device manager: loading config....
D/UEI.SmartControl( 6833): QS Service init finished
,D/UEI.SmartControl( 6833): QS Service version name: 0.1.73
D/UEI.SmartControl( 6833): QS Service version code: 1073
D/UEI.SmartControl( 6833): Service requested: Control
D/UEI.SmartControl( 6833): Config is loaded...
I/Icing   ( 5990): Internal init done: storage state 0
,I/Icing   ( 5990): Post-init done
,I/Icing   ( 5990): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 6833):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6833): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6833): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6833): Internal service binding...
,D/UEI.SmartControl( 6833): -----IControl: 11
,D/UEI.SmartControl( 6833): Caller: com.lge.qremote
D/UEI.SmartControl( 6833): ------------ IControl registerCallback...
I/UEI.SmartControl( 6833): Registering callback...
D/UEI.SmartControl( 6833): -----IControl: 19
D/UEI.SmartControl( 6833): Caller: com.lge.qremote
I/UEI.SmartControl( 6833): Registering Services Ready callback...
I/UEI.SmartControl( 6833): Notify client services are ready...
,D/UEI.SmartControl( 6833): -----IControl: 8
D/UEI.SmartControl( 6833): Caller: com.lge.qremote
,I/AudioManager( 6480): getMode name:com.lge.qremote
I/AudioManager( 6480): getMode name:com.lge.qremote
,I/AudioManager( 6480): getMode name:com.lge.qremote
W/ProcessCpuTracker(  874): Skipping unknown process pid 6848
,W/ProcessCpuTracker(  874): Skipping unknown process pid 6849
W/ProcessCpuTracker(  874): Skipping unknown process pid 6867
W/ProcessCpuTracker(  874): Skipping unknown process pid 6870
W/ProcessCpuTracker(  874): Skipping unknown process pid 6883
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 5990): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5990): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5990): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  874): Killing 6664:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  874): failed to open /acct/uid_10011/pid_6664/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  874): Killing 6301:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  874): failed to open /acct/uid_10061/pid_6301/cgroup.procs: No such file or directory
,D/charger_monitor(  482): init target 500000
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/WifiController(  874): battery changed pluggedType: 2
,W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,D/UEI.SmartControl( 6833): Internal timer expired: 1
,I/CheckinService( 5990): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerManagerServiceEx(  874): acquireWakeLockInternal: lock=202836864, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=874
,D/WeatherService( 2688): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:53:0
D/WeatherService( 2688): 2 : TimeTick Intent And Screen On
D/WeatherService( 2688): 2 : SDK version : 21
W/ActivityManager(  874): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2688): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2688): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2688): 2 : Fixed theme : optimus
D/WeatherReflect( 2688): 2 : Map key string is -2
,D/lim     ( 2688): 2 : time = 13:53
I/WeatherReflect( 2688): Model Name : LG-D722
D/WeatherTheme( 2688): 2 : Different view - status_min_formatted : 52 != 53
D/WeatherTheme( 2688): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2688): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2688): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/Weather4x2_optimus( 2688): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2688): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2688): forecast size is 0
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2688): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2688): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2688): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2688): url is : null
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2688): 2 : update view, appWidgetId: 2
D/WeatherService( 2688): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:53:0
,D/PowerManagerServiceEx(  874): releaseWakeLockInternal: lock=202836864 [*alarm*], flags=0x0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 134908834691; DSPS: 4519204; Offset : -3018546464
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{3a5c5b7f type 2 when 136486 com.google.android.gms} when 136486
,I/PerfProfileCollectorService( 5990): Turn off PerfProfile Collection
,W/InstanceID/Rpc( 5990): Found 10006
,D/PerfProfileCollectorService( 5990): removeStateFiles() called
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{374e6449 type 2 when 136783 android} when 136783
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/VacuumService( 1735): Vacuum at: now=1453985585263 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/PowerManagerService(  874): ALS enabled for SRE
D/PowerManagerServiceEx(  874): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30578 ms ago)
,D/qdlights(  874): set_light_backlight: 253
,D/qdlights(  874): set_light_backlight: 250
,D/qdlights(  874): set_light_backlight: 246
,D/qdlights(  874): set_light_backlight: 243
,D/qdlights(  874): set_light_backlight: 240
,D/qdlights(  874): set_light_backlight: 236
,D/qdlights(  874): set_light_backlight: 233
,D/qdlights(  874): set_light_backlight: 230
,D/qdlights(  874): set_light_backlight: 226
,D/qdlights(  874): set_light_backlight: 223
,D/qdlights(  874): set_light_backlight: 220
,D/qdlights(  874): set_light_backlight: 216
,D/qdlights(  874): set_light_backlight: 213
,D/qdlights(  874): set_light_backlight: 210
,D/qdlights(  874): set_light_backlight: 206
,D/qdlights(  874): set_light_backlight: 203
,D/qdlights(  874): set_light_backlight: 200
,D/qdlights(  874): set_light_backlight: 196
,D/qdlights(  874): set_light_backlight: 193
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  874): set_light_backlight: 190
,D/qdlights(  874): set_light_backlight: 186
,D/qdlights(  874): set_light_backlight: 183
,D/qdlights(  874): set_light_backlight: 180
,D/qdlights(  874): set_light_backlight: 176
,D/qdlights(  874): set_light_backlight: 173
,D/qdlights(  874): set_light_backlight: 170
,D/qdlights(  874): set_light_backlight: 166
,D/qdlights(  874): set_light_backlight: 163
,D/qdlights(  874): set_light_backlight: 160
,D/qdlights(  874): set_light_backlight: 156
,D/qdlights(  874): set_light_backlight: 153
,D/qdlights(  874): set_light_backlight: 150
,D/qdlights(  874): set_light_backlight: 146
,D/qdlights(  874): set_light_backlight: 143
,D/qdlights(  874): set_light_backlight: 140
,D/qdlights(  874): set_light_backlight: 136
,D/qdlights(  874): set_light_backlight: 133
,D/qdlights(  874): set_light_backlight: 130
,D/qdlights(  874): set_light_backlight: 126
,D/qdlights(  874): set_light_backlight: 123
,D/qdlights(  874): set_light_backlight: 120
,D/qdlights(  874): set_light_backlight: 116
,D/qdlights(  874): set_light_backlight: 113
,D/qdlights(  874): set_light_backlight: 110
,D/qdlights(  874): set_light_backlight: 106
,D/qdlights(  874): set_light_backlight: 103
,D/qdlights(  874): set_light_backlight: 100
,D/qdlights(  874): set_light_backlight: 96
,D/qdlights(  874): set_light_backlight: 93
,D/qdlights(  874): set_light_backlight: 90
,D/qdlights(  874): set_light_backlight: 86
,D/qdlights(  874): set_light_backlight: 83
,D/qdlights(  874): set_light_backlight: 80
,D/qdlights(  874): set_light_backlight: 76
,D/qdlights(  874): set_light_backlight: 73
,D/qdlights(  874): set_light_backlight: 70
,D/qdlights(  874): set_light_backlight: 66
,D/qdlights(  874): set_light_backlight: 63
,D/qdlights(  874): set_light_backlight: 60
,D/qdlights(  874): set_light_backlight: 56
,D/qdlights(  874): set_light_backlight: 53
,D/qdlights(  874): set_light_backlight: 50
,D/qdlights(  874): set_light_backlight: 46
,D/qdlights(  874): set_light_backlight: 43
,D/qdlights(  874): set_light_backlight: 40
,D/qdlights(  874): set_light_backlight: 36
,D/qdlights(  874): set_light_backlight: 33
,D/qdlights(  874): set_light_backlight: 30
,D/qdlights(  874): set_light_backlight: 26
,D/qdlights(  874): set_light_backlight: 23
,D/qdlights(  874): set_light_backlight: 20
,D/qdlights(  874): set_light_backlight: 16
,D/qdlights(  874): set_light_backlight: 13
,D/qdlights(  874): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 154909807964; DSPS: 5174596; Offset : -3018548479
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  874): ALS enabled for SRE
D/PowerManagerServiceEx(  874): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (37571 ms ago)
,I/PowerManagerService(  874): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  874): ALS enabled for SRE
D/PowerManagerServiceEx(  874): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (37583 ms ago)
W/ContextImpl(  874): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  874): Sleeping (uid 1000)...
D/LPWGController(  874): [updateScreenState] screen on = false
D/LPWGController(  874): disable proximity sensor
,D/LPWGController(  874): enable proximity sensor
I/SensorManager(  874): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@abbab7c] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  874): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  874): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  874): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  874): activate: handle is 48, enable
V/sensors_hal_Ctx(  874): activate sensors is 1400000000000
D/sensors_hal_Thresh(  874): enable: handle=48
I/sensors_hal_SAM(  874): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  874): waitForResponse: timeout=1000
V/sensors_hal_SAM(  874): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  874): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  874): enable: Received response: 0
D/PowerManagerServiceEx(  874): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37626 ms ago)
I/Adreno-EGL(  874): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  874): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  874): Build Date: 03/02/15 Mon
I/Adreno-EGL(  874): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  874): Remote Branch: 
I/Adreno-EGL(  874): Local Patches: 
I/Adreno-EGL(  874): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (152 us)
,I/Sensors (  411): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  874): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  874): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  874): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  874): processInd: handle 48, count=1
V/sensors_hal_Thresh(  874): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  874): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  874): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  874): poll: count: 256
I/sensors_hal_Ctx(  874): poll: released wakelock sensor_ind
D/sensors_hal_Util(  874): waitForResponse: timeout=0
D/LPWGController(  874): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  874): current mode = 1  value = 1 1
I/LPWGController(  874): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  874): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  874): set_light_backlight: 0
,I/SensorManager(  874): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  874): activate: handle is 46, disable
V/sensors_hal_Ctx(  874): activate sensors is 1000000000000
D/sensors_hal_LP2(  874): enable: handle=46
D/sensors_hal_LP2(  874): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  874): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  874): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  874): Display changed displayId=0
,V/sensors_hal_SAM(  874): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  874): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1747): Display #0 changed.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
D/SurfaceControl(  874): Excessive delay in setPowerMode(): 238ms
I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  874): Got set_interactive hint
,D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
D/WifiServerServiceExt(  874): sendKtScanInterval  mRtspPlay : false
,D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 874
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  285): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
,I/WifiServerServiceExt(  874): set CMD_KT_SCAN_INTERVAL
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/GpsLocationProvider(  874): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
I/Sensors (  411): sns_pwr.c(301):releasing wakelock
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1803): lockStatus = 0
D/LEDService( 1803): stopPatternFlashing()
D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1803): RESTART MSG
,D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 3
D/NfcService( 1788): Discovery configuration equal, not updating.
D/SplitWindow(  874): check instance of lgWin Window{b2f768b u0 SearchPanel}
,D/Ulp_jni (  874): JNI:system_update. Event-0
D/InputDispatcher(  874): Window went away: Window{1931ddc3 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:53:27
,D/WeatherService( 2688): 2 : ACTION screen on
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:53:27
D/AppCleanupService( 3906): android.intent.action.SCREEN_ON
,W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): ACTION_SCREEN_ON
V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 874
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
D/WifiController(  874): CMD_SCREEN_OFF 
D/WifiController(  874): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  874): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:53:27
,D/WeatherService( 2688): 2 : ACTION screen off
D/WeatherService( 2688): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:53:27
D/AppCleanupService( 3906): android.intent.action.SCREEN_OFF
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppCleanupService( 3906): AppUsageStatsSaveTask
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  874): ACTION_SCREEN_OFF
,E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
,D/NfcService( 1788): newParams.techmask= mTechMask: 0
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 1
E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{33d60368 type 2 when 163537 com.android.systemui} when 163537
,D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1747): getCallState : 0
,D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{11995381 type 2 when 166788 android} when 166788
,E/ActivityThread( 5990): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  874): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 140427, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  874): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 231437, reason: UserStart
I/NotificationManager(  874): android: cancelAsUser(716319171) by android
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 174910776395; DSPS: 5829988; Offset : -3018556141
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): init target 500000
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  874): battery changed pluggedType: 2
,V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{dd0c4b2 type 2 when 187522 android} when 187522
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{117e2c03 type 2 when 189639 com.google.android.gms} when 189639
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 8335 seconds from now (1453985638286)
,D/GetConfigurationSnapshotOperation( 1735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  874): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 49957(3MB) AllocSpace objects, 46(736KB) LOS objects, 40% free, 13MB/22MB, paused 2.813ms total 167.157ms
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1735): propertyValue:false
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  874): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  874): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/LocationManagerService(  874): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  874): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  874): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  874): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  874): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 194911513263; DSPS: 6485372; Offset : -3018552633
,D/PowerManagerServiceEx(  874): acquireWakeLockInternal: lock=202836864, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=874
,V/AlarmManager(  874): ELAPSED_WAKEUP set : Alarm{2cec20b0 type 2 when 196816 android} when 196816
D/PowerManagerServiceEx(  874): releaseWakeLockInternal: lock=202836864 [*alarm*], flags=0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 214912187630; DSPS: 7140754; Offset : -3018548741
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 234912875904; DSPS: 7796137; Offset : -3018562631
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  874): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 254913696000; DSPS: 8451524; Offset : -3018566354
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 274914369118; DSPS: 9106906; Offset : -3018564701
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 294915104787; DSPS: 9762290; Offset : -3018561323
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  874): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  874): battery changed pluggedType: 2
I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  874): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  874): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  874): tsOffsetIs: Apps: 314915858529; DSPS: 10417674; Offset : -3018540394
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  874): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  874): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  874): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5486): --= Surplus to requirements =--
I/jxcore-log( 5486): 
I/jxcore-log( 5486): ****TEST TOOK:  ms ****
I/jxcore-log( 5486): 
I/jxcore-log( 5486): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5486): 
,D/AndroidRuntime( 7048): 
D/AndroidRuntime( 7048): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7048): CheckJNI is OFF
,D/AndroidRuntime( 7048): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  874): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  874): Killing 5486:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  874): Skipping PackageSetting{35e6d966 com.example.hello/10317} due to missing metadata
,I/WindowState(  874): WIN DEATH: Window{2e01d2a3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  874): Focus left window: Window{2e01d2a3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  874): Window went away: Window{2e01d2a3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  874):   Force finishing activity ActivityRecord{2cfa8e5e u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  874): Display changed displayId=0
D/DSDPConnection( 1747): Display #0 changed.
,W/ActivityManager(  874): Spurious death for ProcessRecord{a9fbb29 5486:com.test.thalitest/u0a316}, curProc for 5486: null
,I/ActivityManager(  874): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
,W/System.err( 3402): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/InputReader(  874): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3402): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3402): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,W/System.err( 3402): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3402): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3402): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3402): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3402): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3402): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
,I/ActivityManager(  874): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7079 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     ( 1938): Explicit concurrent mark sweep GC freed 8390(504KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 29.777ms total 130.749ms
I/[LGHome]EVENT( 1879): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
,D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
,I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1373): handleShortcutListChanged...
,I/SystemUI[Framework](  874): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  874): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  874): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  874): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  874): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@14a87290,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  874): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  874): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/PhoneWindowManagerEx(  874): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  874): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  874): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  874): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@14a87290,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  874): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
D/InputDispatcher(  874): Focus entered window: Window{3bc8c38c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
I/art     (  874): Explicit concurrent mark sweep GC freed 59169(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 11.986ms total 266.253ms
,I/art     (  874): WaitForGcToComplete blocked for 233.276ms for cause Explicit
D/KeyguardModel( 1373): handleShortcutListChanged...
,W/ResourcesManager( 7079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/administrator(  874): Handling package changes for user 0
,I/art     (  874): Explicit concurrent mark sweep GC freed 3990(225KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 5.067ms total 193.361ms
,I/LGEmail ( 7079): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7079): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
D/AndroidRuntime( 7048): Shutting down VM
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
W/InputMethodManagerService(  874): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  874): Got RemoteException sending setActive(false) notification to pid 5486 uid 10316
,I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  874): Timeline: Activity_windows_visible id: ActivityRecord{20d9eb7e u0 com.lge.launcher2/.Launcher t221} time:324065
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/NotificationService(  874): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  874): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  874): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  874): removeObsoleteFile: deleting file=222_task.xml
W/IInputConnectionWrapper( 1879): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1607): Unable to connect to the editor to retrieve text... will retry later
I/PackageChangeReceiver( 7079): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/ActivityManager(  874): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7106 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  874): Killing 6686:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1879): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/libprocessgroup(  874): failed to open /acct/uid_10023/pid_6686/cgroup.procs: No such file or directory
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/AppUp4:AppBoxCP( 7106): onCreate
W/AppUp4:DB( 7106):  [AppBoxDatabaseHelper] construct
,E/SQLiteDatabase( 7106): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 7106): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 7106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 7106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7106): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 7106): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 7106): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 7106): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 7106): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 7106): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 7106): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 7106): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7106): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7106): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7106): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 7106): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7106): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7106): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 7106): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 7106): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 7106): FATAL EXCEPTION: main
E/AndroidRuntime( 7106): Process: com.lge.appbox.client, PID: 7106
E/AndroidRuntime( 7106): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7106): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 7106): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 7106): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 7106): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 7106): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7106): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7106): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7106): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 7106): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7106): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7106): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 7106): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 7106): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 7106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 7106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7106): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7106): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 7106): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 7106): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 7106): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 7106): 	... 11 more
,E/DropBoxManagerService(  874): Can't write: system_app_crash
E/DropBoxManagerService(  874): java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  874): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  874): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  874): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  874): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  874): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  874): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  874): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  874): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  874): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  874): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  874): 	... 5 more
I/ActivityManager(  874): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7126 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a

```
