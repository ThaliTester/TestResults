#### Test 5615109319b4771_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/AndroidRuntime( 6110): 
D/AndroidRuntime( 6110): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6110): CheckJNI is OFF
D/AndroidRuntime( 6110): Calling main entry com.android.commands.am.Am
--------- beginning of system
V/AlarmManager(  917): ELAPSED_WAKEUP set : Alarm{3dbcb125 type 2 when 60244 com.google.android.talk} when 60244
I/ActivityManager(  917): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/AlarmManager(  917): RTC_WAKEUP set : Alarm{c3b00ab type 0 when 1453044797212 com.android.vending} when 1453044797212
D/Finsky  ( 6023): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/ActivityManager(  917): setTaskToReturnTo : TaskRecord{18ac3aa1 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  917): setTaskToReturnTo : TaskRecord{18ac3aa1 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  917): AppWindowTokenEx init.. 
D/ContextHelper(  917): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  917): Focus left window: Window{210f5178 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6110): Shutting down VM
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  917): check instance of lgWin Window{b28f57f u0 Starting com.test.thalitest}
I/NotificationManager(  917): android: cancelAsUser(2) by android
I/ActivityManager(  917): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6139 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1940): Closing mic
,I/MicrophoneInputStream( 1940): mic_close com.google.android.apps.gsa.speech.audio.u@3e1e892
I/WindowStateAnimator(  917): Starting window displayed
V/AudioRecord( 1940): stop()
D/AudioRecord( 1940): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
I/SystemUI[Framework](  917): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 17
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3865000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
W/PhoneWindowManagerEx(  917): Call!!!getLGSystemUiVisibility. =0x0
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
D/StatusBarManagerServiceEx(  917): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  917): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  917): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@162af5f9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  917): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1376): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1376):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1376): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1376): draw background and invalidate : color = 16000000
D/BarTransitions( 1376): draw background and invalidate : color = 16161616
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
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
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3865000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 17
V/AudioPolicyManager(  283): closeInput(17)
V/AudioFlinger(  283): closeInput() 17
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1376): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1940): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 2660): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread 0xb3865000 exiting
V/AudioSystem( 3217): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1990): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  917): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): releasing 16 from 1940 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioFlinger(  283): removeClient_l() pid 1940, calling pid 283
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1940): Stopping hotword detection.
I/HotwordRecognitionRnr( 1940): Hotword detection finished
D/libc-netbsd( 6023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6023): propertyValue:false
D/libc-netbsd( 6023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ContextHelper( 6139): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6139): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/libc-netbsd( 6023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/GAV2    ( 5887): Thread[GAThread,5,main]: No campaign data found.
I/LibraryLoader( 6139): Time to load native libraries: 11 ms (timestamps 4978-4989)
I/LibraryLoader( 6139): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6139): Binding Chromium to main looper Looper (main, tid 1) {1b24c3e5}
I/LibraryLoader( 6139): Expected native library version number "",actual native library version number ""
I/chromium( 6139): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6139): Initializing chromium process, singleProcess=true
W/art     ( 6139): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6139): ApplicationContext is null in ApplicationStatus
W/chromium( 6139): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6139): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6139): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6139): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6139): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6139): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6139): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6139): Remote Branch: 
I/Adreno-EGL( 6139): Local Patches: 
I/Adreno-EGL( 6139): Reconstruct Branch: 
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  917): android: cancelAsUser(2) by android
,V/AudioPolicyService(  283): registerClient() client 0xb551c6e0, uid 10316
,D/BluetoothManagerService(  917): Message: 20
D/BluetoothManagerService(  917): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dda2603:true
,D/BluetoothAdapterService(509786465)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@395d4a3f
I/qtaguid ( 6023): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6023): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6023): untagSocket(41) failed with errno -22
,D/Finsky  ( 6023): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
W/art     ( 6139): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6139): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager(  917): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6192 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 95435552155; DSPS: 3225135; Offset : -2996679357
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SystemWebViewEngine( 6139): CordovaWebView is running on device made by: LGE
,I/NotificationManager(  917): android: cancelAsUser(2) by android
W/art     ( 6139): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6139): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 6192): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6192): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Activity( 6139): Activity.onPostResume() called 
,D/OpenGLRenderer( 6139): Render dirty regions requested: true
I/OpenGLRenderer( 6139): Initialized EGL, version 1.4
D/OpenGLRenderer( 6139): Enabling debug mode 0
,D/Atlas   ( 6139): Validating map...
,D/SplitWindow(  917): check instance of lgWin Window{32235874 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6139): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/MultiDex( 6192): VM with version 2.1.0 has multidex support
I/MultiDex( 6192): install
I/MultiDex( 6192): VM has multidex support, MultiDex support library is disabled.
,D/InputDispatcher(  917): Focus entered window: Window{32235874 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,V/JNIHelp ( 6192): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/AlertService( 5942): Beginning updateAlertNotification
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/AlertService( 5942): No fired or scheduled alerts
I/NotificationManager( 5942): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 5942): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(18) by com.android.calendar
,I/NotificationManager( 5942): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5942): com.android.calendar: cancel(20) by com.android.calendar
W/InputMethodManagerService(  917): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  917): Displayed com.test.thalitest/.MainActivity: +1s308ms
I/Timeline(  917): Timeline: Activity_windows_visible id: ActivityRecord{34b834c6 u0 com.test.thalitest/.MainActivity t222} time:95722
,I/Timeline( 6139): Timeline: Activity_idle id: android.os.BinderProxy@3c65fff8 time:95742
,I/qtaguid ( 6023): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6023): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6023): untagSocket(41) failed with errno -22
D/AlertService( 5942): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5942): No events found starting within 1 week.
,W/ActivityThread( 6192): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6192): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@224cd41f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6192): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6192): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6192): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4214): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/BindingManager( 6139): Cannot call determinedVisibility() - never saw a connection for the pid: 6139
,D/ChimeraCfgMgr( 6192): Reading stored module config
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,D/ChimeraCfgMgr( 6192): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 6192): Connecting to CarCallService...
,D/NativeLibraryUtils( 6192): Install completed successfully. count=14 extracted=0
,I/art     ( 6192): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6192): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6023): CheckpointMarkThreadRoots callback created = 0xb057d270
,D/CAR.SERVICE( 6192): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6192): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6192): Creating a new PhoneAdapter instance
I/art     ( 6023): CheckpointMarkThreadRoots callback created = 0xb057d230
W/ActivityManager(  917): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6192): setListener: com.google.android.gms.car.dn@2385557a
W/ActivityManager(  917): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6192): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6192): Starting CarCallService with initial phone null
I/art     ( 6023): WaitForGcToComplete blocked for 36.067ms for cause HomogeneousSpaceCompact
,I/NotificationManager( 6192): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6192): Package validated; name: com.android.vending
,I/ActivityManager(  917): Process com.android.contacts (pid 5814) has died
,I/NotificationManager( 6023): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6023): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/JsMessageQueue( 6139): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6139): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622768128
,D/JX-Cordova( 6139): jxcore cordova android initializing
I/art     ( 6139): CheckpointMarkThreadRoots callback created = 0x9f683400
,I/art     ( 6139): CheckpointMarkThreadRoots callback created = 0x9f6833d0
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  917): android: cancelAsUser(2) by android
,I/qtaguid ( 6023): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6023): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6023): untagSocket(41) failed with errno -22
,I/art     (  917): Explicit concurrent mark sweep GC freed 27909(1301KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.548ms total 188.391ms
,W/ResourcesManager( 6023): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6023): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6023): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6023): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  917): RTC_WAKEUP set : Alarm{33fab66c type 0 when 1453044800702 com.android.vending} when 1453044800702
,I/ActivityManager(  917): Process com.android.calendar (pid 5942) has died
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 6023): [755] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  917): android: cancelAsUser(2) by android
,D/Finsky  ( 6023): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6023): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/libc-netbsd( 6023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
,D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 6023): propertyValue:false
I/ActivityManager(  917): Process com.lge.lockscreensettings (pid 5833) has died
,I/art     ( 6139): Background partial concurrent mark sweep GC freed 13630(948KB) AllocSpace objects, 3(3MB) LOS objects, 39% free, 16MB/26MB, paused 6.523ms total 40.155ms
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,W/jxcore-log( 6139): Initializing JXcore engine
,W/jxcore-log( 6139): JXcore engine is ready
W/jxcore-log( 6139): Starting JXcore engine
,I/ActivityManager(  917): Process com.google.android.apps.plus (pid 5547) has died
W/.test.thalitest( 6139): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6401]" dev="sockfs" ino=6401 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6139): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6139): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7491]" dev="sockfs" ino=7491 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6139): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/.test.thalitest( 6139): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6139): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28909]" dev="sockfs" ino=28909 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ActivityManager(  917): Process com.android.providers.calendar (pid 6071) has died
,W/jxcore-log( 6139): Platform android
W/jxcore-log( 6139): 
,W/jxcore-log( 6139): Process ARCH arm
W/jxcore-log( 6139): 
V/AlarmManager(  917): RTC_WAKEUP set : Alarm{8d1bf22 type 0 when 1453044802725 com.google.android.googlequicksearchbox} when 1453044802725
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/jxcore-log( 6139): JXcore Cordova bridge is ready!
I/jxcore-log( 6139): 
,W/jxcore-log( 6139): JXcore engine is started
I/chromium( 6139): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6139): Toggling radios to true
I/jxcore-log( 6139): 
,D/BluetoothAdapter( 6139): enable(): BT is already enabled..!
D/WifiServiceImplEx(  917): setWifiEnabled: true pid=6139, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  917): setWifiEnabled: true pid=6139, uid=10316
D/WifiServiceImplEx(  917): disconnect pid=6139, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  917): reconnect pid=6139, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6139): Radios toggled
I/jxcore-log( 6139): 
I/jxcore-log( 6139): My device name is: LGE-LG-D722
I/jxcore-log( 6139): 
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2739): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2739): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,E/WifiStateMachine(  917): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  917): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1795): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/LGWifiP2pService(  917): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  917): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  917): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1732): Read error: ssl=0xb0465600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb0465600: I/O error during system call, Broken pipe
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/WifiHS20(  917): hidePasspointNotification off =false
,D/ConnectivityService(  917): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:23.835 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  917): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/ConnectivityService(  917): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): DefaultState{ when=-35ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): Forcing reevaluation
,D/WifiServiceExtension( 1795): isInternetCheckAvailable return false
I/ActivityManager(  917): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6298 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  917): Start Disconnecting Watchdog 1
D/WifiHS20(  917): hidePasspointNotification off =false
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  917): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  917): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2739): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:23.956 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/ConnectivityService(  917): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  917): disableDataServiceNotify
D/DSQN    (  917): stop dsqn bin
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:23.969 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  917): hidePasspointNotification off =false
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1795): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/WifiNetworkAgent(  917): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  917): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  917): hidePasspointNotification off =false
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:24.001 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/DhcpStateMachine(  917): StoppedState
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/DhcpStateMachine(  917): StoppedState{ when=-69ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  917): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524292
D/Nat464Xlat(  917): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:24.006 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
,D/CSLegacyTypeTracker(  917): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  917): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  917): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1837): |CORE| No family connected
V/NetworkPolicy(  917): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  917): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  917): MasterInitialState.processMessage what=3
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiServerServiceExt(  917): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  917): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/ConnectivityService(  917): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  917): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  917): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/NetworkPolicy(  917): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    (  917): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt(  917): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  917): setSupplicantStateSCANNING
D/WIFI    (  917):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = -1
D/NetworkManagementService(  917): Removing idletimer
,D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  917): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  917): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6298): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6298): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6298): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6298): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6298): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6298): Using schema version: 115
,I/IndexDatabaseHelper( 6298): Index is fine
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
I/art     (  308): Background concurrent mark sweep GC freed 813(34KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 5.850ms total 26.133ms
,I/ActivityManager(  917): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6321 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6321): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6321): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6321): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
I/PCSuite ( 6321): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/CAR.SERVICE( 6192): mConnectedToCar = false, abort
D/PCSuite ( 6321): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6321): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ActivityThread( 6192): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@19e76422 that was originally bound here
E/ActivityThread( 6192): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@19e76422 that was originally bound here
E/ActivityThread( 6192): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6192): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6192): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6192): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6192): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6192): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6192): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6192): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6192): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6192): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6192): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6192): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6192): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6192): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6192): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6192): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6192): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6192): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6192): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6192): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6192): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6192): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
E/ActivityThread( 6192): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16b35da5 that was originally bound here
E/ActivityThread( 6192): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16b35da5 that was originally bound here
E/ActivityThread( 6192): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6192): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6192): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6192): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6192): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6192): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6192): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6192): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6192): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6192): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6192): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6192): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6192): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E,/ActivityThread( 6192): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6192): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6192): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6192): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6192): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6192): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6192): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6192): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  917): Unbind failed: could not find connection for android.os.BinderProxy@1fd6edb3
I/PCSuite ( 6321): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6321): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6321): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
I/PCSuite ( 6321): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6321): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6321): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
I/wpa_supplicant( 2739): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,D/LocSvc_java(  917): onReceive
,I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.11 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/wpa_supplicant( 2739): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.125 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/WifiServerServiceExt(  917): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  917): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  917): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  917): setSupplicantStateASSOCIATED
,W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.151 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.155 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2739): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2739): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  917): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  917): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/WifiServiceExtension(  917): setVHTCapabilityType  : false
D/WiFiOffLoadBroadcast( 6298): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
I/WifiServerServiceExt(  917): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  917): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  917): setSecurityType  : 2
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService(  917): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.222 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  917): Got NetworkAgent Messenger
D/ConnectivityService(  917): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  917): NetworkAgent connected
D/WifiServiceExtension( 1795): isInternetCheckAvailable return false
E/WifiConfigStore(  917): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.224 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
E/WifiConfigStore(  917): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  917): Start Dhcp Watchdog 2
D/DhcpStateMachine(  917): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  917): WaitBeforeStartState
D/WifiServerServiceExt(  917): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  917): setSupplicantStateGROUP_HANDSHAKE
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  917): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  917): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  917): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
E/WifiStateMachine(  917): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  917): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  917): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e1d7f01 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  917): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e1d7f01 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  917): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  917): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  917): DHCP Start wake lock is acquired.
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  917): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  917): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  917): setSupplicantStateCOMPLETED
D/ConnectivityService(  917): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  917): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  917): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  917): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  917): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  917): ignoring duplicate network state non-change
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1795): isInternetCheckAvailable return false
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.371 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  917): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  917): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1795): isInternetCheckAvailable return false
E/WifiStateMachine(  917): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.389 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  917): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.392 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/WifiHS20(  917): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1837): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:25.396 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1837): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/ConnectivityService(  917): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  917): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  917): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
D/ConnectivityService(  917): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  917): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  917): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  917): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  917): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  917): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  917): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  917): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  917):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  917):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  917):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): Connected
D/ConnectivityService(  917):   checkin,g if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  917):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  917): currentScore = 0, newScore = 20
D/ConnectivityService(  917):    accepting network in place of null
D/ConnectivityService(  917): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  917): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  917):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  917): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  917): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  917): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  917): [e] list.add(nai) empty : false size: 1
D/Tethering(  917): MasterInitialState.processMessage what=3
D/ConnectivityService(  917): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = true, mWifiLevel = 2
W/QCNEJ   ( 1837): |CORE| No family connected
I/QCNEJ   ( 1837): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1837): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  917): validation of new default Network = false
D/ConnectivityService(  917): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  917): enableDataServiceNotify 
D/DSQN    (  917): start dsqn bin
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): [LWD] wait 500ms before dns check
V/NetworkPolicy(  917): [LG_RESTRICTED] checkMobilePolicy_type()
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  917): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  917): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/DSQN    ( 6370): DSQN samuel.seo ver 141203
E/DSQN    ( 6370): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6370): created command queue thread
I/DSQN    ( 6370): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6370): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
I/PCSuite ( 6321): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6321): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6298): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6298): MCCMNC not supported: null
I/PCSuite ( 6321): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6321): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DhcpStateMachine(  917): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  917): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  917): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6373): version 5.5.6 starting
E/dhcpcd  ( 6373): get_duid: Read-only file system
,I/dhcpcd  ( 6373): wlan0: rebinding lease of 192.168.1.134
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): [LWD] DNSResolver start dns
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  917): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6370): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6370): restart monitoring
,I/DSQN    ( 6370): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  917): DSQM DsqnNotification wlan0  1
D/DSQN    (  917): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:33:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453044806043], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453044806027]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1795): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  917): Validated
D/ConnectivityService(  917): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  917): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  917):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  917):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  917):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  917): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  917): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  917): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  917): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  917): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  917):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiDataContinuityService(  917): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  917): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  917): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  917): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  917): identical MTU - not setting
D/Nat464Xlat(  917): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  917): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  917):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:26.675 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  917): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524295
D/ConnectivityService(  917): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  917): enableDataServiceNotify 
D/DSQN    (  917): start dsqn bin
D/DSQN    (  917): dsqn is running restart
,I/DSQN    ( 6389): DSQN samuel.seo ver 141203
E/DSQN    ( 6389): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6389): created command queue thread
,I/DSQN    ( 6389): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6389): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/dhcpcd  ( 6373): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6373): wlan0: leased 192.168.1.134 for 86400 seconds
,D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  917): onReceive
D/LocSvc_java(  917): got connectivity action
D/LocSvc_java(  917): broadcast - no network connections
D/LocSvc_java(  917): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  917): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  917): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  917): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  917): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  917): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6410 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  917): onReceive
D/LocSvc_java(  917): got connectivity action
D/LocSvc_java(  917): broadcast - no network connections
D/LocSvc_java(  917): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  917): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  917): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  917): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  917): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  917): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  917): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  917): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  917): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  917): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  917): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  917): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  917): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  917): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  917): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  917): RunningState
D/GpsLocationProvider(  917): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  917): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  917): Process com.google.android.gms:car (pid 6192) has died
,I/MusicStore( 6410): Database version: 120
,I/ActivityManager(  917): Process com.google.android.gm (pid 5887) has died
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6410): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6410): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6410): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/NotificationManager( 1940): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,W/ResourcesManager( 6410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6410): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6410): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6410): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e6415f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6410): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6410): GMSCore installation verified
,I/ConfigStore( 6410): Config Database version: 1
,I/MediaRouter( 6410): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6410): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6410): type=WIFI subType= reason=null isConnected=true
I/QCNEJ   ( 1837): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1837): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-17 16:33:28.276 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NetworkMonitor( 6410): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  917): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6469 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/WifiInternetCheck(  917): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/GHttpClientFactory( 6410): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ConnectivityService(  917): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  917): onReceive
D/LocSvc_java(  917): got connectivity action
D/LocSvc_java(  917): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  917): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  917): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  917): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  917): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  917): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  917): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/GoogleURLConnFactory( 6410): Using platform SSLCertificateSocketFactory
I/NetworkMonitor( 6410): type=WIFI subType= reason=null isConnected=true
,I/NotificationManager( 6410): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6469): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6469): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/jxcore-log( 6139): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6139): 
,I/LGEmail ( 6469): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6469): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  917): Process com.google.android.talk (pid 5729) has died
,D/eas_req ( 6469): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  917): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6500 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6469): JNI_OnLoad()
I/HubEmail( 6469): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6469): registerNatives()
I/HubEmail( 6469): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6469): registerNativeMethods()
I/HubEmail( 6469): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6469): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6469): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6500): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6500): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6500): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6500): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6500): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6500): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/SQLiteConnectionPool( 4214): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/LGDMClient( 6500): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6500): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  917): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6534 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 22.374ms
,I/jxcore-log( 6139): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6139): 
,I/jxcore-log( 6139): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6139): 
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.384ms
W/ContextImpl( 6500): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 23.902ms
E/LGDMClient( 6500): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6500): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6500): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6500): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6500): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/jxcore-log( 6139): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6139): 
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/jxcore-log( 6139): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6139): 
,I/jxcore-log( 6139): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6139): 
I/AppUp4:AppBoxCP( 6534): onCreate
,W/AppUp4:DB( 6534):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6534):  setFingerPrint start
I/AppUp4:DB( 6534):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6534):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6534):  SDK version = 0
I/AppUp4:DB( 6534):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6534): AppBoxApplication onCreate()
I/jxcore-log( 6139): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6139): 
I/NetworkStateForAutoUpdateMonitor( 6534): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6534): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6534): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6534): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6534): onReceive
I/AppUp4:CustModeStarterReceiver( 6534): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6534): Context : android.app.ReceiverRestrictedContext@2a755eba
,D/AppUp4:CustFacade( 6534): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6534): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6534): begin check event
I/AppUp4:CustModeStarterReceiver( 6534): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6534): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6534): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6534): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6534): handleAsyncCustNotification do not startCustService
I/ActivityManager(  917): Killing 6023:com.android.vending/u0a36 (adj 15): empty #11
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  917): failed to open /acct/uid_10036/pid_6023/cgroup.procs: No such file or directory
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  917): propertyValue:false
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  917): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  917): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  917): propertyValue:false
I/LgeMiscReceiver( 3217): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3217): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3217): networkInfo.isConnected() = false
I/DSQN    ( 6389): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6389): restart monitoring
,D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6389): dsqn report finish
D/DSQN    (  917): DSQM DsqnNotification wlan0  1
D/DSQN    (  917): start to monitor internet connection
V/WifiInternetCheck(  917): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  917): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6562 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6562): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6562): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6562): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  917): Killing 6298:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  917): failed to open /acct/uid_1000/pid_6298/cgroup.procs: No such file or directory
,I/CheckinService( 4214): Checkin interval check for package: unspecified last checkin: 1453044782361 min interval config: 0 actual interval: 27701
,V/DownloadManager( 3241): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3241): DownloadService onCreate
,D/PhoneMonitor( 6562): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6562): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  917): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6588 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/NotificationManager( 3241): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/TelephonyAutoProfiling( 6562): [parse] Load xml
I/DownloadManager( 3241): in removeSpuriousFiles
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/TelephonyAutoProfiling( 6562): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6562): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/jxcore-log( 6139): Test app app.js loaded
I/jxcore-log( 6139): 
,V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@27e6cbbe on behalf of 3241
,D/PhoneMonitor( 6562): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/DownloadManager( 3241): in trimDatabase
,V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3241): DownloadService onStartCommand
V/DownloadManager( 3241): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@1697bd35 on behalf of 3241
I/CheckinService( 4214): Checking schedule, now: 1453044810210 next: 1453044812303
I/CheckinService( 4214): active receiver: disabled
I/chromium( 6139): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@263fe5ca on behalf of 3241
,I/ActivityManager(  917): Killing 5706:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5095): android.os.DeadObjectException
,W/System.err( 5095): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5095): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5095): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5095): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5095): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5095): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5095): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5095): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5095): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5095): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5095): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5095): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5095): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5095): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5095): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5095): android.os.DeadObjectException
W/System.err( 5095): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5095): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5095): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5095): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5095): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5095): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5095): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 5095): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5095): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5095): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5095): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5095): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5095): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5095): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5095): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/lowmemorykiller(  245): Error opening /proc/5706/oom_score_adj; errno=2
,D/WeatherAncestor( 2643): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:33:30
,W/ActivityManager(  917): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  917): android.os.DeadObjectException
W/ActivityManager(  917): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  917): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  917): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  917): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  917): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  917): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  917): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  917): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  917): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  917): 	at android.os.Binder.execTransact(Binder.java:446)
W/ActivityManager(  917): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  917): android.os.DeadObjectException
W/ActivityManager(  917): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  917): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  917): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  917): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  917): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  917): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  917): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  917): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  917): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  917): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  917): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  917): 	at android.os.Binder.execTransact(Binder.java:446)
,W/libprocessgroup(  917): failed to open /acct/uid_10089/pid_5706/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2643): 2 : This is isUpdating : false
V/DownloadManager( 3241): DownloadService onDestroy
D/WeatherAncestor( 2643): connectivity changed - connection : true
D/Weather_cast( 2643): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2643): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:33:30
D/WeatherService( 2643): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  917): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6619 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  917): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6639 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  917): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2643): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2643): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2643): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6619): Quickset Services start...
,I/UEI.SmartControl( 6619): Manufacture = LGE
D/UEI.SmartControl( 6619): File observer start...
E/UEI.SmartControl( 6619): IR Port is disabled: false
D/UEI.SmartControl( 6619): Starting file observer...
D/UEI.SmartControl( 6619): Extracting JNI libs...
D/UEI.SmartControl( 6619): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6639): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6619): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6619): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6619): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6619): --- Selecting new region: 2
,I/UEI.SmartControl( 6619): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6619): Platform has CIR...
,D/UEI.SmartControl( 6619): NO CIR support, need to check package...
I/UEI.SmartControl( 6619): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6619): QS Service created
E/UEI.SmartControl( 6619): QS start get config
,I/ActivityManager(  917): Process com.google.android.music:main (pid 6410) has died
,D/UEI.SmartControl( 6619): Loading JNI Libs...
,D/UEI.SmartControl( 6619):  configuring local db...
I/Babel_SMS( 6639): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6639): MmsConfig.loadMmsSettings
I/Babel_SMS( 6639): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6639): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6639): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6639): MmsConfig.loadFromResources
E/Babel_SMS( 6639): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6639): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6639): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6639): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6639): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6639): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6639): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6639): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6639): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6639): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6639): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6639): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6639): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6639): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6639): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6639): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6639): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6639): found sensor: Motion Accel, handle=46
,W/Settings( 6639): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6639): startup - clean
I/art     ( 6639): CheckpointMarkThreadRoots callback created = 0xaaf487b0
,I/Babel   ( 6639): deleted: false for 0
,I/art     ( 6639): CheckpointMarkThreadRoots callback created = 0xaaf48790
D/UEI.SmartControl( 6619):  ---- Has DB8: true
,D/UEI.SmartControl( 6619): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6619): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6619): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6619): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6619): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6619): IrrcClient ++ 
D/irrcClient( 6619): getIrrcService ++ 
,D/irrcClient( 6619): getIrrcService -- 
D/irrcClient( 6619): IrrcClient -- 
W/irrc_jni( 6619): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6619): Services init done
,I/UEI.SmartControl( 6619): Device manager: loading config....
D/UEI.SmartControl( 6619): Config is loaded...
I/ActivityManager(  917): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6683 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6619): QS Service init finished
D/UEI.SmartControl( 6619):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6619): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6619): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6619): QS Service version code: 1073
D/UEI.SmartControl( 6619): Service requested: Control
D/UEI.SmartControl( 6619): -----IControl: 11
D/UEI.SmartControl( 6619): Internal service binding...
D/UEI.SmartControl( 6619): Caller: com.lge.qremote
D/UEI.SmartControl( 6619): ------------ IControl registerCallback...
I/UEI.SmartControl( 6619): Registering callback...
D/UEI.SmartControl( 6619): -----IControl: 19
,D/UEI.SmartControl( 6619): Caller: com.lge.qremote
I/UEI.SmartControl( 6619): Registering Services Ready callback...
I/UEI.SmartControl( 6619): Notify client services are ready...
W/AudioCapabilities( 6639): Unsupported mime audio/x-lg-flac
D/UEI.SmartControl( 6619): -----IControl: 8
D/UEI.SmartControl( 6619): Caller: com.lge.qremote
W/AudioCapabilities( 6639): Unsupported mime audio/adpcm
W/AudioCapabilities( 6639): Unsupported mime audio/g726
W/AudioCapabilities( 6639): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6639): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6639): Unsupported mime video/mjpg
W/VideoCapabilities( 6639): Unsupported mime video/theora
,W/AudioCapabilities( 6639): Unsupported mime audio/evrc
,W/AudioCapabilities( 6639): Unsupported mime audio/qcelp
W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6639): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6639): Unsupported mime audio/qcelp
W/AudioCapabilities( 6639): Unsupported mime audio/evrc
W/VideoCapabilities( 6639): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6639): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6639): onServiceConnected
,W/Babel   ( 6639): Attempted to change video mute state without an active call.
I/NotificationManager( 6639): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6639): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6639): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6639): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6639): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6639): propertyValue:false
I/Babel   ( 6639): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  917): Killing 6321:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  917): failed to open /acct/uid_1000/pid_6321/cgroup.procs: No such file or directory
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6683): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6683):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6683):   adb logcat -s GAv4
,I/art     (  917): Explicit concurrent mark sweep GC freed 82227(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.451ms total 205.715ms
,W/GAv4    ( 6683): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6683): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6683): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6683): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6683): Time to load native libraries: 2 ms (timestamps 9105-9107)
,I/LibraryLoader( 6683): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6683): Binding Chromium to main looper Looper (main, tid 1) {3d59030f}
I/LibraryLoader( 6683): Expected native library version number "",actual native library version number ""
I/chromium( 6683): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6683): Initializing chromium process, singleProcess=true
,W/art     ( 6683): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6683): ApplicationContext is null in ApplicationStatus
W/chromium( 6683): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6683): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6683): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6683): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6683): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6683): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6683): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6683): Remote Branch: 
I/Adreno-EGL( 6683): Local Patches: 
I/Adreno-EGL( 6683): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb551c7a0, uid 10079
,W/AudioManagerAndroid( 6683): Requires BLUETOOTH permission
I/NSApplication( 6683): Starting up...
I/ActivityManager(  917): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6751 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  917): Killing 5095:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  917): failed to open /acct/uid_10106/pid_5095/cgroup.procs: No such file or directory
,I/ActivityManager(  917): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6770 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  917): Killing 6469:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  917): failed to open /acct/uid_10021/pid_6469/cgroup.procs: No such file or directory
,W/ResourcesManager( 6770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  917): Killing 6500:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  917): failed to open /acct/uid_1000/pid_6500/cgroup.procs: No such file or directory
,I/ActivityManager(  917): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6794 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6794): Database version: 120
,V/AlarmManager(  917): RTC_WAKEUP set : Alarm{1790d8e4 type 0 when 1453044812303 com.google.android.gms} when 1453044812303
,V/AlarmManager(  917): RTC_WAKEUP set : Alarm{29063402 type 0 when 1453044813437 com.google.android.googlequicksearchbox} when 1453044813437
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6794): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/AlarmManager(  917): ELAPSED_WAKEUP set : Alarm{1f2415a type 2 when 110491 com.google.android.gms} when 110491
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6794): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6794): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6794): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6794): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6794): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6794): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6794): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e6415f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6794): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6794): GMSCore installation verified
I/ConfigStore( 6794): Config Database version: 1
,I/MediaRouter( 6794): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6794): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6794): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6794): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  917): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6826 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6794): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6794): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  917): Killing 6534:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6826): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6826): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6826): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  917): failed to open /acct/uid_10011/pid_6534/cgroup.procs: No such file or directory
,I/NotificationManager( 6794): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 6826): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6826): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/eas_req ( 6826): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  917): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6854 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6826): JNI_OnLoad()
I/HubEmail( 6826): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6826): registerNatives()
I/HubEmail( 6826): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6826): registerNativeMethods()
I/HubEmail( 6826): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6826): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  917): Killing 6562:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  917): failed to open /acct/uid_10038/pid_6562/cgroup.procs: No such file or directory
,W/Settings( 6826): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6854): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6854): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6854): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6854): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6854): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6854): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  917): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6878 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.585ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 23.182ms
,E/LGDMClient( 6854): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6854): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6854): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6854): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.967ms
D/LGDMClient( 6854): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  917): Killing 6588:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 6878): onCreate
,W/AppUp4:DB( 6878):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6878):  setFingerPrint start
I/AppUp4:DB( 6878):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6878):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6878):  SDK version = 0
I/AppUp4:DB( 6878):  beforefinger == newfinger no write in DB
W/libprocessgroup(  917): failed to open /acct/uid_10051/pid_6588/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6878): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6878): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6878): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6878): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6878): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6878): onReceive
I/AppUp4:CustModeStarterReceiver( 6878): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6878): Context : android.app.ReceiverRestrictedContext@2a755eba
D/AppUp4:CustFacade( 6878): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6878): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6878): begin check event
,I/AppUp4:CustModeStarterReceiver( 6878): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6878): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6878): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6878): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6878): handleAsyncCustNotification do not startCustService
I/ActivityManager(  917): Killing 6619:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  917): failed to open /acct/uid_10089/pid_6619/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3217): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3217): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3217): networkInfo.isConnected() = false
,I/ActivityManager(  917): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6898 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6898): Register our PhoneStateListener
,I/ActivityManager(  917): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6918 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  917): RTC_WAKEUP set : Alarm{3154e93c type 0 when 1453044815004 com.android.vending} when 1453044815004
D/MobileConnectivityChangeReceiver( 6898): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6898): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  917): Killing 6639:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6898): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6898): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6898): [parse] Load xml
,V/TelephonyAutoProfiling( 6898): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6898): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6898): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3241): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  917): failed to open /acct/uid_10061/pid_6639/cgroup.procs: No such file or directory
I/CheckinService( 4214): Checkin interval check for package: unspecified last checkin: 1453044782361 min interval config: 0 actual interval: 32791
,V/DownloadManager( 3241): DownloadService onCreate
I/DownloadManager( 3241): in removeSpuriousFiles
I/NotificationManager( 3241): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@1293f7b1 on behalf of 3241
I/DownloadManager( 3241): in trimDatabase
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@25e9496 on behalf of 3241
I/ActivityManager(  917): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6941 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3241): DownloadService onStartCommand
V/DownloadManager( 3241): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@24f54404 on behalf of 3241
I/CheckinService( 4214): Checking schedule, now: 1453044815222 next: 1453044812303
I/CheckinService( 4214): active receiver: enabled
,I/CheckinService( 4214): Preparing to send checkin request
I/EventLogService( 4214): Accumulating logs since 1453044774753
V/DownloadManager( 3241): DownloadService onDestroy
,D/WeatherAncestor( 2643): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:33:35
,D/UpdateThreadPoolManager( 2643): 2 : This is isUpdating : false
D/WeatherAncestor( 2643): connectivity changed - connection : true
D/Weather_cast( 2643): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2643): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:33:35
D/WeatherService( 2643): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4214): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  917): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6973 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  917): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2643): 2 : Utils getTopActivity com.lge.launcher2 / true
E/ActivityThread( 4214): Failed to find provider info for com.google.android.wearable.settings
D/WeatherService( 2643): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2643): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/Finsky  ( 6918): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6973): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  917): Explicit concurrent mark sweep GC freed 21212(1139KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.210ms total 153.259ms
,D/Finsky  ( 6918): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6918): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6918): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6918): com.android.vending: cancel(-1050172287) by com.android.vending
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@19e76422 on behalf of 6918
D/Finsky  ( 6918): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6918): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6918): Skipping gmscore version check
,D/Finsky  ( 6918): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6918): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Babel_SMS( 6973): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6973): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6973): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6973): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6973): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6973): MmsConfig.loadFromResources
E/Babel_SMS( 6973): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6973): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/ActivityManager(  917): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7020 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/SensorManager( 6973): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6973): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6973): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6973): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6973): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6973): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6973): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6973): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6973): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6973): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6973): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6973): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6973): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6973): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6973): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6973): found sensor: Motion Accel, handle=46
,W/ResourcesManager( 7020): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7020): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Settings( 6973): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6973): startup - clean
I/art     ( 6973): CheckpointMarkThreadRoots callback created = 0xb042d800
,I/art     ( 6973): CheckpointMarkThreadRoots callback created = 0xb042d7e0
,D/Finsky  ( 6918): [855] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,W/art     ( 7020): Verification of void com.google.android.gms.common.app.GmsApplication.<init>() took 107.598ms
D/Finsky  ( 6918): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/Babel   ( 6973): deleted: false for 0
I/MultiDex( 7020): VM with version 2.1.0 has multidex support
I/MultiDex( 7020): install
I/MultiDex( 7020): VM has multidex support, MultiDex support library is disabled.
,W/AudioCapabilities( 6973): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6973): Unsupported mime audio/adpcm
W/AudioCapabilities( 6973): Unsupported mime audio/g726
W/AudioCapabilities( 6973): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6973): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6973): Unsupported mime video/mjpg
V/MusicLeanback( 6794): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
V/JNIHelp ( 7020): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/VideoCapabilities( 6973): Unsupported mime video/theora
D/LGDMClient( 6854): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6854): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6878): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6878): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6878): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6878): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6878): onReceive
I/AppUp4:CustModeStarterReceiver( 6878): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6878): Context : android.app.ReceiverRestrictedContext@2a755eba
D/AppUp4:CustFacade( 6878): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6878): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6878): begin check event
I/AppUp4:CustModeStarterReceiver( 6878): Event For GoodConnectivity, noConnectivity : false, but skip! 
W/Settings( 6826): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3217): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3217): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3217): networkInfo.isConnected() = true
D/PhoneState( 3217): setPdpRejectCasuse : false
D/LGDMClient( 6854): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/LGDMClient( 6854): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6854): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/MobileConnectivityChangeReceiver( 6898): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6898): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3241): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 6854): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3241): DownloadService onCreate
D/WeatherAncestor( 2643): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:33:36
I/NotificationManager( 3241): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/UpdateThreadPoolManager( 2643): 2 : This is isUpdating : false
I/DownloadManager( 3241): in removeSpuriousFiles
,D/WeatherAncestor( 2643): connectivity changed - connection : true
D/Weather_cast( 2643): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2643): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:33:36
D/WeatherService( 2643): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ActivityManager(  917): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2643): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@1c542eb3 on behalf of 3241
D/WeatherService( 2643): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2643): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/ContextImpl( 6854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6854): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6854): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6854): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6854): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/DownloadManager( 3241): in trimDatabase
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 6854): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@7849c70 on behalf of 3241
,V/DownloadManager( 3241): DownloadService onStartCommand
,V/DownloadManager( 3241): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@3d59030f on behalf of 3241
W/ActivityThread( 7020): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7020): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@224cd41f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7020): Installed default security provider GmsCore_OpenSSL
W/AudioCapabilities( 6973): Unsupported mime audio/evrc
W/AudioCapabilities( 6973): Unsupported mime audio/qcelp
W/VideoCapabilities( 6973): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6973): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6973): Unsupported mime audio/qcelp
,I/NotificationManager( 7020): com.google.android.gms: cancel(10436) by com.google.android.gms
W/AudioCapabilities( 6973): Unsupported mime audio/evrc
I/NotificationManager( 7020): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,V/DownloadManager( 3241): DownloadService onDestroy
,W/VideoCapabilities( 6973): Unsupported mime video/mp4v-esdp
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/VideoCapabilities( 6973): Unsupported profile 4 for video/mp4v-es
I/art     ( 7020): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7020): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/VideoCapabilities( 6973): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6973): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6973): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6973): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6973): onServiceConnected
,W/Babel   ( 6973): Attempted to change video mute state without an active call.
I/art     ( 6770): CheckpointMarkThreadRoots callback created = 0xb042ddd0
I/ActivityManager(  917): Killing 6918:com.android.vending/u0a36 (adj 15): empty #11
,I/NotificationManager( 6973): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6973): propertyValue:false
I/art     ( 6770): CheckpointMarkThreadRoots callback created = 0xb042dda0
,I/Babel   ( 6973): connection state changed from UNKNOWN to CONNECTED
,D/NativeLibraryUtils( 7020): Install completed successfully. count=14 extracted=0
W/libprocessgroup(  917): failed to open /acct/uid_10036/pid_6918/cgroup.procs: No such file or directory
,D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  283): L1 library not specified. Falling Back to L3
I/ActivityManager(  917): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7053 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  917): Killing 6794:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  283): PrepareKeyRequest: nonce=2116571939
W/libprocessgroup(  917): failed to open /acct/uid_10081/pid_6794/cgroup.procs: No such file or directory
,W/ResourcesManager( 7053): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  917): Message: 20
D/BluetoothManagerService(  917): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31c760c9:true
,D/BluetoothAdapterService(509786465)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@395d4a3f
D/BluetoothAdapterService(509786465)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@395d4a3f
I/ActivityManager(  917): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7071 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7053): Create singleton instance
,D/UEI.SmartControl( 7071): Quickset Services start...
I/UEI.SmartControl( 7071): Manufacture = LGE
,D/UEI.SmartControl( 7071): File observer start...
E/UEI.SmartControl( 7071): IR Port is disabled: false
D/UEI.SmartControl( 7071): Starting file observer...
D/UEI.SmartControl( 7071): Extracting JNI libs...
D/UEI.SmartControl( 7071): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7053): getMode name:com.lge.qremote
,I/CheckinService( 4214): Checkin interval check for package: unspecified last checkin: 1453044782361 min interval config: 0 actual interval: 34882
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4214): Restart initialization of location
E/MDM     ( 1732): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/dex2oat ( 7089): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 7053): getMode name:com.lge.qremote
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ContextImpl( 3606): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/dex2oat ( 7089): dex2oat took 128.777ms (threads: 4)
I/art     ( 7020): CheckpointMarkThreadRoots callback created = 0xb04cbe50
,I/Adreno-EGL( 7020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7020): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7020): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7020): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7020): Remote Branch: 
I/Adreno-EGL( 7020): Local Patches: 
I/Adreno-EGL( 7020): Reconstruct Branch: 
I/art     ( 7020): CheckpointMarkThreadRoots callback created = 0xb04cbe40
,D/UEI.SmartControl( 7071): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7071): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7071): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7071): --- Selecting new region: 2
I/UEI.SmartControl( 7071): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7071): Platform has CIR...
,D/UEI.SmartControl( 7071): NO CIR support, need to check package...
I/UEI.SmartControl( 7071): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7071): QS Service created
,E/UEI.SmartControl( 7071): QS start get config
,I/Adreno-EGL( 7020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7020): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7020): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7020): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7020): Remote Branch: 
I/Adreno-EGL( 7020): Local Patches: 
I/Adreno-EGL( 7020): Reconstruct Branch: 
D/UEI.SmartControl( 7071): Loading JNI Libs...
,D/UEI.SmartControl( 7071):  configuring local db...
,D/UEI.SmartControl( 7071):  ---- Has DB8: true
,D/UEI.SmartControl( 7071): QS start statue = true Error code = 0
D/UEI.SmartControl( 7071): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7071): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7071): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7071): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7071): IrrcClient ++ 
D/irrcClient( 7071): getIrrcService ++ 
,D/irrcClient( 7071): getIrrcService -- 
D/irrcClient( 7071): IrrcClient -- 
W/irrc_jni( 7071): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7071): Services init done
I/UEI.SmartControl( 7071): Device manager: loading config....
D/UEI.SmartControl( 7071): QS Service init finished
D/UEI.SmartControl( 7071): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7071): QS Service version code: 1073
D/UEI.SmartControl( 7071): Config is loaded...
D/UEI.SmartControl( 7071): Service requested: Control
D/UEI.SmartControl( 7071): Internal service binding...
D/UEI.SmartControl( 7071): -----IControl: 11
D/UEI.SmartControl( 7071): Caller: com.lge.qremote
D/UEI.SmartControl( 7071): ------------ IControl registerCallback...
I/UEI.SmartControl( 7071): Registering callback...
D/UEI.SmartControl( 7071): -----IControl: 19
,D/UEI.SmartControl( 7071): Caller: com.lge.qremote
I/UEI.SmartControl( 7071): Registering Services Ready callback...
I/UEI.SmartControl( 7071): Notify client services are ready...
D/UEI.SmartControl( 7071): -----IControl: 8
D/UEI.SmartControl( 7071): Caller: com.lge.qremote
I/AudioManager( 7053): getMode name:com.lge.qremote
,I/ActivityManager(  917): Killing 6878:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/UEI.SmartControl( 7071):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7071): Notify AllClients services are ready: 0
,I/ActivityManager(  917): Killing 6826:com.lge.email/u0a21 (adj 15): empty #12
,I/Adreno-EGL( 7020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7020): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7020): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7020): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7020): Remote Branch: 
I/Adreno-EGL( 7020): Local Patches: 
I/Adreno-EGL( 7020): Reconstruct Branch: 
,W/libprocessgroup(  917): failed to open /acct/uid_10011/pid_6878/cgroup.procs: No such file or directory
,W/libprocessgroup(  917): failed to open /acct/uid_10021/pid_6826/cgroup.procs: No such file or directory
,I/AudioManager( 7053): getMode name:com.lge.qremote
I/AudioManager( 7053): getMode name:com.lge.qremote
,I/WVCdm   (  283): CdmEngine::OpenSession
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 115436206158; DSPS: 3880516; Offset : -2996665493
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=2315277587
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicWidget( 2601): mDelayedStopHandler : unbind
,I/MusicBrowser( 2660): [MediaPlaybackService.java:2912:onUnbind()] oooooo ,
,I/MusicBrowser( 2660): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2660): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2660): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2660): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2660): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2660): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2660): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  917):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3c65fff8com.lge.music.MediaPlaybackService$6@3d3bbcd1
D/MusicBrowser( 2660): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@68aac86
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2660): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2660): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2660): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2660): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2660): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2660): reset
V/MediaPlayer[Native]( 2660): setListener
V/MediaPlayer[Native]( 2660): disconnect
V/MediaPlayer[Native]( 2660): destructor
V/AudioFlinger(  283): releasing 19 from 2660 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
,V/MediaPlayer[Native]( 2660): disconnect
D/MusicBrowser( 2660): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2660): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2660): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2660): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2660): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2660): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2660): [SmartShareManagerClient] unregisterListener: 547177270
W/SmartShareClient( 2660): [SmartShareManagerClient] unregisterListener invalid listener: 547177270
I/SmartShareClient( 2660): [SmartShareManagerClient] terminate service: 2660/MediaPlaybackService/675882716
,E/HomeCloudIF( 2660): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2660): [SmartShareManagerClient] unbindService context:android.app.Application@3f344237
V/CloudHub( 2660): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2660): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2660): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2660): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2660): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  917): Killing 6941:com.lge.drmservice/u0a51 (adj 15): empty #11
I/CloudHub( 2660): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29988
,W/libprocessgroup(  917): failed to open /acct/uid_10051/pid_6941/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  917): ELAPSED_WAKEUP set : Alarm{1c8754f5 type 2 when 117672 com.google.android.gms} when 117672
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
I/CheckinRequestBuilder( 4214): Classify the device as Phone.
,D/libc-netbsd( 4214): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4214): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4214): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4214): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 4214): propertyValue:false
,D/libc-netbsd( 4214): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4214): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4214): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4214): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4214): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4214): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4214): Sending checkin request (9904 bytes)
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 4214): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4214): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5588): Explicit concurrent mark sweep GC freed 2053(91KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.093ms total 61.906ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4214): Classify the device as Phone.
,I/CheckinTask( 4214): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4214): Checking schedule, now: 1453044822040 next: 1453572071037
I/CheckinService( 4214): active receiver: disabled
,I/CheckinService( 4214): Checking schedule, now: 1453044822095 next: 1453572071037
I/CheckinService( 4214): active receiver: disabled
,D/CheckinService( 4214): Recording last checkin time for package unspecified as 1453044822104
V/SetupWizard( 6898): Connected to Gservices successfully
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  917): Killing 6683:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/ActivityManager(  917): Killing 6854:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  917): failed to open /acct/uid_10079/pid_6683/cgroup.procs: No such file or directory
,W/libprocessgroup(  917): failed to open /acct/uid_1000/pid_6854/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7071): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1376): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  917): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1376): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1376): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  917): Handling package changes for user 0
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 6973): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6973): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  917): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7166 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 6973): com.google.android.talk: cancel(8) by com.google.android.talk
V/JNIHelp ( 6973): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7166): onCreate
,W/AppUp4:DB( 7166):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7166):  setFingerPrint start
,I/AppUp4:DB( 7166):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7166):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7166):  SDK version = 0
I/AppUp4:DB( 7166):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7166): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7166): onReceive
I/AppUp4:CustModeStarterReceiver( 7166): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7166): Context : android.app.ReceiverRestrictedContext@24fbef4f
D/AppUp4:CustFacade( 7166): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7166): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7166): begin check event
I/AppUp4:CustModeStarterReceiver( 7166): Event For Nothing, skip.
,W/System  ( 6973): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6973): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  917): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7187 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  917): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  917): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  917): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  917): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  917): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  917): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@82598fa
W/ResourcesManager( 7187): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7187): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7187): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
W/ResourcesManager(  917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  917): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  917): Explicit concurrent mark sweep GC freed 27767(1358KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 11.770ms total 201.107ms
,I/AppConfig( 7187): Total System Memory = 906309632
,I/GalleryUtils( 7187): Application Heap = 96 MB
,I/AppConfig( 7187): App Tier : NOT_DEF
,D/LocationProviderProxy(  917): applying state to connected service
D/SystemHelper( 7187): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  917): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7210 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  917): Killing 6751:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  917): failed to open /acct/uid_10048/pid_6751/cgroup.procs: No such file or directory
,W/ResourcesManager( 7210): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7210): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7210): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7210): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7210): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/SystemConfig( 7210): BUILD Country: EU
,I/SystemConfig( 7210): BUILD Operator: OPEN
,I/ActivityManager(  917): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7232 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  917): Killing 6770:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 23.002ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 21.849ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.182ms
,W/libprocessgroup(  917): failed to open /acct/uid_10086/pid_6770/cgroup.procs: No such file or directory
,I/SystemConfig( 7210): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7210): existFile = false
I/SystemConfig( 7210): canReadFile = false
I/SystemConfig( 7210): systemFeature RCS result false
D/SystemConfig( 7210): refreshRcsSupport() :false
I/LockScreenSettings( 7232): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7232): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7232): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7232): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7232): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7232): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  917): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7253 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  917): Killing 2660:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  283): 2660 died, releasing its sessions
V/AudioFlinger(  283):  pid 1750 @ 0
V/AudioFlinger(  283):  pid 3217 @ 1
V/AudioFlinger(  283):  pid 3217 @ 2
,W/libprocessgroup(  917): failed to open /acct/uid_10028/pid_2660/cgroup.procs: No such file or directory
,W/ResourcesManager( 7253): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  917): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7282 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  917): Killing 6898:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 104 ms] updated apps [took 104 ms] 
,W/libprocessgroup(  917): failed to open /acct/uid_10038/pid_6898/cgroup.procs: No such file or directory
,D/Finsky  ( 7282): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7282): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7282): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7282): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7282): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@16b35da5 on behalf of 7282
D/Finsky  ( 7282): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7282): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7282): Skipping gmscore version check
D/Finsky  ( 7282): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4214): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 7282): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PackageBroadcastService( 4214): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4214): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 4214): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 4214): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  917): Killing 7020:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  917): failed to open /acct/uid_10006/pid_7020/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
,D/WifiController(  917): battery changed pluggedType: 2
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  917): Killing 7071:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7053): android.os.DeadObjectException
,W/System.err( 7053): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7053): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7053): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7053): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7053): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7053): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7053): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7053): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7053): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7053): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7053): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7053): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7053): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7053): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7053): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7053): android.os.DeadObjectException
W/System.err( 7053): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7053): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7053): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7053): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7053): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7053): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7053): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7053): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7053): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7053): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7053): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7053): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7053): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7053): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7053): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  917): failed to open /acct/uid_10089/pid_7071/cgroup.procs: No such file or directory
W/ActivityManager(  917): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  917): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7355 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7355): Quickset Services start...
,I/UEI.SmartControl( 7355): Manufacture = LGE
,D/UEI.SmartControl( 7355): File observer start...
E/UEI.SmartControl( 7355): IR Port is disabled: false
D/UEI.SmartControl( 7355): Starting file observer...
D/UEI.SmartControl( 7355): Extracting JNI libs...
D/UEI.SmartControl( 7355): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7355): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7355): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7355): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7355): --- Selecting new region: 2
,I/UEI.SmartControl( 7355): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7355): Platform has CIR...
D/UEI.SmartControl( 7355): NO CIR support, need to check package...
I/UEI.SmartControl( 7355): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7355): QS Service created
E/UEI.SmartControl( 7355): QS start get config
,D/UEI.SmartControl( 7355): Loading JNI Libs...
,D/UEI.SmartControl( 7355):  configuring local db...
D/UEI.SmartControl( 7355):  ---- Has DB8: true
,D/UEI.SmartControl( 7355): QS start statue = true Error code = 0
D/UEI.SmartControl( 7355): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7355): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7355): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7355): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7355): IrrcClient ++ 
D/irrcClient( 7355): getIrrcService ++ 
,D/irrcClient( 7355): getIrrcService -- 
D/irrcClient( 7355): IrrcClient -- 
W/irrc_jni( 7355): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7355): Services init done
I/UEI.SmartControl( 7355): Device manager: loading config....
,D/UEI.SmartControl( 7355): QS Service init finished
,D/UEI.SmartControl( 7355): QS Service version name: 0.1.73
D/UEI.SmartControl( 7355): QS Service version code: 1073
D/UEI.SmartControl( 7355): Service requested: Control
D/UEI.SmartControl( 7355): Config is loaded...
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,D/UEI.SmartControl( 7355):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7355): Request IControl service: devices are loaded...
I/UEI.SmartControl( 7355): Notify AllClients services are ready: 0
,I/ActivityManager(  917): Killing 7053:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  917): failed to open /acct/uid_10106/pid_7053/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7355): Internal service binding...
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,D/UEI.SmartControl( 7355): Internal timer expired: 1
,D/UEI.SmartControl( 7355): Service.onUnbind: IControl
D/UEI.SmartControl( 7355): Service.onDestroy
W/System.err( 7355): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1e62b961
W/System.err( 7355): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7355): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7355): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7355): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7355): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7355): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7355): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7355): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7355): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7355): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7355): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7355): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7355): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7355): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7355): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1e62b961
D/UEI.SmartControl( 7355): Shutdown IRRCPlayer... 
,W/irrc_jni( 7355): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7355): ~IrrcClient ++ 
D/irrcClient( 7355): ~IrrcClient -- 
W/irrc_jni( 7355): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7355): Blaster closed
D/UEI.SmartControl( 7355): Blaster closed
D/UEI.SmartControl( 7355): Shut down QS...
,D/UEI.SmartControl( 7355): Stopped file observer...
I/UEI.SmartControl( 7355): QS lib stop result = true
D/UEI.SmartControl( 7355): QS shutdown complete
D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 135440564015; DSPS: 4536019; Offset : -2996671233
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  917): acquireWakeLockInternal: lock=57798620, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=917
,D/WeatherService( 2643): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:34:0
,D/WeatherService( 2643): 2 : TimeTick Intent And Screen On
D/WeatherService( 2643): 2 : SDK version : 21
W/ActivityManager(  917): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2643): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2643): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2643): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2643): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2643): 2 : This is isUpdating : false
D/WeatherService( 2643): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2643): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2643): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2643): 2 : Fixed theme : optimus
D/WeatherReflect( 2643): 2 : Map key string is -2
,D/lim     ( 2643): 2 : time = 16:34
,I/WeatherReflect( 2643): Model Name : LG-D722
D/WeatherTheme( 2643): 2 : Different view - status_min_formatted : 33 != 34
D/WeatherTheme( 2643): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2643): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2643): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/Weather4x2_optimus( 2643): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2643): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2643): forecast size is 0
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2643): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2643): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2643): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2643): url is : null
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2643): 2 : update view, appWidgetId: 2
D/WeatherService( 2643): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:34:0
,D/PowerManagerServiceEx(  917): releaseWakeLockInternal: lock=57798620 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  917): ELAPSED_WAKEUP set : Alarm{ec058e5 type 2 when 140994 com.google.android.gms} when 140994
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1453044844271 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  917): ALS enabled for SRE
,D/PowerManagerServiceEx(  917): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28858 ms ago)
D/qdlights(  917): set_light_backlight: 253
,D/qdlights(  917): set_light_backlight: 250
,D/qdlights(  917): set_light_backlight: 247
,D/qdlights(  917): set_light_backlight: 243
,D/qdlights(  917): set_light_backlight: 240
,D/qdlights(  917): set_light_backlight: 237
,D/qdlights(  917): set_light_backlight: 233
,D/qdlights(  917): set_light_backlight: 230
,D/qdlights(  917): set_light_backlight: 227
,D/qdlights(  917): set_light_backlight: 223
,D/qdlights(  917): set_light_backlight: 220
,D/qdlights(  917): set_light_backlight: 217
,D/qdlights(  917): set_light_backlight: 213
,D/qdlights(  917): set_light_backlight: 210
,D/qdlights(  917): set_light_backlight: 207
,D/qdlights(  917): set_light_backlight: 203
,D/qdlights(  917): set_light_backlight: 200
,D/qdlights(  917): set_light_backlight: 197
,D/qdlights(  917): set_light_backlight: 193
,D/qdlights(  917): set_light_backlight: 190
,D/qdlights(  917): set_light_backlight: 187
,D/qdlights(  917): set_light_backlight: 183
,D/qdlights(  917): set_light_backlight: 180
,D/qdlights(  917): set_light_backlight: 177
,D/qdlights(  917): set_light_backlight: 173
,D/qdlights(  917): set_light_backlight: 170
,D/qdlights(  917): set_light_backlight: 167
,D/qdlights(  917): set_light_backlight: 163
,D/qdlights(  917): set_light_backlight: 160
,D/qdlights(  917): set_light_backlight: 157
,D/qdlights(  917): set_light_backlight: 153
,D/qdlights(  917): set_light_backlight: 150
,D/qdlights(  917): set_light_backlight: 147
,D/qdlights(  917): set_light_backlight: 143
,D/qdlights(  917): set_light_backlight: 140
,D/qdlights(  917): set_light_backlight: 137
,D/qdlights(  917): set_light_backlight: 133
,D/qdlights(  917): set_light_backlight: 130
,D/qdlights(  917): set_light_backlight: 127
,D/qdlights(  917): set_light_backlight: 123
,D/qdlights(  917): set_light_backlight: 120
,D/qdlights(  917): set_light_backlight: 117
,D/qdlights(  917): set_light_backlight: 113
,D/qdlights(  917): set_light_backlight: 110
,D/qdlights(  917): set_light_backlight: 107
,D/qdlights(  917): set_light_backlight: 103
,D/qdlights(  917): set_light_backlight: 100
,D/qdlights(  917): set_light_backlight: 97
,D/qdlights(  917): set_light_backlight: 93
,D/qdlights(  917): set_light_backlight: 90
,D/qdlights(  917): set_light_backlight: 87
,D/qdlights(  917): set_light_backlight: 83
,D/qdlights(  917): set_light_backlight: 80
,D/qdlights(  917): set_light_backlight: 77
,D/qdlights(  917): set_light_backlight: 73
,D/qdlights(  917): set_light_backlight: 70
,D/qdlights(  917): set_light_backlight: 67
,D/qdlights(  917): set_light_backlight: 63
,D/qdlights(  917): set_light_backlight: 60
,D/qdlights(  917): set_light_backlight: 57
,D/qdlights(  917): set_light_backlight: 53
,D/qdlights(  917): set_light_backlight: 50
,D/qdlights(  917): set_light_backlight: 47
,D/qdlights(  917): set_light_backlight: 43
,D/qdlights(  917): set_light_backlight: 40
,D/qdlights(  917): set_light_backlight: 37
,D/qdlights(  917): set_light_backlight: 33
,D/qdlights(  917): set_light_backlight: 30
,D/qdlights(  917): set_light_backlight: 27
,D/qdlights(  917): set_light_backlight: 23
,D/qdlights(  917): set_light_backlight: 20
,D/qdlights(  917): set_light_backlight: 17
,D/qdlights(  917): set_light_backlight: 13
,D/qdlights(  917): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 155441160622; DSPS: 5191399; Offset : -2996685109
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  917): ALS enabled for SRE
D/PowerManagerServiceEx(  917): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35846 ms ago)
I/PowerManagerService(  917): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  917): ALS enabled for SRE
D/PowerManagerServiceEx(  917): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35859 ms ago)
,W/ContextImpl(  917): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  917): Sleeping (uid 1000)...
D/LPWGController(  917): [updateScreenState] screen on = false
,D/LPWGController(  917): disable proximity sensor
D/LPWGController(  917): enable proximity sensor
I/SensorManager(  917): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2ef69c12] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  917): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  917): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  917): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  917): activate: handle is 48, enable
V/sensors_hal_Ctx(  917): activate sensors is 1400000000000
D/sensors_hal_Thresh(  917): enable: handle=48
I/sensors_hal_SAM(  917): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  917): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  917): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  917): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  917): enable: Received response: 0
D/PowerManagerServiceEx(  917): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35902 ms ago)
I/Adreno-EGL(  917): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  917): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  917): Build Date: 03/02/15 Mon
I/Adreno-EGL(  917): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  917): Remote Branch: 
I/Adreno-EGL(  917): Local Patches: 
I/Adreno-EGL(  917): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1306 us)
,I/Sensors (  428): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  917): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  917): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  917): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  917): processInd: handle 48, count=1
V/sensors_hal_Thresh(  917): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  917): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  917): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  917): poll: count: 256
I/sensors_hal_Ctx(  917): poll: released wakelock sensor_ind
D/sensors_hal_Util(  917): waitForResponse: timeout=0
D/LPWGController(  917): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  917): current mode = 1  value = 1 1
I/LPWGController(  917): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  917): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/ActivityManager(  917): Process com.google.android.talk (pid 6973) has died
,D/qdlights(  917): set_light_backlight: 0
,I/SensorManager(  917): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  917): activate: handle is 46, disable
V/sensors_hal_Ctx(  917): activate sensors is 1000000000000
D/sensors_hal_LP2(  917): enable: handle=46
D/sensors_hal_LP2(  917): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  917): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  917): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  917): Display changed displayId=0
,V/sensors_hal_SAM(  917): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  917): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
D/SurfaceControl(  917): Excessive delay in setPowerMode(): 195ms
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  917): Got set_interactive hint
D/KeyguardViewMediator( 1376): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
D/KeyguardViewMediator( 1376): notifyScreenOffLocked
,D/KeyguardViewMediator( 1376): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1376): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1376): unregisterProximitySensor
,D/WifiServerServiceExt(  917): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1376): onScreenTurnedOff why = 3
V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 917
,I/WifiServerServiceExt(  917): set CMD_KT_SCAN_INTERVAL
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
,V/voice   (  283): voice_set_parameters: enter: screen_state=on
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
,D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/GpsLocationProvider(  917): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:true
I/LEDService( 1795): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1795): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1795): stopPatternFlashing()
D/Cliptray Service( 1795): lockStatus = 0
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
I/LEDService( 1795): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
I/LEDService( 1795): updateLightsLocked : turn off led
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1795): RESTART MSG
,D/SplitWindow(  917): check instance of lgWin Window{2ac7b899 u0 SearchPanel}
,D/Ulp_jni (  917): JNI:system_update. Event-0
,D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1785): isRequireNfcCRouting() return true
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
D/InputDispatcher(  917): Window went away: Window{8391f28 u0 SearchPanel}
I/[SystemUI]Clock( 1376): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1376): time changed, timezoneChanged : false
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2643): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:34:20
D/WeatherService( 2643): 2 : ACTION screen on
,D/WeatherService( 2643): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2643): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2643): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:34:20
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): ACTION_SCREEN_ON
D/AppCleanupService( 4058): android.intent.action.SCREEN_ON
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 917
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
D/WifiController(  917): CMD_SCREEN_OFF 
D/WifiController(  917): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  917): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:false
,I/LEDService( 1795): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1795): stopPatternFlashing()
D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1795): clear
I/Cliptray Service( 1795): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1795): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1795): set_light_notifications: 0,0,0,0,3
I/LEDService( 1795): updateLightsLocked : turn on led
E/LEDService( 1795): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1795): Can't handle this request of patternId:0
D/LEDHandler( 1795): RESTART MSG
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2643): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:34:20
D/WeatherService( 2643): 2 : ACTION screen off
D/WeatherService( 2643): 2 : TimeTick Receiver Unregister
D/WeatherService( 2643): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:34:20
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  917): ACTION_SCREEN_OFF
D/AppCleanupService( 4058): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4058): AppUsageStatsSaveTask
E/NxpNfcJni( 1785): getReconnectState = 0x0
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,D/LNfcService( 1785): isRequireNfcCRouting() return true
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
,I/Sensors (  428): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1376): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  917): ELAPSED_WAKEUP set : Alarm{309e675e type 2 when 161713 com.android.systemui} when 161713
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1376): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1376): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 175441912489; DSPS: 5846784; Offset : -2996696285
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  917): battery changed pluggedType: 2
V/AlarmManager(  917): ELAPSED_WAKEUP set : Alarm{7a4d73f type 2 when 187400 com.google.android.gms} when 187400
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 14013 seconds from now (1453044890787)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  917): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 43704(2MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 13MB/22MB, paused 1.502ms total 90.855ms
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/LocationManagerService(  917): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  917): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  917): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  917): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  917): ELAPSED_WAKEUP set : Alarm{34c80e2f type 2 when 190734 android} when 190734
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 195442608939; DSPS: 6502167; Offset : -2996702208
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  917): battery changed pluggedType: 2
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  917): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 215443302891; DSPS: 7157549; Offset : -2996679148
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 235443981581; DSPS: 7812932; Offset : -2996703170
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  917): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 255444645427; DSPS: 8468313; Offset : -2996679386
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 275445263180; DSPS: 9123694; Offset : -2996702267
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 295445919370; DSPS: 9779075; Offset : -2996687258
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  917): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  917): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  917): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  917): tsOffsetIs: Apps: 315446516342; DSPS: 10434455; Offset : -2996700482
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1795): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1795): Battery Level Remaining: 100%
D/LEDHandler( 1795): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  917): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  917): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  917): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1795): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6139): --= Surplus to requirements =--
I/jxcore-log( 6139): 
I/jxcore-log( 6139): ****TEST TOOK:  ms ****
I/jxcore-log( 6139): 
I/jxcore-log( 6139): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6139): 
,D/AndroidRuntime( 7516): 
D/AndroidRuntime( 7516): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7516): CheckJNI is OFF
,D/AndroidRuntime( 7516): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  917): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  917): Killing 6139:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  917): WIN DEATH: Window{32235874 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  917): Focus left window: Window{32235874 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  917): Window went away: Window{32235874 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  917): Skipping PackageSetting{303627af com.example.hello/10317} due to missing metadata
,I/ActivityManager(  917):   Force finishing activity ActivityRecord{34b834c6 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  917): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
,W/ActivityManager(  917): Spurious death for ProcessRecord{14da8c3c 6139:com.test.thalitest/u0a316}, curProc for 6139: null
,I/ActivityManager(  917): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1875): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1875): [Launcher.java:776:onResume()]onResume
,D/KeyguardModel( 1376): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  917): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1940): Explicit concurrent mark sweep GC freed 9429(649KB) AllocSpace objects, 4(95KB) LOS objects, 39% free, 12MB/20MB, paused 2.905ms total 90.357ms
W/System.err( 3606): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3606): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3606): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3606): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3606): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3606): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3606): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3606): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3606): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3606): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ActivityManager(  917): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7547 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     ( 4214): Explicit concurrent mark sweep GC freed 20562(1208KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 14MB/18MB, paused 787us total 136.808ms
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1376): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1376): createShortcutInfo...
I/[SystemUI]QSlideListController( 1376): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1875): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1875): [Launcher.java:929:onResume()]onResume end
I/Activity( 1875): Activity.onPostResume() called 
D/KeyguardModel( 1376): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1376): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1376): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1376): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1376): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1376): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1376): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1376): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1376): handleShortcutListChanged...
W/[LGHome]LGWallpaperInfo( 1875): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1875): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1376): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1376): createShortcutInfo...
I/SystemUI[Framework](  917): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/KeyguardModel( 1376): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1376): createShortcutInfo...
W/PhoneWindowManagerEx(  917): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  917): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  917): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  917): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@162af5f9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  917): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.mms: Resource ID #0x0
,I/SystemUI[Framework](  917): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/KeyguardModel( 1376): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1376): createShortcutInfo...
W/PhoneWindowManagerEx(  917): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx(  917): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  917): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  917): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@162af5f9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  917): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/InputDispatcher(  917): Focus entered window: Window{210f5178 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,D/KeyguardModel( 1376): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1376): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourcesManager( 7547): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7547): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/ResourcesManager( 7547): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1376): handleShortcutListChanged...
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1875): [setNavigationBarColor] color=0x 0
I/art     (  917): Explicit concurrent mark sweep GC freed 64894(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 6.193ms total 267.229ms
I/art     (  917): WaitForGcToComplete blocked for 146.845ms for cause Explicit
D/administrator(  917): Handling package changes for user 0
,W/InputMethodManagerService(  917): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  917): Got RemoteException sending setActive(false) notification to pid 6139 uid 10316
I/art     (  917): Explicit concurrent mark sweep GC freed 6315(377KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 19.004ms total 295.320ms
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/LGEmail ( 7547): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  917): Timeline: Activity_windows_visible id: ActivityRecord{bc6083 u0 com.lge.launcher2/.Launcher t221} time:333320
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
D/LGEmail ( 7547): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,W/IInputConnectionWrapper( 1875): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1607): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1875): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7516): Shutting down VM
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/NotificationService(  917): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  917): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  917): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  917): removeObsoleteFile: deleting file=222_task.xml
,D/PhoneStatusBar( 1376): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1376): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1376):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1376): , Keyguard show=false, IME shown=false, Panel expanded=false
I/PackageChangeReceiver( 7547): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/AppUp4:PreloadHelper( 7166): added Exclude : com.test.thalitest
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/ResourcesManager(  917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  917): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7573 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/ResourcesManager( 7573): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7573): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7573): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7573): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7573): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourceType(  917): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SQLiteDatabase( 7573): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 7573): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 7573): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 7573): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7573): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7573): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 7573): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 7573): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 7573): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 7573): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 7573): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 7573): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 7573): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7573): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7573): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7573): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 7573): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7573): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7573): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 7573): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/AndroidRuntime( 7573): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 7573): FATAL EXCEPTION: main
E/AndroidRuntime( 7573): Process: com.android.settings, PID: 7573
E/AndroidRuntime( 7573): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7573): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 7573): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 7573): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 7573): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 7573): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7573): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7573): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7573): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 7573): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7573): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7573): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 7573): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 7573): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 7573): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 7573): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7573): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7573): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 7573): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 7573): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 7573): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 7573): 	... 11 more

```
