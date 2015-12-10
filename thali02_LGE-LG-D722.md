#### Test 50650278c17c777_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/art     (  838): Explicit concurrent mark sweep GC freed 14843(675KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.435ms total 163.853ms
V/TelephonyAutoProfiling( 1746): [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
D/PhoneInterfaceManager( 1746): [PhoneIntfMgr] handleMessage : 2
D/PhoneInterfaceManager( 1746): [PhoneIntfMgr] handleMessage : 3
D/AndroidRuntime( 5520): 
D/AndroidRuntime( 5520): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5520): CheckJNI is OFF
--------- beginning of system
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{3e6afe9d type 0 when 1449746222045 com.android.vending} when 1449746222045
D/Finsky  ( 4992): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  838): android: cancelAsUser(2) by android
D/AndroidRuntime( 5520): Calling main entry com.android.commands.am.Am
I/ActivityManager(  838): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  838): setTaskToReturnTo : TaskRecord{30019637 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  838): setTaskToReturnTo : TaskRecord{30019637 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  838): AppWindowTokenEx init.. 
D/ContextHelper(  838): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  838): Focus left window: Window{35311e18 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5520): Shutting down VM
D/SplitWindow(  838): check instance of lgWin Window{29fae909 u0 Starting com.test.thalitest}
I/ActivityManager(  838): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5540 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1935): Closing mic
I/MicrophoneInputStream( 1935): mic_close com.google.android.apps.gsa.speech.audio.u@1664daad
V/AudioRecord( 1935): stop()
I/WindowStateAnimator(  838): Starting window displayed
D/AudioRecord( 1935): AudioRecord->stop()
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioFlinger(  276): Record stopped OK
V/AudioPolicyManager(  276): stopInput() input 17
I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioPolicyService(  276): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  276): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  276): ThreadBase::setParameters() routing=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9e71484,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb3ddc000
D/audio_hw_primary(  276): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1369): draw background and invalidate : color = f000000
D/BarTransitions( 1369): draw background and invalidate : color = 100f0f0f
V/audio_hw_primary(  276): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  276): disable_audio_route: enter: usecase(7)
,V/msm8974_platform_lge(  276): LGE_platform_add_backend_name: enter: 144
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
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
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
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb3ddc000
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioPolicyManager(  276): releaseInput() 17
V/AudioPolicyManager(  276): closeInput(17)
V/AudioFlinger(  276): releasing 16 from 1935 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/AudioFlinger(  276): closeInput() 17
V/AudioSystem(  276): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  838): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1935): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): ThreadBase::exit
V/AudioSystem( 1746): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioSystem( 3111): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): RecordThread 0xb3ddc000 exiting
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  276): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  276): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioSystem( 2687): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  276): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  276): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  276): releaseInput() exit
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioFlinger(  276): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  276): AudioCommandThread() processing update audio port list
V/AudioFlinger(  276): removeClient_l() pid 1935, calling pid 276
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1935): Stopping hotword detection.
D/libc-netbsd( 4992): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4992): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4992): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4992): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/HotwordRecognitionRnr( 1935): Hotword detection finished
W/Finsky  ( 4992): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  838): android: cancelAsUser(2) by android
D/libc-netbsd( 4992): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4992): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ContextHelper( 5540): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5540): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  838): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5569 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/LibraryLoader( 5540): Time to load native libraries: 2 ms (timestamps 3444-3446)
I/LibraryLoader( 5540): Expected native library version number "",actual native library version number ""
I/art     ( 1728): Explicit concurrent mark sweep GC freed 27607(1630KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 13MB/22MB, paused 1.620ms total 102.226ms
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WebViewChromiumFactoryProvider( 5540): Binding Chromium to main looper Looper (main, tid 1) {393f01ac}
I/LibraryLoader( 5540): Expected native library version number "",actual native library version number ""
I/chromium( 5540): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/NotificationManager(  838): android: cancelAsUser(2) by android
W/ResourcesManager( 5569): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5569): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/BrowserStartupController( 5540): Initializing chromium process, singleProcess=true
W/art     ( 5540): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5540): ApplicationContext is null in ApplicationStatus
W/chromium( 5540): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
D/libc-netbsd( 4992): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4992): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 4992): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/MultiDex( 5569): VM with version 2.1.0 has multidex support
I/MultiDex( 5569): install
I/MultiDex( 5569): VM has multidex support, MultiDex support library is disabled.
W/chromium( 5540): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
V/JNIHelp ( 5569): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/libEGL  ( 5540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5540): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5540): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5540): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5540): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5540): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5540): Remote Branch: 
I/Adreno-EGL( 5540): Local Patches: 
I/Adreno-EGL( 5540): Reconstruct Branch: 
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
W/ActivityThread( 5569): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5569): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e4f20e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5569): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5569): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5569): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1728): callingUid 10006, callindPid: 1728
,E/MDM     ( 1728): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5279): Restart initialization of location
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr( 5569): Reading stored module config
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AudioPolicyService(  276): registerClient() client 0xb551c880, uid 10316
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39d47346:true
,D/BluetoothAdapter( 5540): 393251992: getState() :  mService = null. Returning STATE_OFF
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
,D/ChimeraCfgMgr( 5569): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 5569): Connecting to CarCallService...
,D/NativeLibraryUtils( 5569): Install completed successfully. count=14 extracted=0
I/art     ( 5569): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5569): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/art     ( 5540): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5540): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5540): CordovaWebView is running on device made by: LGE
,D/CAR.SERVICE( 5569): com.google.android.projection.gearhead isn't installed.
W/art     ( 5540): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5540): Attempt to remove local handle scope entry from IRT, ignoring
D/CAR.TEL.Service( 5569): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5569): Creating a new PhoneAdapter instance
W/ActivityManager(  838): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5569): setListener: com.google.android.gms.car.dn@3ec1f835
W/ActivityManager(  838): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5569): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5569): Starting CarCallService with initial phone null
I/NotificationManager( 5569): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Activity( 5540): Activity.onPostResume() called 
,D/OpenGLRenderer( 5540): Render dirty regions requested: true
I/OpenGLRenderer( 5540): Initialized EGL, version 1.4
D/OpenGLRenderer( 5540): Enabling debug mode 0
,D/Atlas   ( 5540): Validating map...
,D/SplitWindow(  838): check instance of lgWin Window{9fdfcda u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/CAR.SERVICE( 5569): Package validated; name: com.android.vending
,W/chromium( 5540): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/NotificationManager( 4992): com.android.vending: cancel(10436) by com.android.vending
,D/InputDispatcher(  838): Focus entered window: Window{9fdfcda u0 com.test.thalitest/com.test.thalitest.MainActivity}
V/Finsky  ( 4992): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/InputMethodManagerService(  838): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  838): Displayed com.test.thalitest/.MainActivity: +1s330ms
I/Timeline(  838): Timeline: Activity_windows_visible id: ActivityRecord{11fbe7a4 u0 com.test.thalitest/.MainActivity t220} time:94240
,I/Timeline( 5540): Timeline: Activity_idle id: android.os.BinderProxy@1cec4bc8 time:94255
W/BindingManager( 5540): Cannot call determinedVisibility() - never saw a connection for the pid: 5540
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/libc-netbsd( 4992): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4992): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4992): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4992): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4992): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{1375302c type 0 when 1449746223960 com.android.vending} when 1449746223960
,D/Finsky  ( 4992): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1728): client connected with version: 8296000
,D/Finsky  ( 4992): [584] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 94736443040; DSPS: 3195759; Offset : -2793884044
,D/libc-netbsd( 4992): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4992): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4992): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4992): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/JsMessageQueue( 5540): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5540): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622845952
,D/JX-Cordova( 5540): jxcore cordova android initializing
I/art     ( 5540): CheckpointMarkThreadRoots callback created = 0xb04ecd20
,I/art     ( 5540): CheckpointMarkThreadRoots callback created = 0xb04eccf0
,W/jxcore-log( 5540): Initializing JXcore engine
,W/jxcore-log( 5540): JXcore engine is ready
W/jxcore-log( 5540): Starting JXcore engine
,W/.test.thalitest( 5540): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5400]" dev="sockfs" ino=5400 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5540): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 5540): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7683]" dev="sockfs" ino=7683 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5540): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5540): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5540): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26754]" dev="sockfs" ino=26754 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5540): Platform android
W/jxcore-log( 5540): 
W/jxcore-log( 5540): Process ARCH arm
W/jxcore-log( 5540): 
,I/jxcore-log( 5540): JXcore Cordova bridge is ready!
I/jxcore-log( 5540): 
,W/jxcore-log( 5540): JXcore engine is started
I/chromium( 5540): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 5540): Toggling radios to true
I/jxcore-log( 5540): 
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  838): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  838): Message: 1
D/BluetoothManagerService(  838): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(393251992)( 1988): onBind()
,D/BluetoothManagerService(  838): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/WifiServiceImplEx(  838): setWifiEnabled: true pid=5540, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/BluetoothManagerService(  838): Message: 40
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/WifiService(  838): setWifiEnabled: true pid=5540, uid=10316
D/Ulp_jni (  838): JNI:system_update. Event-4
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
D/WifiServiceImplEx(  838): disconnect pid=5540, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  838): reconnect pid=5540, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5540): Radios toggled
I/jxcore-log( 5540): 
I/bluedroid( 1988): config_hci_snoop_log
,D/BluetoothManagerService(  838): Calling onBluetoothServiceUp callbacks
I/LGFTMITEM(  838): [GET_FTM][id=6], offset=12288
D/BluetoothManagerService(  838): Broadcasting onBluetoothServiceUp() to 9 receivers.
E/WifiHW  (  838): Wifi MAC Address = a0:39:f7:70:12:80
E/WifiHW  (  838): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  838): band=b
E/WifiHW  (  838): ": cur_etheraddr=a0:39:f7:70:12:80
,V/LGMDMManagerInternal( 1988): Create singleton instance
,D/SoftapController(  271): Softap fwReload - Ok
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring down wlan0
D/CommandListener(  271): Clearing all IP addresses on wlan0
E/WifiHW  (  838): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
D/WifiMonitor(  838): startMonitoring(wlan0) with mConnected = false
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:08.149 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5685 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [2]
,I/wpa_supplicant( 5677): Successfully initialized wpa_supplicant
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothAdapterService(393251992)( 1988): enable() - Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1988): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1988): Setting state to 11
I/BluetoothAdapterState( 1988): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(393251992)( 1988): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  838): Message: 60
,I/ActivityManager(  838): Killing 5254:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 10 -> 11
D/BluetoothAdapterService(393251992)( 1988): processStart()
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/wpa_supplicant( 5677): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5677): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BtSettings.ProfileConfig( 1988): Unable to read settings
D/BtSettings.ProfileConfig( 1988): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1988): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1988): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): processStart() - Make Bond State Machine
D/BluetoothBondStateMachine( 1988): make
,D/BluetoothAdapterService( 1988): setAdapterService() - set to: null
I/BluetoothBondStateMachine( 1988): StableState(): Entering Off State
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/LGBluetoothServiceAdapter( 1988): [BTUI] check adapter is available - true : set adapter available.
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 1988): Unable to read settings
D/BtSettings.ProfileConfig( 1988): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1988): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_5254/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Process com.google.android.gm (pid 5086) has died
,D/LGBluetoothAPIService( 1799): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 1988): Received start request. Starting profile...
D/BluetoothHeadset(  838): Proxy object connected
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothHeadset( 1746): Proxy object connected
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/LGBluetoothHeadsetServiceJni( 1988): classInitNative: succeeds
,I/[SystemUI]BluetoothHandler( 1369): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,D/LGBluetoothFeatureConfig( 1988): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1988): classInitNative: succeeds
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/HeadsetStateMachine( 1988): make
D/BluetoothHeadset( 1746): Proxy object connected
,D/BluetoothHeadset( 1746): Proxy object connected
I/ActivityManager(  838): Process com.lge.qremote (pid 5058) has died
,D/UEI.SmartControl( 4773): Service.onUnbind: IControl
D/UEI.SmartControl( 4773): Service.onDestroy
D/UEI.SmartControl( 4773): Shutdown IRRCPlayer... 
W/irrc_jni( 4773): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4773): ~IrrcClient ++ 
D/irrcClient( 4773): ~IrrcClient -- 
W/irrc_jni( 4773): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4773): Blaster closed
D/UEI.SmartControl( 4773): Blaster closed
D/UEI.SmartControl( 4773): Shut down QS...
D/UEI.SmartControl( 4773): Stopped file observer...
I/UEI.SmartControl( 4773): QS lib stop result = true
D/UEI.SmartControl( 4773): QS shutdown complete
D/HeadsetStateMachine( 1988): max_hf_connections = 1
I/bluedroid( 1988): get_profile_interface handsfree
I/bt-btif ( 1988): btif_hf_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): max_hf_clients = 1
D/bt-btif ( 1988): btif_max_hf_clients = 1
D/bt-btif ( 1988): btif_enable_service: current services:0xa05c6330
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
V/ToneGenerator( 1988): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  276): registerClient() client 0xb551c840, uid 1002
,V/AudioPolicyManager(  276): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  276): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  276): getOutput() returns output 2
V/AudioFlinger(  276): registerClient() client 0xb3c1bb08, pid 1988
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  276): thread 0xb5651000 type 0 TID 1289 waking up
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  276): thread 0xb56eb000 type 0 TID 1290 waking up
V/AudioFlinger(  276): thread 0xb5735000 type 0 TID 1293 waking up
V/AudioSystem( 1988): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  276): ioConfigChanged() event 0, ioHandle 6
,V/AudioSystem(  276): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1988): ioConfigChanged() event 0, ioHandle 6
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem(  276): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1988): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem(  276): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1988): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  276): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  276): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  838): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  838): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3111): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3111): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  838): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  838): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1369): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3111): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1369): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3111): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 6
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
V/AudioSystem( 1988): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1935): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1935): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2687): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2687): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1988): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1988): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 3111): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3111): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1746): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1746): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1935): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1935): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1935): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2687): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1935): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2687): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2687): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2687): ioConfigChanged() opening already existing output! 2
V/ToneG,enerator( 1988): Create Track: 0xb4909480
V/AudioTrack( 1988): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1988): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
I/AudioFlinger(  276): isAudioPlaybackHookOn() false
D/AudioTrack( 1988): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  276): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  276): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  276): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  276): getOutput() returns output 2
V/AudioSystem( 1988): getLatency() output 2, latency 50
V/AudioSystem( 1988): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1988): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1988): Create normal PCM 0x1 Track
V/AudioFlinger(  276): createTrack() lSessionId: 22
V/AudioFlinger(  276): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 1
D/CAR.SERVICE( 5569): mConnectedToCar = false, abort
W/ResourcesManager( 5685): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5685): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb5651000
W/ResourcesManager( 5685): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
V/AudioTrack( 1988): Flags here  0x4 
V/AudioTrack( 1988): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
W/ResourcesManager( 5685): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5685): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/AudioFlinger(  276): acquiring 22 from 1988, for 1988
V/AudioFlinger(  276):  added new entry for 22
V/ToneGenerator( 1988): ToneGenerator INIT OK, time: 99243
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/HeadsetStateMachine( 1988): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1988): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1988): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1988): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
V/AudioFlinger(  276): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1988
D/audio_hw_primary(  276): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  276): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
V/voice   (  276): voice_set_parameters: exit with code(0)
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  276): platform_set_parameters: enter: bt_samplerate=8000
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothA2dp(  838): Proxy object connected
D/A2dpService( 1988): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 1988): classInitNative: succeeds
V/Avrcp   ( 1988): make
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
D/Avrcp   ( 1988): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1988): get_profile_interface avrcp
I/bt-btif ( 1988): btif_rc_get_interface
I/bt-btif ( 1988): ## init ##
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
I/LGBluetoothAvrcpServiceJni( 1988): classInitNative: succeeds
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
I/LGBluetoothAvrcpAdapter( 1988): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1988): initNative: succeeds
V/ToneGenerator( 1988): ToneGenerator destructor
V/ToneGenerator( 1988): stopTone
V/ToneGenerator( 1988): Delete Track: 0xb4909480
I/BluetoothAvrcpBrcmAdapterJni( 1988): classInitBrcmNative
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
V/AudioTrack( 1988): ~AudioTrack, releasing session id from 1988 on behalf of 1988
V/AudioFlinger(  276): remove track (4099) and delete from mixer
V/AudioPolicyService(  276): AudioCommandThread() adding release output 2
V/AudioFlinger(  276): releasing 22 from 1988 for 1988
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/AudioPolicyService(  276): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  276): releaseOutput() 2
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioFlinger(  276): PlaybackThread::Track destructor
V/AudioFlinger(  276): removeClient_l() pid 1988, calling pid 276
I/BluetoothAvrcpBrcmAdapterJni( 1988): initBrcmNative
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/LGMDMManager( 1988): Create singleton instance
E/ActivityThread( 5569): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@27d5767d that was originally bound here
E/ActivityThread( 5569): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@27d5767d that was originally bound here
E/ActivityThread( 5569): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5569): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5569): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5569): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5569): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5569): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5569): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5569): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5569): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5569): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5569): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5569): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5569): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5569): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5569): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5569): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5569): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5569): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5569): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5569): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5569): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5569): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/BluetoothAdapterState( 1988): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
E/ActivityThread( 5569): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@32243a6c that was originally bound here
E/ActivityThread( 5569): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@32243a6c that was originally bound here
E/ActivityThread( 5569): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5569): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5569): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5569): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5569): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5569): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5569): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5569): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5569): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5569): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5569): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5569): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5569): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5569): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5569): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5569): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5569): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5569): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5569): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5569): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5569): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  838): Unbind failed: could not find connection for android.os.BinderProxy@a2a8924
,V/AudioService(  838): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  838): No RCC entry present to update
E/RemoteController( 1988): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1988): classInitNative
I/BluetoothA2dpServiceJni( 1988): classInitNative: succeeds
D/A2dpStateMachine( 1988): make
I/bluedroid( 1988): get_profile_interface a2dp
I/bt-btif ( 1988): btif_av_get_src_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): btif_enable_service: current services:0xa05c6330
I/IndexDatabaseHelper( 5685): Using schema version: 115
I/LGBluetoothA2dpServiceJni( 1988): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1988): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/IndexDatabaseHelper( 5685): Index is fine
D/LGBluetoothPowerControlManager( 1988): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1988): [BTUI] init
D/LGBluetoothPowerControlManager( 1988): [BTUI] init : getProfileProxy
,D/BluetoothManagerService(  838): Message: 30
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/A2dpStateMachine( 1988): Enter Disconnected: -2
I/BluetoothHidServiceJni( 1988): classInitNative: succeeds
D/HidService( 1988): Received start request. Starting profile...
I/bluedroid( 1988): get_profile_interface hidhost
I/bt-btif ( 1988): btif_hh_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): btif_enable_service: current services:0xa05c6330
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/HeadsetStateMachine( 1988): Proxy object connected
D/LGBluetoothHfpAdapter( 1988): [BTUI] queryPhoneState
I/BluetoothHealthServiceJni( 1988): classInitNative: succeeds
,D/HealthService( 1988): Received start request. Starting profile...
I/bluedroid( 1988): get_profile_interface health
I/bt-btif ( 1988): btif_hl_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): Process name (droid.bluetooth)
D/bt-btif ( 1988): btif_hl_soc_thread_init
D/bt-btif ( 1988): create_thread: entered
D/bt-btif ( 1988): create_thread: thread created successfully
I/LGBluetoothHealthServiceJni( 1988): classInitNative: succeeds
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/bt-btif ( 1988): entered btif_hl_select_thread
D/bt-btif ( 1988): btif_hl_select_wakeup_init
D/bt-btif ( 1988): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1988): max_s=55 
D/bt-btif ( 1988): set curr_set = org_set 
I/BluetoothPanServiceJni( 1988): classInitNative(L105): succeeds
D/PanService( 1988): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1988): initializeNative(L110): pan
I/bluedroid( 1988): get_profile_interface pan
D/bt-btif ( 1988): stack_initialized = 0, btpan_cb.enabled:0
,I/LGBluetoothPanAdapter( 1988): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
I/BtGatt.JNI( 1988): classInitNative(L901): classInitNative: Success!
,D/BtGatt.DebugUtils( 1988): handleDebugAction() action=null
D/BtGatt.GattService( 1988): Received start request. Starting profile...
D/BtGatt.GattService( 1988): start()
I/bluedroid( 1988): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1988): advertise manager created
I/LGBluetoothGattAdapter( 1988): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1988): setGattService:  set to: null
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
,D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 1988): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1988): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
I/LGBluetoothMapAdapter( 1988): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1988): BluetoothMapBinder()
D/BluetoothMapService( 1988): Received start request. Starting profile...
D/BluetoothMapService( 1988): start()
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/art     (  838): Explicit concurrent mark sweep GC freed 18456(882KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 3.454ms total 186.310ms
,D/BluetoothMapEmailSettingsLoader( 1988): Found 0 applications
D/BluetoothMapEmailAppObserver( 1988): createReceiver()
D/BluetoothMapEmailAppObserver( 1988): initObservers()
D/BluetoothMapEmailAppObserver( 1988): getEnabledAccountItems()
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
,I/BluetoothSAPServiceJni( 1988): classInitNative(L170): succeeds
D/SapService( 1988): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1988): initializeNative(L175): sap
I/bluedroid( 1988): get_profile_interface sap
I/bt-btif ( 1988): btif_sc_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): btif_enable_service: current services:0xa05c6330
I/LGBluetoothSapAdapter( 1988): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1988): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1988): [BTUI] initSapManager
D/WiFiOffLoadUpdatePriority( 5685): remove : truetruefalse
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
,D/LgeBluetoothSimManager( 1746): [BTUI] SAP_ENABLE_EVT
,D/WiFiOffLoadUpdatePriority( 5685): remove2
V/WiFiOffLoadSharedPrefsUtils( 5685): save wifi state
V/BluetoothFTPServiceJni( 1988): classInitNative
V/WiFiOffLoadSharedPrefsUtils( 5685): save remove
D/WiFiOffLoadBroadcast( 5685): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
I/BluetoothFTPServiceJni( 1988): classInitNative(L271): succeeds
D/WiFiOffLoadBroadcast( 5685): S: false, R: true
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/BluetoothFTPService( 1988): BluetoothFtpBinder()
,D/**BluetoothFTPService( 1988): Received start request. Starting profile...
V/BluetoothFTPService( 1988): FTP-Server Service start
I/ActivityManager(  838): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5719 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothFTPServiceJni( 1988): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1988): get_profile_interface ftp
I/bt-btif ( 1988): btif_fts_get_interface
I/bt-btif ( 1988): init
D/bt-btif ( 1988): btif_enable_service: current services:0xa05c6330
D/BluetoothFTPServiceJni( 1988): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/LGBluetoothFeatureConfig( 1988): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1988): classInitNative
I/BluetoothOPPServiceJni( 1988): classInitNative(L373): succeeds
V/OppService( 1988): Opp initBinder
D/**OppService( 1988): Received start request. Starting profile...
D/OppService( 1988): Starting OppService 
,D/LGBluetoothOppAdapter( 1988): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1988): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 1988): send message
D/BluetoothOppPreference( 1988): Dumping Names:  
D/BluetoothOppPreference( 1988): {}
D/BluetoothOppPreference( 1988): Dumping Channels:  
D/BluetoothOppPreference( 1988): {}
,D/OppService( 1988): Start()
W/BluetoothOPPServiceJni( 1988): initOppNative
D/BluetoothOPPServiceJni( 1988): initOppNative(L383): OPP
I/bluedroid( 1988): get_profile_interface opp
I/bt-btif ( 1988): btif_op_get_interface
D/BluetoothOPPServiceJni( 1988): initOppNative(L411): mOppCallbacksObj 3147006
D/BluetoothOPPServiceJni( 1988): initOppNative(L413): calling OPP init
I/bt-btif ( 1988): btif_opp_init
D/bt-btif ( 1988): btif_enable_service: current services:0xa05c6330
D/BluetoothOPPServiceJni( 1988): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1988): initOppNative(L430): mOppCallbacksObj 3147006
V/OppService( 1988): setOppService(): set to: com.broadcom.bt.service.opp.OppService@1877fabe
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/BluetoothA2dp( 1988): Proxy object connected
D/LGBluetoothPowerControlManager( 1988): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@266fd71f
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1988): pendingUpdate is :  true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1988): Deleted complete outbound shares, number =  0
,D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
,V/PanService( 1988): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 1988): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1988): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@3504ca on behalf of 
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1988): Handler(): got msg=1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom,.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@3c44c63b on behalf of 
V/BluetoothOppNotification( 1988): update too frequent, put in queue
D/BluetoothAdapterService( 1988): Profile still not running:com.broadcom.bt.service.opp.OppService
V/OppService( 1988): pendingUpdate is :  false
V/BluetoothPbapReceiver( 1988): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1988): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1988): ***********state = 11
E/OppService( 1988): UpdateThread is Completed
V/BluetoothOppNotification( 1988): new notify threadi!
V/BluetoothOppNotification( 1988): send delay message
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - All profile services started.
V/OppService( 1988): ContentObserver received notification
D/BluetoothAdapterState( 1988): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1988): enable
I/bt-btif ( 1988): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1988): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/OppService( 1988): ContentObserver received notification
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 1988): pendingUpdate is :  true
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
I/bt_hci_bdroid( 1988): init
I/bt_vendor( 1988): init
I/bt_vnd_conf( 1988): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@2a509158 on behalf of 
I/GKI_LINUX( 1988): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1988): btu_task pending for preload complete event
V/BluetoothOppNotification( 1988): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@12a6e2b1 on behalf of 
,I/bt_vnd_conf( 1988): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1988): libbt-hci init returns 0
V/OppService( 1988): pendingUpdate is :  false
E/OppService( 1988): UpdateThread is Completed
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@1006a396 on behalf of 
V/BluetoothOppNotification( 1988): outbound: succ-0  fail-0
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1988): outbound notification was removed.
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@34af8b17 on behalf of 
,V/BluetoothOppNotification( 1988): inbound: succ-0  fail-0
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1988): inbound notification was removed.
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@15e96b04 on behalf of 
D/BluetoothPermissionRequest( 5685): onReceive
,D/LGBluetoothFeatureConfig( 5685):  get() - isFeatureLoaded : false
D/Tethering(  838): sendTetherStateChangedBroadcast 1, 0, 0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2200556d:true
,I/bt_userial_vendor( 1988): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1988): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1988): device fd = 68 open
E/wpa_supplicant( 5677): USIM:  scard_init function
,I/wpa_supplicant( 5677): rfkill: Cannot open RFKILL control device
V/BluetoothSapReceiver( 1988): [BTUI] checkServiceStart
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 9
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 4
D/LGBluetoothStateChangeReceiver( 1988): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1988): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1988): hw_config_cback state=1
,D/PCSuite ( 5719): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/bt_hwcfg( 1988): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1988): hw_config_cback state=4
D/bt_hwcfg( 1988): Chipset Name: BCM4334B0
D/bt_hwcfg( 1988): Chipset BCM4334B0
D/bt_hwcfg( 1988): Target name = [BCM4334B0]
I/bt_hwcfg( 1988): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1988): hw_config_cback state=2
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1988): hw_config_cback state=3
I/bt_hwcfg( 1988): bt vendor lib: set UART baud 4000000
I/ActivityManager(  838): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5751 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1988): hw_config_cback state=5
,I/wpa_supplicant( 5677): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/UsbSettingsReceiver( 5685): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5685): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5685): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5685): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5685): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/wpa_supplicant( 5677): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiStateMachine(  838): MAC Addr from driver = a0:39:f7:70:12:80
,D/WifiOffDelayIfNotUsed(  838): setPowerSaveActivated(false)
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [3]
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.396 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.WIFI_STATE_CHANGED at null
E/WifiServerServiceExt(  838): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : state:0 event:3
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
D/UsbSettingsControl( 5685): [AUTORUN] getUsbConnected() : connected=true
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/UsbSettingsReceiver( 5685): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5685): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5685): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5685): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5685): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 5685): [AUTORUN] setTetherStatus() : status=false
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
E/WifiConfigStore(  838): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiStateMachine(  838): enableVerboseLogging : level 2
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
W/Settings( 5135): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  838): Setting OUI to DA-A1-19
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiNative-HAL(  838): Setting external_sim to 1
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiNative-HAL(  838): startHal
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x9b4118ec
I/WifiHAL (  838): Initializing wifi
I/WifiHAL (  838): Creating socket
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiHAL (  838): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  838): Did set static halHandle = 0xb07776c0
D/wifi    (  838): halHandle = 0xb07776c0, mVM = 0xb487c280, mCls = 0x301d0a
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x9b41189c
D/wifi    (  838): array field set
I/WifiNative-HAL(  838): interface[0] = wlan0
I/WifiNative-HAL(  838): interface[1] = p2p0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/wifi    (  838): setting scan oui 0x9a1d8a18
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiHAL (  838): Sending mac address OUI
E/WifiHAL (  838): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  838): Setting OUI to DA-A1-19
I/WifiNative-HAL(  838): startHal
D/wifi    (  838): setting scan oui 0x9a1d8a18
D/WifiHAL (  838): Sending mac address OUI
E/WifiHAL (  838): failed to set scanning mac OUI; result = -95
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiNative-HAL(  838): Waiting for HAL events mWifiHalHandle=-1334348096
D/wifi    (  838): waitForHalEvents called, vm = 0xb487c280, obj = 0x301d0a, env = 0xaaf04dd0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/wifi    (  838): getStaticLongField sWifiHalHandle 0x98f89b2c
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1799): Supplicant Connection state is changed : true
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1799): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1799): Set the WFDS Monitor: true
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiHS20(  838): hidePasspointNotification off =false
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsMonitor( 1799): WfdsMonitorThread create
D/WfdsMonitor( 1799): WFDS Monitor is created and started
D/WfdsService( 1799): WiFi: Supplicant connection re-established
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring up p2p0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiMonitor(  838): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService(  838): P2pEnablingState
D/LGWifiP2pService(  838): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2p socket connection successful
D/LGWifiP2pService(  838): P2pEnabledState
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/CtrlSupplicant( 1799): Access OK "@android:wpa_wlan0"
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/LGWifiP2pService(  838): [LGE_P2P] initializeP2pSettings() check postfix
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): before postfix = G3s-1
D/WifiServerServiceExt(  838): postfix byte check : 5
D/LGWifiP2pService(  838): after postfix = G3s-1
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiScanningService(  838): SCAN_AVAILABLE : 3
D/WifiScanningService(  838): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  838): startHal
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/RttService(  838): SCAN_AVAILABLE : 3
D/RttService(  838): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/wifi    (  838): getting scan capabilities on interface[0] = 0x9a1d8a18
D/WifiHAL (  838): Creating message to get scan capablities; iface = 24
D/wifi    (  838): failed to get capabilities : -95
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/WifiScanningService(  838): could not get scan capabilities
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.488 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
E/CtrlSupplicant( 1799): Succeed to open control connection
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/CtrlSupplicant( 1799): Succeed to open monitor connection
D/WfdsMonitor( 1799): Supplicant connection established
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1799): Connected to the supplicant for wfds
D/WifiNative-HAL(  838): p2pGetDeviceAddress
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D,/WifiNative-HAL(  838): p2pGetDeviceAddress returning a2:39:f7:70:12:80
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5685): remove : truetruetrue
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): DeviceAddress: a2:39:f7:70:12:80
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1799): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiServerServiceExt(  838): set CMD_ADD_DEFAULT_PROFILE
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiServerServiceExt(  838): setWifiDualbandAPConnection band : 1
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1799): Update P2p Interface State: 3
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/wpa_supplicant( 5677): nWIFIDualbandAPConnection: 1
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): sending p2p persistent groups changed broadcast
I/WifiServerServiceExt(  838): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5677): disconnect_rssi_lvl: -100
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): sending p2p connection changed broadcast
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): InactiveState
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiServerServiceExt(  838): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5677): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1799): WifiP2pState is changed : true
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiServerServiceExt(  838): set CMD_UPDATE_DEFAULT_PROFILE
D/WfdsService( 1799): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1799): Receive the WFDS_ENABLE Method
D/WfdsService( 1799): Set the WFDS Monitor: true
D/WfdsService( 1799): Connected to the supplicant for wfds
D/WfdsJNI ( 1799): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 5677): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsJNI ( 1799): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5677): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1799): doCommand: WFDS_CLEAR_PD_INFO
I/wpa_supplicant( 5677): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1799): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1799): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1799): selectPreferredScanChannel [6]
D/WfdsService( 1799): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): InactiveState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
E/WifiServerServiceExt(  838): No p2p device connected
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGWifiP2pService(  838): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WfdsService( 1799): isConnected: false
D/WfdsService( 1799): GroupInfoAvailable: mGroupInfo is null
W/WfdsService( 1799): DefaultState - msg [9441285] is not handled
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
W/ResourcesManager( 5751): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/wpa_supplicant( 5677): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
I/wpa_supplicant( 5677): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5751): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.619 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 5677): wlan0: Associated with c0:ff:d4:d3:aa:48
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/LocSvc_java(  838): onReceive
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.648 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/GONS    ( 1746): GONS isTestMode: false Country: 
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateSCANNING
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.662 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/bt_hwcfg( 1988): hw_config_cback opco,de:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,I/wpa_supplicant( 5677): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5677): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WiFiOffLoadUpdatePriority( 5685): remove1
V/WiFiOffLoadSharedPrefsUtils( 5685): save remove
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.707 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1988): hw_config_cback state=6
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.712 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt_hwcfg( 1988): hw_config_cback state=6
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateASSOCIATING
D/bt_hwcfg( 1988): ,hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateASSOCIATED
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiServiceExtension(  838): setVHTCapabilityType  : false
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/WiFiOffLoadBroadcast( 5685): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5685): S: false, R: false
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1988): hw_config_cback state=6
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1988): hw_config_cback state=6
I/WifiServerServiceExt(  838): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  838): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  838): setSecurityType  : 2
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.768 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.771 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,D/WifiExtManager(  838): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@319c3bb4
,D/ConnectivityService(  838): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  838): Got NetworkAgent Messenger
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  838): NetworkAgent connected
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  271): Setting iface cfg
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  838): StoppedState
E/WifiStateMachine(  838): Start Dhcp Watchdog 1
D/DhcpStateMachine(  838): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): WaitBeforeStartState
,D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadUpdatePriority( 5685): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5685): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5685): private wpa: "NG700" 300
I/bt_hwcfg( 1988): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1988): Settlement delay -- 100 ms
I/bt_hwcfg( 1988): Setting fw settlement delay to 100 
D/WifiServiceImplEx(  838): addOrUpdateNetwork pid=5685, uid=1000, packageName=android.uid.system:1000
,E/addOrUpdateNetwork(  838):  uid = 1000 SSID "NG700" nid=0
I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:09.839 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine(  838): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28f74613 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28f74613 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  838): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  838): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  838): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateCOMPLETED
E/WifiConfigStore(  838):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1988): hw_config_cback state=2
,D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1988): hw_config_cback state=7
I/bt_hwcfg( 1988): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1988): Setting local bd addr to F8:95:C7:87:85:54
D/bt_hwcfg( 1988): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1988): hw_config_cback state=8
I/bt_hwcfg( 1988): vendor lib fwcfg completed
I/bt-btif ( 1988): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1988): btu_task received preload complete event
,I/        ( 1988): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1988): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1988): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1988): BTE_InitTraceLevels -- TRC_PROTOCOL,0
E/WifiConfigStore(  838): Setting BSSID for "NG700"WPA_PSK to any
D/WiFiOffLoadUpdatePriority( 5685):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5685): configuration updated: 0
,I/WifiServerServiceExt(  838): set CMD_UPDATE_DEFAULT_PROFILE
D/WiFiOffLoadUpdatePriority( 5685): configuration saved: true
D/PCSuite ( 5719): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5778 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  838): Killing 4773:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,E/bt-btif ( 1988): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 1988): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1988): warning : media task started media_task_refcnt 1 
D/BT_PROF_AUDIO( 1988): created moving average (N=100)
D/BT_PROF_AUDIO( 1988): reset rate average
W/bt-btif ( 1988): overflow 0, enter 0, exit 0
E/bt-btif ( 1988): Calling BTA_HhEnable
E/bt-btif ( 1988): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1988): Address is:F8:95:C7:87:85:54
W/bt-smp  ( 1988): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1988): Plain text(LSB ~ MSB) = 07 74 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1988): Encrypted text(LSB ~ MSB) = 06 e0 a1 be 07 20 8f fb 0d e3 e5 53 22 2a 3b cd 
W/bt-btm  ( 1988): Stopping oneshot timer
D/DhcpStateMachine(  838): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  838): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  838): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5797): version 5.5.6 starting
,E/dhcpcd  ( 5797): get_duid: Read-only file system
V/BluetoothOppNotification( 1988): new notify threadi!
V/BluetoothOppNotification( 1988): send delay message
,V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@3c15f8ed on behalf of 
V/BluetoothOppNotification( 1988): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@3b816322 on behalf of 
V/BluetoothOppNotification( 1988): outbound: succ-0  fail-0
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1988): outbound notification was removed.
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@1097c1b3 on behalf of 
V/BluetoothOppNotification( 1988): inbound: succ-0  fail-0
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 1988): inbound notification was removed.
V/BluetoothOppProvider( 1988): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1988): created cursor android.database.sqlite.SQLiteCursor@11143370 on behalf of 
I/dhcpcd  ( 5797): wlan0: rebinding lease of 192.168.1.134
,W/libprocessgroup(  838): failed to open /acct/uid_10089/pid_4773/cgroup.procs: No such file or directory
D/BluetoothAdapterProperties( 1988): Name is: G3s-1
D/BluetoothManagerService(  838): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  838): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 1988): Scan Mode:20
D/BluetoothAdapterProperties( 1988): Discoverable Timeout:120
E/bt-btif ( 1988): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1988): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1988): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1988): BTA_JvEnable
E/bt-btif ( 1988): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 1988): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 1988): init_hci_slots(L136): in
D/IOP_DB_BT( 1988): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1988): db_open: db_open : handle 2690451420l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1988): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1988): db_query: result 1
I/        ( 1988): iop_db_open: iop_db_open status 0
E/bt-btif ( 1988): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1988): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1988): bta_pan_co_init
D/bte_conf( 1988): Device ID record 1 : primary
D/bte_conf( 1988):   vendorId            = 00c4
D/bte_conf( 1988):   vendorIdSource      = 0001
D/bte_conf( 1988):   product             = 13a1
D/bte_conf( 1988):   version             = 1000
D/bte_conf( 1988):   clientExecutableURL = 
D/bte_conf( 1988):   serviceDescription  = 
D/bte_conf( 1988):   documentationURL    = 
D/bte_conf( 1988): bte_load_did_conf no section named DID2.
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1988): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1988): ScanMode =  20
D/BluetoothAdapterProperties( 1988): State =  11
D/BluetoothAdapterProperties( 1988): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1988): Setting state to 12
I/BluetoothAdapterState( 1988): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(393251992)( 1988): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  838): Message: 60
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  838): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset(  838): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 1988): Entering On State
I/BluetoothAdapterState( 1988): Entering On State from state = 11
D/BluetoothA2dp( 1988): onBluetoothStateChange: up=true
E/bt-btif ( 1988): btif_hf_upstreams_evt: wrong handle = 12336 
I/bt-btif ( 1988): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1988): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 1988): onOpcStateChange()
I/bt-btif ( 1988): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1988): ops_state_cb(L223):  ops_state_cb state:0
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/OppService( 1988): onOpsStateChange() :0
I/bt-btif ( 1988): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1988): operation_cmpl_callback(L192):  oper:3 status:0
D/BluetoothAdapterService(393251992)( 1988): isQuetModeEnabled() - Enabled = false
I/BluetoothFTPService( 1988): onFtpServerEnabled: /storage
D/BluetoothAdapterService(393251992)( 1988): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1988): [BTUI] autoConnect() : not allowed
D/BluetoothPanServiceJni( 1988): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_properties_cb
D/OppService( 1988): Recieved MESSAGE_OPC_ENABLE
D/BluetoothAdapterProperties( 1988): Scan Mode:21
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 1988): Discoverable Timeout:120
D/LGBluetoothServiceAdapter( 1988): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1988): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1988): [BTUI]         local_name: G3s-1
D/LGBluetoothFeatureConfig( 1988): isPrivacyLogsEnabled : true
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothAdapterService(393251992)( 1988): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(393251992)( 1988): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1988): [BTUI] autoConnect() : not allowed
D/BluetoothA2dp(  838): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=true
D/OppService( 1988): Recieved MESSAGE_OPS_ENABLE
E/BluetoothManagerService(  838): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothManagerService(  838): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothManagerService(  838): Message: 40
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/bt_h4   ( 1988): vendor lib postload completed
D/LGBluetoothAPIService( 1799): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1369): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
I/BluetoothMapService( 1988): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1988): STATE_ON
V/BluetoothMapService( 1988): Handler(): got msg=1
D/BluetoothMapMasInstance( 1988): Map Service startRfcommSocketListener
D/LGBluetoothAPIService( 1799): Message: 1
D/BluetoothMapMasInstance( 1988): MAS initSocket()
D/LGBluetoothAPIService( 1799): MESSAGE_BOOT_COMPLETED
D/BluetoothMapMasInstance( 1988):   masId = 00
D/BluetoothMapMasInstance( 1988):   msgTypes = 0e
D/BluetoothMapMasInstance( 1988):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1988):   SDP string = 000eSMS/MMS
,D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/LGBluetoothAPIService( 1799): [BTUI] LGBluetoothAPIService Binding Success
W/BluetoothAdapter( 1988): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1988): BTA_JvCreateRecordByUser
W/ContextImpl( 5685): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/bt-btif ( 1988): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1988): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothMapMasInstance( 1988): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1988): Accepting socket connection...
V/BluetoothPbapService( 1988): Pbap Service onCreate
V/BluetoothPbapService( 1988): Starting PBAP service
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,D/LGBluetoothPbapAdapter( 1988): [BTUI] getInstance : create
V/BluetoothPbapService( 1988): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1988): state: 12
D/LGBluetoothAPIServer( 1988): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1988): [BTUI] onBind()
V/BluetoothPbapReceiver( 1988): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1988): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1988): ***********state = 12
D/LGBluetoothAPIService( 1799): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1799): Message: 100
V/BluetoothPbapService( 1988): Handler(): got msg=1
D/LGBluetoothAPIService( 1799): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 1988): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 1988): Pbap Service initSocket
D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1988): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1988): BTA_JvCreateRecordByUser
D/LGBluetoothServiceAdapter( 1988): [BTUI] createSocketChannel FD=85 mFd=83
I/bt-btif ( 1988): BTA_JvRfcommStartServer
V/BluetoothPbapService( 1988): Succeed to create listening socket 
V/BluetoothPbapService( 1988): Accepting socket connection...
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/LocalBluetoothProfileManager( 5685): Adding local A2DP profile
D/BluetoothManagerService(  838): Message: 30
D/LocalBluetoothProfileManager( 5685): Adding local HEADSET profile
,D/BluetoothManagerService(  838): Message: 30
D/BluetoothManagerService(  838): Message: 30
D/BluetoothManagerService(  838): Message: 30
D/LocalBluetoothProfileManager( 5685): Adding local MAP profile
,D/BluetoothMap( 5685): Create BluetoothMap proxy object
D/BluetoothManagerService(  838): Message: 30
D/BluetoothManagerService(  838): Message: 30
V/BluetoothPbapService( 1988): Pbap Service onBind
D/LocalBluetoothProfileManager( 5685): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 5685): [BTUI] initUserBindClient
,D/LGDMClient( 5778): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5778): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5685): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
W/ContextImpl( 5778): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5778): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/DockEventReceiver( 5685): finishStartingService: stopping service
D/BluetoothA2dp( 5685): Proxy object connected
D/A2dpProfile( 5685): Bluetooth service connected
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothHeadset( 5685): Proxy object connected
D/HeadsetProfile( 5685): Bluetooth service connected
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,D/BluetoothInputDevice( 5685): Proxy object connected
D/HidProfile( 5685): Bluetooth service connected
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothPan( 5685): BluetoothPAN Proxy object connected
D/LGDMClient( 5778): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/PanProfile( 5685): Bluetooth service connected
D/LGDMClient( 5778): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothMap( 5685): Proxy object connected
D/MapProfile( 5685): Bluetooth service connected
D/BluetoothMap( 5685): getConnectedDevices()
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
V/BluetoothMapService( 1988): getConnectedDevices()
,D/BluetoothPbap( 5685): Proxy object connected
D/PbapServerProfile( 5685): Bluetooth service connected
D/LGBluetoothUserBindClient( 5685): [BTUI] onServiceConnected
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDMClient( 5778): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
D/BluetoothPermissionRequest( 5685): onReceive
D/LGBluetoothFeatureConfig( 5685): isPrivacyLogsEnabled : true
,D/LGBluetoothUtils( 5685): [BTUI] FileNotFound: readProperty
I/PCSuite ( 5719): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
V/BluetoothOppReceiver( 1988): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
D/PCSuite ( 5719): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5719): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/BluetoothOppManager( 1988): restoreApplicationData! falsefalsenullnull
,I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5822 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  838): Killing 5421:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10013/pid_5421/cgroup.procs: No such file or directory
,V/BluetoothSapReceiver( 1988): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 1988): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ResourcesManager( 5822): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@128edb86:true
,D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,I/ActivityManager(  838): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5845 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 6
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/[BNRBootReceiver]( 5845): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5845): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5845): Boot Receiver Return
,V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
I/ActivityManager(  838): Killing 5379:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10014/pid_5379/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 5685): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5864 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5822): Create singleton instance
,I/AudioManager( 5822): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5864): Quickset Services start...
,I/UEI.SmartControl( 5864): Manufacture = LGE
D/UEI.SmartControl( 5864): File observer start...
E/UEI.SmartControl( 5864): IR Port is disabled: false
D/UEI.SmartControl( 5864): Starting file observer...
D/UEI.SmartControl( 5864): Extracting JNI libs...
D/UEI.SmartControl( 5864): --- this system supports 32-bit or 64-bit only
I/dhcpcd  ( 5797): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5797): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5864): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5864): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5864): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5864): --- Selecting new region: 2
I/UEI.SmartControl( 5864): -- Running on KitKat(19) and above! JNI will be used.
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5864): Platform has CIR...
D/UEI.SmartControl( 5864): NO CIR support, need to check package...
I/UEI.SmartControl( 5864): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5864): QS Service created
,E/UEI.SmartControl( 5864): QS start get config
,V/AudioFlinger(  276): thread 0xb5651000 type 0 TID 1289 going to sleep
,V/AudioFlinger(  276): thread 0xb56eb000 type 0 TID 1290 going to sleep
V/AudioFlinger(  276): thread 0xb5735000 type 0 TID 1293 going to sleep
D/UEI.SmartControl( 5864): Loading JNI Libs...
,D/UEI.SmartControl( 5864):  configuring local db...
I/ActivityManager(  838): Process com.google.android.talk (pid 5135) has died
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  457): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  838): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  838): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  838): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  838): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  838): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  838): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  838): DHCP Start/Renew wake lock is released.
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): RunningState
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine(  838): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  838): ignoring duplicate network state non-change
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  838): Adding iface wlan0 to network 100
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  838): [PASSPOINT] passpointNotification: hs20AP list is checked
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:11.775 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:11.779 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:11.781 DNS addrs= 192.168.1.1, 0.0.0.0, 
E/WifiStateMachine(  838): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/WifiHS20(  838): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:11.791 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
E/ConnectivityService(  838): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  838): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
,D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  838): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  838): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  838): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  838): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  838): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  838): currentScore = 0, newScore = 20
D/ConnectivityService(  838):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  838): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  838): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1746): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  838): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  838): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/QCNEJ   ( 1835): |CORE| No family connected
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1835): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/CSLegacyTypeTracker(  838): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  838): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/ConnectivityService(  838): validation of new default Network = false
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/ConnectivityService(  838): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  838): enableDataServiceNotify 
D/DSQN    (  838): start dsqn bin
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/Tethering(  838): MasterInitialState.processMessage what=3
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/QCNEJ   ( 1835): |CORE| sendDefaultNwMsg: default = 1
,D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] wait 500ms before dns check
V/NetworkPolicy(  838): [LG_RESTRICTED] checkMobilePolicy_type()
,D/ConnectivityService(  838): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 5912): DSQN samuel.seo ver 141203
E/DSQN    ( 5912): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5912): created command queue thread
I/DSQN    ( 5912): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5912): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
I/PCSuite ( 5719): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5719): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 5685): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5685): MCCMNC not supported: null
I/PCSuite ( 5719): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5719): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/UEI.SmartControl( 5864):  ---- Has DB8: true
,D/UEI.SmartControl( 5864): QS start statue = true Error code = 0
D/UEI.SmartControl( 5864): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5864): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5864): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5864): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5864): IrrcClient ++ 
D/irrcClient( 5864): getIrrcService ++ 
D/irrcClient( 5864): getIrrcService -- 
D/irrcClient( 5864): IrrcClient -- 
W/irrc_jni( 5864): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5864): Services init done
I/UEI.SmartControl( 5864): Device manager: loading config....
D/UEI.SmartControl( 5864): QS Service init finished
D/UEI.SmartControl( 5864): QS Service version name: 0.1.73
D/UEI.SmartControl( 5864): Config is loaded...
D/UEI.SmartControl( 5864): QS Service version code: 1073
D/UEI.SmartControl( 5864): Service requested: Control
D/UEI.SmartControl( 5864): Internal service binding...
,D/UEI.SmartControl( 5864): -----IControl: 11
D/UEI.SmartControl( 5864): Caller: com.lge.qremote
D/UEI.SmartControl( 5864): ------------ IControl registerCallback...
I/UEI.SmartControl( 5864): Registering callback...
D/UEI.SmartControl( 5864): -----IControl: 19
D/UEI.SmartControl( 5864): Caller: com.lge.qremote
I/UEI.SmartControl( 5864): Registering Services Ready callback...
I/UEI.SmartControl( 5864): Notify client services are ready...
D/UEI.SmartControl( 5864): -----IControl: 8
,D/UEI.SmartControl( 5864): Caller: com.lge.qremote
I/AudioManager( 5822): getMode name:com.lge.qremote
I/ActivityManager(  838): Killing 1959:com.google.process.gapps/u0a6 (adj 15): empty #11
D/UEI.SmartControl( 5864):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5864): Notify AllClients services are ready: 0
,W/libprocessgroup(  838): failed to open /acct/uid_10006/pid_1959/cgroup.procs: No such file or directory
,I/AudioManager( 5822): getMode name:com.lge.qremote
I/AudioManager( 5822): getMode name:com.lge.qremote
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] DNSResolver start dns
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5912): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5912): restart monitoring
,I/DSQN    ( 5912): dsqn report finish
D/LGDataListener(  271): argv[0]=dsqncommand
D/LGDataListener(  271): argv[1]=wlan0
D/LGDataListener(  271): argv[2]=1
D/LGDataListener(  271): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  838): DSQM DsqnNotification wlan0  1
D/DSQN    (  838): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:17:11 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449746232494], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449746232472]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Validated
,D/ConnectivityService(  838): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  838): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  838): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
D/ConnectivityService(  838): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1746): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiDataContinuityService(  838): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  838): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:12.859 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  268): 
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/WifiInternetCheck(  838): Single check msg out of sync, ignoring.
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  838): onReceive
D/LocSvc_java(  838): got connectivity action
,D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:1 arg2:1
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5952 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 289us total 30.449ms
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/NetworkChangeNotifierAutoDetect( 1935): Network connectivity changed, type is: 2
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 29.902ms
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
I/System.out(  838): propertyValue:false
D/LocSvc_java(  838): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  838): Sending msg: 5 arg1:0 arg2:1
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 21.245ms
D/AlarmManagerService(  838): Setting time of day to sec=1449746234
W/AlarmManagerService(  838): Unable to set rtc to 1449746234: Invalid argument
,D/LocSvc_java(  838): NTP server returned: 1449746234464 (Thu Dec 10 12:17:14 GMT+01:00 2015) reference: 105617 certainty: 7 system time offset: 6
D/LocSvc_java(  838): Sending msg: 10 arg1:0 arg2:1
,D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/[SystemUI]Clock( 1369): onReceive = android.intent.action.TIME_SET
,D/WeatherService( 2677): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:17:14
D/WeatherService( 2677): 2 : requestRefreshAppWidget, isUpdateStart : false
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
D/WeatherService( 2677): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2677): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2677): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2677): 2 : Fixed theme : optimus
,D/WeatherReflect( 2677): 2 : Map key string is -2
,I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5980 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  838): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 1873): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=10 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 1873): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
,I/ActivityManager(  838): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5986 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/lim     ( 2677): 2 : time = 12:17
I/WeatherReflect( 2677): Model Name : LG-D722
D/WeatherTheme( 2677): 2 : exactly same view!
D/WeatherTheme( 2677): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
,D/WeatherService( 2677): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:17:14
I/[LGHome]LGCalendarIcon( 1873): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
,I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/GpsLocationProvider(  838): No APN found to select.
W/ResourcesManager( 5986): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5986): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5986): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/LgeGpsConstants(  838): Can't find 'ext_gps.conf'!!
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
W/ResourcesManager( 5980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5980): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5980): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  838): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6023 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
I/AppConfig( 5986): Total System Memory = 906309632
I/GalleryUtils( 5986): Application Heap = 96 MB
,I/AppConfig( 5986): App Tier : NOT_DEF
D/SystemHelper( 5986): region [EU], country [EU], operator [OPEN], sub-operator []
D/LgeGpsLocationProvider(  838): NTP server: europe.pool.ntp.org
D/LgeGpsLocationProvider(  838): NTP server returned: 1449746234911 (Thu Dec 10 12:17:14 GMT+01:00 2015) reference: 106064 certainty: 24 system time offset: 5
,I/GservicesProvider( 6023): Gservices pushing to system: true; secure/global: true
,I/ActivityManager(  838): Process com.android.vending (pid 4992) has died
,I/NotificationManager(  838): android: cancelAsUser(-1816247584) by android
,I/LGEmail ( 5980): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/NotificationManager(  838): android: cancelAsUser(-1597574061) by android
,I/MusicStore( 5952): Database version: 120
,D/LGEmail ( 5980): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/GoogleHttpClient( 6023): GMS http client unavailable, use old client
,I/GoogleHttpClient( 6023): GMS http client unavailable, use old client
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5952): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:15.323 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/ActivityThread( 5279): Failed to find provider info for com.android.contacts.metadata
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/art     (  838): Explicit concurrent mark sweep GC freed 75535(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 9.141ms total 280.367ms
I/ActivityManager(  838): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6065 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5952): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/SyncManager(  838): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37700, reason: UserStart, SyncResult: databaseError: true stats []
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5952): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/SyncManager(  838): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 138797, reason: UserStart
,I/NotificationManager(  838): android: cancelAsUser(716319171) by android
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
E/Auth.Api.Credentials( 5279): [CredentialSyncAdapter] Unknown sync event.
,W/ResourcesManager( 5952): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5952): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/WifiInternetCheck(  838): isHttpConnectionAvailable - We got a valid response : 204
I/ActivityManager(  838): Process com.google.android.gms:car (pid 5569) has died
I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
,D/ALBootInit( 6065): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6065): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6065): [setNextAlert] start
D/Alarms  ( 6065): [setNextAlert] (1)
,D/Alarms  ( 6065):  minTime  = 0
D/Alarms  ( 6065):  -- OK multi -- 0
E/jeny.kim( 6065): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6065): [setNextAlert]setNextAlert temp_AlarmLinkText + 
V/JNIHelp ( 5952): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  838): Process com.lge.lgdmsclient (pid 5778) has died
,W/ActivityThread( 5952): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/CommonUtil( 6065): BUILD Operator: OPEN
W/System  ( 5952): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7c4da21: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5952): Installed default security provider GmsCore_OpenSSL
D/Alarms  ( 6065): broadcastToWidgetProvider : false
,D/AndroidMusic( 5952): GMSCore installation verified
D/Alarms  ( 6065): Enter formatDayAndTime(final Context context, long timeInMiliSec)
I/NotificationManager(  838): android: cancelAsUser(-1816247584) by android
,V/SettingsProvider(  838): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6065): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6065): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1c8d3e0a
E/ConnectivityChangeReceiver( 5279): Ignoring connectivity change
,V/DigitalAppWidgetProvider( 6065): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1c8d3e0a
I/ConfigStore( 5952): Config Database version: 1
D/QuickCoverProvider( 6065): onReceiver
,I/ActivityManager(  838): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6091 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/NotificationManager(  838): android: cancelAsUser(-1597574061) by android
,D/ConnectivityService(  838): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): dumpNetworkRequest
,D/ConnectivityService(  838):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  838):     Requests:
D/ConnectivityService(  838):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     Lingered:
D/ConnectivityService(  838): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  838): apparently satisfied.  currentScore=60
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5279): CM callback handler got msg 524290
,W/ResourcesManager( 6091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6091): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6091): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6091): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3a3f6fb9, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3231ffe, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@628335f, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@393f01ac, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@95e4e75, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1c8d3e0a, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@36c6a67b, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@17708c98, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1b525cf1, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@dc930d6, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@70f2f57, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@162dda44, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3e9ed72d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@28ff8462, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@14ed69f3, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@245056b0, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2cbeb929, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@85584ae, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@276ab24f, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2dc2ddc, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@21e0bee5, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@30f93dba, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2ca246b, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1cec4bc8, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@34636461, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1aed7b86, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@22649c47, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@325e5c74, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2810e59d, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2995ca12, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3444b5e3, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@13ecbe0, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@391b3e99, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2102755e, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3282cd3f, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@19f4c60c, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1ad82b55, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@23fc896a, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3660fe5b, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@a2e36f8, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@263d27d1, lg_preferences_recen,t_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@6d1d236,
,D/GeneralPreferenceUtils( 6091): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6091): [init]
,I/Config  ( 6091): LGCalendar ver.4.40.17
I/Config  ( 6091): start check model
I/Config  ( 6091): start check native_ca
I/Config  ( 6091): Config Operator=OPEN, Country=EU
D/Config  ( 6091): [setDefaultValuesToPref]
D/Config  ( 6091): [parseProfiles]
D/ProfilesParser( 6091): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6091): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6091): [updateProfiletoCountryInfo]
D/GeneralPreference( 6091): [checkAndMigrateOldPreference]
I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
,E/AgendaWidgetManager( 6091): [updateWidgets] 
I/InitNotificationRingtoneService( 6091): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6091): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/MediaRouter( 5952): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6118 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/MusicLeanback( 5952): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
W/HolidayIntentService( 6091): onHandleIntent
,D/MonthWidgetProvider( 6091): [onReceive]
D/HolidayDataLoader( 6091): readJsonAsset : holiday.json
D/CalendarWidgetProvider( 6091): [onReceive]
D/CalendarWidgetProvider( 6091): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6091): [onUpdateAndInitCalendarTime]
,D/WeekWidgetProvider( 6091): [onReceive]
D/CalendarWidgetProvider( 6091): [onReceive]
D/CalendarWidgetProvider( 6091): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6091): [onUpdateAndInitCalendarTime]
I/NetworkMonitor( 5952): type=WIFI subType= reason=null isConnected=true
,D/WeatherAncestor( 2677): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:17:16
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
,D/Weather_cast( 2677): 2 : set auto-update time : 12/10 15:17
I/AlertUtils( 6091): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/WeatherAncestor( 2677): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:17:16
,D/WeatherService( 2677): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2677): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2677): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/ActivityManager(  838): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6136 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/HolidayIntentService( 6091): onHandleIntent:holiday data empty
,I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/ActivityManager(  838): Process com.lge.bnr (pid 5845) has died
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6091): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6091): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 6091): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6091): End InitializeAlertRingtoneService.onHandleIntent
,D/TimeService( 6136): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449746236579
D/        ( 6136): TimeServiceNative: User Time to be set is 1449746236579
D/QC-time-services( 6136): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6136): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6136): Lib:time_genoff_operation: pargs->ts_val = 1449746236579
D/QC-time-services( 6136): Lib:time_genoff_operation: Send to server  passed!!
W/ResourcesManager( 6118): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/QC-time-services(  318): Daemon: Connection accepted:time_genoff
D/QC-time-services(  318): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449746236579
D/QC-time-services(  318): Daemon:genoff_opr: Base = 2, val = 1449746236579, operation = 0
D/QC-time-services(  318): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/22/70 15:19:3
D/QC-time-services(  318): Daemon:Value read from RTC seconds = 9645543000
D/QC-time-services(  318): Daemon:new time 1449746236579 
D/QC-time-services(  318): Daemon: delta 1440100693579 genoff 1440100693579 
D/QC-time-services(  318): Daemon:genoff_persistent_update: Writing genoff = 1440100693579 to memory
D/QC-time-services(  318): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  318): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  318): Updating the TOD offset
D/QC-time-services(  318): Daemon:genoff_persistent_update: Writing genoff = 1440100693579 to memory
D/QC-time-services(  318): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  318): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  318): Daemon:Update to modem bit set
D/QC-time-services(  318): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  318): Daemon: Base = 2, Value being sent to MODEM = 1124135893579
E/QC-time-services( 6136): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  318): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  318): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager(  838): Process com.lge.settings.easy (pid 5751) has died
,I/CheckinService( 5279): Checkin interval check for package: unspecified last checkin: 1449704270962 min interval config: 0 actual interval: 41965742
,I/NetworkMonitor( 5952): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 5952): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5952): Using platform SSLCertificateSocketFactory
D/eas_req ( 5980): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6169 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/NotificationManager( 5952): com.google.android.music: cancel(1061) by com.google.android.music
,I/HubEmail( 5980): JNI_OnLoad()
I/HubEmail( 5980): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5980): registerNatives()
I/HubEmail( 5980): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5980): registerNativeMethods()
I/HubEmail( 5980): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5980): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/NotificationManager(  838): android: cancelAsUser(-1548111331) by android
,W/Settings( 5980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UEI.SmartControl( 5864): Internal timer expired: 1
,D/LGDMClient( 6169): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6169): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6169): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6169): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6169): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6169): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/art     ( 6023): Explicit concurrent mark sweep GC freed 7832(394KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 458us total 116.014ms
D/LGDMClient( 6169): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6169): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6198 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6169): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/ActivityManager(  838): Killing 5685:com.android.settings/1000 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     (  838): Explicit concurrent mark sweep GC freed 21424(1017KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 28.048ms total 243.867ms
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_5685/cgroup.procs: No such file or directory
,E/LGDMClient( 6169): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6169): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6169): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6169): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6169): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  838): Killing 5864:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5822): android.os.DeadObjectException
,W/System.err( 5822): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5822): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5822): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5822): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5822): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5822): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5822): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5822): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5822): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5822): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5822): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5822): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5822): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5822): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5822): android.os.DeadObjectException
W/System.err( 5822): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5822): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5822): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5822): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5822): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5822): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5822): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5822): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5822): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5822): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5822): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5822): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5822): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5822): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/AppUp4:AppBoxCP( 6198): onCreate
,W/AppUp4:DB( 6198):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6198):  setFingerPrint start
I/AppUp4:DB( 6198):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6198):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6198):  SDK version = 0
I/AppUp4:DB( 6198):  beforefinger == newfinger no write in DB
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,E/libprocessgroup(  838): failed to kill 1 processes for processgroup 5864
,W/ActivityManager(  838): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/AppUp4:AppBoxApplication( 6198): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6198): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6198): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6198): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6198): [onReceive] request level :IDLE....
I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6225 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AppUp4:CustModeStarterReceiver( 6198): onReceive
I/AppUp4:CustModeStarterReceiver( 6198): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6198): Context : android.app.ReceiverRestrictedContext@95e4e75
D/AppUp4:CustFacade( 6198): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6198): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6198): begin check event
I/AppUp4:CustModeStarterReceiver( 6198): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6198): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6198): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6198): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6198): handleAsyncCustNotification do not startCustService
I/ActivityManager(  838): Killing 5719:com.lge.sync/1000 (adj 15): empty #11
W/DriveInitializer( 5279): Awaiting to be initialized
W/DriveInitializer( 5279): Background init thread started
D/UEI.SmartControl( 6225): Quickset Services start...
,I/UEI.SmartControl( 6225): Manufacture = LGE
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5279): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/UEI.SmartControl( 6225): File observer start...
E/UEI.SmartControl( 6225): IR Port is disabled: false
D/UEI.SmartControl( 6225): Starting file observer...
D/UEI.SmartControl( 6225): Extracting JNI libs...
D/UEI.SmartControl( 6225): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6225): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6225): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6225): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6225): --- Selecting new region: 2
,I/UEI.SmartControl( 6225): -- Running on KitKat(19) and above! JNI will be used.
W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_5719/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6225): Platform has CIR...
,D/UEI.SmartControl( 6225): NO CIR support, need to check package...
I/UEI.SmartControl( 6225): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6225): QS Service created
E/UEI.SmartControl( 6225): QS start get config
,I/LgeMiscReceiver( 3111): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3111): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3111): networkInfo.isConnected() = true
D/UEI.SmartControl( 6225): Loading JNI Libs...
,D/UEI.SmartControl( 6225):  configuring local db...
D/PhoneState( 3111): setPdpRejectCasuse : false
W/DriveInitializer( 5279): Background init thread ended
,I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6269 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.265ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 20.888ms
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 21.528ms
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  838): Killing 5822:com.lge.qremote/u0a106 (adj 15): empty #11
I/NotificationManager(  838): android: cancelAsUser(353845882) by android
,W/libprocessgroup(  838): failed to open /acct/uid_10106/pid_5822/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6269): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6269): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6269): onReceive CONNECTIVITY_CHANGE networkType=1
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Killing 6065:com.lge.clock/u0a10 (adj 15): empty #11
D/UEI.SmartControl( 6225):  ---- Has DB8: true
D/UEI.SmartControl( 6225): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6225): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6225): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6225): IRRCDataComm has AudioManager!!!!.
D/PhoneMonitor( 6269): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6269): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6269): [parse] Load xml
W/irrc_jni( 6225): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6225): IrrcClient ++ 
D/irrcClient( 6225): getIrrcService ++ 
D/irrcClient( 6225): getIrrcService -- 
D/irrcClient( 6225): IrrcClient -- 
W/irrc_jni( 6225): IRRCPlayer_nativeInit -- 
V/TelephonyAutoProfiling( 6269): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6269): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/UEI.SmartControl( 6225): Services init done
,I/UEI.SmartControl( 6225): Device manager: loading config....
D/UEI.SmartControl( 6225): Config is loaded...
D/PhoneMonitor( 6269): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/NotificationManager(  838): android: cancelAsUser(-1874035846) by android
,D/UEI.SmartControl( 6225):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6225): Notify AllClients services are ready: 0
W/libprocessgroup(  838): failed to open /acct/uid_10010/pid_6065/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6225): QS Service init finished
D/UEI.SmartControl( 6225): QS Service version name: 0.1.73
D/UEI.SmartControl( 6225): QS Service version code: 1073
D/UEI.SmartControl( 6225): Service requested: Control
V/DownloadManager( 3143): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  838): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6296 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{19752c84 type 0 when 1449746238553 com.android.vending} when 1449746238553
,D/UEI.SmartControl( 6225): Service.onUnbind: IControl
D/UEI.SmartControl( 6225): Service.onDestroy
D/UEI.SmartControl( 6225): Shutdown IRRCPlayer... 
W/irrc_jni( 6225): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6225): ~IrrcClient ++ 
D/irrcClient( 6225): ~IrrcClient -- 
W/irrc_jni( 6225): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6225): Blaster closed
D/UEI.SmartControl( 6225): Blaster closed
D/UEI.SmartControl( 6225): Shut down QS...
D/UEI.SmartControl( 6225): Stopped file observer...
I/UEI.SmartControl( 6225): QS lib stop result = true
D/UEI.SmartControl( 6225): QS shutdown complete
D/UEI.SmartControl( 6225): QS Service created
,E/UEI.SmartControl( 6225): QS start get config
,D/UEI.SmartControl( 6225):  configuring local db...
,V/DownloadManager( 3143): DownloadService onCreate
I/CheckinService( 5279): Checkin interval check for package: unspecified last checkin: 1449704270962 min interval config: 0 actual interval: 41967737
,I/DownloadManager( 3143): in removeSpuriousFiles
I/NotificationManager( 3143): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3143): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3143): created cursor android.database.sqlite.SQLiteCursor@a2e36f8 on behalf of 3143
I/ActivityManager(  838): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6316 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/DownloadManager( 3143): in trimDatabase
V/DownloadManager( 3143): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3143): DownloadService onStartCommand
V/DownloadManager( 3143): created cursor android.database.sqlite.SQLiteCursor@21272537 on behalf of 3143
V/DownloadManager( 3143): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5279): Disabling old GoogleServicesFramework version
I/NotificationManager(  838): android: cancelAsUser(2) by android
,V/DownloadManager( 3143): created cursor android.database.sqlite.SQLiteCursor@a8bcaa4 on behalf of 3143
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/NotificationManager(  838): android: cancelAsUser(353845882) by android
,V/DownloadManager( 3143): DownloadService onDestroy
W/art     ( 6118): Attempt to remove local handle scope entry from IRT, ignoring
D/DrmBroadcastReceiver( 6316): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6316): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6316): Service onCreate
D/DrmService( 6316): Received new request = 2
,D/WeatherAncestor( 2677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:17:19
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
I/DrmSntpClient( 6316): Start Sync process
D/DrmSntpClient( 6316): Server : 0
D/WeatherAncestor( 2677): connectivity changed - connection : true
,D/Weather_cast( 2677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:17:19
D/libc-netbsd( 6316): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6316): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6316): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6316): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  271): App 10051 tries DNS query. Accept family:0 protocol:0
D/WeatherService( 2677): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6316): propertyValue:false
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6346 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2677): 2 : Utils getTopActivity com.lge.launcher2 / true
,I/LGDrmClient( 6316): _DRM_ServiceGet() : Bind lgdrm service
,D/UEI.SmartControl( 6225):  ---- Has DB8: true
,V/ILGDrmService(  281): eDRM_SetDRMTime +++
D/WeatherService( 2677): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/NotificationManager(  838): android: cancelAsUser(-1548111331) by android
I/LGDRM   (  281): [DRM] SET TIME : YR=2015, MON=12, DAY=10
I/LGDRM   (  281): [DRM] SET TIME : HR=11, MIN=17, SEC=19
,D/UEI.SmartControl( 6225): QS start statue = true Error code = 0
D/UEI.SmartControl( 6225): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6225): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6225): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6225): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6225): IrrcClient ++ 
D/irrcClient( 6225): getIrrcService ++ 
D/irrcClient( 6225): getIrrcService -- 
D/irrcClient( 6225): IrrcClient -- 
W/irrc_jni( 6225): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6225): Services init done
D/UEI.SmartControl( 6225): QS Service init finished
D/UEI.SmartControl( 6225): QS Service version name: 0.1.73
D/UEI.SmartControl( 6225): QS Service version code: 1073
D/UEI.SmartControl( 6225): Service requested: Control
V/ILGDrmService(  281): eDRM_SetDRMTime ---
I/DrmSntpClient( 6316): Synched
D/DrmService( 6316): Completed !! request = 2
D/DrmService( 6316): Request count = 0
,E/ActivityThread( 6225): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@17708c98 that was originally bound here
E/ActivityThread( 6225): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@17708c98 that was originally bound here
E/ActivityThread( 6225): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6225): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6225): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6225): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6225): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6225): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6225): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6225): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6225): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6225): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6225): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6225): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6225): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6225): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6225): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6225): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6225): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
V/DrmService( 6316): Service onDestroy
D/libc-netbsd( 6118): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6118): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  271): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  271): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/CheckinService( 5279): Checking schedule, now: 1449746239180 next: 1449704300928
I/CheckinService( 5279): active receiver: enabled
I/UEI.SmartControl( 6225): Device manager: loading config....
,D/UEI.SmartControl( 6225): Internal service binding...
,D/UEI.SmartControl( 6225): Config is loaded...
I/CheckinService( 5279): Preparing to send checkin request
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/EventLogService( 5279): Accumulating logs since 1449745195814
D/Finsky  ( 6296): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 6225):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6225): Notify AllClients services are ready: 0
,W/ResourcesManager( 6346): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 5279): Explicit concurrent mark sweep GC freed 12207(1036KB) AllocSpace objects, 29(464KB) LOS objects, 24% free, 12MB/16MB, paused 1.326ms total 142.626ms
,D/Finsky  ( 6296): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6296): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6296): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6296): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 6296): Skipping gmscore version check
,D/Finsky  ( 6296): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6296): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  838): Killing 5986:com.android.gallery3d/u0a23 (adj 15): empty #11
I/CheckinRequestBuilder( 5279): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  838): failed to open /acct/uid_10023/pid_5986/cgroup.procs: No such file or directory
,E/ActivityThread( 5279): Failed to find provider info for com.google.android.wearable.settings
V/DownloadManager( 3143): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3143): created cursor android.database.sqlite.SQLiteCursor@2e0dbc2 on behalf of 6296
,D/Finsky  ( 6296): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6296): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Babel_SMS( 6346): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6346): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6346): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6346): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6346): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6346): MmsConfig.loadFromResources
E/Babel_SMS( 6346): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6346): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/art     ( 6346): CheckpointMarkThreadRoots callback created = 0xaaf22f30
,I/art     ( 6346): CheckpointMarkThreadRoots callback created = 0xaaf22f20
,I/NotificationManager( 6118): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,D/SensorManager( 6346): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6346): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6346): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6346): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6346): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6346): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6346): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6346): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6346): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6346): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6346): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6346): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6346): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6346): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6346): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6346): found sensor: Motion Accel, handle=46
,W/Settings( 6346): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6346): startup - clean
I/NotificationManager(  838): android: cancelAsUser(2145784878) by android
,I/Babel   ( 6346): deleted: false for 0
,D/Finsky  ( 6296): [740] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6296): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  838): Killing 6091:com.android.calendar/u0a13 (adj 15): empty #11
,I/NotificationManager(  838): android: cancelAsUser(2145784878) by android
W/libprocessgroup(  838): failed to open /acct/uid_10013/pid_6091/cgroup.procs: No such file or directory
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,W/art     ( 6346): Suspending all threads took: 21.466ms
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  838): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6410 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 6136:com.qualcomm.timeservice/1000 (adj 15): empty #11
,W/AudioCapabilities( 6346): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6346): Unsupported mime audio/adpcm
W/AudioCapabilities( 6346): Unsupported mime audio/g726
W/AudioCapabilities( 6346): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6346): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6346): Unsupported mime video/mjpg
W/VideoCapabilities( 6346): Unsupported mime video/theora
,W/AudioCapabilities( 6346): Unsupported mime audio/evrc
,W/AudioCapabilities( 6346): Unsupported mime audio/qcelp
W/VideoCapabilities( 6346): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6346): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6346): Unsupported mime audio/qcelp
W/AudioCapabilities( 6346): Unsupported mime audio/evrc
W/VideoCapabilities( 6346): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6346): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6346): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6346): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6346): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  838): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6427 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_6136/cgroup.procs: No such file or directory
,W/VideoCapabilities( 6346): Unrecognized profile 2130706433 for video/avc
,I/art     (  838): Explicit concurrent mark sweep GC freed 26251(1177KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.722ms total 157.220ms
,I/vclib   ( 6346): onServiceConnected
,W/Babel   ( 6346): Attempted to change video mute state without an active call.
I/NotificationManager( 6346): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 6427): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6427): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd( 6346): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6346): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6346): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6346): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  271): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6346): propertyValue:false
,I/Babel   ( 6346): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  838): Killing 5952:com.google.android.music:main/u0a81 (adj 15): empty #11
I/MultiDex( 6427): VM with version 2.1.0 has multidex support
,I/MultiDex( 6427): install
I/MultiDex( 6427): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  838): failed to open /acct/uid_10081/pid_5952/cgroup.procs: No such file or directory
,V/JNIHelp ( 6427): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6427): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6427): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e4f20e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6427): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6427): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6427): com.google.android.gms: cancel(39789) by com.google.android.gms
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6410): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6410): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6410):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6410):   adb logcat -s GAv4
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6410): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/art     ( 6427): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6427): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6410): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6410): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6410): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 5540): Test app app.js loaded
I/jxcore-log( 5540): 
,W/GAv4    ( 6410): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6410): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  838): Process com.lge.email (pid 5980) has died
,I/chromium( 5540): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NativeLibraryUtils( 6427): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): CdmEngine::OpenSession
I/WVCdm   (  276): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  276): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  276): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  276): L1 library not specified. Falling Back to L3
,I/GoogleURLConnFactory( 6427): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 6427): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6427): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6427): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6427): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6427): propertyValue:false
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=3120498500
I/WebViewFactory( 6410): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6410): Time to load native libraries: 2 ms (timestamps 3191-3193)
I/LibraryLoader( 6410): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6410): Binding Chromium to main looper Looper (main, tid 1) {1877fabe}
I/LibraryLoader( 6410): Expected native library version number "",actual native library version number ""
I/chromium( 6410): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6410): Initializing chromium process, singleProcess=true
,W/art     ( 6410): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6410): ApplicationContext is null in ApplicationStatus
D/libc-netbsd( 6427): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6427): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6427): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6427): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/chromium( 6410): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6410): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6410): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6410): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6410): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6410): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6410): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6410): Remote Branch: 
I/Adreno-EGL( 6410): Local Patches: 
I/Adreno-EGL( 6410): Reconstruct Branch: 
V/AudioPolicyService(  276): registerClient() client 0xb3db5d20, uid 10079
,W/AudioManagerAndroid( 6410): Requires BLUETOOTH permission
I/NSApplication( 6410): Starting up...
,I/ActivityManager(  838): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6506 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6427): CheckpointMarkThreadRoots callback created = 0xb042dcc0
I/art     ( 6427): CheckpointMarkThreadRoots callback created = 0xb042dcb0
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  838): Process com.uei.lg.quicksetsdk.lite (pid 6225) has died
,I/iu.SyncManager( 5279): SYNC; picasa accounts
,D/NetworkLogImpl( 5279): Loaded NetworkSpeedPredictor
I/iu.Environment( 5279): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5279): num queued entries: 0
I/iu.UploadsManager( 5279): num updated entries: 0
I/iu.SyncManager( 5279): NEXT; no task
I/art     ( 6023): Explicit concurrent mark sweep GC freed 2926(120KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 471us total 35.509ms
,I/dex2oat ( 6536): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6548 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
I/dex2oat ( 6536): dex2oat took 125.425ms (threads: 4)
,I/Adreno-EGL( 6427): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6427): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6427): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6427): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6427): Remote Branch: 
I/Adreno-EGL( 6427): Local Patches: 
I/Adreno-EGL( 6427): Reconstruct Branch: 
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Process com.lge.appbox.client (pid 6198) has died
,W/ResourcesManager( 6548): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCM     ( 1728): GCM config loaded
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec0c010:true
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,I/ActivityManager(  838): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6575 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/Adreno-EGL( 6427): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6427): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6427): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6427): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6427): Remote Branch: 
I/Adreno-EGL( 6427): Local Patches: 
I/Adreno-EGL( 6427): Reconstruct Branch: 
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 114737223501; DSPS: 3851144; Offset : -2793871053
,I/DigitalAppWidgetProvider( 6575): onReceive: android.intent.action.ALARM_CHANGED
I/Adreno-EGL( 6427): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6427): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6427): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6427): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6427): Remote Branch: 
I/Adreno-EGL( 6427): Local Patches: 
I/Adreno-EGL( 6427): Reconstruct Branch: 
,D/WeatherAncestor( 2677): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:17:23
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
,D/Weather_cast( 2677): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2677): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:17:23
D/WeatherService( 2677): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2677): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2677): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/LocationInitializer( 5279): Restart initialization of location
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/WearableService( 1728): callingUid 10006, callindPid: 1728
W/ContextImpl( 3427): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
I/WVCdm   (  276): CdmEngine::OpenSession
E/MDM     ( 1728): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
I/ActivityManager(  838): Process com.google.android.setupwizard (pid 6269) has died
,I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6608 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6548): Create singleton instance
,I/AudioManager( 6548): getMode name:com.lge.qremote
I/WVCdm   (  276): CdmEngine::CloseSession
,D/UEI.SmartControl( 6608): Quickset Services start...
,I/UEI.SmartControl( 6608): Manufacture = LGE
D/UEI.SmartControl( 6608): File observer start...
E/UEI.SmartControl( 6608): IR Port is disabled: false
D/UEI.SmartControl( 6608): Starting file observer...
D/UEI.SmartControl( 6608): Extracting JNI libs...
D/UEI.SmartControl( 6608): --- this system supports 32-bit or 64-bit only
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=1566906356
D/UEI.SmartControl( 6608): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6608): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6608): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6608): --- Selecting new region: 2
I/UEI.SmartControl( 6608): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6608): Platform has CIR...
D/UEI.SmartControl( 6608): NO CIR support, need to check package...
I/UEI.SmartControl( 6608): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6608): QS Service created
E/UEI.SmartControl( 6608): QS start get config
,D/UEI.SmartControl( 6608): Loading JNI Libs...
,D/UEI.SmartControl( 6608):  configuring local db...
D/UEI.SmartControl( 6608):  ---- Has DB8: true
,D/UEI.SmartControl( 6608): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6608): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6608): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6608): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6608): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6608): IrrcClient ++ 
D/irrcClient( 6608): getIrrcService ++ 
D/irrcClient( 6608): getIrrcService -- 
D/irrcClient( 6608): IrrcClient -- 
W/irrc_jni( 6608): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6608): Services init done
I/UEI.SmartControl( 6608): Device manager: loading config....
D/UEI.SmartControl( 6608): QS Service init finished
D/UEI.SmartControl( 6608): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6608): QS Service version code: 1073
D/UEI.SmartControl( 6608): Service requested: Control
D/UEI.SmartControl( 6608): Config is loaded...
D/UEI.SmartControl( 6608):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6608): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6608): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6608): Internal service binding...
D/UEI.SmartControl( 6608): -----IControl: 11
D/UEI.SmartControl( 6608): Caller: com.lge.qremote
D/UEI.SmartControl( 6608): ------------ IControl registerCallback...
I/UEI.SmartControl( 6608): Registering callback...
D/UEI.SmartControl( 6608): -----IControl: 19
D/UEI.SmartControl( 6608): Caller: com.lge.qremote
,I/UEI.SmartControl( 6608): Registering Services Ready callback...
I/UEI.SmartControl( 6608): Notify client services are ready...
D/UEI.SmartControl( 6608): -----IControl: 8
D/UEI.SmartControl( 6608): Caller: com.lge.qremote
I/AudioManager( 6548): getMode name:com.lge.qremote
I/ActivityManager(  838): Killing 6169:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/MusicWidget( 2617): mDelayedStopHandler : unbind
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_6169/cgroup.procs: No such file or directory
,I/AudioManager( 6548): getMode name:com.lge.qremote
I/AudioManager( 6548): getMode name:com.lge.qremote
,I/MusicBrowser( 2687): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
,I/MusicBrowser( 2687): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2687): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2687): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2687): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2687): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  838):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@30f93dbacom.lge.music.MediaPlaybackService$6@2ca246b
,D/MusicBrowser( 2687): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1b525cf1
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2687): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2687): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2687): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2687): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2687): reset
,V/MediaPlayer[Native]( 2687): setListener
,V/MediaPlayer[Native]( 2687): disconnect
,V/MediaPlayer[Native]( 2687): destructor
,V/AudioFlinger(  276): releasing 19 from 2687 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/MediaPlayer[Native]( 2687): disconnect
D/MusicBrowser( 2687): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2687): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2687): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2687): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2687): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
,V/MusicBrowser( 2687): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2687): [SmartShareManagerClient] unregisterListener: 485247944
W/SmartShareClient( 2687): [SmartShareManagerClient] unregisterListener invalid listener: 485247944
I/SmartShareClient( 2687): [SmartShareManagerClient] terminate service: 2687/MediaPlaybackService/103297887
E/HomeCloudIF( 2687): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2687): [SmartShareManagerClient] unbindService context:android.app.Application@34636461
V/CloudHub( 2687): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2687): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2687): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2687): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2687): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  838): Killing 6316:com.lge.drmservice/u0a51 (adj 15): empty #11
I/CloudHub( 2687): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
W/libprocessgroup(  838): failed to open /acct/uid_10051/pid_6316/cgroup.procs: No such file or directory
,I/WVCdm   (  276): CdmEngine::CloseSession
,I/WVCdm   (  276): L3 Terminate.
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/CheckinRequestBuilder( 5279): Classify the device as Phone.
,D/libc-netbsd( 5279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5279): propertyValue:false
D/libc-netbsd( 5279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 5279): Sending checkin request (10144 bytes)
,I/art     ( 6118): CheckpointMarkThreadRoots callback created = 0xb042d400
,I/art     ( 6118): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinResponseProcessor( 5279): From server: 4 gservices updates and 3 deletes
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:27.383 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/CertBlacklister(  838): Certificate blacklist changed, updating...
,I/CertBlacklister(  838): Certificate blacklist updated
,I/GservicesProvider( 6023): main difference update completed
I/CheckinRequestBuilder( 5279): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  838): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6646 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,E/ActivityThread( 5279): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  838): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6676 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 22.596ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.911ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 31.219ms
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  838): Explicit concurrent mark sweep GC freed 18992(876KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.853ms total 146.349ms
,I/ActivityManager(  838): Killing 6296:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10036/pid_6296/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 6676): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6676): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6676): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6676): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  838): Killing 6410:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/CheckinRequestBuilder( 5279): Classify the device as Phone.
,W/libprocessgroup(  838): failed to open /acct/uid_10079/pid_6410/cgroup.procs: No such file or directory
,I/CheckinTask( 5279): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5279): Checkin interval check for package: unspecified last checkin: 1449704270962 min interval config: 0 actual interval: 41977385
I/CheckinService( 5279): Checking schedule, now: 1449746248351 next: 1450273497338
I/CheckinService( 5279): active receiver: disabled
,I/GservicesUpdateTask( 1935): Updating Gservices keys
,I/SystemUpdateService( 5279): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/CheckinService( 5279): Checking schedule, now: 1449746248417 next: 1450273497338
I/CheckinService( 5279): active receiver: disabled
D/CheckinService( 5279): Recording last checkin time for package unspecified as 1449746248433
,D/SystemUpdateService( 5279): onCreate
D/SystemUpdateService( 5279): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5279): cancelUpdate (empty URL)
I/SystemUpdateService( 5279): active receiver: disabled
,I/NotificationManager( 5279): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 5279): com.google.android.gms: cancel(2130838166) by com.google.android.gms
W/InstanceID/Rpc( 5279): Found 10006
,I/art     ( 6023): Explicit concurrent mark sweep GC freed 8532(432KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 746us total 33.932ms
,I/art     ( 5279): Explicit concurrent mark sweep GC freed 18194(1323KB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 12MB/20MB, paused 1.315ms total 69.914ms
,I/art     ( 6023): Explicit concurrent mark sweep GC freed 2800(106KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 925us total 30.550ms
,D/SystemUpdateService( 5279): onDestroy
,E/DynamiteModule( 5279): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5279): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5279): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5279): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5279): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5279): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5279): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5279): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5279): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5279): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5279): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5279): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5279): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5279): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5279): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5279): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5279): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5279): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5279): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5279): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5279): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5279): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5279): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5279): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5279): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5279): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5279): 		... 17 more
E/DynamiteModule( 5279): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 5279): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5279): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 5279): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5279): Updating ocr activity enabled=false
W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 5279): Updating downloaded model state (gservices changed)
,I/ActivityManager(  838): Killing 6506:com.android.chrome/u0a48 (adj 15): empty #11
,I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 37081(2MB) AllocSpace objects, 48(768KB) LOS objects, 40% free, 13MB/22MB, paused 1.306ms total 115.542ms
,W/libprocessgroup(  838): failed to open /acct/uid_10048/pid_6506/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/art     ( 6023): Explicit concurrent mark sweep GC freed 2705(107KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 981us total 33.041ms
,I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,D/UEI.SmartControl( 6608): Internal timer expired: 1
,D/GCM     ( 1728): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  838): Killing 6118:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/administrator(  838): Handling package changes for user 0
,W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_6118/cgroup.procs: No such file or directory
,W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
I/NotificationService(  838): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  838): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  838): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourceType(  838): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,V/BackupManagerService(  838): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  838): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@35cc40fd
I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreUlr( 1728): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1728): DispatchingService.onCreate()
,I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6752 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/GCoreNlp( 1728): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/GCoreUlr( 1728): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
D/LocationProviderProxy(  838): applying state to connected service
,W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
,D/PhoneMonitor( 6752): Register our PhoneStateListener
,V/SetupWizard( 6752): Connected to Gservices successfully
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 15649(878KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 13MB/23MB, paused 4.494ms total 105.545ms
,D/PhoneMonitor( 6752): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6752): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6752): [parse] Load xml
V/TelephonyAutoProfiling( 6752): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6752): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
E/ctxmgr  ( 1728): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/PhoneMonitor( 6752): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     ( 6023): Explicit concurrent mark sweep GC freed 2677(106KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 861us total 25.069ms
,D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  838): Killing 6575:com.lge.clock/u0a10 (adj 15): empty #11
,I/GCoreUlr( 1728): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/QCNEJ   ( 1835): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:17:30.422 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/libprocessgroup(  838): failed to open /acct/uid_10010/pid_6575/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
,I/GCoreUlr( 1728): DispatchingService.onDestroy()
I/GCoreUlr( 1728): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1728): Unbound from all location providers
I/GCoreUlr( 1728): Place inference reporting - stopped
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6778 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ctxmgr  ( 1728): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1728): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,W/ResourcesManager( 6346): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6346): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 6346): com.google.android.talk: cancel(8) by com.google.android.talk
I/AppUp4:AppBoxCP( 6778): onCreate
W/AppUp4:DB( 6778):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6778):  setFingerPrint start
,I/AppUp4:DB( 6778):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6778):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6778):  SDK version = 0
I/AppUp4:DB( 6778):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6778): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6778): onReceive
I/AppUp4:CustModeStarterReceiver( 6778): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,V/JNIHelp ( 6346): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AppUp4:CustFacade( 6778): Context : android.app.ReceiverRestrictedContext@3231ffe
D/AppUp4:CustFacade( 6778): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6778): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6778): begin check event
I/AppUp4:CustModeStarterReceiver( 6778): Event For Nothing, skip.
,W/System  ( 6346): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6346): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  838): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6799 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6799): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6799): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6799): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 6799): Total System Memory = 906309632
,I/GalleryUtils( 6799): Application Heap = 96 MB
I/AppConfig( 6799): App Tier : NOT_DEF
D/SystemHelper( 6799): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  838): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6818 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  838): Killing 2687:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  276): 2687 died, releasing its sessions
V/AudioFlinger(  276):  pid 1746 @ 0
V/AudioFlinger(  276):  pid 3111 @ 1
,V/AudioFlinger(  276):  pid 3111 @ 2
W/libprocessgroup(  838): failed to open /acct/uid_10028/pid_2687/cgroup.procs: No such file or directory
,W/ResourcesManager( 6818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6818): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6818): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6818): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6818): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/SystemConfig( 6818): BUILD Country: EU
I/SystemConfig( 6818): BUILD Operator: OPEN
I/ActivityManager(  838): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6840 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 6646:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10009/pid_6646/cgroup.procs: No such file or directory
,I/SystemConfig( 6818): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6818): existFile = false
I/SystemConfig( 6818): canReadFile = false
I/SystemConfig( 6818): systemFeature RCS result false
D/SystemConfig( 6818): refreshRcsSupport() :false
I/LockScreenSettings( 6840): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6840): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6840): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6840): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6840): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6840): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6857 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 6676:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10003/pid_6676/cgroup.procs: No such file or directory
,W/ResourcesManager( 6857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 3143): Explicit concurrent mark sweep GC freed 5502(376KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 426us total 41.680ms
,I/art     (  838): Explicit concurrent mark sweep GC freed 31107(1645KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.302ms total 153.779ms
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  838): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6882 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 6752:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 106 ms] updated apps [took 106 ms] 
,W/libprocessgroup(  838): failed to open /acct/uid_10038/pid_6752/cgroup.procs: No such file or directory
,D/Finsky  ( 6882): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/Finsky  ( 6882): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6882): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6882): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6882): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 6882): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6882): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6882): Skipping gmscore version check
V/DownloadManager( 3143): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3143): created cursor android.database.sqlite.SQLiteCursor@36beddd3 on behalf of 6882
,I/ActivityManager(  838): Killing 6427:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10006/pid_6427/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5279): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5279): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6882): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6882): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5279): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 5279): Explicit concurrent mark sweep GC freed 19894(1297KB) AllocSpace objects, 16(256KB) LOS objects, 25% free, 12MB/16MB, paused 1.364ms total 83.508ms
,W/SQLiteConnectionPool( 5279): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 5279): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5279): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5279): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  838): Killing 6608:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6548): android.os.DeadObjectException
,W/System.err( 6548): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6548): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6548): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6548): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6548): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6548): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6548): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6548): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6548): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6548): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6548): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6548): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6548): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6548): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6548): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6548): android.os.DeadObjectException
W/System.err( 6548): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6548): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6548): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6548): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6548): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6548): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6548): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6548): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6548): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6548): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6548): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6548): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6548): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
,W/System.err( 6548): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6548): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  838): failed to open /acct/uid_10089/pid_6608/cgroup.procs: No such file or directory
W/ActivityManager(  838): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6958 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  457): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
,D/UEI.SmartControl( 6958): Quickset Services start...
,I/UEI.SmartControl( 6958): Manufacture = LGE
D/UEI.SmartControl( 6958): File observer start...
E/UEI.SmartControl( 6958): IR Port is disabled: false
D/UEI.SmartControl( 6958): Starting file observer...
D/UEI.SmartControl( 6958): Extracting JNI libs...
D/UEI.SmartControl( 6958): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6958): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6958): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6958): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6958): --- Selecting new region: 2
,I/UEI.SmartControl( 6958): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6958): Platform has CIR...
D/UEI.SmartControl( 6958): NO CIR support, need to check package...
I/UEI.SmartControl( 6958): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6958): QS Service created
E/UEI.SmartControl( 6958): QS start get config
,D/UEI.SmartControl( 6958): Loading JNI Libs...
,D/UEI.SmartControl( 6958):  configuring local db...
D/UEI.SmartControl( 6958):  ---- Has DB8: true
,D/UEI.SmartControl( 6958): QS start statue = true Error code = 0
D/UEI.SmartControl( 6958): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6958): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6958): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6958): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6958): IrrcClient ++ 
D/irrcClient( 6958): getIrrcService ++ 
D/irrcClient( 6958): getIrrcService -- 
D/irrcClient( 6958): IrrcClient -- 
,W/irrc_jni( 6958): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6958): Services init done
I/UEI.SmartControl( 6958): Device manager: loading config....
D/UEI.SmartControl( 6958): QS Service init finished
D/UEI.SmartControl( 6958): QS Service version name: 0.1.73
D/UEI.SmartControl( 6958): QS Service version code: 1073
D/UEI.SmartControl( 6958): Service requested: Control
,D/UEI.SmartControl( 6958): Config is loaded...
D/UEI.SmartControl( 6958): Request IControl service: devices are loaded...
,I/ActivityManager(  838): Killing 6548:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6958):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6958): Notify AllClients services are ready: 0
,W/libprocessgroup(  838): failed to open /acct/uid_10106/pid_6548/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6958): Internal service binding...
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/PackageSettings(  838): Skipping PackageSetting{20658119 com.example.hello/10030} due to missing metadata
,I/CheckinService( 5279): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6958): Internal timer expired: 1
,D/UEI.SmartControl( 6958): Service.onUnbind: IControl
D/UEI.SmartControl( 6958): Service.onDestroy
W/System.err( 6958): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@17708c98
W/System.err( 6958): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6958): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6958): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6958): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6958): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6958): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6958): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6958): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6958): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6958): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6958): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6958): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6958): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@17708c98
D/UEI.SmartControl( 6958): Shutdown IRRCPlayer... 
,W/irrc_jni( 6958): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6958): ~IrrcClient ++ 
D/irrcClient( 6958): ~IrrcClient -- 
W/irrc_jni( 6958): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6958): Blaster closed
D/UEI.SmartControl( 6958): Blaster closed
D/UEI.SmartControl( 6958): Shut down QS...
D/UEI.SmartControl( 6958): Stopped file observer...
I/UEI.SmartControl( 6958): QS lib stop result = true
D/UEI.SmartControl( 6958): QS shutdown complete
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 134738029586; DSPS: 4506531; Offset : -2793888630
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{f58315f type 2 when 135780 android} when 135780
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  838): ALS enabled for SRE
,D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29632 ms ago)
D/qdlights(  838): set_light_backlight: 253
,D/qdlights(  838): set_light_backlight: 250
,D/qdlights(  838): set_light_backlight: 247
,D/qdlights(  838): set_light_backlight: 243
,D/qdlights(  838): set_light_backlight: 240
,D/qdlights(  838): set_light_backlight: 237
,D/qdlights(  838): set_light_backlight: 233
,D/qdlights(  838): set_light_backlight: 230
,D/qdlights(  838): set_light_backlight: 227
,D/qdlights(  838): set_light_backlight: 223
,D/qdlights(  838): set_light_backlight: 220
,D/qdlights(  838): set_light_backlight: 217
,D/qdlights(  838): set_light_backlight: 213
,D/qdlights(  838): set_light_backlight: 210
,D/qdlights(  838): set_light_backlight: 207
,D/qdlights(  838): set_light_backlight: 203
,D/qdlights(  838): set_light_backlight: 200
,D/qdlights(  838): set_light_backlight: 197
,D/qdlights(  838): set_light_backlight: 193
,D/qdlights(  838): set_light_backlight: 190
,D/qdlights(  838): set_light_backlight: 187
,D/qdlights(  838): set_light_backlight: 183
,D/qdlights(  838): set_light_backlight: 180
,D/qdlights(  838): set_light_backlight: 177
,D/qdlights(  838): set_light_backlight: 173
,D/qdlights(  838): set_light_backlight: 170
,D/qdlights(  838): set_light_backlight: 167
,D/qdlights(  838): set_light_backlight: 163
,D/qdlights(  838): set_light_backlight: 160
,D/qdlights(  838): set_light_backlight: 157
,D/qdlights(  838): set_light_backlight: 153
,D/qdlights(  838): set_light_backlight: 150
,D/qdlights(  838): set_light_backlight: 147
,D/qdlights(  838): set_light_backlight: 143
,D/qdlights(  838): set_light_backlight: 140
,D/qdlights(  838): set_light_backlight: 137
,D/qdlights(  838): set_light_backlight: 133
,D/qdlights(  838): set_light_backlight: 130
,D/qdlights(  838): set_light_backlight: 127
,D/qdlights(  838): set_light_backlight: 123
,D/qdlights(  838): set_light_backlight: 120
,D/qdlights(  838): set_light_backlight: 117
,D/qdlights(  838): set_light_backlight: 113
,D/qdlights(  838): set_light_backlight: 110
,D/qdlights(  838): set_light_backlight: 107
,D/qdlights(  838): set_light_backlight: 103
,D/qdlights(  838): set_light_backlight: 100
,D/qdlights(  838): set_light_backlight: 97
,D/qdlights(  838): set_light_backlight: 93
,D/qdlights(  838): set_light_backlight: 90
,D/qdlights(  838): set_light_backlight: 87
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  838): set_light_backlight: 83
,D/qdlights(  838): set_light_backlight: 80
,D/qdlights(  838): set_light_backlight: 77
,D/qdlights(  838): set_light_backlight: 73
,D/qdlights(  838): set_light_backlight: 70
,D/qdlights(  838): set_light_backlight: 67
,D/qdlights(  838): set_light_backlight: 63
,D/qdlights(  838): set_light_backlight: 60
,D/qdlights(  838): set_light_backlight: 57
,D/qdlights(  838): set_light_backlight: 53
,D/qdlights(  838): set_light_backlight: 50
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,D/qdlights(  838): set_light_backlight: 47
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,D/qdlights(  838): set_light_backlight: 43
D/qdlights(  838): set_light_backlight: 40
,D/qdlights(  838): set_light_backlight: 37
,D/qdlights(  838): set_light_backlight: 33
,D/qdlights(  838): set_light_backlight: 30
,D/qdlights(  838): set_light_backlight: 27
,D/qdlights(  838): set_light_backlight: 23
,D/qdlights(  838): set_light_backlight: 20
,D/qdlights(  838): set_light_backlight: 17
,D/qdlights(  838): set_light_backlight: 13
,D/qdlights(  838): set_light_backlight: 10
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,D/WeatherService( 2677): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:18:0
D/WeatherService( 2677): 2 : TimeTick Intent And Screen On
D/WeatherService( 2677): 2 : SDK version : 21
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2677): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2677): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2677): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
D/WeatherService( 2677): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2677): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2677): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2677): 2 : Fixed theme : optimus
,D/WeatherReflect( 2677): 2 : Map key string is -2
D/lim     ( 2677): 2 : time = 12:18
,I/WeatherReflect( 2677): Model Name : LG-D722
D/WeatherTheme( 2677): 2 : Different view - status_min_formatted : 17 != 18
D/WeatherTheme( 2677): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2677): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2677): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/Weather4x2_optimus( 2677): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2677): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2677): forecast size is 0
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2677): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2677): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2677): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2677): url is : null
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2677): 2 : update view, appWidgetId: 2
D/WeatherService( 2677): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:18:0
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{361227ac type 2 when 151661 com.google.android.gms} when 151661
,I/ActivityManager(  838): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7020 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
W/ResourcesManager( 7020): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7020): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7020): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/System  ( 7020): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7020): Installed default security provider GmsCore_OpenSSL
I/NotificationManager(  838): android: cancelAsUser(2) by android
,W/ResourcesManager( 7020): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7020): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 7020): CheckpointMarkThreadRoots callback created = 0xb042d9f0
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     ( 7020): CheckpointMarkThreadRoots callback created = 0xb4958de0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/YouTube MDX( 7020): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dex2oat ( 7066): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-1443255018.jar --oat-fd=97 --oat-location=/data/data/com.google.android.gms/cache/ads-1443255018.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7065): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1443255018.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads-1443255018.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7020): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 7066): dex2oat took 103.870ms (threads: 4)
,I/dex2oat ( 7065): dex2oat took 108.487ms (threads: 4)
,I/NotificationManager( 7020): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7020): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7020): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7020): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 7020): Found 10006
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7020): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/NotificationManager( 7020): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  271): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 7020): propertyValue:false
D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  271): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 7020): propertyValue:false
D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7020): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7020): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  838): Process com.google.android.talk (pid 6346) has died
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/libc-netbsd( 5279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5279): propertyValue:false
D/libc-netbsd( 5279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 154738648797; DSPS: 5161911; Offset : -2793880889
,I/VacuumService( 1728): Vacuum at: now=1449746283750 tag=VacuumService
,I/PowerManagerService(  838): ALS enabled for SRE
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36496 ms ago)
,I/PowerManagerService(  838): Going to sleep due to screen timeout (uid 1000)...
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  838): ALS enabled for SRE
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36532 ms ago)
W/ContextImpl(  838): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  838): Sleeping (uid 1000)...
D/LPWGController(  838): [updateScreenState] screen on = false
D/LPWGController(  838): disable proximity sensor
,D/LPWGController(  838): enable proximity sensor
I/SensorManager(  838): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@34438f72] by com.android.server.power.ProximitySensorListener.enable():120
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
D/sensors_hal_Thresh(  838): enable: Received response: 0
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36604 ms ago)
I/Adreno-EGL(  838): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  838): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  838): Build Date: 03/02/15 Mon
I/Adreno-EGL(  838): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  838): Remote Branch: 
I/Adreno-EGL(  838): Local Patches: 
I/Adreno-EGL(  838): Reconstruct Branch: 
,D/PermissionCache(  243): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (166 us)
,I/Sensors (  416): sns_pwr.c(273):acquiring wakelock
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
,I/ActivityManager(  838): Process com.android.contacts (pid 6818) has died
,D/qdlights(  838): set_light_backlight: 0
,I/SensorManager(  838): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  838): activate: handle is 46, disable
V/sensors_hal_Ctx(  838): activate sensors is 1000000000000
D/sensors_hal_LP2(  838): enable: handle=46
D/sensors_hal_LP2(  838): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  838): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  243): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  243): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  838): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  838): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  838): Display changed displayId=0
,D/DSDPConnection( 1746): Display #0 changed.
,D/qdhwcomposer(  243): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  838): Excessive delay in setPowerMode(): 201ms
,I/qdhwcomposer(  243): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  838): Got set_interactive hint
D/KeyguardViewMediator( 1369): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1369): notifyScreenOffLocked
,D/WifiServerServiceExt(  838): sendKtScanInterval  mRtspPlay : false
,D/KeyguardViewMediator( 1369): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1369): handleNotifyScreenOff
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 838
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  276): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  838): set CMD_KT_SCAN_INTERVAL
,D/ScreenTurnOffBySensor( 1369): unregisterProximitySensor
,D/StatusBarWindowView( 1369): onScreenTurnedOff why = 3
,D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/GpsLocationProvider(  838): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1835): |CORE| sendScreenState: state:true
I/LEDService( 1799): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1799): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1799): stopPatternFlashing()
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/LEDService( 1799): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/LEDService( 1799): updateLightsLocked : turn off led
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1799): lockStatus = 0
,D/LNfcService( 1782): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1799): RESTART MSG
D/NfcServiceNXP( 1782): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1782): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1782): isRequireNfcCRouting() return true
D/LNfcService( 1782): isHCERoutingtoHost() return : true
D/NfcService( 1782): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): newParams.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): screenState= 3
D/NfcService( 1782): Discovery configuration equal, not updating.
,D/SplitWindow(  838): check instance of lgWin Window{2ca4b79 u0 SearchPanel}
,D/Ulp_jni (  838): JNI:system_update. Event-0
,D/InputDispatcher(  838): Window went away: Window{126f4fd1 u0 SearchPanel}
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2677): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:18:6
D/WeatherService( 2677): 2 : ACTION screen on
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2677): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2677): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:18:6
D/AppCleanupService( 3892): android.intent.action.SCREEN_ON
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): ACTION_SCREEN_ON
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 838
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
D/WifiController(  838): CMD_SCREEN_OFF 
D/WifiController(  838): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  838): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1835): |CORE| sendScreenState: state:false
,I/LEDService( 1799): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1799): stopPatternFlashing()
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1799): clear
I/LEDService( 1799): getCurrentHighestLGLedRecord : size = 1
I/Cliptray Service( 1799): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1782): action : android.intent.action.SCREEN_OFF
I/LEDService( 1799): updateLightsLocked : turn on led
E/LEDService( 1799): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1799): Can't handle this request of patternId:0
D/LEDHandler( 1799): RESTART MSG
D/NfcServiceNXP( 1782): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1873): [Launcher.java:1711:onReceive()]Screen Off
,E/NxpNfcJni( 1782): getReconnectState = 0x0
D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
D/LNfcService( 1782): isRequireNfcCRouting() return true
D/LNfcService( 1782): isHCERoutingtoHost() return : true
D/NfcService( 1782): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): newParams.techmask= mTechMask: 0
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): screenState= 1
V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2677): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:18:6
D/WeatherService( 2677): 2 : ACTION screen off
D/WeatherService( 2677): 2 : TimeTick Receiver Unregister
D/WeatherService( 2677): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:18:6
D/AppCleanupService( 3892): android.intent.action.SCREEN_OFF
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): ACTION_SCREEN_OFF
D/AppCleanupService( 3892): AppUsageStatsSaveTask
E/NxpNfcJni( 1782): getReconnectState = 0x0
,I/ActivityManager(  838): Process com.android.gallery3d (pid 6799) has died
,I/Sensors (  416): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{2bb730be type 2 when 162468 com.android.systemui} when 162468
,D/KeyguardViewMediator( 1369): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1746): getCallState : 0
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1369): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1369): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1ecdd51f type 2 when 165789 android} when 165789
,E/ActivityThread( 5279): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  838): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 138797, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  838): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 230109, reason: UserStart
I/NotificationManager(  838): android: cancelAsUser(716319171) by android
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 174739353998; DSPS: 5817294; Offset : -2793878505
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/ClearcutLoggerApiImpl( 1728): disconnect managed GoogleApiClient
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{6261758 type 2 when 187955 com.google.android.gms} when 187955
,I/PhenotypeConfigurator( 1728): Scheduling Phenotype for one-off execution 10330 seconds from now (1449746317158)
,D/GetConfigurationSnapshotOperation( 1728): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1728): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1728): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/art     (  838): Explicit concurrent mark sweep GC freed 64161(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 2.340ms total 171.896ms
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 1728): propertyValue:false
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{2e9804e9 type 2 when 188822 android} when 188822
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 48378(2MB) AllocSpace objects, 7(135KB) LOS objects, 40% free, 14MB/23MB, paused 1.961ms total 124.174ms
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 194740087533; DSPS: 6472679; Offset : -2793906060
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1f226821 type 2 when 195812 android} when 195812
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 214741098514; DSPS: 7128072; Offset : -2793902393
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 234741823403; DSPS: 7783455; Offset : -2793879877
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 254742583395; DSPS: 8438840; Offset : -2793882382
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 274743444794; DSPS: 9094228; Offset : -2793875241
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 294744291244; DSPS: 9749616; Offset : -2793883778
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 314744957174; DSPS: 10404998; Offset : -2793888870
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 334745613729; DSPS: 11060380; Offset : -2793903910
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  838): remove f9f8afb
D/LocationManagerService(  838): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  838): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  838): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 354746354763; DSPS: 11715764; Offset : -2793895351
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 374747120640; DSPS: 12371149; Offset : -2793892230
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 394747796779; DSPS: 13026531; Offset : -2793887270
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 414748634948; DSPS: 13681919; Offset : -2793904504
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  838): android: cancelAsUser(2) by android
,D/libc-netbsd( 6882): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6882): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6882): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6882): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 6882): propertyValue:false
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 434749308794; DSPS: 14337301; Offset : -2793901447
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5540): Toggling radios to false
I/jxcore-log( 5540): 
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  838): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@375984cc mBinding = false
,D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
D/BluetoothManagerService(  838): Message: 2
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothManagerService(  838): Sending off request.
D/WifiServiceImplEx(  838): setWifiEnabled: false pid=5540, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  838): setWifiEnabled: false pid=5540, uid=10316
D/BluetoothAdapterService(393251992)( 1988): disable() called...
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothAdapterState( 1988): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1988): Setting state to 13
I/BluetoothAdapterState( 1988): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(393251992)( 1988): updateAdapterState() - Broadcasting state to 1 receivers.
,E/WifiStateMachine(  838): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log( 5540): Radios toggled
I/jxcore-log( 5540): 
,D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
D/BluetoothAdapterProperties( 1988): onBluetoothDisable()
,D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,I/BluetoothAdapterState( 1988): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1988): Scan Mode:20
,D/BluetoothAdapterState( 1988): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1988): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 1988): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 1988): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 1988): BTA_JvDeleteRecord
I/bt-btif ( 1988): BTA_JvRfcommStopServer
I/bt-btif ( 1988): BTA_JvDeleteRecord
I/bt-btif ( 1988): BTA_JvRfcommStopServer
,W/bt-btif ( 1988): invalid rfc slot id: 1
D/IOP_DB_BT( 1988): db_close: nbr users 0
D/IOP_DB_BT( 1988): db_close: free database
D/btif_config_util( 1988): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService(  838): Message: 60
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 12 -> 13
,W/bt-btif ( 1988): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
E/bt-btif ( 1988): Ignore event 10 in state 1
W/bt-obex ( 1988): Ignore event 10 in state 1
I/bt-btif ( 1988): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1988): ops_state_cb(L223):  ops_state_cb state:3
W/bt-obex ( 1988): Ignore event 10 in state 1
D/OppService( 1988): onOpsStateChange() :3
D/OppService( 1988): Recieved MESSAGE_OPS_DISABLE
E/bt-btif ( 1988): bta_gattc_deregister Deregister Failedm unknown client cif
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 1988): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/LGBluetoothAPIService( 1799): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:G3s-1
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1988): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1988): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
,D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1988): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1988): enum_config(L344): out, value:x
D/btif_config_util( 1988): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 1988): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1988): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 1988): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1988): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 1988): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1988): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 1988): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1988): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 1988): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/btif_config_util( 1988): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1988): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, va,lue:
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
I/BluetoothMapService( 1988): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/BluetoothMapService( 1988): STATE_TURNING_OFF
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
,D/btif_config_util( 1988): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer,
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:$
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/b,tif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:A5-1
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
V/BluetoothMapService( 1988): Handler(): got msg=4
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/BluetoothMapService( 1988): MAP Service closeService in
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/BluetoothMapMasInstance( 1988): MAP Service shutdown
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
,D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
,D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:#
D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
,D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
,D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:XT1072
,D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
,D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:,
D/btif_config_util( 1988): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:a
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:S5-1
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
,D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/LGWifiP2pService(  838): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
V/BluetoothPbapService( 1988): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/[SystemUI]BluetoothHandler( 1369): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
,D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
,D/btif_config_util( 1988): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
,D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer,
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
,D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  838): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 7
V/BluetoothMapMasInstance( 1988): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 1988): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 1988): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 1988): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 1988): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 1988): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130),
V/BluetoothMapMasInstance( 1988): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 1988): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 1988): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1988): MAP Service closeService out,
D/btif_config_util( 1988): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
,D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
,D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:A
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
,D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:	a
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Note3-1
D/btif,_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:,
,D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:A3-1
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Lmp,Ver
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:XT1039
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_con,fig_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:	a
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:"
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Note4-1
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, va,lue:DevClass
V/NativeCrypto( 1728): Read error: ssl=0xb045bc00: I/O error during system call, Connection timed out
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:G3-1
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:	a
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:�
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
,D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:A
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 7
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 1988): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:���
D/btif_config_util( 1988): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:#
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:onem9-1
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 1988): enum_config(L344): out, value:H
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 1988): enum_config(L344): out, value:?C
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:Tab4
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:Z
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 1988): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1988): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:�h�
D/btif_config_util( 1988): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:��h
D/btif_config_util( 1988): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:J���J�hrD�hrD�
D/btif_config_util( 1988): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 1988): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
D/btif_config_util( 1988): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 1988): enum_config(L344): out, value:$��
D/btif_config_util( 1988): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:84:24:c0:aa:ff:,ff, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:`��
D/btif_config_util( 1988): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/btif_config_util( 1988): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 1988): enum_config(L344): out, value:���
D/btif_config_util( 1988): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1988): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
D/btif_config_util( 1988): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1988): enum_config(L344): out, value:
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7287 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  838): hidePasspointNotification off =false
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
V/NativeCrypto( 1728): SSL shutdown failed: ssl=0xb045bc00: I/O error during system call, Broken pipe
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:22:52.415 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  838): hidePasspointNotification off =false
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/LGWifiP2pService(  838): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiNetworkAgent(  838): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:22:52.472 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService(  838): SCAN_AVAILABLE : 1
D/RttService(  838): SCAN_AVAILABLE : 1
D/RttService(  838): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  838): DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pDisablingState
D/LGWifiP2pService(  838): P2pDisablingState{ when=-20ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): p2p socket connection lost
D/LGWifiP2pService(  838): P2pDisabledState
D/ConnectivityService(  838): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,D/LGWifiP2pService(  838): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1799): WifiP2pState is changed : false
D/WfdsService( 1799): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1799): doCommand: P2P_STOP_FIND
,D/WfdsService( 1799): Set the WFDS Monitor: false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=-16ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-22ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Forcing reevaluation
D/WifiServiceExtension( 1799): isInternetCheckAvailable return false
D/WfdsMonitor( 1799): WFDS Monitor is stopped
D/CtrlSupplicant( 1799): Received on exit socket, terminate
E/CtrlSupplicant( 1799): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsService( 1799): STATE : WfdsDisabledState - enter
D/WfdsService( 1799): WFDS: Scanner is paused
,D/WfdsMonitor( 1799): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1799): WfdsMonitorThread is received the interrupt - closing
D/WfdsDiscoveryStore( 1799): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1799): DefaultState - msg [9441355] is not handled
,D/CommandListener(  271): Clearing all IP addresses on wlan0
D/ConnectivityService(  838): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  838): disableDataServiceNotify
D/DSQN    (  838): stop dsqn bin
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:22:52.543 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  838): hidePasspointNotification off =false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:22:52.55 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [0]
,D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  838): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524292
D/ConnectivityService(  838): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  838): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 5279): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Disconnected - quitting
D/CSLegacyTypeTracker(  838): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  838): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  838): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1835): |CORE| No family connected
D/Tethering(  838): MasterInitialState.processMessage what=3
V/NetworkPolicy(  838): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  838): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1835): |CORE| No family connected
I/QCNEJ   ( 1835): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  838): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  838): Removing idletimer
W/Settings(  838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1835): |CORE| sendDefaultNwMsg: default = -1
E/ConnectivityService(  838): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory-1( 1746): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 5
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 5677): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 5677): monitor socket send errors count : 1
I/wpa_supplicant( 5677): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1799-2\x00 that cannot receive messages
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 7
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/wpa_supplicant( 5677): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 5677): USIM:  scard_deinit function
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/DhcpStateMachine(  838): StoppedState
D/DhcpStateMachine(  838): StoppedState{ when=-156ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 5677): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  838): InitialState.processMessage what=4
,D/Tethering(  838): sendTetherStateChangedBroadcast 0, 0, 0
D/WfdsService( 1799): Supplicant Connection state is changed : false
D/WfdsService( 1799): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1799): Set the WFDS Monitor: false
D/WfdsMonitor( 1799): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed(  838): stopMonitoring
I/QCNEJ   ( 1835): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1835): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-10 12:22:52.696 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1835): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : this is not treated
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,W/Settings( 1728): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ResourcesManager( 7287): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7287): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7287): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7287): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7287): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/IndexDatabaseHelper( 7287): Using schema version: 115
,I/IndexDatabaseHelper( 7287): Index is fine
,W/ContextImpl( 7287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 1988): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 1988): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1988): ***********state = 13
V/BluetoothPbapReceiver( 1988): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 1988): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1988): state: 13
V/BluetoothPbapService( 1988): Pbap Service closeService in
,V/BluetoothPbapService( 1988): successfully stopped pbap service
V/BluetoothPbapService( 1988): Pbap Service closeService out
V/BluetoothPbapService( 1988): Pbap Service onDestroy
V/BluetoothPbapService( 1988): Pbap Service closeService in
V/BluetoothPbapService( 1988): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1988): [BTUI] cleanup
V/WiFiOffLoadBroadcast( 7287): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7287): MCCMNC not supported: null
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e70dc1b:true
,D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
,D/BluetoothManagerService(  838): Message: 30
,D/BluetoothManagerService(  838): Message: 30
D/LocalBluetoothProfileManager( 7287): Adding local MAP profile
D/BluetoothMap( 7287): Create BluetoothMap proxy object
D/BluetoothManagerService(  838): Message: 30
D/BluetoothManagerService(  838): Message: 30
,D/LocalBluetoothProfileManager( 7287): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7287):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 7287): [BTUI] initUserBindClient
,W/ContextImpl( 7287): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 7287): finishStartingService: stopping service
,D/BluetoothInputDevice( 7287): Proxy object connected
D/HidProfile( 7287): Bluetooth service connected
,D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothPan( 7287): BluetoothPAN Proxy object connected
D/PanProfile( 7287): Bluetooth service connected
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothMap( 7287): Proxy object connected
D/MapProfile( 7287): Bluetooth service connected
D/BluetoothMap( 7287): getConnectedDevices()
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothMap( 7287): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7287): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 7287): [BTUI] cancel All Notification
I/NotificationManager( 7287): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000041) by com.android.settings
I/ActivityManager(  838): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7319 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothPermissionRequest( 7287): onReceive
,D/LGBluetoothAuthorization( 7287): [BTUI] cancel All Notification
I/NotificationManager( 7287): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 7287): com.android.settings: cancel(-1000041) by com.android.settings
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 30.830ms
,V/BluetoothOppReceiver( 1988): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 1988): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 1988): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 1988): com.android.bluetooth: cancel(-1) by com.android.bluetooth
V/BluetoothSapReceiver( 1988): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 1988): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.836ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 23.672ms
,W/bt_userial( 1988): select_read return size <=0:0, exiting userial_read_thread
,D/bt_hwcfg( 1988): hw_epilog_process
,I/bt_userial_vendor( 1988): device fd = 68 close
W/bt-l2cap( 1988): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1988): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1988): ag scb idx 1 not allocated
E/bt-btif ( 1988): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1988): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1988): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1988): ag scb idx 1 not allocated
E/bt-btif ( 1988): BTA AG is already disabled, ignoring ...
E/bt-btif ( 1988): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 1988): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_vendor( 1988): [BTUI] Proto is enabled. Set Proto disable!!
,I/ActivityManager(  838): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7338 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/GKI_LINUX( 1988): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/GKI_LINUX( 1988): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1988): GKI_destroy_task(): task [BTU] terminated
,I/bt-btif ( 1988): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1988): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): Unable to read settings
D/BtSettings.ProfileConfig( 1988): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1988): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1988): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 1988): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1988): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1988): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
W/ResourcesManager( 7338): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
D/HeadsetService( 1988): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1988): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
I/LGBluetoothHfpAdapter( 1988): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 1988): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
W/BluetoothAdapterSe,rvice( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothHeadset( 1746): Proxy object disconnected
D/BluetoothHeadset(  838): Proxy object disconnected
D/AudioService(  838): onServiceDisconnected: Bluetooth profile: 1
D/HeadsetStateMachine( 1988): Exit Disconnected: -1
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1988): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1988): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterState( 1988): Stopping profile services that were post enabled
D/A2dpService( 1988): Received stop request...Stopping profile...
D/BluetoothHeadset( 1746): Proxy object disconnected
D/BluetoothHeadset( 1746): Proxy object disconnected
,I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/A2dpStateMachine( 1988): Exit Disconnected: -1
D/PCSuite ( 7319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7358 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/LGBluetoothA2dpAdapter( 1988): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1988): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 1988): [BTUI] terminate
I/ActivityManager(  838): Killing 6778:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_6778/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  838): Message: 31
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/BluetoothA2dp(  838): Proxy object disconnected
D/AudioService(  838): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 1988): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/HealthService( 1988): Received stop request...Stopping profile...
D/BluetoothInputDevice( 7287): Proxy object disconnected
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/HidProfile( 7287): Bluetooth service disconnected
D/PanService( 1988): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
,D/BtGatt.DebugUtils( 1988): handleDebugAction() action=null
D/BtGatt.GattService( 1988): Received stop request...Stopping profile...
D/BtGatt.GattService( 1988): stop()
D/BtGatt.AdvertiseManager( 1988): advertise clients cleared
D/BluetoothPan( 7287): BluetoothPAN Proxy object disconnected
D/PanProfile( 7287): Bluetooth service disconnected
D/LGBluetoothGattAdapter( 1988): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/BluetoothMapService( 1988): Received stop request...Stopping profile...
D/BluetoothMapService( 1988): stop()
D/BluetoothMapEmailAppObserver( 1988): deinitObservers()
D/BluetoothMapEmailAppObserver( 1988): removeReceiver()
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothMap( 7287): Proxy object disconnected
D/MapProfile( 7287): Bluetooth service disconnected
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/SapService( 1988): Received stop request...Stopping profile...
D/SapService( 1988): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1988): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 1988): [BTUI] terminateSapManager
,D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/HeadsetStateMachine( 1988): Unbinding service...
D/LgeBluetoothSimManager( 1746): [BTUI] SAP_DISABLE_EVT
D/HeadsetPhoneState( 1988): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1988): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1988): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1988): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 1988): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1988): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1988): [BTUI] LGBluetoothHfpAdapter cleanup
D/**BluetoothFTPService( 1988): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1988): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1988): closeFtpServerNative
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/**OppService( 1988): Received stop request...Stopping profile...
D/OppService( 1988): Stopping Bluetooth OppService
D/OppService( 1988): cleanup OPP Service
W/BluetoothOPPServiceJni( 1988): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 1988): Cleaning up Bluetooth OPP callback object
D/OppService( 1988): remove callbacks and handler
D/LGBluetoothOppAdapter( 1988): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1988): cleanup done
D/BluetoothAdapterService( 1988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17708c98
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 1988): cleanupNative
I/GKI_LINUX( 1988): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1988): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1988): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(,393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,W/BluetoothHidServiceJni( 1988): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 1988): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 1988): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1988): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1988): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 1988): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1988): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1988): Handler(): got msg=4
D/BluetoothMapService( 1988): MAP Service closeService in
D/LGBluetoothMapAdapter( 1988): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1988): MAP Service closeService out
D/,BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 1988): cleanup()
D/BluetoothMapService( 1988): MAP Service closeService in
D/LGBluetoothMapAdapter( 1988): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1988): MAP Service closeService out
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 1988): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 1988): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1988): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1988): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 1988): cleanup FTP Service
,V/BluetoothFTPServiceJni( 1988): closeFtpServerNative
V/BluetoothFTPServiceJni( 1988): cleanupNative
W/BluetoothFTPServiceJni( 1988): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1988): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1988): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1988): cleanup done
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - Message: 1
D/BluetoothAdapterService(393251992)( 1988): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 1988): isTurningOnRadio()=false
D/BluetoothAdapterState( 1988): isTurningOffRadio()=false
,D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1988): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1988): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(393251992)( 1988): onProfileServiceStateChange() - All profile services stopped...
D/BluetoothAdapterState( 1988): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1988): Setting state to 10
I/BluetoothAdapterState( 1988): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(393251992)( 1988): updateAdapterState() - Broadcasting state to 1 receivers.
,D/BluetoothManagerService(  838): Message: 60
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  838): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 1988): Entering OffState
D/OppService( 1988): cleanup OPP Service
D/OppService( 1988): remove callbacks and handler
D/LGBluetoothOppAdapter( 1988): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1988): cleanup done
D/BluetoothHeadset(  838): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=false
D/BluetoothA2dp(  838): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7287): onBluetoothStateChange: up=false
D/BluetoothMap( 7287): onBluetoothStateChange: up=false
D/BluetoothPan( 7287): onBluetoothStateChange on: false
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=false
D/BluetoothPbap( 7287): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1746): onBluetoothStateChange: up=false
D/BluetoothAdapterService(393251992)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@85584ae
D/BluetoothManagerService(  838): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  838): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  838): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  838): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  838): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@375984cc mBinding = false
D/BluetoothManagerService(  838): Sending unbind request.
D/BluetoothAdapterService(393251992)( 1988): onUnbind() - calling cleanup
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService(393251992)( 1988): cleanup()
D/LGBluetoothAPIService( 1799): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 1369): 513779980: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1369): 513779980: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1799): Message: 2
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1369): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/LGBluetoothAPIService( 1799): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@36d5ca27 mBinding = false
D/LGBluetoothAPIService( 1799): Sending unbind request.
D/LGBluetoothFeatureConfig( 7287): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7287): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7287): [BTUI] clear device connection state
W/ResourcesManager( 7358): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ContextImpl( 7287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapterService(393251992)( 1988): cleanup() - Cleaning up adapter native
I/bt-btif ( 1988): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1988): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 1988): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 1988): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1988): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1988): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1988): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1988): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1988): GKI_exit_task 2 done
I/GKI_LINUX( 1988): GKI_exit_task 1 done
I/GKI_LINUX( 1988): GKI_exit_task 0 done
I/BluetoothServiceJni( 1988): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 1988): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 1988): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(393251992)( 1988): cleanup() - Bluetooth process exited normally.
D/DockEventReceiver( 7287): finishStartingService: stopping service
D/BluetoothAdapterService(393251992)( 1988): cleanup() done
,I/art     ( 1988): System.exit called, status: 0
,I/AndroidRuntime( 1988): VM exiting with result code 0, cleanup skipped.
D/BluetoothAdapter( 1728): 580121543: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1728): 580121543: getState() :  mService = null. Returning STATE_OFF
V/AudioFlinger(  276): 1988 died, releasing its sessions
V/AudioFlinger(  276):  pid 1746 @ 0
V/AudioFlinger(  276):  pid 3111 @ 1
V/AudioFlinger(  276):  pid 3111 @ 2
D/LGBluetoothUserBindClient( 7287): [BTUI] onServiceDisconnected
,D/FMFRW_FmProxy( 1799): Fm Proxy object disconnected
,I/ActivityManager(  838): Process com.android.bluetooth (pid 1988) has died
W/ActivityManager(  838): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager(  838): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 11000ms
D/BluetoothPermissionRequest( 7287): onReceive
,D/LGBluetoothUtils( 7287): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7287): cancelDiscoverableAlarm(): Enter
,I/ActivityManager(  838): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7383 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,W/ResourcesManager( 7383): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7383): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7383): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 7383): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34e4218a:true
D/BluetoothAdapter( 7358): 393251992: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 7358): 393251992: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapterApp( 7383): Loading JNI Library
V/WiFiOffLoadBroadcast( 7287): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7287): MCCMNC not supported: null
I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,E/BluetoothServiceJni( 7383): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,D/BluetoothAdapterApp( 7383): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3609fa03 Instance Count = 1
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7404 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BluetoothAdapterApp( 7383): onCreate
I/LGBluetoothServiceJni( 7383): classInitNative: succeeds
D/BtSettings.ProfileConfig( 7383): [BTUI] HeadsetServiceis supported
,D/BtSettings.ProfileConfig( 7383): Adding HeadsetService
D/BtSettings.ProfileConfig( 7383): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding A2dpService
D/BtSettings.ProfileConfig( 7383): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding HidService
D/BtSettings.ProfileConfig( 7383): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding HealthService
D/LGBluetoothFeatureConfig( 7383): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 7383): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 7383): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding PanService
,D/BtSettings.ProfileConfig( 7383): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding GattService
D/BtSettings.ProfileConfig( 7383): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 7383): [BTUI] region:EU country:EU
D/BtSettings.ProfileConfig( 7383): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding SapService
,D/BtSettings.ProfileConfig( 7383): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding FTPService
E/BtSettings.ProfileConfig( 7383): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 7383): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 7383): Adding OppService
,D/BtSettings.ProfileConfig( 7383): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 7383): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7383): Unable to read settings
D/BtSettings.ProfileConfig( 7383): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 7383): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 7383): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 7383): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 7383): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 7383): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 7383): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 7383): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 7383): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 7383): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 7383): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 7383): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 7383): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 7383): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 7383): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 7383): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 7383): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 7383): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 7383): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 7383): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/LGBluetoothOppAdapter( 7383): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/LGBluetoothUserBindClient( 7287): [BTUI] onServiceConnected
I/FmServiceJni( 7383): classInitNative: succeeds
,D/FmService( 7383): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@628335fservicecom.broadcom.fm.fmreceiver.FmService@393f01ac
D/FmNativehandler( 7383): start
D/BluetoothRadioManager( 7383): [BTUI] getRadioManager()
D/BluetoothRadioManager( 7383): [BTUI] BluetoothRadioManager()
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@173f64d7:true
,W/ResourcesManager( 7404): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothRadioManager( 7383): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
,V/FmService( 7383): FM Service  onCreate
D/FmService( 7383): Binding service...
D/FMFRW_FmProxy( 1799): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@3dc924d4
D/BluetoothAdapterService( 7383): Set JNI Library before classInit
,D/BluetoothAdapterService(458382577)( 7383): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothAdapterService(458382577)( 7383): onCreate()
,D/BluetoothAdapterState( 7383): make
I/bluedroid( 7383): init
I/BluetoothAdapterState( 7383): Entering OffState
,I/bte_conf( 7383): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 7383): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 7383): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 7383): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 7383): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 7383):  [BTUI] Load_abtddress
D/BTIF_CORE( 7383): [BTUI] lge_wait_for_load_bluetooth_address : success!
D/bt-btif ( 7383): PERSIST_BDADDR_PROPERTY is  F8:95:C7:87:85:54
D/bt-btif ( 7383): Got prior random BDA F8:95:C7:87:85:54
I/bluedroid( 7383): get_profile_interface socket
I/GKI_LINUX( 7383): gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 7383): btif task starting
I/bluedroid( 7383): get_profile_interface map_client
D/bt-btif ( 7383): btif_associate_evt: notify ASSOCIATE_JVM
E/BluetoothServiceJni( 7383): Error getting mapclient interface
I/bt-btif ( 7383): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 7383): btif_get_adapter_property 2
I/bt-btif ( 7383): btif_get_adapter_property 1
I/bt-btif ( 7383): execute storage request event : 3
D/bt-btif ( 7383): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 7383): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 7383): Address is:F8:95:C7:87:85:54
I/bt-btif ( 7383): execute storage request event : 3
D/bt-btif ( 7383): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 7383): in, bd addr:, prop type:1, len:512
I/bt-btif ( 7383): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 7383): Name is: G3s-1
,D/BluetoothManagerService(  838): Bluetooth Adapter name changed to G3s-1
D/BluetoothAdapterService( 7383): getAdapterService() - Service not available
D/LGBluetoothServiceAdapter( 7383): [BTUI] check adapter is available - false.
D/LGBluetoothSettingsDBObserver( 7383): [BTUI] register observer for LG device name DB
D/BluetoothManagerService(  838): Stored Bluetooth name: G3s-1
D/BluetoothAdapterService(458382577)( 7383): onBind()
D/lge_bdaddr_loader( 7430): [BTUI] bdaddr_loader ::: START
,D/lge_bdaddr_loader( 7430): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 7430): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 7430): [BTUI] bdaddr to set in property : F8:95:C7:87:85:54
V/BluetoothSapReceiver( 7383): [BTUI] checkServiceStart
D/BluetoothRadioManager( 7383): onServiceConnected: connected to AdapterService com.android.bluetooth.btservice.AdapterService
D/BluetoothRadioManager( 7383): Message: 40
D/BluetoothRadioManager( 7383): MESSAGE_RADIO_SERVICE_CONNECTED: 1
D/BluetoothRadioManager( 7383):  Turning on BT modules Radio on = false
D/LGBluetoothStateChangeReceiver( 7383): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
E/lge_bdaddr_loader( 7430): [BTUI] bluetooth_load_bdaddress : OK => F8:95:C7:87:85:54
D/lge_bdaddr_loader( 7430): [BTUI] bdaddr_loader ::: END
,I/ActivityManager(  838): Process com.android.vending (pid 6882) has died
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 7338): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/AuthorizationBluetoothService( 1728): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Babel_SMS( 7404): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7404): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7404): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7404): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7404): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7404): MmsConfig.loadFromResources
E/Babel_SMS( 7404): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7404): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7404): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7404): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7404): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7404): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7404): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7404): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7404): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7404): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7404): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7404): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7404): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7404): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7404): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7404): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7404): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7404): found sensor: Motion Accel, handle=46
,W/Settings( 7404): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7404): startup - clean
I/art     ( 7404): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/Babel   ( 7404): deleted: false for 0
,I/art     ( 7404): CheckpointMarkThreadRoots callback created = 0xb042d890
,V/WiFiOffLoadBroadcast( 7287): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7287): MCCMNC not supported: null
I/PCSuite ( 7319): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7287): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7287): MCCMNC not supported: null
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 7404): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7404): Unsupported mime audio/adpcm
W/AudioCapabilities( 7404): Unsupported mime audio/g726
W/AudioCapabilities( 7404): Unsupported mime audio/x-ms-wma
D/UsbSettingsReceiver( 7287): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
W/AudioCapabilities( 7404): Unsupported mime audio/wma-voice
,D/UsbSettingsReceiver( 7287): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7287): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7287): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7287): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/VideoCapabilities( 7404): Unsupported mime video/mjpg
W/VideoCapabilities( 7404): Unsupported mime video/theora
W/AudioCapabilities( 7404): Unsupported mime audio/evrc
,W/AudioCapabilities( 7404): Unsupported mime audio/qcelp
,D/UsbSettingsControl( 7287): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7287): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7287): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7287): [AUTORUN] onReceive() : errorList=[]
W/VideoCapabilities( 7404): Unrecognized profile 2130706433 for video/avc
D/UsbSettingsControl( 7287): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7287): [AUTORUN] setTetherStatus() : status=false
W/AudioCapabilities( 7404): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7404): Unsupported mime audio/qcelp
W/AudioCapabilities( 7404): Unsupported mime audio/evrc
W/VideoCapabilities( 7404): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7404): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7404): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7404): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7451 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/VideoCapabilities( 7404): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7404): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7404): onServiceConnected
W/Babel   ( 7404): Attempted to change video mute state without an active call.
I/NotificationManager( 7404): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/LGDMClient( 7451): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 7451): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 7287): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7287): MCCMNC not supported: null
I/PCSuite ( 7319): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 7451): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 7451): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7451): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  838): Killing 6840:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10069/pid_6840/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6958): QS Service created
V/LGMDMManager( 7358): Create singleton instance
,E/UEI.SmartControl( 6958): QS start get config
,D/UEI.SmartControl( 6958):  configuring local db...
,I/AudioManager( 7358): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6958):  ---- Has DB8: true
,D/UEI.SmartControl( 6958): QS start statue = true Error code = 0
D/UEI.SmartControl( 6958): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6958): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6958): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6958): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6958): IrrcClient ++ 
D/irrcClient( 6958): getIrrcService ++ 
D/irrcClient( 6958): getIrrcService -- 
D/irrcClient( 6958): IrrcClient -- 
W/irrc_jni( 6958): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6958): Services init done
I/UEI.SmartControl( 6958): Device manager: loading config....
D/UEI.SmartControl( 6958): Config is loaded...
D/UEI.SmartControl( 6958): QS Service init finished
,D/UEI.SmartControl( 6958): QS Service version name: 0.1.73
D/UEI.SmartControl( 6958): QS Service version code: 1073
D/UEI.SmartControl( 6958): Service requested: Control
D/UEI.SmartControl( 6958): Internal service binding...
D/UEI.SmartControl( 6958): -----IControl: 11
D/UEI.SmartControl( 6958): File observer start...
E/UEI.SmartControl( 6958): IR Port is disabled: false
D/UEI.SmartControl( 6958): Starting file observer...
D/UEI.SmartControl( 6958): Caller: com.lge.qremote
D/UEI.SmartControl( 6958): ------------ IControl registerCallback...
I/UEI.SmartControl( 6958): Registering callback...
D/UEI.SmartControl( 6958): -----IControl: 19
D/UEI.SmartControl( 6958): Caller: com.lge.qremote
I/UEI.SmartControl( 6958): Registering Services Ready callback...
I/UEI.SmartControl( 6958): Notify client services are ready...
D/UEI.SmartControl( 6958): -----IControl: 8
,D/UEI.SmartControl( 6958): Caller: com.lge.qremote
I/AudioManager( 7358): getMode name:com.lge.qremote
I/ActivityManager(  838): Killing 6857:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,D/UEI.SmartControl( 6958):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6958): Notify AllClients services are ready: 0
W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_6857/cgroup.procs: No such file or directory
I/AudioManager( 7358): getMode name:com.lge.qremote
,I/AudioManager( 7358): getMode name:com.lge.qremote
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  838): onReceive
D/LocSvc_java(  838): got connectivity action
D/LocSvc_java(  838): broadcast - no network connections
D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
,I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7485 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocSvc_java(  838): onReceive
D/LocSvc_java(  838): got connectivity action
D/LocSvc_java(  838): broadcast - no network connections
D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkChangeNotifierAutoDetect( 1935): Network connectivity changed, type is: 6
,I/MusicStore( 7485): Database version: 120
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7485): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7485): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7485): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7485): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7485): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7485): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7485): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7485): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7c4da21: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7485): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7485): GMSCore installation verified
I/ConfigStore( 7485): Config Database version: 1
D/ConnectivityService(  838): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3740a49a)
,D/ConnectivityService(  838): dumpNetworkRequest
D/ConnectivityService(  838): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  838): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  838): Process com.google.android.gms (pid 5279) has died
,I/art     (  838): Explicit concurrent mark sweep GC freed 49765(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.212ms total 146.213ms
,I/MediaRouter( 7485): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7485): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7530 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  838): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=7548 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GHttpClientFactory( 7485): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7485): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7548): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7548): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7530): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7530): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7530): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/MultiDex( 7548): VM with version 2.1.0 has multidex support
I/MultiDex( 7548): install
I/MultiDex( 7548): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  838): Process com.google.android.youtube (pid 7020) has died
,I/LGEmail ( 7530): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7530): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/JNIHelp ( 7548): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7548): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7548): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15e96b04: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7548): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7548): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7548): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/NotificationManager( 7485): com.google.android.music: cancel(1061) by com.google.android.music
,W/ProcessCpuTracker(  838): Skipping unknown process pid 7404
,I/ActivityManager(  838): Process com.google.android.talk (pid 7404) has died
,D/eas_req ( 7530): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 7451): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7451): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7451): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/HubEmail( 7530): JNI_OnLoad()
I/HubEmail( 7530): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7530): registerNatives()
I/HubEmail( 7530): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7530): registerNativeMethods()
I/HubEmail( 7530): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7530): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/LGDMClient( 7451): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7451): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7588 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 7530): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/NativeLibraryUtils( 7548): Install completed successfully. count=14 extracted=0
,I/AppUp4:AppBoxCP( 7588): onCreate
,W/AppUp4:DB( 7588):  [AppBoxDatabaseHelper] construct
D/LGWifiP2pService(  838): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/AppUp4:DB( 7588):  setFingerPrint start
I/AppUp4:DB( 7588):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7588):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7588):  SDK version = 0
I/AppUp4:DB( 7588):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7588): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7588): onReceive
I/AppUp4:CustModeStarterReceiver( 7588): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7588): Context : android.app.ReceiverRestrictedContext@95e4e75
D/AppUp4:CustFacade( 7588): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7588): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7588): begin check event
I/AppUp4:CustModeStarterReceiver( 7588): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7588): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7588): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7588): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7588): handleAsyncCustNotification do not startCustService
I/ActivityManager(  838): Killing 7338:com.lge.settings.easy/1000 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_7338/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3111): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3111): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3111): networkInfo.isConnected() = false
,I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7613 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7613): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7613): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7613): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  838): Killing 7287:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 7613): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7613): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7613): [parse] Load xml
V/TelephonyAutoProfiling( 7613): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7613): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7613): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_7287/cgroup.procs: No such file or directory
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ActivityManager(  838): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7633 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.305ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 22.780ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.686ms
,I/ActivityManager(  838): Killing 7319:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_7319/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:22:57
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
D/WeatherAncestor( 2677): connectivity changed - connection : true
,D/Weather_cast( 2677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:22:57
D/WeatherService( 2677): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : false
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7650 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7650): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7650): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7650): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7650): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7650): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7650): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7650): MmsConfig.loadFromResources
E/Babel_SMS( 7650): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7650): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7650): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7650): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7650): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7650): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7650): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7650): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7650): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7650): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7650): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7650): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7650): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7650): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7650): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7650): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7650): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7650): found sensor: Motion Accel, handle=46
,W/Settings( 7650): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7650): startup - clean
,I/Babel   ( 7650): deleted: false for 0
,I/art     ( 7650): CheckpointMarkThreadRoots callback created = 0xb042d910
,I/art     ( 7650): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,I/ActivityManager(  838): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7689 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7650): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7650): Unsupported mime audio/adpcm
W/AudioCapabilities( 7650): Unsupported mime audio/g726
W/AudioCapabilities( 7650): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7650): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7650): Unsupported mime video/mjpg
W/VideoCapabilities( 7650): Unsupported mime video/theora
W/AudioCapabilities( 7650): Unsupported mime audio/evrc
,W/AudioCapabilities( 7650): Unsupported mime audio/qcelp
W/VideoCapabilities( 7650): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7650): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7650): Unsupported mime audio/qcelp
W/AudioCapabilities( 7650): Unsupported mime audio/evrc
,W/VideoCapabilities( 7650): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7650): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7650): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7650): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7650): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7650): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7650): onServiceConnected
,W/Babel   ( 7650): Attempted to change video mute state without an active call.
I/Babel   ( 7650): connection state changed from UNKNOWN to DISCONNECTED
I/NotificationManager( 7650): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  838): Killing 6958:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7358): android.os.DeadObjectException
,W/System.err( 7358): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7358): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7358): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7358): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7358): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7358): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7358): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7358): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7358): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7358): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
,W/System.err( 7358): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7358): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7358): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7358): android.os.DeadObjectException
W/System.err( 7358): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7358): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7358): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7358): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7358): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7358): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7358): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7358): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7358): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7358): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7358): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7358): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7358): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  838): failed to open /acct/uid_10089/pid_6958/cgroup.procs: No such file or directory
W/ActivityManager(  838): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7711 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
D/UEI.SmartControl( 7711): Quickset Services start...
W/ContextImpl( 7689): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/UEI.SmartControl( 7711): Manufacture = LGE
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7689): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/UEI.SmartControl( 7711): File observer start...
E/UEI.SmartControl( 7711): IR Port is disabled: false
D/UEI.SmartControl( 7711): Starting file observer...
D/UEI.SmartControl( 7711): Extracting JNI libs...
D/UEI.SmartControl( 7711): --- this system supports 32-bit or 64-bit only
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7689): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7689): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7689): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7689):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7689):   adb logcat -s GAv4
,W/GAv4    ( 7689): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7689): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7689): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/UEI.SmartControl( 7711): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7711): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7711): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7711): --- Selecting new region: 2
,I/UEI.SmartControl( 7711): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7711): Platform has CIR...
D/UEI.SmartControl( 7711): NO CIR support, need to check package...
I/UEI.SmartControl( 7711): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7711): QS Service created
E/UEI.SmartControl( 7711): QS start get config
,D/UEI.SmartControl( 7711): Loading JNI Libs...
,D/UEI.SmartControl( 7711):  configuring local db...
I/WebViewFactory( 7689): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7689): Time to load native libraries: 4 ms (timestamps 449-453)
I/LibraryLoader( 7689): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7689): Binding Chromium to main looper Looper (main, tid 1) {2efdba40}
I/LibraryLoader( 7689): Expected native library version number "",actual native library version number ""
I/chromium( 7689): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7689): Initializing chromium process, singleProcess=true
,W/art     ( 7689): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7689): ApplicationContext is null in ApplicationStatus
W/chromium( 7689): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7689): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7689): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7689): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7689): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7689): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7689): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7689): Remote Branch: 
I/Adreno-EGL( 7689): Local Patches: 
I/Adreno-EGL( 7689): Reconstruct Branch: 
D/UEI.SmartControl( 7711):  ---- Has DB8: true
,D/UEI.SmartControl( 7711): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7711): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7711): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7711): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7711): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7711): IrrcClient ++ 
D/irrcClient( 7711): getIrrcService ++ 
D/irrcClient( 7711): getIrrcService -- 
D/irrcClient( 7711): IrrcClient -- 
W/irrc_jni( 7711): IRRCPlayer_nativeInit -- 
V/AudioPolicyService(  276): registerClient() client 0xb40275c0, uid 10079
,W/AudioManagerAndroid( 7689): Requires BLUETOOTH permission
D/UEI.SmartControl( 7711): Services init done
I/NSApplication( 7689): Starting up...
D/UEI.SmartControl( 7711): QS Service init finished
I/UEI.SmartControl( 7711): Device manager: loading config....
D/UEI.SmartControl( 7711): QS Service version name: 0.1.73
D/UEI.SmartControl( 7711): QS Service version code: 1073
D/UEI.SmartControl( 7711): Service requested: Control
,D/UEI.SmartControl( 7711): Config is loaded...
D/UEI.SmartControl( 7711):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7711): Notify AllClients services are ready: 0
I/ActivityManager(  838): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7779 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 7358:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7711): Request IControl service: devices are loaded...
,W/libprocessgroup(  838): failed to open /acct/uid_10106/pid_7358/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Killing 7485:com.google.android.music:main/u0a81 (adj 15): empty #11
,D/UEI.SmartControl( 7711): Internal service binding...
W/libprocessgroup(  838): failed to open /acct/uid_10081/pid_7485/cgroup.procs: No such file or directory
I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7805 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 7530:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10021/pid_7530/cgroup.procs: No such file or directory
,W/ResourcesManager( 7805): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
,I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
W/art     ( 7548): Suspending all threads took: 5.394ms
,I/iu.SyncManager( 7548): SYNC; picasa accounts
,D/NetworkLogImpl( 7548): Loaded NetworkSpeedPredictor
I/ActivityManager(  838): Killing 7451:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_7451/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7843 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7843): Database version: 120
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7843): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7843): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7843): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7843): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7843): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7843): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7843): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7843): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7c4da21: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7843): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7843): GMSCore installation verified
I/ConfigStore( 7843): Config Database version: 1
,I/art     (  838): Explicit concurrent mark sweep GC freed 16674(876KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.243ms total 151.492ms
,I/MediaRouter( 7843): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7843): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7871 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7843): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7843): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  838): Killing 7588:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 7871): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7871): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7871): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_7588/cgroup.procs: No such file or directory
,I/NotificationManager( 7843): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7871): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7871): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7871): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7894 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7871): JNI_OnLoad()
I/HubEmail( 7871): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7871): registerNatives()
I/HubEmail( 7871): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7871): registerNativeMethods()
I/HubEmail( 7871): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7871): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  838): Killing 7613:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10038/pid_7613/cgroup.procs: No such file or directory
,W/Settings( 7871): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7894): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7894): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7894): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7894): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7894): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7916 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 7633:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10051/pid_7633/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7916): onCreate
,W/AppUp4:DB( 7916):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7916):  setFingerPrint start
I/AppUp4:DB( 7916):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7916):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7916):  SDK version = 0
I/AppUp4:DB( 7916):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7916): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7916): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7916): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7916): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7916): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7916): onReceive
I/AppUp4:CustModeStarterReceiver( 7916): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7916): Context : android.app.ReceiverRestrictedContext@95e4e75
D/AppUp4:CustFacade( 7916): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7916): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7916): begin check event
I/AppUp4:CustModeStarterReceiver( 7916): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7916): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7916): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7916): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7916): handleAsyncCustNotification do not startCustService
I/ActivityManager(  838): Killing 7650:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10061/pid_7650/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3111): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3111): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3111): networkInfo.isConnected() = false
I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7935 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7935): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7935): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7935): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  838): Killing 7689:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/PhoneMonitor( 7935): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7935): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 7935): [parse] Load xml
V/TelephonyAutoProfiling( 7935): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7935): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7935): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  838): failed to open /acct/uid_10079/pid_7689/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7954 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 361us total 22.778ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.768ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.066ms
,I/ActivityManager(  838): Killing 7711:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10089/pid_7711/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:2
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
D/WeatherAncestor( 2677): connectivity changed - connection : true
D/Weather_cast( 2677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:2
D/WeatherService( 2677): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : false
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7971 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7971): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{24dd1d3d type 2 when 453571 com.google.android.gms} when 453571
,I/Babel_SMS( 7971): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7971): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7971): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7971): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7971): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7971): MmsConfig.loadFromResources
E/Babel_SMS( 7971): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7971): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7971): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7971): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7971): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7971): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7971): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7971): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7971): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7971): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7971): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7971): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7971): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7971): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7971): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7971): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7971): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7971): found sensor: Motion Accel, handle=46
,W/Settings( 7971): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7971): startup - clean
,I/Babel   ( 7971): deleted: false for 0
,I/art     ( 7971): CheckpointMarkThreadRoots callback created = 0xb042d590
,D/ConnectivityService(  838): Failed to find a new network - expiring NetTransition Wakelock
I/art     ( 7971): CheckpointMarkThreadRoots callback created = 0xb042d560
,I/ActivityManager(  838): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8008 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7971): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7971): Unsupported mime audio/adpcm
W/AudioCapabilities( 7971): Unsupported mime audio/g726
W/AudioCapabilities( 7971): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7971): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7971): Unsupported mime video/mjpg
W/VideoCapabilities( 7971): Unsupported mime video/theora
,W/AudioCapabilities( 7971): Unsupported mime audio/evrc
W/AudioCapabilities( 7971): Unsupported mime audio/qcelp
W/VideoCapabilities( 7971): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7971): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7971): Unsupported mime audio/qcelp
W/AudioCapabilities( 7971): Unsupported mime audio/evrc
W/VideoCapabilities( 7971): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7971): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7971): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7971): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7971): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7971): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7971): onServiceConnected
,W/Babel   ( 7971): Attempted to change video mute state without an active call.
I/Babel   ( 7971): connection state changed from UNKNOWN to DISCONNECTED
I/NotificationManager( 7971): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  838): Killing 7779:com.android.chrome/u0a48 (adj 15): empty #11
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,W/libprocessgroup(  838): failed to open /acct/uid_10048/pid_7779/cgroup.procs: No such file or directory
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8008): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8008): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 8008): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8008):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8008):   adb logcat -s GAv4
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8008): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8008): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 8008): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8008): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8008): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 8008): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8008): Time to load native libraries: 1 ms (timestamps 4338-4339)
,I/LibraryLoader( 8008): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 8008): Binding Chromium to main looper Looper (main, tid 1) {2efdba40}
I/LibraryLoader( 8008): Expected native library version number "",actual native library version number ""
I/chromium( 8008): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8008): Initializing chromium process, singleProcess=true
,W/art     ( 8008): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 8008): ApplicationContext is null in ApplicationStatus
W/chromium( 8008): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8008): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8008): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8008): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8008): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8008): Build Date: 03/02/15 Mon
I/Adreno-EGL( 8008): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 8008): Remote Branch: 
I/Adreno-EGL( 8008): Local Patches: 
I/Adreno-EGL( 8008): Reconstruct Branch: 
I/NSApplication( 8008): Starting up...
,V/AudioPolicyService(  276): registerClient() client 0xb3db5ee0, uid 10079
,W/AudioManagerAndroid( 8008): Requires BLUETOOTH permission
I/ActivityManager(  838): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8074 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 7805:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_7805/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8093 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 7843:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10081/pid_7843/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 454750085038; DSPS: 14992686; Offset : -2793888558
W/ResourcesManager( 8093): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Killing 7871:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10021/pid_7871/cgroup.procs: No such file or directory
,D/WearableService( 1728): callingUid 10006, callindPid: 1728
,E/MDM     ( 1728): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7548): Restart initialization of location
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=8123 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     ( 7548): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7548): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/ResourcesManager( 8123): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  838): Message: 20
,D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d714cc0:true
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
D/BluetoothAdapter( 8123): 393251992: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 8123): 393251992: getState() :  mService = null. Returning STATE_OFF
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
I/art     (  838): Explicit concurrent mark sweep GC freed 14155(663KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.526ms total 166.174ms
,I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8159 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 8123): Create singleton instance
,W/IcingInternalCorpora( 7548): getNumBytesRead when not calculated.
,D/UEI.SmartControl( 8159): Quickset Services start...
,I/UEI.SmartControl( 8159): Manufacture = LGE
D/UEI.SmartControl( 8159): File observer start...
E/UEI.SmartControl( 8159): IR Port is disabled: false
D/UEI.SmartControl( 8159): Starting file observer...
D/UEI.SmartControl( 8159): Extracting JNI libs...
D/UEI.SmartControl( 8159): --- this system supports 32-bit or 64-bit only
I/AudioManager( 8123): getMode name:com.lge.qremote
,D/UEI.SmartControl( 8159): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8159): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8159): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 8159): --- Selecting new region: 2
,I/UEI.SmartControl( 8159): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 8159): Platform has CIR...
D/UEI.SmartControl( 8159): NO CIR support, need to check package...
I/UEI.SmartControl( 8159): Model: LG-D722 uses JNI
D/UEI.SmartControl( 8159): QS Service created
E/UEI.SmartControl( 8159): QS start get config
,D/UEI.SmartControl( 8159): Loading JNI Libs...
,D/UEI.SmartControl( 8159):  configuring local db...
D/UEI.SmartControl( 8159):  ---- Has DB8: true
,D/UEI.SmartControl( 8159): QS start statue = true Error code = 0
D/UEI.SmartControl( 8159): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8159): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8159): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 8159): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8159): IrrcClient ++ 
D/irrcClient( 8159): getIrrcService ++ 
D/irrcClient( 8159): getIrrcService -- 
D/irrcClient( 8159): IrrcClient -- 
W/irrc_jni( 8159): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 8159): Services init done
I/UEI.SmartControl( 8159): Device manager: loading config....
D/UEI.SmartControl( 8159): QS Service init finished
D/UEI.SmartControl( 8159): QS Service version name: 0.1.73
D/UEI.SmartControl( 8159): QS Service version code: 1073
D/UEI.SmartControl( 8159): Config is loaded...
,D/UEI.SmartControl( 8159): Service requested: Control
D/UEI.SmartControl( 8159): Internal service binding...
D/UEI.SmartControl( 8159): -----IControl: 11
D/UEI.SmartControl( 8159): Caller: com.lge.qremote
D/UEI.SmartControl( 8159): ------------ IControl registerCallback...
I/UEI.SmartControl( 8159): Registering callback...
D/UEI.SmartControl( 8159): -----IControl: 19
D/UEI.SmartControl( 8159):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 8159): Caller: com.lge.qremote
I/UEI.SmartControl( 8159): Registering Services Ready callback...
I/UEI.SmartControl( 8159): Notify AllClients services are ready: 0
I/UEI.SmartControl( 8159): Notify client services are ready...
D/UEI.SmartControl( 8159): -----IControl: 8
D/UEI.SmartControl( 8159): Caller: com.lge.qremote
I/AudioManager( 8123): getMode name:com.lge.qremote
,I/ActivityManager(  838): Killing 7894:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_7894/cgroup.procs: No such file or directory
,I/AudioManager( 8123): getMode name:com.lge.qremote
I/AudioManager( 8123): getMode name:com.lge.qremote
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ActivityManager(  838): Killing 7916:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_7916/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8159): Internal timer expired: 1
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,W/SQLiteConnectionPool( 7548): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 474750877842; DSPS: 15648072; Offset : -2793888377
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{5ea2f97 type 2 when 475007 com.google.android.gms} when 475007
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  838): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 494751669502; DSPS: 16303458; Offset : -2793890175
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{5007584 type 2 when 514738 com.google.android.gms} when 514738
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 514755950952; DSPS: 16958958; Offset : -2793882384
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 534760466622; DSPS: 17614466; Offset : -2793884306
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 554761198489; DSPS: 18269850; Offset : -2793882698
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 574761987961; DSPS: 18925236; Offset : -2793886815
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{2d18716d type 2 when 594177 com.google.android.gms} when 594177
D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 594762663005; DSPS: 19580618; Offset : -2793883417
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 614763348154; DSPS: 20236001; Offset : -2793901970
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 634764121792; DSPS: 20891386; Offset : -2793889031
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 654764883920; DSPS: 21546771; Offset : -2793889816
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 674765557297; DSPS: 22202153; Offset : -2793890014
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 694766374112; DSPS: 22857540; Offset : -2793895246
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 714767048011; DSPS: 23512922; Offset : -2793892448
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 734767830972; DSPS: 24168308; Offset : -2793905235
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{d45b1a2 type 2 when 753014 com.google.android.gms} when 753014
D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 754768703360; DSPS: 24823696; Offset : -2793885203
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 774769404551; DSPS: 25479079; Offset : -2793888026
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 794770550689; DSPS: 26134477; Offset : -2793899317
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 814771426932; DSPS: 26789865; Offset : -2793877930
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 834772103539; DSPS: 27445248; Offset : -2793902994
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 854772856135; DSPS: 28100632; Offset : -2793883053
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 874773634878; DSPS: 28756018; Offset : -2793898575
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 894774312995; DSPS: 29411400; Offset : -2793890595
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 914774989497; DSPS: 30066782; Offset : -2793885818
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 934775756365; DSPS: 30722167; Offset : -2793882097
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 954776431722; DSPS: 31377550; Offset : -2793908463
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 974777112235; DSPS: 32032932; Offset : -2793899231
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 994777879050; DSPS: 32688317; Offset : -2793897414
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1014778716386; DSPS: 33343704; Offset : -2793884052
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1034779491743; DSPS: 33999090; Offset : -2793900121
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1054780394340; DSPS: 34654479; Offset : -2793882300
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{28182e33 type 2 when 1070651 com.google.android.gms} when 1070651
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager(  838): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8268 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 8268): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8268): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3231ffe
D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
I/ActivityManager(  838): Killing 7935:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10038/pid_7935/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1074781267145; DSPS: 35309868; Offset : -2793894792
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1094782057190; DSPS: 35965254; Offset : -2793900157
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1114782823380; DSPS: 36620639; Offset : -2793894431
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1134783588580; DSPS: 37276024; Offset : -2793892328
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1154784269927; DSPS: 37931406; Offset : -2793884685
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1174784950492; DSPS: 38586789; Offset : -2793905868
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1194785647047; DSPS: 39242171; Offset : -2793880908
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1214786428497; DSPS: 39897557; Offset : -2793892837
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  838): User[0] Flushing usage stats to disk
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1234787267135; DSPS: 40552945; Offset : -2793908613
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1254787950461; DSPS: 41208327; Offset : -2793894721
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1274788627381; DSPS: 41863709; Offset : -2793889135
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1294789393362; DSPS: 42519094; Offset : -2793888229
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1314790225022; DSPS: 43174481; Offset : -2793878382
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1334791081473; DSPS: 43829869; Offset : -2793878534
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1354791859485; DSPS: 44485255; Offset : -2793892103
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1374792638906; DSPS: 45140641; Offset : -2793908093
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1394793420200; DSPS: 45796026; Offset : -2793887628
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1414794209724; DSPS: 46451412; Offset : -2793891431
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1434795088830; DSPS: 47106801; Offset : -2793897543
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1454795856374; DSPS: 47762186; Offset : -2793894709
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1474796704648; DSPS: 48417574; Offset : -2793900978
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1494797557609; DSPS: 49072962; Offset : -2793902616
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1514798307862; DSPS: 49728346; Offset : -2793884863
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1534799065563; DSPS: 50383731; Offset : -2793890153
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1554799725086; DSPS: 51039113; Offset : -2793902016
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1574800856590; DSPS: 51694510; Offset : -2793899611
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1594801656999; DSPS: 52349896; Offset : -2793890393
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1614802415741; DSPS: 53005281; Offset : -2793896857
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  838): battery changed pluggedType: 2
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1634803274796; DSPS: 53660669; Offset : -2793892293
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
,I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1654804066298; DSPS: 54316055; Offset : -2793894274
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1674804841082; DSPS: 54971440; Offset : -2793882377
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  838): battery changed pluggedType: 2
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1694805702429; DSPS: 55626829; Offset : -2793903801
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1ed165f0 type 2 when 1705928 com.google.android.gms} when 1705928
D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1714806383254; DSPS: 56282211; Offset : -2793894206
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1734807063976; DSPS: 56937593; Offset : -2793887292
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1754807746677; DSPS: 57592976; Offset : -2793904595
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{33d7b769 type 2 when 1758164 android} when 1758164
D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1774808528908; DSPS: 58248361; Offset : -2793886085
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1794809210359; DSPS: 58903744; Offset : -2793905263
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1814810280665; DSPS: 59559138; Offset : -2793872554
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1834811020292; DSPS: 60214523; Offset : -2793895971
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1854811785754; DSPS: 60869908; Offset : -2793893370
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=593477980, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{3e1d7a8f type 0 when 1449746995921 com.google.android.gms} when 1449746995921
,I/ProcessStatsService(  838): Prepared write state in 18ms
,I/DigitalAppWidgetProvider( 8268): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8268): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3231ffe
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=593477980 [*alarm*], flags=0x0
I/NotificationManager( 7548): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
I/EventLogService( 7548): Aggregate from 1449746239474 (log), 1449745195814 (data)
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
V/NativeCrypto( 1728): SSL shutdown failed: ssl=0xb045b800: I/O error during system call, Connection timed out
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
V/NativeCrypto( 1728): SSL shutdown failed: ssl=0xaaee0000: I/O error during system call, Connection timed out
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,E/Auth    ( 1728): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
I/ProcessStatsService(  838): Pruning old procstats: /data/system/procstats/state-2015-12-09-17-14-38.bin
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  457): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1874812574652; DSPS: 61525294; Offset : -2793897981
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 1894813354904; DSPS: 62180679; Offset : -2793880851
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8441): 
D/AndroidRuntime( 8441): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8441): CheckJNI is OFF
D/AndroidRuntime( 8441): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  838): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  838): Killing 5540:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  838): Skipping PackageSetting{20658119 com.example.hello/10030} due to missing metadata
I/WindowState(  838): WIN DEATH: Window{9fdfcda u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  838): Focus left window: Window{9fdfcda u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  838): Window went away: Window{9fdfcda u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
I/ActivityManager(  838):   Force finishing activity ActivityRecord{11fbe7a4 u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  838): Display changed displayId=0
D/DSDPConnection( 1746): Display #0 changed.
W/ActivityManager(  838): Spurious death for ProcessRecord{a139a9b 5540:com.test.thalitest/u0a316}, curProc for 5540: null
I/ActivityManager(  838): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  838):   Force finishing activity ActivityRecord{11fbe7a4 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  838): Duplicate finish request for ActivityRecord{11fbe7a4 u0 com.test.thalitest/.MainActivity t220 f}
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1873): [Launcher.java:5203:onStart()]onStart
I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
I/art     ( 1935): Explicit concurrent mark sweep GC freed 9842(608KB) AllocSpace objects, 2(47KB) LOS objects, 40% free, 12MB/20MB, paused 1.366ms total 94.306ms
W/System.err( 3427): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3427): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3427): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3427): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3427): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3427): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3427): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3427): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3427): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3427): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3427): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3427): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1873): [Launcher.java:776:onResume()]onResume
I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8473 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  838): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8481 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     (  838): Explicit concurrent mark sweep GC freed 35132(2MB) AllocSpace objects, 10(304KB) LOS objects, 33% free, 23MB/35MB, paused 4.575ms total 200.290ms
I/art     (  838): WaitForGcToComplete blocked for 171.574ms for cause Explicit
I/[LGHome]LGActivityUtil( 1873): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1873): [Launcher.java:929:onResume()]onResume end
I/Activity( 1873): Activity.onPostResume() called 
W/ResourcesManager( 8473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8473): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8473): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
I/LockScreenSettings( 8481): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/[LGHome]LGWallpaperInfo( 1873): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1873): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
D/InputDispatcher(  838): Focus entered window: Window{35311e18 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9e71484,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9e71484,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1369): handleShortcutListChanged...
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
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
D/administrator(  838): Handling package changes for user 0
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/ActivityManager(  838): Killing 7954:com.lge.drmservice/u0a51 (adj 15): empty #11
I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1873): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1369): handleShortcutListChanged...
W/libprocessgroup(  838): failed to open /acct/uid_10051/pid_7954/cgroup.procs: No such file or directory
I/LGEmail ( 8473): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8473): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/art     (  838): Explicit concurrent mark sweep GC freed 4773(260KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.378ms total 323.064ms
D/AndroidRuntime( 8441): Shutting down VM
I/PackageChangeReceiver( 8473): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/NotificationService(  838): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  838): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8514 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  838): Killing 8008:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/InputMethodManagerService(  838): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  838): Got RemoteException sending setActive(false) notification to pid 5540 uid 10316
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  838): failed to open /acct/uid_10079/pid_8008/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
D/TaskPersister(  838): removeObsoleteFile: deleting file=220_task.xml
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  838): Timeline: Activity_windows_visible id: ActivityRecord{27578791 u0 com.lge.launcher2/.Launcher t219} time:1906315
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/AppUp4:AppBoxCP( 8514): onCreate
W/AppUp4:DB( 8514):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8514):  setFingerPrint start
I/AppUp4:DB( 8514):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8514):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8514):  SDK version = 0
I/AppUp4:DB( 8514):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8514): AppBoxApplication onCreate()
W/IInputConnectionWrapper( 1873): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1873): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1873): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AppUp4:PreloadHelper( 8514): added Exclude : com.test.thalitest
E/b       ( 1598): Unable to connect to the editor to retrieve text... will retry later
I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8537 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  838): Killing 8074:com.android.chrome/u0a48 (adj 15): empty #11
I/[LGHome]EVENT( 1873): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1873): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1873): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 335us total 33.987ms
I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 23.800ms
W/libprocessgroup(  838): failed to open /acct/uid_10048/pid_8074/cgroup.procs: No such file or directory
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.211ms
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1873): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}

```
