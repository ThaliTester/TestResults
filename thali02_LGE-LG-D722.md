#### Test 5635717154d1b6f_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  986): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6384 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,--------- beginning of main
I/GservicesProvider( 6384): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient( 6384): GMS http client unavailable, use old client
I/GoogleHttpClient( 6384): GMS http client unavailable, use old client
D/libc-netbsd( 5793): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5793): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5793): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5793): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5793): propertyValue:false
D/libc-netbsd( 5793): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5793): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AndroidRuntime( 6408): 
D/AndroidRuntime( 6408): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6408): CheckJNI is OFF
D/libc-netbsd( 5793): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5793): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAV2    ( 6069): Thread[GAThread,5,main]: No campaign data found.
I/NotificationManager(  986): android: cancelAsUser(2) by android
D/AndroidRuntime( 6408): Calling main entry com.android.commands.am.Am
I/ActivityManager(  986): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  986): setTaskToReturnTo : TaskRecord{aa6ba3d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  986): setTaskToReturnTo : TaskRecord{aa6ba3d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
I/qtaguid ( 5793): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5793): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5793): untagSocket(41) failed with errno -22
D/Finsky  ( 5793): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/WindowStateEx(  986): AppWindowTokenEx init.. 
D/ContextHelper(  986): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  986): Focus left window: Window{1e2e6554 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/SplitWindow(  986): check instance of lgWin Window{1b00fcdf u0 Starting com.test.thalitest}
D/AndroidRuntime( 6408): Shutting down VM
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  986): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6432 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  986): Starting window displayed
I/SystemUI[Framework](  986): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
I/HotwordDetector( 1940): Closing mic
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  986): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  986): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  986): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  986): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7c05c5a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  986): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/MicrophoneInputStream( 1940): mic_close com.google.android.apps.gsa.speech.audio.u@3a0154a7
V/AudioRecord( 1940): stop()
D/AudioRecord( 1940): AudioRecord->stop()
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
I/[SystemUI]NavigationThemeResource( 1376): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1376):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1376): , Keyguard show=false, IME shown=false, Panel expanded=false
,V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb398d000
D/BarTransitions( 1376): draw background and invalidate : color = 11000000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
D/BarTransitions( 1376): draw background and invalidate : color = 11111111
I/ActivityManager(  986): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6460 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
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
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb398d000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1376): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioSystem( 1940): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 2111): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb398d000 exiting
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioSystem(  986): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2003): ioConfigChanged() event 4, ioHandle 17
I/NotificationManager(  986): android: cancelAsUser(2) by android
V/AudioSystem( 3217): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioFlinger(  281): releasing 16 from 1940 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1940, calling pid 281
I/HotwordRecognitionRnr( 1940): Stopping hotword detection.
I/HotwordRecognitionRnr( 1940): Hotword detection finished
W/ResourcesManager( 6460): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6460): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ContextHelper( 6432): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/MultiDex( 6460): VM with version 2.1.0 has multidex support
I/MultiDex( 6460): install
I/MultiDex( 6460): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6460): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/WebViewFactory( 6432): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/ActivityThread( 6460): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6460): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ab9a7d2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6460): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6460): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6460): com.google.android.gms: cancel(39789) by com.google.android.gms
I/LibraryLoader( 6432): Time to load native libraries: 2 ms (timestamps 6361-6363)
I/LibraryLoader( 6432): Expected native library version number "",actual native library version number ""
D/ChimeraCfgMgr( 6460): Reading stored module config
D/WearableService( 1734): callingUid 10006, callindPid: 1734
D/LocationInitializer( 4382): Restart initialization of location
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1734): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/WebViewChromiumFactoryProvider( 6432): Binding Chromium to main looper Looper (main, tid 1) {225c9410}
I/LibraryLoader( 6432): Expected native library version number "",actual native library version number ""
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/chromium( 6432): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
E/lowmemorykiller(  244): Error writing /proc/6259/oom_score_adj; errno=22
W/GCoreFlp( 1734): No location to return for getLastLocation()
I/BrowserStartupController( 6432): Initializing chromium process, singleProcess=true
W/FusedLocationProvider( 1734): location=null
W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6432): ApplicationContext is null in ApplicationStatus
D/ChimeraCfgMgr( 6460): Loading module com.google.android.gms.car from APK com.google.android.gms
I/ActivityManager(  986): Process com.android.gallery3d (pid 6259) has died
W/chromium( 6432): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6432): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6432): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6432): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6432): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6432): Remote Branch: 
I/Adreno-EGL( 6432): Local Patches: 
I/Adreno-EGL( 6432): Reconstruct Branch: 
I/qtaguid ( 5793): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5793): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5793): untagSocket(41) failed with errno -22
D/NativeLibraryUtils( 6460): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 6460): Connecting to CarCallService...
V/AudioPolicyService(  281): registerClient() client 0xb4027480, uid 10316
,D/BluetoothManagerService(  986): Message: 20
D/BluetoothManagerService(  986): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bb435bc:true
I/art     ( 6460): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6460): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/BluetoothAdapterService(610197820)( 2003): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@14e50872
D/CAR.SERVICE( 6460): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6460): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6460): Creating a new PhoneAdapter instance
W/ActivityManager(  986): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6460): setListener: com.google.android.gms.car.dn@1d3478c9
W/ActivityManager(  986): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6460): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6460): Starting CarCallService with initial phone null
W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
,I/NotificationManager( 6460): com.google.android.gms: cancel(10436) by com.google.android.gms
W/AwContents( 6432): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6432): CordovaWebView is running on device made by: LGE
,W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
D/AlertService( 6171): Beginning updateAlertNotification
D/CAR.SERVICE( 6460): Package validated; name: com.android.vending
,I/art     ( 5793): CheckpointMarkThreadRoots callback created = 0xaaf14810
,I/ActivityManager(  986): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6518 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5793): CheckpointMarkThreadRoots callback created = 0xaaf98160
,I/Activity( 6432): Activity.onPostResume() called 
D/OpenGLRenderer( 6432): Render dirty regions requested: true
I/OpenGLRenderer( 6432): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6432): Enabling debug mode 0
,I/NotificationManager( 5793): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5793): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/Atlas   ( 6432): Validating map...
W/ResourcesManager( 6518): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/SplitWindow(  986): check instance of lgWin Window{e4e85ec u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6432): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/CalendarProvider2( 6518): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@9f8d837
,D/InputDispatcher(  986): Focus entered window: Window{e4e85ec u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/CalendarProvider2( 6518): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6518): Created com.android.providers.calendar.CalendarAlarmManager@225c9410(com.android.providers.calendar.CalendarProvider2@9f8d837)
W/InputMethodManagerService(  986): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  986): Displayed com.test.thalitest/.MainActivity: +1s278ms
I/Timeline(  986): Timeline: Activity_windows_visible id: ActivityRecord{1dea1232 u0 com.test.thalitest/.MainActivity t222} time:97142
I/Timeline( 6432): Timeline: Activity_idle id: android.os.BinderProxy@284faa1f time:97160
,D/AlertService( 6171): No fired or scheduled alerts
I/NotificationManager( 6171): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(6) by com.android.calendar
,I/NotificationManager( 6171): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 6171): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6171): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6171): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/BindingManager( 6432): Cannot call determinedVisibility() - never saw a connection for the pid: 6432
,D/AlarmScheduler( 6171): No events found starting within 1 week.
D/JsMessageQueue( 6432): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  986): Killing 6171:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10013/pid_6171/cgroup.procs: No such file or directory
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  986): android: cancelAsUser(2) by android
,D/jxcore_app_log( 6432): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622971392
D/JX-Cordova( 6432): jxcore cordova android initializing
I/qtaguid ( 5793): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5793): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5793): untagSocket(41) failed with errno -22
,I/art     ( 6432): CheckpointMarkThreadRoots callback created = 0x9f51e4b0
,I/art     ( 6432): CheckpointMarkThreadRoots callback created = 0x9f51e480
,W/ResourcesManager( 5793): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5793): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5793): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5793): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  986): RTC_WAKEUP set : Alarm{107db8b4 type 0 when 1453132520398 com.android.vending} when 1453132520398
,D/Finsky  ( 5793): [709] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1734): client connected with version: 8296000
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  986): android: cancelAsUser(2) by android
,D/Finsky  ( 5793): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5793): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5793): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5793): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5793): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5793): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5793): propertyValue:false
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  986): Process com.google.android.talk (pid 5920) has died
,I/ActivityManager(  986): Killing 6239:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10011/pid_6239/cgroup.procs: No such file or directory
,I/art     (  986): Explicit concurrent mark sweep GC freed 26058(1260KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.583ms total 184.122ms
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/jxcore-log( 6432): Initializing JXcore engine
,W/jxcore-log( 6432): JXcore engine is ready
W/jxcore-log( 6432): Starting JXcore engine
,I/art     ( 6432): Background sticky concurrent mark sweep GC freed 49514(4MB) AllocSpace objects, 0(0B) LOS objects, 12% free, 23MB/26MB, paused 8.760ms total 115.285ms
W/.test.thalitest( 6432): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6338]" dev="sockfs" ino=6338 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6432): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6432): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6110]" dev="sockfs" ino=6110 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6432): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6432): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6432): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31175]" dev="sockfs" ino=31175 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6432): Platform android
W/jxcore-log( 6432): 
W/jxcore-log( 6432): Process ARCH arm
W/jxcore-log( 6432): 
,I/ActivityManager(  986): Process com.google.android.gm (pid 6069) has died
,V/AlarmManager(  986): RTC_WAKEUP set : Alarm{1da467aa type 0 when 1453132523252 com.google.android.googlequicksearchbox} when 1453132523252
,I/jxcore-log( 6432): JXcore Cordova bridge is ready!
I/jxcore-log( 6432): 
,W/jxcore-log( 6432): JXcore engine is started
I/chromium( 6432): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6432): Skipped 205 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 6432): Toggling radios to true
I/jxcore-log( 6432): 
,D/BluetoothAdapter( 6432): enable(): BT is already enabled..!
D/WifiServiceImplEx(  986): setWifiEnabled: true pid=6432, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  986): setWifiEnabled: true pid=6432, uid=10316
D/WifiServiceImplEx(  986): disconnect pid=6432, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  986): reconnect pid=6432, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6432): Radios toggled
I/jxcore-log( 6432): 
,I/jxcore-log( 6432): My device name is: LGE-LG-D722
I/jxcore-log( 6432): 
I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2681): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  986): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  986): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1806): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/LGWifiP2pService(  986): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  986): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  986): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  277): Clearing all IP addresses on wlan0
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1734): Read error: ssl=0xaaede600: I/O error during system call, Connection timed out
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  986): hidePasspointNotification off =false
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xaaede600: I/O error during system call, Broken pipe
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:23.824 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  986): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  986): ignoring duplicate network state non-change
D/ConnectivityService(  986): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/ActivityManager(  986): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6599 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  986): Start Disconnecting Watchdog 1
D/WifiHS20(  986): hidePasspointNotification off =false
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  986): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  986): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:23.903 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  986): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
,I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): DefaultState{ when=-10ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): Forcing reevaluation
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/ConnectivityService(  986): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  986): disableDataServiceNotify
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/WifiHS20(  986): hidePasspointNotification off =false
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:23.946 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/DSQN    (  986): stop dsqn bin
D/WifiNetworkAgent(  986): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/WifiHS20(  986): hidePasspointNotification off =false
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:23.958 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:23.967 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
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
D/ConnectivityService(  986): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  986):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  986):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DhcpStateMachine(  986): StoppedState
D/DhcpStateMachine(  986): StoppedState{ when=-101ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  986): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat(  986): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): Disconnected - quitting
D/CSLegacyTypeTracker(  986): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  986): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  986): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ActivityManager(  986): Process com.google.android.apps.plus (pid 6321) has died
,D/WifiServerServiceExt(  986): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  986): setSupplicantStateDISCONNECTED
D/ConnectivityService(  986): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1843): |CORE| No family connected
V/NetworkPolicy(  986): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  986): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  986): MasterInitialState.processMessage what=3
D/ConnectivityService(  986): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiServerServiceExt(  986): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  986): setSupplicantStateSCANNING
V/NetworkPolicy(  986): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  986): MasterInitialState.processMessage what=3
D/ConnectivityService(  986): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  986): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1843): |CORE| No family connected
D/WIFI    (  986): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  986):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1843): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  986): Removing idletimer
I/QCNEJ   ( 1843): |CORE| sendDefaultNwMsg: default = -1
W/Settings(  986): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1753): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/CAR.SERVICE( 6460): mConnectedToCar = false, abort
,E/ActivityThread( 6460): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@296a4891 that was originally bound here
E/ActivityThread( 6460): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@296a4891 that was originally bound here
E/ActivityThread( 6460): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6460): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6460): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6460): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6460): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6460): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6460): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6460): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6460): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6460): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6460): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6460): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6460): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6460): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6460): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6460): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6460): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6460): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6460): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6460): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6460): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6460): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6460): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6460): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@144cd0d0 that was originally bound here
E/ActivityThread( 6460): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@144cd0d0 that was originally bound here
E/ActivityThread( 6460): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6460): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6460): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6460): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6460): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6460): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6460): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6460): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6460): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6460): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6460): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6460): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6460): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6460): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6460): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6460): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6460): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6460): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6460): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6460): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6460): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6460): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  986): Unbind failed: could not find connection for android.os.BinderProxy@e121f9b
W/ResourcesManager( 6599): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6599): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6599): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6599): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6599): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  489): init target 500000
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  986): battery changed pluggedType: 2
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
D/charger_monitor(  489): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1806): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/WifiController(  986): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/IndexDatabaseHelper( 6599): Using schema version: 115
I/IndexDatabaseHelper( 6599): Index is fine
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
,I/ActivityManager(  986): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6622 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6622): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6622): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6622): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
I/PCSuite ( 6622): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6622): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6622): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  986): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6647 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  986): Killing 6281:com.android.contacts/u0a18 (adj 15): empty #11
I/wpa_supplicant( 2681): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
W/libprocessgroup(  986): failed to open /acct/uid_10018/pid_6281/cgroup.procs: No such file or directory
,D/LocSvc_java(  986): onReceive
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2681): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.067 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.07 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  986): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  986): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/WifiServerServiceExt(  986): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  986): setSupplicantStateASSOCIATED
,W/ResourcesManager( 6647): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  986): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  986): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.113 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.114 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/wpa_supplicant( 2681): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt(  986): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  986): setSupplicantStateGROUP_HANDSHAKE
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/WifiServiceExtension(  986): setVHTCapabilityType  : false
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/WifiServerServiceExt(  986): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  986): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  986): setSecurityType  : 2
,I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.172 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.181 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/ConnectivityService(  986): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  986): Got NetworkAgent Messenger
D/ConnectivityService(  986): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/ConnectivityService(  986): NetworkAgent connected
E/WifiConfigStore(  986): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  986): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
D/CommandListener(  277): Setting iface cfg
E/WifiStateMachine(  986): Start Dhcp Watchdog 2
D/DhcpStateMachine(  986): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  986): WaitBeforeStartState
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/ConnectivityService(  986): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  986): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2eadc9c3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  986): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2eadc9c3 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  986): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  986): DHCP Start wake lock is acquired.
E/WifiStateMachine(  986): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  986): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  986): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  277): Setting iface cfg
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/CommandListener(  277): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  986): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiServerServiceExt(  986): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  986): setSupplicantStateCOMPLETED
D/LGWifiP2pService(  986): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  986): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  986): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/ConnectivityService(  986): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  986): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  986): ignoring duplicate network state non-change
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  986): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  986): Adding iface wlan0 to network 101
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.441 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.447 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  986): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
,E/ConnectivityService(  986): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  986): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  986): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  986): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  277): netlink response contains error (File exists)
D/ConnectivityService(  986): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  986): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  986): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  986): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.465 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = true, mWifiLevel = 2
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiHS20(  986): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:25.475 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/Nat464Xlat(  986): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  986): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  986): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  986): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  986):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): Connected
D/ConnectivityService(  986):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  986):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  986):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  986):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  986): currentScore = 0, newScore = 20
D/ConnectivityService(  986):    accepting network in place of null
D/ConnectivityService(  986): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  986): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  986):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  986): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NO,T_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  986): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  986): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): [LWD] wait 500ms before dns check
D/ConnectivityService(  986): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  986): [e] list.add(nai) empty : false size: 1
D/Tethering(  986): MasterInitialState.processMessage what=3
D/ConnectivityService(  986): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1843): |CORE| No family connected
I/QCNEJ   ( 1843): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  986): validation of new default Network = false
D/ConnectivityService(  986): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  986): enableDataServiceNotify 
D/DSQN    (  986): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1843): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/ConnectivityService(  986): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  986):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  986):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  986): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  986): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524290
,I/DSQN    ( 6677): DSQN samuel.seo ver 141203
E/DSQN    ( 6677): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6677): created command queue thread
I/DSQN    ( 6677): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6677): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/Babel_SMS( 6647): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6647): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6647): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6647): MmsConfig.loadFromDatabase
D/DhcpStateMachine(  986): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  986): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  986): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6685): version 5.5.6 starting
,E/dhcpcd  ( 6685): get_duid: Read-only file system
E/Babel_SMS( 6647): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6647): MmsConfig.loadFromResources
E/Babel_SMS( 6647): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6647): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/dhcpcd  ( 6685): wlan0: rebinding lease of 192.168.1.134
,I/art     ( 6647): CheckpointMarkThreadRoots callback created = 0xb042d800
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/art     ( 6647): CheckpointMarkThreadRoots callback created = 0xb042d7f0
D/SensorManager( 6647): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6647): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6647): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6647): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6647): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6647): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6647): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6647): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6647): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6647): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6647): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6647): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6647): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6647): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6647): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6647): found sensor: Motion Accel, handle=46
,I/ActivityManager(  986): Process com.android.providers.calendar (pid 6518) has died
W/Settings( 6647): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6647): startup - clean
,I/Babel   ( 6647): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
I/PCSuite ( 6622): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6622): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6622): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6647): Unsupported mime audio/x-lg-flac
,V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6647): Unsupported mime audio/adpcm
W/AudioCapabilities( 6647): Unsupported mime audio/g726
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
W/AudioCapabilities( 6647): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6647): Unsupported mime audio/wma-voice
,I/PCSuite ( 6622): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6622): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6622): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6647): Unsupported mime video/mjpg
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
,W/VideoCapabilities( 6647): Unsupported mime video/theora
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6599): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
W/AudioCapabilities( 6647): Unsupported mime audio/evrc
,W/AudioCapabilities( 6647): Unsupported mime audio/qcelp
W/VideoCapabilities( 6647): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): [LWD] DNSResolver start dns
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
W/AudioCapabilities( 6647): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6647): Unsupported mime audio/qcelp
W/AudioCapabilities( 6647): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  986): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6647): Unsupported mime video/mp4v-esdp
,I/DSQN    ( 6677): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6677): restart monitoring
I/DSQN    ( 6677): dsqn report finish
D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  986): DSQM DsqnNotification wlan0  1
D/DSQN    (  986): start to monitor internet connection
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
I/VideoCapabilities( 6647): Unsupported profile 4 for video/mp4v-es
,V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6647): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
I/PCSuite ( 6622): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
W/VideoCapabilities( 6647): Unrecognized profile 2130706433 for video/avc
,D/PCSuite ( 6622): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 15:55:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453132526133], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453132526061]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): Don't send network conditions - lacking user consent.
W/VideoCapabilities( 6647): Unrecognized profile 2130706433 for video/avc
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  986): Validated
D/ConnectivityService(  986): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  986): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  986):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  986):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  986):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  986): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  986): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  986):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  986):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  986): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  986): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  986): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  986): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524290
D/WIFI    (  986):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  986): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  986): set CMD_CAPTIVE_CHECK_COMPLETED
V/WiFiOffLoadBroadcast( 6599): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6647): Unrecognized profile 2130706433 for video/avc
,D/WiFiOffLoadBroadcast( 6599): MCCMNC not supported: null
I/PCSuite ( 6622): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6622): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/vclib   ( 6647): onServiceConnected
W/Babel   ( 6647): Attempted to change video mute state without an active call.
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/NotificationManager( 6647): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  986): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/dhcpcd  ( 6685): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  986): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  986): identical MTU - not setting
D/Nat464Xlat(  986): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  986): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  986):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  986):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  986): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  986): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  986): enableDataServiceNotify 
D/DSQN    (  986): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524295
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:26.888 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/dhcpcd  ( 6685): wlan0: leased 192.168.1.134 for 86400 seconds
,D/DSQN    (  986): dsqn is running restart
I/DSQN    ( 6708): DSQN samuel.seo ver 141203
E/DSQN    ( 6708): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6708): created command queue thread
I/DSQN    ( 6708): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6708): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/ConnectivityService(  986): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  986): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  986): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  986): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6728 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  986): onReceive
D/LocSvc_java(  986): got connectivity action
,D/LocSvc_java(  986): broadcast - no network connections
D/LocSvc_java(  986): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  986): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  986): onReceive
D/LocSvc_java(  986): got connectivity action
D/LocSvc_java(  986): broadcast - no network connections
D/LocSvc_java(  986): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  986): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  986): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  986): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  986): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  986): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  986): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  986): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  986): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  986): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  986): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  986): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  986): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  986): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  986): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  986): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  986): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  986): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  986): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  986): RunningState
I/MusicStore( 6728): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6728): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6728): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6728): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6728): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6728): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6728): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6728): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6728): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3083ecf5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6728): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6728): GMSCore installation verified
I/ConfigStore( 6728): Config Database version: 1
,I/MediaRouter( 6728): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6728): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6728): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6728): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  986): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6780 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6728): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6728): Using platform SSLCertificateSocketFactory
,I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-18 16:55:28.333 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6780): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6780): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6780): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  986): Process com.lge.lockscreensettings (pid 6304) has died
,V/WifiInternetCheck(  986): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NotificationManager( 1940): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/ConnectivityService(  986): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  986): Process com.android.vending (pid 5793) has died
,I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  986): onReceive
D/LocSvc_java(  986): got connectivity action
D/LocSvc_java(  986): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  986): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  986): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  986): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  986): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  986): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  986): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6728): type=WIFI subType= reason=null isConnected=true
I/LGEmail ( 6780): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6780): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/SQLiteConnectionPool( 4382): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/jxcore-log( 6432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6432): 
,I/ActivityManager(  986): Process com.google.android.talk (pid 6647) has died
,I/NotificationManager( 6728): com.google.android.music: cancel(1061) by com.google.android.music
,D/eas_req ( 6780): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  986): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6816 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6780): JNI_OnLoad()
I/HubEmail( 6780): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6780): registerNatives()
I/HubEmail( 6780): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6780): registerNativeMethods()
I/HubEmail( 6780): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6780): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6780): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6816): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6816): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6816): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6816): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6816): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6816): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  986): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6840 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.148ms
,E/LGDMClient( 6816): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6816): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6816): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.533ms
,D/LGDMClient( 6816): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6816): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 31.169ms
,I/AppUp4:AppBoxCP( 6840): onCreate
,W/AppUp4:DB( 6840):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6840):  setFingerPrint start
I/AppUp4:DB( 6840):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6840):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6840):  SDK version = 0
I/AppUp4:DB( 6840):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6840): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6840): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6840): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6840): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6840): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6840): onReceive
I/AppUp4:CustModeStarterReceiver( 6840): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6840): Context : android.app.ReceiverRestrictedContext@2ae81b09
D/AppUp4:CustFacade( 6840): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6840): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6840): begin check event
I/AppUp4:CustModeStarterReceiver( 6840): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6840): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6840): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6840): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6840): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  986): Killing 6460:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  986): failed to open /acct/uid_10006/pid_6460/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3217): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3217): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3217): networkInfo.isConnected() = false
I/jxcore-log( 6432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6432): 
,I/jxcore-log( 6432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6432): 
I/ActivityManager(  986): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6864 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/jxcore-log( 6432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6432): 
,I/jxcore-log( 6432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6432): 
I/jxcore-log( 6432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6432): 
,I/jxcore-log( 6432): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6432): 
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/PhoneMonitor( 6864): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6864): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6864): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  986): Killing 6599:com.android.settings/1000 (adj 15): empty #11
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  986): propertyValue:false
,D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  986): propertyValue:false
I/DSQN    ( 6708): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6708): restart monitoring
,D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  986): DSQM DsqnNotification wlan0  1
D/DSQN    (  986): start to monitor internet connection
I/DSQN    ( 6708): dsqn report finish
V/WifiInternetCheck(  986): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup(  986): failed to open /acct/uid_1000/pid_6599/cgroup.procs: No such file or directory
,V/DownloadManager( 3262): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 4382): Checkin interval check for package: unspecified last checkin: 1453132503457 min interval config: 0 actual interval: 26381
V/DownloadManager( 3262): DownloadService onCreate
,I/DownloadManager( 3262): in removeSpuriousFiles
I/NotificationManager( 3262): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@3ab9a7d2 on behalf of 3262
D/PhoneMonitor( 6864): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6864): [loadFeatureFromXml] *** start feature loading from xml
I/DownloadManager( 3262): in trimDatabase
,V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/TelephonyAutoProfiling( 6864): [parse] Load xml
V/TelephonyAutoProfiling( 6864): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6864): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@309aa0a3 on behalf of 3262
I/ActivityManager(  986): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6895 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3262): DownloadService onStartCommand
I/CheckinService( 4382): Checking schedule, now: 1453132529890 next: 1453132533384
I/CheckinService( 4382): active receiver: disabled
V/DownloadManager( 3262): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 6864): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@35100759 on behalf of 3262
,V/DownloadManager( 3262): DownloadService onDestroy
,I/ActivityManager(  986): Killing 5892:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5873): android.os.DeadObjectException
,W/System.err( 5873): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5873): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5873): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5873): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5873): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5873): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5873): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5873): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5873): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5873): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5873): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5873): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5873): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5873): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5873): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5873): android.os.DeadObjectException
W/System.err( 5873): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5873): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5873): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5873): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5873): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5873): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5873): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5873): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5873): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5873): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5873): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5873): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5873): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
,W/System.err( 5873): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5873): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  986): failed to open /acct/uid_10089/pid_5892/cgroup.procs: No such file or directory
W/ActivityManager(  986): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/WeatherAncestor( 2806): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:30
I/ActivityManager(  986): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6921 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2806): 2 : This is isUpdating : false
D/WeatherAncestor( 2806): connectivity changed - connection : true
D/Weather_cast( 2806): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2806): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:30
D/WeatherService( 2806): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  986): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6934 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/jxcore-log( 6432): Test app app.js loaded
I/jxcore-log( 6432): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6432): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6432): BLE advertisement is supported
I/jxcore-log( 6432): 
W/ActivityManager(  986): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2806): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2806): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2806): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/chromium( 6432): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ResourcesManager( 6934): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6921): Quickset Services start...
,I/UEI.SmartControl( 6921): Manufacture = LGE
D/UEI.SmartControl( 6921): File observer start...
,E/UEI.SmartControl( 6921): IR Port is disabled: false
D/UEI.SmartControl( 6921): Starting file observer...
D/UEI.SmartControl( 6921): Extracting JNI libs...
D/UEI.SmartControl( 6921): --- this system supports 32-bit or 64-bit only
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/Babel_SMS( 6934): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6934): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6934): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6934): MmsConfig.loadFromDatabase
,D/UEI.SmartControl( 6921): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6921): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6921): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/Babel_SMS( 6934): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6934): MmsConfig.loadFromResources
E/Babel_SMS( 6934): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6934): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/UEI.SmartControl( 6921): --- Selecting new region: 2
,I/UEI.SmartControl( 6921): -- Running on KitKat(19) and above! JNI will be used.
D/SensorManager( 6934): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6934): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6934): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6934): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6934): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6934): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6934): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6934): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6934): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6934): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6934): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6934): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6934): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6934): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6934): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6934): found sensor: Motion Accel, handle=46
D/UEI.SmartControl( 6921): Platform has CIR...
D/UEI.SmartControl( 6921): NO CIR support, need to check package...
I/UEI.SmartControl( 6921): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6921): QS Service created
E/UEI.SmartControl( 6921): QS start get config
,I/art     ( 6934): CheckpointMarkThreadRoots callback created = 0xb042d8d0
W/Settings( 6934): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6934): startup - clean
I/Babel   ( 6934): deleted: false for 0
,I/art     ( 6934): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,D/UEI.SmartControl( 6921): Loading JNI Libs...
D/UEI.SmartControl( 6921):  configuring local db...
I/ActivityManager(  986): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6980 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6934): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6934): Unsupported mime audio/adpcm
W/AudioCapabilities( 6934): Unsupported mime audio/g726
,W/AudioCapabilities( 6934): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6934): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6934): Unsupported mime video/mjpg
W/VideoCapabilities( 6934): Unsupported mime video/theora
,W/AudioCapabilities( 6934): Unsupported mime audio/evrc
,W/AudioCapabilities( 6934): Unsupported mime audio/qcelp
W/VideoCapabilities( 6934): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6934): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6934): Unsupported mime audio/qcelp
W/AudioCapabilities( 6934): Unsupported mime audio/evrc
W/VideoCapabilities( 6934): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6934): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6934): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6934): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6934): Unrecognized profile 2130706433 for video/avc
,D/UEI.SmartControl( 6921):  ---- Has DB8: true
W/VideoCapabilities( 6934): Unrecognized profile 2130706433 for video/avc
,D/UEI.SmartControl( 6921): QS start statue = true Error code = 0
D/UEI.SmartControl( 6921): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6921): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/vclib   ( 6934): onServiceConnected
W/Babel   ( 6934): Attempted to change video mute state without an active call.
D/UEI.SmartControl( 6921): IRRCDataComm has AudioManager!!!!.
,D/libc-netbsd( 6934): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6934): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6934): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6934): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6934): propertyValue:false
I/NotificationManager( 6934): com.google.android.talk: cancel(10436) by com.google.android.talk
W/irrc_jni( 6921): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6921): IrrcClient ++ 
D/irrcClient( 6921): getIrrcService ++ 
D/irrcClient( 6921): getIrrcService -- 
D/irrcClient( 6921): IrrcClient -- 
W/irrc_jni( 6921): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6921): Services init done
I/Babel   ( 6934): connection state changed from UNKNOWN to CONNECTED
D/UEI.SmartControl( 6921): QS Service init finished
D/UEI.SmartControl( 6921): QS Service version name: 0.1.73
I/UEI.SmartControl( 6921): Device manager: loading config....
,D/UEI.SmartControl( 6921): QS Service version code: 1073
D/UEI.SmartControl( 6921): Service requested: Control
I/ActivityManager(  986): Killing 6622:com.lge.sync/1000 (adj 15): empty #11
,D/UEI.SmartControl( 6921): Config is loaded...
W/libprocessgroup(  986): failed to open /acct/uid_1000/pid_6622/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6921): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6921):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6921): Notify AllClients services are ready: 0
I/art     (  986): Explicit concurrent mark sweep GC freed 81073(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.578ms total 185.688ms
,I/ActivityManager(  986): Killing 5873:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  986): failed to open /acct/uid_10106/pid_5873/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6921): Internal service binding...
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6980): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6980): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6980): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6980): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6980): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6980):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6980):   adb logcat -s GAv4
,W/GAv4    ( 6980): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6980): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6980): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6980): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6980): Time to load native libraries: 2 ms (timestamps 54-56)
,I/LibraryLoader( 6980): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6980): Binding Chromium to main looper Looper (main, tid 1) {e97a982}
I/LibraryLoader( 6980): Expected native library version number "",actual native library version number ""
I/chromium( 6980): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6980): Initializing chromium process, singleProcess=true
,W/art     ( 6980): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6980): ApplicationContext is null in ApplicationStatus
W/chromium( 6980): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6980): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6980): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6980): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6980): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6980): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6980): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6980): Remote Branch: 
I/Adreno-EGL( 6980): Local Patches: 
I/Adreno-EGL( 6980): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb38049a0, uid 10079
,W/AudioManagerAndroid( 6980): Requires BLUETOOTH permission
I/NSApplication( 6980): Starting up...
,I/ActivityManager(  986): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7050 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  986): Killing 6728:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  986): failed to open /acct/uid_10081/pid_6728/cgroup.procs: No such file or directory
,I/ActivityManager(  986): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7069 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  986): Killing 6780:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10021/pid_6780/cgroup.procs: No such file or directory
,W/ResourcesManager( 7069): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  986): Killing 6816:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_1000/pid_6816/cgroup.procs: No such file or directory
,I/ActivityManager(  986): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7093 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7093): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7093): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7093): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7093): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AlarmManager(  986): RTC_WAKEUP set : Alarm{e907af4 type 0 when 1453132533384 com.google.android.gms} when 1453132533384
,V/AlarmManager(  986): RTC_WAKEUP set : Alarm{2d7d4c92 type 0 when 1453132533528 com.google.android.googlequicksearchbox} when 1453132533528
V/JNIHelp ( 7093): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AlarmManager(  986): ELAPSED_WAKEUP set : Alarm{169a4663 type 2 when 111552 com.google.android.gms} when 111552
W/ActivityThread( 7093): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7093): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3083ecf5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7093): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7093): GMSCore installation verified
I/ConfigStore( 7093): Config Database version: 1
,I/MediaRouter( 7093): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7093): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7093): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7093): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  986): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7125 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7093): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7093): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  986): Killing 6840:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10011/pid_6840/cgroup.procs: No such file or directory
,W/ResourcesManager( 7125): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7125): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7125): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 7093): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7125): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7125): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7125): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  986): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7157 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7125): JNI_OnLoad()
I/HubEmail( 7125): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7125): registerNatives()
I/HubEmail( 7125): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7125): registerNativeMethods()
I/HubEmail( 7125): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7125): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  986): Killing 6864:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10038/pid_6864/cgroup.procs: No such file or directory
W/Settings( 7125): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  986): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7175 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  986): RTC_WAKEUP set : Alarm{31ca34ab type 0 when 1453132534616 com.android.vending} when 1453132534616
,D/LGDMClient( 7157): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7157): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 30.158ms
,W/ContextImpl( 7157): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 22.894ms
W/ContextImpl( 7157): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 372us total 22.575ms
,D/LGDMClient( 7157): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7157): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7157): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7157): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  986): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7202 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7157): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7157): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7157): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7157): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7157): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7157): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  986): Killing 6895:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10051/pid_6895/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7202): onCreate
,W/AppUp4:DB( 7202):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7202):  setFingerPrint start
,I/AppUp4:DB( 7202):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7202):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7202):  SDK version = 0
I/AppUp4:DB( 7202):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7202): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7202): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7202): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7202): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7202): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7202): onReceive
I/AppUp4:CustModeStarterReceiver( 7202): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7202): Context : android.app.ReceiverRestrictedContext@2ae81b09
D/AppUp4:CustFacade( 7202): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7202): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7202): begin check event
,I/AppUp4:CustModeStarterReceiver( 7202): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7202): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7202): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7202): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7202): handleAsyncCustNotification do not startCustService
D/Finsky  ( 7175): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/LgeMiscReceiver( 3217): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3217): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3217): networkInfo.isConnected() = false
,I/ActivityManager(  986): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7234 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7234): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7234): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7234): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  986): Killing 6921:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  986): failed to open /acct/uid_10089/pid_6921/cgroup.procs: No such file or directory
,V/DownloadManager( 3262): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3262): DownloadService onCreate
I/NotificationManager( 3262): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3262): in removeSpuriousFiles
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@142ca3ff on behalf of 3262
,I/DownloadManager( 3262): in trimDatabase
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@733b5cc on behalf of 3262
D/PhoneMonitor( 7234): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7234): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 7234): [parse] Load xml
V/TelephonyAutoProfiling( 7234): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7234): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7234): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  986): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7264 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3262): DownloadService onStartCommand
,V/DownloadManager( 3262): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4382): Checkin interval check for package: unspecified last checkin: 1453132503457 min interval config: 0 actual interval: 31884
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@3cb1811b on behalf of 3262
,I/CheckinService( 4382): Checking schedule, now: 1453132535375 next: 1453132533384
,I/CheckinService( 4382): active receiver: enabled
D/Finsky  ( 7175): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/CheckinService( 4382): Preparing to send checkin request
I/EventLogService( 4382): Accumulating logs since 1453132494075
W/Settings( 7175): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7175): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7175): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  986): Process com.google.android.apps.magazines (pid 6980) has died
,D/WeatherAncestor( 2806): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:35
V/DownloadManager( 3262): DownloadService onDestroy
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/UpdateThreadPoolManager( 2806): 2 : This is isUpdating : false
D/WeatherAncestor( 2806): connectivity changed - connection : true
D/Weather_cast( 2806): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2806): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:35
D/WeatherService( 2806): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@296a4891 on behalf of 7175
W/ActivityManager(  986): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2806): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2806): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2806): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  986): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7299 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 4382): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4382): Failed to find provider info for com.google.android.wearable.settings
,D/Finsky  ( 7175): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7175): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7175): Skipping gmscore version check
,D/Finsky  ( 7175): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7175): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/art     (  986): Explicit concurrent mark sweep GC freed 22695(1162KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.436ms total 163.357ms
,D/Finsky  ( 7175): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7175): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  986): Killing 7050:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  986): failed to open /acct/uid_10048/pid_7050/cgroup.procs: No such file or directory
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7299): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7299): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7299): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7299): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7299):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7299):   adb logcat -s GAv4
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7299): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7299): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7299): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7299): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  986): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7328 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7328): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7328): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7328): VM with version 2.1.0 has multidex support
I/MultiDex( 7328): install
I/MultiDex( 7328): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7328): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7328): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7328): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ab9a7d2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7328): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7328): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7328): com.google.android.gms: cancel(39789) by com.google.android.gms
I/WebViewFactory( 7299): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7299): Time to load native libraries: 2 ms (timestamps 4207-4209)
,I/LibraryLoader( 7299): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7299): Binding Chromium to main looper Looper (main, tid 1) {e97a982}
I/LibraryLoader( 7299): Expected native library version number "",actual native library version number ""
I/chromium( 7299): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7299): Initializing chromium process, singleProcess=true
,W/art     ( 7299): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7299): ApplicationContext is null in ApplicationStatus
W/chromium( 7299): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/art     ( 7328): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7328): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/libEGL  ( 7299): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7299): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7299): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7299): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7299): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7299): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7299): Remote Branch: 
I/Adreno-EGL( 7299): Local Patches: 
I/Adreno-EGL( 7299): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb4027040, uid 10079
W/AudioManagerAndroid( 7299): Requires BLUETOOTH permission
,I/NSApplication( 7299): Starting up...
I/ActivityManager(  986): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7390 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  986): Killing 7069:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/NativeLibraryUtils( 7328): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  986): failed to open /acct/uid_10086/pid_7069/cgroup.procs: No such file or directory
,I/ActivityManager(  986): Process com.google.android.music:main (pid 7093) has died
D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): CdmEngine::OpenSession
I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 114508980638; DSPS: 3850513; Offset : -3002281310
W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  281): L1 library not specified. Falling Back to L3
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,I/ActivityManager(  986): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7413 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  281): PrepareKeyRequest: nonce=3246076491
,W/ResourcesManager( 7413): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 7328): CheckpointMarkThreadRoots callback created = 0xb042d930
,I/art     ( 7328): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,I/ActivityManager(  986): Killing 7125:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10021/pid_7125/cgroup.procs: No such file or directory
,I/dex2oat ( 7437): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  986): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7440 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dex2oat ( 7437): dex2oat took 111.930ms (threads: 4)
,I/Adreno-EGL( 7328): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7328): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7328): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7328): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7328): Remote Branch: 
I/Adreno-EGL( 7328): Local Patches: 
I/Adreno-EGL( 7328): Reconstruct Branch: 
,I/MusicStore( 7440): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Adreno-EGL( 7328): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7328): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7328): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7328): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7328): Remote Branch: 
I/Adreno-EGL( 7328): Local Patches: 
I/Adreno-EGL( 7328): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7440): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7440): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7440): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/WVCdm   (  281): CdmEngine::OpenSession
,W/ActivityThread( 7440): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7440): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3083ecf5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7440): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7440): GMSCore installation verified
I/ConfigStore( 7440): Config Database version: 1
,I/art     ( 6384): Explicit concurrent mark sweep GC freed 2020(87KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 376us total 32.525ms
,I/MediaRouter( 7440): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7440): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7440): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7440): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  986): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7476 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7440): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7440): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  986): Killing 7157:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7476): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7476): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  986): failed to open /acct/uid_1000/pid_7157/cgroup.procs: No such file or directory
,I/NotificationManager( 7440): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7476): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7476): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7476): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  986): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7503 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7476): JNI_OnLoad()
I/HubEmail( 7476): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7476): registerNatives()
I/HubEmail( 7476): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7476): registerNativeMethods()
I/HubEmail( 7476): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7476): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  986): Killing 7202:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  986): failed to open /acct/uid_10011/pid_7202/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings( 7476): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7503): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7503): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7503): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7503): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 7503): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7503): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7503): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7503): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  986): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7527 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7503): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  311): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 294us total 21.406ms
,E/LGDMClient( 7503): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7503): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7503): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7503): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/art     (  311): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.340ms
D/LGDMClient( 7503): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  986): Killing 7234:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.902ms
,W/libprocessgroup(  986): failed to open /acct/uid_10038/pid_7234/cgroup.procs: No such file or directory
I/WVCdm   (  281): CdmEngine::CloseSession
,I/AppUp4:AppBoxCP( 7527): onCreate
W/AppUp4:DB( 7527):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7527):  setFingerPrint start
I/AppUp4:DB( 7527):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7527):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7527):  SDK version = 0
,I/AppUp4:DB( 7527):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7527): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7527): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7527): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7527): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7527): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7527): onReceive
I/AppUp4:CustModeStarterReceiver( 7527): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7527): Context : android.app.ReceiverRestrictedContext@2ae81b09
D/AppUp4:CustFacade( 7527): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7527): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7527): begin check event
I/AppUp4:CustModeStarterReceiver( 7527): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7527): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7527): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7527): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7527): handleAsyncCustNotification do not startCustService
I/ActivityManager(  986): Killing 7264:com.lge.drmservice/u0a51 (adj 15): empty #11
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=38589723
W/libprocessgroup(  986): failed to open /acct/uid_10051/pid_7264/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3217): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3217): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3217): networkInfo.isConnected() = true
,D/PhoneState( 3217): setPdpRejectCasuse : false
I/ActivityManager(  986): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7553 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7553): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7553): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7553): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  986): Killing 6934:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7553): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7553): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7553): [parse] Load xml
,V/TelephonyAutoProfiling( 7553): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7553): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7553): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  986): failed to open /acct/uid_10061/pid_6934/cgroup.procs: No such file or directory
,V/DownloadManager( 3262): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3262): DownloadService onCreate
I/NotificationManager( 3262): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3262): in removeSpuriousFiles
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@358343f6 on behalf of 3262
I/DownloadManager( 3262): in trimDatabase
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@2b40f264 on behalf of 3262
,I/ActivityManager(  986): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7578 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3262): DownloadService onStartCommand
V/DownloadManager( 3262): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4382): Checkin interval check for package: unspecified last checkin: 1453132503457 min interval config: 0 actual interval: 35783
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@e97a982 on behalf of 3262
,V/DownloadManager( 3262): DownloadService onDestroy
,I/art     (  986): Explicit concurrent mark sweep GC freed 15234(720KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.421ms total 158.754ms
,I/ActivityManager(  986): Killing 7175:com.android.vending/u0a36 (adj 15): empty #11
,I/MusicWidget( 2726): mDelayedStopHandler : unbind
,W/libprocessgroup(  986): failed to open /acct/uid_10036/pid_7175/cgroup.procs: No such file or directory
D/WeatherAncestor( 2806): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:39
,D/UpdateThreadPoolManager( 2806): 2 : This is isUpdating : false
D/WeatherAncestor( 2806): connectivity changed - connection : true
D/Weather_cast( 2806): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2806): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:55:39
D/WeatherService( 2806): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/MusicBrowser( 2111): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/ActivityManager(  986): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7595 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  986): getTasks: caller 10074 does not hold GET_TASKS; limiting output
I/MusicBrowser( 2111): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2111): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/Weather.Utils( 2806): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2806): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2806): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/MusicBrowser( 2111): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2111): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2111): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2111): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  986):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@77739becom.lge.music.MediaPlaybackService$6@284faa1f
,D/MusicBrowser( 2111): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@156e5ec5
,I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2111): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2111): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
W/ResourcesManager( 7595): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
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
,V/AudioFlinger(  281): releasing 19 from 2111 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2111): disconnect
D/MusicBrowser( 2111): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2111): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2111): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2111): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2111): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2111): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2111): [SmartShareManagerClient] unregisterListener: 582685036
W/SmartShareClient( 2111): [SmartShareManagerClient] unregisterListener invalid listener: 582685036
I/SmartShareClient( 2111): [SmartShareManagerClient] terminate service: 2111/MediaPlaybackService/645447891
E/HomeCloudIF( 2111): unregiterHomeCloudBroadcast(), Illegal argument.
,I/SmartShareClient( 2111): [SmartShareManagerClient] unbindService context:android.app.Application@396933ca
V/CloudHub( 2111): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2111): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2111): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2111): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2111): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  986): Killing 7299:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/CloudHub( 2111): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
E/libprocessgroup(  986): failed to kill 1 processes for processgroup 7299
,I/Babel_SMS( 7595): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7595): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7595): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7595): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7595): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7595): MmsConfig.loadFromResources
E/Babel_SMS( 7595): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7595): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7595): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7595): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7595): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7595): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7595): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7595): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7595): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7595): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7595): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7595): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7595): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7595): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7595): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7595): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7595): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7595): found sensor: Motion Accel, handle=46
W/Settings( 7595): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7595): startup - clean
I/art     ( 7595): CheckpointMarkThreadRoots callback created = 0xb042d800
I/art     ( 7595): CheckpointMarkThreadRoots callback created = 0xb042d7e0
,I/Babel   ( 7595): deleted: false for 0
I/ActivityManager(  986): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7627 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7595): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7595): Unsupported mime audio/adpcm
W/AudioCapabilities( 7595): Unsupported mime audio/g726
W/AudioCapabilities( 7595): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7595): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7595): Unsupported mime video/mjpg
W/VideoCapabilities( 7595): Unsupported mime video/theora
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/AudioCapabilities( 7595): Unsupported mime audio/evrc
,W/AudioCapabilities( 7595): Unsupported mime audio/qcelp
W/VideoCapabilities( 7595): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7595): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7595): Unsupported mime audio/qcelp
W/AudioCapabilities( 7595): Unsupported mime audio/evrc
,W/VideoCapabilities( 7595): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7595): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7595): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7595): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7595): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7595): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7595): onServiceConnected
W/Babel   ( 7595): Attempted to change video mute state without an active call.
D/libc-netbsd( 7595): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7595): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager( 7595): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7595): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7595): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 7595): propertyValue:false
I/GAv4    ( 7627): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7627):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7627):   adb logcat -s GAv4
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7627): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7627): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7627): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7627): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7627): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7595): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  986): Killing 7390:com.android.chrome/u0a48 (adj 15): empty #11
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,W/GAv4    ( 7627): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7627): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  986): failed to open /acct/uid_10048/pid_7390/cgroup.procs: No such file or directory
,I/WVCdm   (  281): CdmEngine::CloseSession
,I/WVCdm   (  281): L3 Terminate.
I/WebViewFactory( 7627): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7627): Time to load native libraries: 1 ms (timestamps 8968-8969)
I/LibraryLoader( 7627): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7627): Binding Chromium to main looper Looper (main, tid 1) {e97a982}
I/LibraryLoader( 7627): Expected native library version number "",actual native library version number ""
I/chromium( 7627): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7627): Initializing chromium process, singleProcess=true
,W/art     ( 7627): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7627): ApplicationContext is null in ApplicationStatus
W/chromium( 7627): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7627): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7627): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7627): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7627): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7627): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7627): Remote Branch: 
I/Adreno-EGL( 7627): Local Patches: 
I/Adreno-EGL( 7627): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb4027300, uid 10079
,W/AudioManagerAndroid( 7627): Requires BLUETOOTH permission
I/NSApplication( 7627): Starting up...
,I/ActivityManager(  986): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7691 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  986): Killing 7413:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  986): failed to open /acct/uid_10086/pid_7413/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7328): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7328): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7328): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7328): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7328): Remote Branch: 
I/Adreno-EGL( 7328): Local Patches: 
I/Adreno-EGL( 7328): Reconstruct Branch: 
,I/ActivityManager(  986): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7713 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  986): Killing 7440:com.google.android.music:main/u0a81 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  986): failed to open /acct/uid_10081/pid_7440/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4382): Classify the device as Phone.
,W/ResourcesManager( 7713): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/libc-netbsd( 4382): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4382): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4382): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4382): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 4382): propertyValue:false
D/libc-netbsd( 4382): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4382): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  986): Killing 7476:com.lge.email/u0a21 (adj 15): empty #11
,D/libc-netbsd( 4382): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4382): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4382): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4382): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  986): failed to open /acct/uid_10021/pid_7476/cgroup.procs: No such file or directory
,I/CheckinTask( 4382): Sending checkin request (9755 bytes)
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 4382): Checkin interval check for package: unspecified last checkin: 1453132503457 min interval config: 0 actual interval: 38470
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,W/ContextImpl( 3711): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
D/LocationInitializer( 4382): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1734): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinRequestBuilder( 4382): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4382): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 4382): Classify the device as Phone.
,I/CheckinTask( 4382): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4382): Checking schedule, now: 1453132542370 next: 1453659791365
I/CheckinService( 4382): active receiver: disabled
,I/CheckinService( 4382): Checking schedule, now: 1453132542405 next: 1453659791365
,I/CheckinService( 4382): active receiver: disabled
D/CheckinService( 4382): Recording last checkin time for package unspecified as 1453132542416
,V/AlarmManager(  986): ELAPSED_WAKEUP set : Alarm{17c5e78e type 2 when 120332 com.google.android.gms} when 120332
V/SetupWizard( 7553): Connected to Gservices successfully
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1376): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  986): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1376): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1376): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/QCNEJ   ( 1843): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/AppUp4:CustModeStarterReceiver( 7527): onReceive
I/AppUp4:CustModeStarterReceiver( 7527): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7527): Context : android.app.ReceiverRestrictedContext@2ae81b09
,D/AppUp4:CustFacade( 7527): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7527): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7527): begin check event
,I/AppUp4:CustModeStarterReceiver( 7527): Event For Nothing, skip.
I/NotificationManager( 7595): com.google.android.talk: cancel(8) by com.google.android.talk
,D/administrator(  986): Handling package changes for user 0
W/ResourcesManager( 7595): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7595): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  986): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7799 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,V/JNIHelp ( 7595): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7799): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7799): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7799): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/NotificationService(  986): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  986): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  986): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/System  ( 7595): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7595): Installed default security provider GmsCore_OpenSSL
I/BackupManagerService(  986): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  986): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  986): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@37cac881
W/ResourcesManager(  986): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
I/AppConfig( 7799): Total System Memory = 906309632
,V/AudioFlinger(  281): 2111 died, releasing its sessions
,V/AudioFlinger(  281):  pid 1753 @ 0
V/AudioFlinger(  281):  pid 3217 @ 1
V/AudioFlinger(  281):  pid 3217 @ 2
,I/GalleryUtils( 7799): Application Heap = 96 MB
,I/AppConfig( 7799): App Tier : NOT_DEF
I/ActivityManager(  986): Process com.lge.music (pid 2111) has died
,D/SystemHelper( 7799): region [EU], country [EU], operator [OPEN], sub-operator []
W/ResourceType(  986): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  986): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7822 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7822): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7822): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7822): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7822): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7822): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  986): applying state to connected service
,I/ActivityManager(  986): Process com.google.android.apps.magazines (pid 7627) has died
,I/SystemConfig( 7822): BUILD Country: EU
,I/SystemConfig( 7822): BUILD Operator: OPEN
,I/ActivityManager(  986): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7846 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/SystemConfig( 7822): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7822): existFile = false
,I/SystemConfig( 7822): canReadFile = false
I/SystemConfig( 7822): systemFeature RCS result false
D/SystemConfig( 7822): refreshRcsSupport() :false
,I/art     (  986): Explicit concurrent mark sweep GC freed 26697(1362KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.137ms total 152.894ms
,I/LockScreenSettings( 7846): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7846): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7846): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7846): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7846): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7846): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  986): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7871 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7713): CheckpointMarkThreadRoots callback created = 0xb042d430
I/ActivityManager(  986): Killing 7503:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/art     ( 7713): CheckpointMarkThreadRoots callback created = 0xb042d420
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 136 ms] updated apps [took 135 ms] 
,I/ActivityManager(  986): Killing 7578:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  986): failed to open /acct/uid_1000/pid_7503/cgroup.procs: No such file or directory
,W/libprocessgroup(  986): failed to open /acct/uid_10051/pid_7578/cgroup.procs: No such file or directory
D/Finsky  ( 7871): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7871): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7871): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7871): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7871): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@144cd0d0 on behalf of 7871
D/Ads     ( 7871): Skipping gmscore version check
D/Finsky  ( 7871): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7871): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  986): Killing 7691:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10048/pid_7691/cgroup.procs: No such file or directory
,D/Finsky  ( 7871): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4382): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4382): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7871): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4382): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 4382): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4382): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/charger_monitor(  489): init target 500000
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  986): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
D/charger_monitor(  489): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  986): Killing 7553:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  986): failed to open /acct/uid_10038/pid_7553/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 134509839641; DSPS: 4505901; Offset : -3002277295
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  986): acquireWakeLockInternal: lock=517521424, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=986
,D/WeatherService( 2806): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:56:0
,D/WeatherService( 2806): 2 : TimeTick Intent And Screen On
D/WeatherService( 2806): 2 : SDK version : 21
W/ActivityManager(  986): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2806): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2806): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2806): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2806): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2806): 2 : This is isUpdating : false
D/WeatherService( 2806): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2806): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2806): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2806): 2 : Fixed theme : optimus
,D/WeatherReflect( 2806): 2 : Map key string is -2
,D/lim     ( 2806): 2 : time = 16:56
,I/WeatherReflect( 2806): Model Name : LG-D722
D/WeatherTheme( 2806): 2 : Different view - status_min_formatted : 55 != 56
D/WeatherTheme( 2806): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2806): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2806): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2806): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/Weather4x2_optimus( 2806): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2806): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2806): forecast size is 0
D/Theme   ( 2806): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2806): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2806): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2806): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2806): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2806): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2806): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2806): url is : null
D/Theme   ( 2806): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2806): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2806): 2 : update view, appWidgetId: 2
D/WeatherService( 2806): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:56:0
,D/PowerManagerServiceEx(  986): releaseWakeLockInternal: lock=517521424 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  986): ELAPSED_WAKEUP set : Alarm{92ed709 type 2 when 140944 com.google.android.gms} when 140944
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 33048(2MB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 13MB/22MB, paused 1.545ms total 105.729ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1734): Vacuum at: now=1453132563363 tag=VacuumService
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/PhenotypeConfigurator( 1734): Server returned 404
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  986): ALS enabled for SRE
,D/PowerManagerServiceEx(  986): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28179 ms ago)
D/qdlights(  986): set_light_backlight: 252
,D/qdlights(  986): set_light_backlight: 248
D/qdlights(  986): set_light_backlight: 245
,D/qdlights(  986): set_light_backlight: 242
,D/qdlights(  986): set_light_backlight: 238
,D/qdlights(  986): set_light_backlight: 235
,D/qdlights(  986): set_light_backlight: 232
,D/qdlights(  986): set_light_backlight: 228
,D/qdlights(  986): set_light_backlight: 225
,D/qdlights(  986): set_light_backlight: 222
,D/qdlights(  986): set_light_backlight: 218
,D/qdlights(  986): set_light_backlight: 215
,D/qdlights(  986): set_light_backlight: 212
,D/qdlights(  986): set_light_backlight: 208
,D/qdlights(  986): set_light_backlight: 205
,D/qdlights(  986): set_light_backlight: 202
,D/qdlights(  986): set_light_backlight: 198
,D/qdlights(  986): set_light_backlight: 195
,D/qdlights(  986): set_light_backlight: 192
,D/qdlights(  986): set_light_backlight: 188
,D/qdlights(  986): set_light_backlight: 185
,D/qdlights(  986): set_light_backlight: 182
,D/qdlights(  986): set_light_backlight: 178
,D/qdlights(  986): set_light_backlight: 175
,D/qdlights(  986): set_light_backlight: 172
,D/qdlights(  986): set_light_backlight: 168
,D/qdlights(  986): set_light_backlight: 165
,D/qdlights(  986): set_light_backlight: 162
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/qdlights(  986): set_light_backlight: 158
D/qdlights(  986): set_light_backlight: 155
,D/qdlights(  986): set_light_backlight: 152
,D/qdlights(  986): set_light_backlight: 148
,D/qdlights(  986): set_light_backlight: 145
,D/qdlights(  986): set_light_backlight: 142
,D/qdlights(  986): set_light_backlight: 138
,D/qdlights(  986): set_light_backlight: 135
,D/qdlights(  986): set_light_backlight: 132
,D/qdlights(  986): set_light_backlight: 128
,D/qdlights(  986): set_light_backlight: 125
,D/qdlights(  986): set_light_backlight: 122
,D/qdlights(  986): set_light_backlight: 118
,D/qdlights(  986): set_light_backlight: 115
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  986): set_light_backlight: 112
,D/qdlights(  986): set_light_backlight: 108
,D/qdlights(  986): set_light_backlight: 105
,D/qdlights(  986): set_light_backlight: 102
,D/qdlights(  986): set_light_backlight: 98
,D/qdlights(  986): set_light_backlight: 95
,D/qdlights(  986): set_light_backlight: 92
,D/qdlights(  986): set_light_backlight: 88
,D/qdlights(  986): set_light_backlight: 85
,D/qdlights(  986): set_light_backlight: 82
,D/qdlights(  986): set_light_backlight: 78
,D/qdlights(  986): set_light_backlight: 75
,D/qdlights(  986): set_light_backlight: 72
,D/qdlights(  986): set_light_backlight: 68
,D/qdlights(  986): set_light_backlight: 65
,D/qdlights(  986): set_light_backlight: 62
,D/qdlights(  986): set_light_backlight: 58
,D/qdlights(  986): set_light_backlight: 55
,D/qdlights(  986): set_light_backlight: 52
,D/qdlights(  986): set_light_backlight: 48
,D/qdlights(  986): set_light_backlight: 45
,D/qdlights(  986): set_light_backlight: 42
,D/qdlights(  986): set_light_backlight: 38
,D/qdlights(  986): set_light_backlight: 35
,D/qdlights(  986): set_light_backlight: 32
,D/qdlights(  986): set_light_backlight: 28
,D/qdlights(  986): set_light_backlight: 25
,D/qdlights(  986): set_light_backlight: 22
,D/qdlights(  986): set_light_backlight: 18
,D/qdlights(  986): set_light_backlight: 15
,D/qdlights(  986): set_light_backlight: 12
,D/qdlights(  986): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 154510645311; DSPS: 5161287; Offset : -3002264821
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  986): ALS enabled for SRE
D/PowerManagerServiceEx(  986): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35170 ms ago)
I/PowerManagerService(  986): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  986): ALS enabled for SRE
D/PowerManagerServiceEx(  986): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35185 ms ago)
,W/ContextImpl(  986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  986): Sleeping (uid 1000)...
,D/LPWGController(  986): [updateScreenState] screen on = false
D/LPWGController(  986): disable proximity sensor
,D/LPWGController(  986): enable proximity sensor
I/SensorManager(  986): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1960fd6c] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  986): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  986): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  986): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  986): activate: handle is 48, enable
,V/sensors_hal_Ctx(  986): activate sensors is 1400000000000
D/sensors_hal_Thresh(  986): enable: handle=48
I/sensors_hal_SAM(  986): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  986): waitForResponse: timeout=1000
V/sensors_hal_SAM(  986): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  986): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  986): enable: Received response: 0
D/PowerManagerServiceEx(  986): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35250 ms ago)
I/Adreno-EGL(  986): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  986): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  986): Build Date: 03/02/15 Mon
I/Adreno-EGL(  986): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  986): Remote Branch: 
I/Adreno-EGL(  986): Local Patches: 
I/Adreno-EGL(  986): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (980 us)
,I/Sensors (  440): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  986): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  986): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  986): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  986): processInd: handle 48, count=1
V/sensors_hal_Thresh(  986): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  986): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  986): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  986): poll: count: 256
I/sensors_hal_Ctx(  986): poll: released wakelock sensor_ind
D/sensors_hal_Util(  986): waitForResponse: timeout=0
D/LPWGController(  986): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  986): current mode = 1  value = 1 1
I/LPWGController(  986): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  986): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  986): set_light_backlight: 0
,I/SensorManager(  986): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  986): activate: handle is 46, disable
V/sensors_hal_Ctx(  986): activate sensors is 1000000000000
D/sensors_hal_LP2(  986): enable: handle=46
D/sensors_hal_LP2(  986): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  986): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  986): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  986): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  986): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  986): Display changed displayId=0
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/DSDPConnection( 1753): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
D/SurfaceControl(  986): Excessive delay in setPowerMode(): 189ms
I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  986): Got set_interactive hint
,D/KeyguardViewMediator( 1376): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1337): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1376): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1337): notifyScreenOffLocked
D/SmartCoverViewMediator( 1337): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1376): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1376): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1376): unregisterProximitySensor
,D/StatusBarWindowView( 1376): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  986): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WifiServerServiceExt(  986): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 986
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
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
,D/GpsLocationProvider(  986): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1843): |CORE| sendScreenState: state:true
I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1806): RESTART MSG
,D/SplitWindow(  986): check instance of lgWin Window{106ea53b u0 SearchPanel}
,I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1806): lockStatus = 0
,D/LNfcService( 1789): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1789): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1789): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
D/InputDispatcher(  986): Window went away: Window{bba5926 u0 SearchPanel}
,I/[SystemUI]Clock( 1376): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1376): time changed, timezoneChanged : false
,D/Ulp_jni (  986): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): ACTION_SCREEN_ON
,D/WeatherService( 2806): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:56:18
D/WeatherService( 2806): 2 : ACTION screen on
D/WeatherService( 2806): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2806): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2806): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:56:18
,D/AppCleanupService( 4202): android.intent.action.SCREEN_ON
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 986
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
,V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
D/WifiController(  986): CMD_SCREEN_OFF 
D/WifiController(  986): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  986): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1843): |CORE| sendScreenState: state:false
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1806): clear
I/LEDService( 1806): updateLightsLocked : turn on led
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
,I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1789): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1789): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
I/Sensors (  440): sns_pwr.c(301):releasing wakelock
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  986): ACTION_SCREEN_OFF
,D/WeatherService( 2806): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:56:19
D/WeatherService( 2806): 2 : ACTION screen off
D/WeatherService( 2806): 2 : TimeTick Receiver Unregister
D/WeatherService( 2806): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:56:19
D/AppCleanupService( 4202): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4202): AppUsageStatsSaveTask
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
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1376): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  986): ELAPSED_WAKEUP set : Alarm{3c168458 type 2 when 161100 com.android.systemui} when 161100
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1376): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1376): doKeyguard: not showing because lockscreen is off
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 174511435667; DSPS: 5816673; Offset : -3002270084
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  986): ELAPSED_WAKEUP set : Alarm{25f959b1 type 2 when 186996 com.google.android.gms} when 186996
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  986): battery changed pluggedType: 2
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  986): ELAPSED_WAKEUP set : Alarm{34654e96 type 2 when 191340 android} when 191340
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 194512105868; DSPS: 6472055; Offset : -3002269420
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 214512781121; DSPS: 7127437; Offset : -3002265475
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  986): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
,W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  986): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 234513482259; DSPS: 7782820; Offset : -3002266424
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  986): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 254514159804; DSPS: 8438202; Offset : -3002260083
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 274514834900; DSPS: 9093584; Offset : -3002256401
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  986): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  986): battery changed pluggedType: 2
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 294515596455; DSPS: 9748969; Offset : -3002257602
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/HeadsetStateMachine( 2003): Disconnected process message: 10, size: 0
W/Settings(  986): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  986): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  986): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  986): tsOffsetIs: Apps: 314516457176; DSPS: 10404357; Offset : -3002251347
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6432): --= Surplus to requirements =--
I/jxcore-log( 6432): 
I/jxcore-log( 6432): ****TEST TOOK:  ms ****
I/jxcore-log( 6432): 
I/jxcore-log( 6432): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6432): 
,D/AndroidRuntime( 8096): 
D/AndroidRuntime( 8096): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8096): CheckJNI is OFF
,D/AndroidRuntime( 8096): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  986): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  986): Killing 6432:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  986): WIN DEATH: Window{e4e85ec u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  986): Focus left window: Window{e4e85ec u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  986): Window went away: Window{e4e85ec u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  986): Skipping PackageSetting{2ced1aa2 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  986):   Force finishing activity ActivityRecord{1dea1232 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  986): Display changed displayId=0
D/DSDPConnection( 1753): Display #0 changed.
,W/ActivityManager(  986): Spurious death for ProcessRecord{b185a17 6432:com.test.thalitest/u0a316}, curProc for 6432: null
I/ActivityManager(  986): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  986):   Force finishing activity ActivityRecord{1dea1232 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  986): Duplicate finish request for ActivityRecord{1dea1232 u0 com.test.thalitest/.MainActivity t222 f}
,I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
,D/KeyguardModel( 1376): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  986): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1843): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
,I/art     ( 1940): Explicit concurrent mark sweep GC freed 10196(674KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.649ms total 117.043ms
W/System.err( 3711): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3711): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3711): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3711): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3711): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3711): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3711): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3711): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3711): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3711): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3711): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3711): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ActivityManager(  986): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8128 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     ( 4382): Explicit concurrent mark sweep GC freed 259(9KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 15.365ms total 136.460ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 25.073ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 24.487ms
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,D/KeyguardModel( 1376): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1376): createShortcutInfo...
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=2ms
D/KeyguardModel( 1376): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1376): createShortcutInfo...
I/[SystemUI]QSlideListController( 1376): onReceive = android.intent.action.PACKAGE_REMOVED
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 426us total 26.261ms
,W/PackageManager( 1376): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1376): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1376): createShortcutInfo...
I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1376): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1376): createShortcutInfo...
,W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1376): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1376): createShortcutInfo...
,I/art     (  986): Explicit concurrent mark sweep GC freed 54320(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 4.528ms total 230.325ms
I/art     (  986): WaitForGcToComplete blocked for 198.747ms for cause Explicit
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1376): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1376): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1376): handleShortcutListChanged...
I/SystemUI[Framework](  986): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  986): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  986): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx(  986): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  986): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7c05c5a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  986): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  986): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  986): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  986): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  986): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  986): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7c05c5a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  986): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  986): Focus entered window: Window{1e2e6554 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1376): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1376): createShortcutInfo...
,D/KeyguardModel( 1376): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1376): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,D/KeyguardModel( 1376): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1376): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1376): createShortcutInfo...
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1376): handleShortcutListChanged...
,I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 8128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8128): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8128): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/administrator(  986): Handling package changes for user 0
,I/LGEmail ( 8128): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8128): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/InputMethodManagerService(  986): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  986): Got RemoteException sending setActive(false) notification to pid 6432 uid 10316
,I/art     (  986): Explicit concurrent mark sweep GC freed 7717(443KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 5.025ms total 276.930ms
,I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  986): Timeline: Activity_windows_visible id: ActivityRecord{c056851 u0 com.lge.launcher2/.Launcher t221} time:334061
,W/IInputConnectionWrapper( 1879): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1612): Unable to connect to the editor to retrieve text... will retry later
I/PackageChangeReceiver( 8128): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AppUp4:PreloadHelper( 7527): added Exclude : com.test.thalitest
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1879): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 8096): Shutting down VM
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,I/ActivityManager(  986): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8155 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  986): Killing 7595:com.google.android.talk/u0a61 (adj 15): empty #11
I/NotificationService(  986): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  986): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  986): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/PhoneStatusBar( 1376): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
I/[SystemUI]NavigationThemeResource( 1376): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1376):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1376): , Keyguard show=false, IME shown=false, Panel expanded=false
W/libprocessgroup(  986): failed to open /acct/uid_10061/pid_7595/cgroup.procs: No such file or directory
D/TaskPersister(  986): removeObsoleteFile: deleting file=222_task.xml
I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  986): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/sensors_hal_Time(  986): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  986): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  986): tsOffsetIs: Apps: 334517105033; DSPS: 11059738; Offset : -3002244698
,W/ResourceType(  986): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8155): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8155): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8155): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8155): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8155): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 1879): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
,I/Timeline( 1879): Timeline: Activity_idle id: android.os.BinderProxy@1b5bd47e time:334648
I/art     ( 1879): Explicit concurrent mark sweep GC freed 27317(1486KB) AllocSpace objects, 17(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.363ms total 52.612ms
,E/SQLiteDatabase( 8155): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 8155): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8155): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8155): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8155): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8155): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 8155): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8155): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8155): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8155): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8155): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8155): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8155): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8155): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8155): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8155): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8155): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8155): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8155): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8155): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/AndroidRuntime( 8155): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8155): FATAL EXCEPTION: main
E/AndroidRuntime( 8155): Process: com.android.settings, PID: 8155
E/AndroidRuntime( 8155): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8155): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8155): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8155): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 8155): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8155): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8155): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8155): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8155): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8155): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8155): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8155): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8155): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8155): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8155): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8155): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8155): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8155): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 8155): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8155): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8155): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8155): 	... 11 more
I/Process ( 8155): Sending signal. PID: 8155 SIG: 9

```
