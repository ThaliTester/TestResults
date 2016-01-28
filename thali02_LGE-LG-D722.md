#### Test 573480789efee08_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{145d6fc0 type 0 when 1453981572608 com.android.vending} when 1453981572608
--------- beginning of main
D/Finsky  ( 5163): [620] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5163): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 5333): 
D/AndroidRuntime( 5333): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5333): CheckJNI is OFF
D/AndroidRuntime( 5333): Calling main entry com.android.commands.am.Am
I/ActivityManager(  838): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  838): setTaskToReturnTo : TaskRecord{125544f9 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  838): setTaskToReturnTo : TaskRecord{125544f9 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  838): AppWindowTokenEx init.. 
D/ContextHelper(  838): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  838): Focus left window: Window{19359aa5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5333): Shutting down VM
D/SplitWindow(  838): check instance of lgWin Window{127bd1bb u0 Starting com.test.thalitest}
I/ActivityManager(  838): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5360 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  838): Starting window displayed
I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3b48def6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
I/HotwordDetector( 1937): Closing mic
D/BarTransitions( 1373): draw background and invalidate : color = 11000000
D/BarTransitions( 1373): draw background and invalidate : color = 13121212
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@2ace4555
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 17
,V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb39dc000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
,V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  283): setParameters(): io 17, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb39dc000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
,V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 17
V/AudioPolicyManager(  283): closeInput(17)
V/AudioFlinger(  283): closeInput() 17
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): ThreadBase::exit
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2111): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): RecordThread 0xb39dc000 exiting
V/AudioSystem(  838): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioSystem( 3106): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): releasing 16 from 1937 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 1937, calling pid 283
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1937): Hotword detection finished
D/ContextHelper( 5360): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5360): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5360): Time to load native libraries: 2 ms (timestamps 3260-3262)
I/LibraryLoader( 5360): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5360): Binding Chromium to main looper Looper (main, tid 1) {20b70ec7}
,I/LibraryLoader( 5360): Expected native library version number "",actual native library version number ""
I/chromium( 5360): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{e34bd33 type 0 when 1453981574039 com.android.vending} when 1453981574039
D/Finsky  ( 5163): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/BrowserStartupController( 5360): Initializing chromium process, singleProcess=true
W/art     ( 5360): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5360): ApplicationContext is null in ApplicationStatus
W/chromium( 5360): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 5360): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/libEGL  ( 5360): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5360): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5360): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5360): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5360): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5360): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5360): Remote Branch: 
I/Adreno-EGL( 5360): Local Patches: 
I/Adreno-EGL( 5360): Reconstruct Branch: 
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{ef59fc6 type 2 when 93466 com.google.android.gms} when 93466
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 33234(2MB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 13MB/22MB, paused 2.007ms total 106.880ms
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/NotificationManager(  838): android: cancelAsUser(2) by android
,V/AudioPolicyService(  283): registerClient() client 0xb551c8c0, uid 10316
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38e2e19e:true
D/BluetoothAdapter( 5360): 764137571: getState() :  mService = null. Returning STATE_OFF
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/libc-netbsd( 5163): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5163): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5163): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5163): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 5163): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/libc-netbsd( 5163): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5163): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/art     ( 5360): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5360): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager(  838): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5423 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SystemWebViewEngine( 5360): CordovaWebView is running on device made by: LGE
I/NotificationManager(  838): android: cancelAsUser(2) by android
,W/art     ( 5360): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5360): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd( 5163): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5163): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 5163): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 5423): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5423): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Activity( 5360): Activity.onPostResume() called 
D/OpenGLRenderer( 5360): Render dirty regions requested: true
I/OpenGLRenderer( 5360): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5360): Enabling debug mode 0
D/Atlas   ( 5360): Validating map...
,D/SplitWindow(  838): check instance of lgWin Window{90d150a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5360): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/MultiDex( 5423): VM with version 2.1.0 has multidex support
I/MultiDex( 5423): install
,I/MultiDex( 5423): VM has multidex support, MultiDex support library is disabled.
D/InputDispatcher(  838): Focus entered window: Window{90d150a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,V/JNIHelp ( 5423): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/InputMethodManagerService(  838): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  838): Displayed com.test.thalitest/.MainActivity: +1s247ms
I/Timeline(  838): Timeline: Activity_windows_visible id: ActivityRecord{1ae86c3e u0 com.test.thalitest/.MainActivity t222} time:94033
,I/Timeline( 5360): Timeline: Activity_idle id: android.os.BinderProxy@1f419853 time:94048
,W/ActivityThread( 5423): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5423): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e285131: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5423): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5423): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5423): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
D/LocationInitializer( 3970): Restart initialization of location
,D/ChimeraCfgMgr( 5423): Reading stored module config
W/BindingManager( 5360): Cannot call determinedVisibility() - never saw a connection for the pid: 5360
,D/ChimeraCfgMgr( 5423): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
D/JsMessageQueue( 5360): Set native->JS mode to OnlineEventsBridgeMode
,D/NativeLibraryUtils( 5423): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5423): Connecting to CarCallService...
I/art     ( 5423): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5423): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 5423): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5423): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5423): Creating a new PhoneAdapter instance
W/ActivityManager(  838): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5423): setListener: com.google.android.gms.car.dn@271ddb4
W/ActivityManager(  838): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5423): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5423): Starting CarCallService with initial phone null
I/NotificationManager( 5423): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 5423): Package validated; name: com.android.vending
,I/NotificationManager( 5163): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5163): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 94888483562; DSPS: 3207925; Offset : -3020469075
,D/jxcore_app_log( 5360): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622759936
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  838): android: cancelAsUser(2) by android
D/libc-netbsd( 5163): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5163): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/chromium( 5360): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/Finsky  ( 5163): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5163): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{2065230d type 0 when 1453981575839 com.android.vending} when 1453981575839
,D/Finsky  ( 5163): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,I/art     ( 5360): CheckpointMarkThreadRoots callback created = 0x9b587450
,D/DeviceConnectionService( 1730): client connected with version: 8296000
,D/Finsky  ( 5163): [629] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/art     ( 5360): CheckpointMarkThreadRoots callback created = 0x9b587420
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5163): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5163): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/libc-netbsd( 5163): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5163): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5163): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5163): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/art     (  838): Explicit concurrent mark sweep GC freed 31161(1415KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.013ms total 209.834ms
,W/jxcore-log( 5360): Initializing JXcore engine
,W/jxcore-log( 5360): JXcore engine is ready
W/Thread-636( 5478): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7349]" dev="sockfs" ino=7349 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-636( 5478): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-636( 5478): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6471]" dev="sockfs" ino=6471 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-636( 5478): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-636( 5478): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-636( 5478): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25347]" dev="sockfs" ino=25347 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5360): Starting JXcore engine
,W/jxcore-log( 5360): Platform android
W/jxcore-log( 5360): 
W/jxcore-log( 5360): Process ARCH arm
W/jxcore-log( 5360): 
,I/ActivityManager(  838): Process com.google.android.gm (pid 5005) has died
,I/jxcore-log( 5360): JXcore Cordova bridge is ready!
I/jxcore-log( 5360): 
,W/jxcore-log( 5360): JXcore engine is started
I/jxcore-log( 5360): Toggling radios to true
I/jxcore-log( 5360): 
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  838): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  838): Message: 1
D/BluetoothManagerService(  838): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(764137571)( 1982): onBind()
,D/BluetoothManagerService(  838): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  838): Message: 40
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/WifiServiceImplEx(  838): setWifiEnabled: true pid=5360, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/WifiService(  838): setWifiEnabled: true pid=5360, uid=10316
D/Ulp_jni (  838): JNI:system_update. Event-4
,D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
D/WifiServiceImplEx(  838): disconnect pid=5360, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  838): reconnect pid=5360, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5360): Radios toggled
I/jxcore-log( 5360): 
I/jxcore-log( 5360): My device name is: LGE-LG-D722
I/jxcore-log( 5360): 
I/LGFTMITEM(  838): [GET_FTM][id=6], offset=12288
E/WifiHW  (  838): Wifi MAC Address = a0:39:f7:70:12:80
I/bluedroid( 1982): config_hci_snoop_log
D/BluetoothManagerService(  838): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  838): Broadcasting onBluetoothServiceUp() to 9 receivers.
,E/WifiHW  (  838): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  838): band=b
E/WifiHW  (  838): ": cur_etheraddr=a0:39:f7:70:12:80
D/SoftapController(  279): Softap fwReload - Ok
,V/LGMDMManagerInternal( 1982): Create singleton instance
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring down wlan0
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1982): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1982): Setting state to 11
I/BluetoothAdapterState( 1982): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(764137571)( 1982): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  838): Message: 60
D/BluetoothAdapterService(764137571)( 1982): processStart()
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1801): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/BtSettings.ProfileConfig( 1982): Unable to read settings
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
E/WifiHW  (  838): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5520 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1982): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): processStart() - Make Bond State Machine
D/BluetoothBondStateMachine( 1982): make
,D/BluetoothAdapterService( 1982): setAdapterService() - set to: null
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
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
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/HeadsetService( 1982): Received start request. Starting profile...
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/BluetoothHeadset(  838): Proxy object connected
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
D/BluetoothHeadset( 1749): Proxy object connected
I/LGBluetoothHeadsetServiceJni( 1982): classInitNative: succeeds
I/wpa_supplicant( 5527): Successfully initialized wpa_supplicant
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
D/LGBluetoothFeatureConfig( 1982): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1982): classInitNative: succeeds
D/HeadsetStateMachine( 1982): make
D/WifiMonitor(  838): startMonitoring(wlan0) with mConnected = false
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [2]
V/LGMDMManager( 1982): Create singleton instance
,D/BluetoothHeadset( 1749): Proxy object connected
D/BluetoothHeadset( 1749): Proxy object connected
I/wpa_supplicant( 5527): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5527): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:19.485 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/BluetoothAdapterState( 1982): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/HeadsetStateMachine( 1982): max_hf_connections = 1
I/bluedroid( 1982): get_profile_interface handsfree
,I/bt-btif ( 1982): btif_hf_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): max_hf_clients = 1
D/bt-btif ( 1982): btif_max_hf_clients = 1
D/bt-btif ( 1982): btif_enable_service: current services:0xa0692330
V/ToneGenerator( 1982): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  283): registerClient() client 0xb39b69a0, uid 1002
V/AudioPolicyManager(  283): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  283): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  283): getOutput() returns output 2
V/AudioFlinger(  283): registerClient() client 0xb40331f0, pid 1982
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  283): thread 0xb5651000 type 0 TID 1289 waking up
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  283): thread 0xb56eb000 type 0 TID 1290 waking up
V/AudioFlinger(  283): thread 0xb5735000 type 0 TID 1292 waking up
V/AudioSystem( 1982): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
,V/AudioFlinger(  283): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioFlinger(  283): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  283): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  283): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 4
,V/AudioSystem(  838): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1749): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1749): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1982): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1982): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1937): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1937): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3106): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3106): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  283): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  283): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  838): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 1982): Create Track: 0xb4909480
V/AudioTrack( 1982): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1982): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1749): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1749): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1982): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1982): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem(  283): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  283): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1749): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1749): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  838): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1937): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1937): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1937): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1937): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 2111): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2111): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1373): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1373): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1982): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1982): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 3106): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3106): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3106): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3106): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2111): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2111): ioConfigChanged() opening already existing output! 2
,V/AudioSystem( 2111): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2111): ioConfigChanged() opening already existing output! 6
I/AudioFlinger(  283): isAudioPlaybackHookOn() false
D/AudioTrack( 1982): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  283): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  283): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  283): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  283): getOutput() returns output 2
V/AudioSystem( 1982): getLatency() output 2, latency 50
V/AudioSystem( 1982): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1982): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1982): Create normal PCM 0x1 Track
V/AudioFlinger(  283): createTrack() lSessionId: 22
V/AudioFlinger(  283): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1982): Flags here  0x4 
V/AudioTrack( 1982): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  283): acquiring 22 from 1982, for 1982
V/AudioFlinger(  283):  added new entry for 22
V/ToneGenerator( 1982): ToneGenerator INIT OK, time: 98834
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/HeadsetStateMachine( 1982): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1982): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1982): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1982): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  283): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1982
D/audio_hw_primary(  283): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  283): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  283): platform_set_parameters: enter: bt_samplerate=8000
,V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb5651000
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
V/ToneGenerator( 1982): ToneGenerator destructor
V/ToneGenerator( 1982): stopTone
V/ToneGenerator( 1982): Delete Track: 0xb4909480
V/AudioTrack( 1982): ~AudioTrack, releasing session id from 1982 on behalf of 1982
V/AudioFlinger(  283): remove track (4099) and delete from mixer
V/AudioPolicyService(  283): AudioCommandThread() adding release output 2
V/AudioPolicyService(  283): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  283): PlaybackThread::Track destructor
V/AudioFlinger(  283): removeClient_l() pid 1982, calling pid 283
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioFlinger(  283): releasing 22 from 1982 for 1982
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioPolicyService(  283): AudioCommandThread() processing release output 2
V/AudioFlinger(  283): purging stale effects
V/AudioPolicyManager(  283): releaseOutput() 2
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
W/Process (  838): Unable to open /proc/5542/status
I/ActivityManager(  838): Process com.lge.qremote (pid 4981) has died
,D/UEI.SmartControl( 4672): Service.onUnbind: IControl
D/UEI.SmartControl( 4672): Service.onDestroy
D/UEI.SmartControl( 4672): Shutdown IRRCPlayer... 
W/irrc_jni( 4672): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4672): ~IrrcClient ++ 
D/irrcClient( 4672): ~IrrcClient -- 
W/irrc_jni( 4672): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4672): Blaster closed
D/UEI.SmartControl( 4672): Blaster closed
D/UEI.SmartControl( 4672): Shut down QS...
D/UEI.SmartControl( 4672): Stopped file observer...
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
I/UEI.SmartControl( 4672): QS lib stop result = true
D/UEI.SmartControl( 4672): QS shutdown complete
I/ActivityManager(  838): Process com.google.android.apps.plus (pid 4870) has died
,D/A2dpService( 1982): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 1982): classInitNative: succeeds
D/BluetoothA2dp(  838): Proxy object connected
V/Avrcp   ( 1982): make
D/Avrcp   ( 1982): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1982): get_profile_interface avrcp
I/bt-btif ( 1982): btif_rc_get_interface
I/bt-btif ( 1982): ## init ##
I/LGBluetoothAvrcpServiceJni( 1982): classInitNative: succeeds
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/LGBluetoothAvrcpAdapter( 1982): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1982): initNative: succeeds
I/BluetoothAvrcpBrcmAdapterJni( 1982): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 1982): initBrcmNative
,W/ResourcesManager( 5520): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5520): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 5520): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5520): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5520): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/AudioService(  838): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  838): No RCC entry present to update
E/RemoteController( 1982): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1982): classInitNative
I/BluetoothA2dpServiceJni( 1982): classInitNative: succeeds
D/A2dpStateMachine( 1982): make
I/bluedroid( 1982): get_profile_interface a2dp
I/bt-btif ( 1982): btif_av_get_src_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0692330
I/LGBluetoothA2dpServiceJni( 1982): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1982): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1982): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1982): [BTUI] init
D/LGBluetoothPowerControlManager( 1982): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  838): Message: 30
,D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/A2dpStateMachine( 1982): Enter Disconnected: -2
I/BluetoothHidServiceJni( 1982): classInitNative: succeeds
D/HidService( 1982): Received start request. Starting profile...
I/bluedroid( 1982): get_profile_interface hidhost
I/bt-btif ( 1982): btif_hh_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0692330
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
I/BluetoothHealthServiceJni( 1982): classInitNative: succeeds
D/HealthService( 1982): Received start request. Starting profile...
I/bluedroid( 1982): get_profile_interface health
I/bt-btif ( 1982): btif_hl_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): Process name (droid.bluetooth)
D/bt-btif ( 1982): btif_hl_soc_thread_init
D/bt-btif ( 1982): create_thread: entered
,D/bt-btif ( 1982): create_thread: thread created successfully
D/bt-btif ( 1982): entered btif_hl_select_thread
D/bt-btif ( 1982): btif_hl_select_wakeup_init
D/bt-btif ( 1982): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1982): max_s=55 
D/bt-btif ( 1982): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1982): classInitNative: succeeds
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
I/BluetoothPanServiceJni( 1982): classInitNative(L105): succeeds
D/PanService( 1982): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1982): initializeNative(L110): pan
I/bluedroid( 1982): get_profile_interface pan
D/bt-btif ( 1982): stack_initialized = 0, btpan_cb.enabled:0
I/IndexDatabaseHelper( 5520): Using schema version: 115
,I/IndexDatabaseHelper( 5520): Index is fine
I/LGBluetoothPanAdapter( 1982): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
I/BtGatt.JNI( 1982): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 1982): handleDebugAction() action=null
,D/BtGatt.GattService( 1982): Received start request. Starting profile...
D/BtGatt.GattService( 1982): start()
I/bluedroid( 1982): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1982): advertise manager created
I/LGBluetoothGattAdapter( 1982): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1982): setGattService:  set to: null
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
I/LGBluetoothMapAdapter( 1982): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1982): BluetoothMapBinder()
D/BluetoothMapService( 1982): Received start request. Starting profile...
D/BluetoothMapService( 1982): start()
,D/BluetoothMapEmailSettingsLoader( 1982): Found 0 applications
D/BluetoothMapEmailAppObserver( 1982): createReceiver()
D/BluetoothMapEmailAppObserver( 1982): initObservers()
D/BluetoothMapEmailAppObserver( 1982): getEnabledAccountItems()
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
,I/BluetoothSAPServiceJni( 1982): classInitNative(L170): succeeds
D/SapService( 1982): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1982): initializeNative(L175): sap
I/bluedroid( 1982): get_profile_interface sap
I/bt-btif ( 1982): btif_sc_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0692330
I/LGBluetoothSapAdapter( 1982): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1982): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1982): [BTUI] initSapManager
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
,V/BluetoothFTPServiceJni( 1982): classInitNative
D/LgeBluetoothSimManager( 1749): [BTUI] SAP_ENABLE_EVT
I/BluetoothFTPServiceJni( 1982): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/BluetoothFTPService( 1982): BluetoothFtpBinder()
,D/**BluetoothFTPService( 1982): Received start request. Starting profile...
V/BluetoothFTPService( 1982): FTP-Server Service start
D/BluetoothFTPServiceJni( 1982): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1982): get_profile_interface ftp
I/bt-btif ( 1982): btif_fts_get_interface
I/bt-btif ( 1982): init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0692330
D/BluetoothFTPServiceJni( 1982): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/LGBluetoothFeatureConfig( 1982): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1982): classInitNative
I/BluetoothOPPServiceJni( 1982): classInitNative(L373): succeeds
V/OppService( 1982): Opp initBinder
D/**OppService( 1982): Received start request. Starting profile...
D/OppService( 1982): Starting OppService 
D/LGBluetoothOppAdapter( 1982): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1982): com.android.bluetooth: cancelAll by com.android.bluetooth
,V/BluetoothOppNotification( 1982): send message
D/BluetoothOppPreference( 1982): Dumping Names:  
D/BluetoothOppPreference( 1982): {}
D/BluetoothOppPreference( 1982): Dumping Channels:  
D/BluetoothOppPreference( 1982): {}
D/OppService( 1982): Start()
W/BluetoothOPPServiceJni( 1982): initOppNative
D/BluetoothOPPServiceJni( 1982): initOppNative(L383): OPP
I/bluedroid( 1982): get_profile_interface opp
I/bt-btif ( 1982): btif_op_get_interface
D/BluetoothOPPServiceJni( 1982): initOppNative(L411): mOppCallbacksObj 2098426
D/BluetoothOPPServiceJni( 1982): initOppNative(L413): calling OPP init
,I/bt-btif ( 1982): btif_opp_init
D/bt-btif ( 1982): btif_enable_service: current services:0xa0692330
D/BluetoothOPPServiceJni( 1982): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1982): initOppNative(L430): mOppCallbacksObj 2098426
V/OppService( 1982): setOppService(): set to: com.broadcom.bt.service.opp.OppService@8fc5a87
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/HeadsetStateMachine( 1982): Proxy object connected
V/OppService( 1982): Deleted complete outbound shares, number =  0
D/LGBluetoothHfpAdapter( 1982): [BTUI] queryPhoneState
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
V/OppService( 1982): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1982): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@271ddb4 on behalf of 
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1982): Proxy object connected
D/LGBluetoothPowerControlManager( 1982): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@29406ddd
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 1982): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1982): Disconnected process message: 11, size: 0
,D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1982): pendingUpdate is :  true
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@7d64d52 on behalf of 
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1982): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppNotification( 1982): update too frequent, put in queue
,D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1982): Handler(): got msg=1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1982): pendingUpdate is :  false
E/OppService( 1982): UpdateThread is Completed
D/BluetoothAdapterService( 1982): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1982): new notify threadi!
V/BluetoothOppNotification( 1982): send delay message
V/OppService( 1982): ContentObserver received notification
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - All profile services started.
V/OppService( 1982): ContentObserver received notification
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 1982): pendingUpdate is :  true
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterState( 1982): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1982): enable
I/bt-btif ( 1982): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1982): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@7292120 on behalf of 
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@13a1823 on behalf of 
V/BluetoothOppNotification( 1982): mUpdateCompleteNotification = true
I/bt_hci_bdroid( 1982): init
I/bt_vendor( 1982): init
I/bt_vnd_conf( 1982): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/GKI_LINUX( 1982): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1982): btu_task pending for preload complete event
,I/bt_vnd_conf( 1982): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1982): libbt-hci init returns 0
V/OppService( 1982): pendingUpdate is :  false
E/OppService( 1982): UpdateThread is Completed
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@135b0ad9 on behalf of 
V/BluetoothOppNotification( 1982): outbound: succ-0  fail-0
V/BluetoothPbapReceiver( 1982): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1982): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1982): ***********state = 11
I/NotificationManager( 1982): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
,V/BluetoothOppNotification( 1982): outbound notification was removed.
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@37e7ec9e on behalf of 
V/BluetoothOppNotification( 1982): inbound: succ-0  fail-0
I/NotificationManager( 1982): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1982): inbound notification was removed.
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@180c137f on behalf of 
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/bt_userial_vendor( 1982): userial vendor open: opening /dev/ttyHS99
D/WiFiOffLoadUpdatePriority( 5520): remove : truetruefalse
D/bt_userial_vendor( 1982): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1982): device fd = 67 open
D/WiFiOffLoadUpdatePriority( 5520): remove2
V/WiFiOffLoadSharedPrefsUtils( 5520): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5520): save remove
D/WiFiOffLoadBroadcast( 5520): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5520): S: false, R: true
D/bt_hwcfg( 1982): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1982): hw_config_cback state=1
,D/bt_hwcfg( 1982): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1982): hw_config_cback state=4
D/bt_hwcfg( 1982): Chipset Name: BCM4334B0
D/bt_hwcfg( 1982): Chipset BCM4334B0
D/bt_hwcfg( 1982): Target name = [BCM4334B0]
,I/bt_hwcfg( 1982): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1982): hw_config_cback state=2
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1982): hw_config_cback state=3
I/bt_hwcfg( 1982): bt vendor lib: set UART baud 4000000
I/ActivityManager(  838): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5564 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1982): hw_config_cback state=5
,D/BluetoothPermissionRequest( 5520): onReceive
,D/LGBluetoothFeatureConfig( 5520):  get() - isFeatureLoaded : false
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
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3db35182:true
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
V/BluetoothSapReceiver( 1982): [BTUI] checkServiceStart
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/LGBluetoothStateChangeReceiver( 1982): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
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
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
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
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
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
I/ActivityManager(  838): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5584 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
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
D/PCSuite ( 5564): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
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
D/Tethering(  838): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1982): hw_config_cback state=6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1982): hw_config_cback state=6
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
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
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
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
D/UsbSettingsReceiver( 5520): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5520): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5520): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5520): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/UsbSettingsReceiver( 5520): [AUTORUN] onReceive() : app userid = 0, current userid = 0
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
D/UsbSettingsControl( 5520): [AUTORUN] getUsbConnected() : connected=true
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/UsbSettingsReceiver( 5520): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5520): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5520): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5520): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5520): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/UsbSettingsControl( 5520): [AUTORUN] setTetherStatus() : status=false
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
E/wpa_supplicant( 5527): USIM:  scard_init function
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/wpa_supplicant( 5527): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 9
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
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
W/ResourcesManager( 5584): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
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
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/CAR.SERVICE( 5423): mConnectedToCar = false, abort
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
I/wpa_supplicant( 5527): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
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
I/wpa_supplicant( 5527): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/WifiStateMachine(  838): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  838): setPowerSaveActivated(false)
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.594 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [3]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : state:0 event:3
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5584): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
E/WifiServerServiceExt(  838): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
E/ActivityThread( 5423): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1dfdc71c that was originally bound here
E/ActivityThread( 5423): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1dfdc71c that was originally bound here
E/ActivityThread( 5423): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5423): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5423): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5423): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5423): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5423): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5423): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5423): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5423): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5423): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5423): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5423): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5423): 	at com.google.android.chimera.ServiceProxy.onCreate(S,ourceFile:105)
E/ActivityThread( 5423): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5423): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5423): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5423): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5423): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5423): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5423): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5423): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5423): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5423): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/AuthorizationBluetoothService( 1730): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
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
D/WiFiOffLoadUpdatePriority( 5520): remove : truetruetrue
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
E/ActivityThread( 5423): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@8fc5a87 that was originally bound here
E/ActivityThread( 5423): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@8fc5a87 that was originally bound here
E/ActivityThread( 5423): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5423): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5423): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5423): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5423): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5423): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5423): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5423): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5423): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5423): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5423): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5423): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5423): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5423): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5423): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5423): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5423): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5423): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5423): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5423): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5423): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5423): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
W/ActivityManager(  838): Unbind failed: could not find connection for android.os.BinderProxy@3f7c4001
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
D/bt_hwcfg(, 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1982): hw_config_cback state=6
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1982): hw_config_cback state=6
E/WifiConfigStore(  838): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine(  838): enableVerboseLogging : level 2
D/WifiStateMachine(  838): Setting OUI to DA-A1-19
W/Settings( 5047): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  838): Setting external_sim to 1
,D/WfdsService( 1801): Supplicant Connection state is changed : true
I/WifiNative-HAL(  838): startHal
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x9abc88ec
I/WifiHAL (  838): Initializing wifi
I/WifiHAL (  838): Creating socket
D/WfdsService( 1801): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1801): Set the WFDS Monitor: true
I/WifiHAL (  838): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  838): Did set static halHandle = 0xb0566a00
D/wifi    (  838): halHandle = 0xb0566a00, mVM = 0xb487c280, mCls = 0x801ace
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x9abc889c
D/wifi    (  838): array field set
D/WfdsMonitor( 1801): WfdsMonitorThread create
I/WifiNative-HAL(  838): interface[0] = wlan0
I/WifiNative-HAL(  838): interface[1] = p2p0
D/WfdsMonitor( 1801): WFDS Monitor is created and started
D/WfdsService( 1801): WiFi: Supplicant connection re-established
D/wifi    (  838): setting scan oui 0xaafee100
D/WifiHAL (  838): Sending mac address OUI
E/WifiHAL (  838): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  838): Setting OUI to DA-A1-19
I/WifiNative-HAL(  838): startHal
D/wifi    (  838): setting scan oui 0xaafee100
D/WifiHAL (  838): Sending mac address OUI
E/WifiHAL (  838): failed to set scanning mac OUI; result = -95
E/CtrlSupplicant( 1801): Access OK "@android:wpa_wlan0"
I/WifiNative-HAL(  838): Waiting for HAL events mWifiHalHandle=-1336514048
D/wifi    (  838): waitForHalEvents called, vm = 0xb487c280, obj = 0x801ace, env = 0xb0426b00
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x990e5b2c
E/CtrlSupplicant( 1801): Succeed to open control connection
E/CtrlSupplicant( 1801): Succeed to open monitor connection
D/WfdsMonitor( 1801): Supplicant connection established
D/WfdsService( 1801): Connected to the supplicant for wfds
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/WifiHS20(  838): hidePasspointNotification off =false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.655 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/LGWifiP2pService(  838): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring up p2p0
D/WifiMonitor(  838): startMonitoring(p2p0) with mConnected = true
D/WifiScanningService(  838): SCAN_AVAILABLE : 3
D/LGWifiP2pService(  838): P2pEnablingState
D/LGWifiP2pService(  838): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2p socket connection successful
D/LGWifiP2pService(  838): P2pEnabledState
D/RttService(  838): SCAN_AVAILABLE : 3
,D/RttService(  838): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  838): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  838): startHal
D/wifi    (  838): getting scan capabilities on interface[0] = 0xaafee100
D/WifiHAL (  838): Creating message to get scan capablities; iface = 24
D/wifi    (  838): failed to get capabilities : -95
E/WifiScanningService(  838): could not get scan capabilities
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/LGWifiP2pService(  838): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  838): before postfix = G3s-1
D/WifiServerServiceExt(  838): postfix byte check : 5
D/LGWifiP2pService(  838): after postfix = G3s-1
I/WifiServerServiceExt(  838): set CMD_ADD_DEFAULT_PROFILE
D/WifiNative-HAL(  838): p2pGetDeviceAddress
D/WifiNative-HAL(  838): p2pGetDeviceAddress returning a2:39:f7:70:12:80
I/WifiServerServiceExt(  838): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 5527): nWIFIDualbandAPConnection: 1
I/WifiServerServiceExt(  838): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5527): disconnect_rssi_lvl: -100
,I/WifiServerServiceExt(  838): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5527): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
D/WfdsService( 1801): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/LGWifiP2pService(  838): DeviceAddress: a2:39:f7:70:12:80
I/WifiServerServiceExt(  838): set CMD_UPDATE_DEFAULT_PROFILE
D/WfdsService( 1801): Update P2p Interface State: 3
D/LGWifiP2pService(  838): sending p2p persistent groups changed broadcast
,D/LGWifiP2pService(  838): sending p2p connection changed broadcast
D/LGWifiP2pService(  838): InactiveState
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1801): WifiP2pState is changed : true
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1801): Receive the WFDS_ENABLE Method
D/WfdsService( 1801): Set the WFDS Monitor: true
D/WfdsService( 1801): Connected to the supplicant for wfds
D/WfdsService( 1801): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsJNI ( 1801): doCommand: WFDS_SET TRUE
E/WifiServerServiceExt(  838): No p2p device connected
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1801): isConnected: false
D/WfdsService( 1801): GroupInfoAvailable: mGroupInfo is null
I/bt_hwcfg( 1982): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1982): Settlement delay -- 100 ms
I/bt_hwcfg( 1982): Setting fw settlement delay to 100 
I/wpa_supplicant( 5527): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/wpa_supplicant( 5527): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1801): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5527): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/wpa_supplicant( 5527): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
,D/WfdsJNI ( 1801): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5527): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1801): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1801): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1801): selectPreferredScanChannel [6]
D/WfdsService( 1801): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
W/WfdsService( 1801): DefaultState - msg [9441285] is not handled
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.768 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5527): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WiFiOffLoadUpdatePriority( 5520): remove1
V/WiFiOffLoadSharedPrefsUtils( 5520): save remove
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.798 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LocSvc_java(  838): onReceive
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.806 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateSCANNING
D/WiFiOffLoadBroadcast( 5520): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5520): S: false, R: false
D/GONS    ( 1749): GONS isTestMode: false Country: 
,I/wpa_supplicant( 5527): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5527): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.828 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1982): hw_config_cback state=2
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.832 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateASSOCIATING
D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1982): hw_config_cback state=7
I/bt_hwcfg( 1982): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1982): Setting local bd addr to F8:95:C7:87:85:54
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateASSOCIATED
D/WiFiOffLoadUpdatePriority( 5520): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5520): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5520): private wpa: "NG700" 300
D/WifiServiceImplEx(  838): addOrUpdateNetwork pid=5520, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  838):  uid = 1000 SSID "NG700" nid=0
I/WifiServiceExtension(  838): setVHTCapabilityType  : false
,D/bt_hwcfg( 1982): hw_config_cback opcode:0xfc01
,D/bt_hwcfg( 1982): hw_config_cback state=8
I/bt_hwcfg( 1982): vendor lib fwcfg completed
I/bt-btif ( 1982): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1982): btu_task received preload complete event
I/WifiServerServiceExt(  838): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  838): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  838): setSecurityType  : 2
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
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.898 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:20.901 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  838): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  838): Got NetworkAgent Messenger
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  838): NetworkAgent connected
D/WifiExtManager(  838): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@34768518
D/WifiExtManager(  838): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@39bf30fb
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
D/DhcpStateMachine(  838): StoppedState
E/WifiStateMachine(  838): Start Dhcp Watchdog 1
D/DhcpStateMachine(  838): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): WaitBeforeStartState
,D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateGROUP_HANDSHAKE
E/WifiConfigStore(  838):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WiFiOffLoadUpdatePriority( 5520):  ssid "NG700" prio 300
,D/WiFiOffLoadUpdatePriority( 5520): configuration updated: 0
I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:21.031 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
E/bt-btif ( 1982): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 1982): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1982): warning : media task started media_task_refcnt 1 
W/bt-smp  ( 1982): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1982): Plain text(LSB ~ MSB) = 30 f9 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1982): Encrypted text(LSB ~ MSB) = c8 28 63 57 ed 60 72 d5 79 13 5a e7 e7 29 8c da 
W/bt-btm  ( 1982): Stopping oneshot timer
D/BT_PROF_AUDIO( 1982): created moving average (N=100)
D/BT_PROF_AUDIO( 1982): reset rate average
W/bt-btif ( 1982): overflow 0, enter 0, exit 0
E/bt-btif ( 1982): Calling BTA_HhEnable
E/bt-btif ( 1982): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1982): Address is:F8:95:C7:87:85:54
D/BluetoothAdapterProperties( 1982): Name is: G3s-1
D/BluetoothManagerService(  838): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  838): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1982): Scan Mode:20
D/BluetoothAdapterProperties( 1982): Discoverable Timeout:120
E/bt-btif ( 1982): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1982): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/bt-btif ( 1982): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1982): BTA_JvEnable
E/bt-btif ( 1982): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1982): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1982): init_hci_slots(L136): in
D/IOP_DB_BT( 1982): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1982): db_open: db_open : handle 2691287004l, read 11046 bytes onto local cache
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
,D/BluetoothAdapterProperties( 1982): ScanMode =  20,
D/BluetoothAdapterProperties( 1982): State =  11
D/BluetoothAdapterProperties( 1982): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1982): Setting state to 12
I/BluetoothAdapterState( 1982): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(764137571)( 1982): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 1982): onOpcStateChange()
I/bt-btif ( 1982): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1982): ops_state_cb(L223):  ops_state_cb state:0
D/BluetoothManagerService(  838): Message: 60
D/OppService( 1982): onOpsStateChange() :0
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/bt-btif ( 1982): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1982): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1982): onFtpServerEnabled: /storage
D/BluetoothManagerService(  838): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/OppService( 1982): Recieved MESSAGE_OPC_ENABLE
D/BluetoothPanServiceJni( 1982): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_properties_cb
D/LGBluetoothFeatureConfig( 1982): isPrivacyLogsEnabled : true
I/BluetoothAdapterState( 1982): Entering On State
I/BluetoothAdapterState( 1982): Entering On State from state = 11
D/OppService( 1982): Recieved MESSAGE_OPS_ENABLE
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(764137571)( 1982): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1982): [BTUI] autoConnect() : not allowed
D/BluetoothAdapterProperties( 1982): Scan Mode:21
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1982): Discoverable Timeout:120
D/BluetoothHeadset( 1749): onBluetoothStateChange: up=true
D/BluetoothHeadset(  838): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 1982): [BTUI] OnState
D/BluetoothA2dp( 1982): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 1982): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1982): [BTUI]         local_name: G3s-1
D/BluetoothA2dp(  838): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1749): onBluetoothStateChange: up=true
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(764137571)( 1982): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1982): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1749): onBluetoothStateChange: up=true
E/BluetoothManagerService(  838): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  838): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/LGBluetoothAPIService( 1801): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManagerService(  838): Message: 40
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/BluetoothMapService( 1982): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1982): STATE_ON
D/LGBluetoothAPIService( 1801): Message: 1
D/LGBluetoothAPIService( 1801): MESSAGE_BOOT_COMPLETED
D/bt_h4   ( 1982): vendor lib postload completed
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
V/BluetoothPbapService( 1982): Pbap Service onCreate
V/BluetoothPbapService( 1982): Starting PBAP service
I/LGBluetoothAPIService( 1801): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/LGBluetoothPbapAdapter( 1982): [BTUI] getInstance : create
V/BluetoothPbapService( 1982): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1982): state: 12
V/BluetoothMapService( 1982): Handler(): got msg=1
D/BluetoothMapMasInstance( 1982): Map Service startRfcommSocketListener
V/BluetoothOppNotification( 1982): new notify threadi!
V/BluetoothOppNotification( 1982): send delay message
D/LGBluetoothAPIServer( 1982): [BTUI] onCreate()
D/BluetoothMapMasInstance( 1982): MAS initSocket()
D/BluetoothMapMasInstance( 1982):   masId = 00
D/BluetoothMapMasInstance( 1982):   msgTypes = 0e
D/BluetoothMapMasInstance( 1982):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1982):   SDP string = 000eSMS/MMS
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/LGBluetoothAPIServer( 1982): [BTUI] onBind()
,V/BluetoothPbapService( 1982): Handler(): got msg=1
D/LGBluetoothAPIService( 1801): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1801): Message: 100
D/LGBluetoothAPIService( 1801): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 1982): Pbap Service startRfcommSocketListener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@ae234aa on behalf of 
V/BluetoothPbapService( 1982): Pbap Service initSocket
W/BluetoothAdapter( 1982): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 1982): mUpdateCompleteNotification = true
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
W/BluetoothAdapter( 1982): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1982): [BTUI] createSocketChannel FD=83 mFd=0
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1982): [BTUI] createSocketChannel FD=85 mFd=83
V/BluetoothMapMasInstance( 1982): Succeed to create listening socket 
V/BluetoothPbapService( 1982): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1982): Accepting socket connection...
V/BluetoothPbapService( 1982): Accepting socket connection...
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@33d8689b on behalf of 
,V/BluetoothOppNotification( 1982): outbound: succ-0  fail-0
I/NotificationManager( 1982): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1982): outbound notification was removed.
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@5e5f438 on behalf of 
V/BluetoothOppNotification( 1982): inbound: succ-0  fail-0
I/NotificationManager( 1982): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1982): inbound notification was removed.
V/BluetoothOppProvider( 1982): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1982): created cursor android.database.sqlite.SQLiteCursor@2ea23c11 on behalf of 
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a9bbc1d target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a9bbc1d target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  838): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  838): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  838): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  838): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateCOMPLETED
I/WifiServerServiceExt(  838): set CMD_UPDATE_DEFAULT_PROFILE
D/WiFiOffLoadUpdatePriority( 5520): configuration saved: true
,D/PCSuite ( 5564): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 5520): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 1982): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1982): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1982): ***********state = 12
,I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5621 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,D/LocalBluetoothProfileManager( 5520): Adding local A2DP profile
D/BluetoothManagerService(  838): Message: 30
D/LocalBluetoothProfileManager( 5520): Adding local HEADSET profile
D/BluetoothManagerService(  838): Message: 30
,D/BluetoothManagerService(  838): Message: 30
,D/BluetoothManagerService(  838): Message: 30
D/LocalBluetoothProfileManager( 5520): Adding local MAP profile
D/BluetoothMap( 5520): Create BluetoothMap proxy object
D/BluetoothManagerService(  838): Message: 30
D/BluetoothManagerService(  838): Message: 30
,D/LocalBluetoothProfileManager( 5520): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 1982): Pbap Service onBind
D/LGBluetoothUserBindClient( 5520): [BTUI] initUserBindClient
W/ContextImpl( 5520): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 5520): finishStartingService: stopping service
D/BluetoothA2dp( 5520): Proxy object connected
D/A2dpProfile( 5520): Bluetooth service connected
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,D/BluetoothHeadset( 5520): Proxy object connected
D/HeadsetProfile( 5520): Bluetooth service connected
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothInputDevice( 5520): Proxy object connected
D/HidProfile( 5520): Bluetooth service connected
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothPan( 5520): BluetoothPAN Proxy object connected
D/PanProfile( 5520): Bluetooth service connected
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothMap( 5520): Proxy object connected
,D/MapProfile( 5520): Bluetooth service connected
D/BluetoothMap( 5520): getConnectedDevices()
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/DhcpStateMachine(  838): DHCPV4 request on wlan0
V/BluetoothMapService( 1982): getConnectedDevices()
V/LgDhcpStateMachineHelper(  838): [bssid] hash key :c0:ff:d4:d3:aa:48
D/BluetoothPbap( 5520): Proxy object connected
D/LgDhcpStateMachineHelper(  838): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/PbapServerProfile( 5520): Bluetooth service connected
D/LGBluetoothUserBindClient( 5520): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5520): onReceive
D/LGBluetoothFeatureConfig( 5520): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5520): [BTUI] FileNotFound: readProperty
I/dhcpcd  ( 5642): version 5.5.6 starting
E/dhcpcd  ( 5642): get_duid: Read-only file system
I/ActivityManager(  838): Killing 4672:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/dhcpcd  ( 5642): wlan0: rebinding lease of 192.168.1.134
,V/BluetoothOppReceiver( 1982): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
W/libprocessgroup(  838): failed to open /acct/uid_10089/pid_4672/cgroup.procs: No such file or directory
,V/BluetoothOppManager( 1982): restoreApplicationData! falsefalsenullnull
D/LGDMClient( 5621): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5621): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5621): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/BluetoothSapReceiver( 1982): [BTUI] checkServiceStart
,D/LGBluetoothStateChangeReceiver( 1982): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
W/ContextImpl( 5621): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/AuthorizationBluetoothService( 1730): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDMClient( 5621): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5621): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 5621): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
I/PCSuite ( 5564): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5564): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5564): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5659 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  838): Killing 5278:com.android.calendar/u0a13 (adj 15): empty #11
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 6
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  838): failed to open /acct/uid_10013/pid_5278/cgroup.procs: No such file or directory
W/ResourcesManager( 5659): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1223399f:true
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/ActivityManager(  838): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5679 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  838): Process com.google.android.talk (pid 5047) has died
,V/[BNRBootReceiver]( 5679): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5679): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5679): Boot Receiver Return
,V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
W/MainApplication( 5679): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5520): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5698 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 5642): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
V/LGMDMManager( 5659): Create singleton instance
,I/dhcpcd  ( 5642): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,I/AudioManager( 5659): getMode name:com.lge.qremote
V/AudioFlinger(  283): thread 0xb56eb000 type 0 TID 1290 going to sleep
V/AudioFlinger(  283): thread 0xb5651000 type 0 TID 1289 going to sleep
,V/AudioFlinger(  283): thread 0xb5735000 type 0 TID 1292 going to sleep
D/UEI.SmartControl( 5698): Quickset Services start...
,I/UEI.SmartControl( 5698): Manufacture = LGE
D/UEI.SmartControl( 5698): File observer start...
,E/UEI.SmartControl( 5698): IR Port is disabled: false
D/UEI.SmartControl( 5698): Starting file observer...
D/UEI.SmartControl( 5698): Extracting JNI libs...
D/UEI.SmartControl( 5698): --- this system supports 32-bit or 64-bit only
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5698): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5698): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5698): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  838): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  838): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  838): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  838): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,V/DhcpStateMachine(  838): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  838): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  838): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  838): RunningState
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine(  838): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  838): ignoring duplicate network state non-change
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiHS20(  838): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService(  838): Adding iface wlan0 to network 100
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  838): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine(  838): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:22.806 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:22.811 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:22.813 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/UEI.SmartControl( 5698): --- Selecting new region: 2
I/UEI.SmartControl( 5698): -- Running on KitKat(19) and above! JNI will be used.
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:22.815 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,D/UEI.SmartControl( 5698): Platform has CIR...
D/UEI.SmartControl( 5698): NO CIR support, need to check package...
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
I/UEI.SmartControl( 5698): Model: LG-D722 uses JNI
E/ConnectivityService(  838): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  838): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 5698): QS Service created
D/ConnectivityService(  838): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  838): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  838): Setting Dns servers for network 100 to [/192.168.1.1]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
D/Nat464Xlat(  838): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  838): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  838): currentScore = 0, newScore = 20
D/ConnectivityService(  838):    accepting network in place of null
D/ConnectivityService(  838): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  838): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/TelephonyNetworkFactory-1( 1749): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
E/ConnectivityService(  838): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] Start DNSResolver start to wait
,E/UEI.SmartControl( 5698): QS start get config
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] wait 500ms before dns check
D/CSLegacyTypeTracker(  838): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/CSLegacyTypeTracker(  838): [e] list.add(nai) empty : false size: 1
,D/Tethering(  838): MasterInitialState.processMessage what=3
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/ConnectivityService(  838): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  838): validation of new default Network = false
D/ConnectivityService(  838): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  838): enableDataServiceNotify 
D/DSQN    (  838): start dsqn bin
D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
,V/NetworkPolicy(  838): [LG_RESTRICTED] checkMobilePolicy_type()
,V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
D/ConnectivityService(  838): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 5748): DSQN samuel.seo ver 141203
E/DSQN    ( 5748): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5748): created command queue thread
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 5748): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5748): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/PCSuite ( 5564): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5564): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5520): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 5698): Loading JNI Libs...
D/UEI.SmartControl( 5698):  configuring local db...
D/WiFiOffLoadBroadcast( 5520): MCCMNC not supported: null
,I/PCSuite ( 5564): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5564): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/UEI.SmartControl( 5698):  ---- Has DB8: true
,D/UEI.SmartControl( 5698): QS start statue = true Error code = 0
D/UEI.SmartControl( 5698): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5698): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5698): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5698): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5698): IrrcClient ++ 
D/irrcClient( 5698): getIrrcService ++ 
,D/irrcClient( 5698): getIrrcService -- 
D/irrcClient( 5698): IrrcClient -- 
W/irrc_jni( 5698): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5698): Services init done
I/UEI.SmartControl( 5698): Device manager: loading config....
D/UEI.SmartControl( 5698): Config is loaded...
,I/ActivityManager(  838): Process com.android.vending (pid 5163) has died
,D/UEI.SmartControl( 5698): QS Service init finished
D/UEI.SmartControl( 5698):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5698): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5698): QS Service version name: 0.1.73
D/UEI.SmartControl( 5698): QS Service version code: 1073
D/UEI.SmartControl( 5698): Service requested: Control
D/UEI.SmartControl( 5698): Internal service binding...
,D/UEI.SmartControl( 5698): -----IControl: 11
D/UEI.SmartControl( 5698): Caller: com.lge.qremote
D/UEI.SmartControl( 5698): ------------ IControl registerCallback...
I/UEI.SmartControl( 5698): Registering callback...
D/UEI.SmartControl( 5698): -----IControl: 19
D/UEI.SmartControl( 5698): Caller: com.lge.qremote
I/UEI.SmartControl( 5698): Registering Services Ready callback...
I/UEI.SmartControl( 5698): Notify client services are ready...
D/UEI.SmartControl( 5698): -----IControl: 8
D/UEI.SmartControl( 5698): Caller: com.lge.qremote
,I/AudioManager( 5659): getMode name:com.lge.qremote
I/ActivityManager(  838): Killing 5238:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10014/pid_5238/cgroup.procs: No such file or directory
,I/AudioManager( 5659): getMode name:com.lge.qremote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] DNSResolver start dns
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 5659): getMode name:com.lge.qremote
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5748): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 5748): restart monitoring
I/DSQN    ( 5748): dsqn report finish
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  838): DSQM DsqnNotification wlan0  1
D/DSQN    (  838): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jan 2016 11:46:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453981583671], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453981583644]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Validated
D/ConnectivityService(  838): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  838): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  838): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  838): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  838): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/ConnectivityService(  838): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  838): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkControl,ler.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  838): Process com.google.android.gms (pid 3970) has died
,I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:24.054 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  277): 
I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/WifiInternetCheck(  838): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5776 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  838): onReceive
D/LocSvc_java(  838): got connectivity action
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/art     (  309): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 411us total 26.304ms
,D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:1 arg2:1
,D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  838): Sending msg: 5 arg1:0 arg2:1
,I/art     (  309): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 26.591ms
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.636ms
,D/NetworkChangeNotifierAutoDetect( 1937): Network connectivity changed, type is: 2
,I/ActivityManager(  838): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5809 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
I/System.out(  838): propertyValue:false
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocSvc_java(  838): NTP server returned: 1453981586358 (Thu Jan 28 12:46:26 GMT+01:00 2016) reference: 105573 certainty: 48 system time offset: 46
,D/AlarmManagerService(  838): Setting time of day to sec=1453981586
W/AlarmManagerService(  838): Unable to set rtc to 1453981586: Invalid argument
D/LocSvc_java(  838): Sending msg: 10 arg1:0 arg2:1
,I/ActivityManager(  838): Start proc com.google.android.gms for service com.google.android.gms/.pseudonymous.service.PseudonymousIdService: pid=5827 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/[SystemUI]Clock( 1373): onReceive = android.intent.action.TIME_SET
,D/WeatherService( 2739): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:46:26
I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5838 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/WeatherService( 2739): 2 : requestRefreshAppWidget, isUpdateStart : false
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/art     (  838): Explicit concurrent mark sweep GC freed 78618(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 4.380ms total 374.085ms
,E/GpsLocationProvider(  838): No APN found to select.
W/ActivityManager(  838): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,D/UpdateThreadPoolManager( 2739): 2 : This is isUpdating : false
,D/WeatherService( 2739): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2739): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2739): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2739): 2 : Fixed theme : optimus
D/WeatherReflect( 2739): 2 : Map key string is -2
,D/lim     ( 2739): 2 : time = 12:46
I/WeatherReflect( 2739): Model Name : LG-D722
D/WeatherTheme( 2739): 2 : exactly same view!
D/WeatherTheme( 2739): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2739): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:46:26
,I/[LGHome]LGDateChangeReceiver( 1874): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=28 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
,I/MusicStore( 5776): Database version: 120
,I/[LGHome]LGCalendarIcon( 1874): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 28
I/PhenotypeConfigurator( 1730): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
I/[LGHome]LGCalendarIcon( 1874): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 28
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 5838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5838): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5838): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  838): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5872 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  838): Process com.google.android.gms:car (pid 5423) has died
,W/ResourcesManager( 5827): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5827): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeGpsConstants(  838): Can't find 'ext_gps.conf'!!
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager( 5872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5872): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5872): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 5809): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5809): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
,D/LgeGpsLocationProvider(  838): NTP server: europe.pool.ntp.org
,D/LgeGpsLocationProvider(  838): NTP server returned: 1453981586949 (Thu Jan 28 12:46:26 GMT+01:00 2016) reference: 106118 certainty: 26 system time offset: 53
I/MultiDex( 5827): VM with version 2.1.0 has multidex support
,I/MultiDex( 5827): install
I/MultiDex( 5827): VM has multidex support, MultiDex support library is disabled.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5776): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/AppConfig( 5872): Total System Memory = 906309632
,I/GalleryUtils( 5872): Application Heap = 96 MB
I/LGEmail ( 5838): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/AppConfig( 5872): App Tier : NOT_DEF
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
V/JNIHelp ( 5809): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/SystemHelper( 5872): region [EU], country [EU], operator [OPEN], sub-operator []
,D/LGEmail ( 5838): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/System  ( 5809): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5809): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager(  838): android: cancelAsUser(-1597574061) by android
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
V/JNIHelp ( 5827): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5827): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5827): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@180c137f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5827): Installed default security provider GmsCore_OpenSSL
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5776): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
W/ContextImpl( 5776): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
I/ActivityManager(  838): Process com.lge.settings.easy (pid 5584) has died
,I/NotificationManager( 5827): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5827): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 5827): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  838): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5920 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     ( 5827): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/ResourcesManager( 5776): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5776): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Process com.lge.lgdmsclient (pid 5621) has died
I/art     ( 5809): CheckpointMarkThreadRoots callback created = 0xb042dab0
W/art     ( 5827): Suspending all threads took: 5.322ms
,E/YouTube MDX( 5809): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/art     ( 5827): Background sticky concurrent mark sweep GC freed 24788(1329KB) AllocSpace objects, 2(32KB) LOS objects, 9% free, 10MB/11MB, paused 12.200ms total 114.409ms
D/NativeLibraryUtils( 5827): Install completed successfully. count=14 extracted=0
V/WifiInternetCheck(  838): isHttpConnectionAvailable - We got a valid response : 204
,D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 5809): CheckpointMarkThreadRoots callback created = 0xb4958de0
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5809): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
V/JNIHelp ( 5776): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ALBootInit( 5920): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 5920): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5920): [setNextAlert] start
D/Alarms  ( 5920): [setNextAlert] (1)
,E/ActivityThread( 5827): Failed to find provider info for com.android.contacts.metadata
I/NotificationManager(  838): android: cancelAsUser(-1816247584) by android
D/Alarms  ( 5920):  minTime  = 0
D/Alarms  ( 5920):  -- OK multi -- 0
,E/jeny.kim( 5920): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5920): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/ResourcesManager( 5809): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5809): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CommonUtil( 5920): BUILD Operator: OPEN
,D/Alarms  ( 5920): broadcastToWidgetProvider : false
D/SyncManager(  838): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 38073, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  838): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 140064, reason: UserStart
D/Alarms  ( 5920): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,W/ActivityThread( 5776): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5776): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bd71250: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5776): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5776): GMSCore installation verified
,V/SettingsProvider(  838): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 5920): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 5920): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@5c2dc1d
,I/NotificationManager(  838): android: cancelAsUser(716319171) by android
,V/DigitalAppWidgetProvider( 5920): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@5c2dc1d
D/QuickCoverProvider( 5920): onReceiver
W/art     ( 5776): Suspending all threads took: 6.292ms
,I/art     ( 5827): CheckpointMarkThreadRoots callback created = 0xaaf314b0
,I/ActivityManager(  838): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=5972 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5827): CheckpointMarkThreadRoots callback created = 0xaaf31490
,I/ConfigStore( 5776): Config Database version: 1
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5360): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5360): 
D/UEI.SmartControl( 5698): Internal timer expired: 1
,W/ResourcesManager( 5972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/dex2oat ( 5978): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1927479190.jar --oat-fd=42 --oat-location=/data/data/com.google.android.youtube/cache/ads1927479190.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/ActivityManager(  838): Process com.lge.bnr (pid 5679) has died
,D/CalendarApplication( 5972): CalendarApplication.onCreate()
,E/Auth.Api.Credentials( 5827): [CredentialSyncAdapter] Unknown sync event.
D/PreferenceKeysParser( 5972): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5972): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@12b70448, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@12eaf2e1, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1f102806, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@20b70ec7, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@295c1cf4, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@5c2dc1d, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2e76be92, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2d8bd063, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@d981460, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2361d19, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@83e31de, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@25610fbf, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@29da168c, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@10271d5, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@c778dea, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2920e8db, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3e580f78, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@f055651, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@19389eb6, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@343b37b7, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@16baab24, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@f78068d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@627f042, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1f419853, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2e895590, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@25eb7e89, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@cc8ce8e, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@304366af, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@30563abc, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@4047a45, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2987459a, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@14e9becb, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3baa46a8, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@16f775c1, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1842166, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@22537ca7, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1db12554, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@10c4acfd, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1920edf2, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36b13c43, lg_preferences_alerts_vibratetype=com.androi,d.calendar.adaptation.PreferenceKey$KeyData@28a542c0, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@9341bf9, l
,D/GeneralPreferenceUtils( 5972): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5972): [init]
I/Config  ( 5972): LGCalendar ver.4.40.17
,I/Config  ( 5972): start check model
I/Config  ( 5972): start check native_ca
I/Config  ( 5972): Config Operator=OPEN, Country=EU
D/Config  ( 5972): [setDefaultValuesToPref]
D/Config  ( 5972): [parseProfiles]
D/ProfilesParser( 5972): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5972): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5972): [updateProfiletoCountryInfo]
D/GeneralPreference( 5972): [checkAndMigrateOldPreference]
,I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
I/NotificationManager( 5809): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/AgendaWidgetManager( 5972): [updateWidgets] 
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5809): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5809): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,I/InitNotificationRingtoneService( 5972): Start InitializeAlertRingtoneService.onHandleIntent
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5809): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
I/AlertUtils( 5972): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/InstanceID/Rpc( 5809): Found 10006
,I/AlertUtils( 5972): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,E/ConnectivityChangeReceiver( 5827): Ignoring connectivity change
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
W/ContextImpl( 5809): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
D/ConnectivityService(  838): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): dumpNetworkRequest
D/ConnectivityService(  838):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/ConnectivityService(  838):     Requests:
D/ConnectivityService(  838):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     Lingered:
D/ConnectivityService(  838): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): apparently satisfied.  currentScore=60
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5827): CM callback handler got msg 524290
I/dex2oat ( 5978): dex2oat took 337.830ms (threads: 4)
,I/MediaRouter( 5776): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5776): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/art     (  838): Explicit concurrent mark sweep GC freed 28841(1397KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 4.584ms total 193.581ms
,I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
D/MonthWidgetProvider( 5972): [onReceive]
,W/HolidayIntentService( 5972): onHandleIntent
D/CalendarWidgetProvider( 5972): [onReceive]
D/CalendarWidgetProvider( 5972): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5972): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 5972): readJsonAsset : holiday.json
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
D/WeekWidgetProvider( 5972): [onReceive]
D/CalendarWidgetProvider( 5972): [onReceive]
D/CalendarWidgetProvider( 5972): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5972): [onUpdateAndInitCalendarTime]
I/NetworkMonitor( 5776): type=WIFI subType= reason=null isConnected=true
,D/WeatherAncestor( 2739): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:46:28
D/UpdateThreadPoolManager( 2739): 2 : This is isUpdating : false
,I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/Weather_cast( 2739): 2 : set auto-update time : 1/28 15:46
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5972): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 5972): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/NotificationManager(  838): android: cancelAsUser(-1816247584) by android
D/WeatherAncestor( 2739): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:46:28
D/WeatherService( 2739): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/HolidayIntentService( 5972): onHandleIntent:holiday data empty
,I/ActivityManager(  838): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6035 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/AlertUtils( 5972): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5972): End InitializeAlertRingtoneService.onHandleIntent
,W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2739): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2739): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2739): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  279): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
,I/NotificationManager(  838): android: cancelAsUser(-1597574061) by android
,D/TimeService( 6035): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453981589097
D/        ( 6035): TimeServiceNative: User Time to be set is 1453981589097
D/QC-time-services( 6035): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6035): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6035): Lib:time_genoff_operation: pargs->ts_val = 1453981589097
D/QC-time-services( 6035): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  321): Daemon: Connection accepted:time_genoff
D/QC-time-services(  321): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453981589097
D/QC-time-services(  321): Daemon:genoff_opr: Base = 2, val = 1453981589097, operation = 0
D/QC-time-services(  321): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/10/70 15:48:1
D/QC-time-services(  321): Daemon:Value read from RTC seconds = 13880881000
D/QC-time-services(  321): Daemon:new time 1453981589097 
D/QC-time-services(  321): Daemon: delta 1440100708097 genoff 1440100708097 
D/QC-time-services(  321): Daemon:genoff_persistent_update: Writing genoff = 1440100708097 to memory
D/QC-time-services(  321): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  321): Daemon:time_persistent_memory_opr:Genoff write operation 
I/NetworkMonitor( 5776): type=WIFI subType= reason=null isConnected=true
,D/QC-time-services(  321): Updating the TOD offset
D/QC-time-services(  321): Daemon:genoff_persistent_update: Writing genoff = 1440100708097 to memory
D/QC-time-services(  321): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  321): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  321): Daemon:Update to modem bit set
D/QC-time-services(  321): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  321): Daemon: Base = 2, Value being sent to MODEM = 1124135908097
E/QC-time-services( 6035): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  321): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6063 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/eas_req ( 5838): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/GHttpClientFactory( 5776): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/NotificationManager( 5809): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  838): Process com.android.settings (pid 5520) has died
,I/GoogleURLConnFactory( 5776): Using platform SSLCertificateSocketFactory
,I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6083 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/CheckinService( 5827): Checkin interval check for package: unspecified last checkin: 1453902999990 min interval config: 0 actual interval: 78589488
,W/ResourcesManager( 6063): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationManager( 5776): com.google.android.music: cancel(1061) by com.google.android.music
,I/HubEmail( 5838): JNI_OnLoad()
I/HubEmail( 5838): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5838): registerNatives()
I/HubEmail( 5838): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5838): registerNativeMethods()
I/HubEmail( 5838): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5838): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 5838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6083): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6083): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6083): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6083): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/GoogleURLConnFactory( 5827): Using platform SSLCertificateSocketFactory
,D/LGDMClient( 6083): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6083): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6109 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6083): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/art     ( 3685): Explicit concurrent mark sweep GC freed 2047(78KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 863us total 96.946ms
I/jxcore-log( 5360): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5360): 
,I/LGDMClient( 6083): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/DriveInitializer( 5827): Awaiting to be initialized
W/ContextImpl( 6083): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,W/DriveInitializer( 5827): Background init thread started
E/LGDMClient( 6083): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6083): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6083): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6083): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6083): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5827): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 5809): propertyValue:false
D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/jxcore-log( 5360): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5360): 
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/PhenotypeConfigurator( 1730): Server returned 404
,I/NotificationManager(  838): android: cancelAsUser(2) by android
D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/jxcore-log( 5360): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5360): 
,W/DriveInitializer( 5827): Background init thread ended
I/AppUp4:AppBoxCP( 6109): onCreate
,W/AppUp4:DB( 6109):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6109):  setFingerPrint start
I/jxcore-log( 5360): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5360): 
I/AppUp4:DB( 6109):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/jxcore-log( 5360): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5360): 
,I/AppUp4:DB( 6109):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6109):  SDK version = 0
I/AppUp4:DB( 6109):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6109): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6109): [onReceive] BroadcastReceiver onReceive
I/jxcore-log( 5360): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5360): 
I/NetworkStateForAutoUpdateMonitor( 6109): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6109): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6109): [onReceive] request level :IDLE....
,D/ChimeraCfgMgr( 5827): Reading stored module config
D/ChimeraCfgMgr( 5827): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5827): Loading module APK com.google.android.play.games
,I/AppUp4:CustModeStarterReceiver( 6109): onReceive
I/AppUp4:CustModeStarterReceiver( 6109): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6109): Context : android.app.ReceiverRestrictedContext@295c1cf4
D/AppUp4:CustFacade( 6109): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6109): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6109): begin check event
I/AppUp4:CustModeStarterReceiver( 6109): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6109): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6109): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6109): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6109): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  838): Killing 5564:com.lge.sync/1000 (adj 15): empty #11
I/NotificationManager(  838): android: cancelAsUser(353845882) by android
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 5827): propertyValue:false
I/ActivityManager(  838): Process com.lge.qremote (pid 5659) has died
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_5564/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5698): Service.onUnbind: IControl
D/UEI.SmartControl( 5698): Service.onDestroy
D/UEI.SmartControl( 5698): Shutdown IRRCPlayer... 
W/irrc_jni( 5698): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5698): ~IrrcClient ++ 
D/irrcClient( 5698): ~IrrcClient -- 
W/irrc_jni( 5698): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5698): Blaster closed
D/UEI.SmartControl( 5698): Blaster closed
D/UEI.SmartControl( 5698): Shut down QS...
D/UEI.SmartControl( 5698): Stopped file observer...
,I/UEI.SmartControl( 5698): QS lib stop result = true
D/UEI.SmartControl( 5698): QS shutdown complete
I/LgeMiscReceiver( 3106): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3106): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3106): networkInfo.isConnected() = true
D/PhoneState( 3106): setPdpRejectCasuse : false
I/ActivityManager(  838): Process com.android.calendar (pid 5972) has died
,D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6165 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.595ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.611ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.416ms
,I/ActivityManager(  838): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6182 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{128c29e1 type 0 when 1453981590485 com.android.vending} when 1453981590485
I/GamesSyncServiceMain( 5827): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 5827): Failed to execute periodic sync, missing client context - aborting
I/ActivityManager(  838): Process com.lge.clock (pid 5920) has died
,I/NotificationManager( 5827): com.google.android.gms: cancel(10436) by com.google.android.gms
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  279): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/PhoneMonitor( 6165): Register our PhoneStateListener
,I/ActivityManager(  838): Process com.uei.lg.quicksetsdk.lite (pid 5698) has died
,D/MobileConnectivityChangeReceiver( 6165): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6165): onReceive CONNECTIVITY_CHANGE networkType=1
,D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  279): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
,V/DownloadManager( 3128): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/PhoneMonitor( 6165): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6165): [loadFeatureFromXml] *** start feature loading from xml
,V/DownloadManager( 3128): DownloadService onCreate
D/TelephonyAutoProfiling( 6165): [parse] Load xml
V/TelephonyAutoProfiling( 6165): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6165): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  838): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6220 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/NotificationManager( 3128): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3128): in removeSpuriousFiles
V/DownloadManager( 3128): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 5809): propertyValue:false
I/System.out( 5809): propertyValue:false
D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/DownloadManager( 3128): created cursor android.database.sqlite.SQLiteCursor@28a542c0 on behalf of 3128
D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/DownloadManager( 3128): DownloadService onStartCommand
V/DownloadManager( 3128): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3128): in trimDatabase
V/DownloadManager( 3128): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3128): created cursor android.database.sqlite.SQLiteCursor@274bf73e on behalf of 3128
D/Finsky  ( 6182): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
V/DownloadManager( 3128): created cursor android.database.sqlite.SQLiteCursor@18a1599f on behalf of 3128
,D/PhoneMonitor( 6165): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5827): Checkin interval check for package: unspecified last checkin: 1453902999990 min interval config: 0 actual interval: 78591373
,I/CheckinService( 5827): Disabling old GoogleServicesFramework version
V/DownloadManager( 3128): DownloadService onDestroy
,D/DrmBroadcastReceiver( 6220): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6220): 1  network is available. Sync DRM Time with NTP
D/WeatherAncestor( 2739): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:46:31
D/UpdateThreadPoolManager( 2739): 2 : This is isUpdating : false
D/WeatherAncestor( 2739): connectivity changed - connection : true
V/DrmService( 6220): Service onCreate
D/DrmService( 6220): Received new request = 2
,D/Weather_cast( 2739): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2739): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:46:31
D/WeatherService( 2739): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 6220): Start Sync process
D/DrmSntpClient( 6220): Server : 0
D/libc-netbsd( 6220): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6220): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6220): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6220): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  279): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6251 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2739): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WeatherService( 2739): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2739): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinService( 5827): Checking schedule, now: 1453981591586 next: 1453903029789
I/CheckinService( 5827): active receiver: enabled
,I/CheckinService( 5827): Preparing to send checkin request
I/EventLogService( 5827): Accumulating logs since 1453981570557
,D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5809): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5809): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Finsky  ( 6182): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6220): propertyValue:false
W/Settings( 6182): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6182): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6182): com.android.vending: cancel(-1050172287) by com.android.vending
W/ResourcesManager( 6251): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 6182): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/DownloadManager( 3128): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 6182): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6182): Skipping gmscore version check
V/DownloadManager( 3128): created cursor android.database.sqlite.SQLiteCursor@32917eb5 on behalf of 6182
I/art     (  838): Explicit concurrent mark sweep GC freed 28873(1357KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/34MB, paused 2.612ms total 177.361ms
,I/LGDrmClient( 6220): _DRM_ServiceGet() : Bind lgdrm service
D/Finsky  ( 6182): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/ILGDrmService(  290): eDRM_SetDRMTime +++
,I/LGDRM   (  290): [DRM] SET TIME : YR=2016, MON=1, DAY=28
I/LGDRM   (  290): [DRM] SET TIME : HR=11, MIN=46, SEC=30
V/ILGDrmService(  290): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6220): Synched
D/DrmService( 6220): Completed !! request = 2
D/DrmService( 6220): Request count = 0
V/DrmService( 6220): Service onDestroy
D/Finsky  ( 6182): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/CheckinRequestBuilder( 5827): Checkin reason type: 8 attempt count: 1
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
E/ActivityThread( 5827): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 6251): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6251): MmsConfig.loadMmsSettings
,W/art     ( 6063): Attempt to remove local handle scope entry from IRT, ignoring
I/Babel_SMS( 6251): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6251): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6251): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6251): MmsConfig.loadFromResources
E/Babel_SMS( 6251): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6251): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/libc-netbsd( 6063): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6063): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,E/BandwidthController(  279): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  279): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
D/Finsky  ( 6182): [740] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6182): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/SensorManager( 6251): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6251): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6251): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6251): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6251): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6251): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6251): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6251): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6251): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6251): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6251): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6251): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6251): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6251): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6251): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6251): found sensor: Motion Accel, handle=46
W/art     ( 6251): Suspending all threads took: 5.143ms
,I/art     ( 5827): Explicit concurrent mark sweep GC freed 31510(2MB) AllocSpace objects, 26(439KB) LOS objects, 40% free, 12MB/20MB, paused 2.039ms total 160.704ms
,W/Settings( 6251): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6251): startup - clean
I/art     ( 6251): CheckpointMarkThreadRoots callback created = 0xaaf404e0
I/art     ( 6251): CheckpointMarkThreadRoots callback created = 0xaaf404c0
,I/Babel   ( 6251): deleted: false for 0
,I/ActivityManager(  838): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6307 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager(  838): android: cancelAsUser(2126026182) by android
W/AudioCapabilities( 6251): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6251): Unsupported mime audio/adpcm
W/AudioCapabilities( 6251): Unsupported mime audio/g726
,W/AudioCapabilities( 6251): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6251): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6251): Unsupported mime video/mjpg
W/VideoCapabilities( 6251): Unsupported mime video/theora
,W/AudioCapabilities( 6251): Unsupported mime audio/evrc
,W/AudioCapabilities( 6251): Unsupported mime audio/qcelp
W/VideoCapabilities( 6251): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6251): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6251): Unsupported mime audio/qcelp
W/AudioCapabilities( 6251): Unsupported mime audio/evrc
I/NotificationManager(  838): android: cancelAsUser(353845882) by android
,W/VideoCapabilities( 6251): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6251): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6251): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6251): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6251): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6251): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  838): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6325 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 6251): onServiceConnected
W/Babel   ( 6251): Attempted to change video mute state without an active call.
I/NotificationManager( 6251): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6251): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6251): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6251): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6251): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6251): propertyValue:false
,I/ActivityManager(  838): Process com.google.android.music:main (pid 5776) has died
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/Babel   ( 6251): connection state changed from UNKNOWN to CONNECTED
,I/GAv4    ( 6307): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6307):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6307):   adb logcat -s GAv4
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  838): Killing 5809:com.google.android.youtube/u0a100 (adj 15): empty #11
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/ActivityManager(  838): Application dead when creating service ServiceRecord{1f4f978f u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
W/libprocessgroup(  838): failed to open /acct/uid_10100/pid_5809/cgroup.procs: No such file or directory
,W/ActivityManager(  838): Scheduling restart of crashed service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator in 1000ms
W/ActivityManager(  838): Scheduling restart of crashed service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator in 4000ms
W/ActivityManager(  838): Spurious death for ProcessRecord{18f28dc8 0:com.google.android.youtube/u0a100}, curProc for 5809: null
W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAv4    ( 6307): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6307): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6307): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/Gmail   ( 6325): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6325): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/InstanceID/Rpc( 5827): Found 10006
,I/ActivityManager(  838): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6370 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6325): getAccountsCursor
,E/Gmail   ( 6325): Error finding the version of the Email provider.....
E/Gmail   ( 6325): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6325): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6325): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6325): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6325): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6325): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6325): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6325): We do not support migrating this version of the Email provider.
W/Gmail   ( 6325): Sync started for account: account:61035162
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6325): Observing account changes for notifications
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6370): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6370): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6370): VM with version 2.1.0 has multidex support
I/MultiDex( 6370): install
I/MultiDex( 6370): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  838): Process com.lge.email (pid 5838) has died
,I/Gmail   ( 6325): notifyAccountChanged
,I/Gmail   ( 6325): getAccountsCursor
I/Gmail   ( 6325): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  838): Process com.android.gallery3d (pid 5872) has died
I/Gmail   ( 6325): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6325): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/JNIHelp ( 6370): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Gmail   ( 6325): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6325): notifyAccountChanged
,W/ActivityThread( 6370): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6370): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e285131: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6370): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6370): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6370): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/WebViewFactory( 6307): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/art     ( 6370): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6370): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3685): Explicit concurrent mark sweep GC freed 2997(122KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 5.962ms total 71.155ms
I/LibraryLoader( 6307): Time to load native libraries: 1 ms (timestamps 3252-3253)
I/LibraryLoader( 6307): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6307): Binding Chromium to main looper Looper (main, tid 1) {3fbee8a1}
,I/LibraryLoader( 6307): Expected native library version number "",actual native library version number ""
I/ActivityManager(  838): Process com.qualcomm.timeservice (pid 6035) has died
I/chromium( 6307): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6307): Initializing chromium process, singleProcess=true
,W/art     ( 6307): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6307): ApplicationContext is null in ApplicationStatus
I/Gmail   ( 6325): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/NativeLibraryUtils( 6370): Install completed successfully. count=14 extracted=0
W/chromium( 6307): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6307): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6307): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6307): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6307): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6307): Remote Branch: 
I/Adreno-EGL( 6307): Local Patches: 
I/Adreno-EGL( 6307): Reconstruct Branch: 
D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
I/ActivityManager(  838): Process com.lge.appbox.client (pid 6109) has died
,I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
,D/ChimeraCfgMgr( 5827): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5827): Module APK com.google.android.play.games already loaded
W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
I/BackgroundMemoryTrimmer( 1937): Trimming objects from memory, since app is in the background.
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=265452541
,V/AudioPolicyService(  283): registerClient() client 0xb551c6a0, uid 10079
,W/AudioManagerAndroid( 6307): Requires BLUETOOTH permission
I/ActivityManager(  838): Process com.lge.lgdmsclient (pid 6083) has died
,I/art     (  838): Explicit concurrent mark sweep GC freed 20123(894KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.355ms total 192.479ms
,I/Gmail   ( 6325): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15750, normalSync: true
,I/ActivityManager(  838): Process com.google.android.setupwizard (pid 6165) has died
,I/PhoneApp( 1749): onTrimMemory: 15
I/PhoneApp( 1749): trim memory
I/NSApplication( 6307): Starting up...
I/GoogleURLConnFactory( 6370): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 6370): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6370): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6370): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6370): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6370): propertyValue:false
I/ActivityManager(  838): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6441 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAv4-SVC( 5827): Google Analytics 8.4.89 is starting up.
,W/ResourcesManager( 6325): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6325): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  838): Process com.google.android.talk (pid 6251) has died
,I/art     ( 6063): CheckpointMarkThreadRoots callback created = 0xb04e79f0
,W/System  ( 6325): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6325): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6063): CheckpointMarkThreadRoots callback created = 0xb04e7830
I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/libc-netbsd( 6325): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6325): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6325): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6325): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10053
D/DnsProxyListener(  279): App 10053 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/iu.SyncManager( 5827): SYNC; picasa accounts
,D/NetworkLogImpl( 5827): Loaded NetworkSpeedPredictor
I/iu.Environment( 5827): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5827): num queued entries: 0
I/iu.UploadsManager( 5827): num updated entries: 0
I/iu.SyncManager( 5827): NEXT; no task
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5827): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6479 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  838): tsOffsetIs: Apps: 114891119180; DSPS: 3863371; Offset : -3020463204
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
E/lowmemorykiller(  243): Error writing /proc/6182/oom_score_adj; errno=22
,E/lowmemorykiller(  243): Error writing /proc/6182/oom_score_adj; errno=22
E/lowmemorykiller(  243): Error writing /proc/6182/oom_score_adj; errno=22
,W/ResourcesManager( 6479): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Process com.android.vending (pid 6182) has died
,W/IcingInternalCorpora( 5827): getNumBytesRead when not calculated.
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ae43d2f:true
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,I/ActivityManager(  838): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6503 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/MusicWidget( 2700): mDelayedStopHandler : unbind
,I/MusicBrowser( 2111): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2111): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2111): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2111): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2111): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2111): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  838):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@f78068dcom.lge.music.MediaPlaybackService$6@627f042
,D/MusicBrowser( 2111): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@d981460
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2111): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2111): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2111): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2111): reset
V/MediaPlayer[Native]( 2111): setListener
V/MediaPlayer[Native]( 2111): disconnect
V/MediaPlayer[Native]( 2111): destructor
,V/AudioFlinger(  283): releasing 19 from 2111 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2111): disconnect
D/MusicBrowser( 2111): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2111): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2111): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2111): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2111): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2111): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2111): [SmartShareManagerClient] unregisterListener: 524392531
W/SmartShareClient( 2111): [SmartShareManagerClient] unregisterListener invalid listener: 524392531
I/SmartShareClient( 2111): [SmartShareManagerClient] terminate service: 2111/MediaPlaybackService/521152518
E/HomeCloudIF( 2111): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2111): [SmartShareManagerClient] unbindService context:android.app.Application@2e895590
V/CloudHub( 2111): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2111): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2111): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/DigitalAppWidgetProvider( 6503): onReceive: android.intent.action.ALARM_CHANGED
I/MusicBrowser( 2111): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2111): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,D/WeatherAncestor( 2739): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:46:36
D/UpdateThreadPoolManager( 2739): 2 : This is isUpdating : false
D/Weather_cast( 2739): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2739): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:46:36
I/CloudHub( 2111): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29988
D/WeatherService( 2739): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2739): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2739): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2739): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/ContextImpl( 3365): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/LocationInitializer( 5827): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1730): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6536 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6479): Create singleton instance
,I/AudioManager( 6479): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6536): Quickset Services start...
,I/UEI.SmartControl( 6536): Manufacture = LGE
D/UEI.SmartControl( 6536): File observer start...
E/UEI.SmartControl( 6536): IR Port is disabled: false
D/UEI.SmartControl( 6536): Starting file observer...
D/UEI.SmartControl( 6536): Extracting JNI libs...
D/UEI.SmartControl( 6536): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 6536): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6536): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6536): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6536): --- Selecting new region: 2
,I/UEI.SmartControl( 6536): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6536): Platform has CIR...
D/UEI.SmartControl( 6536): NO CIR support, need to check package...
I/UEI.SmartControl( 6536): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6536): QS Service created
,I/ActivityManager(  838): Process com.google.android.apps.magazines (pid 6307) has died
,I/BackgroundMemoryTrimmer( 1937): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
,E/UEI.SmartControl( 6536): QS start get config
,D/UEI.SmartControl( 6536): Loading JNI Libs...
D/UEI.SmartControl( 6536):  configuring local db...
,I/ActivityManager(  838): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6565 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.197ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.609ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 25.101ms
,D/UEI.SmartControl( 6536):  ---- Has DB8: true
,D/UEI.SmartControl( 6536): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6536): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6536): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6536): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6536): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6536): IrrcClient ++ 
D/irrcClient( 6536): getIrrcService ++ 
D/irrcClient( 6536): getIrrcService -- 
D/irrcClient( 6536): IrrcClient -- 
W/irrc_jni( 6536): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6536): Services init done
D/UEI.SmartControl( 6536): QS Service init finished
,D/UEI.SmartControl( 6536): QS Service version name: 0.1.73
D/UEI.SmartControl( 6536): QS Service version code: 1073
D/UEI.SmartControl( 6536): Service requested: Control
I/UEI.SmartControl( 6536): Device manager: loading config....
D/UEI.SmartControl( 6536): Config is loaded...
,W/ResourcesManager( 6565): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6565): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6536): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6536): Service.onTrimMemory: 10
E/UEI.SmartControl( 6536): Setup service releasing memory...
D/UEI.SmartControl( 6536): -----IControl: 11
D/UEI.SmartControl( 6536):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 6536): Caller: com.lge.qremote
I/UEI.SmartControl( 6536): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6536): ------------ IControl registerCallback...
I/UEI.SmartControl( 6536): Registering callback...
,D/UEI.SmartControl( 6536): -----IControl: 19
D/UEI.SmartControl( 6536): Caller: com.lge.qremote
I/UEI.SmartControl( 6536): Registering Services Ready callback...
I/UEI.SmartControl( 6536): Notify client services are ready...
D/UEI.SmartControl( 6536): -----IControl: 8
D/UEI.SmartControl( 6536): Caller: com.lge.qremote
I/AudioManager( 6479): getMode name:com.lge.qremote
,I/art     ( 6536): Explicit concurrent mark sweep GC freed 10614(757KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 383us total 54.593ms
,D/UEI.SmartControl( 6536): Internal service binding...
V/JNIHelp ( 6565): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6325): propertyValue:false
,D/libc-netbsd( 6325): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6325): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AudioManager( 6479): getMode name:com.lge.qremote
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/AudioManager( 6479): getMode name:com.lge.qremote
W/System  ( 6565): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6565): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6325): CheckpointMarkThreadRoots callback created = 0xaaf62330
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/NotificationManager( 6063): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
D/libc-netbsd( 6370): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6370): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6370): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6370): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6325): CheckpointMarkThreadRoots callback created = 0xb042d920
I/NotificationManager(  838): android: cancelAsUser(2145784878) by android
,I/art     ( 6325): WaitForGcToComplete blocked for 65.974ms for cause HomogeneousSpaceCompact
I/ActivityManager(  838): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6604 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  838): Process com.android.chrome (pid 6441) has died
,I/GCM     ( 1730): GCM config loaded
,D/libc-netbsd( 6325): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6325): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/VacuumService( 1730): Vacuum at: now=1453981598328 tag=VacuumService
,I/art     ( 6565): CheckpointMarkThreadRoots callback created = 0xaaf38690
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6604): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6604): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6604): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6604):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6604):   adb logcat -s GAv4
I/art     ( 6565): CheckpointMarkThreadRoots callback created = 0xb4958de0
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6604): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6604): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6604): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GAV2    ( 6325): Thread[GAThread,5,main]: No campaign data found.
W/GAv4    ( 6604): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6604): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/YouTube MDX( 6565): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 6565): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6565): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 6565): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6565): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 73777(4MB) AllocSpace objects, 45(743KB) LOS objects, 39% free, 13MB/23MB, paused 3.568ms total 188.651ms
,I/dex2oat ( 6664): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1927479190.jar --oat-fd=34 --oat-location=/data/data/com.google.android.youtube/cache/ads1927479190.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     (  838): Explicit concurrent mark sweep GC freed 23869(1112KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.742ms total 159.477ms
,I/art     ( 6370): CheckpointMarkThreadRoots callback created = 0xb042dc00
I/art     ( 6370): CheckpointMarkThreadRoots callback created = 0xb042dbf0
,I/dex2oat ( 6664): dex2oat took 191.334ms (threads: 4)
,I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6678 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/WebViewFactory( 6604): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6604): Time to load native libraries: 2 ms (timestamps 8383-8385)
I/LibraryLoader( 6604): Expected native library version number "",actual native library version number ""
,I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:39.156 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WebViewChromiumFactoryProvider( 6604): Binding Chromium to main looper Looper (main, tid 1) {2cae3908}
,I/LibraryLoader( 6604): Expected native library version number "",actual native library version number ""
I/chromium( 6604): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6604): Initializing chromium process, singleProcess=true
,W/art     ( 6604): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6604): ApplicationContext is null in ApplicationStatus
W/chromium( 6604): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6604): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6604): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6604): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6604): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6604): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6604): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6604): Remote Branch: 
I/Adreno-EGL( 6604): Local Patches: 
I/Adreno-EGL( 6604): Reconstruct Branch: 
I/NotificationManager( 6565): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ResourcesManager( 6678): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 6565): Found 10006
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,V/AudioPolicyService(  283): registerClient() client 0xb39b6e40, uid 10079
,W/AudioManagerAndroid( 6604): Requires BLUETOOTH permission
I/NSApplication( 6604): Starting up...
,D/WVCdm   (  283): Instantiating CDM.
I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6565): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
V/AudioFlinger(  283): 2111 died, releasing its sessions
V/AudioFlinger(  283):  pid 1749 @ 0
V/AudioFlinger(  283):  pid 3106 @ 1
V/AudioFlinger(  283):  pid 3106 @ 2
,I/SyncAdapterService( 6604): Ignoring sync request for non-current account
I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=1725758658
I/ActivityManager(  838): Process com.lge.music (pid 2111) has died
E/lowmemorykiller(  243): Error writing /proc/6220/oom_score_adj; errno=22
,I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
D/UEI.SmartControl( 6536): Service.onTrimMemory: 60
E/UEI.SmartControl( 6536): Setup service releasing memory...
I/BackgroundMemoryTrimmer( 1937): Trimming objects from memory, since app is in the background.
,I/ActivityManager(  838): Process com.lge.drmservice (pid 6220) has died
,I/NotificationManager( 6325): com.google.android.gm: cancel(10436) by com.google.android.gm
,E/lowmemorykiller(  243): Error writing /proc/6479/oom_score_adj; errno=22
,I/NotificationManager( 6565): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/NotificationManager(  838): android: cancelAsUser(-701419433) by android
E/lowmemorykiller(  243): Error writing /proc/6479/oom_score_adj; errno=22
D/libc-netbsd( 6565): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6565): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6565): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6565): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  279): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6565): propertyValue:false
D/libc-netbsd( 6565): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6565): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  838): Process com.lge.qremote (pid 6479) has died
I/BackgroundMemoryTrimmer( 1937): Trimming objects from memory, since app is in the background.
D/UEI.SmartControl( 6536): Service.onTrimMemory: 60
E/UEI.SmartControl( 6536): Setup service releasing memory...
I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
,I/Babel_SMS( 6678): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6678): MmsConfig.loadMmsSettings
,D/libc-netbsd( 6565): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6565): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel_SMS( 6678): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6678): MmsConfig.loadFromDatabase
,I/art     ( 6678): CheckpointMarkThreadRoots callback created = 0xaaf23f70
,E/Babel_SMS( 6678): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6678): MmsConfig.loadFromResources
E/Babel_SMS( 6678): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6678): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6678): CheckpointMarkThreadRoots callback created = 0xaaf23f50
,I/ActivityManager(  838): Process com.lge.clock (pid 6503) has died
,I/PhoneApp( 1749): onTrimMemory: 15
I/PhoneApp( 1749): trim memory
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SensorManager( 6678): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6678): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6678): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6678): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6678): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6678): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6678): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6678): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6678): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6678): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6678): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6678): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6678): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6678): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6678): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6678): found sensor: Motion Accel, handle=46
W/Settings( 6678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6678): startup - clean
,I/Babel   ( 6678): deleted: false for 0
,W/AudioCapabilities( 6678): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6678): Unsupported mime audio/adpcm
W/AudioCapabilities( 6678): Unsupported mime audio/g726
W/AudioCapabilities( 6678): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6678): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6678): Unsupported mime video/mjpg
W/VideoCapabilities( 6678): Unsupported mime video/theora
I/NotificationManager(  838): android: cancelAsUser(-1874035846) by android
,W/AudioCapabilities( 6678): Unsupported mime audio/evrc
,W/AudioCapabilities( 6678): Unsupported mime audio/qcelp
W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6678): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6678): Unsupported mime audio/qcelp
W/AudioCapabilities( 6678): Unsupported mime audio/evrc
,W/VideoCapabilities( 6678): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6678): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6678): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6678): onServiceConnected
W/Babel   ( 6678): Attempted to change video mute state without an active call.
,I/NotificationManager( 6678): com.google.android.talk: cancel(10436) by com.google.android.talk
I/PeopleSync( 5827): onPerformSync() [5005f081]
,I/PeopleDatabaseHelper( 5827): cleanUpNonGplusAccounts done.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 5360): Test app app.js loaded
I/jxcore-log( 5360): 
,I/art     ( 6325): Explicit concurrent mark sweep GC freed 11954(422KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 10MB/14MB, paused 1.197ms total 79.114ms
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 5360): BLE advertisement is supported
I/jxcore-log( 5360): 
,I/Gmail   ( 6325): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15845, normalSync: true
,I/PeopleSync( 5827): Setting subscription: result=true [5005f081]
I/Gmail   ( 6325): lowestBackward conversation id 0
I/PeopleSync( 5827): Starting sync, feed=null [5005f081]
,I/art     ( 3685): Explicit concurrent mark sweep GC freed 3119(122KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.218ms total 39.140ms
,I/chromium( 5360): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  838): Process com.google.android.youtube (pid 6565) has died
,I/BackgroundMemoryTrimmer( 1937): Trimming objects from memory, since app is in the background.
D/UEI.SmartControl( 6536): Service.onTrimMemory: 60
E/UEI.SmartControl( 6536): Setup service releasing memory...
I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
,I/WVCdm   (  283): CdmEngine::CloseSession
I/WVCdm   (  283): L3 Terminate.
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/Icing   ( 5827): Storage manager: low false usage 1.71MB avail 2.36GB capacity 4.06GB
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/UEI.SmartControl( 6536): Service.onTrimMemory: 80
E/UEI.SmartControl( 6536): Setup service releasing memory...
,D/UEI.SmartControl( 6536): Service.onTrimMemory: 80
E/UEI.SmartControl( 6536): Setup service releasing memory...
W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6789 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/BackgroundMemoryTrimmer( 1937): Trimming objects from memory, since app is in the background.
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 6678): com.google.android.talk: cancel(8) by com.google.android.talk
,D/administrator(  838): Handling package changes for user 0
W/ResourcesManager( 6678): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6678): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/BaseAppContext( 5827): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/dex2oat ( 6788): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=43 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,V/JNIHelp ( 6678): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6789): onCreate
,W/AppUp4:DB( 6789):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6789):  setFingerPrint start
I/AppUp4:DB( 6789):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6789):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6789):  SDK version = 0
I/AppUp4:DB( 6789):  beforefinger == newfinger no write in DB
W/System  ( 6678): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6678): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 6788): dex2oat took 248.706ms (threads: 4)
,I/Adreno-EGL( 6370): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6370): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6370): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6370): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6370): Remote Branch: 
I/Adreno-EGL( 6370): Local Patches: 
I/Adreno-EGL( 6370): Reconstruct Branch: 
,I/ActivityManager(  838): Process com.uei.lg.quicksetsdk.lite (pid 6536) has died
,I/PhoneApp( 1749): onTrimMemory: 15
,I/PhoneApp( 1749): trim memory
I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:46:42.357 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/AppUp4:AppBoxApplication( 6789): AppBoxApplication onCreate()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     ( 5827): Explicit concurrent mark sweep GC freed 26295(1977KB) AllocSpace objects, 32(512KB) LOS objects, 25% free, 13MB/17MB, paused 1.404ms total 324.637ms
,I/NotificationService(  838): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  838): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Process com.google.android.apps.magazines (pid 6604) has died
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
I/AppUp4:CustModeStarterReceiver( 6789): onReceive
I/AppUp4:CustModeStarterReceiver( 6789): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
I/BackupManagerService(  838): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/AppUp4:CustFacade( 6789): Context : android.app.ReceiverRestrictedContext@12eaf2e1
,D/AppUp4:CustFacade( 6789): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6789): isSimDevice : true
V/BackupManagerService(  838): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  838): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1e5695dc
D/AppUp4:CustModeStarterReceiver( 6789): begin check event
I/AppUp4:CustModeStarterReceiver( 6789): Event For Nothing, skip.
W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,I/Adreno-EGL( 6370): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6370): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6370): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6370): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6370): Remote Branch: 
I/Adreno-EGL( 6370): Local Patches: 
I/Adreno-EGL( 6370): Reconstruct Branch: 
I/ActivityManager(  838): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6821 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/PeopleSync( 5827): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourceType(  838): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ResourcesManager( 6821): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6821): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6821): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
,I/Adreno-EGL( 6370): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6370): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6370): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6370): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6370): Remote Branch: 
I/Adreno-EGL( 6370): Local Patches: 
I/Adreno-EGL( 6370): Reconstruct Branch: 
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Icing   ( 5827): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 6821): Total System Memory = 906309632
I/GalleryUtils( 6821): Application Heap = 96 MB
,I/AppConfig( 6821): App Tier : NOT_DEF
D/SystemHelper( 6821): region [EU], country [EU], operator [OPEN], sub-operator []
,D/charger_monitor(  483): init target 500000
,D/charger_monitor(  483): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/art     (  838): Explicit concurrent mark sweep GC freed 36143(1762KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.733ms total 219.289ms
,I/ActivityManager(  838): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6844 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/LocationProviderProxy(  838): applying state to connected service
D/WifiController(  838): battery changed pluggedType: 2
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,W/ResourcesManager( 6844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6844): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6844): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6844): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6844): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/Icing   ( 5827): Internal init done: storage state 0
,I/Icing   ( 5827): Post-init done
,I/NotificationManager( 6325): com.google.android.gm: cancel(10436) by com.google.android.gm
,I/NotificationManager( 6325): com.google.android.gm: cancel(10436) by com.google.android.gm
I/Gmail   ( 6325): notifyAccountChanged
,I/Gmail   ( 6325): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6325): notifyAccountChanged
,I/Gmail   ( 6325): getAccountsCursor
W/Gmail   ( 6325): Sync complete for account: account:61035162
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  838): android: cancelAsUser(1479798955) by android
,I/SystemConfig( 6844): BUILD Country: EU
I/SystemConfig( 6844): BUILD Operator: OPEN
,I/NotificationManager(  838): android: cancelAsUser(1500439826) by android
,I/CheckinRequestBuilder( 5827): Classify the device as Phone.
I/ActivityManager(  838): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6868 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6887 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6844): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6844): existFile = false
I/SystemConfig( 6844): canReadFile = false
I/SystemConfig( 6844): systemFeature RCS result false
D/SystemConfig( 6844): refreshRcsSupport() :false
,I/ActivityManager(  838): Process com.android.gallery3d (pid 6821) has died
,I/BackgroundMemoryTrimmer( 1937): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1749): onTrimMemory: 10
I/PhoneApp( 1749): trim memory
D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 5827): propertyValue:false
I/LockScreenSettings( 6887): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LockScreenSettings( 6887): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6887): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6887): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 6887): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6887): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/MusicStore( 6868): Database version: 120
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/ActivityManager(  838): Process com.android.contacts (pid 6844) has died
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 84 ms] updated apps [took 82 ms] 
,I/CheckinTask( 5827): Sending checkin request (10141 bytes)
I/ActivityManager(  838): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6914 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6868): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/BackgroundMemoryTrimmer( 1937): Trimming objects from memory, since app is in the background.
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6868): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6868): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6868): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6868): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 5827): propertyValue:false
V/JNIHelp ( 6868): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5827): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5827): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ActivityThread( 6868): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6868): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bd71250: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6868): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6868): GMSCore installation verified
I/ConfigStore( 6868): Config Database version: 1
,I/Icing   ( 5827): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,D/Finsky  ( 6914): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/Icing   ( 5827): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
,I/MediaRouter( 6868): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 6868): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6868): Using platform SSLCertificateSocketFactory
I/art     ( 6868): CheckpointMarkThreadRoots callback created = 0xb042d380
D/Finsky  ( 6914): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/MusicLifecycle( 6868): Sync started
,I/NetworkMonitor( 6868): type=WIFI subType= reason=null isConnected=true
I/art     ( 6868): CheckpointMarkThreadRoots callback created = 0xb042d360
W/Settings( 6914): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6914): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6914): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3128): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  838): Process com.lge.appbox.client (pid 6789) has died
,I/PhoneApp( 1749): onTrimMemory: 15
I/PhoneApp( 1749): trim memory
I/NetworkMonitor( 6868): type=WIFI subType= reason=null isConnected=true
,D/Ads     ( 6914): Skipping gmscore version check
I/art     ( 3128): Explicit concurrent mark sweep GC freed 5607(409KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/10MB, paused 584us total 69.332ms
D/Finsky  ( 6914): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6914): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3128): created cursor android.database.sqlite.SQLiteCursor@118c494a on behalf of 6914
I/GHttpClientFactory( 6868): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6868): Using platform SSLCertificateSocketFactory
D/PackageBroadcastService( 5827): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6968 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5827): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 6914): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 5827): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 6914): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/NotificationManager( 6868): com.google.android.music: cancel(1061) by com.google.android.music
W/ResourcesManager( 6968): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/libc-netbsd( 6868): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6868): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6868): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6868): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10081
D/DnsProxyListener(  279): App 10081 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
,I/CheckinResponseProcessor( 5827): From server: 2 gservices updates and 1 deletes
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6868): propertyValue:false
I/art     (  838): Explicit concurrent mark sweep GC freed 23826(1092KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.246ms total 148.648ms
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b368d63:true
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6996 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/CertBlacklister(  838): Certificate blacklist changed, updating...
,I/CertBlacklister(  838): Certificate blacklist updated
I/GservicesProvider( 3685): main difference update completed
,I/CheckinRequestBuilder( 5827): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5827): Failed to find provider info for com.google.android.wearable.settings
V/LGMDMManager( 6968): Create singleton instance
,D/UEI.SmartControl( 6996): Quickset Services start...
I/art     ( 3685): Explicit concurrent mark sweep GC freed 8969(438KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 497us total 32.417ms
,I/UEI.SmartControl( 6996): Manufacture = LGE
D/UEI.SmartControl( 6996): File observer start...
E/UEI.SmartControl( 6996): IR Port is disabled: false
D/UEI.SmartControl( 6996): Starting file observer...
D/UEI.SmartControl( 6996): Extracting JNI libs...
D/UEI.SmartControl( 6996): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6968): getMode name:com.lge.qremote
,I/ActivityManager(  838): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=7016 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.637ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 22.632ms
,E/lowmemorykiller(  243): Error writing /proc/6063/oom_score_adj; errno=22
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 356us total 21.049ms
E/lowmemorykiller(  243): Error writing /proc/6063/oom_score_adj; errno=22
E/lowmemorykiller(  243): Error writing /proc/6063/oom_score_adj; errno=22
,D/UEI.SmartControl( 6996): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6996): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6996): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6996): --- Selecting new region: 2
I/UEI.SmartControl( 6996): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6996): Platform has CIR...
D/UEI.SmartControl( 6996): NO CIR support, need to check package...
I/UEI.SmartControl( 6996): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6996): QS Service created
I/ActivityManager(  838): Process com.google.android.apps.plus (pid 6063) has died
,I/PhoneApp( 1749): onTrimMemory: 15
I/PhoneApp( 1749): trim memory
E/UEI.SmartControl( 6996): QS start get config
,D/UEI.SmartControl( 6996): Loading JNI Libs...
,D/UEI.SmartControl( 6996):  configuring local db...
I/CheckinRequestBuilder( 5827): Classify the device as Phone.
,I/ActivityManager(  838): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=7044 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd( 6868): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6868): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 5827): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5827): Checking schedule, now: 1453981605981 next: 1454508854951
I/CheckinService( 5827): active receiver: disabled
,D/CheckinService( 5827): Recording last checkin time for package unspecified as 1453981606038
,D/UEI.SmartControl( 6996):  ---- Has DB8: true
,D/UEI.SmartControl( 6996): QS start statue = true Error code = 0
D/UEI.SmartControl( 6996): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6996): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6996): IRRCDataComm has AudioManager!!!!.
E/UpdateRequestReceiver( 7044): Received malformed URL while handling Gservices.CHANGED_ACTION
W/irrc_jni( 6996): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6996): IrrcClient ++ 
D/irrcClient( 6996): getIrrcService ++ 
,D/irrcClient( 6996): getIrrcService -- 
D/irrcClient( 6996): IrrcClient -- 
W/irrc_jni( 6996): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6996): Services init done
I/UEI.SmartControl( 6996): Device manager: loading config....
D/UEI.SmartControl( 6996): QS Service init finished
,D/UEI.SmartControl( 6996): QS Service version name: 0.1.73
D/UEI.SmartControl( 6996): QS Service version code: 1073
E/UpdateRequestReceiver( 7044): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/UEI.SmartControl( 6996): Service requested: Control
E/UpdateRequestReceiver( 7044): Received malformed URL while handling Gservices.CHANGED_ACTION
D/UEI.SmartControl( 6996): Config is loaded...
E/UpdateRequestReceiver( 7044): Received malformed URL while handling Gservices.CHANGED_ACTION
D/UEI.SmartControl( 6996):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6996): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6996): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6996): Service.onTrimMemory: 15
E/UEI.SmartControl( 6996): Setup service releasing memory...
D/UEI.SmartControl( 6996): -----IControl: 11
,D/UEI.SmartControl( 6996): Caller: com.lge.qremote
,D/UEI.SmartControl( 6996): ------------ IControl registerCallback...
I/UEI.SmartControl( 6996): Registering callback...
I/CheckinService( 5827): Checkin interval check for package: unspecified last checkin: 1453981606038 min interval config: 0 actual interval: 148
D/UEI.SmartControl( 6996): -----IControl: 19
D/UEI.SmartControl( 6996): Caller: com.lge.qremote
I/UEI.SmartControl( 6996): Registering Services Ready callback...
I/UEI.SmartControl( 6996): Notify client services are ready...
D/UEI.SmartControl( 6996): -----IControl: 8
D/UEI.SmartControl( 6996): Caller: com.lge.qremote
,I/Icing   ( 5827): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/GservicesUpdateTask( 1937): Updating Gservices keys
I/SystemUpdateService( 5827): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/CheckinService( 5827): Checking schedule, now: 1453981606238 next: 1454508854951
I/CheckinService( 5827): active receiver: disabled
,D/SystemUpdateService( 5827): onCreate
I/art     ( 6996): Explicit concurrent mark sweep GC freed 10609(756KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 1.960ms total 79.750ms
D/UEI.SmartControl( 6996): Internal service binding...
,D/SystemUpdateService( 5827): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/Icing   ( 5827): Loaded CLD2 Version V2.0 - 20141016
,I/SystemUpdateService( 5827): cancelUpdate (empty URL)
I/SystemUpdateService( 5827): active receiver: disabled
I/NotificationManager( 5827): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 5827): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/Icing   ( 5827): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     ( 5827): Explicit concurrent mark sweep GC freed 45826(2MB) AllocSpace objects, 22(352KB) LOS objects, 24% free, 14MB/18MB, paused 1.141ms total 98.005ms
,W/SQLiteConnectionPool( 5827): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     ( 3685): Explicit concurrent mark sweep GC freed 4427(198KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 396us total 26.003ms
,D/libc-netbsd( 6868): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6868): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 3685): Explicit concurrent mark sweep GC freed 2795(106KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 392us total 30.828ms
,D/SystemUpdateService( 5827): onDestroy
,E/DynamiteModule( 5827): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5827): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5827): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5827): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5827): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5827): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5827): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5827): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5827): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5827): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5827): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5827): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5827): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5827): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5827): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5827): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5827): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5827): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5827): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5827): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5827): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5827): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5827): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5827): 		... 17 more
E/DynamiteModule( 5827): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 5827): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 5827): Selected local version of com.google.android.gms.flags
D/SystemEventReceiver( 5827): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5827): Updating ocr activity enabled=false
I/NotificationManager(  838): android: cancelAsUser(148851818) by android
,I/PeopleSync( 5827): Sync finished, successful=false, took 4428ms
W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
D/OcrModelManager( 5827): Updating downloaded model state (gservices changed)
,I/art     ( 3685): Explicit concurrent mark sweep GC freed 2759(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 843us total 25.063ms
,I/MusicSyncAdapter( 6868): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,I/MusicSyncAdapter( 6868): Periodic update
I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
,I/PeopleSync( 5827): ***Sync canceled***, duration: 6067 [5005f081]
D/SyncManager(  838): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 49925, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,W/MusicApiClient( 6868): Activity events list is null or empty. Skip reporting.
,I/NotificationManager(  838): android: cancelAsUser(148851818) by android
,I/MusicLifecycle( 6868): Sync ended
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 29406(1788KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 13MB/23MB, paused 1.219ms total 117.856ms
,I/art     (  838): Explicit concurrent mark sweep GC freed 20241(990KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.275ms total 145.974ms
,D/SyncManager(  838): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 120191, mTimeoutStartTime 120191, mHistoryRowId 14, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 158687, reason: Periodic
I/NotificationManager(  838): android: cancelAsUser(-1123058983) by android
,I/ActivityManager(  838): Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=7118 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,W/ResourcesManager( 7118): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/GCM     ( 1730): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 5827): Explicit concurrent mark sweep GC freed 11260(835KB) AllocSpace objects, 12(192KB) LOS objects, 24% free, 14MB/19MB, paused 1.198ms total 76.885ms
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
E/App     ( 7118): [App][onCreate()] 4.40.23
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,W/BaseAppContext( 5827): Using Auth Proxy for data requests.
W/BaseAppContext( 5827): Using Auth Proxy for data requests.
,I/art     ( 3685): Explicit concurrent mark sweep GC freed 2699(105KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.669ms total 53.668ms
,I/NotificationManager(  838): android: cancelAsUser(-379682945) by android
I/ActivityManager(  838): Killing 6678:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10061/pid_6678/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): init target 500000
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  483): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/AccountManager( 7118): setSyncFrequency
,D/DriveSyncService( 7118): onCreate
D/DriveSyncService( 7118): onBind
,D/DriveSyncAdapter( 7118): onPerformSync() START
D/DriveSyncAdapter( 7118): Not added account. Stop
I/NotificationManager(  838): android: cancelAsUser(1312559638) by android
,I/ActivityManager(  838): Killing 6887:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10069/pid_6887/cgroup.procs: No such file or directory
,I/GCoreUlr( 1730): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
I/GCoreUlr( 1730): DispatchingService.onCreate()
I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7147 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/GCoreUlr( 1730): Uploading GCM registration ID for account#2#
,I/GCoreUlr( 1730): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ActivityManager(  838): Killing 6325:com.google.android.gm/u0a53 (adj 15): empty #11
,W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
W/libprocessgroup(  838): failed to open /acct/uid_10053/pid_6325/cgroup.procs: No such file or directory
,E/ctxmgr  ( 1730): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/PhoneMonitor( 7147): Register our PhoneStateListener
,V/SetupWizard( 7147): Connected to Gservices successfully
,D/PhoneMonitor( 7147): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/AudioManager( 6968): getMode name:com.lge.qremote
,V/TelephonyAutoProfiling( 7147): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7147): [parse] Load xml
V/TelephonyAutoProfiling( 7147): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7147): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7147): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     ( 1730): Explicit concurrent mark sweep GC freed 14997(912KB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 14MB/23MB, paused 2.429ms total 94.984ms
W/BaseAppContext( 1730): Using Auth Proxy for data requests.
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/BaseAppContext( 1730): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/art     ( 3685): Explicit concurrent mark sweep GC freed 3214(129KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 2.543ms total 31.342ms
I/GCoreUlr( 1730): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1730): Unbound from all location providers
I/GCoreUlr( 1730): Place inference reporting - stopped
W/ctxmgr  ( 1730): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,I/GCoreUlr( 1730): DispatchingService.onDestroy()
I/GCoreUlr( 1730): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1730): Unbound from all location providers
I/GCoreUlr( 1730): Place inference reporting - stopped
,E/ctxmgr  ( 1730): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6868): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6868): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,I/AudioManager( 6968): getMode name:com.lge.qremote
I/NotificationManager(  838): android: cancelAsUser(-1548111331) by android
,I/AudioManager( 6968): getMode name:com.lge.qremote
,I/MusicLeanback( 6868): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6868): Stop autocaching.
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  838): android: cancelAsUser(898701380) by android
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6868): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/WearableService( 1730): callingUid 10006, callindPid: 1730
I/NotificationManager(  838): android: cancelAsUser(-1816247584) by android
,E/GmsUtils( 6868): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6868): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/Auth.Api.Credentials( 5827): [CredentialSyncAdapter] Unknown sync event.
,I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
I/ActivityManager(  838): Killing 7016:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10009/pid_7016/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/MusicLeanback( 6868): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6868): Stop autocaching.
,E/GmsUtils( 6868): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6868): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 6996): Internal timer expired: 1
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinService( 5827): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Volley  ( 1730): [1] Request.finish: 3998 ms: [ ] https://www.googleapis.com/userlocation/v1/settings/1371912506?androidGcmRegistrationId=APA91bG_a9yDQoMus-dytd11Yp4uBX037XcetqxE7Xt7igqaN-yeTAzfgBSq0akkIzejrOAR4VlAa8WofNIeimVA7zUAd5gXEvDcR22k6Q_-Ei-AvgVzKwzNNtXK7BBt-3pHoHjLmrwh&devicePrettyName=LG-D722&deviceRestriction=noRestriction&gmsVersion=8489236&nlpVersion=2021&osLevel=21&platform=android%2Flge%2Fjagnm_global_com%2Fjagnm%3A5.0.2%2FLRX22G.A1428918170%2F151031842f939%3Auser%2Frelease-keys 0x30b75e1c NORMAL 1
,I/GCoreUlr( 1730): GCM ID uploaded for account#2#
I/GCoreUlr( 1730): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1730): DispatchingService.onCreate()
I/NotificationManager(  838): android: cancelAsUser(1222422273) by android
,I/GCoreUlr( 1730): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1730): Unbound from all location providers
I/GCoreUlr( 1730): Place inference reporting - stopped
I/GCoreUlr( 1730): DispatchingService.onDestroy()
I/GCoreUlr( 1730): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1730): Unbound from all location providers
I/GCoreUlr( 1730): Place inference reporting - stopped
I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 4640 seconds from now (1453981613927)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     (  838): Explicit concurrent mark sweep GC freed 32199(1516KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.174ms total 155.887ms
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 134892035994; DSPS: 4518761; Offset : -3020460796
,W/PackageSettings(  838): Skipping PackageSetting{b8b21e6 com.example.hello/10317} due to missing metadata
,I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7255 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  838): Handling package changes for user 0
,I/art     ( 1784): Background sticky concurrent mark sweep GC freed 79040(4MB) AllocSpace objects, 0(0B) LOS objects, 26% free, 10MB/14MB, paused 1.537ms total 104.560ms
,W/ResourcesManager( 7255): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/NotificationService(  838): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  838): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  838): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/NotificationManager(  838): android: cancelAsUser(2) by android
V/BackupManagerService(  838): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  838): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@295f9c01
W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1784): getDefaultRoute
,I/ActivityManager(  838): Process com.google.android.gms.unstable (pid 6370) has died
,W/ResourceType(  838): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Babel_SMS( 7255): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7255): MmsConfig.loadMmsSettings
,I/ActivityManager(  838): Process com.google.android.configupdater (pid 7044) has died
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1b08d118 type 2 when 135985 android} when 135985
I/Babel_SMS( 7255): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7255): MmsConfig.loadFromDatabase
I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel_SMS( 7255): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7255): MmsConfig.loadFromResources
E/Babel_SMS( 7255): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7255): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/LocationProviderProxy(  838): applying state to connected service
D/SensorManager( 7255): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7255): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7255): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7255): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 7255): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7255): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7255): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7255): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7255): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7255): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7255): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7255): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7255): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7255): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7255): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7255): found sensor: Motion Accel, handle=46
W/Settings( 7255): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 7255): CheckpointMarkThreadRoots callback created = 0xb042d450
,I/Babel_Crash( 7255): startup - clean
I/Babel   ( 7255): deleted: false for 0
,I/art     ( 7255): CheckpointMarkThreadRoots callback created = 0xb042d430
W/AudioCapabilities( 7255): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7255): Unsupported mime audio/adpcm
W/AudioCapabilities( 7255): Unsupported mime audio/g726
W/AudioCapabilities( 7255): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7255): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7255): Unsupported mime video/mjpg
W/VideoCapabilities( 7255): Unsupported mime video/theora
,I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7289 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 7255): Unsupported mime audio/evrc
W/AudioCapabilities( 7255): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7255): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7255): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7255): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7255): Unsupported mime audio/evrc
W/VideoCapabilities( 7255): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7255): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7255): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7255): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7255): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7255): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 7289): onCreate
,W/AppUp4:DB( 7289):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7289):  setFingerPrint start
,I/AppUp4:DB( 7289):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7289):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7289):  SDK version = 0
I/AppUp4:DB( 7289):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7289): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7289): onReceive
,I/AppUp4:CustModeStarterReceiver( 7289): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7289): Context : android.app.ReceiverRestrictedContext@12eaf2e1
D/AppUp4:CustFacade( 7289): isCustomizationCompleted : false
W/art     ( 7255): Suspending all threads took: 21.854ms
D/AppUp4:CustFacade( 7289): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7289): begin check event
,I/AppUp4:CustModeStarterReceiver( 7289): Event For Nothing, skip.
I/ActivityManager(  838): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7310 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  838): Process com.lge.qmemoplus (pid 7118) has died
,I/vclib   ( 7255): onServiceConnected
W/Babel   ( 7255): Attempted to change video mute state without an active call.
I/NotificationManager( 7255): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7255): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7255): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 7255): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7255): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7255): Installed default security provider GmsCore_OpenSSL
,I/AppConfig( 7310): Total System Memory = 906309632
,I/NotificationManager( 7255): com.google.android.talk: cancel(10436) by com.google.android.talk
I/GalleryUtils( 7310): Application Heap = 96 MB
I/AppConfig( 7310): App Tier : NOT_DEF
D/SystemHelper( 7310): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  838): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7335 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager(  838): Process com.google.android.setupwizard (pid 7147) has died
,W/ResourcesManager( 7335): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7335): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7335): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7335): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7335): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  838): Process com.android.vending (pid 6914) has died
,I/SystemConfig( 7335): BUILD Country: EU
I/SystemConfig( 7335): BUILD Operator: OPEN
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager(  838): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7354 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7335): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7335): existFile = false
I/SystemConfig( 7335): canReadFile = false
I/SystemConfig( 7335): systemFeature RCS result false
D/SystemConfig( 7335): refreshRcsSupport() :false
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/LockScreenSettings( 7354): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7354): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7354): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7354): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7354): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7354): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7371 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 41 ms] updated apps [took 41 ms] 
,I/ActivityManager(  838): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7396 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Finsky  ( 7396): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Finsky  ( 7396): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7396): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7396): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7396): com.android.vending: cancel(-1050172287) by com.android.vending
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
V/DownloadManager( 3128): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3128): created cursor android.database.sqlite.SQLiteCursor@304bf0bb on behalf of 7396
D/Finsky  ( 7396): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7396): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7396): Skipping gmscore version check
I/ActivityManager(  838): Killing 5827:com.google.android.gms/u0a6 (adj 15): empty #11
,D/ConnectivityService(  838): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2cea3a89)
,D/ConnectivityService(  838): dumpNetworkRequest
D/ConnectivityService(  838):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  838):     Requests:
D/ConnectivityService(  838):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):     Lingered:
,D/ConnectivityService(  838): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  838): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ActivityManager(  838): Application dead when creating service ServiceRecord{232f645 u0 com.google.android.gms/.ads.identifier.service.AdvertisingIdService}
,D/Finsky  ( 7396): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/libprocessgroup(  838): failed to open /acct/uid_10006/pid_5827/cgroup.procs: No such file or directory
W/ActivityManager(  838): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 1000ms
W/ActivityManager(  838): Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 4000ms
W/ActivityManager(  838): Spurious death for ProcessRecord{412b73f 0:com.google.android.gms/u0a6}, curProc for 5827: null
I/ActivityManager(  838): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=7440 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 7396): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 322us total 21.610ms
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.555ms
W/ResourcesManager( 7440): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7440): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 20.804ms
I/MultiDex( 7440): VM with version 2.1.0 has multidex support
I/MultiDex( 7440): install
,I/MultiDex( 7440): VM has multidex support, MultiDex support library is disabled.
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/JNIHelp ( 7440): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/ActivityThread( 7440): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7440): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@180c137f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7440): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7440): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7440): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 7440): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7440): Null package name or gms related package.  Ignoreing.
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 7440): Restart initialization of location
,I/art     ( 3685): Explicit concurrent mark sweep GC freed 3184(126KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 455us total 30.203ms
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,D/NativeLibraryUtils( 7440): Install completed successfully. count=14 extracted=0
,I/art     (  838): Explicit concurrent mark sweep GC freed 38580(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.169ms total 147.687ms
,I/art     ( 7440): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7440): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Icing   ( 7440): Storage manager: low false usage 1.71MB avail 2.36GB capacity 4.06GB
,I/art     ( 7440): CheckpointMarkThreadRoots callback created = 0xaae7b700
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=244713133, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,I/art     ( 7440): CheckpointMarkThreadRoots callback created = 0xb042dcb0
D/WeatherService( 2739): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:47:0
D/WeatherService( 2739): 2 : TimeTick Intent And Screen On
D/WeatherService( 2739): 2 : SDK version : 21
,W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2739): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2739): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2739): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2739): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2739): 2 : This is isUpdating : false
D/WeatherService( 2739): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2739): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2739): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2739): 2 : Fixed theme : optimus
D/WeatherReflect( 2739): 2 : Map key string is -2
,D/lim     ( 2739): 2 : time = 12:47
I/WeatherReflect( 2739): Model Name : LG-D722
D/WeatherTheme( 2739): 2 : Different view - status_min_formatted : 46 != 47
D/WeatherTheme( 2739): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2739): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/art     ( 7440): Background partial concurrent mark sweep GC freed 4815(557KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 10MB/17MB, paused 10.443ms total 88.084ms
,D/Theme   ( 2739): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2739): currentPackage=com.lge.sizechangable.weather.theme.optimus
W/IcingInternalCorpora( 7440): getNumBytesRead when not calculated.
,D/Weather4x2_optimus( 2739): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2739): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2739): forecast size is 0
D/Theme   ( 2739): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2739): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2739): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2739): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2739): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2739): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2739): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2739): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2739): url is : null
D/Theme   ( 2739): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2739): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2739): 2 : update view, appWidgetId: 2
D/WeatherService( 2739): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:47:0
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=244713133 [*alarm*], flags=0x0
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/Icing   ( 7440): updateResources: need to parse f{com.google.android.gms}
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/Icing   ( 7440): Internal init done: storage state 0
,I/NotificationManager( 7440): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Icing   ( 7440): Post-init done
,I/Icing   ( 7440): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 102110(5MB) AllocSpace objects, 30(480KB) LOS objects, 39% free, 16MB/27MB, paused 1.816ms total 129.815ms
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 7440): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 7440): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7440): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  838): Killing 6868:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10081/pid_6868/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  483): init target 500000
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  483): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  838): Killing 6996:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6968): android.os.DeadObjectException
,W/System.err( 6968): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6968): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6968): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6968): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6968): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6968): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6968): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6968): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6968): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6968): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6968): android.os.DeadObjectException
W/System.err( 6968): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6968): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6968): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6968): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6968): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6968): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6968): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6968): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6968): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6968): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  838): failed to open /acct/uid_10089/pid_6996/cgroup.procs: No such file or directory
W/ActivityManager(  838): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7526 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7526): Quickset Services start...
,I/UEI.SmartControl( 7526): Manufacture = LGE
D/UEI.SmartControl( 7526): File observer start...
E/UEI.SmartControl( 7526): IR Port is disabled: false
D/UEI.SmartControl( 7526): Starting file observer...
D/UEI.SmartControl( 7526): Extracting JNI libs...
D/UEI.SmartControl( 7526): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7526): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7526): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7526): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7526): --- Selecting new region: 2
,I/UEI.SmartControl( 7526): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7526): Platform has CIR...
D/UEI.SmartControl( 7526): NO CIR support, need to check package...
I/UEI.SmartControl( 7526): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7526): QS Service created
E/UEI.SmartControl( 7526): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7526): Loading JNI Libs...
,D/UEI.SmartControl( 7526):  configuring local db...
D/UEI.SmartControl( 7526):  ---- Has DB8: true
,D/UEI.SmartControl( 7526): QS start statue = true Error code = 0
D/UEI.SmartControl( 7526): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7526): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7526): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7526): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7526): IrrcClient ++ 
D/irrcClient( 7526): getIrrcService ++ 
D/irrcClient( 7526): getIrrcService -- 
D/irrcClient( 7526): IrrcClient -- 
W/irrc_jni( 7526): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7526): Services init done
I/UEI.SmartControl( 7526): Device manager: loading config....
D/UEI.SmartControl( 7526): QS Service init finished
,D/UEI.SmartControl( 7526): Config is loaded...
D/UEI.SmartControl( 7526): QS Service version name: 0.1.73
D/UEI.SmartControl( 7526): QS Service version code: 1073
D/UEI.SmartControl( 7526): Service requested: Control
I/ActivityManager(  838): Killing 6968:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7526):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7526): Notify AllClients services are ready: 0
,W/libprocessgroup(  838): failed to open /acct/uid_10106/pid_6968/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7526): Internal service binding...
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  838): ALS enabled for SRE
,D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28975 ms ago)
D/qdlights(  838): set_light_backlight: 253
,D/qdlights(  838): set_light_backlight: 249
D/qdlights(  838): set_light_backlight: 246
,D/qdlights(  838): set_light_backlight: 243
,D/qdlights(  838): set_light_backlight: 239
,D/qdlights(  838): set_light_backlight: 236
,D/qdlights(  838): set_light_backlight: 233
,D/qdlights(  838): set_light_backlight: 229
,D/qdlights(  838): set_light_backlight: 226
,D/qdlights(  838): set_light_backlight: 223
,D/qdlights(  838): set_light_backlight: 219
,D/qdlights(  838): set_light_backlight: 216
,D/qdlights(  838): set_light_backlight: 213
,D/qdlights(  838): set_light_backlight: 209
,D/qdlights(  838): set_light_backlight: 206
,D/qdlights(  838): set_light_backlight: 203
,D/qdlights(  838): set_light_backlight: 199
,D/qdlights(  838): set_light_backlight: 196
,D/qdlights(  838): set_light_backlight: 193
,D/qdlights(  838): set_light_backlight: 189
,D/qdlights(  838): set_light_backlight: 186
,D/qdlights(  838): set_light_backlight: 183
,D/qdlights(  838): set_light_backlight: 179
,D/qdlights(  838): set_light_backlight: 176
,D/qdlights(  838): set_light_backlight: 173
,D/qdlights(  838): set_light_backlight: 169
,D/qdlights(  838): set_light_backlight: 166
,D/qdlights(  838): set_light_backlight: 163
,D/qdlights(  838): set_light_backlight: 159
,D/qdlights(  838): set_light_backlight: 156
,D/qdlights(  838): set_light_backlight: 153
,D/qdlights(  838): set_light_backlight: 149
,D/qdlights(  838): set_light_backlight: 146
,D/qdlights(  838): set_light_backlight: 143
,D/qdlights(  838): set_light_backlight: 139
,D/qdlights(  838): set_light_backlight: 136
,D/qdlights(  838): set_light_backlight: 133
,D/qdlights(  838): set_light_backlight: 129
,D/qdlights(  838): set_light_backlight: 126
,D/qdlights(  838): set_light_backlight: 123
,D/qdlights(  838): set_light_backlight: 119
,D/qdlights(  838): set_light_backlight: 116
,D/qdlights(  838): set_light_backlight: 113
,D/qdlights(  838): set_light_backlight: 109
,D/qdlights(  838): set_light_backlight: 106
,D/qdlights(  838): set_light_backlight: 103
,D/qdlights(  838): set_light_backlight: 99
,D/qdlights(  838): set_light_backlight: 96
,D/qdlights(  838): set_light_backlight: 93
,D/qdlights(  838): set_light_backlight: 89
,D/qdlights(  838): set_light_backlight: 86
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  838): set_light_backlight: 83
,D/qdlights(  838): set_light_backlight: 79
,D/qdlights(  838): set_light_backlight: 76
,D/qdlights(  838): set_light_backlight: 73
,D/qdlights(  838): set_light_backlight: 69
,D/qdlights(  838): set_light_backlight: 66
,D/qdlights(  838): set_light_backlight: 63
,D/qdlights(  838): set_light_backlight: 59
,D/qdlights(  838): set_light_backlight: 56
,D/qdlights(  838): set_light_backlight: 53
,D/qdlights(  838): set_light_backlight: 49
,D/qdlights(  838): set_light_backlight: 46
,D/qdlights(  838): set_light_backlight: 43
,D/qdlights(  838): set_light_backlight: 39
,D/qdlights(  838): set_light_backlight: 36
,D/qdlights(  838): set_light_backlight: 33
,D/qdlights(  838): set_light_backlight: 29
,D/UEI.SmartControl( 7526): Internal timer expired: 1
D/UEI.SmartControl( 7526): Service.onUnbind: IControl
D/UEI.SmartControl( 7526): Service.onDestroy
W/System.err( 7526): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2d8bd063
W/System.err( 7526): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7526): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7526): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7526): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7526): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7526): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7526): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7526): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7526): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7526): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7526): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7526): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7526): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7526): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7526): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2d8bd063
D/UEI.SmartControl( 7526): Shutdown IRRCPlayer... 
,D/qdlights(  838): set_light_backlight: 26
W/irrc_jni( 7526): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7526): ~IrrcClient ++ 
D/irrcClient( 7526): ~IrrcClient -- 
W/irrc_jni( 7526): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7526): Blaster closed
D/UEI.SmartControl( 7526): Blaster closed
D/UEI.SmartControl( 7526): Shut down QS...
,D/UEI.SmartControl( 7526): Stopped file observer...
D/qdlights(  838): set_light_backlight: 23
I/UEI.SmartControl( 7526): QS lib stop result = true
D/UEI.SmartControl( 7526): QS shutdown complete
D/qdlights(  838): set_light_backlight: 19
,D/qdlights(  838): set_light_backlight: 16
,D/qdlights(  838): set_light_backlight: 13
,D/qdlights(  838): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 154892782550; DSPS: 5174146; Offset : -3020477103
,I/PowerManagerService(  838): ALS enabled for SRE
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35961 ms ago)
I/PowerManagerService(  838): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  838): ALS enabled for SRE
,D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35984 ms ago)
W/ContextImpl(  838): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  838): Sleeping (uid 1000)...
,D/LPWGController(  838): [updateScreenState] screen on = false
D/LPWGController(  838): disable proximity sensor
D/LPWGController(  838): enable proximity sensor
,I/SensorManager(  838): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3a2724a1] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  838): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  838): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  838): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  838): activate: handle is 48, enable
,V/sensors_hal_Ctx(  838): activate sensors is 1400000000000
D/sensors_hal_Thresh(  838): enable: handle=48
I/sensors_hal_SAM(  838): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  838): waitForResponse: timeout=1000
V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  838): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,D/sensors_hal_Thresh(  838): enable: Received response: 0
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36055 ms ago)
I/Adreno-EGL(  838): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  838): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  838): Build Date: 03/02/15 Mon
I/Adreno-EGL(  838): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  838): Remote Branch: 
I/Adreno-EGL(  838): Local Patches: 
I/Adreno-EGL(  838): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (144 us)
,I/Sensors (  422): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  838): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  838): processInd: handle 48, count=1
V/sensors_hal_Thresh(  838): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  838): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  838): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  838): poll: count: 256
I/sensors_hal_Ctx(  838): poll: released wakelock sensor_ind
D/sensors_hal_Util(  838): waitForResponse: timeout=0
D/LPWGController(  838): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  838): current mode = 1  value = 1 1
I/LPWGController(  838): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  838): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  838): set_light_backlight: 0
,I/SensorManager(  838): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  838): activate: handle is 46, disable
V/sensors_hal_Ctx(  838): activate sensors is 1000000000000
D/sensors_hal_LP2(  838): enable: handle=46
D/sensors_hal_LP2(  838): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  838): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  838): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  838): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  838): Display changed displayId=0
,D/DSDPConnection( 1749): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  838): Excessive delay in setPowerMode(): 187ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  838): Got set_interactive hint
D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
,D/WifiServerServiceExt(  838): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 838
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  283): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/WifiServerServiceExt(  838): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  838): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1837): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1801): stopPatternFlashing()
D/Cliptray Service( 1801): lockStatus = 0
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
D/SplitWindow(  838): check instance of lgWin Window{263449b4 u0 SearchPanel}
,D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
,D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 3
D/NfcService( 1784): Discovery configuration equal, not updating.
D/InputDispatcher(  838): Window went away: Window{1d0378e7 u0 SearchPanel}
I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,D/Ulp_jni (  838): JNI:system_update. Event-0
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2739): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:47:18
,D/WeatherService( 2739): 2 : ACTION screen on
D/WeatherService( 2739): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2739): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2739): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:47:18
D/AppCleanupService( 3808): android.intent.action.SCREEN_ON
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): ACTION_SCREEN_ON
V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 838
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/WifiController(  838): CMD_SCREEN_OFF 
D/WifiController(  838): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  838): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2739): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:47:18
D/WeatherService( 2739): 2 : ACTION screen off
D/WeatherService( 2739): 2 : TimeTick Receiver Unregister
D/WeatherService( 2739): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:47:18
D/AppCleanupService( 3808): android.intent.action.SCREEN_OFF
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): ACTION_SCREEN_OFF
D/AppCleanupService( 3808): AppUsageStatsSaveTask
E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1784): getDefaultRoute
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: 0
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,I/Sensors (  422): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{27f069dd type 2 when 161883 com.android.systemui} when 161883
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{3f8c9952 type 2 when 168358 android} when 168358
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,E/ActivityThread( 7440): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  838): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 140064, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  838): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 234424, reason: UserStart
I/NotificationManager(  838): android: cancelAsUser(716319171) by android
I/PeopleSync( 7440): onPerformSync() [5005f081]
,I/PeopleDatabaseHelper( 7440): cleanUpNonGplusAccounts done.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/InstanceID/Rpc( 7440): Found 10006
,I/PeopleSync( 7440): Setting subscription: result=true [5005f081]
,I/PeopleSync( 7440): Starting sync, feed=null [5005f081]
W/BaseAppContext( 7440): Using Auth Proxy for data requests.
,E/BaseAppContext( 7440): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 7440): Using Auth Proxy for data requests.
,W/BaseAppContext( 7440): Using Auth Proxy for data requests.
,I/PeopleSync( 7440): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 7440): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7440): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7440): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7440): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 7440): propertyValue:false
D/libc-netbsd( 7440): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7440): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7440): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7440): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7440): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7440): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Volley  ( 7440): [918] BasicNetwork.logSlowRequests: HTTP response for request=<[ ] https://www.googleapis.com/plus/v2whitelisted/people/me?prettyPrint=false&fields=etag,id,names,images,emails,phoneNumbers,addresses,metadata/ownerId,metadata/ownerUserTypes,coverPhotos&includeLinkedPeople=false&includeProfilesWithState=disabled&includeProfilesWithState=blocked 0x30b75e1c NORMAL 1> [lifetime=4290], [size=517], [rc=200], [retryCount=0]
,D/Volley  ( 7440): [1] Request.finish: 4342 ms: [ ] https://www.googleapis.com/plus/v2whitelisted/people/me?prettyPrint=false&fields=etag,id,names,images,emails,phoneNumbers,addresses,metadata/ownerId,metadata/ownerUserTypes,coverPhotos&includeLinkedPeople=false&includeProfilesWithState=disabled&includeProfilesWithState=blocked 0x30b75e1c NORMAL 1
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 174893607646; DSPS: 5829533; Offset : -3020476242
,I/PeopleSync( 7440): Sync finished, successful=true, took 9503ms
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/PeopleContactsSync( 7440): CP2 sync start [5005f081]
,I/PeopleContactsSync( 7440): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
I/PeopleContactsSync( 7440): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 7440): CP2 cleanup done, kept= duration=73 ms
,I/PeopleContactsSync( 7440): ===CP2 sync finished, success=true, time=92,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
I/PeopleSync( 7440): ***Sync finished***, duration: 10025 [5005f081]
,I/NotificationManager(  838): android: cancelAsUser(148851818) by android
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,D/charger_monitor(  483): init target 500000
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  838): battery changed pluggedType: 2
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1424a5b9 type 2 when 187450 com.google.android.gms} when 187450
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{242f1dfe type 2 when 188595 android} when 188595
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 194894348837; DSPS: 6484917; Offset : -3020467238
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{33a7595f type 2 when 198477 android} when 198477
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 214895026589; DSPS: 7140299; Offset : -3020460795
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 234895699290; DSPS: 7795681; Offset : -3020459559
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  483): init target 500000
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 254896385168; DSPS: 8451064; Offset : -3020475350
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 274897205108; DSPS: 9106451; Offset : -3020479515
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 294897880464; DSPS: 9761833; Offset : -3020475233
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ClearcutLoggerApiImpl( 7440): disconnect managed GoogleApiClient
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  483): init target 500000
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5360): TAP version 13
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # multiplex can send data
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 1 String should be length:200
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # enqueue and run in order
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 2 firstPromise setTimeout
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 3 firstPromise result
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 4 firstPromise testValue
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 5 secondPromise setTimeout
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 6 secondPromise result
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 7 secondPromise testValue
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 8 thirdPromise in promise
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 9 thirdPromise result
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 10 thirdPromise testValue
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 314898700405; DSPS: 10417220; Offset : -3020479293
,I/jxcore-log( 5360): # basic
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 11 sane
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # another
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 12 sane
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 13 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 14 null
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 15 (unnamed assert)
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 16 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 17 should not throw
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 18 (unnamed assert)
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 19 (unnamed assert)
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 20 should not throw
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 21 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 22 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 23 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # failed to get mobile documents path
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 24 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 25 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 26 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 27 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #init should register the networkChanged event
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 28 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # #startBroadcasting should throw on null device name
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 29 should throw
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 30 should throw
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 31 should throw
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 32 should throw
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startBroadcasting should throw on negative port
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 33 should throw
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startBroadcasting should throw on too large port
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 34 should throw
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 35 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 36 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 37 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 38 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 39 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 40 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 41 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 42 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 43 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 44 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 45 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 46 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 47 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 48 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 49 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 50 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 51 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 52 should be equal
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 53 should be equal
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798006.5360
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798006.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1982): BTA_JvCreateRecordByUser
,D/LGBluetoothServiceAdapter( 1982): [BTUI] createSocketChannel FD=87 mFd=85
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798006.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798006.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798006.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798006.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798006.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d4c7a2dc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d4c7a2dc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
,D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798006.5360
D/LGWifiP2pService(  838): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/wpa_supplicant( 5527): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 5360): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
D/WfdsMonitor( 1801): Event [CTRL-EVENT-SCAN-STARTED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
,I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
D/LGWifiP2pService(  838): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5360): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798216.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798216.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798216.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798216.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798216.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798216.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798216.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@99198916 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@99198916 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/jxcore-log( 5360): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798216.5360
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
D/LGWifiP2pService(  838): discovery change broadcast true
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully,
D/LGWifiP2pService(  838): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/LGWifiP2pService(  838): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
I/jxcore-log( 5360): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798289.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798289.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798289.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798289.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798289.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798289.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798289.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9a570102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9a570102 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798289.5360
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5360): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/LGWifiP2pService(  838): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thal,iproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  838): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
D/LGWifiP2pService(  838): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/jxcore-log( 5360): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798340.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798340.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798340.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798340.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798340.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798340.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798340.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ec16211a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ec16211a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798340.5360
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/LGWifiP2pService(  838): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
I/jxcore-log( 5360): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D,/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
I/bt-btif ( 1982): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/bt-btif ( 1982): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
D/LGWifiP2pService(  838): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Cannot restart, because not initialized
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5360): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798391.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798391.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798391.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798391.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798391.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798391.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798391.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@be7d230e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@be7d230e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798391.5360
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/LGWifiP2pService(  838): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  838): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
I/jxcore-log( 5360): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
D/LGWifiP2pService(  838): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5360): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798440.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798440.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798440.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798440.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798440.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798440.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798440.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@46df9b58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@46df9b58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798440.5360
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
D/LGWifiP2pService(  838): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  838): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
I/jxcore-log( 5360): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnec,tions: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
D/LGWifiP2pService(  838): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5360): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
,D/LGWifiP2pService(  838): InactiveState{ when=-5ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-5ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798473.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798473.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798473.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798473.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798473.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798473.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798473.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d214c4c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d214c4c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
,D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798473.5360
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/LGWifiP2pService(  838): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  838): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
I/jxcore-log( 5360): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
I/bt-btif ( 1982): BTA_JvDeleteRecord
D/org.thalipro,ject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  838): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
I/jxcore-log( 5360): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798510.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798510.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798510.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798510.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798510.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798510.5360","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798510.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@756c405c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@756c405c target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798510.5360
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/jxcore-log( 5360): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
D/LGWifiP2pService(  838): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
,D/LGWifiP2pService(  838): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  838): remove client information from framework
I/jxcore-log( 5360): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798542.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798542.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
,I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798542.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798542.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798542.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798542.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798542.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b301a812 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b301a812 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Sta,rting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798542.5360
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
D/LGWifiP2pService(  838): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/jxcore-log( 5360): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
D/BluetoothAdapterService(764137571)( ,1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
D/LGWifiP2pService(  838): remove client information from framework
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/jxcore-log( 5360): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798576.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798576.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
,I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798576.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981798576.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981798576.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981798576.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981798576.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@1efa244 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@1efa244 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981798576.5360
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
I/jxcore-log( 5360): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/LGWifiP2pService(  838): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
I/bt-btif ( 1982): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org,.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
D/LGWifiP2pService(  838): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5360): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
,I/jxcore-log( 5360): # setup,
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 4
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981799153.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981799153.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981799153.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981799153.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981799153.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981799153.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981799153.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
I/art     (  838): Explicit concurrent mark sweep GC freed 48638(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 2.732ms total 170.328ms
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ad9adcd4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ad9adcd4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981799153.5360
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
I/jxcore-log( 5360): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
D/LGWifiP2pService(  838): discovery change broadcast true
I/jxcore-log( 5360): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 5360): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
D/LGWifiP2pService(  838): InactiveState{ when=-5ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5360): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
I/wpa_supplicant( 5527): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/WfdsMonitor( 1801): Event [CTRL-EVENT-SCAN-STARTED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): di,scovery change broadcast false
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
D/LGWifiP2pService(  838): remove client information from framework,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
,D/LGWifiP2pService(  838): InactiveState{ when=-11ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-12ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-12ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/jxcore-log( 5360): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981799664.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981799664.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
,I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981799664.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981799664.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981799664.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981799664.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981799664.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@af57b06 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@af57b06 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  838): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981799664.5360
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/jxcore-log( 5360): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
I/io.jxcore.node.ConnectionHelper( 5360): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 5360): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 5360): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 5360): ok 78 Should not connect to a bad peer
I/jxcore-log( 5360): 
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
D/LGWifiP2pService(  838): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5360): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981800227.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981800227.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5360): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1982): BTA_JvCreateRecordByUser
,I/bt-btif ( 1982): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): start: OK
I/io.jxcore.node.ConnectionHelper( 5360): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981800227.5360
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): createAdvertiseData: From: 1453981800227.5360 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5360): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5360): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5360): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5360): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453981800227.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): start: {"pi":"F8:95:C7:87:85:54","pn":"1453981800227.5360","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453981800227.5360","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Waiting for incoming connections...
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d5d67cb2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d5d67cb2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState add service
D/LGWifiP2pService(  838): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Starting P2P device discovery...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  838): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453981800227.5360
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5527): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): P2P device discovery stopped successfully
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: RESTARTING
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5360): start: OK
I/jxcore-log( 5360): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 5360): 
D/io.jxcore.node.ConnectionHelper( 5360): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 5360): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 5360): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 5360): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 5360): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 5360): 
I/io.jxcore.node.ConnectionHelper( 5360): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5360): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5360): onServerStopped
,I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stop: Stopping peer discovery...
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothLeScanner( 5360): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5360): stop: Stopping services
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service
D/LGWifiP2pService(  838): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5360): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): setState: NOT_INITIALIZED
,D/LGWifiP2pService(  838): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5360): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5360): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5360): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5360): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5360): onDiscoveryManagerStateChanged: NOT_STARTED
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 4
I/jxcore-log( 5360): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 83 host address should match
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 84 port should match
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 85 peer should be available
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 86 peer should be unavailable
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 87 USN should have changed from the first one
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # messages with invalid location or USN should be ignored
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 88 should not have emitted with invalid port
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 89 should not have emitted with invalid USN
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 90 irrelevant messages should be ignored
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 91 relevant messages should not be ignored
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 92 messages from this device should be ignored
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # #start should fail if called twice in a row
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 93 specific error should be received
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,E/jxcore-log( 5360): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 94 specific error should be received
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,E/jxcore-log( 5360): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
E/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 95 specific error expected
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,D/libc-netbsd( 5360): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5360): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=0; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10316
D/DnsProxyListener(  279): App 10316 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=0; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/jxcore-log( 5360): ok 96 server should respond with code 200
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #stop can be called multiple times in a row
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 97 should be in stopped state
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 98 should still be in stopped state
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 99 should be in listening state
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 100 should still be in listening state
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # #stopListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): ok 101 should not be in listening state
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 102 should still not be in listening state
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/jxcore-log( 5360): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 5360): 
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/jxcore-log( 5360): ok 103 should not be in advertising state
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ok 104 should still not be in advertising state
I/jxcore-log( 5360): 
I/jxcore-log( 5360): # setup
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): # functions are run from a queue in the right order
I/jxcore-log( 5360): 
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/jxcore-log( 5360): # teardown
I/jxcore-log( 5360): 
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
D/HeadsetStateMachine( 1982): Disconnected process message: 10, size: 0
I/jxcore-log( 5360): ok 105 call order must match
I/jxcore-log( 5360): 
,I/jxcore-log( 5360): Tests Complete
I/jxcore-log( 5360): 
I/jxcore-log( 5360): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 5360): 
I/jxcore-log( 5360): Toggling radios to false
I/jxcore-log( 5360): 
I/chromium( 5360): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  838): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@14002bfb mBinding = false
D/BluetoothManagerService(  838): Message: 2
,D/WifiServiceImplEx(  838): setWifiEnabled: false pid=5360, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  838): setWifiEnabled: false pid=5360, uid=10316
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothManagerService(  838): Sending off request.
I/chromium( 5360): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
I/jxcore-log( 5360): Radios toggled
I/jxcore-log( 5360): 
D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
I/jxcore-log( 5360): ****TEST TOOK:  ms ****
I/jxcore-log( 5360): 
I/jxcore-log( 5360): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5360): 
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
D/BluetoothAdapterService(764137571)( 1982): disable() called...
E/WifiStateMachine(  838): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,D/BluetoothAdapterState( 1982): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1982): Setting state to 13
I/BluetoothAdapterState( 1982): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(764137571)( 1982): updateAdapterState() - Broadcasting state to 1 receivers.
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/BluetoothAdapterProperties( 1982): onBluetoothDisable()
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothManagerService(  838): Message: 60
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 12 -> 13
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/LGBluetoothAPIService( 1801): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
V/NativeCrypto( 1730): Read error: ssl=0xaaee2400: I/O error during system call, Connection timed out
V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xaaee2400: I/O error during system call, Broken pipe
I/BluetoothAdapterState( 1982): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_properties_cb
,I/jxcore-log( 5360): Toggling radios to false
I/jxcore-log( 5360): 
I/BluetoothMapService( 1982): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1982): STATE_TURNING_OFF
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/BluetoothMapService( 1982): Handler(): got msg=4
D/BluetoothMapService( 1982): MAP Service closeService in
D/BluetoothMapMasInstance( 1982): MAP Service shutdown
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 10
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
V/BluetoothMapMasInstance( 1982): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 1982): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 1982): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 1982): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 1982): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 1982): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 1982): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 1982): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/ConnectivityService(  838): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/LGBluetoothMapAdapter( 1982): [BTUI] LGBluetoothMapAdapter cleanup
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-9ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothMapService( 1982): MAP Service closeService out
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Forcing reevaluation
,I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7746 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterProperties( 1982): Scan Mode:20
D/BluetoothManagerService(  838): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@14002bfb mBinding = false
D/BluetoothManagerService(  838): Message: 2
D/BluetoothAdapterState( 1982): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService(  838): Sending off request.
I/bt-btif ( 1982): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 1982): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20(  838): hidePasspointNotification off =false
D/bt-btif ( 1982): btsock_ctrl_hci_cleanup(L202): poll handle:4
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/bt-btif ( 1982): BTA_JvDeleteRecord
I/bt-btif ( 1982): BTA_JvRfcommStopServer
D/IOP_DB_BT( 1982): db_close: nbr users 0
D/IOP_DB_BT( 1982): db_close: free database
W/bt-btif ( 1982): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/bt-btif ( 1982): btif_hf_upstreams_evt: wrong handle = 24937 
W/bt-obex ( 1982): Ignore event 10 in state 1
W/bt-obex ( 1982): Ignore event 10 in state 1
I/bt-btif ( 1982): HAL bt_op_callbacks->ops_state_cb
,D/btif_config_util( 1982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
E/bt-btif ( 1982): bta_gattc_deregister Deregister Failedm unknown client cif
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 1982): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:G3s-1
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1982): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1982): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1982): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1982): enum_config(L344): out, value:x
D/btif_config_util( 1982): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 1982): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1982): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 1982): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1982): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 1982): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1982): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 1982): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1982): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 1982): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1982): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1982): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:�
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/BluetoothOPPServiceJni( 1982): ops_state_cb(L223):  ops_state_cb state:3
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:$
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
,D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20(  838): hidePasspointNotification off =false
V/BluetoothPbapService( 1982): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/OppService( 1982): onOpsStateChange() :3
D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/OppService( 1982): Recieved MESSAGE_OPS_DISABLE
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:�
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:A5-1
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:,
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:,
,D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:#
D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:�
,D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:XT1072
D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z,
D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:a
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:S5-1
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1982): ,enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:	a
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:G4-1
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
,D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
,D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:a
,D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType,
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
,D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
,D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:�
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
,D/btif_config_util( 1982): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
,D/btif_config_util( 1982): enum_config(L344): out, value:�
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
,D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
,D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:A
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
,D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,D/btif_config_util( 1982): enum_config(L344): out, value:
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:	a
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
,D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1982): enum_config(L344): out, value:
,D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L344): out, value:A3-1
,D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
,D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1982): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
,D/btif_config_util( 1982): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1982): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
,D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks,
,D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
,D/btif_config_util( 1982): enum_config(L344): out, value:�
D/btif_config_util( 1982): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 1982): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 1982): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L344): out, value:Note4-1
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/RttService(  838): SCAN_AVAILABLE : 1
D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1982): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
,D/btif_config_util( 1982): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name,
D/btif_config_util( 1982): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 1982): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1982): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
,D/btif_config_util( 1982): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 1982): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
,D/btif_config_util( 1982): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
,D/btif_config_util( 1982): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 1982): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:���
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int,
D/btif_config_util( 1982): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1982): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1982): enum_config(L344): out, value:
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
,D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
,D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 1982): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
,D/btif_config_util( 1982): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/LGWifiP2pService(  838): P2pDisabledState
D/btif_config_util( 1982): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer,
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
,D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:onem9-1
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
,D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer,
D/btif_config_util( 1982): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 1982): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 1982): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:Tab4
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 1982): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 1982): enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
,D/btif_config_util( 1982): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1982): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 1982): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 1982): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 1982): enum_config(L344): out, value:�h�
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 1982): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:Name
,D/btif_config_util( 1982): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 1982): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 1982): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 1982): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:08:00:00:00:67:73, value:DevClass
,D/btif_config_util( 1982): enum_config(L343): out, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
D/btif_config_util( 1982): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
,D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 1982): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 1982): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
,D/btif_config_util( 1982): enum_config(L344): out, value:�
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 1982): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 1982): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 1982): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 1982): enum_config(L344): out, value:Z
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
,D/btif_config_util( 1982): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 1982): enum_config(L344): out, value:
,D/btif_config_util( 1982): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 1982): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 1982): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 1982): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
,D/btif_config_util( 1982): enum_config(L344): out, value:
D/btif_config_util( 1982): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 1982): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 1982): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 1982): enum_config(L344): out, value:4g�
D/btif_config_util( 1982): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
D/btif_config_util( 1982): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
D/WifiNetworkAgent(  838): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService(  838): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WfdsService( 1801): WifiP2pState is changed : false
,D/WifiServiceImplEx(  838): setWifiEnabled: false pid=5360, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:50:04.398 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:50:04.399 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/BluetoothAdapterService(764137571)( 1982): disable() called...
D/WifiService(  838): setWifiEnabled: false pid=5360, uid=10316
I/jxcore-log( 5360): Radios toggled
I/jxcore-log( 5360): 
D/WfdsService( 1801): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1801): doCommand: P2P_STOP_FIND
,D/WfdsService( 1801): Set the WFDS Monitor: false
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothAdapterService( 1982): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService(  838): IBluetooth.disable() returned false
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/CtrlSupplicant( 1801): Received on exit socket, terminate
,E/CtrlSupplicant( 1801): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1801): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1801): WfdsMonitorThread is received the interrupt - closing
D/WfdsMonitor( 1801): WFDS Monitor is stopped
D/WfdsService( 1801): STATE : WfdsDisabledState - enter
D/WfdsService( 1801): WFDS: Scanner is paused
D/WfdsDiscoveryStore( 1801): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1801): DefaultState - msg [9441355] is not handled
D/DhcpStateMachine(  838): StoppedState
D/DhcpStateMachine(  838): StoppedState{ when=-83ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  838): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  838): disableDataServiceNotify
D/WifiHS20(  838): hidePasspointNotification off =false
D/DSQN    (  838): stop dsqn bin
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:50:04.474 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:50:04.482 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [0]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt(  838): setSupplicantStateDISCONNECTED
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  838): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  838): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Disconnected - quitting
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.p2p.STATE_CHANGED at null
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/CSLegacyTypeTracker(  838): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  838): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  838): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1837): |CORE| No family connected
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  838): [LG_RESTRICTED] !!!isConnected  type  :1
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  838): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  838): Removing idletimer
W/Settings(  838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    (  838): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  838): MasterInitialState.processMessage what=3
V/NetworkPolicy(  838): [LG_RESTRICTED] !!!isConnected  type  :1
E/ConnectivityService(  838): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1749): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 5
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 5527): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 5527): monitor socket send errors count : 1
I/wpa_supplicant( 5527): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1801-2\x00 that cannot receive messages
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 7
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
,I/wpa_supplicant( 5527): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 5527): USIM:  scard_deinit function
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 5527): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  838): InitialState.processMessage what=4
D/Tethering(  838): sendTetherStateChangedBroadcast 0, 0, 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5360): start: Cannot start, because not initialized
,D/WifiOffDelayIfNotUsed(  838): stopMonitoring
D/WfdsService( 1801): Supplicant Connection state is changed : false
,D/WfdsService( 1801): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1801): Set the WFDS Monitor: false
D/WfdsMonitor( 1801): WFDS Monitor is stopped
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-28 12:50:04.796 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : this is not treated
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/Settings( 1730): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AndroidRuntime( 7742): 
D/AndroidRuntime( 7742): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,W/ResourcesManager( 7746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7746): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,D/AndroidRuntime( 7742): CheckJNI is OFF
W/ResourcesManager( 7746): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7746): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7746): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  838): Process com.google.android.talk (pid 7255) has died
,I/IndexDatabaseHelper( 7746): Using schema version: 115
I/IndexDatabaseHelper( 7746): Index is fine
,I/ActivityManager(  838): Process com.android.contacts (pid 7335) has died
,W/ContextImpl( 7746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 1982): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1982): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1982): ***********state = 13
,V/WiFiOffLoadBroadcast( 7746): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/BluetoothPbapReceiver( 1982): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 1982): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1982): state: 13
V/BluetoothPbapService( 1982): Pbap Service closeService in
V/BluetoothPbapService( 1982): successfully stopped pbap service
V/BluetoothPbapService( 1982): Pbap Service closeService out
V/BluetoothPbapService( 1982): Pbap Service onDestroy
V/BluetoothPbapService( 1982): Pbap Service closeService in
V/BluetoothPbapService( 1982): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1982): [BTUI] cleanup
D/AndroidRuntime( 7742): Calling main entry com.android.commands.pm.Pm
,D/WiFiOffLoadBroadcast( 7746): MCCMNC not supported: null
I/ActivityManager(  838): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  838): Killing 5360:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24fe9456:true
,I/WindowState(  838): WIN DEATH: Window{90d150a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  838): Focus left window: Window{90d150a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  838): Window went away: Window{90d150a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  838): Skipping PackageSetting{b8b21e6 com.example.hello/10317} due to missing metadata
,W/bt_userial( 1982): select_read return size <=0:0, exiting userial_read_thread
,D/bt_hwcfg( 1982): hw_epilog_process
,W/bt-l2cap( 1982): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1982): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1982): ag scb idx 1 not allocated
E/bt-btif ( 1982): BTA AG is already disabled, ignoring ...
I/bt_userial_vendor( 1982): device fd = 67 close
W/bt-l2cap( 1982): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1982): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1982): ag scb idx 1 not allocated
E/bt-btif ( 1982): BTA AG is already disabled, ignoring ...
E/bt-btif ( 1982): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 1982): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_vendor( 1982): [BTUI] Proto is enabled. Set Proto disable!!
,I/ActivityManager(  838):   Force finishing activity ActivityRecord{1ae86c3e u0 com.test.thalitest/.MainActivity t222}
,I/GKI_LINUX( 1982): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,V/ActivityManager(  838): Display changed displayId=0
D/DSDPConnection( 1749): Display #0 changed.
,W/ActivityManager(  838): Spurious death for ProcessRecord{4e79fe2 5360:com.test.thalitest/u0a316}, curProc for 5360: null
I/ActivityManager(  838): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  838):   Force finishing activity ActivityRecord{1ae86c3e u0 com.test.thalitest/.MainActivity t222 f}
,W/ActivityManager(  838): Duplicate finish request for ActivityRecord{1ae86c3e u0 com.test.thalitest/.MainActivity t222 f}
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
,D/BluetoothManagerService(  838): Message: 30
,I/GKI_LINUX( 1982): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1982): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 1982): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1982): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1982): Unable to read settings
D/BtSettings.ProfileConfig( 1982): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1982): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1982): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1982): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1982): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1982): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 1982): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 1982): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1982): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1982): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothManagerService(  838): Message: 30
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
W/System.err( 3365): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/[LGHome]EVENT( 1874): [Launcher.java:5203:onStart()]onStart
,D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
,W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1982): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1982): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1982): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterState( 1982): Stopping profile services that were post enabled
D/HeadsetService( 1982): Received stop request...Stopping profile...
,W/System.err( 3365): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3365): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3365): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3365): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3365): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/LocalBluetoothProfileManager( 7746): Adding local MAP profile
I/LGBluetoothHfpAdapter( 1982): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 1982): Cleaning up Bluetooth Handsfree callback object
D/HeadsetStateMachine( 1982): Exit Disconnected: -1
D/BluetoothMap( 7746): Create BluetoothMap proxy object
D/BluetoothManagerService(  838): Message: 30
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/BluetoothHeadset( 1749): Proxy object disconnected
,D/A2dpService( 1982): Received stop request...Stopping profile...
D/A2dpStateMachine( 1982): Exit Disconnected: -1
D/BluetoothManagerService(  838): Message: 30
D/LocalBluetoothProfileManager( 7746): LocalBluetoothProfileManager construction complete
D/LGBluetoothA2dpAdapter( 1982): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1982): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 1982): [BTUI] terminate
D/BluetoothManagerService(  838): Message: 31
,D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/LGBluetoothFeatureConfig( 7746):  get() - isFeatureLoaded : false
D/HidService( 1982): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/HealthService( 1982): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/PanService( 1982): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/BluetoothHeadset( 1749): Proxy object disconnected
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothHeadset( 1749): Proxy object disconnected
,D/BtGatt.DebugUtils( 1982): handleDebugAction() action=null
D/BtGatt.GattService( 1982): Received stop request...Stopping profile...
D/BtGatt.GattService( 1982): stop()
D/BtGatt.AdvertiseManager( 1982): advertise clients cleared
D/LGBluetoothGattAdapter( 1982): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/BluetoothMapService( 1982): Received stop request...Stopping profile...
D/BluetoothMapService( 1982): stop()
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
I/art     ( 1937): Explicit concurrent mark sweep GC freed 14908(896KB) AllocSpace objects, 2(47KB) LOS objects, 39% free, 12MB/21MB, paused 3.584ms total 157.238ms
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
D/BluetoothMapEmailAppObserver( 1982): deinitObservers()
,D/BluetoothMapEmailAppObserver( 1982): removeReceiver()
I/[LGHome]EVENT( 1874): [Launcher.java:776:onResume()]onResume
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/SapService( 1982): Received stop request...Stopping profile...
D/SapService( 1982): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1982): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 1982): [BTUI] terminateSapManager
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/**BluetoothFTPService( 1982): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1982): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1982): closeFtpServerNative
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]EVENT( 1874): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
D/**OppService( 1982): Received stop request...Stopping profile...
D/OppService( 1982): Stopping Bluetooth OppService
D/OppService( 1982): cleanup OPP Service
W/BluetoothOPPServiceJni( 1982): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 1982): Cleaning up Bluetooth OPP callback object
D/LgeBluetoothSimManager( 1749): [BTUI] SAP_DISABLE_EVT
D/OppService( 1982): remove callbacks and handler
D/LGBluetoothOppAdapter( 1982): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1982): cleanup done
D/BluetoothAdapterService( 1982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8bd063
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
,D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/HeadsetStateMachine( 1982): Unbinding service...
D/HeadsetPhoneState( 1982): [BTUI] listenForPhoneState : start = false
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/LGBluetoothHfpManager( 1982): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1982): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1982): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 1982): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1982): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1982): [BTUI] LGBluetoothHfpAdapter cleanup
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 1982): cleanupNative
I/GKI_LINUX( 1982): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1982): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1982): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
,D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
I/[LGHome]LGActivityUtil( 1874): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/[LGHome]EVENT( 1874): [Launcher.java:929:onResume()]onResume end
W/BluetoothHidServiceJni( 1982): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 1982): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 1982): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1982): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1982): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 1982): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1982): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterS,ervice(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1982): Handler(): got msg=4
D/BluetoothMapService( 1982): MAP Service closeService in
D/LGBluetoothMapAdapter( 1982): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1982): MAP Service closeService out
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 1982): cleanup()
D/BluetoothMapService( 1982): MAP Service closeService in
D/LGBluetoothMapAdapter( 1982): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1982): MAP Service closeService out
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
,D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 1982): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 1982): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
,D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1982): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,I/Activity( 1874): Activity.onPostResume() called 
D/BluetoothAdapterService( 1982): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 1982): cleanup FTP Service
V/BluetoothFTPServiceJni( 1982): closeFtpServerNative
,V/BluetoothFTPServiceJni( 1982): cleanupNative
W/BluetoothFTPServiceJni( 1982): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1982): Cleaning up Bluetooth FTP callback object
,D/BluetoothFTPService( 1982): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1982): cleanup done
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - Message: 1
D/BluetoothAdapterService(764137571)( 1982): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 1982): isTurningOnRadio()=false
D/BluetoothAdapterState( 1982): isTurningOffRadio()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1982): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1982): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
,D/BluetoothAdapterService(764137571)( 1982): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 1982): cleanup OPP Service
D/OppService( 1982): remove callbacks and handler,
,D/LGBluetoothOppAdapter( 1982): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1982): cleanup done
D/BluetoothAdapterState( 1982): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1982): Setting state to 10
,I/BluetoothAdapterState( 1982): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(764137571)( 1982): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  838): Message: 60
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  838): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1749): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 1982): Entering OffState,
D/BluetoothHeadset(  838): onBluetoothStateChange: up=false
D/BluetoothA2dp(  838): onBluetoothStateChange: up=false
D/BluetoothPan( 7746): onBluetoothStateChange on: false
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/BluetoothMap( 7746): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1749): onBluetoothStateChange: up=false
,I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1373): handleShortcutListChanged...
D/BluetoothHeadset( 1749): onBluetoothStateChange: up=false
D/BluetoothPbap( 7746): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7746): onBluetoothStateChange: up=false
D/BluetoothAdapterService(764137571)( 1982): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@f055651
D/BluetoothManagerService(  838): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  838): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  838): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  838): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  838): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@14002bfb mBinding = false
W/[LGHome]LGWallpaperInfo( 1874): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1874): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothManagerService(  838): Sending unbind request.
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(764137571)( 1982): onUnbind() - calling cleanup
D/BluetoothAdapterService(764137571)( 1982): cleanup()
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/LGBluetoothAPIService( 1801): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1801): Message: 2
D/LGBluetoothAPIService( 1801): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3d02abee mBinding = false
D/LGBluetoothAPIService( 1801): Sending unbind request.
D/BluetoothAdapter( 1373): 374778791: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1373): 374778791: getState() :  mService = null. Returning STATE_OFF
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothAdapterService(764137571)( 1982): cleanup() - Cleaning up adapter native
I/bt-btif ( 1982): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1982): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 1982): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 1982): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1982): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1982): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1982): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1982): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1982): GKI_exit_task 2 done
I/GKI_LINUX( 1982): GKI_exit_task 1 done
I/GKI_LINUX( 1982): GKI_exit_task 0 done
I/BluetoothServiceJni( 1982): cleanupNative: return from cleanup
,W/LGBluetoothServiceJni( 1982): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 1982): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(764137571)( 1982): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(764137571)( 1982): cleanup() done
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     ( 1982): System.exit called, status: 0
I/AndroidRuntime( 1982): VM exiting with result code 0, cleanup skipped.
D/BluetoothAdapter( 1730): 942419397: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1730): 942419397: getState() :  mService = null. Returning STATE_OFF
,V/AudioFlinger(  283): 1982 died, releasing its sessions
V/AudioFlinger(  283):  pid 1749 @ 0
V/AudioFlinger(  283):  pid 3106 @ 1
V/AudioFlinger(  283):  pid 3106 @ 2
D/FMFRW_FmProxy( 1801): Fm Proxy object disconnected
,I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/LGBluetoothUserBindClient( 7746): [BTUI] initUserBindClient
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3b48def6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
,W/ContextImpl( 7746): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3b48def6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/InputDispatcher(  838): Focus entered window: Window{19359aa5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/Adreno-EGL( 1874): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 1874): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 1874): Build Date: 03/02/15 Mon
I/Adreno-EGL( 1874): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 1874): Remote Branch: 
I/Adreno-EGL( 1874): Local Patches: 
I/Adreno-EGL( 1874): Reconstruct Branch: 
I/OpenGLRenderer( 1874): Initialized EGL, version 1.4
I/ActivityManager(  838): Process com.android.bluetooth (pid 1982) has died
W/ActivityManager(  838): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
,I/art     (  838): Explicit concurrent mark sweep GC freed 32950(1977KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 4.304ms total 327.868ms
,I/art     (  838): WaitForGcToComplete blocked for 318.030ms for cause Explicit
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
,I/ActivityManager(  838): Start proc com.android.bluetooth for service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer: pid=7808 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1373): handleShortcutListChanged...
I/PhoneWindow( 1874): [setNavigationBarColor] color=0x 0
,D/DockEventReceiver( 7746): finishStartingService: stopping service
,D/administrator(  838): Handling package changes for user 0
D/LGBluetoothAuthorization( 7746): [BTUI] cancel All Notification
,I/NotificationManager( 7746): com.android.settings: cancel(17301632) by com.android.settings
,I/NotificationManager( 7746): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7746): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7746): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7746): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7746): com.android.settings: cancel(-1000041) by com.android.settings
W/ResourcesManager( 7808): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7808): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7808): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7808): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 7808): Loading JNI Library
I/ActivityManager(  838): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7828 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/InputMethodManagerService(  838): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,E/BluetoothServiceJni( 7808): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/BluetoothAdapterApp( 7808): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d32223a Instance Count = 1
,W/InputMethodManagerService(  838): Got RemoteException sending setActive(false) notification to pid 5360 uid 10316
D/BluetoothPermissionRequest( 7746): onReceive
D/BluetoothAdapterApp( 7808): onCreate
,D/LGBluetoothAuthorization( 7746): [BTUI] cancel All Notification
I/NotificationManager( 7746): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7746): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7746): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7746): com.android.settings: cancel(-1000021) by com.android.settings
,I/NotificationManager( 7746): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7746): com.android.settings: cancel(-1000041) by com.android.settings
I/LGBluetoothServiceJni( 7808): classInitNative: succeeds
D/BtSettings.ProfileConfig( 7808): [BTUI] HeadsetServiceis supported
,D/BtSettings.ProfileConfig( 7808): Adding HeadsetService
D/BtSettings.ProfileConfig( 7808): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding A2dpService
D/BtSettings.ProfileConfig( 7808): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding HidService
D/BtSettings.ProfileConfig( 7808): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding HealthService
D/LGBluetoothFeatureConfig( 7808): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 7808): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 7808): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding PanService
D/BtSettings.ProfileConfig( 7808): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding GattService
D/BtSettings.ProfileConfig( 7808): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 7808): [BTUI] region:EU country:EU
,D/BtSettings.ProfileConfig( 7808): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding SapService
D/BtSettings.ProfileConfig( 7808): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding FTPService
E/BtSettings.ProfileConfig( 7808): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 7808): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 7808): Adding OppService
D/BtSettings.ProfileConfig( 7808): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 7808): checkAndAdjustDeviceModeConfiguration deviceMode1
,D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7808): Unable to read settings
D/BtSettings.ProfileConfig( 7808): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7808): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 7808): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 7808): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 7808): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 7808): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 7808): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 7808): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 7808): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 7808): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 7808): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 7808): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 7808): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 7808): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 7808): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 7808): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 7808): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 7808): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 7808): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 7808): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/LGBluetoothUserBindClient( 7746): [BTUI] onServiceConnected
,I/art     (  838): Explicit concurrent mark sweep GC freed 5788(330KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.074ms total 371.452ms
,I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/FmServiceJni( 7808): classInitNative: succeeds
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  838): Timeline: Activity_windows_visible id: ActivityRecord{55c43fe u0 com.lge.launcher2/.Launcher t221} time:325460
D/FmService( 7808): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@1f102806servicecom.broadcom.fm.fmreceiver.FmService@20b70ec7
D/FmNativehandler( 7808): start
D/BluetoothRadioManager( 7808): [BTUI] getRadioManager()
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/BluetoothRadioManager( 7808): [BTUI] BluetoothRadioManager()
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d419ec:true
D/BluetoothRadioManager( 7808): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
W/IInputConnectionWrapper( 1874): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
V/FmService( 7808): FM Service  onCreate
D/FmService( 7808): Binding service...
D/FMFRW_FmProxy( 1801): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@3299e88f
D/LGBluetoothOppAdapter( 7808): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppReceiver( 7808): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 7808): [BTUI] cancel opp incoming file confirm notification
E/b       ( 1605): Unable to connect to the editor to retrieve text... will retry later
I/NotificationManager( 7808): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 7808): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 7808): com.android.bluetooth: cancel(-1) by com.android.bluetooth
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1874): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationService(  838): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/PCSuite ( 7828): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/JobSchedulerService(  838): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PCSuite ( 7828): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7828): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothAdapterService( 7808): Set JNI Library before classInit
,I/art     ( 1784): Background partial concurrent mark sweep GC freed 92196(5MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 9MB/15MB, paused 5.150ms total 79.082ms
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
D/BluetoothAdapterService(228070496)( 7808): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothAdapterService(228070496)( 7808): onCreate()
D/BluetoothAdapterState( 7808): make
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,I/bluedroid( 7808): init
I/BluetoothAdapterState( 7808): Entering OffState
I/bte_conf( 7808): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
I/bte_conf( 7808): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 7808): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 7808): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 7808): [BTUI] lge_load_bluetooth_address
I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7857 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/bt-btif ( 7808):  [BTUI] Load_abtddress
D/BTIF_CORE( 7808): [BTUI] lge_wait_for_load_bluetooth_address : waiting...
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/TaskPersister(  838): removeObsoleteFile: deleting file=222_task.xml
D/lge_bdaddr_loader( 7863): [BTUI] bdaddr_loader ::: START
,D/lge_bdaddr_loader( 7863): [BTUI] bluetooth_load_bdaddress
,I/LGFTMITEM( 7863): [GET_FTM][id=8], offset=16384
D/WifiController(  838): battery changed pluggedType: 2
D/lge_bdaddr_loader( 7863): [BTUI] bdaddr to set in property : F8:95:C7:87:85:54
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,D/AndroidRuntime( 7742): Shutting down VM
E/lge_bdaddr_loader( 7863): [BTUI] bluetooth_load_bdaddress : OK => F8:95:C7:87:85:54
D/lge_bdaddr_loader( 7863): [BTUI] bdaddr_loader ::: END
,D/BTIF_CORE( 7808): [BTUI] lge_wait_for_load_bluetooth_address : success!
D/bt-btif ( 7808): PERSIST_BDADDR_PROPERTY is  F8:95:C7:87:85:54
D/bt-btif ( 7808): Got prior random BDA F8:95:C7:87:85:54
,I/bluedroid( 7808): get_profile_interface socket
I/GKI_LINUX( 7808): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 7808): get_profile_interface map_client
E/BluetoothServiceJni( 7808): Error getting mapclient interface
D/bt-btif ( 7808): btif task starting
D/bt-btif ( 7808): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 7808): btif_get_adapter_property 2
I/bt-btif ( 7808): btif_get_adapter_property 2
I/bt-btif ( 7808): btif_get_adapter_property 1
I/bt-btif ( 7808): execute storage request event : 3
D/bt-btif ( 7808): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 7808): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterService( 7808): getAdapterService() - Service not available
D/LGBluetoothServiceAdapter( 7808): [BTUI] check adapter is available - false.
D/LGBluetoothSettingsDBObserver( 7808): [BTUI] register observer for LG device name DB
D/BluetoothAdapterProperties( 7808): Address is:F8:95:C7:87:85:54
I/bt-btif ( 7808): execute storage request event : 3
D/bt-btif ( 7808): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 7808): in, bd addr:, prop type:1, len:512
I/bt-btif ( 7808): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 7808): Name is: G3s-1
D/BluetoothManagerService(  838): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  838): Stored Bluetooth name: G3s-1
D/BluetoothAdapterService(228070496)( 7808): onBind()
D/BluetoothRadioManager( 7808): onServiceConnected: connected to AdapterService com.android.bluetooth.btservice.AdapterService
,D/BluetoothRadioManager( 7808): Message: 40
,D/BluetoothRadioManager( 7808): MESSAGE_RADIO_SERVICE_CONNECTED: 1
D/BluetoothRadioManager( 7808):  Turning on BT modules Radio on = false
V/BluetoothSapReceiver( 7808): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 7808): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
W/ResourcesManager( 7857): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  838): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7876 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d40e80:true
D/BluetoothAdapter( 7857): 764137571: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 7857): 764137571: getState() :  mService = null. Returning STATE_OFF
,W/ResourcesManager( 7876): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,W/ResourceType(  838): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  838): Killing 7289:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AuthorizationBluetoothService( 1730): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_7289/cgroup.procs: No such file or directory
,W/ContextImpl( 7746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/WiFiOffLoadBroadcast( 7746): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothPbapReceiver( 7808): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 7808): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7808): ***********state = 10
,D/WiFiOffLoadBroadcast( 7746): MCCMNC not supported: null
D/DockEventReceiver( 7746): finishStartingService: stopping service
V/LGMDMManagerInternal( 7808): Create singleton instance
I/PCSuite ( 7828): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7828): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7828): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7898 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/BluetoothPermissionRequest( 7746): onReceive
D/LGBluetoothFeatureConfig( 7746): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 7746): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7746): cancelDiscoverableAlarm(): Enter
,V/BluetoothSapReceiver( 7808): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 7808): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7876): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings

```
