#### Test 5065027857de7f1_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
D/Finsky  ( 4916): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
--------- beginning of system
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{15a15867 type 0 when 1449832293566 com.android.vending} when 1449832293566
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
I/ActivityManager(  839): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5339 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/GservicesProvider( 5339): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient( 5339): GMS http client unavailable, use old client
I/GoogleHttpClient( 5339): GMS http client unavailable, use old client
D/libc-netbsd( 4916): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4916): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4916): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4916): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  839): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4916): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
D/libc-netbsd( 4916): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4916): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AndroidRuntime( 5337): 
D/AndroidRuntime( 5337): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager(  839): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5374 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/AndroidRuntime( 5337): CheckJNI is OFF
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
W/ResourcesManager( 5374): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5374): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd( 4916): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4916): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 4916): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/MultiDex( 5374): VM with version 2.1.0 has multidex support
I/MultiDex( 5374): install
I/MultiDex( 5374): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5374): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 5374): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5374): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@aed367c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5374): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5374): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5374): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1742): callingUid 10006, callindPid: 1742
E/MDM     ( 1742): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 3981): Restart initialization of location
D/AuthorizationBluetoothService( 1742): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 5374): Reading stored module config
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 5337): Calling main entry com.android.commands.am.Am
I/NotificationManager( 1742): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  839): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     ( 1742): Explicit concurrent mark sweep GC freed 28101(1669KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 13MB/22MB, paused 1.801ms total 97.459ms
D/ActivityManager(  839): setTaskToReturnTo : TaskRecord{576585b #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  839): setTaskToReturnTo : TaskRecord{576585b #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  839): AppWindowTokenEx init.. 
D/ContextHelper(  839): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  839): Focus left window: Window{1332fbf2 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5337): Shutting down VM
D/SplitWindow(  839): check instance of lgWin Window{3975fa0d u0 Starting com.test.thalitest}
I/[LGHome]EVENT( 1890): [Launcher.java:986:onPause()]onPause
W/GCoreFlp( 1742): No location to return for getLastLocation()
W/FusedLocationProvider( 1742): location=null
D/ChimeraCfgMgr( 5374): Loading module com.google.android.gms.car from APK com.google.android.gms
I/ActivityManager(  839): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5417 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/NativeLibraryUtils( 5374): Install completed successfully. count=14 extracted=0
I/[LGHome]EVENT( 1890): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1965): Closing mic
I/MicrophoneInputStream( 1965): mic_close com.google.android.apps.gsa.speech.audio.u@156683b1
V/AudioRecord( 1965): stop()
D/AudioRecord( 1965): AudioRecord->stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioFlinger(  284): Record stopped OK
V/AudioPolicyManager(  284): stopInput() input 17
V/AudioPolicyService(  284): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  284): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing release audio patch
I/[LGHome]EVENT( 1890): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  284): ThreadBase::setParameters() routing=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb414e000
D/audio_hw_primary(  284): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
I/WindowStateAnimator(  839): Starting window displayed
I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1382): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17d8be8f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1382): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1382):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1382): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/BarTransitions( 1382): draw background and invalidate : color = 1f000000
D/BarTransitions( 1382): draw background and invalidate : color = c0c0c0c
V/audio_hw_primary(  284): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  284): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  284): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  284): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  284): disable_audio_route: exit
E/audio_hw_primary(  284): disable_snd_device: enter 144
D/hardware_info(  284): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  284): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  284): stop_input_stream: exit: status(0)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyManager(  284): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  284): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  284): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  284): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyService(  284): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  284): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  284): setParameters(): io 17, keyvalue hotword_active=0, calling pid 284
V/AudioFlinger(  284): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  284): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  284): in_set_parameters: exit: status(0)
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb414e000
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioRecord( 1965): stop()
,V/AudioRecord( 1965): stop()
V/AudioRecord( 1965): stop()
V/AudioFlinger(  284): releasing 16 from 1965 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioPolicyManager(  284): releaseInput() 17
V/AudioPolicyManager(  284): closeInput(17)
V/AudioFlinger(  284): closeInput() 17
V/AudioSystem(  284): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  839): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): ThreadBase::exit
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioSystem( 3072): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): RecordThread 0xb414e000 exiting
V/AudioSystem( 1965): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1382): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1764): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  284): adev_close_input_stream: enter:stream_handle(0xb40367a0)
D/audio_hw_primary(  284): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioSystem( 2092): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  284): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  284): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  284): releaseInput() exit
,V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioFlinger(  284): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  284): AudioCommandThread() processing update audio port list
V/AudioFlinger(  284): removeClient_l() pid 1965, calling pid 284
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1965): Hotword detection finished
I/HotwordRecognitionRnr( 1965): Stopping hotword detection.
,D/CAR.SERVICE( 5374): Connecting to CarCallService...
,I/art     ( 5374): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5374): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5374): com.google.android.projection.gearhead isn't installed.
,D/ContextHelper( 5417): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,D/CAR.TEL.Service( 5374): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5374): Creating a new PhoneAdapter instance
,W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5374): setListener: com.google.android.gms.car.dn@134a1f7b
,W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5374): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5374): Starting CarCallService with initial phone null
I/NotificationManager( 5374): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/WebViewFactory( 5417): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5417): Time to load native libraries: 2 ms (timestamps 5653-5655)
I/LibraryLoader( 5417): Expected native library version number "",actual native library version number ""
,D/CAR.SERVICE( 5374): Package validated; name: com.android.vending
I/NotificationManager( 4916): com.android.vending: cancel(10436) by com.android.vending
,V/WebViewChromiumFactoryProvider( 5417): Binding Chromium to main looper Looper (main, tid 1) {1e16f44a}
I/LibraryLoader( 5417): Expected native library version number "",actual native library version number ""
V/Finsky  ( 4916): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/chromium( 5417): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5417): Initializing chromium process, singleProcess=true
,W/art     ( 5417): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5417): ApplicationContext is null in ApplicationStatus
,W/chromium( 5417): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5417): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5417): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5417): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5417): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5417): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5417): Remote Branch: 
I/Adreno-EGL( 5417): Local Patches: 
I/Adreno-EGL( 5417): Reconstruct Branch: 
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,V/AudioPolicyService(  284): registerClient() client 0xb4027060, uid 10316
,D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b304596:true
D/BluetoothAdapter( 5417): 1054346006: getState() :  mService = null. Returning STATE_OFF
D/libc-netbsd( 4916): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4916): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4916): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4916): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 4916): [1] DailyHygiene.access$600: Logging device features
D/Finsky  ( 4916): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{4764421 type 0 when 1449832295512 com.android.vending} when 1449832295512
,D/DeviceConnectionService( 1742): client connected with version: 8296000
,D/Finsky  ( 4916): [594] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/libc-netbsd( 4916): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4916): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4916): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4916): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  839): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{2e86aa0 type 2 when 96127 com.google.android.gms} when 96127
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  839): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/art     ( 5417): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5417): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5417): CordovaWebView is running on device made by: LGE
,W/art     ( 5417): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5417): Attempt to remove local handle scope entry from IRT, ignoring
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 96245550592; DSPS: 3252921; Offset : -3030698909
,I/Activity( 5417): Activity.onPostResume() called 
D/OpenGLRenderer( 5417): Render dirty regions requested: true
I/OpenGLRenderer( 5417): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5417): Enabling debug mode 0
D/Atlas   ( 5417): Validating map...
,D/SplitWindow(  839): check instance of lgWin Window{1ae9581b u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5417): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  839): Killing 5174:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10069/pid_5174/cgroup.procs: No such file or directory
,D/InputDispatcher(  839): Focus entered window: Window{1ae9581b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  839): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  839): Displayed com.test.thalitest/.MainActivity: +1s257ms
I/Timeline(  839): Timeline: Activity_windows_visible id: ActivityRecord{13b188f8 u0 com.test.thalitest/.MainActivity t220} time:96432
I/Timeline( 5417): Timeline: Activity_idle id: android.os.BinderProxy@3f8765c6 time:96444
,W/BindingManager( 5417): Cannot call determinedVisibility() - never saw a connection for the pid: 5417
,D/JsMessageQueue( 5417): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5417): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622845952
,D/JX-Cordova( 5417): jxcore cordova android initializing
I/art     ( 5417): CheckpointMarkThreadRoots callback created = 0x9b5cb550
,I/art     ( 5417): CheckpointMarkThreadRoots callback created = 0x9b5cb520
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,W/jxcore-log( 5417): Initializing JXcore engine
,W/jxcore-log( 5417): JXcore engine is ready
W/jxcore-log( 5417): Starting JXcore engine
,W/.test.thalitest( 5417): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5665]" dev="sockfs" ino=5665 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5417): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5417): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6435]" dev="sockfs" ino=6435 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5417): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/.test.thalitest( 5417): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5417): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25341]" dev="sockfs" ino=25341 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5417): Platform android
W/jxcore-log( 5417): 
,W/jxcore-log( 5417): Process ARCH arm
W/jxcore-log( 5417): 
I/ActivityManager(  839): Killing 5191:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_5191/cgroup.procs: No such file or directory
,I/jxcore-log( 5417): JXcore Cordova bridge is ready!
I/jxcore-log( 5417): 
W/jxcore-log( 5417): JXcore engine is started
,I/chromium( 5417): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5417): Skipped 182 frames!  The application may be doing too much work on its main thread.
D/CAR.SERVICE( 5374): mConnectedToCar = false, abort
,E/ActivityThread( 5374): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@6db5303 that was originally bound here
E/ActivityThread( 5374): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@6db5303 that was originally bound here
E/ActivityThread( 5374): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5374): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5374): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5374): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5374): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5374): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5374): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5374): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5374): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5374): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5374): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5374): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5374): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5374): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5374): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5374): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5374): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5374): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5374): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 5374): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3d7efb0a that was originally bound here
E/ActivityThread( 5374): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3d7efb0a that was originally bound here
E/ActivityThread( 5374): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5374): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5374): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5374): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5374): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5374): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5374): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5374): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5374): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5374): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5374): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5374): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5374): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5374): 	at android.app.ActivityThread.access,$1900(ActivityThread.java:155)
E/ActivityThread( 5374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5374): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5374): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5374): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5374): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  839): Unbind failed: could not find connection for android.os.BinderProxy@2d40af93
I/jxcore-log( 5417): Toggling radios to true
I/jxcore-log( 5417): 
,D/BluetoothManagerService(  839): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  839): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  839): Message: 1
D/BluetoothManagerService(  839): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService(  839): getAllProviders()=[passive, gps, network]
,D/BluetoothAdapterService(1054346006)( 2068): onBind()
D/Ulp_jni (  839): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  839): JNI:system_update. Event-4
D/BluetoothManagerService(  839): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  839): Message: 40
D/BluetoothManagerService(  839): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/WifiServiceImplEx(  839): setWifiEnabled: true pid=5417, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  839): setWifiEnabled: true pid=5417, uid=10316
,D/LocationManagerService(  839): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  839): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  839): JNI:system_update. Event-4
I/bluedroid( 2068): config_hci_snoop_log
D/WifiServiceImplEx(  839): disconnect pid=5417, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  839): reconnect pid=5417, uid=10316, packageName=com.test.thalitest
D/BluetoothManagerService(  839): Calling onBluetoothServiceUp callbacks
I/LGFTMITEM(  839): [GET_FTM][id=6], offset=12288
D/BluetoothManagerService(  839): Broadcasting onBluetoothServiceUp() to 9 receivers.
I/jxcore-log( 5417): Radios toggled
I/jxcore-log( 5417): 
E/WifiHW  (  839): Wifi MAC Address = a0:39:f7:70:12:80
,D/BluetoothManagerService(  839): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiHW  (  839): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  839): band=b
E/WifiHW  (  839): ": cur_etheraddr=a0:39:f7:70:12:80
D/SoftapController(  279): Softap fwReload - Ok
V/LGMDMManagerInternal( 2068): Create singleton instance
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring down wlan0
D/CommandListener(  279): Clearing all IP addresses on wlan0
,E/WifiHW  (  839): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/wpa_supplicant( 5535): Successfully initialized wpa_supplicant
,D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothAdapterService(1054346006)( 2068): enable() - Enable called with quiet mode status =  false
D/BluetoothAdapterState( 2068): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2068): Setting state to 11
I/jxcore-log( 5417): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 5417): 
I/BluetoothAdapterState( 2068): Bluetooth adapter state changed: 10-> 11
I/jxcore-log( 5417): Perf Test app loaded loaded
I/jxcore-log( 5417): 
D/BluetoothAdapterService(1054346006)( 2068): updateAdapterState() - Broadcasting state to 1 receivers.
,I/jxcore-log( 5417): check test folder
I/jxcore-log( 5417): 
D/BluetoothManagerService(  839): Message: 60
D/BluetoothManagerService(  839): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  839): Bluetooth State Change Intent: 10 -> 11
D/BluetoothAdapterService(1054346006)( 2068): processStart()
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/LGBluetoothAPIService( 1816): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/wpa_supplicant( 5535): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 5535): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
I/jxcore-log( 5417): found test : ./testFindPeers.js
I/jxcore-log( 5417): 
D/BtSettings.ProfileConfig( 2068): Unable to read settings
D/BtSettings.ProfileConfig( 2068): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2068): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2068): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2068): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2068): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 2068): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 2068): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2068): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2068): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2068): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2068): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5545 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/WifiMonitor(  839): startMonitoring(wlan0) with mConnected = false
I/WifiServerServiceExt(  839): WIFI_STATE_CHANGED_ACTION [2]
,I/jxcore-log( 5417): found test : ./testSendData.js
I/jxcore-log( 5417): 
,W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2068): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1054346006)( 2068): processStart() - Make Bond State Machine
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
,I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:42.063 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/BluetoothBondStateMachine( 2068): make
,I/[SystemUI]BluetoothHandler( 1382): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/BluetoothAdapterService( 2068): setAdapterService() - set to: null
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
,D/LGBluetoothServiceAdapter( 2068): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 2068): StableState(): Entering Off State
D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2068): Unable to read settings
D/BtSettings.ProfileConfig( 2068): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2068): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2068): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2068): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2068): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2068): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 2068): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 2068): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2068): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2068): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2068): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2068): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2068): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2068): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 2068): Received start request. Starting profile...
D/BluetoothHeadset(  839): Proxy object connected
,D/BluetoothHeadset( 1764): Proxy object connected
D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2068): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
I/LGBluetoothHeadsetServiceJni( 2068): classInitNative: succeeds
D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2068): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/LGBluetoothFeatureConfig( 2068): isPrivacyLogsEnabled : true
,I/BluetoothHeadsetServiceJni( 2068): classInitNative: succeeds
D/HeadsetStateMachine( 2068): make
D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2068): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2068): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2068): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothHeadset( 1764): Proxy object connected
,D/BluetoothHeadset( 1764): Proxy object connected
D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2068): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2068): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/BluetoothAdapterService( 2068): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2068): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 2068): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2068): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1054346006)( 2068): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/LGMDMManager( 2068): Create singleton instance
I/BluetoothAdapterState( 2068): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/chromium( 5417): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  839): Process com.google.android.gm (pid 5061) has died
D/HeadsetStateMachine( 2068): max_hf_connections = 1
I/bluedroid( 2068): get_profile_interface handsfree
,I/bt-btif ( 2068): btif_hf_get_interface
I/bt-btif ( 2068): init
D/bt-btif ( 2068): max_hf_clients = 1
D/bt-btif ( 2068): btif_max_hf_clients = 1
D/bt-btif ( 2068): btif_enable_service: current services:0xa0558330
V/ToneGenerator( 2068): ToneGenerator constructor: streamType=8, volume=1.000000
,V/AudioPolicyService(  284): registerClient() client 0xb4027ca0, uid 1002
V/AudioPolicyManager(  284): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  284): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  284): getOutput() returns output 2
V/AudioFlinger(  284): registerClient() client 0xb40332c8, pid 2068
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  284): thread 0xb56eb000 type 0 TID 1292 waking up
V/AudioFlinger(  284): thread 0xb5735000 type 0 TID 1294 waking up
V/AudioFlinger(  284): thread 0xb5651000 type 0 TID 1291 waking up
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  284): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  284): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1382): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1382): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 1764): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1764): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  839): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  839): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  284): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  284): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  839): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  839): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 1764): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1764): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1965): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1965): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1965): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1965): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2068): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2068): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 2068): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2068): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 1382): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1382): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  284): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  284): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1764): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1382): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1764): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1382): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 3072): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3072): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2092): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2092): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  839): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  839): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2068): getOutputSamplin,gRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 2068): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2068): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/ToneGenerator( 2068): Create Track: 0xb4909480
V/AudioTrack( 2068): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 2068): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioSystem( 1965): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1965): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3072): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3072): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3072): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3072): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2092): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2092): ioConfigChanged() opening already existing output! 6
I/AudioFlinger(  284): isAudioPlaybackHookOn() false
V/AudioSystem( 2092): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2092): ioConfigChanged() opening already existing output! 2
D/AudioTrack( 2068): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  284): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  284): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  284): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  284): getOutput() returns output 2
V/AudioSystem( 2068): getLatency() output 2, latency 50
V/AudioSystem( 2068): getFrameCount() output 2, frameCount 960
V/AudioTrack( 2068): createTrack_l() output 2 afLatency 50
V/AudioTrack( 2068): Create normal PCM 0x1 Track
V/AudioFlinger(  284): createTrack() lSessionId: 22
V/AudioFlinger(  284): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 2068): Flags here  0x4 
V/AudioTrack( 2068): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  284): acquiring 22 from 2068, for 2068
V/AudioFlinger(  284):  added new entry for 22
V/ToneGenerator( 2068): ToneGenerator INIT OK, time: 102804
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb5651000
D/HeadsetStateMachine( 2068): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 2068): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2068): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 2068): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  284): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2068
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
D/audio_hw_primary(  284): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  284): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  284): platform_set_parameters: enter: bt_samplerate=8000
D/BluetoothA2dp(  839): Proxy object connected
D/A2dpService( 2068): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2068): classInitNative: succeeds
V/Avrcp   ( 2068): make
D/Avrcp   ( 2068): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 2068): get_profile_interface avrcp
I/bt-btif ( 2068): btif_rc_get_interface
I/bt-btif ( 2068): ## init ##
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
,V/ToneGenerator( 2068): ToneGenerator destructor
V/ToneGenerator( 2068): stopTone
V/ToneGenerator( 2068): Delete Track: 0xb4909480
V/AudioTrack( 2068): ~AudioTrack, releasing session id from 2068 on behalf of 2068
V/AudioFlinger(  284): remove track (4099) and delete from mixer
V/AudioPolicyService(  284): AudioCommandThread() adding release output 2
V/AudioPolicyService(  284): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  284): releaseOutput() 2
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioFlinger(  284): PlaybackThread::Track destructor
V/AudioFlinger(  284): removeClient_l() pid 2068, calling pid 284
I/LGBluetoothAvrcpServiceJni( 2068): classInitNative: succeeds
V/AudioFlinger(  284): releasing 22 from 2068 for 2068
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
I/LGBluetoothAvrcpAdapter( 2068): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 2068): initNative: succeeds
W/ResourcesManager( 5545): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5545): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5545): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5545): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5545): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  839): Process com.lge.qremote (pid 5017) has died
,D/UEI.SmartControl( 5037): Service.onUnbind: IControl
D/UEI.SmartControl( 5037): Service.onDestroy
D/UEI.SmartControl( 5037): Shutdown IRRCPlayer... 
W/irrc_jni( 5037): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5037): ~IrrcClient ++ 
D/irrcClient( 5037): ~IrrcClient -- 
W/irrc_jni( 5037): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5037): Blaster closed
D/UEI.SmartControl( 5037): Blaster closed
D/UEI.SmartControl( 5037): Shut down QS...
D/UEI.SmartControl( 5037): Stopped file observer...
I/UEI.SmartControl( 5037): QS lib stop result = true
,D/UEI.SmartControl( 5037): QS shutdown complete
I/ActivityManager(  839): Process com.android.calendar (pid 5278) has died
,I/IndexDatabaseHelper( 5545): Using schema version: 115
I/IndexDatabaseHelper( 5545): Index is fine
,I/art     (  839): Explicit concurrent mark sweep GC freed 19698(920KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.677ms total 174.648ms
I/BluetoothAvrcpBrcmAdapterJni( 2068): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 2068): initBrcmNative
,V/AudioService(  839): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
E/AudioService(  839): No RCC entry present to update
,E/RemoteController( 2068): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2068): classInitNative
I/BluetoothA2dpServiceJni( 2068): classInitNative: succeeds
D/A2dpStateMachine( 2068): make
I/bluedroid( 2068): get_profile_interface a2dp
I/bt-btif ( 2068): btif_av_get_src_interface
I/bt-btif ( 2068): init
D/bt-btif ( 2068): btif_enable_service: current services:0xa0558330
I/LGBluetoothA2dpServiceJni( 2068): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 2068): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 2068): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 2068): [BTUI] init
D/LGBluetoothPowerControlManager( 2068): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  839): Message: 30
,D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
I/BluetoothHidServiceJni( 2068): classInitNative: succeeds
D/A2dpStateMachine( 2068): Enter Disconnected: -2
D/HidService( 2068): Received start request. Starting profile...
I/bluedroid( 2068): get_profile_interface hidhost
I/bt-btif ( 2068): btif_hh_get_interface
I/bt-btif ( 2068): init
D/bt-btif ( 2068): btif_enable_service: current services:0xa0558330
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
I/BluetoothHealthServiceJni( 2068): classInitNative: succeeds
D/HealthService( 2068): Received start request. Starting profile...
,I/bluedroid( 2068): get_profile_interface health
I/bt-btif ( 2068): btif_hl_get_interface
I/bt-btif ( 2068): init
D/bt-btif ( 2068): Process name (droid.bluetooth)
D/bt-btif ( 2068): btif_hl_soc_thread_init
D/bt-btif ( 2068): create_thread: entered
D/bt-btif ( 2068): create_thread: thread created successfully
D/bt-btif ( 2068): entered btif_hl_select_thread
D/bt-btif ( 2068): btif_hl_select_wakeup_init
I/LGBluetoothHealthServiceJni( 2068): classInitNative: succeeds
D/bt-btif ( 2068): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 2068): max_s=55 
D/bt-btif ( 2068): set curr_set = org_set 
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
I/BluetoothPanServiceJni( 2068): classInitNative(L105): succeeds
D/PanService( 2068): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2068): initializeNative(L110): pan
I/bluedroid( 2068): get_profile_interface pan
D/bt-btif ( 2068): stack_initialized = 0, btpan_cb.enabled:0
,V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager(  839): Process com.uei.lg.quicksetsdk.lite (pid 5037) has died
I/LGBluetoothPanAdapter( 2068): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
I/BtGatt.JNI( 2068): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 2068): handleDebugAction() action=null
D/BtGatt.GattService( 2068): Received start request. Starting profile...
D/BtGatt.GattService( 2068): start()
I/bluedroid( 2068): get_profile_interface gatt
,D/BtGatt.AdvertiseManager( 2068): advertise manager created
,I/LGBluetoothGattAdapter( 2068): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 2068): setGattService:  set to: null
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
I/LGBluetoothMapAdapter( 2068): [BTUI] getInstance : create [LGBluetoothMapAdapter]
,V/BluetoothMapService( 2068): BluetoothMapBinder()
D/BluetoothMapService( 2068): Received start request. Starting profile...
D/BluetoothMapService( 2068): start()
D/BluetoothMapEmailSettingsLoader( 2068): Found 0 applications
D/BluetoothMapEmailAppObserver( 2068): createReceiver()
D/BluetoothMapEmailAppObserver( 2068): initObservers()
D/BluetoothMapEmailAppObserver( 2068): getEnabledAccountItems()
,D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
I/BluetoothSAPServiceJni( 2068): classInitNative(L170): succeeds
D/SapService( 2068): Received start request. Starting profile...
,D/BluetoothSAPServiceJni( 2068): initializeNative(L175): sap
I/bluedroid( 2068): get_profile_interface sap
I/bt-btif ( 2068): btif_sc_get_interface
I/bt-btif ( 2068): init
D/bt-btif ( 2068): btif_enable_service: current services:0xa0558330
I/LGBluetoothSapAdapter( 2068): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 2068): [BTUI] Create LGBluetoothSapManager Instance
D/WiFiOffLoadUpdatePriority( 5545): remove : truetruefalse
D/LGBluetoothSapManager( 2068): [BTUI] initSapManager
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
D/WiFiOffLoadUpdatePriority( 5545): remove2
,V/WiFiOffLoadSharedPrefsUtils( 5545): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5545): save remove
D/WiFiOffLoadBroadcast( 5545): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5545): S: false, R: true
D/LgeBluetoothSimManager( 1764): [BTUI] SAP_ENABLE_EVT
V/BluetoothFTPServiceJni( 2068): classInitNative
,I/BluetoothFTPServiceJni( 2068): classInitNative(L271): succeeds
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
D/BluetoothFTPService( 2068): BluetoothFtpBinder()
D/**BluetoothFTPService( 2068): Received start request. Starting profile...
V/BluetoothFTPService( 2068): FTP-Server Service start
I/ActivityManager(  839): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5580 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothFTPServiceJni( 2068): initFtpNativeDataNative(L275): FTP
I/bluedroid( 2068): get_profile_interface ftp
I/bt-btif ( 2068): btif_fts_get_interface
I/bt-btif ( 2068): init
D/bt-btif ( 2068): btif_enable_service: current services:0xa0558330
D/BluetoothFTPServiceJni( 2068): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
D/LGBluetoothFeatureConfig( 2068): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 2068): classInitNative
I/BluetoothOPPServiceJni( 2068): classInitNative(L373): succeeds
V/OppService( 2068): Opp initBinder
D/**OppService( 2068): Received start request. Starting profile...
D/OppService( 2068): Starting OppService 
D/LGBluetoothOppAdapter( 2068): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,I/NotificationManager( 2068): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 2068): send message
D/BluetoothOppPreference( 2068): Dumping Names:  
D/BluetoothOppPreference( 2068): {}
D/BluetoothOppPreference( 2068): Dumping Channels:  
D/BluetoothOppPreference( 2068): {}
,D/OppService( 2068): Start()
W/BluetoothOPPServiceJni( 2068): initOppNative
D/BluetoothOPPServiceJni( 2068): initOppNative(L383): OPP
I/bluedroid( 2068): get_profile_interface opp
I/bt-btif ( 2068): btif_op_get_interface
D/BluetoothOPPServiceJni( 2068): initOppNative(L411): mOppCallbacksObj 1049850
D/BluetoothOPPServiceJni( 2068): initOppNative(L413): calling OPP init
I/bt-btif ( 2068): btif_opp_init
D/bt-btif ( 2068): btif_enable_service: current services:0xa0558330
D/BluetoothOPPServiceJni( 2068): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 2068): initOppNative(L430): mOppCallbacksObj 1049850
V/OppService( 2068): setOppService(): set to: com.broadcom.bt.service.opp.OppService@152936ac
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
V/OppService( 2068): pendingUpdate is :  true
D/HeadsetStateMachine( 2068): Proxy object connected
D/LGBluetoothHfpAdapter( 2068): [BTUI] queryPhoneState
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
V/OppService( 2068): Deleted complete outbound shares, number =  0
D/BluetoothA2dp( 2068): Proxy object connected
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
D/LGBluetoothPowerControlManager( 2068): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@134a1f7b
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetPhoneState( 2068): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 2068): Disconnected process message: 11, size: 0
,D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@20491198 on behalf of 
V/OppService( 2068): Deleted complete inbound failed shares, number = 0
D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 2068): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 2068): update too frequent, put in queue
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@3608fdf1 on behalf of 
V/OppService( 2068): pendingUpdate is :  false
E/OppService( 2068): UpdateThread is Completed
D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 2068): [BTUI] SIM Extra State :ABSENT
,D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothPbapReceiver( 2068): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2068): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2068): ***********state = 11
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2068): Handler(): got msg=1
,D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2068): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 2068): new notify threadi!
,V/BluetoothOppNotification( 2068): send delay message
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - Message: 1
D/BluetoothAdapterService(1054346006)( 2068): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 2068): isTurningOnRadio()=false
D/BluetoothAdapterState( 2068): isTurningOffRadio()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2068): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2068): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(1054346006)( 2068): onProfileServiceStateChange() - All profile services started.
V/OppService( 2068): ContentObserver received notification
D/BluetoothAdapterState( 2068): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2068): enable
I/bt-btif ( 2068): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 2068): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
,V/OppService( 2068): ContentObserver received notification
I/GKI_LINUX( 2068): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 2068): init
I/bt_vendor( 2068): init
I/bt_vnd_conf( 2068): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,D/BluetoothPermissionRequest( 5545): onReceive
D/LGBluetoothFeatureConfig( 5545):  get() - isFeatureLoaded : false
I/bt_vnd_conf( 2068): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btu  ( 2068): btu_task pending for preload complete event
V/OppService( 2068): pendingUpdate is :  true
I/bt-btif ( 2068): libbt-hci init returns 0
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@1899bdd6 on behalf of 
V/OppService( 2068): pendingUpdate is :  false
E/OppService( 2068): UpdateThread is Completed
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@3ad13857 on behalf of 
V/BluetoothOppNotification( 2068): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@3489af44 on behalf of 
V/BluetoothOppNotification( 2068): outbound: succ-0  fail-0
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ccb1278:true
I/NotificationManager( 2068): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
,V/BluetoothOppNotification( 2068): outbound notification was removed.
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@249e882d on behalf of 
V/BluetoothOppNotification( 2068): inbound: succ-0  fail-0
I/NotificationManager( 2068): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 2068): inbound notification was removed.
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@24cbe162 on behalf of 
,V/BluetoothSapReceiver( 2068): [BTUI] checkServiceStart
,D/LGBluetoothStateChangeReceiver( 2068): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/Tethering(  839): sendTetherStateChangedBroadcast 1, 0, 0
I/bt_userial_vendor( 2068): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 2068): userial_vendor_open():UART is setup
I/bt_userial_vendor( 2068): device fd = 70 open
,E/wpa_supplicant( 5535): USIM:  scard_init function
,D/bt_hwcfg( 2068): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 2068): hw_config_cback state=1
I/wpa_supplicant( 5535): rfkill: Cannot open RFKILL control device
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 9
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 4
D/PCSuite ( 5580): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 2068): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 2068): hw_config_cback state=4
D/bt_hwcfg( 2068): Chipset Name: BCM4334B0
D/bt_hwcfg( 2068): Chipset BCM4334B0
D/bt_hwcfg( 2068): Target name = [BCM4334B0]
,I/bt_hwcfg( 2068): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 2068): hw_config_cback state=2
I/ActivityManager(  839): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5610 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 2068): hw_config_cback state=3
,I/bt_hwcfg( 2068): bt vendor lib: set UART baud 4000000
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  839): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/UsbSettingsReceiver( 5545): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5545): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5545): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5545): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5545): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/wpa_supplicant( 5535): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 2068): hw_config_cback state=5
,D/UsbSettingsControl( 5545): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 5545): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5545): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5545): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5545): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5545): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 5545): [AUTORUN] setTetherStatus() : status=false
,I/wpa_supplicant( 5535): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiStateMachine(  839): MAC Addr from driver = a0:39:f7:70:12:80
,D/WifiOffDelayIfNotUsed(  839): setPowerSaveActivated(false)
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.136 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiServerServiceExt(  839): WIFI_STATE_CHANGED_ACTION [3]
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiServerServiceExt(  839): batteryPsActivateMsgHandler : state:0 event:3
E/WifiServerServiceExt(  839): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5545): remove : truetruetrue
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
W/ResourcesManager( 5610): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
E/WifiConfigStore(  839): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WifiStateMachine(  839): enableVerboseLogging : level 2
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WifiStateMachine(  839): Setting OUI to DA-A1-19
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WifiNative-HAL(  839): Setting external_sim to 1
I/WifiNative-HAL(  839): startHal
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
E/wifi    (  839): getStaticLongField sWifiHalHandle 0x9a1b08ec
I/WifiHAL (  839): Initializing wifi
I/WifiHAL (  839): Creating socket
D/WfdsService( 1816): Supplicant Connection state is changed : true
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WfdsService( 1816): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1816): Set the WFDS Monitor: true
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiHAL (  839): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  839): Did set static halHandle = 0x9da2c180
D/wifi    (  839): halHandle = 0x9da2c180, mVM = 0xb487c280, mCls = 0x801be2
E/wifi    (  839): getStaticLongField sWifiHalHandle 0x9a1b089c
D/wifi    (  839): array field set
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiNative-HAL(  839): interface[0] = wlan0
I/WifiNative-HAL(  839): interface[1] = p2p0
D/WfdsMonitor( 1816): WfdsMonitorThread create
D/WfdsMonitor( 1816): WFDS Monitor is created and started
D/WfdsService( 1816): WiFi: Supplicant connection re-established
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/wifi    (  839): setting scan oui 0x9d99a328
D/WifiHAL (  839): Sending mac address OUI
E/WifiHAL (  839): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  839): Setting OUI to DA-A1-19
I/WifiNative-HAL(  839): startHal
D/wifi    (  839): setting scan oui 0x9d99a328
D/WifiHAL (  839): Sending mac address OUI
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
E/WifiHAL (  839): failed to set scanning mac OUI; result = -95
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiNative-HAL(  839): Waiting for HAL events mWifiHalHandle=-1650278016
D/wifi    (  839): waitForHalEvents called, vm = 0xb487c280, obj = 0x801be2, env = 0xaaf02160
E/wifi    (  839): getStaticLongField sWifiHalHandle 0x989f9b2c
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WifiHS20(  839): hidePasspointNotification off =false
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/CtrlSupplicant( 1816): Access OK "@android:wpa_wlan0"
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/CtrlSupplicant( 1816): Succeed to open control connection
E/CtrlSupplicant( 1816): Succeed to open monitor connection
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
D/WfdsMonitor( 1816): Supplicant connection established
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WfdsService( 1816): Connected to the supplicant for wfds
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.204 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5610): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/LGWifiP2pService(  839): P2pDisabledState{ when=-3ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 2068): hw_config_cback state=6
D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring up p2p0
D/WifiMonitor(  839): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  839): P2pEnablingState
D/LGWifiP2pService(  839): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2p socket connection successful
D/LGWifiP2pService(  839): P2pEnabledState
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/AuthorizationBluetoothService( 1742): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WifiScanningService(  839): SCAN_AVAILABLE : 3
D/RttService(  839): SCAN_AVAILABLE : 3
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiScanningService(  839): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  839): startHal
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
W/Settings( 4975): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/RttService(  839): DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/wifi    (  839): getting scan capabilities on interface[0] = 0x9d99a328
D/WifiHAL (  839): Creating message to get scan capablities; iface = 24
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/wifi    (  839): failed to get capabilities : -95
D/LGWifiP2pService(  839): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  839): before postfix = G3s-1
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WifiServerServiceExt(  839): postfix byte check : 5
E/WifiScanningService(  839): could not get scan capabilities
D/LGWifiP2pService(  839): after postfix = G3s-1
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiServerServiceExt(  839): set CMD_ADD_DEFAULT_PROFILE
D/WifiNative-HAL(  839): p2pGetDeviceAddress
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WifiNative-HAL(  839): p2pGetDeviceAddress returning a2:39:f7:70:12:80
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/LGWifiP2pService(  839): DeviceAddress: a2:39:f7:70:12:80
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WfdsService( 1816): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiServerServiceExt(  839): setWifiDualbandAPConnection band : 1
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WfdsService( 1816): Update P2p Interface State: 3
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
E/wpa_supplicant( 5535): nWIFIDualbandAPConnection: 1
D/LGWifiP2pService(  839): sending p2p persistent groups changed broadcast
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/LGWifiP2pService(  839): sending p2p connection changed broadcast
,I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1816): WifiP2pState is changed : true
D/WfdsService( 1816): Receive the WFDS_ENABLE Method
D/WfdsService( 1816): Set the WFDS Monitor: true
D/WfdsService( 1816): Connected to the supplicant for wfds
D/WfdsJNI ( 1816): doCommand: WFDS_SET TRUE
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/wpa_supplicant( 5535): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/LGWifiP2pService(  839): InactiveState
D/WfdsJNI ( 1816): doCommand: WFDS_GET_MAC_ADDRESS
I/WifiServerServiceExt(  839): set CMD_DISCONNECT_RSSI_LVL : -100
D/LGWifiP2pService(  839): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5535): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/LGWifiP2pService(  839): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 5535): disconnect_rssi_lvl: -100
D/WfdsJNI ( 1816): doCommand: WFDS_CLEAR_PD_INFO
D/LGWifiP2pService(  839): InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/LGWifiP2pService(  839): P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 2068): hw_config_cback state=6
D/LGWifiP2pService(  839): DefaultState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5535): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1816): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1816): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1816): selectPreferredScanChannel [6]
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/WfdsService( 1816): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WfdsService( 1816): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiServerServiceExt(  839): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5535): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
E/WifiServerServiceExt(  839): No p2p device connected
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/WifiServerServiceExt(  839): set CMD_UPDATE_DEFAULT_PROFILE
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/LGWifiP2pService(  839): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/WfdsService( 1816): isConnected: false
D/WfdsService( 1816): GroupInfoAvailable: mGroupInfo is null
W/WfdsService( 1816): DefaultState - msg [9441285] is not handled
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/wpa_supplicant( 5535): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/wpa_supplicant( 5535): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.353 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5535): wlan0: Associated with c0:ff:d4:d3:aa:48
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/wpa_supplicant( 5535): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/wpa_supplicant( 5535): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/WiFiOffLoadUpdatePriority( 5545): remove1
V/WiFiOffLoadSharedPrefsUtils( 5545): save remove
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.471 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/LocSvc_java(  839): onReceive
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.476 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WiFiOffLoadBroadcast( 5545): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5545): S: false, R: false
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.489 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.493 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/GONS    ( 1764): GONS isTestMode: false Country: 
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 2068): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Settin,g wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateSCANNING
,I/WifiServiceExtension(  839): setVHTCapabilityType  : false
I/WifiServerServiceExt(  839): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  839): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  839): setSecurityType  : 2
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.56 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.563 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
D/WifiExtManager(  839): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@14e023fd
D/ConnectivityService(  839): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Tran,sports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  839): Got NetworkAgent Messenger
I/bt_hwcfg( 2068): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2068): Settlement delay -- 100 ms
I/bt_hwcfg( 2068): Setting fw settlement delay to 100 
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  839): NetworkAgent connected
D/WifiServiceExtension( 1816): isInternetCheckAvailable return false
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
E/WifiStateMachine(  839): Start Dhcp Watchdog 1
D/DhcpStateMachine(  839): StoppedState
D/DhcpStateMachine(  839): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  839): WaitBeforeStartState
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateASSOCIATING
,D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateASSOCIATED
D/WiFiOffLoadUpdatePriority( 5545): saved SSID: "NG700"
,D/WiFiOffLoadUpdatePriority( 5545): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5545): private wpa: "NG700" 300
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServiceImplEx(  839): addOrUpdateNetwork pid=5545, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  839):  uid = 1000 SSID "NG700" nid=0
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateGROUP_HANDSHAKE
I/QCNEJ   ( 1852): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:43.656 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 2068): hw_config_cback state=2
,D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 2068): hw_config_cback state=7
I/bt_hwcfg( 2068): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2068): Setting local bd addr to F8:95:C7:87:85:54
D/bt_hwcfg( 2068): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 2068): hw_config_cback state=8
I/bt_hwcfg( 2068): vendor lib fwcfg completed
I/bt-btif ( 2068): HC preload_cb 0 [0:SUCCESS 1:FAIL]
,I/bt-btu  ( 2068): btu_task received preload complete event
I/        ( 2068): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 2068): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 2068): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 2068): BTE_InitTraceLevels -- TRC_PROTOCOL,0
E/WifiStateMachine(  839): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService(  839): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f4cbef0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f4cbef0 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  839): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  839): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  839): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  839): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  839): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateCOMPLETED
E/WifiConfigStore(  839):  key="NG700"WPA_PSK netId=0 uid=0/1000
E/WifiConfigStore(  839): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5545):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5545): configuration updated: 0
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateCOMPLETED
,I/WifiServerServiceExt(  839): set CMD_UPDATE_DEFAULT_PROFILE
D/WiFiOffLoadUpdatePriority( 5545): configuration saved: true
,D/PCSuite ( 5580): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/bt-btif ( 2068): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 2068): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 2068): warning : media task started media_task_refcnt 1 
W/bt-smp  ( 2068): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2068): Plain text(LSB ~ MSB) = 53 04 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2068): Encrypted text(LSB ~ MSB) = e9 8d 87 7d 91 84 e0 36 ef 53 cb 24 79 7c ee 87 
W/bt-btm  ( 2068): Stopping oneshot timer
V/BluetoothOppNotification( 2068): new notify threadi!
V/BluetoothOppNotification( 2068): send delay message
E/bt-btif ( 2068): Calling BTA_HhEnable
E/bt-btif ( 2068): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 2068): HAL bt_hal_cbacks->adapter_properties_cb
I/ActivityManager(  839): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5642 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/BluetoothAdapterProperties( 2068): Address is:F8:95:C7:87:85:54
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/BluetoothAdapterProperties( 2068): Name is: G3s-1
,D/BluetoothAdapterProperties( 2068): Scan Mode:20
D/BluetoothAdapterProperties( 2068): Discoverable Timeout:120
E/bt-btif ( 2068): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2068): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2068): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 2068): BTA_JvEnable
E/bt-btif ( 2068): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 2068): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 2068): init_hci_slots(L136): in
D/IOP_DB_BT( 2068): db_open: file /etc/bluetooth/iop_bt.db
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@3d4702f3 on behalf of 
D/IOP_DB_BT( 2068): db_open: db_open : handle 2690000860l, read 11046 bytes onto local cache
D/IOP_DB_BT( 2068): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/BluetoothManagerService(  839): Bluetooth Adapter name changed to G3s-1
D/IOP_DB_BT( 2068): db_query: result 1
I/        ( 2068): iop_db_open: iop_db_open status 0
E/bt-btif ( 2068): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 2068): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 2068): bta_pan_co_init
D/BluetoothManagerService(  839): Stored Bluetooth name: G3s-1
D/bte_conf( 2068): Device ID record 1 : primary
D/bte_conf( 2068):   vendorId            = 00c4
D/bte_conf( 2068):   vendorIdSource      = 0001
D/bte_conf( 2068):   product             = 13a1
D/bte_conf( 2068):   version             = 1000
D/bte_conf( 2068):   clientExecutableURL = 
D/bte_conf( 2068):   serviceDescription  = 
D/bte_conf( 2068):   documentationURL    = 
D/bte_conf( 2068): bte_load_did_conf no section named DID2.
D/BT_PROF_AUDIO( 2068): created moving average (N=100)
D/BT_PROF_AUDIO( 2068): reset rate average
W/bt-btif ( 2068): overflow 0, enter 0, exit 0
I/bt-btif ( 2068): HAL bt_hal_cbacks->adapter_state_changed_cb
V/BluetoothOppNotification( 2068): mUpdateCompleteNotification = true
E/bt-btif ( 2068): btif_hf_upstreams_evt: wrong handle = 8224 
I/bt-btif ( 2068): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 2068): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterState( 2068): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2068): ScanMode =  20
D/BluetoothAdapterProperties( 2068): State =  11
D/BluetoothAdapterProperties( 2068): mDiscoverableTimeout = 120
D/OppService( 2068): onOpcStateChange()
I/bt-btif ( 2068): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2068): ops_state_cb(L223):  ops_state_cb state:0
D/BluetoothAdapterProperties( 2068): Setting state to 12
I/BluetoothAdapterState( 2068): Bluetooth adapter state changed: 11-> 12
D/OppService( 2068): onOpsStateChange() :0
I/bt-btif ( 2068): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothAdapterService(1054346006)( 2068): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothFTPServiceJni( 2068): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 2068): onFtpServerEnabled: /storage
D/BluetoothManagerService(  839): Message: 60
D/BluetoothManagerService(  839): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothPanServiceJni( 2068): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 2068): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  839): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset(  839): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 2068): Entering On State
I/BluetoothAdapterState( 2068): Entering On State from state = 11
D/OppService( 2068): Recieved MESSAGE_OPC_ENABLE
D/BluetoothAdapterProperties( 2068): Scan Mode:21
D/LGBluetoothFeatureConfig( 2068): isPrivacyLogsEnabled : true
I/bt-btif ( 2068): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2068): Discoverable Timeout:120
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btse,rvice.AdapterProperties@16f27a1c
D/BluetoothAdapterService(1054346006)( 2068): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(1054346006)( 2068): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2068): [BTUI] autoConnect() : not allowed
D/OppService( 2068): Recieved MESSAGE_OPS_ENABLE
D/BluetoothHeadset( 1764): onBluetoothStateChange: up=true
D/BluetoothA2dp(  839): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1764): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 2068): [BTUI] OnState
D/LGBluetoothServiceAdapter( 2068): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 2068): [BTUI]         local_name: G3s-1
D/BluetoothA2dp( 2068): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothHeadset( 1764): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1054346006)( 2068): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(1054346006)( 2068): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2068): [BTUI] autoConnect() : not allowed
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
E/BluetoothManagerService(  839): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  839): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  839): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/LGBluetoothAPIService( 1816): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothManagerService(  839): Message: 40
D/BluetoothManagerService(  839): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1816): Message: 1
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
,I/BluetoothMapService( 2068): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1382): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/BluetoothMapService( 2068): STATE_ON
D/LGBluetoothAPIService( 1816): MESSAGE_BOOT_COMPLETED
D/bt_h4   ( 2068): vendor lib postload completed
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@35147bb0 on behalf of 
V/BluetoothOppNotification( 2068): outbound: succ-0  fail-0
I/NotificationManager( 2068): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 2068): outbound notification was removed.
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@31887a29 on behalf of 
V/BluetoothOppNotification( 2068): inbound: succ-0  fail-0
I/NotificationManager( 2068): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 2068): inbound notification was removed.
V/BluetoothOppProvider( 2068): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2068): created cursor android.database.sqlite.SQLiteCursor@110ab1ae on behalf of 
,W/ContextImpl( 5545): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapterService( 2068): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ed80b16
I/LGBluetoothAPIService( 1816): [BTUI] LGBluetoothAPIService Binding Success
V/BluetoothPbapService( 2068): Pbap Service onCreate
V/BluetoothPbapService( 2068): Starting PBAP service
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/LGBluetoothPbapAdapter( 2068): [BTUI] getInstance : create
V/BluetoothPbapService( 2068): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2068): state: 12
V/BluetoothMapService( 2068): Handler(): got msg=1
D/BluetoothMapMasInstance( 2068): Map Service startRfcommSocketListener
D/DhcpStateMachine(  839): DHCPV4 request on wlan0
D/LGBluetoothAPIServer( 2068): [BTUI] onCreate()
D/LGBluetoothAPIServer( 2068): [BTUI] onBind()
V/LgDhcpStateMachineHelper(  839): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  839): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/LGBluetoothAPIService( 1816): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1816): Message: 100
D/LGBluetoothAPIService( 1816): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 2068): Handler(): got msg=1
V/BluetoothPbapService( 2068): Pbap Service startRfcommSocketListener
V/BluetoothPbapReceiver( 2068): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2068): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2068): ***********state = 12
D/BluetoothMapMasInstance( 2068): MAS initSocket()
D/BluetoothMapMasInstance( 2068):   masId = 00
D/BluetoothMapMasInstance( 2068):   msgTypes = 0e
D/BluetoothMapMasInstance( 2068):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2068):   SDP string = 000eSMS/MMS
,I/dhcpcd  ( 5666): version 5.5.6 starting
D/BluetoothManagerService(  839): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/dhcpcd  ( 5666): get_duid: Read-only file system
V/BluetoothPbapService( 2068): Pbap Service initSocket
D/BluetoothManagerService(  839): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/LocalBluetoothProfileManager( 5545): Adding local A2DP profile
,D/BluetoothManagerService(  839): Message: 30
W/BluetoothAdapter( 2068): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 2068): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 5545): Adding local HEADSET profile
,D/BluetoothManagerService(  839): Message: 30
I/bt-btif ( 2068): BTA_JvCreateRecordByUser
I/bt-btif ( 2068): BTA_JvRfcommStartServer
I/bt-btif ( 2068): BTA_JvCreateRecordByUser
D/LGBluetoothServiceAdapter( 2068): [BTUI] createSocketChannel FD=81 mFd=0
I/bt-btif ( 2068): BTA_JvRfcommStartServer
V/BluetoothPbapService( 2068): Succeed to create listening socket 
V/BluetoothPbapService( 2068): Accepting socket connection...
D/LGBluetoothServiceAdapter( 2068): [BTUI] createSocketChannel FD=85 mFd=81
V/BluetoothMapMasInstance( 2068): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2068): Accepting socket connection...
D/BluetoothManagerService(  839): Message: 30
D/BluetoothManagerService(  839): Message: 30
,I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 6
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocalBluetoothProfileManager( 5545): Adding local MAP profile
D/BluetoothMap( 5545): Create BluetoothMap proxy object
D/BluetoothManagerService(  839): Message: 30
D/BluetoothManagerService(  839): Message: 30
,D/LocalBluetoothProfileManager( 5545): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 2068): Pbap Service onBind
D/LGBluetoothUserBindClient( 5545): [BTUI] initUserBindClient
W/ContextImpl( 5545): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 5545): finishStartingService: stopping service
D/BluetoothA2dp( 5545): Proxy object connected
,D/A2dpProfile( 5545): Bluetooth service connected
I/dhcpcd  ( 5666): wlan0: broadcasting for a lease
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothHeadset( 5545): Proxy object connected
D/HeadsetProfile( 5545): Bluetooth service connected
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothInputDevice( 5545): Proxy object connected
D/HidProfile( 5545): Bluetooth service connected
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothPan( 5545): BluetoothPAN Proxy object connected
D/PanProfile( 5545): Bluetooth service connected
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
,D/BluetoothMap( 5545): Proxy object connected
D/MapProfile( 5545): Bluetooth service connected
D/BluetoothMap( 5545): getConnectedDevices()
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
V/BluetoothMapService( 2068): getConnectedDevices()
D/BluetoothPbap( 5545): Proxy object connected
D/PbapServerProfile( 5545): Bluetooth service connected
D/LGBluetoothUserBindClient( 5545): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5545): onReceive
D/LGBluetoothFeatureConfig( 5545): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5545): [BTUI] FileNotFound: readProperty
,D/LGDMClient( 5642): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5642): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/BluetoothOppReceiver( 2068): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
W/ContextImpl( 5642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/BluetoothOppManager( 2068): restoreApplicationData! falsefalsenullnull
,V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothSapReceiver( 2068): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 2068): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
D/AuthorizationBluetoothService( 1742): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LGDMClient( 5642): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
I/PCSuite ( 5580): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGDMClient( 5642): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/PCSuite ( 5580): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5580): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 5642): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  839): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5691 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 23.438ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.439ms
I/dhcpcd  ( 5666): wlan0: offered 192.168.1.134 from 192.168.1.1
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.755ms
W/ResourcesManager( 5691): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/dhcpcd  ( 5666): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5666): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14ab8767:true
,D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
I/ActivityManager(  839): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5727 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,V/[BNRBootReceiver]( 5727): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5727): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5727): Boot Receiver Return
,V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
I/ActivityManager(  839): Killing 5252:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  839): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  839): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  839): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  839): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
W/libprocessgroup(  839): failed to open /acct/uid_10014/pid_5252/cgroup.procs: No such file or directory
V/LgDhcpStateMachineHelper(  839): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  839): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  839): bShouldSendDhcpAction Result: true
D/LGWifiP2pService(  839): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  839): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  839): RunningState
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine(  839): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WiFiOffLoadBroadcast( 5545): Not supported operator for automatic switch
D/ConnectivityService(  839): ignoring duplicate network state non-change
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1816): isInternetCheckAvailable return false
D/WifiServiceExtension( 1816): isInternetCheckAvailable return false
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  839): Adding iface wlan0 to network 100
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:44.598 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  839): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:44.619 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  839): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  839): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:44.629 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1852): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:44.633 DNS addrs= 192.168.1.1, 0.0.0.0, 
E/ConnectivityService(  839): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  839): Adding Route [fe80::/64 -> :: wlan0] to network 100
I/QCNEJ   ( 1852): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = true, mWifiLevel = 3
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  839): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  839): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityService(  839): addLocalRoutetoDefaultNetwork
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  839): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  839): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
I/[SystemUI]StatusBar.NetworkController( 1382): mWifiConnected = true, mWifiLevel = 3
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1382): Remote
D/Nat464Xlat(  839): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  839): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  839): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  839):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  839): currentScore = 0, newScore = 20
D/ConnectivityService(  839):    accepting network in place of null
,V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  839): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1764): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] Start DNSResolver start to wait
D/TelephonyNetworkFactory-1( 1764):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  839): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  839): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    (  839): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/WIFI    (  839):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  839): [e] list.add(nai) empty : false size: 1
D/Tethering(  839): MasterInitialState.processMessage what=3
D/ConnectivityService(  839): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/DSQN    (  839): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService(  839): validation of new default Network = false
W/QCNEJ   ( 1852): |CORE| No family connected
I/QCNEJ   ( 1852): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  839): Default network via Wi-Fi connected. start DSQN
I/QCNEJ   ( 1852): |CORE| sendDefaultNwMsg: default = 1
D/DSQN    (  839): enableDataServiceNotify 
D/DSQN    (  839): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] wait 500ms before dns check
D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
,V/NetworkPolicy(  839): [LG_RESTRICTED] checkMobilePolicy_type()
,V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1382): null signal icon name: drawable/stat_sys_signal_null
D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
D/ConnectivityService(  839): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]LGNetworkController( 1382): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1382): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 5762): DSQN samuel.seo ver 141203
E/DSQN    ( 5762): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5762): created command queue thread
I/DSQN    ( 5762): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5762): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5766 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
D/ConnectivityService(  839): identical MTU - not setting
D/Nat464Xlat(  839): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  839): enableDataServiceNotify 
D/DSQN    (  839): start dsqn bin
D/DSQN    (  839): dsqn is running restart
,V/LGMDMManager( 5691): Create singleton instance
I/DSQN    ( 5772): DSQN samuel.seo ver 141203
E/DSQN    ( 5772): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5772): created command queue thread
,I/DSQN    ( 5772): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5772): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityManager.CallbackHandler( 1382): CM callback handler got msg 524295
,I/QCNEJ   ( 1852): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:44.945 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/AudioManager( 5691): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5766): Quickset Services start...
I/UEI.SmartControl( 5766): Manufacture = LGE
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 5766): File observer start...
E/UEI.SmartControl( 5766): IR Port is disabled: false
D/UEI.SmartControl( 5766): Starting file observer...
D/UEI.SmartControl( 5766): Extracting JNI libs...
D/UEI.SmartControl( 5766): --- this system supports 32-bit or 64-bit only
,D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
I/PCSuite ( 5580): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5580): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5545): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5545): MCCMNC not supported: null
I/PCSuite ( 5580): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5580): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/UEI.SmartControl( 5766): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5766): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5766): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5766): --- Selecting new region: 2
I/UEI.SmartControl( 5766): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5766): Platform has CIR...
D/UEI.SmartControl( 5766): NO CIR support, need to check package...
I/UEI.SmartControl( 5766): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5766): QS Service created
E/UEI.SmartControl( 5766): QS start get config
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] DNSResolver start dns
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 5766): Loading JNI Libs...
,D/UEI.SmartControl( 5766):  configuring local db...
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  839): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Checking http://clients3.google.com/generate_204 on "NG700"
,V/AudioFlinger(  284): thread 0xb56eb000 type 0 TID 1292 going to sleep
,V/AudioFlinger(  284): thread 0xb5651000 type 0 TID 1291 going to sleep
V/AudioFlinger(  284): thread 0xb5735000 type 0 TID 1294 going to sleep
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 5772): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 5772): restart monitoring
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5772): dsqn report finish
D/DSQN    (  839): DSQM DsqnNotification wlan0  1
D/DSQN    (  839): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Dec 2015 11:11:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449832305344], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449832305326]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1816): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Validated
D/ConnectivityService(  839): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  839): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  839):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  839): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  839): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  839): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1382): CM callback handler got msg 524290
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  839): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyNetworkFactory-1( 1764): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1764):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1382): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1382): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 5766):  ---- Has DB8: true
,D/UEI.SmartControl( 5766): QS start statue = true Error code = 0
D/UEI.SmartControl( 5766): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5766): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5766): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5766): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5766): IrrcClient ++ 
D/irrcClient( 5766): getIrrcService ++ 
D/irrcClient( 5766): getIrrcService -- 
D/irrcClient( 5766): IrrcClient -- 
W/irrc_jni( 5766): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5766): Services init done
,I/UEI.SmartControl( 5766): Device manager: loading config....
D/UEI.SmartControl( 5766): QS Service init finished
D/UEI.SmartControl( 5766): QS Service version name: 0.1.73
D/UEI.SmartControl( 5766): Config is loaded...
D/UEI.SmartControl( 5766): QS Service version code: 1073
D/UEI.SmartControl( 5766): Service requested: Control
D/UEI.SmartControl( 5766): Internal service binding...
D/UEI.SmartControl( 5766): -----IControl: 11
,D/UEI.SmartControl( 5766): Caller: com.lge.qremote
D/UEI.SmartControl( 5766): ------------ IControl registerCallback...
I/UEI.SmartControl( 5766): Registering callback...
D/UEI.SmartControl( 5766): -----IControl: 19
D/UEI.SmartControl( 5766): Caller: com.lge.qremote
I/UEI.SmartControl( 5766): Registering Services Ready callback...
I/UEI.SmartControl( 5766): Notify client services are ready...
D/UEI.SmartControl( 5766): -----IControl: 8
,D/UEI.SmartControl( 5766): Caller: com.lge.qremote
I/AudioManager( 5691): getMode name:com.lge.qremote
I/ActivityManager(  839): Killing 5374:com.google.android.gms:car/u0a6 (adj 15): empty #11
,D/UEI.SmartControl( 5766):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5766): Notify AllClients services are ready: 0
I/ActivityManager(  839): Killing 5339:com.google.process.gapps/u0a6 (adj 15): empty #12
,W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_5374/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_5339/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AudioManager( 5691): getMode name:com.lge.qremote
I/AudioManager( 5691): getMode name:com.lge.qremote
,I/QCNEJ   ( 1852): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1852): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-11 12:11:46.677 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
,I/jxcore-log( 5417): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 5417): 
V/WifiInternetCheck(  839): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1382): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  839): onReceive
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
,D/LocSvc_java(  839): got connectivity action
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  839): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  839): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  839): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  839): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  839): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  839): Sending msg: 5 arg1:0 arg2:1
D/GpsLocationProvider(  839): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out(  839): propertyValue:false
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  839): propertyValue:false
I/ActivityManager(  839): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5821 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  839): NTP server returned: 1449832308228 (Fri Dec 11 12:11:48 GMT+01:00 2015) reference: 108333 certainty: 9 system time offset: 399
D/AlarmManagerService(  839): Setting time of day to sec=1449832308
W/AlarmManagerService(  839): Unable to set rtc to 1449832308: Invalid argument
D/LocSvc_java(  839): Sending msg: 10 arg1:0 arg2:1
D/NetworkChangeNotifierAutoDetect( 1965): Network connectivity changed, type is: 2
,D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
,I/[SystemUI]Clock( 1382): onReceive = android.intent.action.TIME_SET
D/WeatherService( 2690): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:11:48
D/WeatherService( 2690): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2690): 2 : This is isUpdating : false
D/WeatherService( 2690): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2690): 2 : buildUpdate, appWidgetId: 2
,I/LgeClockWidgetControlView( 1382): time changed, timezoneChanged : false
D/WeatherTheme( 2690): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2690): 2 : Fixed theme : optimus
D/WeatherReflect( 2690): 2 : Map key string is -2
,D/lim     ( 2690): 2 : time = 12:11
I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5847 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ActivityManager(  839): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,I/WeatherReflect( 2690): Model Name : LG-D722
D/WeatherTheme( 2690): 2 : exactly same view!
,D/WeatherTheme( 2690): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2690): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:11:48
I/ActivityManager(  839): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5864 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/GpsLocationProvider(  839): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 5864): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5864): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5864): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 5847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5847): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5847): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]LGDateChangeReceiver( 1890): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=11 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 1890): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 11
,I/[LGHome]LGCalendarIcon( 1890): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 11
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/GpsLocationProvider(  839): No APN found to select.
D/LgeGpsConstants(  839): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
I/AppConfig( 5864): Total System Memory = 906309632
,I/GalleryUtils( 5864): Application Heap = 96 MB
I/AppConfig( 5864): App Tier : NOT_DEF
,D/SystemHelper( 5864): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  839): Process com.google.android.talk (pid 4975) has died
,I/GoogleURLConnFactory( 1742): Using platform SSLCertificateSocketFactory
,I/NotificationManager(  839): android: cancelAsUser(-1597574061) by android
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out(  839): propertyValue:false
I/ActivityManager(  839): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5890 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/LGEmail ( 5847): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LgeGpsLocationProvider(  839): NTP server: europe.pool.ntp.org
D/LgeGpsLocationProvider(  839): NTP server returned: 1449832308962 (Fri Dec 11 12:11:48 GMT+01:00 2015) reference: 108940 certainty: 47 system time offset: 129
,D/LGEmail ( 5847): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/MusicStore( 5821): Database version: 120
,I/GservicesProvider( 5890): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 5890): GMS http client unavailable, use old client
I/art     (  839): Explicit concurrent mark sweep GC freed 73867(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.576ms total 232.639ms
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager(  839): android: cancelAsUser(-1816247584) by android
,I/GoogleHttpClient( 5890): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5890): GMS http client unavailable, use old client
,E/ActivityThread( 3981): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 39570, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  839): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 141969, reason: UserStart
I/NotificationManager(  839): android: cancelAsUser(716319171) by android
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5821): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  839): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5931 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  839): Process com.android.vending (pid 4916) has died
,I/PhenotypeConfigurator( 1742): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out(  839): propertyValue:false
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  839): propertyValue:false
E/Auth.Api.Credentials( 3981): [CredentialSyncAdapter] Unknown sync event.
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5821): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5821): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/WifiInternetCheck(  839): isHttpConnectionAvailable - We got a valid response : 204
,I/NotificationManager(  839): android: cancelAsUser(-591465577) by android
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1742): propertyValue:false
D/ALBootInit( 5931): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 5931): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5931): [setNextAlert] start
W/ResourcesManager( 5821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Alarms  ( 5931): [setNextAlert] (1)
,D/Alarms  ( 5931):  minTime  = 0
D/Alarms  ( 5931):  -- OK multi -- 0
E/jeny.kim( 5931): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5931): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/NotificationManager(  839): android: cancelAsUser(-1816247584) by android
,E/ConnectivityChangeReceiver( 3981): Ignoring connectivity change
,I/CommonUtil( 5931): BUILD Operator: OPEN
D/Alarms  ( 5931): broadcastToWidgetProvider : false
D/Alarms  ( 5931): Enter formatDayAndTime(final Context context, long timeInMiliSec)
I/NotificationManager(  839): android: cancelAsUser(-1597574061) by android
,V/JNIHelp ( 5821): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  839): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): dumpNetworkRequest
D/ConnectivityService(  839):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  839):     Requests:
D/ConnectivityService(  839):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839):     Lingered:
D/ConnectivityService(  839): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  839): apparently satisfied.  currentScore=60
D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 3981): CM callback handler got msg 524290
I/ActivityManager(  839): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5962 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/SettingsProvider(  839): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 5931): onReceive: android.intent.action.TIME_SET
I/NotificationManager(  839): android: cancelAsUser(-591465577) by android
V/DigitalAppWidgetProvider( 5931): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@250eccd8
V/DigitalAppWidgetProvider( 5931): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@250eccd8
,D/QuickCoverProvider( 5931): onReceiver
,W/ActivityThread( 5821): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5821): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@233ae547: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5821): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  839): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=5979 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidMusic( 5821): GMSCore installation verified
,I/ConfigStore( 5821): Config Database version: 1
,W/ResourcesManager( 5979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Process com.lge.bnr (pid 5727) has died
,D/CalendarApplication( 5979): CalendarApplication.onCreate()
D/PreferenceKeysParser( 5979): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 5979): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3bc7389f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@110dbdec, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@33ff5b5, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1e16f44a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@970bfbb, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@250eccd8, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@10c73831, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3ed80b16, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3e619c97, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@10fde84, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@27a6266d, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@26c1c2a2, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@35196b33, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@36ee5ef0, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@220bbc69, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@349d66ee, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2675878f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@16f27a1c, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@341ab625, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@187d03fa, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@11cd0dab, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@bbb1c08, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@37658fa1, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3f8765c6, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@accd987, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@8e9f0b4, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@322a84dd, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@30841852, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@9138723, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@388f6420, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@164f91d9, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2527679e, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@158d727f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1356a24c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@341e7295, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2c1e5faa, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3190b79b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@f719738, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc0a311, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1fdacc76, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@13b93277, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1244ee
D/GeneralP,referenceUtils( 5979): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5979): [init]
,I/Config  ( 5979): LGCalendar ver.4.40.17
I/Config  ( 5979): start check model
I/Config  ( 5979): start check native_ca
I/Config  ( 5979): Config Operator=OPEN, Country=EU
D/Config  ( 5979): [setDefaultValuesToPref]
D/Config  ( 5979): [parseProfiles]
D/ProfilesParser( 5979): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5979): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5979): [updateProfiletoCountryInfo]
D/GeneralPreference( 5979): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 5979): [updateWidgets] 
,I/InitNotificationRingtoneService( 5979): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5979): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,W/DriveInitializer( 3981): Awaiting to be initialized
W/DriveInitializer( 3981): Background init thread started
I/AlertUtils( 5979): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3981): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/MediaRouter( 5821): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
V/MusicLeanback( 5821): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5979): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5979): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/NetworkMonitor( 5821): type=WIFI subType= reason=null isConnected=true
,W/DriveInitializer( 3981): Background init thread ended
,I/ActivityManager(  839): Process com.lge.lgdmsclient (pid 5642) has died
,I/AlertUtils( 5979): set default noti to content://media/internal/audio/media/38
W/HolidayIntentService( 5979): onHandleIntent
D/MonthWidgetProvider( 5979): [onReceive]
D/CalendarWidgetProvider( 5979): [onReceive]
D/CalendarWidgetProvider( 5979): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 5979): readJsonAsset : holiday.json
I/InitNotificationRingtoneService( 5979): End InitializeAlertRingtoneService.onHandleIntent
D/CalendarTypeController( 5979): [onUpdateAndInitCalendarTime]
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/HolidayIntentService( 5979): onHandleIntent:holiday data empty
I/ActivityManager(  839): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6022 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{537e4a6 type 0 when 1449832310182 com.android.vending} when 1449832310182
I/ActivityManager(  839): Process com.lge.settings.easy (pid 5610) has died
,D/WeekWidgetProvider( 5979): [onReceive]
D/CalendarWidgetProvider( 5979): [onReceive]
D/CalendarWidgetProvider( 5979): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5979): [onUpdateAndInitCalendarTime]
,D/WeatherAncestor( 2690): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:11:50
,D/UpdateThreadPoolManager( 2690): 2 : This is isUpdating : false
D/Weather_cast( 2690): 2 : set auto-update time : 12/11 15:11
,D/WeatherAncestor( 2690): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:11:50
D/WeatherService( 2690): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
I/ActivityManager(  839): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6046 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2690): 2 : Utils getTopActivity com.lge.launcher2 / true
W/PhenotypeConfigurator( 1742): Server returned 404
D/WeatherService( 2690): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2690): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 346us total 31.967ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 27.044ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 31.648ms
,I/NotificationManager(  839): android: cancelAsUser(353845882) by android
I/NetworkMonitor( 5821): type=WIFI subType= reason=null isConnected=true
,D/TimeService( 6046): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832310586
,D/        ( 6046): TimeServiceNative: User Time to be set is 1449832310586
D/QC-time-services( 6046): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6046): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6046): Lib:time_genoff_operation: pargs->ts_val = 1449832310586
D/QC-time-services( 6046): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  361): Daemon: Connection accepted:time_genoff
D/QC-time-services(  361): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832310586
D/QC-time-services(  361): Daemon:genoff_opr: Base = 2, val = 1449832310586, operation = 0
D/QC-time-services(  361): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/23/70 15:13:36
D/QC-time-services(  361): Daemon:Value read from RTC seconds = 9731616000
D/QC-time-services(  361): Daemon:new time 1449832310586 
D/QC-time-services(  361): Daemon: delta 1440100694586 genoff 1440100694586 
D/QC-time-services(  361): Daemon:genoff_persistent_update: Writing genoff = 1440100694586 to memory
D/QC-time-services(  361): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  361): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  361): Updating the TOD offset
D/QC-time-services(  361): Daemon:genoff_persistent_update: Writing genoff = 1440100694586 to memory
D/QC-time-services(  361): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  361): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  361): Daemon:Update to modem bit set
E/QC-time-services( 6046): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  361): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  361): Daemon: Base = 2, Value being sent to MODEM = 1124135894586
E/QC-time-services(  361): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  361): Daemon: Time-services: Waiting to acceptconnection
I/CheckinService( 3981): Checkin interval check for package: unspecified last checkin: 1449796230071 min interval config: 0 actual interval: 36080567
,D/eas_req ( 5847): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/art     (  839): Explicit concurrent mark sweep GC freed 26073(1257KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.144ms total 242.351ms
,I/art     ( 5890): Explicit concurrent mark sweep GC freed 8164(413KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 840us total 53.155ms
,I/ActivityManager(  839): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6071 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GHttpClientFactory( 5821): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/HubEmail( 5847): JNI_OnLoad()
I/HubEmail( 5847): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5847): registerNatives()
I/HubEmail( 5847): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5847): registerNativeMethods()
I/HubEmail( 5847): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5847): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/GoogleURLConnFactory( 5821): Using platform SSLCertificateSocketFactory
W/Settings( 5847): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6071): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/Finsky  ( 6022): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/LGDMClient( 6071): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/UEI.SmartControl( 5766): Internal timer expired: 1
D/LGDMClient( 6071): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6071): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6071): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6105 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/LGDMClient( 6071): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  839): Process com.android.settings (pid 5545) has died
,W/ContextImpl( 6071): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6071): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6071): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6071): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6071): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6071): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/VacuumService( 1742): Vacuum at: now=1449832311072 tag=VacuumService
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 5821): com.google.android.music: cancel(1061) by com.google.android.music
,D/Finsky  ( 6022): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6022): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6022): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6022): com.android.vending: cancel(-1050172287) by com.android.vending
I/NotificationManager(  839): android: cancelAsUser(-1874035846) by android
,I/AppUp4:AppBoxCP( 6105): onCreate
W/AppUp4:DB( 6105):  [AppBoxDatabaseHelper] construct
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
I/AppUp4:DB( 6105):  setFingerPrint start
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/AppUp4:DB( 6105):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6105):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6105):  SDK version = 0
I/AppUp4:DB( 6105):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6105): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6105): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6105): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6105): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6105): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6105): onReceive
I/AppUp4:CustModeStarterReceiver( 6105): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1742): propertyValue:false
D/AppUp4:CustFacade( 6105): Context : android.app.ReceiverRestrictedContext@970bfbb
D/AppUp4:CustFacade( 6105): isCustomizationCompleted : false
,D/Finsky  ( 6022): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6022): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@f719738 on behalf of 6022
I/ActivityManager(  839): Killing 5766:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/Ads     ( 6022): Skipping gmscore version check
I/NotificationManager(  839): android: cancelAsUser(353845882) by android
W/System.err( 5691): android.os.DeadObjectException
,W/System.err( 5691): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5691): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5691): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5691): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5691): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5691): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5691): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5691): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5691): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5691): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5691): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5691): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5691): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5691): android.os.DeadObjectException
W/System.err( 5691): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5691): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5691): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5691): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5691): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5691): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5691): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5691): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5691): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5691): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5691): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5691): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5691): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_5766/cgroup.procs: No such file or directory
D/AppUp4:CustFacade( 6105): isSimDevice : true
,W/ActivityManager(  839): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/AppUp4:CustModeStarterReceiver( 6105): begin check event
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AppUp4:CustModeStarterReceiver( 6105): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6105): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AppUp4:CustModeStarterReceiver( 6105): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6105): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6105): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6144 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 5580:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_5580/cgroup.procs: No such file or directory
,D/Finsky  ( 6022): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6022): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/UEI.SmartControl( 6144): Quickset Services start...
I/LgeMiscReceiver( 3072): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3072): action = android.net.conn.CONNECTIVITY_CHANGE
I/UEI.SmartControl( 6144): Manufacture = LGE
I/LgeMiscReceiver( 3072): networkInfo.isConnected() = true
D/UEI.SmartControl( 6144): File observer start...
E/UEI.SmartControl( 6144): IR Port is disabled: false
D/UEI.SmartControl( 6144): Starting file observer...
D/UEI.SmartControl( 6144): Extracting JNI libs...
D/UEI.SmartControl( 6144): --- this system supports 32-bit or 64-bit only
D/PhoneState( 3072): setPdpRejectCasuse : false
D/UEI.SmartControl( 6144): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6144): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6144): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6167 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/UEI.SmartControl( 6144): --- Selecting new region: 2
I/UEI.SmartControl( 6144): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6144): Platform has CIR...
D/UEI.SmartControl( 6144): NO CIR support, need to check package...
I/UEI.SmartControl( 6144): Model: LG-D722 uses JNI
,I/NotificationManager( 1742): com.google.android.gms: cancel(0) by com.google.android.gms
D/UEI.SmartControl( 6144): QS Service created
E/UEI.SmartControl( 6144): QS start get config
,D/Finsky  ( 6022): [730] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6022): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  839): Killing 5691:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10106/pid_5691/cgroup.procs: No such file or directory
,W/art     ( 5962): Attempt to remove local handle scope entry from IRT, ignoring
D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  279): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  279): App 10086 tries DNS query. Accept family:2 protocol:0
,D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 6144): Loading JNI Libs...
D/UEI.SmartControl( 6144):  configuring local db...
D/PhoneMonitor( 6167): Register our PhoneStateListener
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,D/MobileConnectivityChangeReceiver( 6167): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6167): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  839): Killing 5864:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10023/pid_5864/cgroup.procs: No such file or directory
,I/NotificationManager(  839): android: cancelAsUser(-1548111331) by android
V/DownloadManager( 3096): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3096): DownloadService onCreate
I/CheckinService( 3981): Checkin interval check for package: unspecified last checkin: 1449796230071 min interval config: 0 actual interval: 36081913
I/NotificationManager( 3096): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3096): in removeSpuriousFiles
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@13b93277 on behalf of 3096
D/PhoneMonitor( 6167): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6167): [loadFeatureFromXml] *** start feature loading from xml
,I/DownloadManager( 3096): in trimDatabase
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/TelephonyAutoProfiling( 6167): [parse] Load xml
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1244eee4 on behalf of 3096
V/TelephonyAutoProfiling( 6167): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6167): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/ActivityManager(  839): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6202 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/CheckinService( 3981): Checking schedule, now: 1449832312029 next: 1449796260011
I/CheckinService( 3981): active receiver: enabled
V/DownloadManager( 3096): DownloadService onStartCommand
D/UEI.SmartControl( 6144):  ---- Has DB8: true
,D/PhoneMonitor( 6167): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@16847f13 on behalf of 3096
D/UEI.SmartControl( 6144): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6144): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6144): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6144): IRRCDataComm has AudioManager!!!!.
I/CheckinService( 3981): Preparing to send checkin request
I/EventLogService( 3981): Accumulating logs since 1449830855575
,I/ActivityManager(  839): Process com.google.android.music:main (pid 5821) has died
W/irrc_jni( 6144): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6144): IrrcClient ++ 
D/irrcClient( 6144): getIrrcService ++ 
D/irrcClient( 6144): getIrrcService -- 
D/irrcClient( 6144): IrrcClient -- 
W/irrc_jni( 6144): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6144): Services init done
,I/UEI.SmartControl( 6144): Device manager: loading config....
D/UEI.SmartControl( 6144): QS Service init finished
D/UEI.SmartControl( 6144): QS Service version name: 0.1.73
D/UEI.SmartControl( 6144): QS Service version code: 1073
D/UEI.SmartControl( 6144): Service requested: Control
,D/UEI.SmartControl( 6144): Config is loaded...
V/DownloadManager( 3096): DownloadService onDestroy
,D/UEI.SmartControl( 6144):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6144): Notify AllClients services are ready: 0
I/NotificationManager( 5962): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,D/UEI.SmartControl( 6144): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6144): Service.onUnbind: IControl
D/UEI.SmartControl( 6144): Service.onDestroy
D/UEI.SmartControl( 6144): Shutdown IRRCPlayer... 
D/DrmBroadcastReceiver( 6202): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6202): 1  network is available. Sync DRM Time with NTP
W/irrc_jni( 6144): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6144): ~IrrcClient ++ 
D/irrcClient( 6144): ~IrrcClient -- 
W/irrc_jni( 6144): IRRCPlayer_nativeFinalize -- 
,D/UEI.SmartControl( 6144): Blaster closed
D/UEI.SmartControl( 6144): Blaster closed
D/UEI.SmartControl( 6144): Shut down QS...
D/UEI.SmartControl( 6144): Stopped file observer...
I/UEI.SmartControl( 6144): QS lib stop result = true
D/UEI.SmartControl( 6144): QS shutdown complete
D/WeatherAncestor( 2690): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:11:52
V/DrmService( 6202): Service onCreate
D/UEI.SmartControl( 6144): QS Service created
D/UpdateThreadPoolManager( 2690): 2 : This is isUpdating : false
D/DrmService( 6202): Received new request = 2
D/WeatherAncestor( 2690): connectivity changed - connection : true
,D/Weather_cast( 2690): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2690): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:11:52
D/WeatherService( 2690): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 6202): Start Sync process
D/DrmSntpClient( 6202): Server : 0
E/UEI.SmartControl( 6144): QS start get config
,D/libc-netbsd( 6202): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6202): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6202): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6202): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  279): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
,D/UEI.SmartControl( 6144):  configuring local db...
,I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6226 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2690): 2 : Utils getTopActivity com.lge.launcher2 / true
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 6202): propertyValue:false
D/WeatherService( 2690): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2690): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/NotificationManager(  839): android: cancelAsUser(2145784878) by android
,I/LGDrmClient( 6202): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  289): eDRM_SetDRMTime +++
,I/LGDRM   (  289): [DRM] SET TIME : YR=2015, MON=12, DAY=11
I/LGDRM   (  289): [DRM] SET TIME : HR=11, MIN=11, SEC=52
V/ILGDrmService(  289): eDRM_SetDRMTime ---
I/DrmSntpClient( 6202): Synched
,D/DrmService( 6202): Completed !! request = 2
D/DrmService( 6202): Request count = 0
V/DrmService( 6202): Service onDestroy
I/ActivityManager(  839): Killing 5931:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10010/pid_5931/cgroup.procs: No such file or directory
,W/ResourcesManager( 6226): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 3981): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 3981): Failed to find provider info for com.google.android.wearable.settings
,D/UEI.SmartControl( 6144):  ---- Has DB8: true
,D/UEI.SmartControl( 6144): QS start statue = true Error code = 0
D/UEI.SmartControl( 6144): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6144): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6144): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6144): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6144): IrrcClient ++ 
D/irrcClient( 6144): getIrrcService ++ 
D/irrcClient( 6144): getIrrcService -- 
D/irrcClient( 6144): IrrcClient -- 
W/irrc_jni( 6144): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6144): Services init done
I/UEI.SmartControl( 6144): Device manager: loading config....
D/UEI.SmartControl( 6144): QS Service init finished
D/UEI.SmartControl( 6144): QS Service version name: 0.1.73
D/UEI.SmartControl( 6144): QS Service version code: 1073
D/UEI.SmartControl( 6144): Service requested: Control
,D/UEI.SmartControl( 6144): Config is loaded...
D/UEI.SmartControl( 6144): Request IControl service: devices are loaded...
,E/ActivityThread( 6144): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@3ed80b16 that was originally bound here
E/ActivityThread( 6144): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@3ed80b16 that was originally bound here
E/ActivityThread( 6144): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6144): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6144): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6144): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6144): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6144): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6144): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6144): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6144): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6144): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6144): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6144): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6144): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6144): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6144): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6144): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6144): Internal service binding...
D/UEI.SmartControl( 6144):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6144): Notify AllClients services are ready: 0
I/art     ( 3981): Explicit concurrent mark sweep GC freed 13973(1111KB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 14MB/24MB, paused 2.160ms total 101.885ms
,I/ActivityManager(  839): Killing 5979:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10013/pid_5979/cgroup.procs: No such file or directory
,I/Babel_SMS( 6226): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6226): MmsConfig.loadMmsSettings
I/art     (  839): Explicit concurrent mark sweep GC freed 27189(1233KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.694ms total 170.757ms
,I/Babel_SMS( 6226): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6226): MmsConfig.loadFromDatabase
I/art     ( 6226): CheckpointMarkThreadRoots callback created = 0xb042d510
,E/Babel_SMS( 6226): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6226): MmsConfig.loadFromResources
E/Babel_SMS( 6226): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6226): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6226): CheckpointMarkThreadRoots callback created = 0xb042d4f0
,D/SensorManager( 6226): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6226): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6226): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6226): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6226): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6226): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6226): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6226): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6226): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6226): found sensor: LGE Significant Motion Detector Sensor, handle=47
,D/SensorManager( 6226): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6226): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6226): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6226): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6226): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6226): found sensor: Motion Accel, handle=46
,W/Settings( 6226): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6226): startup - clean
,I/Babel   ( 6226): deleted: false for 0
,I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6260 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6226): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6226): Unsupported mime audio/adpcm
W/AudioCapabilities( 6226): Unsupported mime audio/g726
W/AudioCapabilities( 6226): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6226): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6226): Unsupported mime video/mjpg
W/VideoCapabilities( 6226): Unsupported mime video/theora
W/AudioCapabilities( 6226): Unsupported mime audio/evrc
,W/AudioCapabilities( 6226): Unsupported mime audio/qcelp
W/VideoCapabilities( 6226): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6226): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6226): Unsupported mime audio/qcelp
W/AudioCapabilities( 6226): Unsupported mime audio/evrc
,W/VideoCapabilities( 6226): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6226): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6226): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6226): Unrecognized profile 2130706433 for video/avc
I/NotificationManager(  839): android: cancelAsUser(2) by android
,W/VideoCapabilities( 6226): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6226): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6226): onServiceConnected
,W/Babel   ( 6226): Attempted to change video mute state without an active call.
I/NotificationManager( 6226): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/NotificationManager( 1742): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6226): propertyValue:false
I/Babel   ( 6226): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  839): Killing 6046:com.qualcomm.timeservice/1000 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6046/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6283 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6260): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6260): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6260): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6260): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6260): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6260):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6260):   adb logcat -s GAv4
,W/ResourcesManager( 6283): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6283): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 6260): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6260): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6260): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/MultiDex( 6283): VM with version 2.1.0 has multidex support
,I/MultiDex( 6283): install
I/MultiDex( 6283): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6283): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6283): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6283): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@aed367c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6283): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6283): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6283): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6283): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6283): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6283): Install completed successfully. count=14 extracted=0
,I/WebViewFactory( 6260): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/WVCdm   (  284): Instantiating CDM.
,I/ActivityManager(  839): Process com.lge.email (pid 5847) has died
I/WVCdm   (  284): CdmEngine::OpenSession
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
I/GoogleURLConnFactory( 6283): Using platform SSLCertificateSocketFactory
,W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
I/LibraryLoader( 6260): Time to load native libraries: 4 ms (timestamps 4311-4315)
,I/LibraryLoader( 6260): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6260): Binding Chromium to main looper Looper (main, tid 1) {152936ac}
I/LibraryLoader( 6260): Expected native library version number "",actual native library version number ""
I/chromium( 6260): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/libc-netbsd( 6283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6283): propertyValue:false
I/BrowserStartupController( 6260): Initializing chromium process, singleProcess=true
W/art     ( 6260): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6260): ApplicationContext is null in ApplicationStatus
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
W/chromium( 6260): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/WVCdm   (  284): PrepareKeyRequest: nonce=2131793505
E/libEGL  ( 6260): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6260): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6260): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6260): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6260): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6260): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6260): Remote Branch: 
I/Adreno-EGL( 6260): Local Patches: 
I/Adreno-EGL( 6260): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb39b09a0, uid 10079
W/AudioManagerAndroid( 6260): Requires BLUETOOTH permission
,D/libc-netbsd( 6283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6283): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6283): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  839): Process com.lge.appbox.client (pid 6105) has died
,I/NSApplication( 6260): Starting up...
,I/art     ( 6283): CheckpointMarkThreadRoots callback created = 0xb04d4f20
,I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6344 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6283): CheckpointMarkThreadRoots callback created = 0xb04d4f10
,I/iu.SyncManager( 3981): SYNC; picasa accounts
,I/WVCdm   (  284): CdmEngine::OpenSession
,D/NetworkLogImpl( 3981): Loaded NetworkSpeedPredictor
,I/iu.Environment( 3981): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 3981): num queued entries: 0
I/iu.UploadsManager( 3981): num updated entries: 0
I/iu.SyncManager( 3981): NEXT; no task
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1742): propertyValue:false
I/ActivityManager(  839): Process com.android.vending (pid 6022) has died
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  839): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6381 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCM     ( 1742): GCM config loaded
,I/DigitalAppWidgetProvider( 6381): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2690): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:11:55
D/UpdateThreadPoolManager( 2690): 2 : This is isUpdating : false
D/Weather_cast( 2690): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2690): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:11:55
D/WeatherService( 2690): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,I/ActivityManager(  839): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6402 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2690): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.523ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.371ms
,D/WeatherService( 2690): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2690): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 324us total 20.801ms
,W/ResourcesManager( 6402): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e49c3c8:true
,D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/BluetoothAdapterService(1054346006)( 2068): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16f27a1c
D/WearableService( 1742): callingUid 10006, callindPid: 1742
,E/MDM     ( 1742): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1742): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 3981): Restart initialization of location
W/ContextImpl( 3362): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1742): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  839): Process com.uei.lg.quicksetsdk.lite (pid 6144) has died
,W/GCoreFlp( 1742): No location to return for getLastLocation()
,W/FusedLocationProvider( 1742): location=null
,I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6436 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6402): Create singleton instance
,I/AudioManager( 6402): getMode name:com.lge.qremote
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 116247480742; DSPS: 3908344; Offset : -3030696472
,I/ActivityManager(  839): Process com.google.android.apps.magazines (pid 6260) has died
,I/MusicWidget( 2665): mDelayedStopHandler : unbind
,D/UEI.SmartControl( 6436): Quickset Services start...
I/UEI.SmartControl( 6436): Manufacture = LGE
D/UEI.SmartControl( 6436): File observer start...
E/UEI.SmartControl( 6436): IR Port is disabled: false
D/UEI.SmartControl( 6436): Starting file observer...
D/UEI.SmartControl( 6436): Extracting JNI libs...
D/UEI.SmartControl( 6436): --- this system supports 32-bit or 64-bit only
,I/MusicBrowser( 2092): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2092): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2092): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2092): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2092): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2092): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2092): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  839):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@bbb1c08com.lge.music.MediaPlaybackService$6@37658fa1
,D/MusicBrowser( 2092): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3e619c97
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2092): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2092): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2092): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2092): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2092): reset
V/MediaPlayer[Native]( 2092): setListener
V/MediaPlayer[Native]( 2092): disconnect
V/MediaPlayer[Native]( 2092): destructor
V/AudioFlinger(  284): releasing 19 from 2092 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/MediaPlayer[Native]( 2092): disconnect
D/MusicBrowser( 2092): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
D/UEI.SmartControl( 6436): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6436): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6436): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/SmartShareClient( 2092): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2092): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2092): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2092): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2092): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2092): [SmartShareManagerClient] unregisterListener: 1065838022
W/SmartShareClient( 2092): [SmartShareManagerClient] unregisterListener invalid listener: 1065838022
I/SmartShareClient( 2092): [SmartShareManagerClient] terminate service: 2092/MediaPlaybackService/54523317
E/HomeCloudIF( 2092): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2092): [SmartShareManagerClient] unbindService context:android.app.Application@accd987
V/CloudHub( 2092): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2092): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2092): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2092): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2092): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2092): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
,I/UEI.SmartControl( 6436): --- Selecting new region: 2
I/UEI.SmartControl( 6436): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6436): Platform has CIR...
D/UEI.SmartControl( 6436): NO CIR support, need to check package...
,I/UEI.SmartControl( 6436): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6436): QS Service created
E/UEI.SmartControl( 6436): QS start get config
,D/UEI.SmartControl( 6436): Loading JNI Libs...
D/UEI.SmartControl( 6436):  configuring local db...
,I/WVCdm   (  284): CdmEngine::CloseSession
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=460429259
D/UEI.SmartControl( 6436):  ---- Has DB8: true
,D/UEI.SmartControl( 6436): QS start statue = true Error code = 0
D/UEI.SmartControl( 6436): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6436): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6436): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6436): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6436): IrrcClient ++ 
D/irrcClient( 6436): getIrrcService ++ 
D/irrcClient( 6436): getIrrcService -- 
D/irrcClient( 6436): IrrcClient -- 
W/irrc_jni( 6436): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6436): Services init done
,I/UEI.SmartControl( 6436): Device manager: loading config....
D/UEI.SmartControl( 6436): QS Service init finished
D/UEI.SmartControl( 6436): QS Service version name: 0.1.73
D/UEI.SmartControl( 6436): Config is loaded...
D/UEI.SmartControl( 6436): QS Service version code: 1073
D/UEI.SmartControl( 6436): Service requested: Control
D/UEI.SmartControl( 6436): Internal service binding...
D/UEI.SmartControl( 6436): -----IControl: 11
,D/UEI.SmartControl( 6436): Caller: com.lge.qremote
D/UEI.SmartControl( 6436): ------------ IControl registerCallback...
I/UEI.SmartControl( 6436): Registering callback...
D/UEI.SmartControl( 6436): -----IControl: 19
D/UEI.SmartControl( 6436): Caller: com.lge.qremote
I/UEI.SmartControl( 6436): Registering Services Ready callback...
I/UEI.SmartControl( 6436): Notify client services are ready...
D/UEI.SmartControl( 6436): -----IControl: 8
D/UEI.SmartControl( 6436): Caller: com.lge.qremote
I/art     ( 5962): CheckpointMarkThreadRoots callback created = 0xb042d410
,I/AudioManager( 6402): getMode name:com.lge.qremote
I/ActivityManager(  839): Killing 6071:com.lge.lgdmsclient/1000 (adj 15): empty #11
,D/UEI.SmartControl( 6436):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6436): Notify AllClients services are ready: 0
I/art     ( 5962): CheckpointMarkThreadRoots callback created = 0xb042d3c0
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6071/cgroup.procs: No such file or directory
,I/AudioManager( 6402): getMode name:com.lge.qremote
I/AudioManager( 6402): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/WVCdm   (  284): CdmEngine::CloseSession
,I/WVCdm   (  284): L3 Terminate.
I/dex2oat ( 6471): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=43 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6471): dex2oat took 84.094ms (threads: 4)
,I/Adreno-EGL( 6283): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6283): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6283): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6283): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6283): Remote Branch: 
I/Adreno-EGL( 6283): Local Patches: 
I/Adreno-EGL( 6283): Reconstruct Branch: 
,I/Adreno-EGL( 6283): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6283): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6283): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6283): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6283): Remote Branch: 
I/Adreno-EGL( 6283): Local Patches: 
I/Adreno-EGL( 6283): Reconstruct Branch: 
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
D/WeatherService( 2690): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:12:0
D/WeatherService( 2690): 2 : TimeTick Intent And Screen On
D/WeatherService( 2690): 2 : SDK version : 21
,W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2690): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2690): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2690): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2690): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2690): 2 : This is isUpdating : false
D/WeatherService( 2690): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2690): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2690): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2690): 2 : Fixed theme : optimus
D/WeatherReflect( 2690): 2 : Map key string is -2
,D/lim     ( 2690): 2 : time = 12:12
I/WeatherReflect( 2690): Model Name : LG-D722
D/WeatherTheme( 2690): 2 : Different view - status_min_formatted : 11 != 12
D/WeatherTheme( 2690): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2690): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2690): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2690): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2690): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2690): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2690): forecast size is 0
D/Theme   ( 2690): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2690): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2690): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2690): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2690): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
,D/Theme   ( 2690): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2690): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2690): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2690): url is : null
D/Theme   ( 2690): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2690): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2690): 2 : update view, appWidgetId: 2
D/WeatherService( 2690): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:12:0
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1890): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1890): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
,I/[SystemUI]Clock( 1382): called onTimeUpdated()
I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/Adreno-EGL( 6283): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6283): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6283): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6283): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6283): Remote Branch: 
I/Adreno-EGL( 6283): Local Patches: 
I/Adreno-EGL( 6283): Reconstruct Branch: 
,I/CheckinRequestBuilder( 3981): Classify the device as Phone.
,D/libc-netbsd( 3981): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3981): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 3981): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 3981): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 3981): propertyValue:false
D/libc-netbsd( 3981): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3981): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 3981): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3981): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 3981): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3981): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 3981): Sending checkin request (10031 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinResponseProcessor( 3981): From server: 2 gservices updates and 0 deletes
,I/GservicesProvider( 5890): main difference update completed
,I/CertBlacklister(  839): Certificate blacklist changed, updating...
I/CertBlacklister(  839): Certificate blacklist updated
,I/ActivityManager(  839): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6513 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
D/UEI.SmartControl( 6436): Internal timer expired: 1
,I/CheckinRequestBuilder( 3981): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 3981): Failed to find provider info for com.google.android.wearable.settings
,W/art     ( 6513): No such thread id for suspend: 19
,I/ActivityManager(  839): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6549 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/UpdateRequestReceiver( 6549): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinRequestBuilder( 3981): Classify the device as Phone.
E/UpdateRequestReceiver( 6549): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6549): Received malformed URL while handling Gservices.CHANGED_ACTION
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
E/UpdateRequestReceiver( 6549): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/charger_monitor(  486): init target 500000
,I/CheckinTask( 3981): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 3981): Checkin interval check for package: unspecified last checkin: 1449796230071 min interval config: 0 actual interval: 36092095
,I/art     (  839): Explicit concurrent mark sweep GC freed 23857(1105KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.784ms total 189.548ms
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/CheckinService( 3981): Checking schedule, now: 1449832322185 next: 1450359571149
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
,I/CheckinService( 3981): active receiver: disabled
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QPairHandler( 1382): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  839): Process com.android.chrome (pid 6344) has died
,I/QCNEJ   ( 1852): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]QSlideListController( 1382): onReceive = android.intent.action.PACKAGE_CHANGED
,I/GservicesUpdateTask( 1965): Updating Gservices keys
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1382): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
,I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
,I/SystemUpdateService( 3981): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
I/CheckinService( 3981): Checking schedule, now: 1449832322309 next: 1450359571149
I/CheckinService( 3981): active receiver: disabled
,D/SystemUpdateService( 3981): onCreate
D/SystemUpdateService( 3981): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 3981): cancelUpdate (empty URL)
I/SystemUpdateService( 3981): active receiver: disabled
,I/NotificationManager( 3981): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 3981): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  839): Handling package changes for user 0
,I/art     ( 1742): Explicit concurrent mark sweep GC freed 65072(4MB) AllocSpace objects, 51(839KB) LOS objects, 40% free, 13MB/23MB, paused 1.649ms total 124.293ms
,I/art     ( 5890): Explicit concurrent mark sweep GC freed 9822(487KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 1.882ms total 47.959ms
,I/art     ( 3981): Explicit concurrent mark sweep GC freed 18187(1190KB) AllocSpace objects, 13(208KB) LOS objects, 24% free, 14MB/19MB, paused 1.055ms total 82.380ms
,D/LCardEmulationManager( 1799): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1799): getDefaultRoute
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  839): Process com.google.android.apps.plus (pid 5962) has died
,I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@18a28ca9
,I/GCoreNlp( 1742): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  839): applying state to connected service
,I/art     ( 5890): Explicit concurrent mark sweep GC freed 2893(111KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 805us total 30.535ms
,D/CheckinService( 3981): Recording last checkin time for package unspecified as 1449832323138
,D/SystemUpdateService( 3981): onDestroy
,E/DynamiteModule( 3981): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 3981): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 3981): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 3981): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 3981): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 3981): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 3981): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 3981): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 3981): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 3981): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 3981): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 3981): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 3981): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 3981): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 3981): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 3981): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 3981): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 3981): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 3981): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 3981): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 3981): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 3981): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 3981): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 3981): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 3981): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 3981): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 3981): 		... 17 more
E/DynamiteModule( 3981): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 3981): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 3981): Selected local version of com.google.android.gms.flags
D/SystemEventReceiver( 3981): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 3981): Updating ocr activity enabled=false
,W/ActivityManager(  839): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 3981): Updating downloaded model state (gservices changed)
,I/ActivityManager(  839): Killing 6167:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/NotificationManager(  839): android: cancelAsUser(-591465577) by android
I/art     ( 5890): Explicit concurrent mark sweep GC freed 2860(112KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.073ms total 25.824ms
W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_6167/cgroup.procs: No such file or directory
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/GCM     ( 1742): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ActivityManager(  839): Killing 6202:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10051/pid_6202/cgroup.procs: No such file or directory
,I/GCoreUlr( 1742): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6609 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     ( 1742): Explicit concurrent mark sweep GC freed 13233(667KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 14MB/23MB, paused 2.020ms total 113.686ms
,I/GCoreUlr( 1742): DispatchingService.onCreate()
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/GeofencerStateMachine( 1742): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1742): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
E/ctxmgr  ( 1742): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
I/NotificationManager( 6226): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6226): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 6609): onCreate
,W/AppUp4:DB( 6609):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6609):  setFingerPrint start
I/AppUp4:DB( 6609):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6609):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6609):  SDK version = 0
I/AppUp4:DB( 6609):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6609): AppBoxApplication onCreate()
,W/ctxmgr  ( 1742): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
E/ctxmgr  ( 1742): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/AppUp4:CustModeStarterReceiver( 6609): onReceive
I/AppUp4:CustModeStarterReceiver( 6609): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6609): Context : android.app.ReceiverRestrictedContext@110dbdec
D/AppUp4:CustFacade( 6609): isCustomizationCompleted : false
V/JNIHelp ( 6226): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AppUp4:CustFacade( 6609): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6609): begin check event
,I/AppUp4:CustModeStarterReceiver( 6609): Event For Nothing, skip.
I/GCoreUlr( 1742): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/System  ( 6226): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6226): Installed default security provider GmsCore_OpenSSL
,V/AudioFlinger(  284): 2092 died, releasing its sessions
V/AudioFlinger(  284):  pid 1764 @ 0
V/AudioFlinger(  284):  pid 3072 @ 1
V/AudioFlinger(  284):  pid 3072 @ 2
I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6645 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  839): Process com.lge.music (pid 2092) has died
,I/GCoreUlr( 1742): Unbound from all location providers
I/GCoreUlr( 1742): Place inference reporting - stopped
I/GCoreUlr( 1742): DispatchingService.onDestroy()
I/GCoreUlr( 1742): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1742): Unbound from all location providers
I/GCoreUlr( 1742): Place inference reporting - stopped
W/ResourcesManager( 6645): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6645): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6645): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/art     ( 5890): Explicit concurrent mark sweep GC freed 2427(95KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 904us total 25.096ms
,I/AppConfig( 6645): Total System Memory = 906309632
,I/GalleryUtils( 6645): Application Heap = 96 MB
I/AppConfig( 6645): App Tier : NOT_DEF
D/SystemHelper( 6645): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  839): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6667 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 6667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6667): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6667): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6667): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6667): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6667): BUILD Country: EU
,I/SystemConfig( 6667): BUILD Operator: OPEN
,I/ActivityManager(  839): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6686 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 6381:com.lge.clock/u0a10 (adj 15): empty #11
I/ActivityManager(  839): Process com.lge.qremote (pid 6402) has died
,D/UEI.SmartControl( 6436): Service.onUnbind: IControl
D/UEI.SmartControl( 6436): Service.onDestroy
W/libprocessgroup(  839): failed to open /acct/uid_10010/pid_6381/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6436): Shutdown IRRCPlayer... 
W/irrc_jni( 6436): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6436): ~IrrcClient ++ 
D/irrcClient( 6436): ~IrrcClient -- 
,W/irrc_jni( 6436): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6436): Blaster closed
D/UEI.SmartControl( 6436): Blaster closed
D/UEI.SmartControl( 6436): Shut down QS...
D/UEI.SmartControl( 6436): Stopped file observer...
I/SystemConfig( 6667): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6667): existFile = false
I/SystemConfig( 6667): canReadFile = false
I/SystemConfig( 6667): systemFeature RCS result false
D/SystemConfig( 6667): refreshRcsSupport() :false
I/UEI.SmartControl( 6436): QS lib stop result = true
D/UEI.SmartControl( 6436): QS shutdown complete
I/LockScreenSettings( 6686): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6686): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6706 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 3096): Explicit concurrent mark sweep GC freed 5115(359KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 414us total 34.931ms
,I/art     (  839): Explicit concurrent mark sweep GC freed 29936(1569KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.832ms total 161.426ms
,I/UpdateIcingCorporaServi( 1965): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6731 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6436:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1965): UpdateCorporaTask done [took 128 ms] updated apps [took 128 ms] 
,W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_6436/cgroup.procs: No such file or directory
W/SQLiteConnectionPool( 3981): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/Finsky  ( 6731): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/Finsky  ( 6731): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6731): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6731): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6731): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@14aba349 on behalf of 6731
D/Finsky  ( 6731): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6731): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6731): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6731): Skipping gmscore version check
D/PackageBroadcastService( 3981): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 3981): Null package name or gms related package.  Ignoreing.
I/Icing   ( 3981): updateResources: need to parse f{com.google.android.gms}
D/Finsky  ( 6731): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6792 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6792): Register our PhoneStateListener
,V/SetupWizard( 6792): Connected to Gservices successfully
,I/ActivityManager(  839): Killing 6513:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,D/PhoneMonitor( 6792): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6792): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6792): [parse] Load xml
,V/TelephonyAutoProfiling( 6792): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6792): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6792): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  839): failed to open /acct/uid_10009/pid_6513/cgroup.procs: No such file or directory
D/GCM     ( 1742): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 3981): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 3981): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 3981): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  839): Killing 6549:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10003/pid_6549/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  839): Killing 6283:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_6283/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/PackageSettings(  839): Skipping PackageSetting{18326cc com.example.hello/10030} due to missing metadata
,I/[SystemUI]QPairHandler( 1382): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1852): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1382): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1382): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 6226): com.google.android.talk: cancel(8) by com.google.android.talk
I/AppUp4:CustModeStarterReceiver( 6609): onReceive
I/AppUp4:CustModeStarterReceiver( 6609): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6609): Context : android.app.ReceiverRestrictedContext@110dbdec
D/AppUp4:CustFacade( 6609): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6609): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6609): begin check event
I/AppUp4:CustModeStarterReceiver( 6609): Event For Nothing, skip.
D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/art     ( 1799): Background sticky concurrent mark sweep GC freed 84605(4MB) AllocSpace objects, 0(0B) LOS objects, 34% free, 9MB/14MB, paused 1.099ms total 116.296ms
I/UpdateIcingCorporaServi( 1965): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/administrator(  839): Handling package changes for user 0
,D/PackageBroadcastService( 3981): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 3981): Null package name or gms related package.  Ignoreing.
I/UpdateIcingCorporaServi( 1965): UpdateCorporaTask done [took 46 ms] updated apps [took 46 ms] 
,I/Icing   ( 3981): updateResources: need to parse f{com.google.android.gms}
,I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@211bac72
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1742): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  839): applying state to connected service
,D/LCardEmulationManager( 1799): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1799): getDefaultRoute
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/Icing   ( 3981): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 3981): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 136248315890; DSPS: 4563732; Offset : -3030715685
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{334def07 type 2 when 138535 android} when 138535
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29358 ms ago)
,D/qdlights(  839): set_light_backlight: 252
,D/qdlights(  839): set_light_backlight: 249
,D/qdlights(  839): set_light_backlight: 245
,D/qdlights(  839): set_light_backlight: 242
,D/qdlights(  839): set_light_backlight: 239
,D/qdlights(  839): set_light_backlight: 235
,D/qdlights(  839): set_light_backlight: 232
,D/qdlights(  839): set_light_backlight: 229
,D/qdlights(  839): set_light_backlight: 225
,D/qdlights(  839): set_light_backlight: 222
,D/qdlights(  839): set_light_backlight: 219
,D/qdlights(  839): set_light_backlight: 215
,D/qdlights(  839): set_light_backlight: 212
,D/qdlights(  839): set_light_backlight: 209
,D/qdlights(  839): set_light_backlight: 205
,D/qdlights(  839): set_light_backlight: 202
,D/qdlights(  839): set_light_backlight: 199
,D/qdlights(  839): set_light_backlight: 195
,D/qdlights(  839): set_light_backlight: 192
,D/qdlights(  839): set_light_backlight: 189
,D/qdlights(  839): set_light_backlight: 185
,D/qdlights(  839): set_light_backlight: 182
,D/qdlights(  839): set_light_backlight: 179
,D/qdlights(  839): set_light_backlight: 175
,D/qdlights(  839): set_light_backlight: 172
,D/qdlights(  839): set_light_backlight: 169
,D/qdlights(  839): set_light_backlight: 165
,D/qdlights(  839): set_light_backlight: 162
,D/qdlights(  839): set_light_backlight: 159
,D/qdlights(  839): set_light_backlight: 155
,D/qdlights(  839): set_light_backlight: 152
,D/qdlights(  839): set_light_backlight: 149
,D/qdlights(  839): set_light_backlight: 145
,D/qdlights(  839): set_light_backlight: 142
,D/qdlights(  839): set_light_backlight: 139
,D/qdlights(  839): set_light_backlight: 135
,D/qdlights(  839): set_light_backlight: 132
,D/qdlights(  839): set_light_backlight: 129
,D/qdlights(  839): set_light_backlight: 125
,D/qdlights(  839): set_light_backlight: 122
,D/qdlights(  839): set_light_backlight: 119
,D/qdlights(  839): set_light_backlight: 115
,D/qdlights(  839): set_light_backlight: 112
,D/qdlights(  839): set_light_backlight: 109
,D/qdlights(  839): set_light_backlight: 105
,D/qdlights(  839): set_light_backlight: 102
,D/qdlights(  839): set_light_backlight: 99
,D/qdlights(  839): set_light_backlight: 95
,D/qdlights(  839): set_light_backlight: 92
,D/qdlights(  839): set_light_backlight: 89
,D/qdlights(  839): set_light_backlight: 85
,D/qdlights(  839): set_light_backlight: 82
,D/qdlights(  839): set_light_backlight: 79
,D/qdlights(  839): set_light_backlight: 75
,D/qdlights(  839): set_light_backlight: 72
,D/qdlights(  839): set_light_backlight: 69
,D/qdlights(  839): set_light_backlight: 65
,D/qdlights(  839): set_light_backlight: 62
,D/qdlights(  839): set_light_backlight: 59
,D/qdlights(  839): set_light_backlight: 55
,D/qdlights(  839): set_light_backlight: 52
,D/qdlights(  839): set_light_backlight: 49
,D/qdlights(  839): set_light_backlight: 45
,D/qdlights(  839): set_light_backlight: 42
,D/qdlights(  839): set_light_backlight: 39
,D/qdlights(  839): set_light_backlight: 35
,D/qdlights(  839): set_light_backlight: 32
,D/qdlights(  839): set_light_backlight: 29
,D/qdlights(  839): set_light_backlight: 25
,D/qdlights(  839): set_light_backlight: 22
,D/qdlights(  839): set_light_backlight: 19
,D/qdlights(  839): set_light_backlight: 15
,D/qdlights(  839): set_light_backlight: 12
,D/qdlights(  839): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 156251042706; DSPS: 5219181; Offset : -3030704648
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36341 ms ago)
,I/PowerManagerService(  839): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36359 ms ago)
W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  839): Sleeping (uid 1000)...
D/LPWGController(  839): [updateScreenState] screen on = false
D/LPWGController(  839): disable proximity sensor
,D/LPWGController(  839): enable proximity sensor
I/SensorManager(  839): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3d6d1834] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  839): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  839): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  839): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  839): activate: handle is 48, enable
V/sensors_hal_Ctx(  839): activate sensors is 1400000000000
D/sensors_hal_Thresh(  839): enable: handle=48
I/sensors_hal_SAM(  839): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  839): waitForResponse: timeout=1000
V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  839): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  839): enable: Received response: 0
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36406 ms ago)
I/Adreno-EGL(  839): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  839): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  839): Build Date: 03/02/15 Mon
I/Adreno-EGL(  839): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  839): Remote Branch: 
I/Adreno-EGL(  839): Local Patches: 
I/Adreno-EGL(  839): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (142 us)
,I/Sensors (  427): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  839): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  839): processInd: handle 48, count=1
V/sensors_hal_Thresh(  839): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  839): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  839): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  839): poll: count: 256
I/sensors_hal_Ctx(  839): poll: released wakelock sensor_ind
D/sensors_hal_Util(  839): waitForResponse: timeout=0
D/LPWGController(  839): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  839): current mode = 1  value = 1 1
I/LPWGController(  839): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  839): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  839): set_light_backlight: 0,
,I/SensorManager(  839): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  839): activate: handle is 46, disable
V/sensors_hal_Ctx(  839): activate sensors is 1000000000000
D/sensors_hal_LP2(  839): enable: handle=46
D/sensors_hal_LP2(  839): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  839): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  839): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  839): Display changed displayId=0
,V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  839): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1764): Display #0 changed.
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
D/SurfaceControl(  839): Excessive delay in setPowerMode(): 196ms
I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  839): Got set_interactive hint
,D/KeyguardViewMediator( 1382): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1342): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1342): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1342): handleNotifyScreenOFF
D/KeyguardViewMediator( 1382): notifyScreenOffLocked
,D/KeyguardViewMediator( 1382): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/KeyguardViewMediator( 1382): handleNotifyScreenOff
D/WifiServerServiceExt(  839): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  839): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=on, calling pid 839
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  284): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
D/ScreenTurnOffBySensor( 1382): unregisterProximitySensor
D/StatusBarWindowView( 1382): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1382): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.SCREEN_ON
,I/ActivityManager(  839): Process com.google.android.talk (pid 6226) has died
,D/GpsLocationProvider(  839): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1852): |CORE| sendScreenState: state:true
I/LEDService( 1816): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1816): stopPatternFlashing()
D/qdlights( 1816): set_light_notifications: 0,0,0,0,3
I/LEDService( 1816): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1816): set_light_notifications: 0,0,0,0,3
I/LEDService( 1816): updateLightsLocked : turn off led
D/qdlights( 1816): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1816): RESTART MSG
,D/SplitWindow(  839): check instance of lgWin Window{45074a3 u0 SearchPanel}
,I/Sensors (  427): sns_pwr.c(301):releasing wakelock
,D/InputDispatcher(  839): Window went away: Window{1edf0342 u0 SearchPanel}
,I/[SystemUI]Clock( 1382): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1382): time changed, timezoneChanged : false
,I/Cliptray Service( 1816): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1816): lockStatus = 0
D/LNfcService( 1799): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1799): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1799): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1799): isRequireNfcCRouting() return true
D/LNfcService( 1799): isHCERoutingtoHost() return : true
D/NfcService( 1799): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1799): mEnableLPD: true
D/NfcService( 1799): mEnableReader: false
D/NfcService( 1799): mEnableHostRouting: true
D/NfcService( 1799): newParams.techmask= mTechMask: default
D/NfcService( 1799): mEnableLPD: true
D/NfcService( 1799): mEnableReader: false
D/NfcService( 1799): mEnableHostRouting: true
D/NfcService( 1799): screenState= 3
D/Ulp_jni (  839): JNI:system_update. Event-0
D/NfcService( 1799): Discovery configuration equal, not updating.
,V/PhoneApp( 1764): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2690): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:12:38
,D/WeatherService( 2690): 2 : ACTION screen on
,D/WeatherService( 2690): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2690): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2690): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:12:38
D/AppCleanupService( 3844): android.intent.action.SCREEN_ON
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): ACTION_SCREEN_ON
V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=off, calling pid 839
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
,D/WifiController(  839): CMD_SCREEN_OFF 
D/WifiController(  839): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  839): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1852): |CORE| sendScreenState: state:false
,I/LEDService( 1816): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1816): stopPatternFlashing()
D/qdlights( 1816): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1816): clear
I/LEDService( 1816): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1816): set_light_notifications: 0,0,0,0,3
I/LEDService( 1816): updateLightsLocked : turn on led
I/Cliptray Service( 1816): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/LNfcService( 1799): action : android.intent.action.SCREEN_OFF
E/LEDService( 1816): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1816): Can't handle this request of patternId:0
D/LEDHandler( 1816): RESTART MSG
D/NfcServiceNXP( 1799): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1890): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1764): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2690): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:12:38
D/WeatherService( 2690): 2 : ACTION screen off
D/WeatherService( 2690): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2690): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:12:38
,D/AppCleanupService( 3844): android.intent.action.SCREEN_OFF
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): ACTION_SCREEN_OFF
D/AppCleanupService( 3844): AppUsageStatsSaveTask
E/NxpNfcJni( 1799): getReconnectState = 0x0
,D/LCardEmulationManager( 1799): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1799): getDefaultRoute
D/LNfcService( 1799): isRequireNfcCRouting() return true
D/LNfcService( 1799): isHCERoutingtoHost() return : true
D/NfcService( 1799): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1799): mEnableLPD: true
D/NfcService( 1799): mEnableReader: false
D/NfcService( 1799): mEnableHostRouting: true
D/NfcService( 1799): newParams.techmask= mTechMask: 0
D/NfcService( 1799): mEnableLPD: true
D/NfcService( 1799): mEnableReader: false
D/NfcService( 1799): mEnableHostRouting: true
,D/NfcService( 1799): screenState= 1
E/NxpNfcJni( 1799): getReconnectState = 0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/KeyguardViewMediator( 1382): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{32dd83a0 type 2 when 162273 com.android.systemui} when 162273
,D/PhoneUtils( 1764): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1764): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1764): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1764): getCallState : 0
,D/PhoneUtils( 1764): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1764): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1764): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1382): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1382): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{142bfb59 type 2 when 168547 android} when 168547
,E/ActivityThread( 3981): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  839): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 141969, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  839): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 234189, reason: UserStart
I/NotificationManager(  839): android: cancelAsUser(716319171) by android
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 176251761032; DSPS: 5874565; Offset : -3030718848
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1742): disconnect managed GoogleApiClient
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{cf832a type 2 when 188399 com.google.android.gms} when 188399
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{276aa7f7 type 2 when 188726 android} when 188726
,I/PhenotypeConfigurator( 1742): Scheduling Phenotype for one-off execution 10807 seconds from now (1449832388661)
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/GetConfigurationSnapshotOperation( 1742): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1742): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1742): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1742): Explicit concurrent mark sweep GC freed 24426(1444KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 14MB/23MB, paused 1.430ms total 79.123ms
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1742): propertyValue:false
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  839): Explicit concurrent mark sweep GC freed 56419(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 1.995ms total 152.736ms
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1742): propertyValue:false
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/NotificationManager( 1742): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 196252460920; DSPS: 6529948; Offset : -3030721047
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{22ca3b0b type 2 when 198568 android} when 198568
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 216253229922; DSPS: 7185333; Offset : -3030714854
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 236253939499; DSPS: 7840716; Offset : -3030707259
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 256254616001; DSPS: 8496098; Offset : -3030701909
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 276255281723; DSPS: 9151480; Offset : -3030707939
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
D/LEDHandler( 1816): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 296255947444; DSPS: 9806862; Offset : -3030713319
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 316256613634; DSPS: 10462244; Offset : -3030718410
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5417): Connected to the server!
I/jxcore-log( 5417): 
,I/chromium( 5417): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 336257387637; DSPS: 11117629; Offset : -3030707894
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  839): remove 300cdfcd
,D/LocationManagerService(  839): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  839): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  839): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  839): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 356258137786; DSPS: 11773014; Offset : -3030720215
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 376258952413; DSPS: 12428400; Offset : -3030698993
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 396259667927; DSPS: 13083784; Offset : -3030716682
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,I/ActivityManager(  839): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7038 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 522us total 71.490ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 400us total 52.099ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 419us total 31.633ms
,I/DigitalAppWidgetProvider( 7038): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7038): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@110dbdec
,D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 416260745680; DSPS: 13739179; Offset : -3030706133
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6731): propertyValue:false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 436261419265; DSPS: 14394561; Offset : -3030703727
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{17dcb87e type 0 when 1449832655639 com.google.android.gms} when 1449832655639
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
,I/EventLogService( 3981): Aggregate from 1449832312382 (log), 1449830855575 (data)
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 456262098113; DSPS: 15049943; Offset : -3030696786
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 476262949042; DSPS: 15705331; Offset : -3030700271
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 496263683202; DSPS: 16360715; Offset : -3030698560
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 516264513819; DSPS: 17016102; Offset : -3030691864
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 536265273915; DSPS: 17671487; Offset : -3030694812
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 556266037970; DSPS: 18326872; Offset : -3030693254
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 576266863431; DSPS: 18982259; Offset : -3030692106
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 596267606913; DSPS: 19637644; Offset : -3030711616
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 616268273624; DSPS: 20293026; Offset : -3030716109
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 636269111168; DSPS: 20948413; Offset : -3030702488
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,D/Finsky  ( 6731): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{20c96118 type 0 when 1449832850352 com.android.vending} when 1449832850352
,D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 6731): propertyValue:false
D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 656269858609; DSPS: 21603798; Offset : -3030718247
,D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Volley  ( 6731): [822] BasicNetwork.performRequest: HTTP response for request=<[ ] https://android.clients.google.com/fdfe/toc 0xe8d195d1 NORMAL 1> [lifetime=4529], [size=4070], [rc=200], [retryCount=0]
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/qtaguid ( 6731): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6731): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 6731): untagSocket(44) failed with errno -22
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
D/Finsky  ( 6731): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  839): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7162 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,W/ResourcesManager( 7162): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7162): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7162): VM with version 2.1.0 has multidex support
I/MultiDex( 7162): install
,I/MultiDex( 7162): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7162): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7162): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7162): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@aed367c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7162): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7162): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7162): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 7162): Reading stored module config
,D/AuthorizationBluetoothService( 1742): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 3981): Restart initialization of location
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1742): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 7162): Loading module com.google.android.gms.car from APK com.google.android.gms
D/WearableService( 1742): callingUid 10006, callindPid: 1742
,E/MDM     ( 1742): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1742): No location to return for getLastLocation()
W/FusedLocationProvider( 1742): location=null
,D/NativeLibraryUtils( 7162): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 7162): Connecting to CarCallService...
I/ActivityManager(  839): Process com.google.android.setupwizard (pid 6792) has died
,I/art     ( 7162): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7162): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 7162): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 7162): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7162): Creating a new PhoneAdapter instance
W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7162): setListener: com.google.android.gms.car.dn@134a1f7b
W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7162): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 7162): Starting CarCallService with initial phone null
I/NotificationManager( 7162): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 7162): Package validated; name: com.android.vending
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/NotificationManager( 6731): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6731): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/qtaguid ( 6731): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6731): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6731): untagSocket(44) failed with errno -22
,I/art     ( 6731): CheckpointMarkThreadRoots callback created = 0xaaf0e040
,I/art     ( 6731): CheckpointMarkThreadRoots callback created = 0xb0601ff0
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/qtaguid ( 6731): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 6731): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 6731): untagSocket(44) failed with errno -22
,D/Finsky  ( 6731): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.marvin.talkback to false
,D/Finsky  ( 6731): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.marvin.talkback from d_AAAAAAADF8w= to 
W/ResourcesManager( 6731): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6731): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6731): [1] InstallerImpl.requestInstall: Request install of com.google.android.play.games v=35170036 pri=3 for rapid_auto_update
,D/Finsky  ( 6731): [1] PackageInstallerImpl.innerCreateSession: Created session 1189787226 for com.google.android.play.games
,D/Finsky  ( 6731): [1] InstallerImpl.kick: Installer kick - starting com.google.android.play.games
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/Finsky  ( 6731): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 6731): [1] DailyHygiene.access$600: Logging device features
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{1803e833 type 0 when 1449832863243 com.android.vending} when 1449832863243
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
,D/DeviceConnectionService( 1742): client connected with version: 8296000
D/Finsky  ( 6731): [845] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/CAR.SERVICE( 7162): mConnectedToCar = false, abort
,E/ActivityThread( 7162): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@6db5303 that was originally bound here
E/ActivityThread( 7162): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@6db5303 that was originally bound here
E/ActivityThread( 7162): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7162): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7162): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7162): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7162): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7162): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7162): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7162): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7162): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7162): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 7162): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 7162): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 7162): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 7162): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 7162): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 7162): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 7162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7162): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7162): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7162): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7162): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7162): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7162): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 7162): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3d7efb0a that was originally bound here
E/ActivityThread( 7162): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3d7efb0a that was originally bound here
E/ActivityThread( 7162): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7162): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7162): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7162): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7162): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7162): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7162): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7162): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 7162): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 7162): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 7162): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 7162): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 7162): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 7162): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 7162): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 7162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7162): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7162): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7162): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7162): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7162): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7162): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  839): Unbind failed: could not find connection for android.os.BinderProxy@2e9874fa
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6731): propertyValue:false
D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/Volley  ( 6731): [822] BasicNetwork.performRequest: HTTP response for request=<[ ] https://android.clients.google.com/fdfe/delivery?doc=com.google.android.play.games&ot=1&st=EM_t-bAFGYGV67Odh9VB&vc=35170036&bvc=34120036&pf=1&pf=2&pf=3&ch=OJGKRT0HGZNU-LGa8F7GViztV4g 0xe8d195d1 NORMAL 5> [lifetime=7380], [size=1399], [rc=200], [retryCount=1]
D/Finsky  ( 6731): [1] DownloadImpl.setState: Duplicate state set for 'com.google.android.play.games' (0). Already in that state
,D/Finsky  ( 6731): [1] DownloadQueueImpl.add: Download com.google.android.play.games added to DownloadQueue
D/Finsky  ( 6731): [1] DownloadImpl.setState: com.google.android.play.games from 0 to 1.
I/installd(  285): free_cache(5163679) avail 2539536384
,D/Finsky  ( 6731): [1] StartNextDownloadRunnable.run: Download com.google.android.play.games starting
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@2c4af44e on behalf of 6731
V/DownloadManager( 3096): initiating download with UID 10036
V/DownloadManager( 3096): other UID 1000
I/DownloadManager( 3096): insert() mimeType is null / COLUMN_TYPESORT_INDEX =100
,V/DownloadManager( 3096): DownloadService onCreate
,D/Finsky  ( 6731): [825] DownloadQueueImpl$7.run: Enqueued com.google.android.play.games as content://downloads/my_downloads/75
I/NotificationManager( 3096): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3096): in removeSpuriousFiles
D/Finsky  ( 6731): [1] DownloadImpl.setState: com.google.android.play.games from 1 to 2.
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 6731): [1] DownloadQueueImpl.onStart: com.google.android.play.games: onStart
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@aed367c on behalf of 3096
V/DownloadManager( 3096): DownloadService onStartCommand
V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3096): in trimDatabase
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3466075a on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@2f4abd8b on behalf of 3096
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@d153e68 on behalf of 6731
,D/Finsky  ( 6731): [1] DownloadQueueImpl.notifyProgress: com.google.android.play.games: onProgress 0/-1 Status: 190.
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@377f7281 on behalf of 3096
D/DownloadManager( 3096): DB Update : status 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@6ed3f26 on behalf of 6731
D/Finsky  ( 6731): [1] DownloadQueueImpl.notifyProgress: com.google.android.play.games: onProgress 0/-1 Status: 192.
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@2533d914 on behalf of 3096
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1cafb5bd on behalf of 3096
I/DownloadManager( 3096): Download 75 starting
I/DownloadManager( 3096): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@d5e27b2 on behalf of 3096
I/DownloadManager( 3096): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
,D/DownloadManager( 3096): fileSize : -1state.mContinuingDownload :false
D/libc-netbsd( 3096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10019
D/DnsProxyListener(  279): App 10019 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 3096): propertyValue:false
,D/libc-netbsd( 3096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,W/ActivityThread( 3096): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/libc-netbsd( 3096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 3096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10019
D/DnsProxyListener(  279): App 10019 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 3096): propertyValue:false
D/libc-netbsd( 3096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3096): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3096): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/DownloadManager( 3096): Content-Disposition: null
V/DownloadManager( 3096): Content-Length: 5163679
V/DownloadManager( 3096): Content-Location: null
V/DownloadManager( 3096): Content-Type: application/vnd.android.package-delta
V/DownloadManager( 3096): ETag: 1367bc79_d7a0d0fd_2cd4de22_d6803a6f_9442b16f
V/DownloadManager( 3096): Transfer-Encoding: null
V/DownloadManager( 3096): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 3096): Min update size = 32768
,V/DownloadManager( 3096): using default filename
I/DownloadManager( 3096): in verifySpace, destination: 2, path: downloadfile, length: 5163679
I/DownloadManager( 3096): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2539503616
D/DownloadManager( 3096): initial value of space = 209715200
D/DownloadManager( 3096): file count in data dir = 0
I/DownloadManager( 3096): available space (in bytes) in downloads data dir: 209715200
V/DownloadManager( 3096): couldn't find extension for application/vnd.android.package-delta
V/DownloadManager( 3096): adding default binary extension
V/DownloadManager( 3096): target file: /data/data/com.android.providers.downloads/cache/downloadfile.bin
,I/DowlnoadThread( 3096): updateDatabaseFromHeaders mMimeType =application/vnd.android.package-deltafilename=/data/data/com.android.providers.downloads/cache/downloadfile.bin
I/DownloadProvider.LgeUtils( 3096): getTypeSortIndex mimeType is =application/vnd.android.package-delta / filename=/data/data/com.android.providers.downloads/cache/downloadfile.bin
I/DownloadProvider.LgeUtils( 3096): getTypeSortIndex mediaType is =application / extension=bin
I/DownloadProvider.LgeUtils( 3096): getTypeSortIndex  index is =100
I/DowlnoadThread( 3096): updateDatabaseFromHeaders  COLUMN_TYPESORT_INDEX =100
V/DownloadManager( 3096): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3d7efb0a on behalf of 3096
D/DownloadManager( 3096): DB Update : etag 1367bc79_d7a0d0fd_2cd4de22_d6803a6f_9442b16f
D/DownloadManager( 3096): DB Update : title downloadfile.bin
D/DownloadManager( 3096): DB Update : _data /data/data/com.android.providers.downloads/cache/downloadfile.bin
D/DownloadManager( 3096): DB Update : total_bytes 5163679
D/DownloadManager( 3096): DB Update : type_sort_index 100
D/DownloadManager( 3096): DB Update : mimetype application/vnd.android.package-delta
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 3096): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,I/LGDrmClient( 3096): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  289): eDRM_GetObjectInfo +++
,V/ILGDrmService(  289): eDRM_GetObjectInfo ---
,V/DownloadManager( 3096): ID : 75, transferData threadNum -1 start for https://android.clients.google.com/market/download/Download?packageName=com.google.android.play.games&versionCode=35170036&ssl=1&token=AOTCm0QDHfNa3ioY7f5fmKYwk5NySJ4W_R9vD-JuTwaw6ubAAHQtGvK7PGXabca8klmOwlFHp_LaxXfr6StyHHxsPsq7__8yNUVAuvM67yJA8zPAslGoRvpyvuhijbJGWpmiFGWbnETeUVFQWKmrlLRc5mjY1vT0diozP9SsfWzGjIkoyPR05i2vqCbW_bxGZbQFDFmszFvNlQxxtobGytJrU4Eckg7E5yZVnyOvajgSwZ3L&downloadId=7997794453599515204&baseVersion=34120036&pf=2
D/DownloadManager( 3096): DB Update : current_bytes 32768
I/art     (  839): Explicit concurrent mark sweep GC freed 35293(1912KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.581ms total 258.483ms
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@134a1f7b on behalf of 3096
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@20491198 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3608fdf1 on behalf of 3096
V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1899bdd6 on behalf of 3096
,V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3ad13857 on behalf of 3096
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  839): tsOffsetIs: Apps: 676271691258; DSPS: 22259217; Offset : -3030686942
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{3f62ab4c type 0 when 1449832876663 com.android.vending} when 1449832876663
,D/Finsky  ( 6731): [835] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6731): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/DownloadManager( 3096): DB Update : current_bytes 851968
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3489af44 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@249e882d on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@24cbe162 on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/DownloadManager( 3096): DB Update : current_bytes 884736
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3d4702f3 on behalf of 3096
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@35147bb0 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@31887a29 on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ActivityManager(  839): Waited long enough for: ServiceRecord{3e7ca952 u0 com.android.providers.downloads/.DownloadService}
,D/DownloadManager( 3096): DB Update : current_bytes 917504
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@110ab1ae on behalf of 3096
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1e44db4f on behalf of 6731
,V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@c3da2dc on behalf of 3096
I/DownloadManager( 3096): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.bin, length: 32768
I/DownloadManager( 3096): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2538496000
D/DownloadManager( 3096): initial value of space = 209715200
D/DownloadManager( 3096): file count in data dir = 1
D/DownloadManager( 3096): remain space = 208699392
I/DownloadManager( 3096): available space (in bytes) in downloads data dir: 208699392
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/DownloadManager( 3096): DB Update : current_bytes 1114112
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@10058fe5 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@34543aba on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@179ddd6b on behalf of 3096
,D/DownloadManager( 3096): DB Update : current_bytes 1998848
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@137010c8 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@2e844561 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@257b4886 on behalf of 3096
I/DownloadManager( 3096): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.bin, length: 32768
,I/DownloadManager( 3096): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2537447424
D/DownloadManager( 3096): initial value of space = 209715200
D/DownloadManager( 3096): file count in data dir = 1
D/DownloadManager( 3096): remain space = 207650816
I/DownloadManager( 3096): available space (in bytes) in downloads data dir: 207650816
D/DownloadManager( 3096): DB Update : current_bytes 2326528
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@233ae547 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@dd97174 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@19ded69d on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 696272454479; DSPS: 22914603; Offset : -3030716449
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/DownloadManager( 3096): DB Update : current_bytes 2392064
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3b36712 on behalf of 3096
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@6b68ee3 on behalf of 6731
,I/art     ( 3096): CheckpointMarkThreadRoots callback created = 0xb05ea590
,V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@21d630e0 on behalf of 3096
I/art     ( 3096): CheckpointMarkThreadRoots callback created = 0xb05ea560
,D/DownloadManager( 3096): DB Update : current_bytes 2654208
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@18573f99 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3bdce25e on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3cb9363f on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/DownloadManager( 3096): DB Update : current_bytes 2752512
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3d1d7b0c on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@38533c55 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1690c66a on behalf of 3096
D/DownloadManager( 3096): DB Update : current_bytes 2916352
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1814f75b on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@fad3bf8 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@ed848d1 on behalf of 3096
D/DownloadManager( 3096): DB Update : current_bytes 3047424
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1aecdf36 on behalf of 3096
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3ca1ae37 on behalf of 6731
,V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@9761fa4 on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/DownloadManager( 3096): DB Update : current_bytes 3112960
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@21c7a10d on behalf of 3096
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@121fb8c2 on behalf of 6731
,V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@9d8f6d3 on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 716273225670; DSPS: 23569988; Offset : -3030708562
,I/DownloadManager( 3096): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.bin, length: 32768
I/DownloadManager( 3096): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2536398848
D/DownloadManager( 3096): initial value of space = 209715200
D/DownloadManager( 3096): file count in data dir = 1
D/DownloadManager( 3096): remain space = 206602240
I/DownloadManager( 3096): available space (in bytes) in downloads data dir: 206602240
,D/DownloadManager( 3096): DB Update : current_bytes 3145728
V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@6c79210 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@39da4109 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@37b49f0e on behalf of 3096
D/DownloadManager( 3096): DB Update : current_bytes 3211264
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@13322d2f on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@177bbf3c on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@185ce4c5 on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
D/DownloadManager( 3096): DB Update : current_bytes 3375104
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@229f9e1a on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@23e6d4b on behalf of 6731
,V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@ce39328 on behalf of 3096
D/DownloadManager( 3096): DB Update : current_bytes 3735552
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@cac0841 on behalf of 3096
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@330981e6 on behalf of 6731
,V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3e849327 on behalf of 3096
,I/DownloadManager( 3096): in verifySpace, destination: 2, path: /data/data/com.android.providers.downloads/cache/downloadfile.bin, length: 32768
I/DownloadManager( 3096): available space (in bytes) in filesystem rooted at: /data/data/com.android.providers.downloads/cache is: 2535350272
D/DownloadManager( 3096): initial value of space = 209715200
,D/DownloadManager( 3096): file count in data dir = 1
D/DownloadManager( 3096): remain space = 205553664
I/DownloadManager( 3096): available space (in bytes) in downloads data dir: 205553664
D/DownloadManager( 3096): DB Update : current_bytes 4390912
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3a72b9d4 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@256fe77d on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@10dbd672 on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/DownloadManager( 3096): DB Update : current_bytes 4620288
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@371d3ac3 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@152b9f40 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@39987e79 on behalf of 3096
D/DownloadManager( 3096): DB Update : current_bytes 4784128
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@70ce7be on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@2a0ec01f on behalf of 6731
,V/DownloadManager( 3096): processing updated download 75, status: 192
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1dcb6f6c on behalf of 3096
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/DownloadManager( 3096): DB Update : current_bytes 4980736
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@5198935 on behalf of 3096
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@7abc1ca on behalf of 6731
,V/DownloadManager( 3096): processing updated download 75, status: 192
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@5693f3b on behalf of 3096
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/DownloadManager( 3096): DB Update : current_bytes 5013504
,V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1b61658 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@156683b1 on behalf of 6731
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@24ac3096 on behalf of 3096
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 736273896964; DSPS: 24225370; Offset : -3030708864
,D/DownloadManager( 3096): ID : 75, transferData threadNum -1 is completed
,D/DownloadManager( 3096): DB Update : current_bytes 5163679
V/DownloadManager( 3096): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3e229417 on behalf of 3096
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1ea24004 on behalf of 6731
,V/LFT     ( 3096): notifyThroughDatabase after updateDB  id :  75, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 3096): notifyThroughDatabase start id : 75 name : /data/data/com.android.providers.downloads/cache/downloadfile.bin status : 200
V/DownloadManager( 3096): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1aea9ed on behalf of 3096
D/DownloadManager( 3096): DB Update : numfailed 0
D/DownloadManager( 3096): DB Update : method 0
D/DownloadManager( 3096): DB Update : _data /data/data/com.android.providers.downloads/cache/downloadfile.bin
D/DownloadManager( 3096): DB Update : lastmod 1449832936278
D/DownloadManager( 3096): DB Update : status 200
D/DownloadManager( 3096): DB Update : mimetype application/vnd.android.package-delta
,D/Finsky  ( 6731): [1] DownloadBroadcastReceiver.onReceive: Intent received at DownloadBroadcastReceiver
,I/DownloadManager( 3096): Download 75 finished with status SUCCESS
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@972c022 on behalf of 6731
,D/Finsky  ( 6731): [1] DownloadQueueImpl.notifyProgress: com.google.android.play.games: onProgress 5163679/5163679 Status: 200.
V/DownloadManager( 3096): processing updated download 75, status: 192
V/DownloadManager( 3096): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@38b25ab3 on behalf of 3096
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@15055870 on behalf of 6731
D/DownloadManager( 3096): checkStatusUpdate current status 192 is changed to 200
D/DownloadManager( 3096): checkStatusUpdate return true mID : mStatus = 75 : 200 => 200
D/Finsky  ( 6731): [1] DownloadImpl.setState: com.google.android.play.games from 2 to 3.
V/DownloadManager( 3096): DownloadService onDestroy
D/Finsky  ( 6731): [1] DownloadQueueImpl.onComplete: com.google.android.play.games: onComplete
D/Finsky  ( 6731): [1] DownloadQueueImpl.remove: Download com.google.android.play.games removed from DownloadQueue
,I/installd(  285): free_cache(0) avail 2534363136
D/Finsky  ( 6731): [1] InstallerTask.advanceState: Prepare to patch com.google.android.play.games (com.google.android.play.games) from content://downloads/my_downloads/75 format 2
V/DownloadManager( 3096): openFile uri: content://downloads/my_downloads/75, mode: r, uid: 10036
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; selection is null; selectionArgs is null; sort is _id.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@120bc6e on behalf of 6731
V/DownloadManager( 3096): row 75 available
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@1f6def0f on behalf of 6731
V/DownloadManager( 3096): filename in openFile: /data/data/com.android.providers.downloads/cache/downloadfile.bin
V/DownloadManager( 3096): file exists in openFile
V/DownloadManager( 3096): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@153f8b9c on behalf of 6731
I/installd(  285): free_cache(11974554) avail 2534363136
,V/Herrevad( 3981): NQAS connected
,E/lowmemorykiller(  244): Error writing /proc/6667/oom_score_adj; errno=22
,E/lowmemorykiller(  244): Error writing /proc/6667/oom_score_adj; errno=22
I/ActivityManager(  839): Process com.android.contacts (pid 6667) has died
,I/ConfigService( 1742): onCreate
,I/CheckinRequestBuilder( 1742): Classify the device as Phone.
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1742): propertyValue:false
D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1742): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1742): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     (  839): Explicit concurrent mark sweep GC freed 17332(920KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.697ms total 144.682ms
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ActivityManager(  839): Process com.android.gallery3d (pid 6645) has died
,D/Finsky  ( 6731): [836] InstallerTask$8.doInBackground$1a3e6397: Patch apply task for com.google.android.play.games (com.google.android.play.games) (format 2) completed in -5085 ms
,D/Finsky  ( 6731): [1] InstallerTask$8.onPostExecute: Successfully applied patch to update com.google.android.play.games (com.google.android.play.games)
D/Finsky  ( 6731): [1] InstallerTask.advanceState: Begin install of com.google.android.play.games
I/ConfigService( 1742): onDestroy
,I/ActivityManager(  839): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7382 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,D/Finsky  ( 6731): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
,D/Finsky  ( 6731): [1] WorkerTask.onPreExecute: Verification Requested for id = 0, data=file:///data/app/vmdl1189787226.tmp flags=18 fromVerificationActivity=false
,D/Finsky  ( 6731): [837] PackageVerificationService.getPackageInfo: Cannot read archive for file:///data/app/vmdl1189787226.tmp in request id=0
D/Finsky  ( 6731): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
D/PackageManager(  839): /data/app/vmdl1189787226.tmp already staged; skipping copy
,D/PackageManager(  839): Renaming /data/app/vmdl1189787226.tmp to /data/app/com.google.android.play.games-1, and oldCodePath : /data/app/com.google.android.play.games-2
,I/ActivityManager(  839): Force stopping com.google.android.play.games appid=10085 user=-1: replace sys pkg
W/PackageManager(  839): Trying to update system app code path from /data/app/com.google.android.play.games-2 to /data/app/com.google.android.play.games-1
,I/art     (  839): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.google.android.play.games-1@base.apk@classes.dex' for file location '/data/app/com.google.android.play.games-1/base.apk': Failed to open oat filename for reading: No such file or directory
,I/art     (  839): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.google.android.play.games-1/arm/base.odex' for file location '/data/app/com.google.android.play.games-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/PackageManager(  839): Running dexopt on: /data/app/com.google.android.play.games-1/base.apk pkg=com.google.android.play.games isa=arm vmSafeMode=false
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/dex2oat ( 7400): /system/bin/dex2oat --zip-fd=6 --zip-location=/data/app/com.google.android.play.games-1/base.apk --oat-fd=7 --oat-location=/data/dalvik-cache/arm/data@app@com.google.android.play.games-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/dex2oat ( 7400): dex2oat took 9.861s (threads: 4)
,I/ActivityManager(  839): Force stopping com.google.android.play.games appid=10085 user=-1: update pkg
,W/PackageManager(  839): Code path for pkg : com.google.android.play.games changing from /data/app/com.google.android.play.games-2 to /data/app/com.google.android.play.games-1
W/PackageManager(  839): Resource path for pkg : com.google.android.play.games changing from /data/app/com.google.android.play.games-2 to /data/app/com.google.android.play.games-1
W/PackageSettings(  839): Skipping PackageSetting{18326cc com.example.hello/10030} due to missing metadata
,I/PackageManager(  839): Un-granting permission android.permission.WRITE_MEDIA_STORAGE from package com.android.providers.downloads.ui (protectionLevel=18 flags=0x48be44)
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
W/PackageSettings(  839): Skipping PackageSetting{18326cc com.example.hello/10030} due to missing metadata
,I/ActivityManager(  839): Force stopping com.google.android.play.games appid=10085 user=0: pkg removed
D/administrator(  839): Handling package changes for user 0
I/NotificationService(  839): action=android.intent.action.PACKAGE_REMOVED queryReplace=true
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.play.games flg=0x4000010 (has extras) }
,D/JobSchedulerService(  839): Receieved: android.intent.action.PACKAGE_REMOVED
I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7443 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
W/Settings(  839): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.play.games flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.play.games flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 2
D/KeyguardModel( 1382): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.play.games flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.play.games flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 2
,I/[SystemUI]QSlideListController( 1382): onReceive = android.intent.action.PACKAGE_REMOVED
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/QCNEJ   ( 1852): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/QCNEJ   ( 1852): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1382): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.google.android.play.games
I/QCNEJ   ( 1852): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1382): onReceive = android.intent.action.PACKAGE_ADDED
,D/KeyguardModel( 1382): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1382): createShortcutInfo...
,D/KeyguardModel( 1382): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1382): createShortcutInfo...
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1382): onReceive = android.intent.action.PACKAGE_ADDED, packageName : com.google.android.play.games
W/ResourcesManager( 1382): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1382): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1382): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1382): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1382): createShortcutInfo...
I/art     ( 1890): Explicit concurrent mark sweep GC freed 10063(540KB) AllocSpace objects, 8(809KB) LOS objects, 24% free, 15MB/20MB, paused 545us total 118.800ms
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1382): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1382): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1382): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1382): createShortcutInfo...
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7443): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7443): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 1382): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1382): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1382): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7443): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1382): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1382): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1382): createShortcutInfo...
D/KeyguardModel( 1382): handleShortcutListChanged...
,I/NotificationService(  839): action=android.intent.action.PACKAGE_ADDED queryReplace=false
,D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.play.games flg=0x4000010 (has extras) }
I/art     (  839): Explicit concurrent mark sweep GC freed 122668(5MB) AllocSpace objects, 21(1614KB) LOS objects, 33% free, 23MB/35MB, paused 24.793ms total 428.798ms
,I/LGEmail ( 7443): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7443): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 6731): [1] InstallerTask$3.installSucceeded: Successful install of com.google.android.play.games
,I/NotificationManager( 6731): com.android.vending: cancel(-1050172287) by com.android.vending
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.android.vending/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6731): Failed to ensure directory: /storage/external_SD/Android/data/com.android.vending/files
,D/LCardEmulationManager( 1799): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1799): getDefaultRoute
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/PackageChangeReceiver( 7443): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7477 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/LCardEmulationManager( 1799): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1799): getDefaultRoute
,W/ResourcesManager( 7477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7477): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7477): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7477): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7477): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 7477): Using schema version: 115
,I/IndexDatabaseHelper( 7477): Index is fine
D/LCardEmulationManager( 1799): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1799): getDefaultRoute
,D/PackageIntentReceiver( 7477): Not supported Hotkey customization function 
,D/HideNavigationAppsReceiver( 7477): Receive package name : com.google.android.play.games, replacing=true, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 7477): replacing : true
D/ButtonCombinationReceiver( 7477): Receive package name : com.google.android.play.games
D/ButtonCombinationReceiver( 7477): replacing : true
,I/ActivityManager(  839): Killing 6706:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_6706/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7498 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7498): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7498): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7498): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 7498): Total System Memory = 906309632
,I/GalleryUtils( 7498): Application Heap = 96 MB
I/AppConfig( 7498): App Tier : NOT_DEF
D/SystemHelper( 7498): region [EU], country [EU], operator [OPEN], sub-operator []
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 756274620602; DSPS: 24880754; Offset : -3030717751
,I/ActivityManager(  839): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7520 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  839): Killing 7038:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10010/pid_7038/cgroup.procs: No such file or directory
,W/ResourcesManager( 7520): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7520): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7520): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7520): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7520): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7520): BUILD Country: EU
I/SystemConfig( 7520): BUILD Operator: OPEN
,I/ActivityManager(  839): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7540 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  839): Killing 7162:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_7162/cgroup.procs: No such file or directory
I/SystemConfig( 7520): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7520): existFile = false
I/SystemConfig( 7520): canReadFile = false
I/SystemConfig( 7520): systemFeature RCS result false
D/SystemConfig( 7520): refreshRcsSupport() :false
W/ContextImpl( 7540): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2663 
,D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6686): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  839): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7558 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 3981:com.google.android.gms/u0a6 (adj 15): empty #11
D/ConnectivityService(  839): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@35d89b63)
,D/ConnectivityService(  839): dumpNetworkRequest
D/ConnectivityService(  839):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  839):     Requests:
D/ConnectivityService(  839):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):     Lingered:
D/ConnectivityService(  839): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  839): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_3981/cgroup.procs: No such file or directory
,I/GAv4    ( 7558): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7558):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7558):   adb logcat -s GAv4
,W/GAv4    ( 7558): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7558): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7558): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 7558): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7558): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 7558): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7558): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7589 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5890:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_5890/cgroup.procs: No such file or directory
,I/art     ( 7558): CheckpointMarkThreadRoots callback created = 0xaaf2b210
,W/ResourcesManager( 7589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 7558): CheckpointMarkThreadRoots callback created = 0xaaf2ba10
,W/art     ( 7558): Suspending all threads took: 8.701ms
,V/JNIHelp ( 7558): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7558): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7558): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  839): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7623 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  839): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7640 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 312us total 22.672ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.847ms
,I/GservicesProvider( 7623): Gservices pushing to system: true; secure/global: true
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.002ms
D/[BNRAppListMgrReceiver]( 7640): android.intent.action.PACKAGE_REMOVED : com.google.android.play.games
,I/NotificationManager( 6731): com.android.vending: cancel(-1050172287) by com.android.vending
,I/GoogleHttpClient( 7623): GMS http client unavailable, use old client
I/ActivityManager(  839): Killing 7382:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10004/pid_7382/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=7660 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GoogleHttpClient( 7623): GMS http client unavailable, use old client
,I/ActivityManager(  839): Killing 7443:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_7443/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Killing 6609:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ResourcesManager( 7660): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7660): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_6609/cgroup.procs: No such file or directory
,I/MultiDex( 7660): VM with version 2.1.0 has multidex support
I/MultiDex( 7660): install
I/MultiDex( 7660): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7660): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7660): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7660): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24cbe162: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7660): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7660): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7660): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 7660): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.play.games
,D/ChimeraCfgMgr( 7660): Reading stored module config
D/ChimeraCfgMgr( 7660): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 7660): Loading module APK com.google.android.play.games
W/ChimeraModuleLdr( 7660): Config is out of date: InstalledApk(com.google.android.play.games) has incorrect timestamp
,D/GmsModuleFndr( 7660): Beginning GMS chimera module scan
D/NativeLibraryUtils( 7660): Install completed successfully. count=14 extracted=0
,I/art     ( 7660): CheckpointMarkThreadRoots callback created = 0xb050abf0
,D/GmsModuleFndr( 7660): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
I/art     ( 7660): CheckpointMarkThreadRoots callback created = 0xb050abd0
D/ChimeraCfgMgr( 7660): Beginning module configuration check
,D/ChimeraModuleApk( 7660): Loading chimera manifest from InstalledApk(com.google.android.play.games)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.games,v35170000) from InstalledApk(com.google.android.play.games)
,D/ChimeraFileApk( 7660): Loading chimera manifest from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.maps,v8489000) from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk)
D/ChimeraModuleApk( 7660): Loading chimera manifest from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 7660): Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.car,v8489000) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.cast,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.games,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.gass,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.piccard,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 7660): Considering module(com.google.android.gms.vision,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgRslvr( 7660): Beginning module config resolution
D/ChimeraCfgRslvr( 7660): module(built-in,v0) has no external dependencies, accepted
D/ChimeraCfgRslvr( 7660): module(com.google.android.gms.car,v8489000) accepted
D/ChimeraCfgRslvr( 7660): module(com.google.android.gms.cast,v1) accepted
D/ChimeraCfgRslvr( 7660): module(com.google.android.gms.games,v35170000) accepted
D/ChimeraCfgRslvr( 7660): module(com.google.android.gms.gass,v1) accepted
D/ChimeraCfgRslvr( 7660): module(com.google.android.gms.kids,v3) accepted
D/ChimeraCfgRslvr( 7660): module(com.google.android.gms.maps,v8489000) accepted
D/ChimeraCfgRslvr( 7660): module(com.google.android.gms.piccard,v1) accepted
D/ChimeraCfgRslvr( 7660): module(com.google.android.gms.vision,v1) accepted
D/ChimeraCfgRslvr( 7660): Module config resolution complete
D/ChimeraCfgMgr( 7660): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7660): Loading module APK com.google.android.play.games
,E/NetworkScheduler.SchedulerReceiver( 1742): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1742): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7705 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  839): Process com.android.settings (pid 7477) has died
,D/ChimeraCfgMgr( 7660): Notified of config change, reloading
,W/ResourcesManager( 7705): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7705): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7705): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/Icing   ( 7660): Storage manager: low false usage 1.72MB avail 2.36GB capacity 4.06GB
,I/LGEmail ( 7705): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7705): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/PackageChangeReceiver( 7705): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  839): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=7737 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/Icing   ( 7660): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7757 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  839): Killing 7498:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10023/pid_7498/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7757): onCreate
,W/AppUp4:DB( 7757):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7757):  setFingerPrint start
I/AppUp4:DB( 7757):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7757):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7757):  SDK version = 0
I/AppUp4:DB( 7757):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7757): AppBoxApplication onCreate()
I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7777 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/Icing   ( 7660): Internal init done: storage state 0
I/ActivityManager(  839): Killing 7520:com.android.contacts/u0a18 (adj 15): empty #11
,W/ResourcesManager( 7777): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7777): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7777): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/libprocessgroup(  839): failed to open /acct/uid_10018/pid_7520/cgroup.procs: No such file or directory
,I/AppConfig( 7777): Total System Memory = 906309632
,I/GalleryUtils( 7777): Application Heap = 96 MB
I/AppConfig( 7777): App Tier : NOT_DEF
D/SystemHelper( 7777): region [EU], country [EU], operator [OPEN], sub-operator []
,I/art     (  839): Explicit concurrent mark sweep GC freed 22605(1223KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.253ms total 150.963ms
,I/Icing   ( 7660): Post-init done
I/ActivityManager(  839): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7796 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7540:com.android.keychain/1000 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7540/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Killing 6686:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/ResourcesManager( 7796): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7796): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7796): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7796): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7796): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  839): failed to open /acct/uid_10069/pid_6686/cgroup.procs: No such file or directory
,I/SystemConfig( 7796): BUILD Country: EU
I/SystemConfig( 7796): BUILD Operator: OPEN
,I/ActivityManager(  839): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7816 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7558:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10058/pid_7558/cgroup.procs: No such file or directory
I/SystemConfig( 7796): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7796): existFile = false
I/SystemConfig( 7796): canReadFile = false
I/SystemConfig( 7796): systemFeature RCS result false
D/SystemConfig( 7796): refreshRcsSupport() :false
I/LockScreenSettings( 7816): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 7816): New app installed broadcast received ..
,I/LockScreenSettings( 7816): Number of installed packages  1
,I/ActivityManager(  839): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=7833 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  839): Killing 7589:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_7589/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 7833): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 7833): uri : package:com.google.android.play.games
,I/ActivityManager(  839): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7850 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 7640:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7640/cgroup.procs: No such file or directory
,I/GAv4    ( 7850): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7850):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7850):   adb logcat -s GAv4
,W/GAv4    ( 7850): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7850): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7850): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7850): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7850): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 7850): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7850): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7881 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6731:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10036/pid_6731/cgroup.procs: No such file or directory
,I/art     ( 7850): CheckpointMarkThreadRoots callback created = 0xaaede230
W/ResourcesManager( 7881): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 7850): CheckpointMarkThreadRoots callback created = 0xb0512a60
,V/JNIHelp ( 7850): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7850): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7850): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  839): Killing 7660:com.google.android.gms/u0a6 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_7660/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=7916 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/UpdateIcingCorporaServi( 1965): Updating corpora: APPS=com.google.android.play.games, CONTACTS=MAYBE
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.393ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.680ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.197ms
,D/[BNRAppListMgrReceiver]( 7916): android.intent.action.PACKAGE_ADDED : com.google.android.play.games
,I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7933 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7705:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_7705/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.google.android.gms for service com.google.android.gms/.icing.service.IndexService: pid=7950 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7950): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7950): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7950): VM with version 2.1.0 has multidex support
I/MultiDex( 7950): install
I/MultiDex( 7950): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7950): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Finsky  ( 7933): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ActivityThread( 7950): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7950): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24cbe162: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7950): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7950): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7950): com.google.android.gms: cancel(39789) by com.google.android.gms
,W/art     ( 7950): Suspending all threads took: 30.040ms
I/art     ( 7950): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7950): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Icing   ( 7950): Storage manager: low false usage 1.72MB avail 2.36GB capacity 4.06GB
,D/NativeLibraryUtils( 7950): Install completed successfully. count=14 extracted=0
D/Finsky  ( 7933): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7933): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7933): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7933): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@3f4029a5 on behalf of 7933
I/NotificationManager( 7933): com.android.vending: cancel(-1884390924) by com.android.vending
D/Ads     ( 7933): Skipping gmscore version check
,D/Finsky  ( 7933): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7933): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7933): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/ChimeraCfgMgr( 7950): Reading stored module config
,I/art     ( 7950): CheckpointMarkThreadRoots callback created = 0xb042d420
D/Finsky  ( 7933): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  839): Killing 7737:com.google.android.partnersetup/u0a9 (adj 15): empty #11
D/PackageBroadcastService( 7950): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.play.games
,I/art     ( 7950): CheckpointMarkThreadRoots callback created = 0xb042d410
,W/libprocessgroup(  839): failed to open /acct/uid_10009/pid_7737/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7950): Loading module APK com.google.android.play.games
,D/GmsModuleFndr( 7950): Beginning GMS chimera module scan
,D/GmsModuleFndr( 7950): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 7950): Beginning module configuration check
,D/ChimeraCfgMgr( 7950): Module APKs unchanged, check complete
I/Icing   ( 7950): updateResources: need to parse f{com.google.android.gms}
,D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7950): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 7950): Submit a task: k
D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 7950): Processing package: com.google.android.play.games
D/b       ( 7950): Look up (com.google.android.play.games:35170036) returned no result
D/LauncherStateReceiver2( 7796): .activities.CallLogSearchResolverActivity enable(1)/disable(2) : 2
,D/k       ( 7950): Starting Hash for package com.google.android.play.games:3.5.17 (2463965-036)
D/LauncherStateReceiver2( 7796): .DialtactsRecentCallsEntryActivity enable(1)/disable(2) : 2
D/LauncherStateReceiver2( 7796): .alias.SpeedDialListActivity enable(1)/disable(2) : 2
I/ActivityManager(  839): Start proc com.lge.sizechangable.weather.platform for broadcast com.lge.sizechangable.weather.platform/com.lge.sizechangable.weather.receiver.WSReceiver: pid=8033 uid=10075 gids={50075, 9997, 3003} abi=armeabi-v7a
,I/PeopleDatabaseHelper( 7950): cleanUpNonGplusAccounts done.
,I/art     ( 8033): Almond Protected OAT
,W/BaseAppContext( 7950): Using Auth Proxy for data requests.
E/BaseAppContext( 7950): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 7950): Using Auth Proxy for data requests.
,I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=8061 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7757:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/k       ( 7950): Package com.google.android.play.games's hash: 88e1b0a7377f56ff572809c8e90586eaf8f99f6eb3e96e0a45a9eb225c5674c1
,D/b       ( 7950): Look up (com.google.android.play.games:35170036) returned no result
D/k       ( 7950): Saved the app info in cache for package:com.google.android.play.games.
,W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_7757/cgroup.procs: No such file or directory
W/BaseAppContext( 7950): Using Auth Proxy for data requests.
,I/Icing   ( 7950): Internal init done: storage state 0
I/NotificationManager( 7950): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/BaseAppContext( 7950): Using Auth Proxy for data requests.
W/BaseAppContext( 7950): Using Auth Proxy for data requests.
W/BaseAppContext( 7950): Using Auth Proxy for data requests.
,I/Icing   ( 7950): Post-init done
W/BaseAppContext( 7950): Using Auth Proxy for data requests.
I/UpdateIcingCorporaServi( 1965): UpdateCorporaTask done [took 1800 ms] updated apps [took 1800 ms] 
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8061): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8061): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 8061): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8061):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8061):   adb logcat -s GAv4
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8061): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8061): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 8061): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 8061): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8061): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  839): Process com.android.gallery3d (pid 7777) has died
,W/art     ( 7950): Suspending all threads took: 5.773ms
,I/WebViewFactory( 8061): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 7950): Module APK com.google.android.play.games already loaded
,I/LibraryLoader( 8061): Time to load native libraries: 11 ms (timestamps 4573-4584)
,I/LibraryLoader( 8061): Expected native library version number "",actual native library version number ""
,I/GamesDatabaseHelper( 7950): Upgrading from version 1701 to 1801
V/WebViewChromiumFactoryProvider( 8061): Binding Chromium to main looper Looper (main, tid 1) {152936ac}
,I/LibraryLoader( 8061): Expected native library version number "",actual native library version number ""
,I/chromium( 8061): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8061): Initializing chromium process, singleProcess=true
,W/art     ( 8061): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8061): ApplicationContext is null in ApplicationStatus
W/chromium( 8061): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8061): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8061): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8061): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8061): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8061): Build Date: 03/02/15 Mon
I/Adreno-EGL( 8061): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 8061): Remote Branch: 
I/Adreno-EGL( 8061): Local Patches: 
I/Adreno-EGL( 8061): Reconstruct Branch: 
,V/AudioPolicyService(  284): registerClient() client 0xb39b03a0, uid 10079
,W/AudioManagerAndroid( 8061): Requires BLUETOOTH permission
I/Icing   ( 7950): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/art     (  839): Explicit concurrent mark sweep GC freed 25345(1338KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.167ms total 152.203ms
,I/ActivityManager(  839): Process com.lge.lockscreensettings (pid 7816) has died
,D/Icing   ( 7950): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7950): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/Icing   ( 7950): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,I/NSApplication( 8061): Starting up...
,D/PackageBroadcastService( 7950): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.play.games
D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 7950): Submit a task: k
D/GmsModuleFndr( 7950): Beginning GMS chimera module scan
D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 7950): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 7950): Processing package: com.google.android.play.games
D/GmsModuleFndr( 7950): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 7950): Beginning module configuration check
D/GassUtils( 7950): Found app info for package com.google.android.play.games:35170036. Hash: 88e1b0a7377f56ff572809c8e90586eaf8f99f6eb3e96e0a45a9eb225c5674c1
D/k       ( 7950): Found info for package com.google.android.play.games in db.
,D/ChimeraCfgMgr( 7950): Module APKs unchanged, check complete
E/NetworkScheduler.SchedulerReceiver( 1742): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1742): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  839): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.DeviceBroadcastReceiver: pid=8138 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/Icing   ( 7950): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
,W/ResourcesManager( 8138): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Process com.google.android.apps.docs (pid 7850) has died
,E/App     ( 8138): [App][onCreate()] 4.40.23
,D/AccountManager( 8138): setSyncFrequency
,D/DeviceBroadcastReceiver( 8138): [DeviceBroadcastReceiver]android.intent.action.PACKAGE_REPLACED
,D/WearableService( 1742): callingUid 10006, callindPid: 1742
,E/MDM     ( 1742): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 7950): Restart initialization of location
,D/AuthorizationBluetoothService( 1742): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1742): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1742): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1742): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1742): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1742): No location to return for getLastLocation()
,W/FusedLocationProvider( 1742): location=null
D/LocationInitializer( 7950): Restart initialization of location
,W/GCoreFlp( 1742): No location to return for getLastLocation()
,W/FusedLocationProvider( 1742): location=null
,W/IcingInternalCorpora( 7950): getNumBytesRead when not calculated.
I/Icing   ( 7950): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 7950): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/QCNEJ   ( 1852): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1382): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8202 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1382): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1382): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1382): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  839): Handling package changes for user 0
,W/ResourcesManager( 8202): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@e10c694
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1742): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/DataBuffer( 1742): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18176a37)
,I/art     ( 1742): Explicit concurrent mark sweep GC freed 70156(4MB) AllocSpace objects, 22(351KB) LOS objects, 39% free, 15MB/25MB, paused 1.844ms total 135.840ms
D/LocationProviderProxy(  839): applying state to connected service
,I/Babel_SMS( 8202): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8202): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8202): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 8202): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8202): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8202): MmsConfig.loadFromResources
E/Babel_SMS( 8202): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8202): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/art     ( 8202): Suspending all threads took: 13.347ms
,I/art     ( 8202): CheckpointMarkThreadRoots callback created = 0xb042d860
,D/SensorManager( 8202): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 8202): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 8202): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 8202): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 8202): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 8202): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 8202): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 8202): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 8202): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 8202): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 8202): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 8202): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 8202): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 8202): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 8202): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 8202): found sensor: Motion Accel, handle=46
I/art     ( 8202): CheckpointMarkThreadRoots callback created = 0xb042d850
,W/Settings( 8202): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8202): startup - clean
I/Babel   ( 8202): deleted: false for 0
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 776275402261; DSPS: 25536139; Offset : -3030698537
,W/AudioCapabilities( 8202): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 8202): Unsupported mime audio/adpcm
W/AudioCapabilities( 8202): Unsupported mime audio/g726
W/AudioCapabilities( 8202): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 8202): Unsupported mime audio/wma-voice
W/VideoCapabilities( 8202): Unsupported mime video/mjpg
W/VideoCapabilities( 8202): Unsupported mime video/theora
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8253 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 8202): Unsupported mime audio/evrc
W/AudioCapabilities( 8202): Unsupported mime audio/qcelp
,W/VideoCapabilities( 8202): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 8202): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 8202): Unsupported mime audio/qcelp
W/AudioCapabilities( 8202): Unsupported mime audio/evrc
I/ActivityManager(  839): Process com.android.vending (pid 7933) has died
,W/VideoCapabilities( 8202): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 8202): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8202): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8202): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8202): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8202): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 8253): onCreate
W/AppUp4:DB( 8253):  [AppBoxDatabaseHelper] construct
,W/art     ( 8202): Suspending all threads took: 6.176ms
I/AppUp4:DB( 8253):  setFingerPrint start
I/AppUp4:DB( 8253):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8253):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8253):  SDK version = 0
I/AppUp4:DB( 8253):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8253): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 8253): onReceive
I/AppUp4:CustModeStarterReceiver( 8253): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 8253): Context : android.app.ReceiverRestrictedContext@110dbdec
D/AppUp4:CustFacade( 8253): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 8253): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 8253): begin check event
I/AppUp4:CustModeStarterReceiver( 8253): Event For Nothing, skip.
I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8280 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 8202): onServiceConnected
,W/Babel   ( 8202): Attempted to change video mute state without an active call.
I/NotificationManager( 8202): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 8202): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8202): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 8280): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8280): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8280): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 8202): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 8280): Total System Memory = 906309632
,W/System  ( 8202): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8202): Installed default security provider GmsCore_OpenSSL
I/GalleryUtils( 8280): Application Heap = 96 MB
I/AppConfig( 8280): App Tier : NOT_DEF
I/NotificationManager( 8202): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/SystemHelper( 8280): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  839): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8302 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7833:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7833/cgroup.procs: No such file or directory
,I/LockScreenSettings( 8302): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 8302): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 8302): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 8302): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 8302): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 8302): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1965): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8322 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1965): UpdateCorporaTask done [took 43 ms] updated apps [took 43 ms] 
I/ActivityManager(  839): Killing 7916:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7916/cgroup.procs: No such file or directory
,D/Finsky  ( 8322): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8322): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8322): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8322): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 8322): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3096): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3096): created cursor android.database.sqlite.SQLiteCursor@15a0317a on behalf of 8322
D/Finsky  ( 8322): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8322): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 8322): Skipping gmscore version check
D/Finsky  ( 8322): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 7950): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7950): Null package name or gms related package.  Ignoreing.
I/Icing   ( 7950): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 8322): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{24ac95f9 type 0 when 1449832977827 com.android.vending} when 1449832977827
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
,I/art     (  839): Explicit concurrent mark sweep GC freed 29385(1422KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.391ms total 155.480ms
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/libc-netbsd( 8322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 8322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 8322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/Icing   ( 7950): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 7950): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
,I/[SystemUI]Clock( 1382): called onTimeUpdated()
I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 8322): propertyValue:false
D/libc-netbsd( 8322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  839): Killing 8033:com.lge.sizechangable.weather.platform/u0a75 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10075/pid_8033/cgroup.procs: No such file or directory
,D/libc-netbsd( 8322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/Volley  ( 8322): [992] BasicNetwork.performRequest: HTTP response for request=<[ ] https://android.clients.google.com/vending/api/ApiRequest 0xe8d195d1 NORMAL 1 ContentSyncRequestProto> [lifetime=6983], [size=33], [rc=200], [retryCount=0]
,D/Finsky  ( 8322): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
,D/Finsky  ( 8322): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  839): Killing 8061:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10079/pid_8061/cgroup.procs: No such file or directory
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 796276176524; DSPS: 26191525; Offset : -3030717887
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 816276833600; DSPS: 26846906; Offset : -3030700951
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 836277572707; DSPS: 27502290; Offset : -3030694318
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 856278337543; DSPS: 28157675; Offset : -3030692708
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 876278968525; DSPS: 28813056; Offset : -3030702699
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{181f0d84 type 2 when 877423 android} when 877423
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 896279821382; DSPS: 29468444; Offset : -3030704231
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 916281018458; DSPS: 30123843; Offset : -3030697365
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 936281569388; DSPS: 30779221; Offset : -3030697158
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 956282318391; DSPS: 31434606; Offset : -3030709584
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 976282988642; DSPS: 32089988; Offset : -3030710616
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 996283634209; DSPS: 32745369; Offset : -3030705971
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{336f296d type 2 when 1004249 com.android.bluetooth} when 1004249
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
,W/bt-smp  ( 2068): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2068): Plain text(LSB ~ MSB) = b5 c7 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2068): Encrypted text(LSB ~ MSB) = 10 a5 d9 3c 51 50 87 c9 a9 81 1f 88 d7 53 e7 23 
W/bt-btm  ( 2068): Stopping oneshot timer
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{3c4209a2 type 2 when 1015573 com.google.android.gms} when 1015573
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1016284390242; DSPS: 33400754; Offset : -3030713501
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1036285157683; DSPS: 34056139; Offset : -3030708089
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1056285794863; DSPS: 34711520; Offset : -3030712324
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1076286514230; DSPS: 35366903; Offset : -3030694705
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1742): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/libc-netbsd( 8322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 8322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 8322): propertyValue:false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1096287268806; DSPS: 36022288; Offset : -3030703225
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1116288016037; DSPS: 36677673; Offset : -3030718674
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1136288744207; DSPS: 37333056; Offset : -3030692304
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1156289457637; DSPS: 37988440; Offset : -3030711556
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1176290466171; DSPS: 38643833; Offset : -3030709945
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1196291158091; DSPS: 39299216; Offset : -3030720060
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1216291936104; DSPS: 39954601; Offset : -3030705091
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  839): User[0] Flushing usage stats to disk
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1236292679794; DSPS: 40609985; Offset : -3030693823
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1256293327131; DSPS: 41265367; Offset : -3030717612
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1276294079154; DSPS: 41920751; Offset : -3030698142
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1296294731125; DSPS: 42576133; Offset : -3030717790
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1316295371170; DSPS: 43231514; Offset : -3030718642
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1336296128558; DSPS: 43886898; Offset : -3030693571
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1356296757092; DSPS: 44542279; Offset : -3030705933
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1376297496459; DSPS: 45197663; Offset : -3030699039
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1396298243795; DSPS: 45853048; Offset : -3030715033
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1416298971809; DSPS: 46508432; Offset : -3030718999
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1436299691801; DSPS: 47163815; Offset : -3030700936
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1456300430856; DSPS: 47819199; Offset : -3030694408
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1476301174078; DSPS: 48474584; Offset : -3030714307
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1496301849174; DSPS: 49129966; Offset : -3030710052
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1516302585000; DSPS: 49785350; Offset : -3030706751
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1536303300096; DSPS: 50440733; Offset : -3030693715
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1556303950036; DSPS: 51096115; Offset : -3030715006
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1576304760967; DSPS: 51751501; Offset : -3030697611
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1596305396584; DSPS: 52406882; Offset : -3030702862
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1616306047826; DSPS: 53062263; Offset : -3030692672
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1636306815319; DSPS: 53717648; Offset : -3030687806
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1656307543488; DSPS: 54373033; Offset : -3030722681
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1676308207594; DSPS: 55028414; Offset : -3030699703
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1696308973264; DSPS: 55683799; Offset : -3030696687
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1716309603725; DSPS: 56339180; Offset : -3030707199
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1736310554031; DSPS: 56994571; Offset : -3030703017
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1756311412981; DSPS: 57649959; Offset : -3030698194
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1776312251880; DSPS: 58305347; Offset : -3030714074
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1796312822237; DSPS: 58960725; Offset : -3030692825
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1816313500667; DSPS: 59616108; Offset : -3030716377
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1836314343471; DSPS: 60271495; Offset : -3030697418
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1856315152058; DSPS: 60926882; Offset : -3030712753
,I/[SystemUI]TimeTickManager( 1382): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1382): called onTimeUpdated()
I/[SystemUI]Clock( 1382): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
I/[SystemUI]DateView( 1382): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1382): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
,D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1382): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1382): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1852): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1816): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1816): Battery Level Remaining: 100%
D/LEDHandler( 1816): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1852): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2068): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1382): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1382): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1816): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1382): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1382): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1382): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1876315781008; DSPS: 61582262; Offset : -3030694572
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1896316585115; DSPS: 62237649; Offset : -3030714673
,I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=628540068, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{f64fcc6 type 2 when 1904399 com.android.bluetooth} when 1904399
,W/bt-smp  ( 2068): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2068): Plain text(LSB ~ MSB) = be 26 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2068): Encrypted text(LSB ~ MSB) = 3d 34 cd d9 54 cd 54 11 fa 8b df 43 9e 93 ad c2 
W/bt-btm  ( 2068): Stopping oneshot timer
I/ProcessStatsService(  839): Prepared write state in 14ms
,I/ProcessStatsService(  839): Prepared write state in 9ms
,I/ActivityManager(  839): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8524 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 425us total 61.522ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 410us total 36.246ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 407us total 30.741ms
,I/DigitalAppWidgetProvider( 8524): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8524): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@110dbdec
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=628540068 [*alarm*], flags=0x0
I/ActivityManager(  839): Killing 8138:com.lge.qmemoplus/1000 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_8138/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms),I/ThermalEngine(  297): Sensor:pa_therm0:28000 mC
I/ProcessStatsService(  839): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-09-28.bin
D/AndroidRuntime( 8565): 
D/AndroidRuntime( 8565): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8565): CheckJNI is OFF
D/AndroidRuntime( 8565): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  839): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  839): Killing 5417:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  839): WIN DEATH: Window{1ae9581b u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  839): Skipping PackageSetting{18326cc com.example.hello/10030} due to missing metadata
D/InputDispatcher(  839): Focus left window: Window{1ae9581b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  839): Window went away: Window{1ae9581b u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  839):   Force finishing activity ActivityRecord{13b188f8 u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  839): Display changed displayId=0
D/DSDPConnection( 1764): Display #0 changed.
W/ActivityManager(  839): Spurious death for ProcessRecord{1a282487 5417:com.test.thalitest/u0a316}, curProc for 5417: null
I/ActivityManager(  839): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  839):   Force finishing activity ActivityRecord{13b188f8 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  839): Duplicate finish request for ActivityRecord{13b188f8 u0 com.test.thalitest/.MainActivity t220 f}
I/[LGHome]EVENT( 1890): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1382): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1852): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1742): Ignoring removeGeofence because network location is disabled.
W/System.err( 3362): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3362): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3362): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3362): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3362): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3362): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1890): [Launcher.java:776:onResume()]onResume
I/art     ( 1965): Explicit concurrent mark sweep GC freed 29423(1806KB) AllocSpace objects, 2(47KB) LOS objects, 40% free, 12MB/21MB, paused 1.125ms total 135.907ms
I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8592 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1890): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1382): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1890): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1382): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1382): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1890): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1890): [Launcher.java:929:onResume()]onResume end
I/Activity( 1890): Activity.onPostResume() called 
D/KeyguardModel( 1382): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1382): createShortcutInfo...
W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1382): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1382): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1382): createShortcutInfo...
W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1382): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1382): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1382): createShortcutInfo...
W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1382): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/art     (  839): Explicit concurrent mark sweep GC freed 30749(2MB) AllocSpace objects, 10(307KB) LOS objects, 33% free, 23MB/35MB, paused 4.567ms total 215.814ms
D/KeyguardModel( 1382): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1382): createShortcutInfo...
I/art     (  839): WaitForGcToComplete blocked for 46.630ms for cause Explicit
I/[LGHome]EVENT( 1890): [Launcher.java:986:onPause()]onPause
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1382): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1382): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1382): handleShortcutListChanged...
W/[LGHome]LGWallpaperInfo( 1890): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1890): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 8592): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8592): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8592): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/administrator(  839): Handling package changes for user 0
D/KeyguardModel( 1382): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1382): createShortcutInfo...
I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1382): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1382): createShortcutInfo...
W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1382): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/InputDispatcher(  839): Focus entered window: Window{1332fbf2 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1382): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1382): createShortcutInfo...
W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1382): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1382): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1382): createShortcutInfo...
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17d8be8f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
W/ResourceType( 1382): No package identifier when getting value for resource number 0x00000000
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17d8be8f,  pkg=WindowManager.LayoutParams
W/PackageManager( 1382): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1382): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1382): createShortcutInfo...
D/KeyguardModel( 1382): handleShortcutListChanged...
I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1890): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1890): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1890): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1890): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  839): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  839): Got RemoteException sending setActive(false) notification to pid 5417 uid 10316
I/NotificationService(  839): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  839): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  839): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1382): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1382): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1382):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1382): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 1890): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/LGEmail ( 8592): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  839): Timeline: Activity_windows_visible id: ActivityRecord{313895cc u0 com.lge.launcher2/.Launcher t219} time:1906911
D/LGEmail ( 8592): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/IInputConnectionWrapper( 1890): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1890): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  839): Explicit concurrent mark sweep GC freed 8030(446KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.614ms total 369.216ms
E/b       ( 1618): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1890): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1890): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1890): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
D/LCardEmulationManager( 1799): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1799): getDefaultRoute
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1890): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/PackageChangeReceiver( 8592): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/AppUp4:PreloadHelper( 8253): added Exclude : com.test.thalitest
D/AndroidRuntime( 8565): Shutting down VM
W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8620 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  839): Killing 8202:com.google.android.talk/u0a61 (adj 15): empty #11
W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_8202/cgroup.procs: No such file or directory
I/[LgeWidgetLib]LgeAppWidgetHostView( 1890): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1890): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1890): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1890): getTextAfterCursor on inactive InputConnection
I/[LGHome]EVENT( 1890): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1890): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/ResourcesManager( 8620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8620): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1890): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1890): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1890): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1890): Timeline: Activity_idle id: android.os.BinderProxy@137010c8 time:1907517
E/SharedPreferencesImpl( 1890): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak

```
