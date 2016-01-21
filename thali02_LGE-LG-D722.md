#### Test 56672827039a409_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/Finsky  ( 4966): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
--------- beginning of system
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{2c5ac4dc type 0 when 1453396491559 com.android.vending} when 1453396491559
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  853): android: cancelAsUser(2) by android
D/libc-netbsd( 4966): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4966): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4966): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4966): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  853): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4966): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  853): android: cancelAsUser(2) by android
D/libc-netbsd( 4966): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4966): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  853): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5425 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  853): android: cancelAsUser(2) by android
D/libc-netbsd( 4966): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4966): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 4966): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5425): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5425): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5425): VM with version 2.1.0 has multidex support
I/MultiDex( 5425): install
I/MultiDex( 5425): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5425): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 5425): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5425): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3614062f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5425): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5425): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5425): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1727): callingUid 10006, callindPid: 1727
E/MDM     ( 1727): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 5425): Reading stored module config
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
D/AuthorizationBluetoothService( 1727): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5236): Restart initialization of location
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1727): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 5425): Loading module com.google.android.gms.car from APK com.google.android.gms
W/GCoreFlp( 1727): No location to return for getLastLocation()
W/FusedLocationProvider( 1727): location=null
D/CAR.SERVICE( 5425): Connecting to CarCallService...
D/NativeLibraryUtils( 5425): Install completed successfully. count=14 extracted=0
I/art     ( 5425): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5425): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 5425): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 5425): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5425): Creating a new PhoneAdapter instance
W/ActivityManager(  853): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5425): setListener: com.google.android.gms.car.dn@33ab6eca
W/ActivityManager(  853): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5425): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5425): Starting CarCallService with initial phone null
I/NotificationManager( 5425): com.google.android.gms: cancel(10436) by com.google.android.gms
D/AndroidRuntime( 5448): 
D/AndroidRuntime( 5448): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5448): CheckJNI is OFF
D/CAR.SERVICE( 5425): Package validated; name: com.android.vending
I/NotificationManager( 4966): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 4966): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{2f69c296 type 2 when 93765 com.google.android.gms} when 93765
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  853): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  853): android: cancelAsUser(2) by android
D/AndroidRuntime( 5448): Calling main entry com.android.commands.am.Am
D/libc-netbsd( 4966): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4966): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 4966): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ActivityManager(  853): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/Finsky  ( 4966): [1] DailyHygiene.access$600: Logging device features
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{1a9c590f #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  853): setTaskToReturnTo : TaskRecord{1a9c590f #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  853): AppWindowTokenEx init.. 
D/ContextHelper(  853): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1871): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  853): Focus left window: Window{22886c08 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5448): Shutting down VM
V/AlarmManager(  853): RTC_WAKEUP set : Alarm{39b5fd46 type 0 when 1453396492859 com.android.vending} when 1453396492859
D/Finsky  ( 4966): [1] DailyHygiene.reschedule: Scheduling new run in 90 minutes (failures=3)
D/SplitWindow(  853): check instance of lgWin Window{c291434 u0 Starting com.test.thalitest}
I/ActivityManager(  853): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5490 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1871): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/DeviceConnectionService( 1727): client connected with version: 8296000
D/Finsky  ( 4966): [599] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/[LGHome]EVENT( 1871): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1929): Closing mic
I/MicrophoneInputStream( 1929): mic_close com.google.android.apps.gsa.speech.audio.u@23b3abe2
V/AudioRecord( 1929): stop()
D/AudioRecord( 1929): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
I/WindowStateAnimator(  853): Starting window displayed
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 16
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3840000
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@290b6f4d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1368): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1368): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1368):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1368): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1368): draw background and invalidate : color = f000000
D/Finsky  ( 4966): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/BarTransitions( 1368): draw background and invalidate : color = 14131313
D/Finsky  ( 4966): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
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
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  281): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  281): setParameters(): io 16, keyvalue hotword_active=0, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3840000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1929): stop()
,V/AudioRecord( 1929): stop()
V/AudioRecord( 1929): stop()
V/AudioFlinger(  281): releasing 15 from 1929 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 16
V/AudioPolicyManager(  281): closeInput(16)
V/AudioFlinger(  281): closeInput() 16
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  853): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  281): ThreadBase::exit
V/AudioSystem( 1929): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 2714): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3115): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  281): RecordThread 0xb3840000 exiting
V/AudioSystem( 1368): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb546dde0)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioSystem( 1745): ioConfigChanged() event 4, ioHandle 16
I/HotwordRecognitionRnr( 1929): Stopping hotword detection.
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1929, calling pid 281
I/HotwordRecognitionRnr( 1929): Hotword detection finished
,I/art     ( 1727): Explicit concurrent mark sweep GC freed 28830(1751KB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 13MB/22MB, paused 1.920ms total 118.874ms
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  853): android: cancelAsUser(2) by android
,D/ContextHelper( 5490): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,D/libc-netbsd( 4966): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4966): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4966): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4966): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  853): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager(  853): Killing 5206:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/WebViewFactory( 5490): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/libprocessgroup(  853): failed to open /acct/uid_10069/pid_5206/cgroup.procs: No such file or directory
I/LibraryLoader( 5490): Time to load native libraries: 15 ms (timestamps 4645-4660)
,I/LibraryLoader( 5490): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5490): Binding Chromium to main looper Looper (main, tid 1) {33422075}
,I/LibraryLoader( 5490): Expected native library version number "",actual native library version number ""
I/chromium( 5490): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5490): Initializing chromium process, singleProcess=true
,W/art     ( 5490): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5490): ApplicationContext is null in ApplicationStatus
,W/chromium( 5490): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5490): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5490): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5490): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5490): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5490): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5490): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5490): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5490): Remote Branch: 
I/Adreno-EGL( 5490): Local Patches: 
I/Adreno-EGL( 5490): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb382bba0, uid 10316
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 94883163092; DSPS: 3201177; Offset : -2818725705
D/BluetoothManagerService(  853): Message: 20
,D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@815dbce:true
D/BluetoothAdapter( 5490): 1052177476: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5490): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5490): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5490): CordovaWebView is running on device made by: LGE
,W/art     ( 5490): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5490): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5490): Activity.onPostResume() called 
,D/OpenGLRenderer( 5490): Render dirty regions requested: true
I/OpenGLRenderer( 5490): Initialized EGL, version 1.4
D/OpenGLRenderer( 5490): Enabling debug mode 0
,D/Atlas   ( 5490): Validating map...
,D/SplitWindow(  853): check instance of lgWin Window{1796d47e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5490): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  853): Focus entered window: Window{1796d47e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  853): Displayed com.test.thalitest/.MainActivity: +1s227ms
I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{284ead9c u0 com.test.thalitest/.MainActivity t222} time:95327
I/Timeline( 5490): Timeline: Activity_idle id: android.os.BinderProxy@52d661 time:95350
,W/BindingManager( 5490): Cannot call determinedVisibility() - never saw a connection for the pid: 5490
,D/JsMessageQueue( 5490): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5490): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622832128
,I/chromium( 5490): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5490): CheckpointMarkThreadRoots callback created = 0x9f69c3d0
,I/art     ( 5490): CheckpointMarkThreadRoots callback created = 0x9f69c3a0
,W/jxcore-log( 5490): Initializing JXcore engine
,W/jxcore-log( 5490): JXcore engine is ready
W/Thread-651( 5564): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8641]" dev="sockfs" ino=8641 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-651( 5564): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-651( 5564): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8821]" dev="sockfs" ino=8821 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-651( 5564): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-651( 5564): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-651( 5564): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25035]" dev="sockfs" ino=25035 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5490): Starting JXcore engine
,W/jxcore-log( 5490): Platform android
W/jxcore-log( 5490): 
W/jxcore-log( 5490): Process ARCH arm
W/jxcore-log( 5490): 
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  853): Killing 4926:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10086/pid_4926/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5425): mConnectedToCar = false, abort
,E/ActivityThread( 5425): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3a26e372 that was originally bound here
E/ActivityThread( 5425): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3a26e372 that was originally bound here
E/ActivityThread( 5425): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5425): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5425): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5425): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5425): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5425): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5425): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5425): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5425): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5425): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5425): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5425): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5425): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5425): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5425): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5425): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5425): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5425): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5425): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5425): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 5425): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@19c7ca35 that was originally bound here
E/ActivityThread( 5425): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@19c7ca35 that was originally bound here
E/ActivityThread( 5425): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5425): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5425): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5425): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5425): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5425): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5425): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5425): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5425): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5425): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5425): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5425): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5425): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5425): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 5425): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5425): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5425): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5425): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5425): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  853): Unbind failed: could not find connection for android.os.BinderProxy@d6ef556
I/jxcore-log( 5490): JXcore Cordova bridge is ready!
I/jxcore-log( 5490): 
,W/jxcore-log( 5490): JXcore engine is started
I/jxcore-log( 5490): Toggling radios to true
I/jxcore-log( 5490): 
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  853): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  853): Message: 1
D/BluetoothManagerService(  853): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(346115825)( 1969): onBind()
,D/BluetoothManagerService(  853): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  853): Message: 40
,D/LocationManagerService(  853): getAllProviders()=[passive, gps, network]
D/BluetoothManagerService(  853): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/Ulp_jni (  853): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  853): JNI:system_update. Event-4
D/WifiServiceImplEx(  853): setWifiEnabled: true pid=5490, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  853): setWifiEnabled: true pid=5490, uid=10316
,D/LocationManagerService(  853): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  853): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  853): JNI:system_update. Event-4
D/WifiServiceImplEx(  853): disconnect pid=5490, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  853): reconnect pid=5490, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5490): Radios toggled
I/jxcore-log( 5490): 
I/bluedroid( 1969): config_hci_snoop_log
I/jxcore-log( 5490): My device name is: LGE-LG-D722
I/jxcore-log( 5490): 
I/LGFTMITEM(  853): [GET_FTM][id=6], offset=12288
E/WifiHW  (  853): Wifi MAC Address = a0:39:f7:70:12:80
D/BluetoothManagerService(  853): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  853): Broadcasting onBluetoothServiceUp() to 9 receivers.
E/WifiHW  (  853): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  853): band=b
E/WifiHW  (  853): ": cur_etheraddr=a0:39:f7:70:12:80
D/SoftapController(  277): Softap fwReload - Ok
,W/art     ( 1929): Suspending all threads took: 19.760ms
,V/LGMDMManagerInternal( 1969): Create singleton instance
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring down wlan0
D/CommandListener(  277): Clearing all IP addresses on wlan0
E/WifiHW  (  853): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,I/wpa_supplicant( 5577): Successfully initialized wpa_supplicant
,D/WifiMonitor(  853): startMonitoring(wlan0) with mConnected = false
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1969): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1969): Setting state to 11
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/BluetoothAdapterState( 1969): Bluetooth adapter state changed: 10-> 11
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:14:58.361 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/BluetoothAdapterService(346115825)( 1969): updateAdapterState() - Broadcasting state to 1 receivers.
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/BluetoothManagerService(  853): Message: 60
,I/wpa_supplicant( 5577): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5577): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothManagerService(  853): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  853): Bluetooth State Change Intent: 10 -> 11
D/BluetoothAdapterService(346115825)( 1969): processStart()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5587 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/WifiServerServiceExt(  853): WIFI_STATE_CHANGED_ACTION [2]
D/BtSettings.ProfileConfig( 1969): Unable to read settings
D/BtSettings.ProfileConfig( 1969): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1969): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1969): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1969): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1969): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1969): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1969): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1969): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1969): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1969): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/LGBluetoothAPIService( 1798): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.pan.PanService
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1969): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): processStart() - Make Bond State Machine
I/[SystemUI]BluetoothHandler( 1368): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/BluetoothBondStateMachine( 1969): make
D/BluetoothAdapterService( 1969): setAdapterService() - set to: null
,D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/LGBluetoothServiceAdapter( 1969): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 1969): StableState(): Entering Off State
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1969): Unable to read settings
D/BtSettings.ProfileConfig( 1969): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1969): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1969): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1969): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1969): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1969): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1969): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1969): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1969): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1969): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1969): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 1969): Received start request. Starting profile...
D/BluetoothHeadset( 1745): Proxy object connected
D/BluetoothHeadset(  853): Proxy object connected
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
I/LGBluetoothHeadsetServiceJni( 1969): classInitNative: succeeds
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
,D/LGBluetoothFeatureConfig( 1969): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1969): classInitNative: succeeds
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/HeadsetStateMachine( 1969): make
D/BluetoothHeadset( 1745): Proxy object connected
D/BluetoothHeadset( 1745): Proxy object connected
,D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1969): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1969): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
D/HeadsetStateMachine( 1969): max_hf_connections = 1
I/bluedroid( 1969): get_profile_interface handsfree
,D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1969): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
I/bt-btif ( 1969): btif_hf_get_interface
I/bt-btif ( 1969): init
D/bt-btif ( 1969): max_hf_clients = 1
D/bt-btif ( 1969): btif_max_hf_clients = 1
D/bt-btif ( 1969): btif_enable_service: current services:0xa06d1330
V/LGMDMManager( 1969): Create singleton instance
,V/ToneGenerator( 1969): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  281): registerClient() client 0xb382bbc0, uid 1002
V/AudioPolicyManager(  281): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  281): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  281): getOutput() returns output 2
V/AudioFlinger(  281): registerClient() client 0xb55629e8, pid 1969
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): thread 0xb5651000 type 0 TID 1283 waking up
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  281): thread 0xb5735000 type 0 TID 1287 waking up
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioFlinger(  281): thread 0xb56eb000 type 0 TID 1284 waking up
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1368): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1368): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3115): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3115): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1368): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1368): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 3115): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3115): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1929): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1929): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1929): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1929): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2714): ioConfigChanged() event 0, ioHandle 4
,V/AudioSystem(  281): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  281): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2714): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1969): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1969): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 2714): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2714): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2714): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2714): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1368): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1368): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1929): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1929): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3115): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3115): ioConfigChanged() opening already existing output! 2
,V/AudioSystem( 1969): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1969): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 1969): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  853): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  853): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  853): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  853): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1745): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1745): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  853): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  853): ioConfigChanged() opening already existing output! 2
I/BluetoothAdapterState( 1969): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/AudioSystem( 1969): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/ToneGenerator( 1969): Create Track: 0xb4908a80
V/AudioTrack( 1969): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1969): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
I/AudioFlinger(  281): isAudioPlaybackHookOn() false
D/AudioTrack( 1969): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  281): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  281): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  281): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  281): getOutput() returns output 2
V/AudioSystem( 1969): getLatency() output 2, latency 50
V/AudioSystem( 1969): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1969): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1969): Create normal PCM 0x1 Track
V/AudioFlinger(  281): createTrack() lSessionId: 21
V/AudioFlinger(  281): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1969): Flags here  0x4 
V/AudioTrack( 1969): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  281): acquiring 21 from 1969, for 1969
V/AudioFlinger(  281):  added new entry for 21
V/ToneGenerator( 1969): ToneGenerator INIT OK, time: 99655
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/HeadsetStateMachine( 1969): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1969): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1969): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1969): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  281): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1969
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb5651000
D/BluetoothA2dp(  853): Proxy object connected
,D/A2dpService( 1969): Received start request. Starting profile...
D/audio_hw_primary(  281): adev_set_parameters: enter: bt_samplerate=8000
I/BluetoothAvrcpServiceJni( 1969): classInitNative: succeeds
V/voice   (  281): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  281): platform_set_parameters: enter: bt_samplerate=8000
V/Avrcp   ( 1969): make
D/Avrcp   ( 1969): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1969): get_profile_interface avrcp
I/bt-btif ( 1969): btif_rc_get_interface
I/bt-btif ( 1969): ## init ##
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
I/LGBluetoothAvrcpServiceJni( 1969): classInitNative: succeeds
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/LGBluetoothAvrcpAdapter( 1969): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1969): initNative: succeeds
V/ToneGenerator( 1969): ToneGenerator destructor
V/ToneGenerator( 1969): stopTone
V/ToneGenerator( 1969): Delete Track: 0xb4908a80
V/AudioTrack( 1969): ~AudioTrack, releasing session id from 1969 on behalf of 1969
V/AudioFlinger(  281): releasing 21 from 1969 for 1969
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): remove track (4099) and delete from mixer
V/AudioPolicyService(  281): AudioCommandThread() adding release output 2
V/AudioPolicyService(  281): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  281): PlaybackThread::Track destructor
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioFlinger(  281): removeClient_l() pid 1969, calling pid 281
V/AudioPolicyService(  281): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  281): releaseOutput() 2
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
,I/BluetoothAvrcpBrcmAdapterJni( 1969): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 1969): initBrcmNative
V/AudioService(  853): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  853): No RCC entry present to update
E/RemoteController( 1969): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1969): classInitNative
I/BluetoothA2dpServiceJni( 1969): classInitNative: succeeds
D/A2dpStateMachine( 1969): make
I/bluedroid( 1969): get_profile_interface a2dp
I/bt-btif ( 1969): btif_av_get_src_interface
I/bt-btif ( 1969): init
D/bt-btif ( 1969): btif_enable_service: current services:0xa06d1330
I/LGBluetoothA2dpServiceJni( 1969): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1969): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1969): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1969): [BTUI] init
D/LGBluetoothPowerControlManager( 1969): [BTUI] init : getProfileProxy
,D/BluetoothManagerService(  853): Message: 30
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/A2dpStateMachine( 1969): Enter Disconnected: -2
I/BluetoothHidServiceJni( 1969): classInitNative: succeeds
D/HidService( 1969): Received start request. Starting profile...
I/bluedroid( 1969): get_profile_interface hidhost
I/bt-btif ( 1969): btif_hh_get_interface
I/bt-btif ( 1969): init
D/bt-btif ( 1969): btif_enable_service: current services:0xa06d1330
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
I/BluetoothHealthServiceJni( 1969): classInitNative: succeeds
D/HealthService( 1969): Received start request. Starting profile...
I/bluedroid( 1969): get_profile_interface health
I/bt-btif ( 1969): btif_hl_get_interface
I/bt-btif ( 1969): init
D/bt-btif ( 1969): Process name (droid.bluetooth)
D/bt-btif ( 1969): btif_hl_soc_thread_init
,D/bt-btif ( 1969): create_thread: entered
D/bt-btif ( 1969): create_thread: thread created successfully
D/bt-btif ( 1969): entered btif_hl_select_thread
I/LGBluetoothHealthServiceJni( 1969): classInitNative: succeeds
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
I/BluetoothPanServiceJni( 1969): classInitNative(L105): succeeds
D/PanService( 1969): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1969): initializeNative(L110): pan
I/bluedroid( 1969): get_profile_interface pan
D/bt-btif ( 1969): stack_initialized = 0, btpan_cb.enabled:0
D/bt-btif ( 1969): stack_initialized = 0, btpan_cb.enabled:0
D/bt-btif ( 1969): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1969): max_s=55 
D/bt-btif ( 1969): set curr_set = org_set 
,I/LGBluetoothPanAdapter( 1969): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
I/BtGatt.JNI( 1969): classInitNative(L901): classInitNative: Success!
,D/BtGatt.DebugUtils( 1969): handleDebugAction() action=null
D/BtGatt.GattService( 1969): Received start request. Starting profile...
D/BtGatt.GattService( 1969): start()
I/bluedroid( 1969): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1969): advertise manager created
W/ResourcesManager( 5587): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5587): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5587): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/LGBluetoothGattAdapter( 1969): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1969): setGattService:  set to: null
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
,W/ResourcesManager( 5587): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5587): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
I/LGBluetoothMapAdapter( 1969): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1969): BluetoothMapBinder()
D/BluetoothMapService( 1969): Received start request. Starting profile...
D/BluetoothMapService( 1969): start()
D/BluetoothMapEmailSettingsLoader( 1969): Found 0 applications
D/BluetoothMapEmailAppObserver( 1969): createReceiver()
,D/BluetoothMapEmailAppObserver( 1969): initObservers()
D/BluetoothMapEmailAppObserver( 1969): getEnabledAccountItems()
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
I/BluetoothSAPServiceJni( 1969): classInitNative(L170): succeeds
,D/SapService( 1969): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1969): initializeNative(L175): sap
I/bluedroid( 1969): get_profile_interface sap
I/bt-btif ( 1969): btif_sc_get_interface
I/bt-btif ( 1969): init
D/bt-btif ( 1969): btif_enable_service: current services:0xa06d1330
I/LGBluetoothSapAdapter( 1969): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1969): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1969): [BTUI] initSapManager
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/LgeBluetoothSimManager( 1745): [BTUI] SAP_ENABLE_EVT
,V/BluetoothFTPServiceJni( 1969): classInitNative
I/BluetoothFTPServiceJni( 1969): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/BluetoothFTPService( 1969): BluetoothFtpBinder()
D/**BluetoothFTPService( 1969): Received start request. Starting profile...
V/BluetoothFTPService( 1969): FTP-Server Service start
D/BluetoothFTPServiceJni( 1969): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1969): get_profile_interface ftp
I/bt-btif ( 1969): btif_fts_get_interface
I/bt-btif ( 1969): init
D/bt-btif ( 1969): btif_enable_service: current services:0xa06d1330
D/BluetoothFTPServiceJni( 1969): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/HeadsetStateMachine( 1969): Proxy object connected
D/LGBluetoothHfpAdapter( 1969): [BTUI] queryPhoneState
D/LGBluetoothFeatureConfig( 1969): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1969): classInitNative
I/BluetoothOPPServiceJni( 1969): classInitNative(L373): succeeds
V/OppService( 1969): Opp initBinder
,D/**OppService( 1969): Received start request. Starting profile...
D/OppService( 1969): Starting OppService 
D/LGBluetoothOppAdapter( 1969): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/IndexDatabaseHelper( 5587): Using schema version: 115
,I/IndexDatabaseHelper( 5587): Index is fine
I/art     (  853): Explicit concurrent mark sweep GC freed 18401(864KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.340ms total 185.055ms
,I/NotificationManager( 1969): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 1969): send message
D/BluetoothOppPreference( 1969): Dumping Names:  
,D/BluetoothOppPreference( 1969): {}
D/BluetoothOppPreference( 1969): Dumping Channels:  
D/BluetoothOppPreference( 1969): {}
D/OppService( 1969): Start()
W/BluetoothOPPServiceJni( 1969): initOppNative
D/BluetoothOPPServiceJni( 1969): initOppNative(L383): OPP
I/bluedroid( 1969): get_profile_interface opp
I/bt-btif ( 1969): btif_op_get_interface
D/BluetoothOPPServiceJni( 1969): initOppNative(L411): mOppCallbacksObj 1049854
D/BluetoothOPPServiceJni( 1969): initOppNative(L413): calling OPP init
I/bt-btif ( 1969): btif_opp_init
D/bt-btif ( 1969): btif_enable_service: current services:0xa06d1330
D/BluetoothOPPServiceJni( 1969): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1969): initOppNative(L430): mOppCallbacksObj 1049854
V/OppService( 1969): setOppService(): set to: com.broadcom.bt.service.opp.OppService@998d91f
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/HeadsetStateMachine( 1969): Disconnected process message: 10, size: 0
V/OppService( 1969): pendingUpdate is :  true
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetPhoneState( 1969): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1969): Disconnected process message: 11, size: 0
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/OppService( 1969): Deleted complete outbound shares, number =  0
D/BluetoothAdapterService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1969): Proxy object connected
D/LGBluetoothPowerControlManager( 1969): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@33ab6eca
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@35fbe83b on behalf of 
,V/OppService( 1969): Deleted complete inbound failed shares, number = 0
D/BluetoothAdapterService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1969): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@15a60b58 on behalf of 
V/BluetoothOppNotification( 1969): update too frequent, put in queue
D/BluetoothAdapterService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1969): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
V/OppService( 1969): pendingUpdate is :  false
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
E/OppService( 1969): UpdateThread is Completed
D/BluetoothAdapte,rService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1969): Handler(): got msg=1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1969): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1969): new notify threadi!
V/BluetoothOppNotification( 1969): send delay message
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - All profile services started.
V/OppService( 1969): ContentObserver received notification
V/OppService( 1969): ContentObserver received notification
D/BluetoothAdapterState( 1969): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1969): enable
I/bt-btif ( 1969): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1969): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 1969): pendingUpdate is :  true
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,I/bt_hci_bdroid( 1969): init
I/bt_vendor( 1969): init
I/bt_vnd_conf( 1969): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/GKI_LINUX( 1969): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1969): btu_task pending for preload complete event
I/bt_vnd_conf( 1969): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1969): libbt-hci init returns 0
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@2d37d4b1 on behalf of 
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@3579ad96 on behalf of 
V/BluetoothOppNotification( 1969): mUpdateCompleteNotification = true
V/OppService( 1969): pendingUpdate is :  false
E/OppService( 1969): UpdateThread is Completed
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@2fb6cd17 on behalf of 
V/BluetoothOppNotification( 1969): outbound: succ-0  fail-0
I/NotificationManager( 1969): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1969): outbound notification was removed.
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@3a1c8504 on behalf of 
V/BluetoothOppNotification( 1969): inbound: succ-0  fail-0
I/NotificationManager( 1969): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1969): inbound notification was removed.
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@13c40aed on behalf of 
,V/BluetoothPbapReceiver( 1969): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1969): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1969): ***********state = 11
,V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/bt_userial_vendor( 1969): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 1969): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1969): device fd = 70 open
D/bt_hwcfg( 1969): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1969): hw_config_cback state=1
,D/WiFiOffLoadUpdatePriority( 5587): remove : truetruefalse
D/WiFiOffLoadUpdatePriority( 5587): remove2
V/WiFiOffLoadSharedPrefsUtils( 5587): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5587): save remove
D/WiFiOffLoadBroadcast( 5587): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5587): S: false, R: true
D/bt_hwcfg( 1969): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1969): hw_config_cback state=4
D/bt_hwcfg( 1969): Chipset Name: BCM4334B0
D/bt_hwcfg( 1969): Chipset BCM4334B0
D/bt_hwcfg( 1969): Target name = [BCM4334B0]
I/bt_hwcfg( 1969): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1969): hw_config_cback state=2
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1969): hw_config_cback state=3
I/bt_hwcfg( 1969): bt vendor lib: set UART baud 4000000
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1969): hw_config_cback state=5
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/ActivityManager(  853): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5633 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothPermissionRequest( 5587): onReceive
D/LGBluetoothFeatureConfig( 5587):  get() - isFeatureLoaded : false
D/Tethering(  853): sendTetherStateChangedBroadcast 1, 0, 0
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
,D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/DSQN    (  853): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
E/wpa_supplicant( 5577): USIM:  scard_init function
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
I/wpa_supplicant( 5577): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 9
I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
I/ActivityManager(  853): Process com.google.android.gm (pid 5053) has died
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/PCSuite ( 5633): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/BluetoothManagerService(  853): Message: 20
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25996931:true
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
I/ActivityManager(  853): Killing 4862:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,W/System.err( 5028): android.os.DeadObjectException
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
W/System.err( 5028): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5028): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5028): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5028): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5028): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5028): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5028): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5028): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5028): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5028): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5028): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5028): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
E/UEI.SmartControl( 5028): IControl.unregisterCallback error: android.os.DeadObjectException
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
W/System.err( 5028): android.os.DeadObjectException
W/System.err( 5028): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5028): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5028): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5028): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5028): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5028): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5028): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5028): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5028): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5028): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5028): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5028): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5028): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
I/wpa_supplicant( 5577): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
I/wpa_supplicant( 5577): wlan0: CTRL-EVENT-SCAN-STARTED 
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/WifiStateMachine(  853): MAC Addr from driver = a0:39:f7:70:12:80
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  853): setPowerSaveActivated(false)
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
,D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1969): hw_config_cback state=6
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1969): hw_config_cback state=6
E/lowmemorykiller(  240): Error opening /proc/4862/oom_score_adj; errno=2
,D/UsbSettingsReceiver( 5587): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5587): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5587): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5587): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/bt_hwcfg( 1969): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1969): Settlement delay -- 100 ms
I/bt_hwcfg( 1969): Setting fw settlement delay to 100 
W/ActivityManager(  853): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  853): android.os.DeadObjectException
W/ActivityManager(  853): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  853): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  853): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  853): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  853): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager(  853): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  853): android.os.DeadObjectException
W/ActivityManager(  853): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  853): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  853): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  853): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  853): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  853): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  853): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_4862/cgroup.procs: No such file or directory
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5660 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/UsbSettingsReceiver( 5587): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServerServiceExt(  853): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt(  853): batteryPsActivateMsgHandler : state:0 event:3
E/WifiServerServiceExt(  853): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
E/WifiConfigStore(  853): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine(  853): enableVerboseLogging : level 2
,D/WifiStateMachine(  853): Setting OUI to DA-A1-19
D/WifiNative-HAL(  853): Setting external_sim to 1
I/WifiNative-HAL(  853): startHal
E/wifi    (  853): getStaticLongField sWifiHalHandle 0x9ace18ec
I/WifiHAL (  853): Initializing wifi
I/WifiHAL (  853): Creating socket
I/WifiHAL (  853): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  853): Did set static halHandle = 0xb072b200
D/wifi    (  853): halHandle = 0xb072b200, mVM = 0xb487c280, mCls = 0x401c0e
E/wifi    (  853): getStaticLongField sWifiHalHandle 0x9ace189c
D/wifi    (  853): array field set
I/WifiNative-HAL(  853): interface[0] = wlan0
I/WifiNative-HAL(  853): interface[1] = p2p0
D/wifi    (  853): setting scan oui 0x9cda1c88
D/WifiHAL (  853): Sending mac address OUI
E/WifiHAL (  853): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  853): Setting OUI to DA-A1-19
I/WifiNative-HAL(  853): startHal
D/wifi    (  853): setting scan oui 0x9cda1c88
D/WifiHAL (  853): Sending mac address OUI
E/WifiHAL (  853): failed to set scanning mac OUI; result = -95
I/WifiNative-HAL(  853): Waiting for HAL events mWifiHalHandle=-1334660608
D/wifi    (  853): waitForHalEvents called, vm = 0xb487c280, obj = 0x401c0e, env = 0x9dceef60
E/wifi    (  853): getStaticLongField sWifiHalHandle 0x99072b2c
,D/WifiHS20(  853): hidePasspointNotification off =false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  853): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiScanningService(  853): SCAN_AVAILABLE : 3
D/RttService(  853): SCAN_AVAILABLE : 3
D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring up p2p0
D/WifiScanningService(  853): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  853): startHal
D/WifiMonitor(  853): startMonitoring(p2p0) with mConnected = true
D/wifi    (  853): getting scan capabilities on interface[0] = 0x9cda1c88
D/WifiHAL (  853): Creating message to get scan capablities; iface = 24
D/LGWifiP2pService(  853): P2pEnablingState
D/wifi    (  853): failed to get capabilities : -95
D/LGWifiP2pService(  853): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiScanningService(  853): could not get scan capabilities
D/LGWifiP2pService(  853): P2p socket connection successful
D/RttService(  853): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1969): hw_config_cback state=2
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:14:59.829 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1969): hw_config_cback state=7
I/bt_hwcfg( 1969): bt vendor lib: set UART baud 4000000
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/bt_hwcfg( 1969): Setting local bd addr to F8:95:C7:87:85:54
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
W/Settings( 5100): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsService( 1798): Supplicant Connection state is changed : true
D/WfdsService( 1798): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1798): Set the WFDS Monitor: true
V/BluetoothSapReceiver( 1969): [BTUI] checkServiceStart
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/WfdsMonitor( 1798): WfdsMonitorThread create
D/LGBluetoothStateChangeReceiver( 1969): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGWifiP2pService(  853): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  853): before postfix = G3s-1
,D/WfdsMonitor( 1798): WFDS Monitor is created and started
D/WfdsService( 1798): WiFi: Supplicant connection re-established
D/WifiServerServiceExt(  853): postfix byte check : 5
D/LGWifiP2pService(  853): after postfix = G3s-1
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:14:59.849 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/WifiServerServiceExt(  853): set CMD_ADD_DEFAULT_PROFILE
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiNative-HAL(  853): p2pGetDeviceAddress
D/WifiNative-HAL(  853): p2pGetDeviceAddress returning a2:39:f7:70:12:80
D/bt_hwcfg( 1969): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1969): hw_config_cback state=8
E/CtrlSupplicant( 1798): Access OK "@android:wpa_wlan0"
I/bt_hwcfg( 1969): vendor lib fwcfg completed
I/bt-btif ( 1969): HC preload_cb 0 [0:SUCCESS 1:FAIL]
E/CtrlSupplicant( 1798): Succeed to open control connection
I/bt-btu  ( 1969): btu_task received preload complete event
E/CtrlSupplicant( 1798): Succeed to open monitor connection
D/WfdsMonitor( 1798): Supplicant connection established
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/WfdsService( 1798): Connected to the supplicant for wfds
I/WifiServerServiceExt(  853): setWifiDualbandAPConnection band : 1
,E/wpa_supplicant( 5577): nWIFIDualbandAPConnection: 1
I/WifiServerServiceExt(  853): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5577): disconnect_rssi_lvl: -100
I/WifiServerServiceExt(  853): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5577): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
I/WifiServerServiceExt(  853): set CMD_UPDATE_DEFAULT_PROFILE
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/        ( 1969): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1969): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1969): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1969): BTE_InitTraceLevels -- TRC_PROTOCOL,0
I/ActivityManager(  853): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5679 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/LGWifiP2pService(  853): DeviceAddress: a2:39:f7:70:12:80
I/wpa_supplicant( 5577): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/wpa_supplicant( 5577): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WfdsService( 1798): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,D/WfdsService( 1798): Update P2p Interface State: 3
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,D/LGWifiP2pService(  853): sending p2p persistent groups changed broadcast
,I/wpa_supplicant( 5577): wlan0: Associated with c0:ff:d4:d3:aa:48
D/LGWifiP2pService(  853): sending p2p connection changed broadcast
D/LGWifiP2pService(  853): InactiveState
D/WfdsService( 1798): WifiP2pState is changed : true
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1798): Receive the WFDS_ENABLE Method
D/WfdsService( 1798): Set the WFDS Monitor: true
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1798): Connected to the supplicant for wfds
D/WfdsJNI ( 1798): doCommand: WFDS_SET TRUE
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/LGWifiP2pService(  853): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsJNI ( 1798): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5577): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsService( 1798): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsJNI ( 1798): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5577): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1798): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1798): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1798): selectPreferredScanChannel [6]
D/WfdsService( 1798): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
E/WifiServerServiceExt(  853): No p2p device connected
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  853): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1798): isConnected: false
D/WfdsService( 1798): GroupInfoAvailable: mGroupInfo is null
W/WfdsService( 1798): DefaultState - msg [9441285] is not handled
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:14:59.98 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/wpa_supplicant( 5577): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5577): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
D/LocSvc_java(  853): onReceive
D/UEI.SmartControl( 5660): Quickset Services start...
I/UEI.SmartControl( 5660): Manufacture = LGE
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=555648605, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,D/UEI.SmartControl( 5660): File observer start...
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:00.005 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/UEI.SmartControl( 5660): IR Port is disabled: false
D/UEI.SmartControl( 5660): Starting file observer...
D/UEI.SmartControl( 5660): Extracting JNI libs...
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
D/UEI.SmartControl( 5660): --- this system supports 32-bit or 64-bit only
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:00.014 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.Netwo,rkController( 1368): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:00.018 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateSCANNING
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:00.023 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/WifiServiceExtension(  853): setVHTCapabilityType  : false
D/GONS    ( 1745): GONS isTestMode: false Country: 
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
,E/bt-btif ( 1969): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/GKI_LINUX( 1969): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1969): warning : media task started media_task_refcnt 1 
D/BT_PROF_AUDIO( 1969): created moving average (N=100)
D/BT_PROF_AUDIO( 1969): reset rate average
W/bt-btif ( 1969): overflow 0, enter 0, exit 0
W/bt-smp  ( 1969): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1969): Plain text(LSB ~ MSB) = 36 43 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1969): Encrypted text(LSB ~ MSB) = 6d 9e 5a ab f4 e6 2c a4 34 21 2f 2a cd 28 c7 10 
W/bt-btm  ( 1969): Stopping oneshot timer
E/bt-btif ( 1969): Calling BTA_HhEnable
E/bt-btif ( 1969): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1969): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1969): Address is:F8:95:C7:87:85:54
D/BluetoothManagerService(  853): Bluetooth Adapter name changed to G3s-1
I/[SystemUI]Clock( 1368): called onTimeUpdated()
D/BluetoothManagerService(  853): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1969): Name is: G3s-1
D/BluetoothAdapterProperties( 1969): Scan Mode:20
I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
D/BluetoothAdapterProperties( 1969): Discoverable Timeout:120
I/[SystemUI]DateView( 1368): called onTimeUpdated()
,E/bt-btif ( 1969): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1969): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
I/[SystemUI]DateView( 1368): called onTimeUpdated()
E/bt-btif ( 1969): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1969): BTA_JvEnable
E/bt-btif ( 1969): btsock_vendor_hci_init: !vhci_init
D/UsbSettingsControl( 5587): [AUTORUN] getUsbConnected() : connected=true
D/bt-btif ( 1969): btsock_ctrl_hci_init(L191): poll handle:6
D/UsbSettingsReceiver( 5587): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5587): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5587): [AUTORUN] onReceive() : errorList=[]
D/bt-btif ( 1969): init_hci_slots(L136): in
D/IOP_DB_BT( 1969): db_open: file /etc/bluetooth/iop_bt.db
D/UsbSettingsControl( 5587): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5587): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/WifiServerServiceExt(  853): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  853): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/IOP_DB_BT( 1969): db_open: db_open : handle 2691545052l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1969): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1969): db_query: result 1
I/        ( 1969): iop_db_open: iop_db_open status 0
E/bt-btif ( 1969): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1969): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1969): bta_pan_co_init
I/WifiServiceExtension(  853): setSecurityType  : 2
D/UsbSettingsControl( 5587): [AUTORUN] setTetherStatus() : status=false
,V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bte_conf( 1969): Device ID record 1 : primary
D/bte_conf( 1969):   vendorId            = 00c4
D/bte_conf( 1969):   vendorIdSource      = 0001
D/bte_conf( 1969):   product             = 13a1
D/bte_conf( 1969):   version             = 1000
D/bte_conf( 1969):   clientExecutableURL = 
D/bte_conf( 1969):   serviceDescription  = 
D/bte_conf( 1969):   documentationURL    = 
D/bte_conf( 1969): bte_load_did_conf no section named DID2.
D/WiFiOffLoadUpdatePriority( 5587): remove : truetruetrue
I/bt-btif ( 1969): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 1969): btif_hf_upstreams_evt: wrong handle = 26465 
I/bt-btif ( 1969): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1969): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 1969): onOpcStateChange()
I/bt-btif ( 1969): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1969): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 1969): onOpsStateChange() :0
I/bt-btif ( 1969): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothAdapterState( 1969): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/OppService( 1969): Recieved MESSAGE_OPC_ENABLE
D/BluetoothFTPServiceJni( 1969): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1969): onFtpServerEnabled: /storage
D/LGBluetoothFeatureConfig( 1969): isPrivacyLogsEnabled : true
D/BluetoothPanServiceJni( 1969): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 1969): ScanMode =  20
D/BluetoothAdapterProperties( 1969): State =  11
D/BluetoothAdapterProperties( 1969): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1969): Setting state to 12
I/BluetoothAdapterState( 1969): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(346115825)( 1969): updateAdapterState() - Broadcasting state to 1 receivers.
I/bt-btif ( 1969): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  853): Message: 60
D/BluetoothManagerService(  853): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/bt_h4   ( 1969): vendor lib postload completed
D/OppService( 1969): Recieved MESSAGE_OPS_ENABLE
I/BluetoothAdapterState( 1969): Entering On State
I/BluetoothAdapterState( 1969): Entering On State from state = 11
D/BluetoothAdapterProperties( 1969): Scan Mode:21
I/bt-btif ( 1969): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1969): Discoverable Timeout:120
D/BluetoothManagerService(  853): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(346115825)( 1969): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1969): [BTUI] autoConnect() : not allowed
D/BluetoothA2dp(  853): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
,D/LGBluetoothServiceAdapter( 1969): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1969): [BTUI]         global_name: G3s-1
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 1969): [BTUI]         local_name: G3s-1
D/BluetoothA2dp( 1969): onBluetoothStateChange: up=true
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): isQuetModeEnabled() - Enabled = false
D/BluetoothHeadset(  853): onBluetoothStateChange: up=true
D/BluetoothAdapterService(346115825)( 1969): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1969): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=true
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:00.089 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:00.091 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/BluetoothManagerService(  853): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
E/BluetoothManagerService(  853): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  853): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  853): Message: 40
D/BluetoothManagerService(  853): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothOppNotification( 1969): new notify threadi!
V/BluetoothOppNotification( 1969): send delay message
,V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/LGBluetoothAPIService( 1798): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@61b0d22 on behalf of 
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/BluetoothMapService( 1969): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1969): STATE_ON
V/BluetoothMapService( 1969): Handler(): got msg=1
D/BluetoothMapMasInstance( 1969): Map Service startRfcommSocketListener
D/LGBluetoothAPIService( 1798): Message: 1
D/LGBluetoothAPIService( 1798): MESSAGE_BOOT_COMPLETED
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
,W/ResourcesManager( 5679): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/LGBluetoothAPIService( 1798): [BTUI] LGBluetoothAPIService Binding Success
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/BluetoothMapMasInstance( 1969): MAS initSocket()
D/BluetoothMapMasInstance( 1969):   masId = 00
D/BluetoothMapMasInstance( 1969):   msgTypes = 0e
D/BluetoothMapMasInstance( 1969):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1969):   SDP string = 000eSMS/MMS
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
V/BluetoothOppNotification( 1969): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothPbapService( 1969): Pbap Service onCreate
V/BluetoothPbapService( 1969): Starting PBAP service
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/LGBluetoothPbapAdapter( 1969): [BTUI] getInstance : create
D/ConnectivityService(  853): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  853): Got NetworkAgent Messenger
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
V/BluetoothPbapService( 1969): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1969): state: 12
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  853): NetworkAgent connected
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1368): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
W/BluetoothAdapter( 1969): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothAPIServer( 1969): [BTUI] onCreate()
D/WifiExtManager(  853): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@80d22d9
D/LGBluetoothAPIServer( 1969): [BTUI] onBind()
D/WifiExtManager(  853): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@787eb7f
V/BluetoothPbapService( 1969): Handler(): got msg=1
,V/BluetoothPbapService( 1969): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 1969): Pbap Service initSocket
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@3f6368e9 on behalf of 
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 1969): outbound: succ-0  fail-0
I/NotificationManager( 1969): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
W/BluetoothAdapter( 1969): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 1969): outbound notification was removed.
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/LGBluetoothAPIService( 1798): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1969): [BTUI] createSocketChannel FD=83 mFd=0
D/LGBluetoothAPIService( 1798): Message: 100
V/BluetoothMapMasInstance( 1969): Succeed to create listening socket 
D/LGBluetoothAPIService( 1798): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothMapMasInstance( 1969): Accepting socket connection...
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1969): [BTUI] createSocketChannel FD=85 mFd=83
V/BluetoothPbapService( 1969): Succeed to create listening socket 
V/BluetoothPbapService( 1969): Accepting socket connection...
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@1480d96e on behalf of 
V/BluetoothOppNotification( 1969): inbound: succ-0  fail-0
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 5679): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
I/NotificationManager( 1969): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/BluetoothOppNotification( 1969): inbound notification was removed.
V/BluetoothOppProvider( 1969): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/AuthorizationBluetoothService( 1727): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppProvider( 1969): created cursor android.database.sqlite.SQLiteCursor@1630480f on behalf of 
D/WeatherService( 2699): 2 : TimeTick Intent has been received, Time(hour:min:sec) 18:15:0
D/WeatherService( 2699): 2 : TimeTick Intent And Screen On
D/WeatherService( 2699): 2 : SDK version : 21
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2699): 2 : Utils getTopActivity com.lge.launcher2 / true
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WeatherService( 2699): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2699): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2699): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
D/WeatherService( 2699): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2699): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2699): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2699): 2 : Fixed theme : optimus
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Setting iface cfg
D/WeatherReflect( 2699): 2 : Map key string is -2
D/UEI.SmartControl( 5660): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
E/WifiStateMachine(  853): Start Dhcp Watchdog 1
D/DhcpStateMachine(  853): StoppedState
D/DhcpStateMachine(  853): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/UEI.SmartControl( 5660): --- Checking lib: libqs_armeabi-v7a.zip
D/lim     ( 2699): 2 : time = 18:15
D/UEI.SmartControl( 5660): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/DhcpStateMachine(  853): WaitBeforeStartState
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateASSOCIATED
,I/WeatherReflect( 2699): Model Name : LG-D722
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WeatherTheme( 2699): 2 : Different view - status_min_formatted : 14 != 15
D/WeatherTheme( 2699): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateGROUP_HANDSHAKE
D/WeatherReflect( 2699): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/QCNEJ   ( 1833): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:00.209 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
,D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2699): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/Weather4x2_optimus( 2699): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2699): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2699): forecast size is 0
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2699): WEATHER_CP_ACCU : 
,I/Theme_WeatherAncestor_optimus( 2699): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2699): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2699): url is : null
I/UEI.SmartControl( 5660): --- Selecting new region: 2
I/UEI.SmartControl( 5660): -- Running on KitKat(19) and above! JNI will be used.
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2699): 2 : update view, appWidgetId: 2
D/UEI.SmartControl( 5660): Platform has CIR...
D/UEI.SmartControl( 5660): NO CIR support, need to check package...
D/WeatherService( 2699): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 18:15:0
I/UEI.SmartControl( 5660): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5660): QS Service created
,D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=555648605 [*alarm*], flags=0x0
E/UEI.SmartControl( 5660): QS start get config
,E/WifiStateMachine(  853): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  853): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  853): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@758f14e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@758f14e target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  853): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  853): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine(  853): WaitBeforeStartState{ when=-3ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateCOMPLETED
D/DhcpStateMachine(  853): DHCP Start wake lock is acquired.
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateCOMPLETED
D/WiFiOffLoadUpdatePriority( 5587): remove1
V/WiFiOffLoadSharedPrefsUtils( 5587): save remove
,D/WiFiOffLoadBroadcast( 5587): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5587): S: false, R: false
,D/WiFiOffLoadUpdatePriority( 5587): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5587): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5587): private wpa: "NG700" 300
D/WifiServiceImplEx(  853): addOrUpdateNetwork pid=5587, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  853):  uid = 1000 SSID "NG700" nid=0
E/WifiConfigStore(  853):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/UEI.SmartControl( 5660): Loading JNI Libs...
D/UEI.SmartControl( 5660):  configuring local db...
,E/WifiConfigStore(  853): Setting BSSID for "NG700"WPA_PSK to any
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/WiFiOffLoadUpdatePriority( 5587):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5587): configuration updated: 0
I/WifiServerServiceExt(  853): set CMD_UPDATE_DEFAULT_PROFILE
D/WiFiOffLoadUpdatePriority( 5587): configuration saved: true
D/PCSuite ( 5633): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/ContextImpl( 5587): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 1969): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1969): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1969): ***********state = 12
I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5720 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/DhcpStateMachine(  853): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  853): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  853): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
E/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/dhcpcd  ( 5726): version 5.5.6 starting
E/dhcpcd  ( 5726): get_duid: Read-only file system
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/LocalBluetoothProfileManager( 5587): Adding local A2DP profile
D/BluetoothManagerService(  853): Message: 30
D/LocalBluetoothProfileManager( 5587): Adding local HEADSET profile
,D/BluetoothManagerService(  853): Message: 30
D/BluetoothManagerService(  853): Message: 30
,D/BluetoothManagerService(  853): Message: 30
,D/LocalBluetoothProfileManager( 5587): Adding local MAP profile
D/BluetoothMap( 5587): Create BluetoothMap proxy object
D/BluetoothManagerService(  853): Message: 30
I/dhcpcd  ( 5726): wlan0: rebinding lease of 192.168.1.134
D/BluetoothManagerService(  853): Message: 30
,D/LocalBluetoothProfileManager( 5587): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 1969): Pbap Service onBind
D/UEI.SmartControl( 5660):  ---- Has DB8: true
D/LGBluetoothUserBindClient( 5587): [BTUI] initUserBindClient
W/ContextImpl( 5587): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/UEI.SmartControl( 5660): QS start statue = true Error code = 0
D/UEI.SmartControl( 5660): QS version = v2.7.11.1_RC1
D/DockEventReceiver( 5587): finishStartingService: stopping service
D/UEI.SmartControl( 5660): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/BluetoothA2dp( 5587): Proxy object connected
D/UEI.SmartControl( 5660): IRRCDataComm has AudioManager!!!!.
,D/A2dpProfile( 5587): Bluetooth service connected
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothHeadset( 5587): Proxy object connected
,D/HeadsetProfile( 5587): Bluetooth service connected
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothInputDevice( 5587): Proxy object connected
D/HidProfile( 5587): Bluetooth service connected
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothPan( 5587): BluetoothPAN Proxy object connected
D/PanProfile( 5587): Bluetooth service connected
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothMap( 5587): Proxy object connected
W/irrc_jni( 5660): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5660): IrrcClient ++ 
D/irrcClient( 5660): getIrrcService ++ 
D/irrcClient( 5660): getIrrcService -- 
D/irrcClient( 5660): IrrcClient -- 
W/irrc_jni( 5660): IRRCPlayer_nativeInit -- 
D/MapProfile( 5587): Bluetooth service connected
D/BluetoothMap( 5587): getConnectedDevices()
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
V/BluetoothMapService( 1969): getConnectedDevices()
D/BluetoothPbap( 5587): Proxy object connected
D/PbapServerProfile( 5587): Bluetooth service connected
D/LGBluetoothUserBindClient( 5587): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5587): onReceive
D/LGBluetoothFeatureConfig( 5587): isPrivacyLogsEnabled : true
,D/LGBluetoothUtils( 5587): [BTUI] FileNotFound: readProperty
I/ActivityManager(  853): Killing 5028:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 5660): Services init done
I/UEI.SmartControl( 5660): Device manager: loading config....
,D/UEI.SmartControl( 5660): Config is loaded...
D/UEI.SmartControl( 5660):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5660): Notify AllClients services are ready: 0
V/BluetoothOppReceiver( 1969): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_5028/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5660): QS Service init finished
D/LGDMClient( 5720): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5720): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/BluetoothOppManager( 1969): restoreApplicationData! falsefalsenullnull
D/UEI.SmartControl( 5660): QS Service version name: 0.1.73
W/ContextImpl( 5720): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/UEI.SmartControl( 5660): QS Service version code: 1073
,W/ContextImpl( 5720): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/BluetoothSapReceiver( 1969): [BTUI] checkServiceStart
D/UEI.SmartControl( 5660): Service requested: Control
D/UEI.SmartControl( 5660): Service.onUnbind: IControl
D/LGBluetoothStateChangeReceiver( 1969): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/UEI.SmartControl( 5660): Service.onDestroy
D/UEI.SmartControl( 5660): Shutdown IRRCPlayer... 
D/AuthorizationBluetoothService( 1727): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
D/LGDMClient( 5720): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,W/irrc_jni( 5660): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5660): ~IrrcClient ++ 
D/irrcClient( 5660): ~IrrcClient -- 
W/irrc_jni( 5660): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5660): Blaster closed
D/UEI.SmartControl( 5660): Blaster closed
D/UEI.SmartControl( 5660): Shut down QS...
D/LGDMClient( 5720): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/UEI.SmartControl( 5660): Stopped file observer...
I/UEI.SmartControl( 5660): QS lib stop result = true
D/UEI.SmartControl( 5660): QS shutdown complete
D/UEI.SmartControl( 5660): QS Service created
D/LGDMClient( 5720): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/PCSuite ( 5633): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 5633): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5633): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/UEI.SmartControl( 5660): QS start get config
D/UEI.SmartControl( 5660):  configuring local db...
,I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5758 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  853): Killing 5353:com.android.calendar/u0a13 (adj 15): empty #11
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 23.269ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.787ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.099ms
,W/libprocessgroup(  853): failed to open /acct/uid_10013/pid_5353/cgroup.procs: No such file or directory
,I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 6
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 5660):  ---- Has DB8: true
,W/ResourcesManager( 5758): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5660): QS start statue = true Error code = 0
D/UEI.SmartControl( 5660): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5660): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5660): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5660): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5660): IrrcClient ++ 
D/irrcClient( 5660): getIrrcService ++ 
D/irrcClient( 5660): getIrrcService -- 
D/irrcClient( 5660): IrrcClient -- 
W/irrc_jni( 5660): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5660): Services init done
,I/UEI.SmartControl( 5660): Device manager: loading config....
D/UEI.SmartControl( 5660): QS Service init finished
D/UEI.SmartControl( 5660): QS Service version name: 0.1.73
D/UEI.SmartControl( 5660): QS Service version code: 1073
D/UEI.SmartControl( 5660): Config is loaded...
D/UEI.SmartControl( 5660): Service requested: Control
I/ActivityManager(  853): Killing 5318:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/UEI.SmartControl( 5660):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5660): Notify AllClients services are ready: 0
,W/libprocessgroup(  853): failed to open /acct/uid_10014/pid_5318/cgroup.procs: No such file or directory
,E/ActivityThread( 5660): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@14a14ef1 that was originally bound here
E/ActivityThread( 5660): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@14a14ef1 that was originally bound here
E/ActivityThread( 5660): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5660): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5660): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5660): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5660): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5660): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 5660): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 5660): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 5660): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5660): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5660): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5660): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5660): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5660): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5660): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5660): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5660): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5660): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 5660): Internal service binding...
D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@117865e0:true
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/ActivityManager(  853): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5781 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/dhcpcd  ( 5726): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5726): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,V/AudioFlinger(  281): thread 0xb56eb000 type 0 TID 1284 going to sleep
,V/AudioFlinger(  281): thread 0xb5735000 type 0 TID 1287 going to sleep
V/AudioFlinger(  281): thread 0xb5651000 type 0 TID 1283 going to sleep
I/ActivityManager(  853): Process com.google.android.talk (pid 5100) has died
,V/[BNRBootReceiver]( 5781): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5781): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5781): Boot Receiver Return
W/MainApplication( 5781): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5587): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
,D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  853): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  853): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  853): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  853): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  853): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  853): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  853): bShouldSendDhcpAction Result: true
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  853): DHCP Start/Renew wake lock is released.
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
D/DhcpStateMachine(  853): RunningState
,E/WifiStateMachine(  853): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  853): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  853): ignoring duplicate network state non-change
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  853): Adding iface wlan0 to network 100
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:01.767 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  853): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService(  853): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  853): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  853): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  853): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:01.785 DNS addrs= 192.168.1.1, 0.0.0.0, 
E/WifiStateMachine(  853): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  853): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService(  853): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  853): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  853): Setting Dns servers for network 100 to [/192.168.1.1]
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:01.803 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:01.805 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,D/Nat464Xlat(  853): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,D/ConnectivityService(  853): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Connected
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  853): currentScore = 0, newScore = 20
D/ConnectivityService(  853):    accepting network in place of null
D/ConnectivityService(  853): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/TelephonyNetworkFactory-1( 1745): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = true, mWifiLevel = 2
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] Start DNSResolver start to wait
E/ConnectivityService(  853): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  853): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  853): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  853): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] wait 500ms before dns check
D/ConnectivityService(  853): validation of new default Network = false
D/ConnectivityService(  853): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  853): enableDataServiceNotify 
D/DSQN    (  853): start dsqn bin
D/Tethering(  853): MasterInitialState.processMessage what=3
,W/QCNEJ   ( 1833): |CORE| No family connected
I/QCNEJ   ( 1833): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
I/QCNEJ   ( 1833): |CORE| sendDefaultNwMsg: default = 1
,V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,V/LGMDMManager( 5758): Create singleton instance
,D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524290
,V/NetworkPolicy(  853): [LG_RESTRICTED] checkMobilePolicy_type()
I/DSQN    ( 5827): DSQN samuel.seo ver 141203
E/DSQN    ( 5827): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5827): created command queue thread
I/DSQN    ( 5827): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5827): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/AudioManager( 5758): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5660): -----IControl: 11
D/UEI.SmartControl( 5660): File observer start...
E/UEI.SmartControl( 5660): IR Port is disabled: false
D/UEI.SmartControl( 5660): Starting file observer...
D/UEI.SmartControl( 5660): Caller: com.lge.qremote
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 5660): ------------ IControl registerCallback...
I/UEI.SmartControl( 5660): Registering callback...
,D/UEI.SmartControl( 5660): -----IControl: 19
D/UEI.SmartControl( 5660): Caller: com.lge.qremote
I/UEI.SmartControl( 5660): Registering Services Ready callback...
I/UEI.SmartControl( 5660): Notify client services are ready...
D/UEI.SmartControl( 5660): -----IControl: 8
D/UEI.SmartControl( 5660): Caller: com.lge.qremote
,D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
I/PCSuite ( 5633): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5633): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 5587): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5587): MCCMNC not supported: null
I/PCSuite ( 5633): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5633): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/AudioManager( 5758): getMode name:com.lge.qremote
I/ActivityManager(  853): Killing 5425:com.google.android.gms:car/u0a6 (adj 15): empty #11
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_5425/cgroup.procs: No such file or directory
,I/AudioManager( 5758): getMode name:com.lge.qremote
I/AudioManager( 5758): getMode name:com.lge.qremote
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] DNSResolver start dns
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5827): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5827): restart monitoring
,D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5827): dsqn report finish
D/DSQN    (  853): DSQM DsqnNotification wlan0  1
D/DSQN    (  853): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 17:15:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453396502491], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453396502467]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Validated
D/ConnectivityService(  853): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  853): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  853): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524290
D/ConnectivityService(  853): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1745): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  853): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  853): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1833): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:15:03.231 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/NotificationManager( 1929): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  853): Process com.google.android.gms (pid 5236) has died
,V/WifiInternetCheck(  853): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  853): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  853): onReceive
D/LocSvc_java(  853): got connectivity action
,D/LocSvc_java(  853): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  853): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  853): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  853): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  853): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  853): Sending msg: 5 arg1:0 arg2:1
I/ActivityManager(  853): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5860 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  853): NTP server returned: 1453396502308 (Thu Jan 21 18:15:02 GMT+01:00 2016) reference: 103067 certainty: 14 system time offset: -2610
,D/LocSvc_java(  853): Sending msg: 10 arg1:0 arg2:1
,D/AlarmManagerService(  853): Setting time of day to sec=1453396505
,W/AlarmManagerService(  853): Unable to set rtc to 1453396505: Invalid argument
I/ActivityManager(  853): Start proc com.google.android.gms for service com.google.android.gms/.chromesync.sync.SyncService: pid=5889 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/UEI.SmartControl( 5660): file observer is disposed!
I/[SystemUI]Clock( 1368): onReceive = android.intent.action.TIME_SET
,D/WeatherService( 2699): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:15:5
D/WeatherService( 2699): 2 : requestRefreshAppWidget, isUpdateStart : false
I/LgeClockWidgetControlView( 1368): time changed, timezoneChanged : false
,D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
D/WeatherService( 2699): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2699): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2699): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2699): 2 : Fixed theme : optimus
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/WeatherReflect( 2699): 2 : Map key string is -2
D/lim     ( 2699): 2 : time = 18:15
I/WeatherReflect( 2699): Model Name : LG-D722
,I/ActivityManager(  853): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5906 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/WeatherTheme( 2699): 2 : exactly same view!
D/WeatherTheme( 2699): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2699): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:15:5
W/ActivityManager(  853): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 1871): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=21 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 1871): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 21
I/[LGHome]LGCalendarIcon( 1871): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 21
,I/ActivityManager(  853): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5917 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/GpsLocationProvider(  853): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 5917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5917): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5917): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
E/GpsLocationProvider(  853): No APN found to select.
,W/ResourcesManager( 5906): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5906): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5906): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LgeGpsConstants(  853): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
I/AppConfig( 5917): Total System Memory = 906309632
I/GalleryUtils( 5917): Application Heap = 96 MB
I/AppConfig( 5917): App Tier : NOT_DEF
,D/SystemHelper( 5917): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourcesManager( 5889): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,D/LgeGpsLocationProvider(  853): NTP server: europe.pool.ntp.org
D/LgeGpsLocationProvider(  853): NTP server returned: 1453396505765 (Thu Jan 21 18:15:05 GMT+01:00 2016) reference: 106527 certainty: 28 system time offset: 67
W/ResourcesManager( 5889): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  853): Process com.android.vending (pid 4966) has died
,I/NotificationManager(  853): android: cancelAsUser(-1597574061) by android
I/LGEmail ( 5906): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5906): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/MultiDex( 5889): VM with version 2.1.0 has multidex support
I/MultiDex( 5889): install
I/MultiDex( 5889): VM has multidex support, MultiDex support library is disabled.
I/MusicStore( 5860): Database version: 120
,I/ActivityManager(  853): Process com.google.process.gapps (pid 4905) has died
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  853): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5953 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  853): Process com.lge.lgdmsclient (pid 5720) has died
,I/art     (  853): Explicit concurrent mark sweep GC freed 77664(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.112ms total 198.634ms
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out(  853): propertyValue:false
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  853): propertyValue:false
,I/GservicesProvider( 5953): Gservices pushing to system: true; secure/global: true
D/UEI.SmartControl( 5660): Internal timer expired: 2
,V/WifiInternetCheck(  853): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5978 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GoogleHttpClient( 5953): GMS http client unavailable, use old client
I/GoogleHttpClient( 5953): GMS http client unavailable, use old client
,V/JNIHelp ( 5889): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5860): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/ALBootInit( 5978): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 5978): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5978): [setNextAlert] start
D/Alarms  ( 5978): [setNextAlert] (1)
D/Alarms  ( 5978):  minTime  = 0
D/Alarms  ( 5978):  -- OK multi -- 0
E/jeny.kim( 5978): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5978): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/jxcore-log( 5490): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5490): 
,W/ActivityThread( 5889): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5889): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13c40aed: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5889): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  853): Process com.lge.settings.easy (pid 5679) has died
,I/NotificationManager( 5889): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5889): com.google.android.gms: cancel(39789) by com.google.android.gms
I/CommonUtil( 5978): BUILD Operator: OPEN
,D/Alarms  ( 5978): broadcastToWidgetProvider : false
D/Alarms  ( 5978): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  853): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 5978): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 5978): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@158bc87b
,V/DigitalAppWidgetProvider( 5978): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@158bc87b
D/QuickCoverProvider( 5978): onReceiver
,I/ActivityManager(  853): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6006 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5860): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
D/NativeLibraryUtils( 5889): Install completed successfully. count=14 extracted=0
W/ContextImpl( 5860): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6006): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Process com.lge.bnr (pid 5781) has died
,D/CalendarApplication( 6006): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6006): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6006): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@154ce9fe, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@397f355f, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@23e6dbac, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@33422075, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@889a80a, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@158bc87b, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@dbc0698, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@14a14ef1, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2e223ad6, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2a047157, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3eb6f444, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@22eae92d, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@36df2e62, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1ef4cbf3, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@355110b0, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3eb9eb29, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2585ceae, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@786344f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1c2e87dc, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1d5d10e5, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@11e427ba, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@161bc66b, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@20a45c8, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@52d661, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@109d0586, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@362e5e47, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2461f674, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2885779d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@bb3f412, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@27e897e3, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@38e205e0, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@146f099, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@17d93f5e, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3982cf3f, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2191a00c, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3f0cfd55, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1275f36a, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3a5f205b, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@37beb0f8, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2ded19d1, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1477dc36, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3e5673
D/GeneralP,referenceUtils( 6006): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6006): [init]
,I/Config  ( 6006): LGCalendar ver.4.40.17
I/Config  ( 6006): start check model
I/Config  ( 6006): start check native_ca
I/Config  ( 6006): Config Operator=OPEN, Country=EU
D/Config  ( 6006): [setDefaultValuesToPref]
D/Config  ( 6006): [parseProfiles]
D/ProfilesParser( 6006): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6006): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6006): [updateProfiletoCountryInfo]
D/GeneralPreference( 6006): [checkAndMigrateOldPreference]
W/ResourcesManager( 5860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/AgendaWidgetManager( 6006): [updateWidgets] 
,I/NotificationManager(  853): android: cancelAsUser(-1816247584) by android
,V/JNIHelp ( 5860): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/ActivityThread( 5889): Failed to find provider info for com.android.contacts.metadata
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityThread( 5860): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5860): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1516a846: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5860): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5860): GMSCore installation verified
D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 36760, reason: UserStart, SyncResult: databaseError: true stats []
I/InitNotificationRingtoneService( 6006): Start InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6006): onHandleIntent
D/MonthWidgetProvider( 6006): [onReceive]
D/CalendarWidgetProvider( 6006): [onReceive]
D/CalendarWidgetProvider( 6006): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6006): readJsonAsset : holiday.json
I/AlertUtils( 6006): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/CalendarTypeController( 6006): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6006): [onReceive]
D/CalendarWidgetProvider( 6006): [onReceive]
D/CalendarWidgetProvider( 6006): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6006): [onUpdateAndInitCalendarTime]
D/SyncManager(  853): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 140751, reason: UserStart
I/NotificationManager(  853): android: cancelAsUser(716319171) by android
D/WeatherAncestor( 2699): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:15:7
D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
,D/Weather_cast( 2699): 2 : set auto-update time : 1/21 21:15
I/ConfigStore( 5860): Config Database version: 1
I/AlertUtils( 6006): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/WeatherAncestor( 2699): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:15:7
D/WeatherService( 2699): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/ActivityManager(  853): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6040 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/Auth.Api.Credentials( 5889): [CredentialSyncAdapter] Unknown sync event.
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2699): 2 : Utils getTopActivity com.lge.launcher2 / true
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,D/WeatherService( 2699): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2699): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/NotificationManager(  853): android: cancelAsUser(-591465577) by android
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6006): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6006): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,E/HolidayIntentService( 6006): onHandleIntent:holiday data empty
I/AlertUtils( 6006): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6006): End InitializeAlertRingtoneService.onHandleIntent
D/TimeService( 6040): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453396507492
D/        ( 6040): TimeServiceNative: User Time to be set is 1453396507492
D/QC-time-services( 6040): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6040): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6040): Lib:time_genoff_operation: pargs->ts_val = 1453396507492
D/QC-time-services( 6040): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  324): Daemon: Connection accepted:time_genoff
D/QC-time-services(  324): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453396507492
D/QC-time-services(  324): Daemon:genoff_opr: Base = 2, val = 1453396507492, operation = 0
D/QC-time-services(  324): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/3/70 21:16:41
D/QC-time-services(  324): Daemon:Value read from RTC seconds = 13295801000
D/QC-time-services(  324): Daemon:new time 1453396507492 
D/QC-time-services(  324): Daemon: delta 1440100706492 genoff 1440100706492 
D/QC-time-services(  324): Daemon:genoff_persistent_update: Writing genoff = 1440100706492 to memory
D/QC-time-services(  324): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  324): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  324): Updating the TOD offset
D/QC-time-services(  324): Daemon:genoff_persistent_update: Writing genoff = 1440100706492 to memory
D/QC-time-services(  324): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  324): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  324): Daemon:Update to modem bit set
D/QC-time-services(  324): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  324): Daemon: Base = 2, Value being sent to MODEM = 1124135906492
E/QC-time-services( 6040): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  324): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  324): Daemon: Time-services: Waiting to acceptconnection
I/art     ( 5889): CheckpointMarkThreadRoots callback created = 0xb042d440
,I/ActivityManager(  853): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6064 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  853): RTC_WAKEUP set : Alarm{358db232 type 0 when 1453396507570 com.android.vending} when 1453396507570
I/NotificationManager(  853): android: cancelAsUser(-1816247584) by android
I/art     ( 5889): CheckpointMarkThreadRoots callback created = 0xb042d430
,I/CheckinService( 5889): Checkin interval check for package: unspecified last checkin: 1453394670206 min interval config: 0 actual interval: 1837481
,I/MediaRouter( 5860): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5860): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NotificationManager(  853): android: cancelAsUser(-1597574061) by android
,I/NetworkMonitor( 5860): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5860): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 5860): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5860): Using platform SSLCertificateSocketFactory
D/ConnectivityService(  853): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  853): dumpNetworkRequest
D/ConnectivityService(  853):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/ConnectivityService(  853):     Requests:
D/ConnectivityService(  853):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853):     Lingered:
D/ConnectivityService(  853): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853): apparently satisfied.  currentScore=60
D/ConnectivityService(  853): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5889): CM callback handler got msg 524290
D/eas_req ( 5906): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/NotificationManager(  853): android: cancelAsUser(-591465577) by android
I/ActivityManager(  853): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6092 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.729ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.535ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 26.739ms
,I/NotificationManager( 5860): com.google.android.music: cancel(1061) by com.google.android.music
,I/jxcore-log( 5490): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5490): 
I/HubEmail( 5906): JNI_OnLoad()
I/HubEmail( 5906): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5906): registerNatives()
I/HubEmail( 5906): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5906): registerNativeMethods()
I/HubEmail( 5906): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 5906): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 5906): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Finsky  ( 6064): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/jxcore-log( 5490): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5490): 
I/jxcore-log( 5490): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5490): 
,I/art     (  853): Explicit concurrent mark sweep GC freed 25979(1209KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.582ms total 169.223ms
,I/art     ( 5953): Explicit concurrent mark sweep GC freed 7880(396KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 472us total 44.538ms
W/DriveInitializer( 5889): Awaiting to be initialized
,W/DriveInitializer( 5889): Background init thread started
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5889): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,D/LGDMClient( 6092): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6092): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6092): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/Finsky  ( 6064): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/ContextImpl( 6092): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/DriveInitializer( 5889): Background init thread ended
D/LGDMClient( 6092): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6092): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/jxcore-log( 5490): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5490): 
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6146 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 6064): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/LGDMClient( 6092): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/jxcore-log( 5490): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5490): 
I/jxcore-log( 5490): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5490): 
,W/Settings( 6064): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/LGDMClient( 6092): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NotificationManager( 6064): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  853): Process com.android.settings (pid 5587) has died
,V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@1275f36a on behalf of 6064
W/ContextImpl( 6092): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6092): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6092): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6092): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6092): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6092): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/Ads     ( 6064): Skipping gmscore version check
,D/Finsky  ( 6064): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6064): [1] Libraries$2.run: Finished loading 1 libraries.
I/NotificationManager( 5889): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/AppUp4:AppBoxCP( 6146): onCreate
,W/AppUp4:DB( 6146):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6146):  setFingerPrint start
,I/AppUp4:DB( 6146):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6146):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6146):  SDK version = 0
I/AppUp4:DB( 6146):  beforefinger == newfinger no write in DB
I/ActivityManager(  853): Process com.lge.qremote (pid 5758) has died
,D/UEI.SmartControl( 5660): Service.onUnbind: IControl
D/UEI.SmartControl( 5660): Service.onDestroy
D/UEI.SmartControl( 5660): Shutdown IRRCPlayer... 
W/irrc_jni( 5660): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5660): ~IrrcClient ++ 
D/irrcClient( 5660): ~IrrcClient -- 
W/irrc_jni( 5660): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5660): Blaster closed
D/UEI.SmartControl( 5660): Blaster closed
D/UEI.SmartControl( 5660): Shut down QS...
D/UEI.SmartControl( 5660): Stopped file observer...
I/UEI.SmartControl( 5660): QS lib stop result = true
D/UEI.SmartControl( 5660): QS shutdown complete
D/AppUp4:AppBoxApplication( 6146): AppBoxApplication onCreate()
D/Finsky  ( 6064): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/NetworkStateForAutoUpdateMonitor( 6146): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6146): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6146): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6146): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6146): onReceive
I/AppUp4:CustModeStarterReceiver( 6146): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/Finsky  ( 6064): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/AppUp4:CustFacade( 6146): Context : android.app.ReceiverRestrictedContext@889a80a
D/AppUp4:CustFacade( 6146): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6146): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6146): begin check event
I/AppUp4:CustModeStarterReceiver( 6146): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6146): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6146): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6146): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6146): handleAsyncCustNotification do not startCustService
I/ActivityManager(  853): Killing 5660:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,D/Finsky  ( 6064): [730] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6064): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_5660/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Killing 5633:com.lge.sync/1000 (adj 15): empty #11
I/NotificationManager(  853): android: cancelAsUser(353845882) by android
I/LgeMiscReceiver( 3115): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3115): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3115): networkInfo.isConnected() = true
,D/PhoneState( 3115): setPdpRejectCasuse : false
I/ActivityManager(  853): Killing 5978:com.lge.clock/u0a10 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6183 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/libprocessgroup(  853): failed to open /acct/uid_10010/pid_5978/cgroup.procs: No such file or directory
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_5633/cgroup.procs: No such file or directory
,I/NotificationManager(  853): android: cancelAsUser(353845882) by android
,D/PhoneMonitor( 6183): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6183): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6183): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  853): Killing 6006:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10013/pid_6006/cgroup.procs: No such file or directory
,V/DownloadManager( 3139): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3139): DownloadService onCreate
I/CheckinService( 5889): Checkin interval check for package: unspecified last checkin: 1453394670206 min interval config: 0 actual interval: 1839393
,I/DownloadManager( 3139): in removeSpuriousFiles
I/NotificationManager( 3139): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3139): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  853): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6213 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
D/PhoneMonitor( 6183): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6183): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6183): [parse] Load xml
I/jxcore-log( 5490): Test app app.js loaded
I/jxcore-log( 5490): 
V/TelephonyAutoProfiling( 6183): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6183): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@1477dc36 on behalf of 3139
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 5490): BLE advertisement is supported
I/jxcore-log( 5490): 
V/DownloadManager( 3139): DownloadService onStartCommand
V/DownloadManager( 3139): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3139): in trimDatabase
V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@19a9e4a4 on behalf of 3139
,V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@2bd8820d on behalf of 3139
I/CheckinService( 5889): Disabling old GoogleServicesFramework version
I/chromium( 5490): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PhoneMonitor( 6183): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3139): DownloadService onDestroy
,I/CheckinService( 5889): Checking schedule, now: 1453396509794 next: 1453394700127
,I/CheckinService( 5889): active receiver: enabled
D/DrmBroadcastReceiver( 6213): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6213): 1  network is available. Sync DRM Time with NTP
I/CheckinService( 5889): Preparing to send checkin request
I/EventLogService( 5889): Accumulating logs since 1453395040327
,D/WeatherAncestor( 2699): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:9
V/DrmService( 6213): Service onCreate
D/DrmService( 6213): Received new request = 2
D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
D/WeatherAncestor( 2699): connectivity changed - connection : true
I/DrmSntpClient( 6213): Start Sync process
D/DrmSntpClient( 6213): Server : 0
D/Weather_cast( 2699): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2699): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:9
D/WeatherService( 2699): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 6213): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6213): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6213): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6213): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  277): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 5889): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5889): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6241 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2699): 2 : Utils getTopActivity com.lge.launcher2 / true
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6213): propertyValue:false
D/WeatherService( 2699): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2699): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/LGDrmClient( 6213): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  287): eDRM_SetDRMTime +++
I/LGDRM   (  287): [DRM] SET TIME : YR=2016, MON=1, DAY=21
I/LGDRM   (  287): [DRM] SET TIME : HR=17, MIN=15, SEC=10
,V/ILGDrmService(  287): eDRM_SetDRMTime ---
I/DrmSntpClient( 6213): Synched
D/DrmService( 6213): Completed !! request = 2
D/DrmService( 6213): Request count = 0
V/DrmService( 6213): Service onDestroy
I/ActivityManager(  853): Process com.google.android.music:main (pid 5860) has died
,W/ResourcesManager( 6241): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 5889): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5889): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 6241): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6241): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6241): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6241): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6241): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6241): MmsConfig.loadFromResources
E/Babel_SMS( 6241): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6241): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 5889): Explicit concurrent mark sweep GC freed 21799(1591KB) AllocSpace objects, 18(288KB) LOS objects, 24% free, 11MB/15MB, paused 778us total 65.572ms
,D/SensorManager( 6241): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6241): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6241): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6241): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6241): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6241): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6241): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6241): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6241): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6241): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6241): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6241): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6241): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6241): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6241): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6241): found sensor: Motion Accel, handle=46
,W/art     ( 6241): Suspending all threads took: 5.930ms
,I/art     ( 6241): CheckpointMarkThreadRoots callback created = 0xb042d8c0
W/Settings( 6241): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6241): startup - clean
I/art     ( 6241): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/Babel   ( 6241): deleted: false for 0
,D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1727): propertyValue:false
,I/ActivityManager(  853): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6275 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6241): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6241): Unsupported mime audio/adpcm
W/AudioCapabilities( 6241): Unsupported mime audio/g726
W/AudioCapabilities( 6241): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6241): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6241): Unsupported mime video/mjpg
W/VideoCapabilities( 6241): Unsupported mime video/theora
,W/AudioCapabilities( 6241): Unsupported mime audio/evrc
,W/AudioCapabilities( 6241): Unsupported mime audio/qcelp
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/VideoCapabilities( 6241): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6241): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6241): Unsupported mime audio/qcelp
W/AudioCapabilities( 6241): Unsupported mime audio/evrc
W/VideoCapabilities( 6241): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6241): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6241): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6241): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6241): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6241): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6241): onServiceConnected
,W/Babel   ( 6241): Attempted to change video mute state without an active call.
I/NotificationManager( 6241): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6241): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6241): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6241): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6241): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6241): propertyValue:false
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6275): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6275): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6275): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6275): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6275):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6275):   adb logcat -s GAv4
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6275): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6275): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6275): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6275): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/NotificationManager(  853): android: cancelAsUser(2) by android
,I/NotificationManager( 1727): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  853): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6320 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6320): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6320): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WebViewFactory( 6275): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/MultiDex( 6320): VM with version 2.1.0 has multidex support
I/MultiDex( 6320): install
I/MultiDex( 6320): VM has multidex support, MultiDex support library is disabled.
,I/LibraryLoader( 6275): Time to load native libraries: 1 ms (timestamps 2250-2251)
,I/LibraryLoader( 6275): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6275): Binding Chromium to main looper Looper (main, tid 1) {998d91f}
I/LibraryLoader( 6275): Expected native library version number "",actual native library version number ""
I/chromium( 6275): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
V/JNIHelp ( 6320): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/BrowserStartupController( 6275): Initializing chromium process, singleProcess=true
W/art     ( 6275): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6275): ApplicationContext is null in ApplicationStatus
W/chromium( 6275): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6275): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6275): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6275): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6275): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6275): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6275): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6275): Remote Branch: 
I/Adreno-EGL( 6275): Local Patches: 
I/Adreno-EGL( 6275): Reconstruct Branch: 
W/ActivityThread( 6320): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6320): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3614062f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6320): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6320): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6320): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/art     ( 6320): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6320): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/NSApplication( 6275): Starting up...
,V/AudioPolicyService(  281): registerClient() client 0xb382bae0, uid 10079
W/AudioManagerAndroid( 6275): Requires BLUETOOTH permission
,I/ActivityManager(  853): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6359 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 6241): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  853): Killing 6040:com.qualcomm.timeservice/1000 (adj 15): empty #11
,D/NativeLibraryUtils( 6320): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  281): Instantiating CDM.
I/WVCdm   (  281): CdmEngine::OpenSession
I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6040/cgroup.procs: No such file or directory
,W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  281): L1 library not specified. Falling Back to L3
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=1836328428
I/ActivityManager(  853): Process com.android.vending (pid 6064) has died
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6383 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6383): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 6320): CheckpointMarkThreadRoots callback created = 0xb04c9e30
,I/art     ( 6320): CheckpointMarkThreadRoots callback created = 0xb04c9e20
,I/ActivityManager(  853): Process com.lge.email (pid 5906) has died
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
I/WVCdm   (  281): CdmEngine::OpenSession
,I/art     (  853): Explicit concurrent mark sweep GC freed 21653(1017KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.517ms total 160.887ms
,I/iu.SyncManager( 5889): SYNC; picasa accounts
,D/NetworkLogImpl( 5889): Loaded NetworkSpeedPredictor
I/iu.Environment( 5889): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5889): num queued entries: 0
I/iu.UploadsManager( 5889): num updated entries: 0
,I/iu.SyncManager( 5889): NEXT; no task
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/WearableService( 1727): callingUid 10006, callindPid: 1727
,D/LocationInitializer( 5889): Restart initialization of location
,D/AuthorizationBluetoothService( 1727): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1727): propertyValue:false
E/MDM     ( 1727): [113] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1727): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  853): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6429 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCM     ( 1727): GCM config loaded
,W/GCoreFlp( 1727): No location to return for getLastLocation()
W/FusedLocationProvider( 1727): location=null
,W/IcingInternalCorpora( 5889): getNumBytesRead when not calculated.
,I/DigitalAppWidgetProvider( 6429): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  853): Killing 5917:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10023/pid_5917/cgroup.procs: No such file or directory
D/WeatherAncestor( 2699): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:15:13
,D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
D/Weather_cast( 2699): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2699): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:15:13
D/WeatherService( 2699): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6461 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  853): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2699): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2699): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2699): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6461): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3af70adc:true
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
E/MDM     ( 1727): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5889): Restart initialization of location
D/AuthorizationBluetoothService( 1727): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1727): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1727): No location to return for getLastLocation()
,W/FusedLocationProvider( 1727): location=null
W/ContextImpl( 3382): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6495 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6461): Create singleton instance
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.797ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.481ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.881ms
,I/AudioManager( 6461): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6495): Quickset Services start...
,I/UEI.SmartControl( 6495): Manufacture = LGE
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 114884016418; DSPS: 3856566; Offset : -2818761712
D/UEI.SmartControl( 6495): File observer start...
E/UEI.SmartControl( 6495): IR Port is disabled: false
D/UEI.SmartControl( 6495): Starting file observer...
D/UEI.SmartControl( 6495): Extracting JNI libs...
D/UEI.SmartControl( 6495): --- this system supports 32-bit or 64-bit only
I/WVCdm   (  281): CdmEngine::CloseSession
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=2405750363
D/UEI.SmartControl( 6495): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6495): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6495): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6495): --- Selecting new region: 2
I/UEI.SmartControl( 6495): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6495): Platform has CIR...
D/UEI.SmartControl( 6495): NO CIR support, need to check package...
I/UEI.SmartControl( 6495): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6495): QS Service created
I/MusicWidget( 2558): mDelayedStopHandler : unbind
,I/ActivityManager(  853): Process com.lge.appbox.client (pid 6146) has died
I/MusicBrowser( 2714): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2714): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2714): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
E/UEI.SmartControl( 6495): QS start get config
D/MusicBrowser( 2714): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2714): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2714): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2714): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  853):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@161bc66bcom.lge.music.MediaPlaybackService$6@20a45c8
,D/MusicBrowser( 2714): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2e223ad6
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2714): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2714): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2714): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2714): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2714): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2714): reset
,D/UEI.SmartControl( 6495): Loading JNI Libs...
V/MediaPlayer[Native]( 2714): setListener
V/MediaPlayer[Native]( 2714): disconnect
V/MediaPlayer[Native]( 2714): destructor
V/AudioFlinger(  281): releasing 18 from 2714 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2714): disconnect
,D/MusicBrowser( 2714): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
D/UEI.SmartControl( 6495):  configuring local db...
I/SmartShareClient( 2714): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2714): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2714): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2714): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2714): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2714): [SmartShareManagerClient] unregisterListener: 5428833
W/SmartShareClient( 2714): [SmartShareManagerClient] unregisterListener invalid listener: 5428833
I/SmartShareClient( 2714): [SmartShareManagerClient] terminate service: 2714/MediaPlaybackService/602332076
E/HomeCloudIF( 2714): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2714): [SmartShareManagerClient] unbindService context:android.app.Application@109d0586
V/CloudHub( 2714): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2714): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2714): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2714): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2714): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2714): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
,D/UEI.SmartControl( 6495):  ---- Has DB8: true
,D/UEI.SmartControl( 6495): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6495): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6495): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6495): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6495): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6495): IrrcClient ++ 
D/irrcClient( 6495): getIrrcService ++ 
D/irrcClient( 6495): getIrrcService -- 
D/irrcClient( 6495): IrrcClient -- 
W/irrc_jni( 6495): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6495): Services init done
I/UEI.SmartControl( 6495): Device manager: loading config....
D/UEI.SmartControl( 6495): Config is loaded...
,D/UEI.SmartControl( 6495):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6495): Notify AllClients services are ready: 0
,I/ActivityManager(  853): Process com.google.android.apps.magazines (pid 6275) has died
,D/UEI.SmartControl( 6495): QS Service init finished
D/UEI.SmartControl( 6495): QS Service version name: 0.1.73
D/UEI.SmartControl( 6495): QS Service version code: 1073
D/UEI.SmartControl( 6495): Service requested: Control
D/UEI.SmartControl( 6495): Internal service binding...
D/UEI.SmartControl( 6495): -----IControl: 11
D/UEI.SmartControl( 6495): Caller: com.lge.qremote
D/UEI.SmartControl( 6495): ------------ IControl registerCallback...
I/UEI.SmartControl( 6495): Registering callback...
,D/UEI.SmartControl( 6495): -----IControl: 19
D/UEI.SmartControl( 6495): Caller: com.lge.qremote
I/UEI.SmartControl( 6495): Registering Services Ready callback...
I/UEI.SmartControl( 6495): Notify client services are ready...
D/UEI.SmartControl( 6495): -----IControl: 8
D/UEI.SmartControl( 6495): Caller: com.lge.qremote
,I/AudioManager( 6461): getMode name:com.lge.qremote
,I/ActivityManager(  853): Killing 6092:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_1000/pid_6092/cgroup.procs: No such file or directory
,I/AudioManager( 6461): getMode name:com.lge.qremote
I/AudioManager( 6461): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  281): CdmEngine::CloseSession
,I/WVCdm   (  281): L3 Terminate.
,I/dex2oat ( 6539): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6539): dex2oat took 87.900ms (threads: 4)
,I/Adreno-EGL( 6320): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6320): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6320): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6320): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6320): Remote Branch: 
I/Adreno-EGL( 6320): Local Patches: 
I/Adreno-EGL( 6320): Reconstruct Branch: 
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/Adreno-EGL( 6320): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6320): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6320): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6320): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6320): Remote Branch: 
I/Adreno-EGL( 6320): Local Patches: 
I/Adreno-EGL( 6320): Reconstruct Branch: 
,I/Adreno-EGL( 6320): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6320): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6320): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6320): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6320): Remote Branch: 
I/Adreno-EGL( 6320): Local Patches: 
I/Adreno-EGL( 6320): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5889): Classify the device as Phone.
,I/art     ( 5953): Explicit concurrent mark sweep GC freed 2731(109KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 998us total 26.685ms
,D/libc-netbsd( 5889): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5889): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5889): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5889): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5889): propertyValue:false
D/libc-netbsd( 5889): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5889): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5889): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5889): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5889): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5889): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 5889): Sending checkin request (9716 bytes)
,I/CheckinRequestBuilder( 5889): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5889): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5889): Classify the device as Phone.
,I/CheckinTask( 5889): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5889): Checking schedule, now: 1453396518870 next: 1453923767864
I/CheckinService( 5889): active receiver: disabled
,D/CheckinService( 5889): Recording last checkin time for package unspecified as 1453396518897
,I/ActivityManager(  853): Killing 6183:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_6183/cgroup.procs: No such file or directory
,I/ActivityManager(  853): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6566 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  853): Killing 6213:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  853): failed to open /acct/uid_10051/pid_6213/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 6566): Register our PhoneStateListener
,V/SetupWizard( 6566): Connected to Gservices successfully
,D/PhoneMonitor( 6566): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6566): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6566): [parse] Load xml
V/TelephonyAutoProfiling( 6566): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6566): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6566): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  853): Killing 6359:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10048/pid_6359/cgroup.procs: No such file or directory
,D/GCM     ( 1727): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 6495): Internal timer expired: 1
,I/[SystemUI]QPairHandler( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1833): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1368): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1871): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1871): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1871): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 6241): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6241): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6241): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  853): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6617 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/administrator(  853): Handling package changes for user 0
,V/JNIHelp ( 6241): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6617): onCreate
,W/AppUp4:DB( 6617):  [AppBoxDatabaseHelper] construct
W/System  ( 6241): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6241): Installed default security provider GmsCore_OpenSSL
I/AppUp4:DB( 6617):  setFingerPrint start
,I/AppUp4:DB( 6617):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6617):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6617):  SDK version = 0
I/AppUp4:DB( 6617):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6617): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6617): onReceive
I/AppUp4:CustModeStarterReceiver( 6617): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6617): Context : android.app.ReceiverRestrictedContext@397f355f
D/AppUp4:CustFacade( 6617): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6617): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6617): begin check event
I/AppUp4:CustModeStarterReceiver( 6617): Event For Nothing, skip.
,I/NotificationService(  853): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  853): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  853): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6638 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Process com.google.android.apps.plus (pid 6383) has died
,D/LCardEmulationManager( 1780): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1780): getDefaultRoute
I/BackupManagerService(  853): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  853): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  853): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@60ef08a
W/ResourcesManager( 6638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6638): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6638): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 6638): Total System Memory = 906309632
,I/GalleryUtils( 6638): Application Heap = 96 MB
I/[LGHome]EVENT( 1871): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/AppConfig( 6638): App Tier : NOT_DEF
,D/SystemHelper( 6638): region [EU], country [EU], operator [OPEN], sub-operator []
,I/GCoreNlp( 1727): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  853): Explicit concurrent mark sweep GC freed 27520(1398KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.701ms total 178.768ms
,I/ActivityManager(  853): Process com.lge.clock (pid 6429) has died
,I/ActivityManager(  853): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6663 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/LocationProviderProxy(  853): applying state to connected service
,W/ResourcesManager( 6663): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6663): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6663): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6663): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6663): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6663): BUILD Country: EU
,I/SystemConfig( 6663): BUILD Operator: OPEN
I/ActivityManager(  853): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6685 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6663): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6663): existFile = false
I/SystemConfig( 6663): canReadFile = false
I/SystemConfig( 6663): systemFeature RCS result false
,D/SystemConfig( 6663): refreshRcsSupport() :false
,I/LockScreenSettings( 6685): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6685): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6685): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6685): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6685): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6685): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  853): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6702 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  853): Killing 2714:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  281): 2714 died, releasing its sessions
V/AudioFlinger(  281):  pid 1745 @ 0
V/AudioFlinger(  281):  pid 3115 @ 1
V/AudioFlinger(  281):  pid 3115 @ 2
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  853): failed to open /acct/uid_10028/pid_2714/cgroup.procs: No such file or directory
W/ResourcesManager( 6702): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1929): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  853): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6743 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1929): UpdateCorporaTask done [took 87 ms] updated apps [took 86 ms] 
,I/ActivityManager(  853): Killing 6566:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  853): failed to open /acct/uid_10038/pid_6566/cgroup.procs: No such file or directory
,D/Finsky  ( 6743): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6743): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6743): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6743): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6743): com.android.vending: cancel(-1050172287) by com.android.vending
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/DownloadManager( 3139): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Ads     ( 6743): Skipping gmscore version check
D/Finsky  ( 6743): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6743): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3139): created cursor android.database.sqlite.SQLiteCursor@341f3fd3 on behalf of 6743
I/ActivityManager(  853): Killing 6320:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  853): failed to open /acct/uid_10006/pid_6320/cgroup.procs: No such file or directory
W/ActivityManager(  853): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
D/Finsky  ( 6743): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6743): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 5889): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5889): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5889): Storage manager: low false usage 1.73MB avail 2.36GB capacity 4.06GB
,I/Icing   ( 5889): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 5889): Internal init done: storage state 0
,I/Icing   ( 5889): Post-init done
,I/Icing   ( 5889): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 5889): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5889): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5889): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  853): Killing 6495:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6461): android.os.DeadObjectException
,W/System.err( 6461): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6461): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6461): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6461): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6461): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6461): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6461): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6461): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6461): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6461): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6461): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6461): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6461): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6461): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6461): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6461): android.os.DeadObjectException
W/System.err( 6461): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6461): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6461): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6461): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6461): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6461): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6461): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6461): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6461): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6461): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6461): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6461): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6461): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6461): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6461): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  853): failed to open /acct/uid_10089/pid_6495/cgroup.procs: No such file or directory
W/ActivityManager(  853): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  853): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6819 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6819): Quickset Services start...
,I/UEI.SmartControl( 6819): Manufacture = LGE
D/UEI.SmartControl( 6819): File observer start...
E/UEI.SmartControl( 6819): IR Port is disabled: false
D/UEI.SmartControl( 6819): Starting file observer...
D/UEI.SmartControl( 6819): Extracting JNI libs...
D/UEI.SmartControl( 6819): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6819): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6819): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6819): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UEI.SmartControl( 6819): --- Selecting new region: 2
I/UEI.SmartControl( 6819): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6819): Platform has CIR...
,D/UEI.SmartControl( 6819): NO CIR support, need to check package...
I/UEI.SmartControl( 6819): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6819): QS Service created
E/UEI.SmartControl( 6819): QS start get config
,D/UEI.SmartControl( 6819): Loading JNI Libs...
,D/UEI.SmartControl( 6819):  configuring local db...
D/UEI.SmartControl( 6819):  ---- Has DB8: true
,D/UEI.SmartControl( 6819): QS start statue = true Error code = 0
D/UEI.SmartControl( 6819): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6819): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6819): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6819): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6819): IrrcClient ++ 
D/irrcClient( 6819): getIrrcService ++ 
D/irrcClient( 6819): getIrrcService -- 
D/irrcClient( 6819): IrrcClient -- 
W/irrc_jni( 6819): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6819): Services init done
,I/UEI.SmartControl( 6819): Device manager: loading config....
D/UEI.SmartControl( 6819): QS Service init finished
D/UEI.SmartControl( 6819): QS Service version name: 0.1.73
D/UEI.SmartControl( 6819): QS Service version code: 1073
D/UEI.SmartControl( 6819): Service requested: Control
D/UEI.SmartControl( 6819): Config is loaded...
D/UEI.SmartControl( 6819):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6819): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6819): Request IControl service: devices are loaded...
,I/ActivityManager(  853): Killing 6461:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6819): Internal service binding...
W/libprocessgroup(  853): failed to open /acct/uid_10106/pid_6461/cgroup.procs: No such file or directory
,D/charger_monitor(  487): init target 500000
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
D/WifiController(  853): battery changed pluggedType: 2
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1969): Disconnected process message: 10, size: 0
D/charger_monitor(  487): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{2722b2a7 type 2 when 130305 com.google.android.gms} when 130305
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1727): Vacuum at: now=1453396529676 tag=VacuumService
W/InstanceID/Rpc( 5889): Found 10006
,I/CheckinService( 5889): Done disabling old GoogleServicesFramework version
,I/PhenotypeConfigurator( 1727): Scheduling Phenotype for one-off execution 7940 seconds from now (1453396530025)
,D/GetConfigurationSnapshotOperation( 1727): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1727): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1727): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 1727): propertyValue:false
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 6819): Internal timer expired: 1
,D/UEI.SmartControl( 6819): Service.onUnbind: IControl
D/UEI.SmartControl( 6819): Service.onDestroy
W/System.err( 6819): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@14a14ef1
W/System.err( 6819): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6819): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6819): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6819): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6819): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6819): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6819): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6819): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6819): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6819): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6819): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6819): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6819): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6819): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6819): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6819): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@14a14ef1
D/UEI.SmartControl( 6819): Shutdown IRRCPlayer... 
W/irrc_jni( 6819): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6819): ~IrrcClient ++ 
D/irrcClient( 6819): ~IrrcClient -- 
W/irrc_jni( 6819): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6819): Blaster closed
D/UEI.SmartControl( 6819): Blaster closed
D/UEI.SmartControl( 6819): Shut down QS...
D/UEI.SmartControl( 6819): Stopped file observer...
I/UEI.SmartControl( 6819): QS lib stop result = true
D/UEI.SmartControl( 6819): QS shutdown complete
D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 134884921880; DSPS: 4511955; Offset : -2818741103
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{12435e8f type 2 when 136264 android} when 136264
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28598 ms ago)
,D/qdlights(  853): set_light_backlight: 253
,D/qdlights(  853): set_light_backlight: 250
D/qdlights(  853): set_light_backlight: 246
,D/qdlights(  853): set_light_backlight: 243
,D/qdlights(  853): set_light_backlight: 240
,D/qdlights(  853): set_light_backlight: 236
,D/qdlights(  853): set_light_backlight: 233
,D/qdlights(  853): set_light_backlight: 230
,D/qdlights(  853): set_light_backlight: 226
,D/qdlights(  853): set_light_backlight: 223
,D/qdlights(  853): set_light_backlight: 220
,D/qdlights(  853): set_light_backlight: 216
,D/qdlights(  853): set_light_backlight: 213
,D/qdlights(  853): set_light_backlight: 210
,D/qdlights(  853): set_light_backlight: 206
,D/qdlights(  853): set_light_backlight: 203
,D/qdlights(  853): set_light_backlight: 200
,D/qdlights(  853): set_light_backlight: 196
,D/qdlights(  853): set_light_backlight: 193
,D/qdlights(  853): set_light_backlight: 190
,D/qdlights(  853): set_light_backlight: 186
,D/qdlights(  853): set_light_backlight: 183
,D/qdlights(  853): set_light_backlight: 180
,D/qdlights(  853): set_light_backlight: 176
,D/qdlights(  853): set_light_backlight: 173
,D/qdlights(  853): set_light_backlight: 170
,D/qdlights(  853): set_light_backlight: 166
,D/qdlights(  853): set_light_backlight: 163
,D/qdlights(  853): set_light_backlight: 160
,D/qdlights(  853): set_light_backlight: 156
,D/qdlights(  853): set_light_backlight: 153
,D/qdlights(  853): set_light_backlight: 150
,D/qdlights(  853): set_light_backlight: 146
,D/qdlights(  853): set_light_backlight: 143
,D/qdlights(  853): set_light_backlight: 140
,D/qdlights(  853): set_light_backlight: 136
,D/qdlights(  853): set_light_backlight: 133
,D/qdlights(  853): set_light_backlight: 130
,D/qdlights(  853): set_light_backlight: 126
,D/qdlights(  853): set_light_backlight: 123
,D/qdlights(  853): set_light_backlight: 120
,D/qdlights(  853): set_light_backlight: 116
,D/qdlights(  853): set_light_backlight: 113
,D/qdlights(  853): set_light_backlight: 110
,D/qdlights(  853): set_light_backlight: 106
,D/qdlights(  853): set_light_backlight: 103
,D/qdlights(  853): set_light_backlight: 100
,D/qdlights(  853): set_light_backlight: 96
,D/qdlights(  853): set_light_backlight: 93
,D/qdlights(  853): set_light_backlight: 90
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  853): set_light_backlight: 86
,D/qdlights(  853): set_light_backlight: 83
,D/qdlights(  853): set_light_backlight: 80
,D/qdlights(  853): set_light_backlight: 76
,D/qdlights(  853): set_light_backlight: 73
,D/qdlights(  853): set_light_backlight: 70
,D/qdlights(  853): set_light_backlight: 66
,D/qdlights(  853): set_light_backlight: 63
,D/qdlights(  853): set_light_backlight: 60
,D/qdlights(  853): set_light_backlight: 56
,D/qdlights(  853): set_light_backlight: 53
,D/qdlights(  853): set_light_backlight: 50
,D/qdlights(  853): set_light_backlight: 46
,D/qdlights(  853): set_light_backlight: 43
,D/qdlights(  853): set_light_backlight: 40
,D/qdlights(  853): set_light_backlight: 36
,D/qdlights(  853): set_light_backlight: 33
,D/qdlights(  853): set_light_backlight: 30
,D/qdlights(  853): set_light_backlight: 26
,D/qdlights(  853): set_light_backlight: 23
,D/qdlights(  853): set_light_backlight: 20
,D/qdlights(  853): set_light_backlight: 16
,D/qdlights(  853): set_light_backlight: 13
,D/qdlights(  853): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 154885578278; DSPS: 5167337; Offset : -2818756248
,I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35592 ms ago)
,I/PowerManagerService(  853): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  853): ALS enabled for SRE
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35607 ms ago)
,W/ContextImpl(  853): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  853): Sleeping (uid 1000)...
D/LPWGController(  853): [updateScreenState] screen on = false
,D/LPWGController(  853): disable proximity sensor
D/LPWGController(  853): enable proximity sensor
I/SensorManager(  853): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3f19051c] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  853): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  853): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  853): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  853): activate: handle is 48, enable
V/sensors_hal_Ctx(  853): activate sensors is 1400000000000
D/sensors_hal_Thresh(  853): enable: handle=48
I/sensors_hal_SAM(  853): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  853): waitForResponse: timeout=1000
V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  853): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,D/sensors_hal_Thresh(  853): enable: Received response: 0
D/PowerManagerServiceEx(  853): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35651 ms ago)
I/Adreno-EGL(  853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  853): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  853): Build Date: 03/02/15 Mon
I/Adreno-EGL(  853): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  853): Remote Branch: 
I/Adreno-EGL(  853): Local Patches: 
I/Adreno-EGL(  853): Reconstruct Branch: 
,D/PermissionCache(  243): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (209 us)
,I/Sensors (  423): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  853): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  853): processInd: handle 48, count=1
V/sensors_hal_Thresh(  853): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  853): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  853): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  853): poll: count: 256
I/sensors_hal_Ctx(  853): poll: released wakelock sensor_ind
D/sensors_hal_Util(  853): waitForResponse: timeout=0
D/LPWGController(  853): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  853): current mode = 1  value = 1 1
I/LPWGController(  853): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  853): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  853): set_light_backlight: 0
,I/SensorManager(  853): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  853): activate: handle is 46, disable
V/sensors_hal_Ctx(  853): activate sensors is 1000000000000
D/sensors_hal_LP2(  853): enable: handle=46
D/sensors_hal_LP2(  853): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  853): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  243): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  243): hwc_blank: Blanking display: 0
I/DisplayManagerService(  853): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  853): Display changed displayId=0
,V/sensors_hal_SAM(  853): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  853): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1745): Display #0 changed.
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdhwcomposer(  243): hwc_blank: Done blanking display: 0
D/SurfaceControl(  853): Excessive delay in setPowerMode(): 178ms
I/qdhwcomposer(  243): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  853): Got set_interactive hint
,D/KeyguardViewMediator( 1368): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1368): notifyScreenOffLocked
D/KeyguardViewMediator( 1368): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1368): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1368): unregisterProximitySensor
D/StatusBarWindowView( 1368): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  853): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 853
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
I/WifiServerServiceExt(  853): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
,D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1833): |CORE| sendScreenState: state:true
I/LEDService( 1798): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1798): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1798): stopPatternFlashing()
D/Cliptray Service( 1798): lockStatus = 0
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1780): action : android.intent.action.SCREEN_ON
I/LEDService( 1798): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): updateLightsLocked : turn off led
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1798): RESTART MSG
,D/Ulp_jni (  853): JNI:system_update. Event-0
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
D/SplitWindow(  853): check instance of lgWin Window{222154ab u0 SearchPanel}
,D/InputDispatcher(  853): Window went away: Window{2ae81cd8 u0 SearchPanel}
,I/[SystemUI]Clock( 1368): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1368): time changed, timezoneChanged : false
,I/Sensors (  423): sns_pwr.c(301):releasing wakelock
,V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2699): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:15:56
D/WeatherService( 2699): 2 : ACTION screen on
,D/WeatherService( 2699): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2699): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2699): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:15:56
D/AppCleanupService( 3843): android.intent.action.SCREEN_ON
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_ON
V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 853
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  853): CMD_SCREEN_OFF 
D/WifiController(  853): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  853): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1833): |CORE| sendScreenState: state:false
,I/LEDService( 1798): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1798): stopPatternFlashing()
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1798): clear
I/LEDService( 1798): updateLightsLocked : turn on led
I/Cliptray Service( 1798): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1798): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
D/LNfcService( 1780): action : android.intent.action.SCREEN_OFF
E/LEDService( 1798): Can't handle this request of patternId:0
D/LEDHandler( 1798): RESTART MSG
D/NfcServiceNXP( 1780): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1871): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2699): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:15:56
,D/WeatherService( 2699): 2 : ACTION screen off
D/WeatherService( 2699): 2 : TimeTick Receiver Unregister
D/WeatherService( 2699): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:15:56
D/AppCleanupService( 3843): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3843): AppUsageStatsSaveTask
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): ACTION_SCREEN_OFF
,E/NxpNfcJni( 1780): getReconnectState = 0x0
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
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
,I/[SystemUI]Clock( 1368): called onTimeUpdated()
I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=555648605, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
,D/KeyguardViewMediator( 1368): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{173f5708 type 2 when 161507 com.android.systemui} when 161507
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1745): getCallState : 0
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1368): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1368): doKeyguard: not showing because lockscreen is off
D/PowerManagerServiceEx(  853): releaseWakeLockInternal: lock=555648605 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{aacaea1 type 2 when 166269 android} when 166269
,I/art     (  853): Explicit concurrent mark sweep GC freed 48328(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 4.309ms total 275.135ms
,E/ActivityThread( 5889): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  853): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 140751, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  853): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 231968, reason: UserStart
I/NotificationManager(  853): android: cancelAsUser(716319171) by android
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 174886430458; DSPS: 5822725; Offset : -2818758925
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1969): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{82e7b52 type 2 when 187552 com.google.android.gms} when 187552
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{18c9ae23 type 2 when 189096 android} when 189096
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 194887162169; DSPS: 6478109; Offset : -2818759402
,V/AlarmManager(  853): ELAPSED_WAKEUP set : Alarm{12ffff20 type 2 when 196296 android} when 196296
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1727): disconnect managed GoogleApiClient
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 214887836328; DSPS: 7133491; Offset : -2818756525
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 234888616321; DSPS: 7788876; Offset : -2818739550
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1969): Disconnected process message: 10, size: 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 254889280688; DSPS: 8444258; Offset : -2818748522
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 274889948909; DSPS: 9099640; Offset : -2818749787
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1969): Disconnected process message: 10, size: 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 294890898590; DSPS: 9755031; Offset : -2818748000
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1969): Disconnected process message: 10, size: 0
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1969): Disconnected process message: 10, size: 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 314891673947; DSPS: 10410417; Offset : -2818764121
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 334892412793; DSPS: 11065800; Offset : -2818727439
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1833): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1833): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1969): Disconnected process message: 10, size: 0
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  853): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5490): TAP version 13
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # multiplex can send data
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 1 String should be length:200
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # enqueue and run in order
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/LocationManagerService(  853): remove 3566c4
,D/LocationManagerService(  853): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  853): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  853): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  853): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  853): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
I/jxcore-log( 5490): ok 2 firstPromise setTimeout expected 0 and got 0
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 3 firstPromise result expected 10 and got 10
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 4 firstPromise testValue expected 10 and got 10
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 5 secondPromise setTimeout expected 10 and got 10
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 6 secondPromise result expected 100 and got 100
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 7 secondPromise testValue expected 100 and got 100
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 8 thirdPromise in promise expected 100 and got 100
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 9 thirdPromise result expected 1000 and got 1000
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 10 thirdPromise result expected 1000 and got 1000
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # basic
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 11 sane
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # another
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 12 sane
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 13 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 14 null
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 15 (unnamed assert)
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 16 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 17 should not throw
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5490): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 18 (unnamed assert)
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 19 (unnamed assert)
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 20 should not throw
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 21 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 22 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 23 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # failed to get mobile documents path
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 24 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 25 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 26 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 27 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #init should register the networkChanged event
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 28 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #startBroadcasting should throw on null device name
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 29 should throw
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 30 should throw
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 31 should throw
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 32 should throw
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # #startBroadcasting should throw on negative port
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 33 should throw
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # #startBroadcasting should throw on too large port
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 34 should throw
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 35 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 36 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 37 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 38 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 39 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 40 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 41 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 42 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 43 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 44 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 45 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 46 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 47 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 48 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 49 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 50 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 51 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 52 should be equal
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 53 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749158.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749158.5490","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1969): [BTUI] createSocketChannel FD=87 mFd=85
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749158.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749158.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749158.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749158.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749158.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749158.5490
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@1771facc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@1771facc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
I/jxcore-log( 5490): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/LGWifiP2pService(  853): add a new client
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5490): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
D/LGWifiP2pService(  853): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/LGWifiP2pService(  853): InactiveState{ when=-11ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  853): P2pEnabledState{ when=-11ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749284.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/wpa_supplicant( 5577): p2p0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  853): remove client information from framework
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
D/LGWifiP2pService(  853): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
D/LGWifiP2pService(  853): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1798): Event [CTRL-EVENT-SCAN-STARTED ]
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749284.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749284.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749284.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749284.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749284.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749284.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7bc7254c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7bc7254c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749284.5490
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
D/LGWifiP2pService(  853): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler },
,D/LGWifiP2pService(  853): discovery change broadcast false
I/jxcore-log( 5490): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5490): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749370.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749370.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749370.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749370.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749370.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749370.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749370.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a52088d4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a52088d4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749370.5490
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
D/LGWifiP2pService(  853): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/jxcore-log( 5490): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopLi,steningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  853): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/jxcore-log( 5490): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749421.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749421.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749421.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749421.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749421.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749421.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749421.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3edb939a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3edb939a target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749421.5490
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5490): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
I/bt-btif ( 1969): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/bt-btif ( 1969): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  853): discovery change broadcast true
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.andro,id.bluetooth.btservice.AdapterProperties@786344f
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothLeScanner( 5490): could not find callback wrapper
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 5490): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749465.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  853): remove client information from framework
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749465.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749465.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749465.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749465.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749465.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749465.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9c887f8a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9c887f8a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749465.5490
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
D/LGWifiP2pService(  853): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
I/jxcore-log( 5490): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING,
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...,
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/jxcore-log( 5490): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749513.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749513.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749513.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749513.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749513.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749513.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749513.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9c3eae96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9c3eae96 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749513.5490
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.bt,connectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  853): discovery change broadcast true
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 5490): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
D/LGWifiP2pService(  853): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
,I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/jxcore-log( 5490): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749551.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749551.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749551.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749551.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749551.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749551.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749551.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c5e1e312 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c5e1e312 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749551.5490
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  853): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
I/jxcore-log( 5490): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5490): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
I/bt-btif ( 1969): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
I/bt-btif ( 1969): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcas,tReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/jxcore-log( 5490): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749585.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749585.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749585.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749585.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749585.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749585.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749585.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@14cfdd44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@14cfdd44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749585.5490
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/LGWifiP2pService(  853): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  853): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
I/jxcore-log( 5490): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
I/bt-btif ( 1969): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.inter,nal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5490): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749632.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749632.5490","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749632.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749632.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749632.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749632.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749632.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8bd9c312 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8bd9c312 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749632.5490
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  853): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5490): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
D/LGWifiP2pService(  853): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): remove client information from framework
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/jxcore-log( 5490): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749664.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749664.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749664.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396749664.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396749664.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396749664.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396749664.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c96f2ac8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c96f2ac8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396749664.5490
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
,D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  853): discovery change broadcast true
I/jxcore-log( 5490): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
I/bt-btif ( 1969): BTA_JvDeleteRecord
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/bt-btif ( 1969): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
,D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  853): remove client information from framework
,D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/jxcore-log( 5490): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 4
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396750295.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396750295.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396750295.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Waiting for incoming connections...
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396750295.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396750295.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396750295.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396750295.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5b2592d8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5b2592d8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396750295.5490
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
I/jxcore-log( 5490): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
D/LGWifiP2pService(  853): discovery change broadcast true
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
I/wpa_supplicant( 5577): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1798): Event [CTRL-EVENT-SCAN-STARTED ]
I/jxcore-log( 5490): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 5490): 
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
,I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
I/jxcore-log( 5490): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
D/LGWifiP2pService(  853): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396750739.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396750739.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396750739.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396750739.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396750739.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396750739.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396750739.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@eb4c7092 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@eb4c7092 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  853): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396750739.5490
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
,D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
I/jxcore-log( 5490): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
I/io.jxcore.node.ConnectionHelper( 5490): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 5490): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 5490): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 5490): ok 78 Should not connect to a bad peer
I/jxcore-log( 5490): 
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
,I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5490): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396751176.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396751176.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5490): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1969): BTA_JvCreateRecordByUser
I/bt-btif ( 1969): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): start: OK
I/io.jxcore.node.ConnectionHelper( 5490): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396751176.5490
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): createAdvertiseData: From: 1453396751176.5490 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5490): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5490): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5490): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5490): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1453396751176.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): start: {"pi":"F8:95:C7:87:85:54","pn":"1453396751176.5490","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1453396751176.5490","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@39de611a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@39de611a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState add service
,D/LGWifiP2pService(  853): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): start: Starting P2P device discovery...
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1798): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  853): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: Peer ID: F8:95:C7:87:85:54, peer name: 1453396751176.5490
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5490): start: OK
I/jxcore-log( 5490): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 5490): 
D/io.jxcore.node.ConnectionHelper( 5490): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 5490): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 5490): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 5490): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5577): P2P-FIND-STOPPED 
I/jxcore-log( 5490): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 5490): 
D/WfdsMonitor( 1798): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 5490): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
D/LGWifiP2pService(  853): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: RESTARTING
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stop: Stopping peer discovery...
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothLeScanner( 5490): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5490): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5490): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5490): onServerStopped
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service
,D/LGWifiP2pService(  853): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5490): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5490): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService(  853): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5490): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5490): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5490): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5490): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5490): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 4
,I/jxcore-log( 5490): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 83 should be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 84 should not be equal
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # setup
I/jxcore-log( 5490): 
I/jxcore-log( 5490): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): # teardown
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): ok 85 irrelevant messages should be ignored
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 86 relevant messages should not be ignored
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ok 87 messages from this device should be ignored
I/jxcore-log( 5490): 
,I/jxcore-log( 5490): Tests Complete
I/jxcore-log( 5490): 
I/chromium( 5490): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 5490): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 5490): 
I/jxcore-log( 5490): Toggling radios to false
I/jxcore-log( 5490): 
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  853): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1cb05ecc mBinding = false
I/chromium( 5490): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/LocationManagerService(  853): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  853): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  853): JNI:system_update. Event-4
D/BluetoothManagerService(  853): Message: 2
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
,D/BluetoothManagerService(  853): Sending off request.
D/WifiServiceImplEx(  853): setWifiEnabled: false pid=5490, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  853): setWifiEnabled: false pid=5490, uid=10316
D/BluetoothAdapterService(346115825)( 1969): disable() called...
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterState( 1969): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1969): Setting state to 13
I/BluetoothAdapterState( 1969): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(346115825)( 1969): updateAdapterState() - Broadcasting state to 1 receivers.
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
,D/BluetoothManagerService(  853): Message: 60
D/BluetoothManagerService(  853): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  853): Bluetooth State Change Intent: 12 -> 13
D/LGBluetoothAPIService( 1798): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterProperties( 1969): onBluetoothDisable()
,I/BluetoothAdapterState( 1969): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1969): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/LocationManagerService(  853): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  853): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni (  853): JNI:system_update. Event-4
I/BluetoothMapService( 1969): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1969): STATE_TURNING_OFF
V/BluetoothMapService( 1969): Handler(): got msg=4
D/BluetoothMapService( 1969): MAP Service closeService in
D/BluetoothMapMasInstance( 1969): MAP Service shutdown
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1368): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,V/BluetoothMapMasInstance( 1969): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 1969): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 1969): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 1969): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 1969): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 1969): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 1969): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 1969): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 1969): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1969): MAP Service closeService out
,E/WifiStateMachine(  853): WifiStateMachine: Leaving Connected state
,I/jxcore-log( 5490): Radios toggled
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ****TEST TOOK:  ms ****
I/jxcore-log( 5490): 
I/jxcore-log( 5490): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5490): 
E/WifiConfigStore(  853): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  853): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/DhcpStateMachine(  853): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1727): Read error: ssl=0xaaedda00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1727): SSL shutdown failed: ssl=0xaaedda00: I/O error during system call, Broken pipe
I/ActivityManager(  853): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7039 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/PowerManagerServiceEx(  853): acquireWakeLockInternal: lock=555648605, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=853
I/jxcore-log( 5490): Toggling radios to false
I/jxcore-log( 5490): 
D/BluetoothAdapterProperties( 1969): Scan Mode:20
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
D/BluetoothAdapterState( 1969): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1969): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 1969): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 1969): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 1969): BTA_JvDeleteRecord
I/bt-btif ( 1969): BTA_JvRfcommStopServer
W/bt-btif ( 1969): invalid rfc slot id: 2
D/IOP_DB_BT( 1969): db_close: nbr users 0
D/IOP_DB_BT( 1969): db_close: free database
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/btif_config_util( 1969): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 1969): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 1969): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 1969): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:G3s-1
D/btif_config_util( 1969): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1969): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1969): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1969): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1969): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/ConnectivityService(  853): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1969): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 1969): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1969): enum_config(L344): out, value:x
D/btif_config_util( 1969): enum_config(L300,): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 1969): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1969): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 1969): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1969): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 1969): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
,D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1969): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 1969): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1969): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 1969): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1969): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1969): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
,D/btif_config_util( 1969): enum_config(L344): out, value:
,D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:�
D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_,util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:$
D/btif_config_util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
,D/btif_config_util( 1969): enum_config(L344): out, value:�
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:A5-1
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z,
,D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
,D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
,D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:#
D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:�
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
,D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:XT1072
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
,D/btif_config_util( 1969): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:a
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
,D/btif_config_util( 1969): enum_config(L344): out, value:S5-1
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
,D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L344): out, value:
,D/btif_config_util( 1969): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1969): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1969): enum_config(L344): out, value:
,D/btif_config_util( 1969): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:	a
D/btif_config_util( 1969): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
,D/btif_config_util( 1969): enum_config(L344): out, value:G4-1
D/btif_config_util( 1969): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
D/btif_config_util( 1969): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
E/bt-btif ( 1969): btif_hf_upstreams_evt: wrong handle = 24937 
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:�
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
,D/btif_config_util( 1969): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
,D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:A
,D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 ,
,D/btif_config_util( 1969): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 1969): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:���
D/btif_config_util( 1969): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
,D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1969): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
,D/btif_config_util( 1969): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 1969): enum_config(L344): out, value:#
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 1969): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
,D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L344): out, value:�
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 1969): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
,D/btif_config_util( 1969): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:Z
D/btif_config_util( 1969): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 1969): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
,D/btif_config_util( 1969): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 1969): enum_config(L344): out, value:
,D/btif_config_util( 1969): enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 1969): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1969): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
,D/btif_config_util( 1969): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 1969): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 1969): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 1969): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 1969): enum_config(L344): out, value:
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:���
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1969): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevClass
,D/btif_config_util( 1969): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 1969): enum_config(L344): out, value:�_
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 1969): enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
D/btif_config_util( 1969): enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 1969): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 1969): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
,D/btif_config_util( 1969): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 1969): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 1969): enum_config(L344): out, value:4g�������v��
D/btif_config_util( 1969): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 1969): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
,D/btif_config_util( 1969): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
D/btif_config_util( 1969): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/bt-obex ( 1969): Ignore event 10 in state 1
,I/bt-btif ( 1969): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1969): ops_state_cb(L223):  ops_state_cb state:3
W/bt-obex ( 1969): Ignore event 10 in state 1
E/bt-btif ( 1969): bta_gattc_deregister Deregister Failedm unknown client cif
D/OppService( 1969): onOpsStateChange() :3
D/OppService( 1969): Recieved MESSAGE_OPS_DISABLE
,D/WifiHS20(  853): hidePasspointNotification off =false
V/BluetoothPbapService( 1969): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  853): hidePasspointNotification off =false
W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  853): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  853): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  853): NetworkAgent: NetworkAgent channel lost
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:19:12.729 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:19:12.73 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/BluetoothManagerService(  853): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  853): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1cb05ecc mBinding = false
D/BluetoothManagerService(  853): Message: 2
,D/BluetoothManagerService(  853): Sending off request.
D/LGWifiP2pService(  853): P2pDisablingState
D/LGWifiP2pService(  853): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): p2p socket connection lost
D/BluetoothAdapterService(346115825)( 1969): disable() called...
,D/LGWifiP2pService(  853): P2pDisabledState
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothAdapterService( 1969): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService(  853): IBluetooth.disable() returned false
,I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0,
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/WifiScanningService(  853): SCAN_AVAILABLE : 1
,D/WifiScanningService(  853): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiServiceImplEx(  853): setWifiEnabled: false pid=5490, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  853): setWifiEnabled: false pid=5490, uid=10316
D/RttService(  853): SCAN_AVAILABLE : 1
D/RttService(  853): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1798): WifiP2pState is changed : false
D/ConnectivityService(  853): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/WfdsService( 1798): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1798): doCommand: P2P_STOP_FIND
I/jxcore-log( 5490): Radios toggled
I/jxcore-log( 5490): 
D/WfdsService( 1798): Set the WFDS Monitor: false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=-1ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Forcing reevaluation
D/WfdsMonitor( 1798): WFDS Monitor is stopped
D/WfdsService( 1798): STATE : WfdsDisabledState - enter
D/WfdsService( 1798): WFDS: Scanner is paused
D/WfdsDiscoveryStore( 1798): Clear Discovery Method Map: ScanAlwaysMode false
D/CtrlSupplicant( 1798): Received on exit socket, terminate
E/CtrlSupplicant( 1798): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1798): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1798): WfdsMonitorThread is received the interrupt - closing
,D/LGWifiP2pService(  853): P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  853): DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/WifiServiceExtension( 1798): isInternetCheckAvailable return false
W/WfdsSession:Controller( 1798): DefaultState - msg [9441355] is not handled
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/DhcpStateMachine(  853): StoppedState
,D/DhcpStateMachine(  853): StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  853): Process com.google.android.talk (pid 6241) has died
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/ConnectivityService(  853): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  853): disableDataServiceNotify
D/DSQN    (  853): stop dsqn bin
,I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  853): hidePasspointNotification off =false
,W/Settings(  853): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  853): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  853): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:19:12.846 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:19:12.853 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/WifiServerServiceExt(  853): WIFI_STATE_CHANGED_ACTION [0]
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/ConnectivityService(  853): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  853): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiServerServiceExt(  853): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  853): setSupplicantStateDISCONNECTED
D/ConnectivityService(  853):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524292
D/Nat464Xlat(  853): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 5889): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  853): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  853): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  853): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  853): Disconnected - quitting
V/NetworkPolicy(  853): [LG_RESTRICTED] !!!isConnected  type  :1
,D/Tethering(  853): MasterInitialState.processMessage what=3
D/ConnectivityService(  853): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1833): |CORE| No family connected
D/ConnectivityService(  853): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  853): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  853):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  853): Removing idletimer
D/TelephonyNetworkFactory-1( 1745): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings(  853): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  853): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy(  853): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1833): |CORE| No family connected
I/QCNEJ   ( 1833): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  853): MasterInitialState.processMessage what=3
,I/QCNEJ   ( 1833): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 4
,I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 5
I/wpa_supplicant( 5577): p2p0: CTRL-EVENT-TERMINATING 
I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 5577): monitor socket send errors count : 1
I/wpa_supplicant( 5577): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1798-2\x00 that cannot receive messages
I/Netd    (  277): M: Get netlink event, ifname: p2p0 action: 7
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/wpa_supplicant( 5577): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,W/wpa_supplicant( 5577): USIM:  scard_deinit function
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  853): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  853): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 5
D/Tethering(  853): InitialState.processMessage what=4
I/wpa_supplicant( 5577): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  853): sendTetherStateChangedBroadcast 0, 0, 0
,D/WfdsService( 1798): Supplicant Connection state is changed : false
D/WifiOffDelayIfNotUsed(  853): stopMonitoring
D/WfdsService( 1798): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1798): Set the WFDS Monitor: false
D/WfdsMonitor( 1798): WFDS Monitor is stopped
I/QCNEJ   ( 1833): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1833): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 18:19:13.139 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1833): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  853): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  853): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  853): batteryPsActivateMsgHandler : this is not treated
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/Settings( 1727): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourcesManager( 7039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7039): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7039): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7039): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7039): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/AndroidRuntime( 7046): 
D/AndroidRuntime( 7046): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7046): CheckJNI is OFF
,I/IndexDatabaseHelper( 7039): Using schema version: 115
,I/IndexDatabaseHelper( 7039): Index is fine
W/ContextImpl( 7039): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 1969): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1969): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1969): ***********state = 13
V/BluetoothPbapReceiver( 1969): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 1969): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1969): state: 13
V/BluetoothPbapService( 1969): Pbap Service closeService in
,V/BluetoothPbapService( 1969): successfully stopped pbap service
V/BluetoothPbapService( 1969): Pbap Service closeService out
V/BluetoothPbapService( 1969): Pbap Service onDestroy
V/BluetoothPbapService( 1969): Pbap Service closeService in
V/BluetoothPbapService( 1969): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1969): [BTUI] cleanup
V/WiFiOffLoadBroadcast( 7039): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7039): MCCMNC not supported: null
D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ef0fe1b:true
,I/ActivityManager(  853): Process com.android.contacts (pid 6663) has died
,D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
D/BluetoothManagerService(  853): Message: 30
D/BluetoothManagerService(  853): Message: 30
,W/bt-l2cap( 1969): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1969): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1969): ag scb idx 1 not allocated
E/bt-btif ( 1969): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1969): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1969): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1969): ag scb idx 1 not allocated
E/bt-btif ( 1969): BTA AG is already disabled, ignoring ...
E/bt-btif ( 1969): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 1969): bta_gattc_deregister Deregister Failedm unknown client cif
W/bt_userial( 1969): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 1969): hw_epilog_process
I/bt_userial_vendor( 1969): device fd = 70 close
D/LocalBluetoothProfileManager( 7039): Adding local MAP profile
D/BluetoothMap( 7039): Create BluetoothMap proxy object
D/BluetoothManagerService(  853): Message: 30
D/AndroidRuntime( 7046): Calling main entry com.android.commands.pm.Pm
,D/BluetoothManagerService(  853): Message: 30
E/bt_vendor( 1969): [BTUI] Proto is enabled. Set Proto disable!!
D/LocalBluetoothProfileManager( 7039): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7039):  get() - isFeatureLoaded : false
,I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  853): Killing 5490:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  853): WIN DEATH: Window{1796d47e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/GKI_LINUX( 1969): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/InputDispatcher(  853): Focus left window: Window{1796d47e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  853): Window went away: Window{1796d47e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  853): Skipping PackageSetting{f6515bf com.example.hello/10317} due to missing metadata
,I/ActivityManager(  853):   Force finishing activity ActivityRecord{284ead9c u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  853): Display changed displayId=0
,D/DSDPConnection( 1745): Display #0 changed.
W/ActivityManager(  853): Spurious death for ProcessRecord{42c75e7 5490:com.test.thalitest/u0a316}, curProc for 5490: null
,I/ActivityManager(  853): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/GKI_LINUX( 1969): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1969): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 1969): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1969): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/LGBluetoothUserBindClient( 7039): [BTUI] initUserBindClient
W/ContextImpl( 7039): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
I/ActivityManager(  853):   Force finishing activity ActivityRecord{284ead9c u0 com.test.thalitest/.MainActivity t222 f}
,W/ActivityManager(  853): Duplicate finish request for ActivityRecord{284ead9c u0 com.test.thalitest/.MainActivity t222 f}
D/BtSettings.ProfileConfig( 1969): Unable to read settings
D/BtSettings.ProfileConfig( 1969): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1969): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1969): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1969): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1969): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1969): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 1969): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 1969): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1969): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1969): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1969): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 1969): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
,I/LGBluetoothHfpAdapter( 1969): [BTUI] LGBluetoothHfpAdapter cleanup
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
D/HeadsetStateMachine( 1969): Exit Disconnected: -1
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
W/LGBluetoothHeadsetServiceJni( 1969): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/A2dpService( 1969): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1969): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1969): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
I/[LGHome]EVENT( 1871): [Launcher.java:5203:onStart()]onStart
D/A2dpStateMachine( 1969): Exit Disconnected: -1
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1969): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
,D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1969): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1969): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterState( 1969): Stopping profile services that were post enabled
D/BluetoothHeadset( 1745): Proxy object disconnected
D/BluetoothHeadset( 1745): Proxy object disconnected
D/BluetoothHeadset( 1745): Proxy object disconnected
D/sensors_hal_Time(  853): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  853): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  853): tsOffsetIs: Apps: 354893100493; DSPS: 11721183; Offset : -2818742347
D/KeyguardModel( 1368): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/QCNEJ   ( 1833): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  853): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 3382): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/GeofencerStateMachine( 1727): Ignoring removeGeofence because network location is disabled.
D/LGBluetoothA2dpAdapter( 1969): [BTUI] LGBluetoothA2dpAdapter cleanup
,W/LGBluetoothA2dpServiceJni( 1969): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 1969): [BTUI] terminate
D/BluetoothManagerService(  853): Message: 31
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
I/[SystemUI]QSlideListController( 1368): onReceive = android.intent.action.PACKAGE_REMOVED
W/System.err( 3382): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,W/System.err( 3382): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3382): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3382): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3382): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/HidService( 1969): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/HealthService( 1969): Received stop request...Stopping profile...
I/[LGHome]EVENT( 1871): [Launcher.java:776:onResume()]onResume
,D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/PanService( 1969): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/KeyguardModel( 1368): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1368): createShortcutInfo...
D/HeadsetStateMachine( 1969): Unbinding service...
,I/[LGHome]EVENT( 1871): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/DockEventReceiver( 7039): finishStartingService: stopping service
D/HeadsetPhoneState( 1969): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1969): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1969): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1969): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 1969): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1969): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1969): [BTUI] LGBluetoothHfpAdapter cleanup
D/BtGatt.DebugUtils( 1969): handleDebugAction() action=null
D/BtGatt.GattService( 1969): Received stop request...Stopping profile...
D/KeyguardModel( 1368): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1368): createShortcutInfo...
D/BtGatt.GattService( 1969): stop()
D/BtGatt.AdvertiseManager( 1969): advertise clients cleared
D/LGBluetoothGattAdapter( 1969): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
I/[LGHome]Launcher.Model( 1871): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/BluetoothMapService( 1969): Received stop request...Stopping profile...
D/BluetoothMapService( 1969): stop()
D/BluetoothMapEmailAppObserver( 1969): deinitObservers()
D/BluetoothMapEmailAppObserver( 1969): removeReceiver()
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
I/[LGHome]LGActivityUtil( 1871): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1871): [Launcher.java:929:onResume()]onResume end
I/Activity( 1871): Activity.onPostResume() called 
D/SapService( 1969): Received stop request...Stopping profile...
D/SapService( 1969): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1969): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 1969): [BTUI] terminateSapManager
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/**BluetoothFTPService( 1969): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1969): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1969): closeFtpServerNative
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/**OppService( 1969): Received stop request...Stopping profile...
D/OppService( 1969): Stopping Bluetooth OppService
D/OppService( 1969): cleanup OPP Service
W/BluetoothOPPServiceJni( 1969): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 1969): Cleaning up Bluetooth OPP callback object
D/OppService( 1969): remove callbacks and handler
D/LGBluetoothOppAdapter( 1969): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1969): cleanup done
D/BluetoothAdapterService( 1969): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a14ef1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 1969): cleanupNative
I/GKI_LINUX( 1969): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/[LGHome]EVENT( 1871): [Launcher.java:986:onPause()]onPause
I/GKI_LINUX( 1969): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1969): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,W/BluetoothHidServiceJni( 1969): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 1969): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 1969): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1969): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1969): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 1969): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1969): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1969): Handler(): got msg=4
D/BluetoothMapService( 1969): MAP Service closeService in
D/LGBluetoothMapAdapter( 1969): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1969): MAP Service closeService out
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
,D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 1969): cleanup()
D/BluetoothMapService( 1969): MAP Service closeService in
D/LGBluetoothMapAdapter( 1969): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1969): MAP Service closeService out
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 1969): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 1969): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1969): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1969): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,D/BluetoothFTPService( 1969): cleanup FTP Service
V/BluetoothFTPServiceJni( 1969): closeFtpServerNative
V/BluetoothFTPServiceJni( 1969): cleanupNative
W/BluetoothFTPServiceJni( 1969): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1969): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1969): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1969): cleanup done
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - Message: 1
D/BluetoothAdapterService(346115825)( 1969): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
,D/BluetoothAdapterState( 1969): isTurningOnRadio()=false
D/BluetoothAdapterState( 1969): isTurningOffRadio()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1969): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1969): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(346115825)( 1969): onProfileServiceStateChange() - All profile services stopped...
D/LgeBluetoothSimManager( 1745): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterState( 1969): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1969): Setting state to 10
I/BluetoothAdapterState( 1969): Bluetooth adapter state changed: 13-> 10
I/art     ( 1929): Explicit concurrent mark sweep GC freed 7882(475KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/19MB, paused 3.485ms total 155.636ms
,D/BluetoothAdapterService(346115825)( 1969): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 1969): cleanup OPP Service
D/OppService( 1969): remove callbacks and handler
D/LGBluetoothOppAdapter( 1969): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1969): cleanup done
D/BluetoothManagerService(  853): Message: 60
I/BluetoothAdapterState( 1969): Entering OffState
D/BluetoothManagerService(  853): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  853): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothA2dp(  853): onBluetoothStateChange: up=false
,D/BluetoothPan( 7039): onBluetoothStateChange on: false
,D/BluetoothHeadset( 1745): onBluetoothStateChange: up=false
D/BluetoothMap( 7039): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1745): onBluetoothStateChange: up=false
D/BluetoothPbap( 7039): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7039): onBluetoothStateChange: up=false
D/BluetoothHeadset(  853): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1745): onBluetoothStateChange: up=false
D/BluetoothAdapterService(346115825)( 1969): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@786344f
,D/BluetoothManagerService(  853): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  853): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService(  853): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  853): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  853): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1cb05ecc mBinding = false
D/BluetoothManagerService(  853): Sending unbind request.
D/BluetoothManagerService(  853): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(346115825)( 1969): onUnbind() - calling cleanup
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1368): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/BluetoothAdapterService(346115825)( 1969): cleanup()
D/KeyguardModel( 1368): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/BluetoothAdapter( 1368): 864134229: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1368): 864134229: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1798): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1798): Message: 2
D/LGBluetoothAPIService( 1798): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@39fb087d mBinding = false
D/LGBluetoothAPIService( 1798): Sending unbind request.
,I/[SystemUI]QuickSettingsHandler( 1368): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1368): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/BluetoothAdapterService(346115825)( 1969): cleanup() - Cleaning up adapter native
I/bt-btif ( 1969): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1969): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 1969): HAL bt_hal_cbacks->thread_evt_cb
,I/GKI_LINUX( 1969): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1969): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1969): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1969): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1969): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1969): GKI_exit_task 2 done
I/GKI_LINUX( 1969): GKI_exit_task 1 done
I/GKI_LINUX( 1969): GKI_exit_task 0 done
I/BluetoothServiceJni( 1969): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 1969): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 1969): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(346115825)( 1969): cleanup() - Bluetooth process exited normally.
D/LGBluetoothUserBindClient( 7039): [BTUI] onServiceConnected
D/LGBluetoothFeatureConfig( 7039): isPrivacyLogsEnabled : true
,D/BluetoothAdapterService(346115825)( 1969): cleanup() done
E/LGBluetoothEventManager( 7039): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7039): [BTUI] clear device connection state
I/art     ( 1969): System.exit called, status: 0
I/AndroidRuntime( 1969): VM exiting with result code 0, cleanup skipped.
D/LGBluetoothAuthorization( 7039): [BTUI] cancel All Notification
I/NotificationManager( 7039): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7039): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7039): com.android.settings: cancel(-1000011) by com.android.settings
D/BluetoothAdapter( 1727): 8861684: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1727): 8861684: getState() :  mService = null. Returning STATE_OFF
V/AudioFlinger(  281): 1969 died, releasing its sessions
V/AudioFlinger(  281):  pid 1745 @ 0
V/AudioFlinger(  281):  pid 3115 @ 1
V/AudioFlinger(  281):  pid 3115 @ 2
,W/[LGHome]LGWallpaperInfo( 1871): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1871): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/NotificationManager( 7039): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7039): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7039): com.android.settings: cancel(-1000041) by com.android.settings
D/LGBluetoothUserBindClient( 7039): [BTUI] onServiceDisconnected
W/ResourcesManager( 1368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1368): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/FMFRW_FmProxy( 1798): Fm Proxy object disconnected
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.android.mms: Resource ID #0x0
,I/ActivityManager(  853): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7099 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/art     (  853): Explicit concurrent mark sweep GC freed 46952(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.298ms total 257.621ms
I/art     (  853): WaitForGcToComplete blocked for 242.543ms for cause Explicit
,I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@290b6f4d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  853): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/KeyguardModel( 1368): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1368): createShortcutInfo...
W/PhoneWindowManagerEx(  853): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  853): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  853): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@290b6f4d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  853): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  853): Focus entered window: Window{22886c08 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,I/[LGHome]EVENT( 1871): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1871): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1871): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/ActivityManager(  853): Process com.android.bluetooth (pid 1969) has died
W/ActivityManager(  853): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
W/ActivityManager(  853): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
D/BluetoothPermissionRequest( 7039): onReceive
W/ResourcesManager( 1368): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/LGBluetoothAuthorization( 7039): [BTUI] cancel All Notification
I/[LGHome]EVENT( 1871): [Launcher.java:5214:onStop()]onStop
I/NotificationManager( 7039): com.android.settings: cancel(17301632) by com.android.settings
,I/NotificationManager( 7039): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7039): com.android.settings: cancel(-1000011) by com.android.settings
D/KeyguardModel( 1368): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1368): createShortcutInfo...
I/NotificationManager( 7039): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7039): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7039): com.android.settings: cancel(-1000041) by com.android.settings
W/ResourcesManager( 1368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1368): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1368): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1368): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1368): createShortcutInfo...
I/[LGHome]EVENT( 1871): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1871): [setNavigationBarColor] color=0x 0
I/ActivityManager(  853): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7119 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 299us total 21.504ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.740ms
,D/KeyguardModel( 1368): handleShortcutListChanged...
D/KeyguardModel( 1368): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1368): createShortcutInfo...
D/administrator(  853): Handling package changes for user 0
D/KeyguardModel( 1368): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1368): createShortcutInfo...
,W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1368): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1368): createShortcutInfo...
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.371ms
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1368): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1368): createShortcutInfo...
,W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1368): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1368): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1368): createShortcutInfo...
D/KeyguardModel( 1368): handleShortcutListChanged...
,I/PCSuite ( 7099): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7099): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7099): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  853): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7139 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/InputMethodManagerService(  853): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  853): Got RemoteException sending setActive(false) notification to pid 5490 uid 10316
,W/ResourcesManager( 7119): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7119): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7119): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7119): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
,I/art     (  853): Explicit concurrent mark sweep GC freed 6709(382KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 10.658ms total 366.185ms
,D/BluetoothAdapterApp( 7119): Loading JNI Library
,I/[LGHome]Launcher.Model( 1871): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/Timeline(  853): Timeline: Activity_windows_visible id: ActivityRecord{3c45b7b8 u0 com.lge.launcher2/.Launcher t221} time:355520
,I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
E/BluetoothServiceJni( 7119): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/BluetoothAdapterApp( 7119): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1dbcc780 Instance Count = 1
,D/BluetoothAdapterApp( 7119): onCreate
W/ResourcesManager( 7139): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/LGBluetoothServiceJni( 7119): classInitNative: succeeds
D/BtSettings.ProfileConfig( 7119): [BTUI] HeadsetServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding HeadsetService
D/BtSettings.ProfileConfig( 7119): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding A2dpService
D/BtSettings.ProfileConfig( 7119): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding HidService
D/BtSettings.ProfileConfig( 7119): [BTUI] HealthServiceis supported
,D/BtSettings.ProfileConfig( 7119): Adding HealthService
D/LGBluetoothFeatureConfig( 7119): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 7119): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 7119): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding PanService
D/BtSettings.ProfileConfig( 7119): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding GattService
W/IInputConnectionWrapper( 1871): getTextBeforeCursor on inactive InputConnection
D/BtSettings.ProfileConfig( 7119): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 7119): [BTUI] region:EU country:EU
I/[LGHome]Launcher.Model( 1871): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/BtSettings.ProfileConfig( 7119): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding SapService
D/BtSettings.ProfileConfig( 7119): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding FTPService
E/BtSettings.ProfileConfig( 7119): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 7119): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 7119): Adding OppService
E/b       ( 1582): Unable to connect to the editor to retrieve text... will retry later
D/BtSettings.ProfileConfig( 7119): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 7119): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 7119): Unable to read settings
D/BtSettings.ProfileConfig( 7119): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7119): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 7119): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 7119): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 7119): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 7119): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 7119): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 7119): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 7119): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 7119): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 7119): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 7119): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 7119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 7119): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 7119): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 7119): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 7119): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 7119): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 7119): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 7119): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/LGBluetoothOppAdapter( 7119): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppReceiver( 7119): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 7119): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 7119): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 7119): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 7119): com.android.bluetooth: cancel(-1) by com.android.bluetooth
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1871): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1871): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService(  853): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  853): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  853): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1368): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1368): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1368):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1368): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/TaskPersister(  853): removeObsoleteFile: deleting file=222_task.xml
,I/FmServiceJni( 7119): classInitNative: succeeds
D/LCardEmulationManager( 1780): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1780): getDefaultRoute
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1871): getTextAfterCursor on inactive InputConnection
D/FmService( 7119): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@397f355fservicecom.broadcom.fm.fmreceiver.FmService@23e6dbac
I/[LGHome]Launcher.Model( 1871): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
D/FmNativehandler( 7119): start
I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/BluetoothRadioManager( 7119): [BTUI] getRadioManager()
,D/BluetoothRadioManager( 7119): [BTUI] BluetoothRadioManager()
D/BluetoothManagerService(  853): Message: 20
D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1df37a8:true
D/AndroidRuntime( 7046): Shutting down VM
D/BluetoothRadioManager( 7119): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
,W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
V/FmService( 7119): FM Service  onCreate
D/FmService( 7119): Binding service...
D/FMFRW_FmProxy( 1798): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@3a26e372
D/LGBluetoothUserBindClient( 7039): [BTUI] onServiceConnected
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
,W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
D/BluetoothManagerService(  853): Message: 20
,D/BluetoothManagerService(  853): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1978bb5:true
D/BluetoothAdapter( 7139): 346115825: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 7139): 346115825: getState() :  mService = null. Returning STATE_OFF
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1871): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,D/BluetoothAdapterService( 7119): Set JNI Library before classInit
V/WiFiOffLoadBroadcast( 7039): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/BluetoothAdapterService(773995222)( 7119): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothAdapterService(773995222)( 7119): onCreate()
D/BluetoothAdapterState( 7119): make
D/WiFiOffLoadBroadcast( 7039): MCCMNC not supported: null
I/bluedroid( 7119): init
I/BluetoothAdapterState( 7119): Entering OffState
,I/bte_conf( 7119): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 7119): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 7119): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 7119): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 7119): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 7119):  [BTUI] Load_abtddress
D/BTIF_CORE( 7119): [BTUI] lge_wait_for_load_bluetooth_address : success!
D/bt-btif ( 7119): PERSIST_BDADDR_PROPERTY is  F8:95:C7:87:85:54
D/bt-btif ( 7119): Got prior random BDA F8:95:C7:87:85:54
I/bluedroid( 7119): get_profile_interface socket
I/bluedroid( 7119): get_profile_interface map_client
E/BluetoothServiceJni( 7119): Error getting mapclient interface
I/bt-btif ( 7119): btif_get_adapter_property 2
I/bt-btif ( 7119): btif_get_adapter_property 1
I/GKI_LINUX( 7119): gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 7119): btif task starting
D/bt-btif ( 7119): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 7119): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 7119): execute storage request event : 3
D/bt-btif ( 7119): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 7119): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 7119): Address is:F8:95:C7:87:85:54
I/bt-btif ( 7119): execute storage request event : 3
D/bt-btif ( 7119): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 7119): in, bd addr:, prop type:1, len:512
I/bt-btif ( 7119): HAL bt_hal_cbacks->adapter_properties_cb
I/PCSuite ( 7099): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7099): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7099): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/lge_bdaddr_loader( 7167): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 7167): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 7167): [GET_FTM][id=8], offset=16384
D/BluetoothAdapterProperties( 7119): Name is: G3s-1
D/lge_bdaddr_loader( 7167): [BTUI] bdaddr to set in property : F8:95:C7:87:85:54
,D/BluetoothManagerService(  853): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  853): Stored Bluetooth name: G3s-1
I/ActivityManager(  853): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7169 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/BluetoothAdapterService( 7119): getAdapterService() - Service not available
D/LGBluetoothServiceAdapter( 7119): [BTUI] check adapter is available - false.
,D/LGBluetoothSettingsDBObserver( 7119): [BTUI] register observer for LG device name DB
E/lge_bdaddr_loader( 7167): [BTUI] bluetooth_load_bdaddress : OK => F8:95:C7:87:85:54
,D/lge_bdaddr_loader( 7167): [BTUI] bdaddr_loader ::: END
D/BluetoothAdapterService(773995222)( 7119): onBind()
V/BluetoothSapReceiver( 7119): [BTUI] checkServiceStart
D/BluetoothRadioManager( 7119): onServiceConnected: connected to AdapterService com.android.bluetooth.btservice.AdapterService
D/BluetoothRadioManager( 7119): Message: 40
D/BluetoothRadioManager( 7119): MESSAGE_RADIO_SERVICE_CONNECTED: 1
D/BluetoothRadioManager( 7119):  Turning on BT modules Radio on = false
D/LGBluetoothStateChangeReceiver( 7119): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
I/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  853): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7186 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ResourcesManager(  853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1871): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/ResourcesManager( 7169): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7186): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  853): Killing 6617:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1871): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1871): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourceType(  853): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)

```
