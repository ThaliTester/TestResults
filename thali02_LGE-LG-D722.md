#### Test 55311151a2306df_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,D/AlertService( 5377): Beginning updateAlertNotification
D/AlertService( 5377): No fired or scheduled alerts
I/NotificationManager( 5377): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5377): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5377): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5377): No events found starting within 1 week.
D/AndroidRuntime( 5441): 
D/AndroidRuntime( 5441): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5441): CheckJNI is OFF
D/AndroidRuntime( 5441): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  960): setTaskToReturnTo : TaskRecord{2bcb0d91 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  960): setTaskToReturnTo : TaskRecord{2bcb0d91 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  960): AppWindowTokenEx init.. 
D/ContextHelper(  960): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  960): Focus left window: Window{3cb2c200 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5441): Shutting down VM
D/SplitWindow(  960): check instance of lgWin Window{7d79593 u0 Starting com.test.thalitest}
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5456 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1939): Closing mic
I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@2da04f3d
V/AudioRecord( 1939): stop()
D/AudioRecord( 1939): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb4319000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40362a0) usecase(7: audio-record)
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  960): Starting window displayed
I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1108119a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1374): draw background and invalidate : color = f000000
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/BarTransitions( 1374): draw background and invalidate : color = 18171717
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
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb4319000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioFlinger(  281): releasing 16 from 1939 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  960): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioSystem( 2002): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2696): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb4319000 exiting
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb40362a0)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40362a0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioFlinger(  281): removeClient_l() pid 1939, calling pid 281
V/AudioSystem( 3119): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
I/HotwordRecognitionRnr( 1939): Hotword detection finished
D/ContextHelper( 5456): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/Finsky  ( 5000): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  960): RTC_WAKEUP set : Alarm{3d0f7da type 0 when 1452155866571 com.android.vending} when 1452155866571
I/WebViewFactory( 5456): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  960): android: cancelAsUser(2) by android
I/LibraryLoader( 5456): Time to load native libraries: 2 ms (timestamps 2247-2249)
I/LibraryLoader( 5456): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5456): Binding Chromium to main looper Looper (main, tid 1) {bde105}
I/LibraryLoader( 5456): Expected native library version number "",actual native library version number ""
I/chromium( 5456): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5456): Initializing chromium process, singleProcess=true
W/art     ( 5456): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5456): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  960): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5488 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/chromium( 5456): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5456): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5456): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5456): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5456): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5456): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5456): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5456): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5456): Remote Branch: 
I/Adreno-EGL( 5456): Local Patches: 
I/Adreno-EGL( 5456): Reconstruct Branch: 
I/GservicesProvider( 5488): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient( 5488): GMS http client unavailable, use old client
V/AudioPolicyService(  281): registerClient() client 0xb551c7c0, uid 10316
D/BluetoothManagerService(  960): Message: 20
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20e75973:true
I/GoogleHttpClient( 5488): GMS http client unavailable, use old client
,D/BluetoothAdapterService(29395073)( 2002): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@201ee25f
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 5000): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/art     ( 5456): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5456): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5456): CordovaWebView is running on device made by: LGE
,I/ActivityManager(  960): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5531 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 5456): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5456): Attempt to remove local handle scope entry from IRT, ignoring
I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 5000): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Activity( 5456): Activity.onPostResume() called 
,D/OpenGLRenderer( 5456): Render dirty regions requested: true
I/OpenGLRenderer( 5456): Initialized EGL, version 1.4
W/ResourcesManager( 5531): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5531): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/OpenGLRenderer( 5456): Enabling debug mode 0
D/Atlas   ( 5456): Validating map...
,D/SplitWindow(  960): check instance of lgWin Window{2eeba690 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5456): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/MultiDex( 5531): VM with version 2.1.0 has multidex support
I/MultiDex( 5531): install
I/MultiDex( 5531): VM has multidex support, MultiDex support library is disabled.
,D/InputDispatcher(  960): Focus entered window: Window{2eeba690 u0 com.test.thalitest/com.test.thalitest.MainActivity}
V/JNIHelp ( 5531): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/InputMethodManagerService(  960): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +1s308ms
I/Timeline(  960): Timeline: Activity_windows_visible id: ActivityRecord{12bd24f6 u0 com.test.thalitest/.MainActivity t220} time:93055
,I/Timeline( 5456): Timeline: Activity_idle id: android.os.BinderProxy@37703f98 time:93082
,W/ActivityThread( 5531): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5531): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f7cfc3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5531): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5531): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5531): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,D/ChimeraCfgMgr( 5531): Reading stored module config
E/MDM     ( 1734): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/BindingManager( 5456): Cannot call determinedVisibility() - never saw a connection for the pid: 5456
D/LocationInitializer( 4014): Restart initialization of location
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
D/ChimeraCfgMgr( 5531): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/FusedLocationProvider( 1734): location=null
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/CAR.SERVICE( 5531): Connecting to CarCallService...
,I/art     ( 5531): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5531): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5531): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 5531): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5531): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5531): Creating a new PhoneAdapter instance
W/ActivityManager(  960): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5531): setListener: com.google.android.gms.car.dn@3c2e1c1a
W/ActivityManager(  960): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5531): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5531): Starting CarCallService with initial phone null
I/NotificationManager( 5531): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 5531): Package validated; name: com.android.vending
,I/NotificationManager( 5000): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5000): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/JsMessageQueue( 5456): Set native->JS mode to OnlineEventsBridgeMode
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5000): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5000): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{1b762a08 type 0 when 1452155868598 com.android.vending} when 1452155868598
,D/Finsky  ( 5000): [1] DailyHygiene.reschedule: Scheduling new run in 271 minutes (failures=4)
,D/jxcore_app_log( 5456): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622772224
D/JX-Cordova( 5456): jxcore cordova android initializing
,D/Finsky  ( 5000): [600] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1734): client connected with version: 8296000
I/art     ( 1734): Explicit concurrent mark sweep GC freed 27019(1609KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 13MB/22MB, paused 1.469ms total 89.067ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5000): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5000): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/NotificationManager(  960): android: cancelAsUser(2) by android
I/art     ( 5456): CheckpointMarkThreadRoots callback created = 0x998f74a0
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/art     ( 5456): CheckpointMarkThreadRoots callback created = 0x998f7470
,I/ActivityManager(  960): Killing 5244:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  960): failed to open /acct/uid_10018/pid_5244/cgroup.procs: No such file or directory
,I/ActivityManager(  960): Killing 5266:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 94580304500; DSPS: 3190503; Offset : -2797993367
,W/libprocessgroup(  960): failed to open /acct/uid_10069/pid_5266/cgroup.procs: No such file or directory
,I/art     (  960): Explicit concurrent mark sweep GC freed 23412(1059KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 3.078ms total 177.068ms
,W/jxcore-log( 5456): Initializing JXcore engine
,W/jxcore-log( 5456): JXcore engine is ready
W/jxcore-log( 5456): Starting JXcore engine
,W/.test.thalitest( 5456): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6772]" dev="sockfs" ino=6772 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5456): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5456): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5724]" dev="sockfs" ino=5724 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5456): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5456): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/.test.thalitest( 5456): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25751]" dev="sockfs" ino=25751 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ActivityManager(  960): Process com.google.android.gm (pid 5114) has died
,W/jxcore-log( 5456): Platform android
W/jxcore-log( 5456): 
W/jxcore-log( 5456): Process ARCH arm
W/jxcore-log( 5456): 
,I/ActivityManager(  960): Process com.lge.qremote (pid 5075) has died
,D/UEI.SmartControl( 5095): Service.onUnbind: IControl
D/UEI.SmartControl( 5095): Service.onDestroy
D/UEI.SmartControl( 5095): Shutdown IRRCPlayer... 
W/irrc_jni( 5095): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5095): ~IrrcClient ++ 
D/irrcClient( 5095): ~IrrcClient -- 
,W/irrc_jni( 5095): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5095): Blaster closed
D/UEI.SmartControl( 5095): Blaster closed
D/UEI.SmartControl( 5095): Shut down QS...
D/UEI.SmartControl( 5095): Stopped file observer...
I/UEI.SmartControl( 5095): QS lib stop result = true
D/UEI.SmartControl( 5095): QS shutdown complete
I/jxcore-log( 5456): JXcore Cordova bridge is ready!
I/jxcore-log( 5456): 
,W/jxcore-log( 5456): JXcore engine is started
I/Choreographer( 5456): Skipped 196 frames!  The application may be doing too much work on its main thread.
I/chromium( 5456): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/CAR.SERVICE( 5531): mConnectedToCar = false, abort
,E/ActivityThread( 5531): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@59476c2 that was originally bound here
E/ActivityThread( 5531): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@59476c2 that was originally bound here
E/ActivityThread( 5531): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5531): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5531): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5531): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5531): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5531): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5531): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5531): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5531): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5531): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5531): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5531): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5531): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5531): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5531): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5531): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5531): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5531): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5531): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5531): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5531): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5531): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 5531): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@93e9ac5 that was originally bound here
E/ActivityThread( 5531): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@93e9ac5 that was originally bound here
E/ActivityThread( 5531): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5531): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5531): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5531): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5531): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5531): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5531): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5531): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5531): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5531): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5531): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5531): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5531): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5531): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5531): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5531): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5531): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5531): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5531): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5531): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5531): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  960): Unbind failed: could not find connection for android.os.BinderProxy@4a147d9
I/jxcore-log( 5456): Toggling radios to true
I/jxcore-log( 5456): 
,D/BluetoothAdapter( 5456): enable(): BT is already enabled..!
D/WifiServiceImplEx(  960): setWifiEnabled: true pid=5456, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  960): setWifiEnabled: true pid=5456, uid=10316
,D/WifiServiceImplEx(  960): disconnect pid=5456, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  960): reconnect pid=5456, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5456): Radios toggled
I/jxcore-log( 5456): 
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5456): Received device characteristics:
I/jxcore-log( 5456): Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 5456): Bluetooth name: G3s-1
I/jxcore-log( 5456): Device name: LGE-LG-D722
I/jxcore-log( 5456): 
I/jxcore-log( 5456): Perf Test app loaded loaded
I/jxcore-log( 5456): 
I/jxcore-log( 5456): check test folder
I/jxcore-log( 5456): 
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/jxcore-log( 5456): found test : ./testFindPeers.js
I/jxcore-log( 5456): 
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-07 09:37:53.841 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/jxcore-log( 5456): found test : ./testSendData.js
I/jxcore-log( 5456): 
,I/ActivityManager(  960): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5604 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/WifiHS20(  960): hidePasspointNotification off =false
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  960): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  960): setSupplicantStateSCANNING
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-07 09:37:53.93 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-07 09:37:53.93 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,I/Choreographer( 5456): Skipped 124 frames!  The application may be doing too much work on its main thread.
I/chromium( 5456): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  960): Process com.google.android.apps.plus (pid 5283) has died
,I/ActivityManager(  960): Process com.android.calendar (pid 5377) has died
W/ResourcesManager( 5604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5604): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5604): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5604): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5604): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 5604): Using schema version: 115
,I/IndexDatabaseHelper( 5604): Index is fine
I/ActivityManager(  960): Process com.uei.lg.quicksetsdk.lite (pid 5095) has died
,V/WiFiOffLoadBroadcast( 5604): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5604): MCCMNC not supported: null
I/ActivityManager(  960): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5643 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  960): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5663 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 5663): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  960): Message: 20
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2be4bd9b:true
,D/BluetoothAdapterService(29395073)( 2002): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@201ee25f
D/BluetoothAdapterService(29395073)( 2002): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@201ee25f
V/WiFiOffLoadBroadcast( 5604): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5604): MCCMNC not supported: null
I/PCSuite ( 5643): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5643): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5643): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5604): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5604): MCCMNC not supported: null
I/ActivityManager(  960): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5688 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 25.159ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 21.384ms
V/LGMDMManager( 5663): Create singleton instance
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 26.862ms
,D/UEI.SmartControl( 5688): Quickset Services start...
I/UEI.SmartControl( 5688): Manufacture = LGE
D/UEI.SmartControl( 5688): File observer start...
E/UEI.SmartControl( 5688): IR Port is disabled: false
D/UEI.SmartControl( 5688): Starting file observer...
D/UEI.SmartControl( 5688): Extracting JNI libs...
,D/UEI.SmartControl( 5688): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5663): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5688): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5688): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5688): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5688): --- Selecting new region: 2
,I/UEI.SmartControl( 5688): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5688): Platform has CIR...
D/UEI.SmartControl( 5688): NO CIR support, need to check package...
I/UEI.SmartControl( 5688): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5688): QS Service created
E/UEI.SmartControl( 5688): QS start get config
,D/UEI.SmartControl( 5688): Loading JNI Libs...
,D/UEI.SmartControl( 5688):  configuring local db...
D/UEI.SmartControl( 5688):  ---- Has DB8: true
,D/UEI.SmartControl( 5688): QS start statue = true Error code = 0
D/UEI.SmartControl( 5688): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5688): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5688): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5688): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5688): IrrcClient ++ 
D/irrcClient( 5688): getIrrcService ++ 
,D/irrcClient( 5688): getIrrcService -- 
D/irrcClient( 5688): IrrcClient -- 
W/irrc_jni( 5688): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5688): Services init done
I/UEI.SmartControl( 5688): Device manager: loading config....
D/UEI.SmartControl( 5688): QS Service init finished
D/UEI.SmartControl( 5688): QS Service version name: 0.1.73
D/UEI.SmartControl( 5688): QS Service version code: 1073
,D/UEI.SmartControl( 5688): Config is loaded...
D/UEI.SmartControl( 5688): Service requested: Control
D/UEI.SmartControl( 5688): Internal service binding...
D/UEI.SmartControl( 5688): -----IControl: 11
D/UEI.SmartControl( 5688): Caller: com.lge.qremote
D/UEI.SmartControl( 5688): ------------ IControl registerCallback...
I/UEI.SmartControl( 5688): Registering callback...
,D/UEI.SmartControl( 5688): -----IControl: 19
D/UEI.SmartControl( 5688): Caller: com.lge.qremote
I/UEI.SmartControl( 5688): Registering Services Ready callback...
I/UEI.SmartControl( 5688): Notify client services are ready...
D/UEI.SmartControl( 5688): -----IControl: 8
D/UEI.SmartControl( 5688): Caller: com.lge.qremote
I/AudioManager( 5663): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5688):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5688): Notify AllClients services are ready: 0
I/AudioManager( 5663): getMode name:com.lge.qremote
,I/AudioManager( 5663): getMode name:com.lge.qremote
,I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/BluetoothAdapterService(29395073)( 2002): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@201ee25f
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5456): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5456): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 5456): BLE is supported
I/jxcore-log( 5456): 
V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{30e1e55a type 2 when 105101 com.google.android.gms} when 105101
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=112597395, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,D/WeatherService( 2688): 2 : TimeTick Intent has been received, Time(hour:min:sec) 9:38:0
,D/WeatherService( 2688): 2 : TimeTick Intent And Screen On
D/WeatherService( 2688): 2 : SDK version : 21
W/ActivityManager(  960): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2688): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2688): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2688): 2 : Fixed theme : optimus
D/WeatherReflect( 2688): 2 : Map key string is -2
,D/lim     ( 2688): 2 : time = 09:38
I/WeatherReflect( 2688): Model Name : LG-D722
D/WeatherTheme( 2688): 2 : Different view - status_min_formatted : 37 != 38
D/WeatherTheme( 2688): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2688): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2688): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/Weather4x2_optimus( 2688): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2688): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2688): forecast size is 0
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
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
,D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2688): 2 : update view, appWidgetId: 2
D/WeatherService( 2688): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 9:38:0
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=112597395 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/UEI.SmartControl( 5688): Internal timer expired: 1
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{1b6f4c68 type 0 when 1452155883286 com.android.vending} when 1452155883286
,W/ContextImpl( 3415): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 5000): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5000): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 114581262877; DSPS: 3845894; Offset : -2797979629
,I/MusicWidget( 2602): mDelayedStopHandler : unbind
,I/MusicBrowser( 2696): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2696): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2696): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2696): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2696): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2696): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2696): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  960):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@37703f98com.lge.music.MediaPlaybackService$6@15bb93f1
D/MusicBrowser( 2696): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3d579d26
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2696): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2696): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2696): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2696): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2696): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2696): reset
V/MediaPlayer[Native]( 2696): setListener
,V/MediaPlayer[Native]( 2696): disconnect
V/MediaPlayer[Native]( 2696): destructor
V/AudioFlinger(  281): releasing 19 from 2696 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2696): disconnect
D/MusicBrowser( 2696): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2696): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2696): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2696): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2696): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2696): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2696): [SmartShareManagerClient] unregisterListener: 89627606
W/SmartShareClient( 2696): [SmartShareManagerClient] unregisterListener invalid listener: 89627606
I/SmartShareClient( 2696): [SmartShareManagerClient] terminate service: 2696/MediaPlaybackService/395183228
E/HomeCloudIF( 2696): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2696): [SmartShareManagerClient] unbindService context:android.app.Application@154cbe57
V/CloudHub( 2696): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2696): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2696): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2696): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2696): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  960): Killing 5349:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/CloudHub( 2696): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29988
,W/libprocessgroup(  960): failed to open /acct/uid_10014/pid_5349/cgroup.procs: No such file or directory
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2696): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
,D/charger_monitor(  487): init target 500000
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/charger_monitor(  487): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  960): battery changed pluggedType: 2
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 134581984797; DSPS: 4501278; Offset : -2797989427
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{181b6881 type 2 when 142884 com.google.android.gms} when 142884
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2696): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2696): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/PowerManagerService(  960): ALS enabled for SRE
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29355 ms ago)
,D/qdlights(  960): set_light_backlight: 252
,D/qdlights(  960): set_light_backlight: 249
,D/qdlights(  960): set_light_backlight: 245
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{3248fd26 type 2 when 130001 com.google.android.gms} when 130001
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/qdlights(  960): set_light_backlight: 242
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/qdlights(  960): set_light_backlight: 239
D/qdlights(  960): set_light_backlight: 235
,D/qdlights(  960): set_light_backlight: 232
,D/qdlights(  960): set_light_backlight: 229
,D/qdlights(  960): set_light_backlight: 225
,D/qdlights(  960): set_light_backlight: 222
,D/qdlights(  960): set_light_backlight: 219
,D/qdlights(  960): set_light_backlight: 215
,D/qdlights(  960): set_light_backlight: 212
,D/qdlights(  960): set_light_backlight: 209
,D/qdlights(  960): set_light_backlight: 205
,D/qdlights(  960): set_light_backlight: 202
,D/qdlights(  960): set_light_backlight: 199
,D/qdlights(  960): set_light_backlight: 195
,D/qdlights(  960): set_light_backlight: 192
,D/qdlights(  960): set_light_backlight: 189
,D/qdlights(  960): set_light_backlight: 185
,D/qdlights(  960): set_light_backlight: 182
,D/qdlights(  960): set_light_backlight: 179
,D/qdlights(  960): set_light_backlight: 175
,D/qdlights(  960): set_light_backlight: 172
,D/qdlights(  960): set_light_backlight: 169
,D/qdlights(  960): set_light_backlight: 165
,D/qdlights(  960): set_light_backlight: 162
,D/qdlights(  960): set_light_backlight: 159
,D/qdlights(  960): set_light_backlight: 155
,D/qdlights(  960): set_light_backlight: 152
,D/qdlights(  960): set_light_backlight: 149
,D/qdlights(  960): set_light_backlight: 145
,D/qdlights(  960): set_light_backlight: 142
,D/qdlights(  960): set_light_backlight: 139
,D/qdlights(  960): set_light_backlight: 135
,D/qdlights(  960): set_light_backlight: 132
,D/qdlights(  960): set_light_backlight: 129
D/qdlights(  960): set_light_backlight: 125
,D/qdlights(  960): set_light_backlight: 122
,D/qdlights(  960): set_light_backlight: 119
,D/qdlights(  960): set_light_backlight: 115
,D/qdlights(  960): set_light_backlight: 112
,D/qdlights(  960): set_light_backlight: 109
,D/qdlights(  960): set_light_backlight: 105
,D/qdlights(  960): set_light_backlight: 102
,D/qdlights(  960): set_light_backlight: 99
,D/qdlights(  960): set_light_backlight: 95
,D/qdlights(  960): set_light_backlight: 92
,D/qdlights(  960): set_light_backlight: 89
,D/qdlights(  960): set_light_backlight: 85
,D/qdlights(  960): set_light_backlight: 82
,D/qdlights(  960): set_light_backlight: 79
,D/qdlights(  960): set_light_backlight: 75
,D/qdlights(  960): set_light_backlight: 72
,D/qdlights(  960): set_light_backlight: 69
,D/qdlights(  960): set_light_backlight: 65
,D/qdlights(  960): set_light_backlight: 62
,D/qdlights(  960): set_light_backlight: 59
,D/qdlights(  960): set_light_backlight: 55
,D/qdlights(  960): set_light_backlight: 52
,D/qdlights(  960): set_light_backlight: 49
,D/qdlights(  960): set_light_backlight: 45
,D/qdlights(  960): set_light_backlight: 42
,D/qdlights(  960): set_light_backlight: 39
,D/qdlights(  960): set_light_backlight: 35
,D/qdlights(  960): set_light_backlight: 32
,D/qdlights(  960): set_light_backlight: 29
,D/qdlights(  960): set_light_backlight: 25
,D/qdlights(  960): set_light_backlight: 22
,D/qdlights(  960): set_light_backlight: 19
,D/qdlights(  960): set_light_backlight: 15
,D/qdlights(  960): set_light_backlight: 12
,D/qdlights(  960): set_light_backlight: 10
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 154582733539; DSPS: 5156663; Offset : -2798003936
,I/PowerManagerService(  960): ALS enabled for SRE
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36232 ms ago)
I/PowerManagerService(  960): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  960): ALS enabled for SRE
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36244 ms ago)
W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  960): Sleeping (uid 1000)...
D/LPWGController(  960): [updateScreenState] screen on = false
D/LPWGController(  960): disable proximity sensor
D/LPWGController(  960): enable proximity sensor
,I/SensorManager(  960): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@25b7c5b2] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  960): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  960): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  960): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  960): activate: handle is 48, enable
V/sensors_hal_Ctx(  960): activate sensors is 1400000000000
D/sensors_hal_Thresh(  960): enable: handle=48
I/sensors_hal_SAM(  960): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  960): waitForResponse: timeout=1000
V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  960): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  960): enable: Received response: 0
D/PowerManagerServiceEx(  960): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36288 ms ago)
I/Adreno-EGL(  960): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  960): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  960): Build Date: 03/02/15 Mon
I/Adreno-EGL(  960): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  960): Remote Branch: 
I/Adreno-EGL(  960): Local Patches: 
I/Adreno-EGL(  960): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (210 us)
,I/Sensors (  418): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  960): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
,D/sensors_hal_Thresh(  960): processInd: handle 48, count=1
V/sensors_hal_Thresh(  960): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  960): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  960): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  960): poll: count: 256
I/sensors_hal_Ctx(  960): poll: released wakelock sensor_ind
D/sensors_hal_Util(  960): waitForResponse: timeout=0
D/LPWGController(  960): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  960): current mode = 1  value = 1 1
I/LPWGController(  960): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/ActivityManager(  960): Process com.google.android.gms (pid 4014) has died
,I/LPWGController(  960): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  960): set_light_backlight: 0
,I/SensorManager(  960): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  960): activate: handle is 46, disable
V/sensors_hal_Ctx(  960): activate sensors is 1000000000000
D/sensors_hal_LP2(  960): enable: handle=46
D/sensors_hal_LP2(  960): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  960): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  960): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  960): Display changed displayId=0
,V/sensors_hal_SAM(  960): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  960): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1753): Display #0 changed.
D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  960): Excessive delay in setPowerMode(): 193ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  960): Got set_interactive hint
,D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,E/WifiNative-wlan0(  960): doBoolean: disable
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
,D/WifiServerServiceExt(  960): sendKtScanInterval  mRtspPlay : false
I/WifiServerServiceExt(  960): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 960
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
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
D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
D/GpsLocationProvider(  960): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1806): lockStatus = 0
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1789): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1806): RESTART MSG
D/NfcServiceNXP( 1789): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1789): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1789): isRequireNfcCRouting() return true
D/LNfcService( 1789): isHCERoutingtoHost() return : true
D/NfcService( 1789): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): newParams.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): screenState= 3
D/NfcService( 1789): Discovery configuration equal, not updating.
D/SplitWindow(  960): check instance of lgWin Window{f0ba6b9 u0 SearchPanel}
,D/InputDispatcher(  960): Window went away: Window{334e085e u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/Ulp_jni (  960): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:38:51
D/WeatherService( 2688): 2 : ACTION screen on
,D/WeatherService( 2688): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:38:51
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_ON
,D/AppCleanupService( 3870): android.intent.action.SCREEN_ON
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 960
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
D/WifiController(  960): CMD_SCREEN_OFF 
,E/WifiNative-wlan0(  960): doBoolean: disable
D/WifiController(  960): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  960): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1,
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn on led
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
D/VolumeVibrator( 1806): clear
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1789): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1789): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:38:51
D/WeatherService( 2688): 2 : ACTION screen off
D/WeatherService( 2688): 2 : TimeTick Receiver Unregister
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:38:51
,W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  960): ACTION_SCREEN_OFF
D/AppCleanupService( 3870): android.intent.action.SCREEN_OFF
D/AppCleanupService( 3870): AppUsageStatsSaveTask
,E/NxpNfcJni( 1789): getReconnectState = 0x0
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
D/LNfcService( 1789): isRequireNfcCRouting() return true
D/LNfcService( 1789): isHCERoutingtoHost() return : true
D/NfcService( 1789): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): newParams.techmask= mTechMask: 0
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): screenState= 1
E/NxpNfcJni( 1789): getReconnectState = 0x0
,I/Sensors (  418): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{20d88afe type 2 when 162207 com.android.systemui} when 162207
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 174583413479; DSPS: 5812045; Offset : -2797995358
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  960): battery changed pluggedType: 2
D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=112597395, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{3500c25f type 2 when 187542 com.google.android.gms} when 187542
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=112597395 [*alarm*], flags=0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 194584087066; DSPS: 6467427; Offset : -2797993079
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{105e4ac type 2 when 187488 android} when 187488
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{436f575 type 2 when 188747 com.google.android.gms} when 188747
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager(  960): Start proc com.google.android.gms for service com.google.android.gms/.udc.service.UdcContextInitService: pid=5874 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 5874): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5874): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5874): VM with version 2.1.0 has multidex support
,I/MultiDex( 5874): install
I/MultiDex( 5874): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5874): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5874): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5874): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e125d7d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5874): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5874): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5874): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,E/MDM     ( 1734): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5874): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/VacuumService( 1734): Vacuum at: now=1452155984937 tag=VacuumService
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/art     ( 5874): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5874): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5874): Install completed successfully. count=14 extracted=0
,I/art     ( 5874): Background sticky concurrent mark sweep GC freed 25898(1407KB) AllocSpace objects, 4(64KB) LOS objects, 10% free, 10MB/11MB, paused 3.633ms total 107.632ms
,I/ActivityManager(  960): Process com.google.android.gms:car (pid 5531) has died
,W/IcingInternalCorpora( 5874): getNumBytesRead when not calculated.
,I/art     ( 5874): CheckpointMarkThreadRoots callback created = 0xaaf5cd40
,I/art     ( 5874): CheckpointMarkThreadRoots callback created = 0xaaf5cd30
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 214584945443; DSPS: 7122815; Offset : -2797989168
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{1be91ec8 type 2 when 218429 com.google.android.gms} when 218429
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 234585624811; DSPS: 7778197; Offset : -2797981083
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 254586423449; DSPS: 8433583; Offset : -2797976059
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 274587095524; DSPS: 9088966; Offset : -2798006018
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 294587871611; DSPS: 9744351; Offset : -2797993104
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 314588654988; DSPS: 10399736; Offset : -2797974386
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 334589514147; DSPS: 11055125; Offset : -2797997946
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/LocationManagerService(  960): remove 39892a56
,D/LocationManagerService(  960): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  960): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  960): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  960): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  960): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=112597395, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=112597395 [*alarm*], flags=0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 354590332265; DSPS: 11710511; Offset : -2797973830
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{533b61 type 2 when 369484 com.google.android.gms} when 369484
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 374591101060; DSPS: 12365897; Offset : -2797998519
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 394591904228; DSPS: 13021283; Offset : -2797988652
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 414592773128; DSPS: 13676671; Offset : -2797975911
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 434593454109; DSPS: 14332054; Offset : -2797996625
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 454594209310; DSPS: 14987439; Offset : -2798004833
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 474595030813; DSPS: 15642825; Offset : -2797974703
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 494595707732; DSPS: 16298208; Offset : -2797999636
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 514596388766; DSPS: 16953590; Offset : -2797989781
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 534597185217; DSPS: 17608976; Offset : -2797986813
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 554597880417; DSPS: 18264359; Offset : -2797993726
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 574598556972; DSPS: 18919741; Offset : -2797988506
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 594599321444; DSPS: 19575126; Offset : -2797986946
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 614600303677; DSPS: 20230518; Offset : -2797981250
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 634601065960; DSPS: 20885903; Offset : -2797981828
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 654601742463; DSPS: 21541285; Offset : -2797976972
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=112597395, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{18e9290c type 2 when 671590 com.google.android.gms} when 671590
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=112597395 [*alarm*], flags=0x0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 674602516049; DSPS: 22196671; Offset : -2797996661
,I/art     (  960): Explicit concurrent mark sweep GC freed 43285(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/34MB, paused 4.871ms total 304.182ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 694603316666; DSPS: 22852057; Offset : -2797989606
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 714604051450; DSPS: 23507441; Offset : -2797987113
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 734604871755; DSPS: 24162828; Offset : -2797990990
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 754605632789; DSPS: 24818213; Offset : -2797992922
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 774606744865; DSPS: 25473609; Offset : -2797979010
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 794607526003; DSPS: 26128995; Offset : -2797993621
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 814608200891; DSPS: 26784377; Offset : -2797988218
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 834608878280; DSPS: 27439759; Offset : -2797982191
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 854609746553; DSPS: 28095148; Offset : -2797998772
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 874610588369; DSPS: 28750535; Offset : -2797981035
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 894611265705; DSPS: 29405917; Offset : -2797975136
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 914612019968; DSPS: 30061302; Offset : -2797983657
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 934612792512; DSPS: 30716687; Offset : -2797973948
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=112597395, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{3d1dbcd3 type 2 when 951391 com.android.bluetooth} when 951391
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=112597395 [*alarm*], flags=0x0
,W/bt-smp  ( 2002): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2002): Plain text(LSB ~ MSB) = 58 6d 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2002): Encrypted text(LSB ~ MSB) = 03 5c c1 69 66 c4 46 03 c8 fe 07 3f 25 25 ba 45 
W/bt-btm  ( 2002): Stopping oneshot timer
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 954613373286; DSPS: 31372066; Offset : -2797973529
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 974614050101; DSPS: 32027449; Offset : -2797998436
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 994614832177; DSPS: 32682834; Offset : -2797979273
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1014615603732; DSPS: 33338220; Offset : -2798000993
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1034616384661; DSPS: 33993605; Offset : -2797983238
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1054617065852; DSPS: 34648988; Offset : -2798003639
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1074617821938; DSPS: 35304372; Offset : -2797980365
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
D/HeadsetStateMachine( 2002): Disconnected process message: 10, size: 0
W/Settings(  960): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  960): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  960): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1094618594013; DSPS: 35959758; Offset : -2798001747
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1114619356766; DSPS: 36615143; Offset : -2798001699
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1134620065665; DSPS: 37270526; Offset : -2797994991
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1154620947585; DSPS: 37925915; Offset : -2797997586
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1174621619244; DSPS: 38581297; Offset : -2797997730
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1194622292986; DSPS: 39236679; Offset : -2797995506
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1214622978187; DSPS: 39892061; Offset : -2797981327
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/UsageStatsService(  960): User[0] Flushing usage stats to disk
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1234623660419; DSPS: 40547444; Offset : -2798001052
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1254624337078; DSPS: 41202826; Offset : -2797995908
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1274625116810; DSPS: 41858211; Offset : -2797979169
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=112597395, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{14eda458 type 2 when 1275786 com.google.android.gms} when 1275786
D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=112597395 [*alarm*], flags=0x0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1294625877062; DSPS: 42513596; Offset : -2797981673
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1314626545493; DSPS: 43168978; Offset : -2797984890
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1334627217985; DSPS: 43824360; Offset : -2797983551
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1354628862039; DSPS: 44479774; Offset : -2797989034
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1374629648126; DSPS: 45135160; Offset : -2797994867
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1394630422181; DSPS: 45790545; Offset : -2797983465
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1414631107954; DSPS: 46445928; Offset : -2798000092
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1434631782218; DSPS: 47101310; Offset : -2797996745
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1454632457106; DSPS: 47756692; Offset : -2797993322
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1474633140327; DSPS: 48412074; Offset : -2797983415
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1494633906570; DSPS: 49067459; Offset : -2797978366
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1514634591666; DSPS: 49722842; Offset : -2797995410
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1534635462596; DSPS: 50378230; Offset : -2797978789
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1554636171494; DSPS: 51033614; Offset : -2798002131
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1574636882632; DSPS: 51688997; Offset : -2797992924
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1594637656896; DSPS: 52344382; Offset : -2797983395
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1614638505326; DSPS: 52999770; Offset : -2797987635
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1634639217974; DSPS: 53655153; Offset : -2797976943
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1654639988904; DSPS: 54310539; Offset : -2797999496
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1674641024782; DSPS: 54965933; Offset : -2798001191
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1694641798681; DSPS: 55621318; Offset : -2797990048
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1714642576173; DSPS: 56276703; Offset : -2797975651
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1734643161218; DSPS: 56932083; Offset : -2798000568
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1754643842304; DSPS: 57587465; Offset : -2797991571
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1774644602973; DSPS: 58242850; Offset : -2797993556
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1794645363851; DSPS: 58898235; Offset : -2797995643
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1814646139260; DSPS: 59553620; Offset : -2797983278
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1834646901492; DSPS: 60209005; Offset : -2797984090
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  960): acquireWakeLockInternal: lock=112597395, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=960
,V/AlarmManager(  960): ELAPSED_WAKEUP set : Alarm{3781b99c type 2 when 1851431 com.android.bluetooth} when 1851431
,W/bt-smp  ( 2002): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2002): Plain text(LSB ~ MSB) = 41 74 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2002): Encrypted text(LSB ~ MSB) = ba d7 00 54 5b 20 4c 56 4a 12 24 4c e2 21 28 19 
W/bt-btm  ( 2002): Stopping oneshot timer
I/ProcessStatsService(  960): Prepared write state in 15ms
,D/PowerManagerServiceEx(  960): releaseWakeLockInternal: lock=112597395 [*alarm*], flags=0x0
,I/ProcessStatsService(  960): Prepared write state in 9ms
,I/ProcessStatsService(  960): Prepared write state in 23ms
,I/ProcessStatsService(  960): Pruning old procstats: /data/system/procstats/state-2016-01-06-08-20-35.bin
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1854647664870; DSPS: 60864390; Offset : -2797983416
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  960): RTC_WAKEUP set : Alarm{1371bfa5 type 0 when 1452157475708 com.google.android.gms} when 1452157475708
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/libc-netbsd(  960): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  960): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  960): getAllProviders()=[passive, gps, network]
,I/NotificationManager( 5874): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/EventLogService( 5874): Aggregate from 1452155675303 (log), 1452155675303 (data)
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/Auth    ( 1734): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1874648436841; DSPS: 61519775; Offset : -2797974932
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  960): android: cancelAsUser(2) by android
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  960): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  960): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  960): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  960): tsOffsetIs: Apps: 1894649209073; DSPS: 62175161; Offset : -2797995740
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6271): 
D/AndroidRuntime( 6271): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6271): CheckJNI is OFF
D/AndroidRuntime( 6271): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  960): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  960): Killing 5456:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  960): WIN DEATH: Window{2eeba690 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  960): Focus left window: Window{2eeba690 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  960): Window went away: Window{2eeba690 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  960): Skipping PackageSetting{1b6c802e com.example.hello/10317} due to missing metadata
I/ActivityManager(  960): Killing 5643:com.lge.sync/1000 (adj 15): empty for 1803s
I/ActivityManager(  960): Killing 5604:com.android.settings/1000 (adj 15): empty for 1803s
I/ActivityManager(  960):   Force finishing activity ActivityRecord{12bd24f6 u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  960): Display changed displayId=0
D/DSDPConnection( 1753): Display #0 changed.
W/ActivityManager(  960): Spurious death for ProcessRecord{275146ef 5456:com.test.thalitest/u0a316}, curProc for 5456: null
W/libprocessgroup(  960): failed to open /acct/uid_1000/pid_5643/cgroup.procs: No such file or directory
W/libprocessgroup(  960): failed to open /acct/uid_1000/pid_5604/cgroup.procs: No such file or directory
I/ActivityManager(  960): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/art     ( 1939): Explicit concurrent mark sweep GC freed 2098(139KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 1.533ms total 88.368ms
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  960): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
W/System.err( 3415): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3415): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3415): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3415): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3415): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3415): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3415): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3415): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3415): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3415): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3415): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3415): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  960): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6304 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  960): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6310 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/art     (  960): Explicit concurrent mark sweep GC freed 30711(2MB) AllocSpace objects, 10(330KB) LOS objects, 33% free, 22MB/34MB, paused 2.604ms total 211.666ms
I/art     (  960): WaitForGcToComplete blocked for 125.460ms for cause Explicit
I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
I/Activity( 1879): Activity.onPostResume() called 
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
W/ResourcesManager( 6304): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 6304): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6304): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1108119a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  960): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  960): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  960): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  960): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1108119a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  960): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  960): Focus entered window: Window{3cb2c200 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/administrator(  960): Handling package changes for user 0
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/LockScreenSettings( 6310): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
I/art     (  960): Explicit concurrent mark sweep GC freed 3650(189KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.624ms total 275.096ms
D/AndroidRuntime( 6271): Shutting down VM
I/LGEmail ( 6304): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6304): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/InputMethodManagerService(  960): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  960): Got RemoteException sending setActive(false) notification to pid 5456 uid 10316
D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
W/IInputConnectionWrapper( 1879): getTextBeforeCursor on inactive InputConnection
I/Timeline( 1879): Timeline: Activity_idle id: android.os.BinderProxy@33ae653b time:1905065
I/Timeline(  960): Timeline: Activity_windows_visible id: ActivityRecord{28c4c5d2 u0 com.lge.launcher2/.Launcher t219} time:1905085
E/b       ( 1604): Unable to connect to the editor to retrieve text... will retry later
I/art     ( 1879): Explicit concurrent mark sweep GC freed 8197(458KB) AllocSpace objects, 5(681KB) LOS objects, 40% free, 15MB/25MB, paused 1.609ms total 50.442ms
W/IInputConnectionWrapper( 1879): getTextAfterCursor on inactive InputConnection
I/ThermalEngine(  295): Sensor:pa_therm0:29000 mC
I/PackageChangeReceiver( 6304): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/NotificationService(  960): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  960): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  960): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  960): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6353 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/TaskPersister(  960): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourcesManager(  960): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
