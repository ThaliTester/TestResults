#### Test 50650278352fc1f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/AndroidRuntime( 5337): 
D/AndroidRuntime( 5337): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5337): CheckJNI is OFF
D/Finsky  ( 5023): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
--------- beginning of system
V/AlarmManager(  964): RTC_WAKEUP set : Alarm{2d500183 type 0 when 1449588487925 com.android.vending} when 1449588487925
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  964): android: cancelAsUser(2) by android
D/AndroidRuntime( 5337): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  964): setTaskToReturnTo : TaskRecord{b4692ad #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  964): setTaskToReturnTo : TaskRecord{b4692ad #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  964): AppWindowTokenEx init.. 
D/ContextHelper(  964): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  964): Focus left window: Window{230c32ce u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5337): Shutting down VM
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  964): check instance of lgWin Window{194891cf u0 Starting com.test.thalitest}
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5364 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1934): Closing mic
I/MicrophoneInputStream( 1934): mic_close com.google.android.apps.gsa.speech.audio.u@2e8e33d3
V/AudioRecord( 1934): stop()
D/AudioRecord( 1934): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
I/WindowStateAnimator(  964): Starting window displayed
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 17
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3c50000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/SystemUI[Framework](  964): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
W/PhoneWindowManagerEx(  964): Call!!!getLGSystemUiVisibility. =0x0
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/StatusBarManagerServiceEx(  964): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  964): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@34e223f4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1369): draw background and invalidate : color = 10000000
D/BarTransitions( 1369): draw background and invalidate : color = 100f0f0f
V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
W/Finsky  ( 5023): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/audio_hw_primary(  279): disable_audio_route: exit
E/audio_hw_primary(  279): disable_snd_device: enter 144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  279): stop_input_stream: exit: status(0)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  279): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  279): setParameters(): io 17, keyvalue hotword_active=0, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3c50000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 95168840853; DSPS: 3217240; Offset : -3015624509
V/AudioRecord( 1934): stop()
V/AudioRecord( 1934): stop()
V/AudioRecord( 1934): stop()
V/AudioFlinger(  279): releasing 16 from 1934 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
,V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
,V/AudioSystem( 1934): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioSystem(  964): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread 0xb3c50000 exiting
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3145): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2001): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1934, calling pid 279
I/HotwordRecognitionRnr( 1934): Stopping hotword detection.
I/HotwordRecognitionRnr( 1934): Hotword detection finished
I/NotificationManager(  964): android: cancelAsUser(2) by android
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  964): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5390 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/ContextHelper( 5364): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 23.462ms
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 22.418ms
I/NotificationManager(  964): android: cancelAsUser(2) by android
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 25.783ms
W/ResourcesManager( 5390): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5390): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5023): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/WebViewFactory( 5364): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/MultiDex( 5390): VM with version 2.1.0 has multidex support
I/MultiDex( 5390): install
I/MultiDex( 5390): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5390): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/LibraryLoader( 5364): Time to load native libraries: 10 ms (timestamps 5555-5565)
I/LibraryLoader( 5364): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5364): Binding Chromium to main looper Looper (main, tid 1) {3a3e724}
I/LibraryLoader( 5364): Expected native library version number "",actual native library version number ""
,I/chromium( 5364): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityThread( 5390): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5390): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c9d26c6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5390): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5390): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5390): com.google.android.gms: cancel(39789) by com.google.android.gms
I/BrowserStartupController( 5364): Initializing chromium process, singleProcess=true
W/art     ( 5364): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5364): ApplicationContext is null in ApplicationStatus
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1965): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 3964): Restart initialization of location
D/AuthorizationBluetoothService( 1965): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/chromium( 5364): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1965): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 3964): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/chromium( 5364): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5364): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5364): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5364): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5364): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5364): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5364): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5364): Remote Branch: 
I/Adreno-EGL( 5364): Local Patches: 
I/Adreno-EGL( 5364): Reconstruct Branch: 
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1965): location=null
,D/NativeLibraryUtils( 5390): Install completed successfully. count=13 extracted=0
,V/AudioPolicyService(  279): registerClient() client 0xb406a180, uid 10316
,D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e57bdbb:true
D/BluetoothAdapter( 5364): 113922448: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5364): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5364): onDetachedFromWindow called when already detached. Ignoring
,I/art     ( 5390): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5390): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/SystemWebViewEngine( 5364): CordovaWebView is running on device made by: LGE
W/art     ( 5364): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5364): Attempt to remove local handle scope entry from IRT, ignoring
I/NotificationManager( 5390): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5023): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5023): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/Activity( 5364): Activity.onPostResume() called 
,D/OpenGLRenderer( 5364): Render dirty regions requested: true
I/OpenGLRenderer( 5364): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5364): Enabling debug mode 0
D/Atlas   ( 5364): Validating map...
,D/SplitWindow(  964): check instance of lgWin Window{2bf27bc6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5364): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  964): Focus entered window: Window{2bf27bc6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  964): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +1s320ms
I/Timeline(  964): Timeline: Activity_windows_visible id: ActivityRecord{2c8b59e2 u0 com.test.thalitest/.MainActivity t220} time:96279
,I/Timeline( 5364): Timeline: Activity_idle id: android.os.BinderProxy@11d3ec0 time:96296
,W/BindingManager( 5364): Cannot call determinedVisibility() - never saw a connection for the pid: 5364
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 5023): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5023): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 5023): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{14d91077 type 0 when 1449588489727 com.android.vending} when 1449588489727
D/Finsky  ( 5023): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 5023): [584] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/JsMessageQueue( 5364): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5364): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622778880
,D/JX-Cordova( 5364): jxcore cordova android initializing
I/art     ( 5364): CheckpointMarkThreadRoots callback created = 0x995f4430
,I/art     ( 5364): CheckpointMarkThreadRoots callback created = 0x995f4400
,I/art     (  964): Explicit concurrent mark sweep GC freed 18761(821KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.741ms total 174.864ms
,I/art     ( 5364): Background sticky concurrent mark sweep GC freed 25358(2MB) AllocSpace objects, 0(0B) LOS objects, 14% free, 17MB/19MB, paused 5.080ms total 54.664ms
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,W/jxcore-log( 5364): Initializing JXcore engine
,W/jxcore-log( 5364): JXcore engine is ready
W/jxcore-log( 5364): Starting JXcore engine
,W/.test.thalitest( 5364): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7711]" dev="sockfs" ino=7711 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5364): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5364): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7850]" dev="sockfs" ino=7850 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5364): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/.test.thalitest( 5364): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5364): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25062]" dev="sockfs" ino=25062 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5364): Platform android
W/jxcore-log( 5364): 
W/jxcore-log( 5364): Process ARCH arm
W/jxcore-log( 5364): 
,I/jxcore-log( 5364): JXcore Cordova bridge is ready!
I/jxcore-log( 5364): 
W/jxcore-log( 5364): JXcore engine is started
,I/Choreographer( 5364): Skipped 189 frames!  The application may be doing too much work on its main thread.
I/chromium( 5364): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/jxcore  ( 5364): Error!: missing ) after argument list
E/jxcore  ( 5364): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5364): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
D/InputDispatcher(  964): Focus left window: Window{2bf27bc6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1074 us)
,W/PluginManager( 5364): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 41ms. Plugin should use CordovaInterface.getThreadPool().
I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
,I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
D/WeatherAncestor( 2688): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:28:13
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 2688): 2 : shouldTimeTickRegistered().........
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 16:28:13
I/SystemUI[Framework](  964): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  964): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  964): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  964): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
I/SystemUI[Framework](  964): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@34e223f4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/InputDispatcher(  964): Focus entered window: Window{230c32ce u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2688): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2688): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2688): 2 : Fixed theme : optimus
D/WeatherReflect( 2688): 2 : Map key string is -2
D/lim     ( 2688): 2 : time = 16:28
I/WeatherReflect( 2688): Model Name : LG-D722
D/WeatherTheme( 2688): 2 : exactly same view!
D/WeatherTheme( 2688): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
,W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  964): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/IInputConnectionWrapper( 5364): showStatusIcon on inactive InputConnection
,I/SystemUI[Framework](  964): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
W/PhoneWindowManagerEx(  964): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  964): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  964): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@34e223f4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 1876): Timeline: Activity_idle id: android.os.BinderProxy@34b78b2 time:100411
D/BarTransitions( 1369): draw background and invalidate : color = e9000000
,D/BarTransitions( 1369): draw background and invalidate : color = e4dbdbdb
I/HotwordRecognitionRnr( 1934): Starting hotword detection.
,I/MicrophoneInputStream( 1934): mic_starting com.google.android.apps.gsa.speech.audio.u@3f5de27a
V/AudioRecord( 1934): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1934): set(): mSessionId 22
V/AudioPolicyManager(  279): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  279): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  279): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  279): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
V/audio_hw_primary(  279): adev_open_input_stream: exit
V/AudioFlinger(  279): openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
,V/AudioFlinger(  279): openInput_l() created record thread: ID 23 thread 0xb426f000
V/AudioSystem(  279): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  964): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1369): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1934): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioSystem( 2001): ioConfigChanged() event 3, ioHandle 23
I/AudioFlinger(  279): AudioFlinger's thread 0xb426f000 ready to run
D/audio_hw_primary(  279): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/AudioSystem( 1750): ioConfigChanged() event 3, ioHandle 23
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioSystem( 3145): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioFlinger(  279): openRecord() lSessionId: 22 input 23
D/audio_hw_primary(  279): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioFlinger(  279): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  279): acquiring 22 from 1934, for -1
V/AudioFlinger(  279):  added new entry for 22
V/AudioRecord( 1934): start, sync event 0 trigger session 0
V/AudioRecord( 1934): mAudioRecord->start()
V/AudioFlinger(  279): RecordHandle::start()
V/AudioFlinger(  279): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  279): startInput() module primary->input primary(23)
V/AudioPolicyManager(  279): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  279): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  279): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  279): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  279): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  279): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  279): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  279): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  279): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb426f000
V/AudioFlinger::PatchPanel(  279): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  279): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  279): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  279): inser,ting command: 3 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  279): setParameters(): io 23, keyvalue hotword_active=1, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
,V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb426f000
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1934): mic_started com.google.android.apps.gsa.speech.audio.u@3f5de27a
,V/msm8974_platform(  279): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  279): start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
V/voice   (  279): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  279): start_input_stream: usecase(7)
E/audio_hw_primary(  279): select_devices: enter and usecase(7)
V/msm8974_platform(  279): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  279): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  279): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  279): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  279): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  279): enable_snd_device: enter  144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  279): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  279): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  279): ACDB -> send_adm_topology
D/ACDB-LOADER(  279): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  279): ACDB -> send_asm_topology
D/ACDB-LOADER(  279): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  279): ACDB -> send_audtable
D/ACDB-LOADER(  279): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  279): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  279): ACDB -> send_audvoltable
D/ACDB-LOADER(  279): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  279): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  279): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  279): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  279): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  279): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  279): enable_audio_route: exit
D/audio_hw_primary(  279): select_devices: done
V/audio_hw_primary(  279): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  279): start_input_stream: exit
I/HotwordWorker( 1934): onReady
,I/Timeline(  964): Timeline: Activity_windows_visible id: ActivityRecord{141cb0d6 u0 com.lge.launcher2/.Launcher t219} time:100677
,I/ActivityManager(  964): Killing 5148:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10069/pid_5148/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Killing 4979:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10086/pid_4979/cgroup.procs: No such file or directory
,D/InputDispatcher(  964): Window went away: Window{2bf27bc6 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/OpenGLRenderer( 1876): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1876): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1876): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1876): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1876): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1876): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  270): 
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{232f5eb9 type 0 when 1449588504383 com.android.vending} when 1449588504383
,W/ContextImpl( 3435): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 5023): [575] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5023): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 115170650065; DSPS: 3872659; Offset : -3015614403
,I/MusicWidget( 2599): mDelayedStopHandler : unbind
,I/MusicBrowser( 2001): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2001): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2001): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2001): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2001): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2001): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2001): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2001): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  964):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1e5ba843com.lge.music.MediaPlaybackService$6@11d3ec0
,D/MusicBrowser( 2001): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2001): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2e5eca89
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2001): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2001): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2001): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2001): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2001): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2001): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2001): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2001): reset
V/MediaPlayer[Native]( 2001): setListener
,V/MediaPlayer[Native]( 2001): disconnect
V/MediaPlayer[Native]( 2001): destructor
V/AudioFlinger(  279): releasing 19 from 2001 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2001): disconnect
D/MusicBrowser( 2001): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2001): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2001): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2001): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2001): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2001): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2001): [SmartShareManagerClient] unregisterListener: 722626553
W/SmartShareClient( 2001): [SmartShareManagerClient] unregisterListener invalid listener: 722626553
I/SmartShareClient( 2001): [SmartShareManagerClient] terminate service: 2001/MediaPlaybackService/575923127
E/HomeCloudIF( 2001): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2001): [SmartShareManagerClient] unbindService context:android.app.Application@161a533e
V/CloudHub( 2001): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2001): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2001): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2001): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2001): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  964): Killing 4429:com.google.android.talk/u0a61 (adj 15): empty #11
,I/CloudHub( 2001): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_4429/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2001): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19962
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 135172026880; DSPS: 4528064; Offset : -3015610775
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2001): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2001): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=326942122, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,D/WeatherService( 2688): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:29:0
D/WeatherService( 2688): 2 : TimeTick Intent And Screen On
D/WeatherService( 2688): 2 : SDK version : 21
W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2688): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2688): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2688): 2 : Fixed theme : optimus
D/WeatherReflect( 2688): 2 : Map key string is -2
D/lim     ( 2688): 2 : time = 16:29
I/WeatherReflect( 2688): Model Name : LG-D722
D/WeatherTheme( 2688): 2 : Different view - status_min_formatted : 28 != 29
D/WeatherTheme( 2688): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2688): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2688): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
,I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
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
,D/Theme_WeatherAncestor_optimus( 2688): url is : null
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2688): 2 : update view, appWidgetId: 2
,D/WeatherService( 2688): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:29:0
,D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=326942122 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{261de2fe type 2 when 129852 com.google.android.gms} when 129852
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{24573a5f type 2 when 131543 com.google.android.gms} when 131543
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
,D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd( 1965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5581 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5581): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5581): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5581): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5581): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5581): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5581): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5581): MmsConfig.loadFromResources
E/Babel_SMS( 5581): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5581): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5581): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5581): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5581): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5581): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5581): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5581): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5581): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5581): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5581): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5581): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5581): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5581): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5581): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5581): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5581): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5581): found sensor: Motion Accel, handle=46
,I/art     ( 5581): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,W/Settings( 5581): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5581): startup - clean
,I/art     ( 5581): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/Babel   ( 5581): deleted: false for 0
,W/AudioCapabilities( 5581): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5581): Unsupported mime audio/adpcm
W/AudioCapabilities( 5581): Unsupported mime audio/g726
W/AudioCapabilities( 5581): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5581): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5581): Unsupported mime video/mjpg
W/VideoCapabilities( 5581): Unsupported mime video/theora
,W/AudioCapabilities( 5581): Unsupported mime audio/evrc
,W/AudioCapabilities( 5581): Unsupported mime audio/qcelp
W/VideoCapabilities( 5581): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5581): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5581): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5581): Unsupported mime audio/evrc
W/VideoCapabilities( 5581): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5581): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5581): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5581): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5581): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5581): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  964): Killing 5180:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10053/pid_5180/cgroup.procs: No such file or directory
,I/vclib   ( 5581): onServiceConnected
W/Babel   ( 5581): Attempted to change video mute state without an active call.
I/NotificationManager( 5581): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 155180663643; DSPS: 5183707; Offset : -3015610460
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/PowerManagerService(  964): ALS enabled for SRE
,D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (47701 ms ago)
D/qdlights(  964): set_light_backlight: 254
,D/qdlights(  964): set_light_backlight: 251
D/qdlights(  964): set_light_backlight: 247
,D/qdlights(  964): set_light_backlight: 244
,D/qdlights(  964): set_light_backlight: 241
,D/qdlights(  964): set_light_backlight: 237
,D/qdlights(  964): set_light_backlight: 234
,D/qdlights(  964): set_light_backlight: 231
,D/qdlights(  964): set_light_backlight: 227
,D/qdlights(  964): set_light_backlight: 224
,D/qdlights(  964): set_light_backlight: 221
,D/qdlights(  964): set_light_backlight: 217
,D/qdlights(  964): set_light_backlight: 214
,D/qdlights(  964): set_light_backlight: 211
,D/qdlights(  964): set_light_backlight: 207
,D/qdlights(  964): set_light_backlight: 204
,D/qdlights(  964): set_light_backlight: 201
,D/qdlights(  964): set_light_backlight: 197
,D/qdlights(  964): set_light_backlight: 194
,D/qdlights(  964): set_light_backlight: 191
,D/qdlights(  964): set_light_backlight: 187
,D/qdlights(  964): set_light_backlight: 184
,D/qdlights(  964): set_light_backlight: 181
,D/qdlights(  964): set_light_backlight: 177
,D/qdlights(  964): set_light_backlight: 174
,D/qdlights(  964): set_light_backlight: 171
,D/qdlights(  964): set_light_backlight: 167
,D/qdlights(  964): set_light_backlight: 164
,D/qdlights(  964): set_light_backlight: 161
,D/qdlights(  964): set_light_backlight: 157
,D/qdlights(  964): set_light_backlight: 154
,D/qdlights(  964): set_light_backlight: 151
,D/qdlights(  964): set_light_backlight: 147
,D/qdlights(  964): set_light_backlight: 144
,D/qdlights(  964): set_light_backlight: 141
,D/qdlights(  964): set_light_backlight: 137
,D/qdlights(  964): set_light_backlight: 134
,D/qdlights(  964): set_light_backlight: 131
,D/qdlights(  964): set_light_backlight: 127
,D/qdlights(  964): set_light_backlight: 124
,D/qdlights(  964): set_light_backlight: 121
,D/qdlights(  964): set_light_backlight: 117
,D/qdlights(  964): set_light_backlight: 114
,D/qdlights(  964): set_light_backlight: 111
,D/qdlights(  964): set_light_backlight: 107
,D/qdlights(  964): set_light_backlight: 104
,D/qdlights(  964): set_light_backlight: 101
,D/qdlights(  964): set_light_backlight: 97
,D/qdlights(  964): set_light_backlight: 94
,D/qdlights(  964): set_light_backlight: 91
,D/qdlights(  964): set_light_backlight: 87
,D/qdlights(  964): set_light_backlight: 84
,D/qdlights(  964): set_light_backlight: 81
,D/qdlights(  964): set_light_backlight: 77
,D/qdlights(  964): set_light_backlight: 74
,D/qdlights(  964): set_light_backlight: 71
,D/qdlights(  964): set_light_backlight: 67
,D/qdlights(  964): set_light_backlight: 64
,D/qdlights(  964): set_light_backlight: 61
,D/qdlights(  964): set_light_backlight: 57
,D/qdlights(  964): set_light_backlight: 54
,D/qdlights(  964): set_light_backlight: 51
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/qdlights(  964): set_light_backlight: 47
D/qdlights(  964): set_light_backlight: 44
,D/qdlights(  964): set_light_backlight: 41
,D/qdlights(  964): set_light_backlight: 37
,D/qdlights(  964): set_light_backlight: 34
,D/qdlights(  964): set_light_backlight: 31
,D/qdlights(  964): set_light_backlight: 27
,D/qdlights(  964): set_light_backlight: 24
,D/qdlights(  964): set_light_backlight: 21
,D/qdlights(  964): set_light_backlight: 17
,D/qdlights(  964): set_light_backlight: 14
,D/qdlights(  964): set_light_backlight: 11
,D/qdlights(  964): set_light_backlight: 10
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/PowerManagerService(  964): ALS enabled for SRE
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (54690 ms ago)
I/PowerManagerService(  964): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  964): ALS enabled for SRE
,D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (54705 ms ago)
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  964): Sleeping (uid 1000)...
D/LPWGController(  964): [updateScreenState] screen on = false
,D/LPWGController(  964): disable proximity sensor
D/LPWGController(  964): enable proximity sensor
I/SensorManager(  964): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@16965de5] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  964): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
,D/sensors_hal_SAM(  964): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  964): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  964): activate: handle is 48, enable
V/sensors_hal_Ctx(  964): activate sensors is 1400000000000
D/sensors_hal_Thresh(  964): enable: handle=48
I/sensors_hal_SAM(  964): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  964): waitForResponse: timeout=1000
V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  964): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  964): enable: Received response: 0
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (54756 ms ago)
I/Adreno-EGL(  964): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  964): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  964): Build Date: 03/02/15 Mon
I/Adreno-EGL(  964): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  964): Remote Branch: 
I/Adreno-EGL(  964): Local Patches: 
I/Adreno-EGL(  964): Reconstruct Branch: 
,I/Sensors (  430): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  964): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  964): processInd: handle 48, count=1
V/sensors_hal_Thresh(  964): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  964): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  964): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  964): poll: count: 256
I/sensors_hal_Ctx(  964): poll: released wakelock sensor_ind
D/sensors_hal_Util(  964): waitForResponse: timeout=0
D/LPWGController(  964): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  964): current mode = 1  value = 1 1
I/LPWGController(  964): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  964): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 175182406396; DSPS: 5839125; Offset : -3015639602
,D/qdlights(  964): set_light_backlight: 0
,I/SensorManager(  964): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  964): activate: handle is 46, disable
V/sensors_hal_Ctx(  964): activate sensors is 1000000000000
D/sensors_hal_LP2(  964): enable: handle=46
D/sensors_hal_LP2(  964): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  964): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  964): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  964): Display changed displayId=0
,V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  964): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1750): Display #0 changed.
D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
D/SurfaceControl(  964): Excessive delay in setPowerMode(): 250ms
,I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  964): Got set_interactive hint
,I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/KeyguardViewMediator( 1369): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1369): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
W/ProcessCpuTracker(  964): Skipping unknown process pid 5640
W/ProcessCpuTracker(  964): Skipping unknown process pid 5641
,W/ProcessCpuTracker(  964): Skipping unknown process pid 5644
W/ProcessCpuTracker(  964): Skipping unknown process pid 5646
W/ProcessCpuTracker(  964): Skipping unknown process pid 5647
D/KeyguardViewMediator( 1369): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1369): handleNotifyScreenOff
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1934): Closing mic
I/MicrophoneInputStream( 1934): mic_close com.google.android.apps.gsa.speech.audio.u@3f5de27a
,V/AudioRecord( 1934): stop()
D/AudioRecord( 1934): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
D/ScreenTurnOffBySensor( 1369): unregisterProximitySensor
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 23
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 24
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
D/StatusBarWindowView( 1369): onScreenTurnedOff why = 3
,V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb426f000
,D/audio_hw_primary(  279): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/WifiServerServiceExt(  964): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  279): disable_audio_route: exit
E/audio_hw_primary(  279): disable_snd_device: enter 144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  279): stop_input_stream: exit: status(0)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
V/voice   (  279): voice_set_parameters: enter: screen_state=on
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: exit
V/voice   (  279): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  279): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  279): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  279): platform_set_parameters: exit with code(0)
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 20 af handle 24
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 23 ,delay 0
V/AudioPolicyService(  279): inserting command: 3 at index 0, num commands 0
V/lge_audio_loopback(  279): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  279): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  279): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  279): adev_set_parameters: exit with code(0)
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=0, io 23
V/AudioFlinger(  279): setParameters(): io 23, keyvalue hotword_active=0, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb426f000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1934): stop()
,V/AudioRecord( 1934): stop()
V/AudioRecord( 1934): stop()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
V/AudioFlinger(  279): releasing 22 from 1934 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 23
V/AudioPolicyManager(  279): closeInput(23)
V/AudioFlinger(  279): closeInput() 23
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem(  964): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  279): ThreadBase::exit
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioSystem( 1934): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  279): RecordThread 0xb426f000 exiting
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 23
I/HotwordRecognitionRnr( 1934): Stopping hotword detection.
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 2001): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 3145): ioConfigChanged() event 4, ioHandle 23
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioFlinger(  279): removeClient_l() pid 1934, calling pid 279
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1934): Hotword detection finished
D/GpsLocationProvider(  964): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
,I/LEDService( 1795): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1795): stopPatternFlashing()
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1795): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/LEDService( 1795): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
,D/Cliptray Service( 1795): lockStatus = 0
D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
I/LEDService( 1795): updateLightsLocked : turn off led
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1795): RESTART MSG
D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 3
D/NfcService( 1784): Discovery configuration equal, not updating.
,D/Ulp_jni (  964): JNI:system_update. Event-0
D/SplitWindow(  964): check instance of lgWin Window{2519b6c8 u0 SearchPanel}
,D/InputDispatcher(  964): Window went away: Window{b5fe40f u0 SearchPanel}
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:29:29
D/WeatherService( 2688): 2 : ACTION screen on
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:29:29
D/AppCleanupService( 3899): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
V/voice   (  279): voice_set_parameters: enter: screen_state=off
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: exit
V/voice   (  279): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  279): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  279): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  279): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  279): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  279): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  279): adev_set_parameters: exit with code(0)
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  964): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
I/LEDService( 1795): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1795): stopPatternFlashing()
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1795): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1795): clear
I/Cliptray Service( 1795): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
I/LEDService( 1795): updateLightsLocked : turn on led
E/LEDService( 1795): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1795): Can't handle this request of patternId:0
D/LEDHandler( 1795): RESTART MSG
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
W/ActivityManager(  964): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:29:29
,D/WeatherService( 2688): 2 : ACTION screen off
D/WeatherService( 2688): 2 : TimeTick Receiver Unregister
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:29:29
D/AppCleanupService( 3899): android.intent.action.SCREEN_OFF
D/AppCleanupService( 3899): AppUsageStatsSaveTask
,E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
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
,I/Sensors (  430): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1369): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{853f361 type 2 when 180699 com.android.systemui} when 180699
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1369): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1369): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{3dec5e86 type 2 when 190996 com.google.android.gms} when 190996
,I/NotificationManager( 1934): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/art     ( 1965): Explicit concurrent mark sweep GC freed 14924(938KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 11MB/19MB, paused 9.729ms total 113.753ms
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 195184983106; DSPS: 6494569; Offset : -3015624909
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{3dd8cce3 type 2 when 206076 com.google.android.gms} when 206076
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 215187534088; DSPS: 7150012; Offset : -3015606861
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{3e4e96e0 type 2 when 189140 android} when 189140
,D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  964): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  964): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 235190417572; DSPS: 7805467; Offset : -3015622234
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 255192455323; DSPS: 8460894; Offset : -3015629291
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 275195009379; DSPS: 9116337; Offset : -3015608299
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 295197421815; DSPS: 9771776; Offset : -3015606726
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 315199971915; DSPS: 10427220; Offset : -3015619815
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 335201624046; DSPS: 11082634; Offset : -3015615764
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  964): remove 1cdee81a
D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=326942122, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{aaead99 type 2 when 267871 com.google.android.gms} when 267871
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=326942122 [*alarm*], flags=0x0
,D/libc-netbsd( 1965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 355204187212; DSPS: 11738078; Offset : -3015616231
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
,I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 375206602307; DSPS: 12393517; Offset : -3015612155
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 395209151832; DSPS: 13048961; Offset : -3015625975
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 415211518855; DSPS: 13704398; Offset : -3015608572
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 435214068953; DSPS: 14359842; Offset : -3015622159
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 455216620715; DSPS: 15015286; Offset : -3015633900
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 475219028892; DSPS: 15670724; Offset : -3015605912
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 495220648824; DSPS: 16326138; Offset : -3015634136
,I/ClearcutLoggerApiImpl( 1965): disconnect managed GoogleApiClient
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 515223198036; DSPS: 16981581; Offset : -3015617962
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 535227397976; DSPS: 17637079; Offset : -3015629057
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 555229680313; DSPS: 18292513; Offset : -3015605230
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 575231801659; DSPS: 18947943; Offset : -3015620166
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 595235997432; DSPS: 19603440; Offset : -3015604988
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 615238407425; DSPS: 20258879; Offset : -3015606170
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 635240965337; DSPS: 20914323; Offset : -3015611838
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 655243386108; DSPS: 21569763; Offset : -3015632449
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 675245940789; DSPS: 22225206; Offset : -3015610727
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=326942122, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{beab641 type 2 when 587838 com.google.android.gms} when 587838
D/Finsky  ( 5023): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  964): RTC_WAKEUP set : Alarm{3fe5f127 type 0 when 1449589078533 com.android.vending} when 1449589078533
,D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=326942122 [*alarm*], flags=0x0
,D/libc-netbsd( 1965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 5023): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5023): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5023): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5023): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 5023): [1] DailyHygiene.access$600: Logging device features
D/Finsky  ( 5023): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
V/AlarmManager(  964): RTC_WAKEUP set : Alarm{2199d9cc type 0 when 1449589079034 com.android.vending} when 1449589079034
D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 5023): [590] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 695248534374; DSPS: 22880652; Offset : -3015641652
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=326942122, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{2066ec93 type 0 when 1449589093757 com.android.vending} when 1449589093757
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=326942122 [*alarm*], flags=0x0
,D/Finsky  ( 5023): [575] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5023): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 715254752179; DSPS: 23536215; Offset : -3015618761
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 735257160036; DSPS: 24191654; Offset : -3015622026
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 755259709404; DSPS: 24847097; Offset : -3015605253
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 775266013613; DSPS: 25502664; Offset : -3015618417
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 795268562408; DSPS: 26158108; Offset : -3015633307
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 815271112299; DSPS: 26813551; Offset : -3015616271
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 835273853071; DSPS: 27469001; Offset : -3015622107
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 855276406083; DSPS: 28124445; Offset : -3015632545
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 875278230399; DSPS: 28779864; Offset : -3015608662
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 895280785080; DSPS: 29435308; Offset : -3015617509
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 915282695175; DSPS: 30090731; Offset : -3015630073
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 935285249544; DSPS: 30746174; Offset : -3015608664
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 955286759639; DSPS: 31401584; Offset : -3015624239
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 975289311040; DSPS: 32057027; Offset : -3015606005
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 995291812544; DSPS: 32712469; Offset : -3015606866
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1015294363418; DSPS: 33367913; Offset : -3015619416
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
,D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1035296767786; DSPS: 34023352; Offset : -3015626040
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1055299319496; DSPS: 34678795; Offset : -3015607160
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1075301733761; DSPS: 35334235; Offset : -3015634326
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1095304281775; DSPS: 35989678; Offset : -3015619272
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1115306310775; DSPS: 36645104; Offset : -3015604588
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1135308862437; DSPS: 37300548; Offset : -3015616220
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1155311735030; DSPS: 37956002; Offset : -3015612306
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=326942122, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{2e409aa6 type 2 when 1156728 com.google.android.gms} when 1156728
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=326942122 [*alarm*], flags=0x0
,D/libc-netbsd( 1965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1965): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1965): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1175314284505; DSPS: 38611446; Offset : -3015626412
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1195316831319; DSPS: 39266889; Offset : -3015612531
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1215319388291; DSPS: 39922333; Offset : -3015618905
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  964): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1235321939170; DSPS: 40577777; Offset : -3015631737
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1255324498795; DSPS: 41233221; Offset : -3015635588
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1275326891555; DSPS: 41888659; Offset : -3015622964
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1295329446749; DSPS: 42544103; Offset : -3015633096
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1315331283460; DSPS: 43199523; Offset : -3015625773
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1335333840070; DSPS: 43854967; Offset : -3015632562
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1355335485689; DSPS: 44510381; Offset : -3015634789
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1375338037083; DSPS: 45165824; Offset : -3015616457
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1395340581087; DSPS: 45821267; Offset : -3015605489
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1415343135140; DSPS: 46476711; Offset : -3015614835
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1435345546280; DSPS: 47132150; Offset : -3015614819
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1455347620176; DSPS: 47787578; Offset : -3015615857
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1475350519806; DSPS: 48443033; Offset : -3015615319
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1495352550786; DSPS: 49098460; Offset : -3015629173
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1515354315779; DSPS: 49753878; Offset : -3015634251
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
,I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1535356870928; DSPS: 50409321; Offset : -3015611931
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1555359420608; DSPS: 51064765; Offset : -3015625910
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1575361970549; DSPS: 51720208; Offset : -3015608851
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  964): Explicit concurrent mark sweep GC freed 54508(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/35MB, paused 2.917ms total 235.150ms
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1595364520541; DSPS: 52375652; Offset : -3015622334
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1615367076575; DSPS: 53031096; Offset : -3015629622
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1635369629484; DSPS: 53686539; Offset : -3015609437
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1655371279840; DSPS: 54341953; Offset : -3015607160
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1675373118218; DSPS: 54997374; Offset : -3015630563
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1695375666908; DSPS: 55652817; Offset : -3015614858
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1715378209974; DSPS: 56308261; Offset : -3015635191
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1735380763299; DSPS: 56963704; Offset : -3015614877
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1755383312615; DSPS: 57619148; Offset : -3015628984
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1775385861045; DSPS: 58274591; Offset : -3015613540
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1795388260987; DSPS: 58930030; Offset : -3015624539
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1815390666187; DSPS: 59585469; Offset : -3015630149
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1835393216335; DSPS: 60240912; Offset : -3015613091
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1855395245026; DSPS: 60896339; Offset : -3015629051
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1875397791160; DSPS: 61551782; Offset : -3015615824
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  964): Prepared write state in 16ms
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  964): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ProcessStatsService(  964): Pruning old procstats: /data/system/procstats/state-2015-12-07-15-36-10.bin
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1895400816366; DSPS: 62207241; Offset : -3015611676
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6009): 
D/AndroidRuntime( 6009): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6009): CheckJNI is OFF
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
D/AndroidRuntime( 6009): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  964): Killing 5364:com.test.thalitest/u0a316 (adj 13): stop com.test.thalitest
W/PackageSettings(  964): Skipping PackageSetting{1ae2b535 com.example.hello/10030} due to missing metadata
I/ActivityManager(  964): Killing 5281:com.android.calendar/u0a13 (adj 15): empty for 1819s
I/ActivityManager(  964): Killing 5066:com.lge.qremote/u0a106 (adj 15): empty for 1824s
I/ActivityManager(  964): Killing 4804:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty for 1824s
W/ActivityManager(  964): Spurious death for ProcessRecord{2aa26406 5364:com.test.thalitest/u0a316}, curProc for 5364: null
I/ActivityManager(  964): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/art     ( 1876): Explicit concurrent mark sweep GC freed 8560(490KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 902us total 43.874ms
I/art     ( 1934): Explicit concurrent mark sweep GC freed 2391(145KB) AllocSpace objects, 2(689KB) LOS objects, 40% free, 12MB/20MB, paused 1.480ms total 62.602ms
W/libprocessgroup(  964): failed to open /acct/uid_10013/pid_5281/cgroup.procs: No such file or directory
W/libprocessgroup(  964): failed to open /acct/uid_10106/pid_5066/cgroup.procs: No such file or directory
E/lowmemorykiller(  244): Error opening /proc/4804/oom_score_adj; errno=2
W/ActivityManager(  964): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  964): android.os.DeadObjectException
W/ActivityManager(  964): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  964): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  964): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  964): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  964): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  964): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/ActivityManager(  964): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  964): android.os.DeadObjectException
W/ActivityManager(  964): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  964): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  964): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  964): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  964): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  964): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  964): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  964): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  964): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/libprocessgroup(  964): failed to open /acct/uid_10089/pid_4804/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3435): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3435): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3435): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3435): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3435): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3435): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3435): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3435): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3435): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3435): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3435): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3435): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6041 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  964): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6047 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/art     (  964): Explicit concurrent mark sweep GC freed 17788(1346KB) AllocSpace objects, 6(196KB) LOS objects, 33% free, 23MB/35MB, paused 2.605ms total 182.759ms
I/art     (  964): WaitForGcToComplete blocked for 164.849ms for cause Explicit
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
D/administrator(  964): Handling package changes for user 0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 6041): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6041): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6041): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LockScreenSettings( 6047): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
D/KeyguardModel( 1369): handleShortcutListChanged...
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/NotificationService(  964): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  964): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
D/JobSchedulerService(  964): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/ActivityManager(  964): Killing 5253:com.android.providers.calendar/u0a14 (adj 15): empty for 1817s
I/art     (  964): Explicit concurrent mark sweep GC freed 4284(231KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 11.636ms total 254.215ms
D/KeyguardModel( 1369): handleShortcutListChanged...
W/libprocessgroup(  964): failed to open /acct/uid_10014/pid_5253/cgroup.procs: No such file or directory
D/TaskPersister(  964): removeObsoleteFile: deleting file=220_task.xml
D/TaskPersister(  964): removeObsoleteFile: deleting file=220_task_thumbnail.png
I/LGEmail ( 6041): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6041): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 6009): Shutting down VM
W/ResourcesManager(  964): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
I/PackageChangeReceiver( 6041): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6082 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  964): Killing 5390:com.google.android.gms:car/u0a6 (adj 15): empty for 1810s
W/ResourceType(  964): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup(  964): failed to open /acct/uid_10006/pid_5390/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/AppUp4:AppBoxCP( 6082): onCreate
W/AppUp4:DB( 6082):  [AppBoxDatabaseHelper] construct
W/FileUtils( 6082): Failed to chmod(/data/data/com.lge.appbox.client/databases/appbox.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/AppUp4:DB( 6082):  setFingerPrint start
I/AppUp4:DB( 6082):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6082):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6082):  SDK version = 0
I/AppUp4:DB( 6082):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6082): AppBoxApplication onCreate()
E/SQLiteLog( 6082): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
E/SQLiteDatabase( 6082): Error inserting package=com.test.thalitest
E/SQLiteDatabase( 6082): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6082): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6082): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
E/SQLiteDatabase( 6082): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 6082): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6082): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
E/SQLiteDatabase( 6082): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
E/SQLiteDatabase( 6082): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 6082): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 6082): 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
E/SQLiteDatabase( 6082): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 6082): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 6082): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 6082): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 6082): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 6082): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/SQLiteDatabase( 6082): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/SQLiteDatabase( 6082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/SQLiteDatabase( 6082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6082): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6082): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 6082): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 6082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  964): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6105 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a

```
