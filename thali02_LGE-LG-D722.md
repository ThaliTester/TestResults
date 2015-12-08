#### Test 50650278cc6513d_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{fd229f8 type 0 when 1449586566653 com.android.vending} when 1449586566653
--------- beginning of main
D/Finsky  ( 5048): [585] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5048): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 5421): 
D/AndroidRuntime( 5421): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5421): CheckJNI is OFF
D/AndroidRuntime( 5421): Calling main entry com.android.commands.am.Am
I/ActivityManager(  859): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  859): setTaskToReturnTo : TaskRecord{33159ed1 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  859): setTaskToReturnTo : TaskRecord{33159ed1 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  859): AppWindowTokenEx init.. 
D/ContextHelper(  859): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  859): Focus left window: Window{21485367 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5421): Shutting down VM
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  859): check instance of lgWin Window{9bb9cd3 u0 Starting com.test.thalitest}
I/ActivityManager(  859): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5449 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1936): Closing mic
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@15c54db6
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
I/WindowStateAnimator(  859): Starting window displayed
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@b914d1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = 16000000
D/BarTransitions( 1370): draw background and invalidate : color = 1e1d1d1d
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  281): stop_input_stream: exit: status(0)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
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
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioSystem(  859): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1746): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb3851000 exiting
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb546dde0)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3126): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1936, calling pid 281
V/AudioSystem( 2617): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): releasing 16 from 1936 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
I/HotwordRecognitionRnr( 1936): Hotword detection finished
D/ContextHelper( 5449): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5449): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5449): Time to load native libraries: 2 ms (timestamps 2793-2795)
I/LibraryLoader( 5449): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5449): Binding Chromium to main looper Looper (main, tid 1) {1de8cb5e}
I/LibraryLoader( 5449): Expected native library version number "",actual native library version number ""
I/chromium( 5449): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5449): Initializing chromium process, singleProcess=true
W/art     ( 5449): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5449): ApplicationContext is null in ApplicationStatus
W/chromium( 5449): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5449): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5449): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5449): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5449): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5449): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5449): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5449): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5449): Remote Branch: 
I/Adreno-EGL( 5449): Local Patches: 
I/Adreno-EGL( 5449): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb551c8c0, uid 10316
,D/BluetoothManagerService(  859): Message: 20
,D/BluetoothManagerService(  859): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ac61d7d:true
D/BluetoothAdapter( 5449): 393444443: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5449): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5449): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5449): CordovaWebView is running on device made by: LGE
,W/art     ( 5449): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5449): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 5449): Activity.onPostResume() called 
,D/OpenGLRenderer( 5449): Render dirty regions requested: true
I/OpenGLRenderer( 5449): Initialized EGL, version 1.4
D/OpenGLRenderer( 5449): Enabling debug mode 0
,D/Atlas   ( 5449): Validating map...
,D/SplitWindow(  859): check instance of lgWin Window{2bfe5fed u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5449): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  859): Focus entered window: Window{2bfe5fed u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,W/InputMethodManagerService(  859): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  859): Displayed com.test.thalitest/.MainActivity: +1s258ms
I/Timeline(  859): Timeline: Activity_windows_visible id: ActivityRecord{3d3e7d36 u0 com.test.thalitest/.MainActivity t220} time:93560
I/Timeline( 5449): Timeline: Activity_idle id: android.os.BinderProxy@2fd1571a time:93580
,W/BindingManager( 5449): Cannot call determinedVisibility() - never saw a connection for the pid: 5449
,D/JsMessageQueue( 5449): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{5cff50f type 0 when 1449586569496 com.android.vending} when 1449586569496
,D/Finsky  ( 5048): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/jxcore_app_log( 5449): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618647552
D/JX-Cordova( 5449): jxcore cordova android initializing
W/Finsky  ( 5048): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  859): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5539 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,I/art     ( 5449): Background sticky concurrent mark sweep GC freed 23304(1830KB) AllocSpace objects, 4(60KB) LOS objects, 4% free, 11MB/11MB, paused 5.214ms total 69.224ms
,I/art     ( 5449): CheckpointMarkThreadRoots callback created = 0x9f9494d0
,D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 5048): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 94740613407; DSPS: 3203435; Offset : -3028942597
,I/art     ( 5449): CheckpointMarkThreadRoots callback created = 0x9f9494a0
W/ResourcesManager( 5539): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5539): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5539): VM with version 2.1.0 has multidex support
I/MultiDex( 5539): install
I/MultiDex( 5539): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5539): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 5539): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5539): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d919970: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5539): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5539): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5539): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1969): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 3932): Restart initialization of location
D/AuthorizationBluetoothService( 1969): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1969): com.google.android.gms: cancel(0) by com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 3932): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1969): location=null
D/NativeLibraryUtils( 5539): Install completed successfully. count=13 extracted=0
,I/art     (  859): Explicit concurrent mark sweep GC freed 18079(804KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.382ms total 156.958ms
,I/art     ( 1969): Explicit concurrent mark sweep GC freed 11764(695KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/19MB, paused 1.516ms total 60.316ms
,I/art     ( 5539): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5539): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/NotificationManager( 5539): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5048): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5048): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5048): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5048): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 5048): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  859): RTC_WAKEUP set : Alarm{264cc6e1 type 0 when 1449586571048 com.android.vending} when 1449586571048
,D/Finsky  ( 5048): [1] DailyHygiene.reschedule: Scheduling new run in 818 minutes (failures=5)
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 5048): [594] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/jxcore-log( 5449): Initializing JXcore engine
,W/jxcore-log( 5449): JXcore engine is ready
W/jxcore-log( 5449): Starting JXcore engine
,W/.test.thalitest( 5449): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[4915]" dev="sockfs" ino=4915 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5449): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5449): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5017]" dev="sockfs" ino=5017 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5449): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/.test.thalitest( 5449): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5449): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25983]" dev="sockfs" ino=25983 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5449): Platform android
W/jxcore-log( 5449): 
W/jxcore-log( 5449): Process ARCH arm
W/jxcore-log( 5449): 
,I/jxcore-log( 5449): JXcore Cordova bridge is ready!
I/jxcore-log( 5449): 
,W/jxcore-log( 5449): JXcore engine is started
I/chromium( 5449): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5449): Skipped 186 frames!  The application may be doing too much work on its main thread.
,E/jxcore  ( 5449): Error!: missing ) after argument list
E/jxcore  ( 5449): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5449): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/InputDispatcher(  859): Focus left window: Window{2bfe5fed u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1403 us)
,W/PluginManager( 5449): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 39ms. Plugin should use CordovaInterface.getThreadPool().
I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
,I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
D/WeatherAncestor( 2584): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:56:13
D/UpdateThreadPoolManager( 2584): 2 : This is isUpdating : false
D/WeatherService( 2584): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2584): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 2584): 2 : shouldTimeTickRegistered().........
,D/WeatherAncestor( 2584): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:56:13
D/WeatherService( 2584): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@b914d1,  pkg=WindowManager.LayoutParams
W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/Weather.Utils( 2584): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2584): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2584): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2584): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 2584): 2 : requestRefreshAppWidget, isUpdateStart : false
D/InputDispatcher(  859): Focus entered window: Window{21485367 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/UpdateThreadPoolManager( 2584): 2 : This is isUpdating : false
D/WeatherService( 2584): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2584): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2584): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2584): 2 : Fixed theme : optimus
D/WeatherReflect( 2584): 2 : Map key string is -2
,D/lim     ( 2584): 2 : time = 15:56
I/WeatherReflect( 2584): Model Name : LG-D722
D/WeatherTheme( 2584): 2 : exactly same view!
D/WeatherTheme( 2584): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2584): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2584): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2584): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  859): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/IInputConnectionWrapper( 5449): showStatusIcon on inactive InputConnection
I/SystemUI[Framework](  859): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
,I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 1879): Timeline: Activity_idle id: android.os.BinderProxy@3dacd8fc time:97924
W/PhoneWindowManagerEx(  859): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  859): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  859): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@b914d1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  859): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/HotwordRecognitionRnr( 1936): Starting hotword detection.
I/MicrophoneInputStream( 1936): mic_starting com.google.android.apps.gsa.speech.audio.u@35fa365e
V/AudioRecord( 1936): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
,V/AudioRecord( 1936): set(): mSessionId 22
D/BarTransitions( 1370): draw background and invalidate : color = e8000000
V/AudioPolicyManager(  281): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  281): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  281): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  281): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e4c0)
V/audio_hw_primary(  281): adev_open_input_stream: exit
V/AudioFlinger(  281): openInput_l() openInputStream returned input 0xb546e4c0, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  281): openInput_l() created record thread: ID 23 thread 0xb3851000
V/AudioSystem(  281): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1370): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1746): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1936): ioConfigChanged() event 3, ioHandle 23
,V/AudioSystem(  859): ioConfigChanged() event 3, ioHandle 23
D/BarTransitions( 1370): draw background and invalidate : color = e1d8d8d8
V/AudioSystem( 2617): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioSystem( 3126): ioConfigChanged() event 3, ioHandle 23
,V/AudioFlinger(  281): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  281): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  281): acquiring 22 from 1936, for -1
V/AudioFlinger(  281):  added new entry for 22
I/AudioFlinger(  281): AudioFlinger's thread 0xb3851000 ready to run
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e4c0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e4c0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioRecord( 1936): start, sync event 0 trigger session 0
V/AudioRecord( 1936): mAudioRecord->start()
V/AudioFlinger(  281): RecordHandle::start()
V/AudioFlinger(  281): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  281): startInput() module primary->input primary(23)
V/AudioPolicyManager(  281): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  281): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  281): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  281): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  281): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  281): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  281): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  281): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  281): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
V/AudioFlinger::PatchPanel(  281): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  281): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  281): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  281): setParameters(): io 23, keyvalue hotword_active=1, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): AudioPolicy,Manager::startInput() input source = 1999
,I/ActivityManager(  859): Process com.google.android.talk (pid 5122) has died
I/MicrophoneInputStream( 1936): mic_started com.google.android.apps.gsa.speech.audio.u@35fa365e
,V/msm8974_platform(  281): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  281): start_input_stream: enter: stream(0xb546e4c0)usecase(7: audio-record)
V/voice   (  281): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  281): start_input_stream: usecase(7)
E/audio_hw_primary(  281): select_devices: enter and usecase(7)
V/msm8974_platform(  281): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  281): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  281): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  281): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  281): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  281): enable_snd_device: enter  144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  281): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  281): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  281): ACDB -> send_adm_topology
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  281): ACDB -> send_asm_topology
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  281): ACDB -> send_audtable
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  281): ACDB -> send_audvoltable
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  281): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  281): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  281): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  281): enable_audio_route: exit
D/audio_hw_primary(  281): select_devices: done
V/audio_hw_primary(  281): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  281): start_input_stream: exit
,I/HotwordWorker( 1936): onReady
,I/Timeline(  859): Timeline: Activity_windows_visible id: ActivityRecord{34fef00 u0 com.lge.launcher2/.Launcher t219} time:98228
D/InputDispatcher(  859): Window went away: Window{2bfe5fed u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/OpenGLRenderer( 1879): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1879): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1879): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1879): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1879): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1879): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/ActivityManager(  859): Killing 5233:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  859): failed to open /acct/uid_10069/pid_5233/cgroup.procs: No such file or directory
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{2cc82bb7 type 2 when 101729 com.google.android.gms} when 101729
,D/libc-netbsd( 1969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager(  859): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5623 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5623): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5623): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5623): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5623): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5623): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5623): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5623): MmsConfig.loadFromResources
E/Babel_SMS( 5623): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5623): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5623): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5623): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5623): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5623): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5623): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5623): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5623): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 5623): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5623): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5623): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5623): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5623): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5623): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5623): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5623): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5623): found sensor: Motion Accel, handle=46
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  479): init target 500000
,W/Settings( 5623): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5623): startup - clean
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
D/WifiController(  859): battery changed pluggedType: 2
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,I/Babel   ( 5623): deleted: false for 0
D/charger_monitor(  479): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/art     ( 5623): CheckpointMarkThreadRoots callback created = 0xb042d520
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
W/AudioCapabilities( 5623): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5623): Unsupported mime audio/adpcm
W/AudioCapabilities( 5623): Unsupported mime audio/g726
I/art     ( 5623): CheckpointMarkThreadRoots callback created = 0xb042d500
W/AudioCapabilities( 5623): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5623): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5623): Unsupported mime video/mjpg
,W/VideoCapabilities( 5623): Unsupported mime video/theora
W/AudioCapabilities( 5623): Unsupported mime audio/evrc
,W/AudioCapabilities( 5623): Unsupported mime audio/qcelp
W/VideoCapabilities( 5623): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5623): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5623): Unsupported mime audio/qcelp
W/AudioCapabilities( 5623): Unsupported mime audio/evrc
W/VideoCapabilities( 5623): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5623): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5623): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5623): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5623): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5623): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  859): Killing 4997:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  859): failed to open /acct/uid_10086/pid_4997/cgroup.procs: No such file or directory
,I/vclib   ( 5623): onServiceConnected
W/Babel   ( 5623): Attempted to change video mute state without an active call.
I/NotificationManager( 5623): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  859): RTC_WAKEUP set : Alarm{220570a7 type 0 when 1449586585783 com.android.vending} when 1449586585783
,W/ContextImpl( 3402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 5048): [585] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5048): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 114742384388; DSPS: 3858853; Offset : -3028939892
,I/MusicWidget( 2533): mDelayedStopHandler : unbind
,I/MusicBrowser( 2617): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2617): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2617): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2617): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2617): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2617): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2617): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2617): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  859):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@22cde1c5com.lge.music.MediaPlaybackService$6@2fd1571a
,D/MusicBrowser( 2617): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2617): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@17737c5b
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2617): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2617): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2617): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2617): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2617): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2617): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2617): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2617): reset
V/MediaPlayer[Native]( 2617): setListener
,V/MediaPlayer[Native]( 2617): disconnect
V/MediaPlayer[Native]( 2617): destructor
V/AudioFlinger(  281): releasing 19 from 2617 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2617): disconnect
D/MusicBrowser( 2617): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2617): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2617): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2617): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2617): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2617): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2617): [SmartShareManagerClient] unregisterListener: 482882123
W/SmartShareClient( 2617): [SmartShareManagerClient] unregisterListener invalid listener: 482882123
I/SmartShareClient( 2617): [SmartShareManagerClient] terminate service: 2617/MediaPlaybackService/384642201
E/HomeCloudIF( 2617): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2617): [SmartShareManagerClient] unbindService context:android.app.Application@31927428
V/CloudHub( 2617): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2617): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2617): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2617): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2617): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  859): Killing 5261:com.google.android.gm/u0a53 (adj 15): empty #11
I/CloudHub( 2617): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29985
,W/libprocessgroup(  859): failed to open /acct/uid_10053/pid_5261/cgroup.procs: No such file or directory
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2617): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19975
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 134744929693; DSPS: 4514297; Offset : -3028957854
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  859): acquireWakeLockInternal: lock=902434947, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=859
,D/WeatherService( 2584): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:57:0
D/WeatherService( 2584): 2 : TimeTick Intent And Screen On
D/WeatherService( 2584): 2 : SDK version : 21
W/ActivityManager(  859): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2584): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2584): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2584): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2584): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 2584): 2 : This is isUpdating : false
D/WeatherService( 2584): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2584): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2584): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2584): 2 : Fixed theme : optimus
D/WeatherReflect( 2584): 2 : Map key string is -2
D/lim     ( 2584): 2 : time = 15:57
I/WeatherReflect( 2584): Model Name : LG-D722
D/WeatherTheme( 2584): 2 : Different view - status_min_formatted : 56 != 57
D/WeatherTheme( 2584): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2584): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2584): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2584): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2584): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2584): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2584): forecast size is 0
D/Theme   ( 2584): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2584): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2584): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2584): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2584): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2584): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2584): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2584): url is : null
D/Theme   ( 2584): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2584): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2584): 2 : update view, appWidgetId: 2
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/WeatherService( 2584): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:57:0
,D/PowerManagerServiceEx(  859): releaseWakeLockInternal: lock=902434947 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/CloudHub( 2617): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2617): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/PowerManagerService(  859): ALS enabled for SRE
,D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29048 ms ago)
D/qdlights(  859): set_light_backlight: 251
,D/qdlights(  859): set_light_backlight: 248
,D/qdlights(  859): set_light_backlight: 245
,D/qdlights(  859): set_light_backlight: 241
,D/qdlights(  859): set_light_backlight: 238
,D/qdlights(  859): set_light_backlight: 235
,D/qdlights(  859): set_light_backlight: 231
,D/qdlights(  859): set_light_backlight: 228
,D/qdlights(  859): set_light_backlight: 225
,D/qdlights(  859): set_light_backlight: 221
,D/qdlights(  859): set_light_backlight: 218
,D/qdlights(  859): set_light_backlight: 215
,D/qdlights(  859): set_light_backlight: 211
,D/qdlights(  859): set_light_backlight: 208
,D/qdlights(  859): set_light_backlight: 205
,D/qdlights(  859): set_light_backlight: 201
,D/qdlights(  859): set_light_backlight: 198
,D/qdlights(  859): set_light_backlight: 195
,D/qdlights(  859): set_light_backlight: 191
,D/qdlights(  859): set_light_backlight: 188
,D/qdlights(  859): set_light_backlight: 185
,D/qdlights(  859): set_light_backlight: 181
,D/qdlights(  859): set_light_backlight: 178
,D/qdlights(  859): set_light_backlight: 175
,D/qdlights(  859): set_light_backlight: 171
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{2cce0954 type 2 when 130637 com.google.android.gms} when 130637
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/qdlights(  859): set_light_backlight: 168
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/qdlights(  859): set_light_backlight: 165
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/qdlights(  859): set_light_backlight: 161
D/qdlights(  859): set_light_backlight: 158
,D/qdlights(  859): set_light_backlight: 155
,D/qdlights(  859): set_light_backlight: 151
,D/qdlights(  859): set_light_backlight: 148
,D/qdlights(  859): set_light_backlight: 145
,D/qdlights(  859): set_light_backlight: 141
,D/qdlights(  859): set_light_backlight: 138
,D/qdlights(  859): set_light_backlight: 135
D/qdlights(  859): set_light_backlight: 131
,D/qdlights(  859): set_light_backlight: 128
,D/qdlights(  859): set_light_backlight: 125
,D/qdlights(  859): set_light_backlight: 121
D/qdlights(  859): set_light_backlight: 118
,D/qdlights(  859): set_light_backlight: 115
,D/qdlights(  859): set_light_backlight: 111
,D/qdlights(  859): set_light_backlight: 108
,D/qdlights(  859): set_light_backlight: 105
,D/qdlights(  859): set_light_backlight: 101
,D/qdlights(  859): set_light_backlight: 98
,D/qdlights(  859): set_light_backlight: 95
,D/qdlights(  859): set_light_backlight: 91
,D/qdlights(  859): set_light_backlight: 88
,D/qdlights(  859): set_light_backlight: 85
,D/qdlights(  859): set_light_backlight: 81
,D/qdlights(  859): set_light_backlight: 78
,D/qdlights(  859): set_light_backlight: 75
,D/qdlights(  859): set_light_backlight: 71
,D/qdlights(  859): set_light_backlight: 68
,D/qdlights(  859): set_light_backlight: 65
,D/qdlights(  859): set_light_backlight: 61
,D/qdlights(  859): set_light_backlight: 58
,D/qdlights(  859): set_light_backlight: 55
,D/qdlights(  859): set_light_backlight: 51
,D/qdlights(  859): set_light_backlight: 48
,D/qdlights(  859): set_light_backlight: 45
,D/qdlights(  859): set_light_backlight: 41
,D/qdlights(  859): set_light_backlight: 38
,D/qdlights(  859): set_light_backlight: 35
,D/qdlights(  859): set_light_backlight: 31
,D/qdlights(  859): set_light_backlight: 28
,D/qdlights(  859): set_light_backlight: 25
,D/qdlights(  859): set_light_backlight: 21
,D/qdlights(  859): set_light_backlight: 18
,D/qdlights(  859): set_light_backlight: 15
,D/qdlights(  859): set_light_backlight: 11
,D/qdlights(  859): set_light_backlight: 10
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 154751238696; DSPS: 5169864; Offset : -3028967891
,I/PowerManagerService(  859): ALS enabled for SRE
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36045 ms ago)
I/PowerManagerService(  859): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  859): ALS enabled for SRE
,D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36063 ms ago)
W/ContextImpl(  859): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  859): Sleeping (uid 1000)...
D/LPWGController(  859): [updateScreenState] screen on = false
,D/LPWGController(  859): disable proximity sensor
D/LPWGController(  859): enable proximity sensor
I/SensorManager(  859): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2589c0fd] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  859): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  859): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  859): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  859): activate: handle is 48, enable
V/sensors_hal_Ctx(  859): activate sensors is 1400000000000
D/sensors_hal_Thresh(  859): enable: handle=48
,I/sensors_hal_SAM(  859): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  859): waitForResponse: timeout=1000
V/sensors_hal_SAM(  859): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  859): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  859): enable: Received response: 0
D/PowerManagerServiceEx(  859): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36107 ms ago)
I/Adreno-EGL(  859): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  859): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  859): Build Date: 03/02/15 Mon
I/Adreno-EGL(  859): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  859): Remote Branch: 
I/Adreno-EGL(  859): Local Patches: 
I/Adreno-EGL(  859): Reconstruct Branch: 
,I/Sensors (  432): sns_pwr.c(273):acquiring wakelock
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
I/LPWGController(  859): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  859): set_light_backlight: 0
,I/SensorManager(  859): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  859): activate: handle is 46, disable
V/sensors_hal_Ctx(  859): activate sensors is 1000000000000
D/sensors_hal_LP2(  859): enable: handle=46
D/sensors_hal_LP2(  859): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  859): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  859): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  859): Display changed displayId=0
V/sensors_hal_SAM(  859): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  859): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1746): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  859): Excessive delay in setPowerMode(): 234ms
,I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  859): Got set_interactive hint
D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
D/KeyguardViewMediator( 1370): notifyScreenOffLocked
,I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1370): handleNotifyScreenOff
I/HotwordDetector( 1936): Closing mic
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@35fa365e
,V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
,V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 23
D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 24
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e4c0) usecase(7: audio-record)
,D/WifiServerServiceExt(  859): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 859
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
,D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  281): stop_input_stream: exit: status(0)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/AudioPolicyManager(  281): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  281): removeAudioPatch() handle 20 af handle 24
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=0, io 23 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
E/lge_audio_pcm_dump(  281): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=0, io 23
V/AudioFlinger(  281): setParameters(): io 23, keyvalue hotword_active=0, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3851000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1936): stop()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
,V/AudioFlinger(  281): releasing 22 from 1936 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 23
V/AudioPolicyManager(  281): closeInput(23)
V/AudioFlinger(  281): closeInput() 23
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 1746): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  281): ThreadBase::exit
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem(  859): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  281): RecordThread 0xb3851000 exiting
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 2617): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 3126): ioConfigChanged() event 4, ioHandle 23
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb546e4c0)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e4c0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1936, calling pid 281
I/HotwordRecognitionRnr( 1936): Hotword detection finished
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
D/GpsLocationProvider(  859): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1841): |CORE| sendScreenState: state:true
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
,D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1805): lockStatus = 0
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1805): RESTART MSG
D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
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
D/Ulp_jni (  859): JNI:system_update. Event-0
,D/SplitWindow(  859): check instance of lgWin Window{16ac66c0 u0 SearchPanel}
,D/InputDispatcher(  859): Window went away: Window{e7f3e81 u0 SearchPanel}
,I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2584): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:57:12
D/WeatherService( 2584): 2 : ACTION screen on
D/WeatherService( 2584): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2584): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2584): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:57:12
D/AppCleanupService( 3864): android.intent.action.SCREEN_ON
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 859
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
D/WifiController(  859): CMD_SCREEN_OFF 
D/WifiController(  859): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  859): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1841): |CORE| sendScreenState: state:false
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1805): clear
,I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
W/ActivityManager(  859): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2584): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:57:12
D/WeatherService( 2584): 2 : ACTION screen off
D/WeatherService( 2584): 2 : TimeTick Receiver Unregister
D/WeatherService( 2584): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:57:12
,D/AppCleanupService( 3864): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3864): AppUsageStatsSaveTask
E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
D/LNfcService( 1788): isRequireNfcCRouting() return true
D/LNfcService( 1788): isHCERoutingtoHost() return : true
D/NfcService( 1788): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): newParams.techmask= mTechMask: 0
D/NfcService( 1788): mEnableLPD: true
D/NfcService( 1788): mEnableReader: false
D/NfcService( 1788): mEnableHostRouting: true
D/NfcService( 1788): screenState= 1
E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/Sensors (  432): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{27366ff9 type 2 when 162002 com.android.systemui} when 162002
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1746): getCallState : 0
D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  859): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 174753783532; DSPS: 5825307; Offset : -3028954244
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/WifiController(  859): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{1be1bb3e type 2 when 163071 com.google.android.gms} when 163071
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{361dcd9f type 2 when 187329 com.google.android.gms} when 187329
V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{7512eec type 2 when 190462 com.google.android.gms} when 190462
D/libc-netbsd( 1969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 194756330449; DSPS: 6480750; Offset : -3028940312
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 214765002998; DSPS: 7136395; Offset : -3028965350
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{7a12531 type 2 when 188553 android} when 188553
,D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  859): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  859): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 234767540383; DSPS: 7791838; Offset : -3028960742
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 254770419334; DSPS: 8447292; Offset : -3028950313
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 274773601046; DSPS: 9102756; Offset : -3028942507
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 294776142286; DSPS: 9758200; Offset : -3028965031
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 314778416396; DSPS: 10413634; Offset : -3028950941
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 334780947438; DSPS: 11069077; Offset : -3028951061
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  859): remove 242ce68e
,D/LocationManagerService(  859): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  859): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  859): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  859): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  859): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  859): acquireWakeLockInternal: lock=902434947, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=859
,V/AlarmManager(  859): ELAPSED_WAKEUP set : Alarm{dd7f416 type 2 when 313180 com.google.android.gms} when 313180
D/PowerManagerServiceEx(  859): releaseWakeLockInternal: lock=902434947 [*alarm*], flags=0x0
,D/libc-netbsd( 1969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 354783487161; DSPS: 11724520; Offset : -3028944427
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 374786153038; DSPS: 12379968; Offset : -3028963784
,V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1969): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  859): android: cancelAsUser(2) by android
,D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  859): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 394788551885; DSPS: 13035406; Offset : -3028945309
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 414791099013; DSPS: 13690850; Offset : -3028961604
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  859): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  859): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  859): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  859): tsOffsetIs: Apps: 434793642652; DSPS: 14346293; Offset : -3028951211
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC

```
